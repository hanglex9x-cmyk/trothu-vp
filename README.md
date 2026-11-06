# Trợ Thủ Văn Phòng

Web app văn phòng đa chức năng — phong cách màu Excel (xanh lá Excel `#217346`, nền trắng). Tên hiển thị mới từ 6/11/2026 (trước đây: Office Việt AI); repo GitHub và project Vercel đã đổi tên thành `trothu-vp`.

## Tính năng

- Tạo Tài liệu / Bảng tính / Bản trình bày / Markdown / HTML / PDF
- 12 mẫu văn bản Việt: Hợp đồng, Báo giá, Biên bản họp, CV, Đơn xin nghỉ phép, Công văn, Quyết định, Đơn xin việc, Thư mời họp, Bảng chấm công, Báo cáo công việc tuần, Thư cảm ơn khách hàng — có tìm kiếm và lọc theo nhóm
- 9 công cụ nhanh: Tính VAT & chiết khấu (kèm đọc số thành chữ), Tính ngày & hạn xử lý, Tạo mã chứng từ, Xoá dòng trùng lặp, Trình tạo CV, …
- Quản lý tệp: tìm kiếm, lọc, sắp xếp, gắn sao, đổi tên, nhân bản
- Trình soạn thảo kiểu Word: Tự lưu, Lịch sử phiên bản, Bình luận, Chế độ đề xuất, Đọc chính tả tiếng Việt, Đọc to, Chế độ đọc tập trung, Kiểm tra văn bản, Hoàn tác / Làm lại, Chèn bảng, Tìm & thay thế
- Bộ công cụ PDF kiểu iLovePDF (28 công cụ chạy được): Gộp (Merge), Tách (Split), Nén, Sắp xếp trang, Xoay, Đánh số trang, Cắt lề (Crop), Che thông tin (Redact), Watermark, Ký, Sửa PDF, PDF ↔ Word / PowerPoint / Excel / JPG / Markdown, Word / PowerPoint / Excel / JPG / HTML → PDF, OCR, Tóm tắt AI, Dịch PDF. Riêng Đặt mật khẩu và PDF/A ghi rõ cần máy chủ nên chưa làm trong bản tĩnh. Công cụ PDF có sheet riêng độc lập (tìm kiếm/lọc theo nhóm, bấm công cụ mở sheet riêng, có nút quay lại) giống Thư viện Hàm Excel.
- Thư viện hàm Excel chuẩn 2019 (15 hàm cơ bản + 15 hàm nâng cao, 8 mẹo, 4 bài tập có đáp án — không dùng hàm chỉ có trên Microsoft 365 như XLOOKUP/FILTER/UNIQUE)
- Cẩm nang Word (7 mục: Styles, mục lục tự động, Mail Merge, bảng/biểu đồ, chú thích cuối trang, theo dõi thay đổi, phím tắt) với ví dụ mẫu và bài tập thực hành
- Giao diện lọc theo mục: chọn mục nào chỉ hiện nội dung mục đó, trang chủ mặc định mở mục Tài liệu — gọn, không cuộn tràn lan
- Mỗi công cụ mở một sheet riêng (có nút quay lại danh sách); icon style 2026 (SVG bo tròn mềm, nền gradient theo nhóm)
- Studio Thiết kế kiểu Canva: thiết kế poster, thiệp, banner từ mẫu sẵn
- Trợ lý AI miễn phí (chạy trên trình duyệt, không cần tài khoản hay API key): soạn Công văn, Quyết định, Thông báo nội bộ, Kế hoạch công việc tuần, viết lại, tóm tắt

## Chạy

Mở `index.html` bằng trình duyệt, hoặc deploy tĩnh lên Vercel (Hobby miễn phí, không cần build).

## Link live

- https://trothu-vp.vercel.app (link chính)
- https://office-viet-ai.vercel.app (link cũ, Vercel giữ làm alias — vẫn mở được, cùng bản mới)

## Ghi chú

- Dữ liệu tệp lưu trong phiên mở trang; tải file xuống máy để giữ lâu dài.
- AI và công cụ PDF chạy ngay trên trình duyệt nên miễn phí, file không tải lên máy chủ nào.
- Cộng tác thời gian thực cần máy chủ riêng nên chưa có — chia sẻ qua file tải xuống.
