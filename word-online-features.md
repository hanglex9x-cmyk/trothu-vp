# Tính năng tham khảo từ Microsoft Word Online — chuẩn bị thêm vào Office Việt AI

> Ghi chú: trang https://word.cloud.microsoft/vi-vn/ không đọc được nội dung qua công cụ fetch
> (browser.open báo lỗi, không được thử lại). Danh sách dưới đây tổng hợp từ kiến thức chung
> về Word for the Web, để đối chiếu khi thêm tính năng — cần kiểm chứng lại trên trang thật
> trước khi chốt.

## Word Online có — Office Việt AI hiện CHƯA có (ưu tiên thêm)

1. **Thanh Ribbon kiểu Word** (Trang đầu / Chèn / Bố trí / Xem lại / Xem) — gom công cụ đang rải rác thành ribbon quen tay.
2. **Chế độ xem trang A4** — khổ giấy, lề, ngắt trang, số trang, đầu trang/chân trang.
3. **Nhận xét (Comments) + @nhắc tên** — ghi chú bên lề từng đoạn, trả lời/gỡ nhận xét.
4. **Theo dõi thay đổi (Track Changes)** — bật/tắt, chấp nhận/từ chối từng sửa đổi.
5. **Trình kiểm tra Editor** — chính tả, ngữ pháp tiếng Việt, gợi ý viết rõ ràng, từ đồng nghĩa.
6. **Đọc chính tả (Dictate)** — gõ bằng giọng nói.
7. **Dịch văn bản** — dịch đoạn/bản dịch toàn tài liệu (hiện AI chỉ có dịch Anh).
8. **Mục lục tự động + Chú thích cuối trang (footnotes)** — theo tiêu đề Heading.
9. **Trình kiểm tra Trợ năng (Accessibility Checker)** — báo lỗi tương phản, alt text ảnh.
10. **Đọc to (Read Aloud) + Trình đọc nhập tâm (Immersive Reader)** — đọc văn bản, tập trung từng dòng.
11. **Lịch sử phiên bản + Tự lưu hiển thị rõ** — xem/khôi phục bản cũ (hiện mới có tự lưu, chưa có lịch sử).
12. **Chia sẻ + phân quyền** — gửi link xem/sửa (cần backend; bản tĩnh hiện chỉ lưu local).

## Word Online có — app ĐÃ có (không cần làm lại)

- Mẫu văn bản, Hoàn tác/Làm lại, Chèn bảng, Tìm & thay thế, Đếm từ, Xuất PDF/In, AI soạn thảo.

## Lưu ý kỹ thuật

- Soạn thảo cộng tác thời gian thực (co-authoring) KHÔNG làm được trên web tĩnh —
  cần backend (VD: Supabase/Vercel) mới làm được, để riêng thành bước lớn sau, không nhét vào đợt này.
- Giữ nguyên phong cách màu Excel đã duyệt; ribbon dùng xanh Excel `#217346`.
