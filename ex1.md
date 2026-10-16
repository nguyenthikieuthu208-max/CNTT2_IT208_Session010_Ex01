**Bài 1 : Chuẩn hóa tài liệu Markdown cho dự án**
PHẦN 1: PHÂN TÍCH 3 LỖI CÚ PHÁP TRONG BẢN THẢO VÀ NGUYÊN NHÂN

1.  Lỗi phân cấp tiêu đề (Heading Cấp độ không theo thứ tự)
    -   Bạn sinh viên gõ cấu trúc tiêu đề nhảy bậc lộn xộn từ `## 1. Tốt cho sức khỏe` (H2) xuống `### 1.1. Tăng cường miễn dịch` (H3), rồi lại quay về `## 2. An toàn và tự nhiên` (H2) và `### 2.1. Bảo vệ môi trường` (H3).
   
2.  Lỗi ảnh không hiển thị (Path sai hoặc sai cú pháp):
    -   _Hiện trạng:_ Đoạn mã gõ là `![Rau sạch][images/rau-sach.jpg]`.
    -   _Nguyên nhân:_ Bạn sinh viên đã dùng sai cặp ký tự. Cú pháp chèn ảnh chuẩn của Markdown bắt buộc phải là **dấu ngoặc đơn `(...)`** cho phần đường dẫn, chứ không được dùng cặp dấu ngoặc vuông thứ hai `[...]`. Do đó, ảnh bị lỗi liên kết và chỉ hiện chữ thay thế (Alt text) "Rau sạch".
3. Lỗi định dạng hiển thị lộn xộn, thiếu nhất quán:
   _Hiện trạng:_ Phần nội dung mô tả dưới các tiêu đề không được định dạng nhấn mạnh, các danh sách bullet point (`-`) nằm sát lề, và câu kết bài dùng thẻ trích dẫn `>` nhưng chưa làm nổi bật được từ khóa cốt lõi
   PHẦN 2: ĐOẠN MÃ MARKDOWN CHUẨN HÓA HOÀN THIỆN
 markdown

```
# Lợi ích của Rau sạch

Rau sạch mang lại rất nhiều lợi ích cho sức khỏe.

## 1. Tốt cho sức khỏe
* **Giàu vitamin** và khoáng chất.
* **Giảm nguy cơ** mắc bệnh.

### 1.1. Tăng cường miễn dịch
Giúp cơ thể khỏe mạnh hơn mỗi ngày.

![Rau sạch](images/rau-sach.jpg)

## 2. An toàn và tự nhiên
Không hóa chất, không thuốc trừ sâu.

### 2.1. Bảo vệ môi trường
Giảm ô nhiễm đất và nguồn nước.

> **Rau sạch — Cho cuộc sống xanh!**
```

