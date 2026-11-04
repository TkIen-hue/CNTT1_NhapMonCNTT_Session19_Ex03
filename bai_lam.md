# Bài 3 : Khắc phục sự cố rò rỉ thông tin đăng nhập
## Phần 1:
**Input:** Các Cookies và mật khẩu truy cập bị tin tặc đánh cắp thông qua việc người dùng vô tình truy cặp vào các trang giả mạo.

**Process:** 
- Xác định đó là dạng lỗi gì để lên phương án đối phó.

- Ngắt ngay kết nối mạng để mã độc không lây lan.
- Sau đó dùng thiết bị khác để cắt quyền truy cặp của tin tặc truy cặp tài khoản.
- Thực hiện thay đổi lại mật khẩu và loại bỏ mã độc.

**Output:** Tài khoản đã loại bỏ mã độc và có thể hoạt động bình thường.

## Phần 2:
### Cách "Đổi mật khẩu từ thiết bị khác" trên Github
- Bước 1: Đăng nhập vào tài khoản GitHub của bạn trên trình duyệt.
- Bước 2: Nhấn vào ảnh đại diện ở góc trên bên phải màn hình, chọn Settings.
- Bước 3: Ở thanh menu bên trái, tìm và chọn mục Password and authentication trong phần "Access".
- Bước 4: Tại ô Change password, bạn điền đầy đủ các thông tin:
- Old password: Mật khẩu cũ hiện tại.
- New password: Mật khẩu mới mong muốn.
- Confirm new password: Nhập lại mật khẩu mới để xác nhận.

- Bước 5: Nhấn nút Update password để lưu lại.

### Cách "Revoke Token" trên GitHub
- Bước 1: Vào Settings từ ảnh đại diện ở góc trên bên phải.
- Bước 2: Ở menu bên trái, chọn Sessions trong mục "Access".
- Bước 3: Bạn sẽ thấy danh sách các thiết bị, trình duyệt đang đăng nhập tại mục Web sessions hoặc GitHub Mobile sessions.

- Bước 4: Bấm See more ở phiên đăng nhập cần kiểm tra, sau đó bấm Revoke session để đăng xuất thiết bị đó.