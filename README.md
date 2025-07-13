# MINDX Car Rental Project

## Mô tả
Dự án website cho thuê xe với giao diện hiện đại và responsive, được phát triển bằng HTML, CSS và JavaScript thuần.

## Tính năng chính
- ✅ Giao diện responsive đẹp mắt
- ✅ Hệ thống đăng nhập/đăng xuất
- ✅ Tìm kiếm xe theo thương hiệu và loại xe
- ✅ Hiển thị danh sách xe cho thuê
- ✅ Quản lý xe cá nhân
- ✅ Form liên hệ và đăng ký nhận tin

## Cách sử dụng

### Đăng nhập
- **Username**: `admin`
- **Password**: `123456`

### Tìm kiếm xe
1. Chọn thương hiệu xe (Toyota, Porsche, Lamborghini, Ferrari, Maybach, Audi)
2. Chọn loại xe tương ứng
3. Nhập giá tiền (tùy chọn)
4. Nhấn "SEARCH NOW"

### Quản lý xe cá nhân
- Sau khi đăng nhập, click vào tên người dùng để mở dropdown menu
- Chọn "Xe cho thuê" để quản lý xe của bạn

## Fix các vấn đề thường gặp

### 1. Vấn đề Auto Login
**Mô tả**: Website tự động đăng nhập khi upload lên GitHub
**Nguyên nhân**: localStorage vẫn giữ dữ liệu từ lần đăng nhập trước
**Giải pháp**: 
- Đã thêm session timeout (24 giờ)
- Thêm nút "Clear Session" trong development mode
- Tự động clear session khi hết hạn

### 2. Vấn đề Dropdown Menu
**Mô tả**: Hiển thị hình ảnh thay vì dropdown menu
**Nguyên nhân**: CSS cho dropdown menu chưa đầy đủ
**Giải pháp**: 
- Đã thêm CSS đầy đủ cho dropdown menu
- Cải thiện responsive design
- Thêm animation và styling

### 3. Cách xóa session thủ công
Nếu gặp vấn đề với auto login, bạn có thể:

**Cách 1: Sử dụng Developer Tools**
1. Mở Developer Tools (F12)
2. Vào tab Console
3. Gõ: `localStorage.clear()`
4. Nhấn Enter
5. Refresh trang

**Cách 2: Sử dụng nút Clear Session**
- Nút này chỉ hiển thị khi chạy trên localhost
- Click vào nút đỏ "Clear Session" ở góc trên bên phải

## Cấu trúc thư mục
```
MINDX/
├── index.html          # Trang chủ
├── login.html          # Trang đăng nhập
├── listings.html       # Danh sách xe
├── car-detail.html     # Chi tiết xe
├── my-cars.html        # Quản lý xe cá nhân
├── add-car.html        # Thêm xe mới
├── payment.html        # Thanh toán
├── style.css           # CSS chính
├── images/             # Thư mục hình ảnh
└── README.md           # Hướng dẫn này
```

## Công nghệ sử dụng
- HTML5
- CSS3 (Flexbox, Grid, Animations)
- JavaScript (ES6+)
- Font Awesome Icons
- Google Fonts (Poppins)

## Responsive Design
- Desktop: 1200px+
- Tablet: 768px - 1199px
- Mobile: < 768px

## Browser Support
- Chrome (khuyến nghị)
- Firefox
- Safari
- Edge

## Lưu ý quan trọng
1. **Session Management**: Session sẽ tự động hết hạn sau 24 giờ
2. **Local Storage**: Dữ liệu được lưu trong localStorage của trình duyệt
3. **Demo Data**: Tất cả dữ liệu xe và người dùng đều là demo
4. **Images**: Đảm bảo tất cả hình ảnh trong thư mục `images/` đều có sẵn

## Hỗ trợ
Nếu gặp vấn đề, vui lòng:
1. Kiểm tra console trong Developer Tools
2. Clear localStorage và thử lại
3. Đảm bảo tất cả file đã được upload đầy đủ

---
**Developed by Thành Trung - MINDX Project** 