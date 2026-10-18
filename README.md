# Bài tập Markdown: Sửa lỗi & Hoàn thiện tài liệu

## Phần 1: Phân tích lỗi cú pháp

Đoạn mã ban đầu gặp các lỗi sau:

1. **Lỗi phân cấp Heading (Thứ tự tiêu đề):** 
   - *Hiện trạng:* Dùng `#` (H1) ngay sau đó nhảy xuống `###` (H3).
   - *Nguyên nhân:* Nhảy cấp tiêu đề làm mất tính logic trong cấu trúc bài viết và render kích thước không đều. Cần dùng `##` (H2) sau `#` (H1).

2. **Lỗi cú pháp chèn ảnh (Image Syntax):**
   - *Hiện trạng:* `[Logo Dự án] (https://greentech.vn/logo.png)`
   - *Nguyên nhân:* Thiếu dấu chấm than `!` ở đầu và có khoảng trắng thừa giữa `]` và `(`. Markdown sẽ hiểu đây là văn bản thường kèm link lỗi chứ không hiển thị được hình ảnh.

3. **Lỗi cú pháp in đậm (Emphasis):**
   - *Hiện trạng:* Chỉ dùng 1 dấu sao `*Rất quan trọng*` hoặc không đúng cú pháp.
   - *Nguyên nhân:* 1 dấu sao `*text*` chỉ tạo chữ *in nghiêng*. Muốn **in đậm** phải dùng 2 dấu sao `**text**` bọc hai đầu và không để khoảng trắng sát bên trong.

---

## Phần 2: Đoạn mã Markdown hoàn thiện

```markdown
# Lợi ích của rau sạch

![Logo Dự án](https://greentech.vn/logo.png)

## Danh sách các loại rau

Rau sạch đóng vai trò **Rất quan trọng** đối với sức khỏe gia đình.

> Ăn rau xanh mỗi ngày giúp tăng cường sức đề kháng và phòng chống bệnh tật.

* Rau cải ngọt
* Rau muống
* Cà chua

Xem thêm thông tin tại [GreenTech Website](https://greentech.vn).
```
