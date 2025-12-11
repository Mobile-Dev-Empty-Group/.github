# 🚀 DineLex App - Ứng dụng Quản lý Deadline

> [cite_start]**Slogan:** "Deadline không đuổi bạn mà bạn đuổi deadline" [cite: 7]

## 📖 Tổng quan dự án (Project Overview)

[cite_start]**DineLex App** là ứng dụng quản lý deadline được thiết kế đặc biệt dành cho sinh viên, giúp quản lý các công việc, bài tập và dự án một cách khoa học[cite: 5, 9].

[cite_start]Vấn đề lớn nhất của sinh viên hiện nay là không biết cách quản lý deadline hiệu quả, thường xuyên bỏ lỡ bài tập hoặc làm việc trễ hạn[cite: 55]. [cite_start]DineLex giải quyết vấn đề này bằng cách tập trung vào **nhắc nhở thông minh** dựa trên độ ưu tiên, giúp giảm thiểu tình trạng quên hạn[cite: 10, 55].

### [cite_start]Mục tiêu chính[cite: 11, 12, 13, 14]:

- Hỗ trợ người dùng theo dõi và sắp xếp công việc theo thời hạn.
- Tạo hệ thống thông báo tự động và tùy chỉnh.
- Đảm bảo giao diện thân thiện, dễ dùng trên nền tảng mobile.

---

## ✨ Tính năng cốt lõi (MVP Features)

[cite_start]Ở giai đoạn MVP (Minimum Viable Product), ứng dụng tập trung vào các tính năng thiết yếu nhất để đảm bảo trải nghiệm người dùng nhanh chóng và hiệu quả[cite: 58]:

| Tính năng                    | Mô tả                                                                                                                |
| :--------------------------- | :------------------------------------------------------------------------------------------------------------------- |
| **📝 Tạo & Quản lý Task**    | [cite_start]Cho phép tạo, sửa, xóa và phân loại các đầu việc cần làm[cite: 59].                                      |
| **🔔 Nhắc nhở thông minh**   | [cite_start]Hệ thống thông báo linh hoạt (Reminders) và tính năng hoãn lại (Snooze) khi chưa thể làm ngay[cite: 60]. |
| **📅 Lịch & Timeline**       | [cite_start]Giao diện hiển thị tổng quan các deadline sắp tới trên lịch hoặc dòng thời gian[cite: 61].               |
| **📈 Theo dõi tiến độ**      | [cite_start]Cập nhật trạng thái hoàn thành hoặc phần trăm tiến độ của công việc[cite: 62].                           |
| **⚡ Tạo nhanh (Quick Add)** | [cite_start]Thêm nhanh deadline mới mà không cần qua nhiều bước phức tạp[cite: 63].                                  |

---

## 📱 Luồng người dùng & Kiến trúc thông tin

Dưới đây là sơ đồ luồng hoạt động của ứng dụng:

### 1. Kiến trúc thông tin (Information Architecture)

[cite_start]Sơ đồ tổng quan các màn hình chính: Onboarding, Đăng nhập, Màn hình chính (Home), Danh sách Task, Tạo Task, Lịch và Hồ sơ người dùng[cite: 65, 70].

![Sơ đồ Kiến trúc thông tin]([Thay thế link hình ảnh Information Architecture tại đây])

### 2. Luồng Đăng nhập & Quên mật khẩu

[cite_start]Quy trình xác thực người dùng, bao gồm đăng ký, đăng nhập và khôi phục mật khẩu qua OTP[cite: 83, 96, 104].

![User Flow: Đăng nhập]([Thay thế link hình ảnh User Flow Login tại đây])

### 3. Luồng Tạo Task (Create Task)

[cite_start]Quy trình người dùng nhập tiêu đề, danh mục, ngày giờ và xác nhận tạo task mới[cite: 109, 113].

![User Flow: Tạo Task]([Thay thế link hình ảnh User Flow Create Task tại đây])

### 4. Luồng Đánh dấu tiến độ (Mark Progress)

[cite_start]Người dùng có thể đánh dấu "Hoàn thành" (Done) hoặc cập nhật phần trăm (%) tiến độ công việc[cite: 127, 132].

![User Flow: Tiến độ]([Thay thế link hình ảnh User Flow Progress tại đây])

### 5. Luồng Nhắc nhở & Snooze (Reminder)

[cite_start]Cách ứng dụng hiển thị thông báo và xử lý khi người dùng chọn "Làm ngay" hoặc "Nhắc lại sau" (Snooze)[cite: 137, 143].

![User Flow: Reminder]([Thay thế link hình ảnh User Flow Reminder tại đây])

---

## 💡 Mô hình kinh doanh (Business Model Canvas)

- [cite_start]**Đối tượng mục tiêu:** Sinh viên đại học (18-25 tuổi), nhóm người dùng am hiểu công nghệ (Tech-savvy Gen Z)[cite: 55].
- [cite_start]**Giải pháp công nghệ:** Ứng dụng đa nền tảng (Cross-platform) sử dụng **React Native**, hỗ trợ đồng bộ hóa ngoại tuyến (Offline Synchronization)[cite: 55].
- **Dòng doanh thu:**
  - Đăng ký gói Premium (Premium Subscriptions).
  - Mua hàng trong ứng dụng (In-app Purchases).
  - [cite_start]Quảng cáo (Advertisement Revenue)[cite: 55].

---

## 🗺️ Định hướng phát triển (Roadmap)

[cite_start]Dựa trên nghiên cứu thị trường từ các ứng dụng như Todoist, TickTick và Microsoft To Do, lộ trình phát triển của DineLex được chia như sau[cite: 19, 29, 46]:

1.  [cite_start]**Giai đoạn 1 (Hiện tại):** Tập trung vào tính năng cốt lõi thật tốt và dễ dùng (Core Features)[cite: 51].
2.  **Giai đoạn 2 (Tương lai):** Sau khi có lượng người dùng ổn định, sẽ mở rộng thêm các module nâng cao như:
    - Dạng bảng (Kanban Board).
    - Lọc nhãn (Filter tags).
    - [cite_start]Template nâng cao[cite: 52].

---

## 🛠️ Cài đặt và Chạy ứng dụng

_(Phần này dành cho Developer)_

**Yêu cầu:**

- Node.js
- React Native CLI / Expo

**Các bước cài đặt:**

1. Clone repository:

```bash
git clone [https://github.com/username/dinelex-app.git](https://github.com/username/dinelex-app.git)
```
