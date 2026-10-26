# Lịch sử thay đổi

## 1.3.0 — 26/10/2026

- Thêm bảng **Điều kiện dự thi · phần video**: mỗi môn hiện số phút còn thiếu, số video còn thiếu, trạng thái trường ghi và mức Còn thiếu nhiều / Sắp đủ (≤ 30 phút) / Chờ buổi Vclass / Đủ phút video. Môn lỗi và môn thiếu nhiều nhất nằm trên cùng.
- Chỉ bấm tab Nội dung / Tiến trình, bài trong cây nội dung, mũi tên nhóm bài, nút “Vào học” và nút phân trang. Bỏ các bộ chọn chung (`nav a`, mọi tab, mọi mũi tên, từ khóa “xem”) có thể bấm nhầm menu hoặc nút “Xem điểm”.
- Khi trang thiếu ID tab, chỉ tìm tab có nhãn bắt đầu bằng “Nội dung” / “Tiến trình”; không dùng cùng một tab cho cả hai.
- Bảng tiến độ chỉ đọc trong tab Tiến trình; không coi tab đang mở bất kỳ là tab Nội dung.
- Quy tắc tải về: địa chỉ cố định trong mã, tối đa 50 KB, chỉ giữ các khóa bộ chọn đã biết; bộ chọn sai cú pháp bị bỏ qua. Tải lại mỗi 6 giờ và khi mở Chrome.
- Tùy chọn **Giữ phát khi chuyển tab** chuyển sang **mặc định tắt**. Khi bật trong Cài đặt, trang trường luôn thấy tab đang hiển thị và video tự phát tiếp khi bị dừng. Giá trị lưu từ bản cũ (trước đây mặc định bật) không còn được dùng; ai muốn dùng phải tự bật lại.
- Gỡ liên kết và mã QR hỗ trợ cũ; báo lỗi qua GitHub Issues.
- Thêm nút **☕ Ủng hộ** ở chân bảng điều khiển: chỉ khi bấm mới tải và hiện mã QR ủng hộ tự nguyện; bấm lần nữa để ẩn.
- Gói nộp Store và gói tải về được rút gọn mã (minify); toàn bộ kiểm thử chạy lại trên bản rút gọn trước khi tạo ZIP.
- Tài liệu, `rules.json` và gói tải về chuyển sang repo công khai `VDtrunG-Dev/utt-tool-study-public`; thêm giấy phép bảo lưu mọi quyền.
- 59 kiểm thử tự động đã qua.

## 1.2.2 — 13/10/2026

- Chờ trang môn khởi tạo ổn định trước khi mở tab tiến độ.
- Chờ dữ liệu phân trang ổn định để tránh đọc lại tên môn cũ và báo trùng.
- Lưu đúng đường dẫn môn trước khi đọc để phục hồi nếu UTT trở về Home.
- Môn tiếp tục lỗi sau phục hồi được ghi lỗi riêng; việc đọc các môn còn lại tiếp tục.
- Giữ phiên Dừng qua lần tải trang tiếp theo; không tự bắt đầu lại một lượt đã dừng.
- 48 kiểm thử tự động đã qua. Quan sát trực tiếp: 7/7 môn, 27 video cần học, thanh tải 100% và video đang phát.

## 1.2.1

- Quay về trang đầu trước khi tìm môn hoặc đọc lại danh sách.
- Lọc đúng trạng thái Đang học / Không đủ điều kiện thi; loại hướng dẫn hệ thống.
- Cho phép phát các môn đã đọc sau lượt quét khi một môn khác lỗi.

## 1.2.0

- Tự lấy danh sách video của các môn, hiển thị tiến độ lấy dữ liệu.
- Chọn video theo môn và giữ lựa chọn khi chuyển trang.

## 1.1.0

- Hàng đợi qua nhiều môn và tự phục hồi sau 3 phút phát không có tiến độ tăng.
- Để lại ghi hình Vclass chưa đến ngày.

## 1.0.3

- Chọn, phát lần lượt video; hiển thị số phút đã ghi nhận và còn thiếu.
- Bỏ qua ghi hình khi đã điểm danh cùng buổi; xử lý xác nhận tiếp tục học theo tùy chọn.
