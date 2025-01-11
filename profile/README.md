# Website Quản Lý Dự Án

## Mô Tả Dự Án
Đây là một dự án phát triển phần mềm quản lý dự án, được thực hiện trong khuôn khổ môn học Lập Trình Hướng Đối Tượng (IT3103) tại Đại học Bách Khoa Hà Nội. Hệ thống được thiết kế nhằm tối ưu hóa quy trình làm việc, theo dõi tiến độ, phân công nhiệm vụ, và cung cấp các công cụ hỗ trợ giao tiếp, báo cáo thông minh cho các đội nhóm.

## Mục Tiêu Dự Án
- Xây dựng một phần mềm quản lý dự án hiện đại, dễ sử dụng, thân thiện với người dùng.
- Hỗ trợ các chức năng chính như: 
  - Quản lý người dùng và phân quyền.
  - Quản lý dự án, công việc và nhiệm vụ phụ (Task/SubTask).
  - Gửi tin nhắn nội bộ và bình luận.
  - Theo dõi tiến độ và phân tích dữ liệu dự án.
  - Quản lý giao dịch thanh toán.

## Thành Viên Nhóm

| STT | Họ và Tên           | MSSV      | Vai Trò             |
|-----|---------------------|-----------|---------------------|
| 1   | Nguyễn Bùi Tuấn Linh | 20225732  | Backend, Frontend   |
| 2   | Nguyễn Bùi Việt Linh | 20225733  | Backend, Báo cáo    |
| 3   | Nguyễn Khánh Toàn    | 20225936  | Database, Báo cáo   |
| 4   | Hồ Tuấn Huy          | 20225856  | Frontend            |
| 5   | Nguyễn Quỳnh Anh     | 20225785  | Frontend, Slide     |
| 6   | Phạm Quốc Cường      | 20225604  | Backend             |

## Công Nghệ Sử Dụng
- **Ngôn ngữ lập trình:** Java, Vue.js
- **Framework:** Spring Boot
- **Cơ sở dữ liệu:** MySQL
- **API:** RESTful API
- **Realtime Communication:** WebSocket

## Chức Năng Chính
### 1. Quản Lý Người Dùng
- Đăng ký, đăng nhập.
- Quản lý thông tin cá nhân.
- Phân quyền người dùng dựa trên vai trò.

### 2. Quản Lý Dự Án
- Tạo, chỉnh sửa, xóa dự án.
- Theo dõi danh sách dự án theo trạng thái.
- Thêm thành viên và quản lý các tác vụ trong dự án.

### 3. Quản Lý Task/SubTask
- Tạo và quản lý các công việc trong dự án.
- Gán công việc cho thành viên.
- Theo dõi tiến độ, trạng thái công việc.

### 4. Giao Tiếp và Báo Cáo
- Thêm bình luận, trao đổi trong từng Task.
- Gửi và nhận tin nhắn nội bộ theo thời gian thực.
- Phân tích dữ liệu và xuất báo cáo tiến độ.

### 5. Quản Lý Thanh Toán
- Đăng ký gói dịch vụ để sử dụng hệ thống.
- Ghi nhận và xử lý giao dịch thanh toán.

## Kiến Trúc Hệ Thống
Hệ thống được xây dựng theo mô hình 3-Layer:
- **Presentation Layer:** Giao diện người dùng với Vue.js.
- **Service Layer:** Xử lý logic và cung cấp API với Spring Boot.
- **Data Layer:** Quản lý cơ sở dữ liệu với MySQL.

## Cách Chạy Dự Án
1. Clone repository:
   ```bash
   git clone <repository-url>
   ```
2. Khởi chạy Backend:
   ```bash
   cd backend
   mvn spring-boot:run
   ```
3. Khởi chạy Frontend:
   ```bash
   cd frontend
   npm install
   npm run serve
   ```
4. Truy cập ứng dụng tại:
   ```
   http://localhost:8080
   ```

## Đóng Góp
Mọi đóng góp đều được chào đón! Vui lòng gửi pull request hoặc mở issue để báo lỗi.

## Giấy Phép
Dự án được cấp phép theo giấy phép MIT.

