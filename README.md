# Quản lý công việc — Xây dựng & Cho thuê BĐS

Ứng dụng quản lý công việc đơn giản, chạy ngay trên trình duyệt (máy tính + điện thoại),
không cần cài đặt, không cần internet. Thiết kế cho công ty nhỏ làm xây dựng và cho thuê BĐS,
thay cho việc giao việc rải rác qua Zalo.

## Dùng thế nào

1. Mở file `index.html` bằng trình duyệt (Chrome, Safari, Cốc Cốc...).
   - Trên máy tính: nhấp đúp vào file.
   - Trên điện thoại: gửi file cho mình qua Zalo/email rồi mở, hoặc xem hướng dẫn "đưa lên web" bên dưới.
2. Bấm **+ Thêm việc** để tạo công việc: tên việc, công trình, người phụ trách, hạn, độ ưu tiên, ghi chú.
3. Tích ô vuông khi việc hoàn thành.

## Tính năng

- **Thống kê nhanh**: đang làm / trễ hạn / sắp đến hạn / đã xong.
- **Lọc theo** người phụ trách, công trình, trạng thái; **tìm kiếm** tự do.
- **Cảnh báo hạn**: việc trễ hạn tô đỏ, sắp đến hạn (trong 3 ngày) tô vàng.
- **Ưu tiên**: gấp (đỏ), bình thường (cam), thấp (xám) — tự sắp xếp việc gấp/sắp hết hạn lên trên.
- **Xuất/Nhập dữ liệu** (file JSON) để sao lưu hoặc chuyển sang máy khác.

## Lưu ý về dữ liệu

Hiện dữ liệu được lưu **trên chính trình duyệt của máy đang dùng** (không tự đồng bộ giữa nhiều người).
Phù hợp để một người (quản lý) theo dõi tổng, hoặc mỗi người tự quản việc của mình rồi báo cáo.

**Muốn cả 10 người cùng xem/sửa chung một danh sách theo thời gian thực?** Đó là bước tiếp theo —
cần đưa ứng dụng lên web có lưu trữ chung. Nhắn để được hỗ trợ dựng.
