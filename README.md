# StudyQueue for UTT ☕

**StudyQueue for UTT - Trợ lý học tập E-learning (không chính thức)**

Tiện ích Chrome giúp theo dõi video còn thiếu tiến độ trên [hệ thống E-learning UTT](https://hoctructuyen.utt.edu.vn/), chọn bài cần xem và phát lần lượt qua các môn.

**[⬇ Tải bản 1.3.1](https://github.com/VDtrunG-Dev/utt-tool-study-public/raw/refs/heads/main/downloads/utt-study-queue-v1.3.1.zip)** · **[Hướng dẫn cài đặt](docs/CAI-DAT.md)** · **[Báo lỗi](https://github.com/VDtrunG-Dev/utt-tool-study-public/issues/new/choose)**

## Tiện ích làm được gì?

- Tìm các môn có trạng thái **Đang học** hoặc **Không đủ điều kiện thi**; loại mục **Hướng dẫn học tập trên hệ thống E-learning**.
- Đọc video cần học của từng môn. Thanh tải chỉ đạt **100% khi đã đọc đủ dữ liệu tất cả môn**.
- Hiển thị số phút trường đã ghi nhận, số phút yêu cầu và số phút còn thiếu. Cho phép chọn cả môn hoặc từng video.
- Bảng **Điều kiện dự thi · phần video** xếp môn theo mức thiếu: Còn thiếu nhiều, Sắp đủ (≤ 30 phút), Chờ buổi Vclass, Đủ phút video. Bảng chỉ tính video; kết luận đủ điều kiện thi vẫn theo trang trường.
- Phát lần lượt các video đã chọn, rồi chuyển sang môn tiếp theo.
- Bỏ qua ghi hình Vclass khi mục điểm danh của cùng buổi đã hoàn thành; để lại ghi hình chưa đến ngày học.
- Khi khoảng **3 phút phát thực tế** không có tiến độ tăng, lưu bài và vị trí, tải lại trang rồi mở lại đúng video. Tối đa 2 lần thử cho một bài.
- Có tùy chọn xác nhận tiếp tục học và báo khi trang cần bạn xử lý.

Tiện ích phát video ở **1×**. Trạng thái đạt yêu cầu lấy từ trang trường. **100% trên thanh tải là hoàn tất lấy danh sách, không phải hoàn thành môn học.**

## Cài nhanh trên Chrome

1. [Tải file ZIP 1.3.1](https://github.com/VDtrunG-Dev/utt-tool-study-public/raw/refs/heads/main/downloads/utt-study-queue-v1.3.1.zip), giải nén vào một thư mục cố định, ví dụ `Documents\UTT-Study-Queue`.
2. Mở thư mục đó và kiểm tra có file `manifest.json` cùng `core.js`, `adapter.js`, `styles.js`, `view.js`, `content.js`, `bridge.js`, `background.js`, `icon.png`, `coffee-qr.jpg`.
3. Mở Chrome, nhập `chrome://extensions` vào thanh địa chỉ rồi nhấn Enter.
4. Bật **Chế độ dành cho nhà phát triển / Developer mode**.
5. Bấm **Tải tiện ích đã giải nén / Load unpacked**, chọn thư mục **chứa trực tiếp `manifest.json`**.
6. Mở UTT, đăng nhập trên trang trường và tải lại trang. Bấm **📚 Danh sách học** ở góc dưới bên phải; dòng đầu phải hiện **1.3.1**.

👉 Xem [hướng dẫn đầy đủ](docs/CAI-DAT.md) để biết cách cập nhật, chọn video, xử lý lỗi và gỡ tiện ích. Đây là bản cài bằng thư mục giải nén; chưa có bản trên Chrome Web Store.

## Cách sử dụng

1. Mở Trang chủ UTT, danh sách lớp hoặc một môn. Tiện ích tự mở từng môn để đọc tiến độ; trang sẽ chuyển qua các môn trong lúc lấy dữ liệu.
2. Chờ lượt đọc kết thúc. Mở **Video cần học của tất cả môn**, chọn môn và mở danh sách bên dưới để chọn từng video.
3. Bấm **Phát danh sách đã chọn**. Chỉ sử dụng một tab UTT để chạy danh sách; giữ tab học hiển thị, máy thức và mạng ổn định.
4. Bấm **Dừng** trước khi đổi lựa chọn. Nếu Chrome chặn tự phát, bấm Play trên video rồi thử lại.

Nếu một môn lỗi, tiện ích ghi rõ lỗi và giữ dữ liệu các môn đã đọc. Sau lượt quét, bạn vẫn có thể chọn, phát các môn đã đọc hoặc bấm **Đọc lại tất cả môn** để thử lại. Môn đã hết video cần xem không được chọn để phát.

## Báo lỗi và hỗ trợ

**[Tạo báo lỗi trên GitHub](https://github.com/VDtrunG-Dev/utt-tool-study-public/issues/new/choose)** là cách thuận tiện để theo dõi việc sửa lỗi. Gửi kèm phiên bản tiện ích, phiên bản Chrome, các bước gây lỗi, điều mong đợi và ảnh thông báo lỗi đã che thông tin cá nhân.

Không gửi mật khẩu, cookie, mã đăng nhập hay thông tin tài khoản vào báo lỗi.

## Ủng hộ cà phê ☕

Nếu tiện ích giúp bạn quản lý việc học dễ hơn, bạn có thể mời mình một ly cà phê để tiếp thêm động lực bảo trì và sửa lỗi. **Ủng hộ hoàn toàn tự nguyện; tiện ích và việc báo lỗi vẫn miễn phí.** Cảm ơn bạn đã sử dụng, góp ý và chia sẻ!

Mở ứng dụng thanh toán/ngân hàng để quét mã dưới đây. Kiểm tra tên người nhận trong ứng dụng trước khi xác nhận chuyển tiền.

<img src="docs/assets/coffee-qr.png" alt="Mã QR nhận ủng hộ cà phê do tác giả cung cấp" width="300">

## Phiên bản và kiểm thử

**1.3.1** tách giao diện khỏi logic, tăng tương phản và cỡ chữ, làm giao diện phẳng hơn, thu gọn panel thành thanh mini khi đang phát, thêm nút chuyển sáng/tối, chuyển mã QR ủng hộ vào Cài đặt và bỏ chức năng xuất tiến độ. **1.3.0** thêm bảng điều kiện dự thi phần video, chỉ cho tiện ích bấm đúng các nút của môn học và danh sách lớp, chuyển tùy chọn Giữ phát khi chuyển tab sang mặc định tắt và giới hạn quy tắc tải về.

- **76 kiểm thử tự động** với dữ liệu mô phỏng cấu trúc UTT đã qua.
- Bản 1.3.1 chưa được kiểm tra trực tiếp trên trang UTT thật.
- **Kiểm tra trực tiếp trên Chrome ngày 13/10/2026 (bản 1.2.2):** hiển thị 100%, đọc đủ 7/7 môn và 27 video cần học; danh sách đang phát video C# và nhận được số phút trường ghi nhận.
- Chưa theo dõi một lượt xem hoàn tất toàn bộ 27 video trên trang thật. Trường có thể đổi giao diện; các lỗi mới được tiếp nhận qua Issues.

Chi tiết ở [TESTING.md](docs/TESTING.md) và [CHANGELOG.md](CHANGELOG.md).

## Dữ liệu và quyền truy cập

Tiện ích chỉ chạy tại `https://hoctructuyen.utt.edu.vn/`. Tiến độ đọc từ trang, lựa chọn video và tùy chọn được lưu trong bộ nhớ Chrome. Tiện ích không có máy chủ riêng và không gửi dữ liệu học tập hay tài khoản đi đâu.

Kết nối ra ngoài duy nhất: khi cài, khi mở Chrome và mỗi 6 giờ, tiện ích tải [`rules.json`](rules.json) từ chính kho GitHub này. File chỉ chứa bộ chọn giúp tìm các phần của trang UTT khi trường đổi giao diện; nó không thể đổi địa chỉ tải, không chứa mã chạy được và không mở rộng được những nút tiện ích được phép bấm. Bộ chọn sai cú pháp bị bỏ qua.

Tiện ích cần quyền **storage** để lưu lựa chọn, **notifications** để báo khi cần thao tác, **alarms** để hẹn giờ tải `rules.json`, và quyền đọc `raw.githubusercontent.com/VDtrunG-Dev/utt-tool-study-public` để tải file đó. Mặc định tiện ích không thay đổi cách trang trường nhận biết bạn chuyển tab hay thu nhỏ cửa sổ; chỉ khi bạn tự bật **Giữ phát khi chuyển tab** trong Cài đặt, trang trường mới luôn thấy tab đang hiển thị. Chi tiết trong [Chính sách quyền riêng tư](docs/PRIVACY.md). Bạn đăng nhập trực tiếp trên UTT; tiện ích không cung cấp biểu mẫu nhập tài khoản.

Đây là tiện ích cộng đồng do **[VDtrunG-Dev](https://github.com/VDtrunG-Dev)** duy trì, không phải sản phẩm chính thức của UTT. Điều kiện học tập và thi vẫn theo hệ thống trường.

## Giấy phép

Bảo lưu mọi quyền. Bạn được cài và dùng tiện ích cho việc học của mình; không được sao chép, sửa đổi hay phát hành lại khi chưa có sự đồng ý của tác giả. Xem [LICENSE](LICENSE).
