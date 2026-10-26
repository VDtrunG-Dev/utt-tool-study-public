# Chính sách quyền riêng tư — Hỗ trợ học UTT

Cập nhật: 26/10/2026 · Áp dụng từ phiên bản 1.3.0

Hỗ trợ học trực tuyến cho UTT E-learning (không chính thức) là tiện ích cộng đồng, không chính thức, do [VDtrunG-Dev](https://github.com/VDtrunG-Dev) duy trì. Tiện ích không phải sản phẩm của Trường Đại học Công nghệ Giao thông Vận tải (UTT).

## Tiện ích đọc dữ liệu gì

Tiện ích chỉ chạy trên `https://hoctructuyen.utt.edu.vn/`. Trên các trang đó, tiện ích đọc:

- tên môn học, trạng thái môn và tên các bài học;
- số phút học trường đã ghi nhận, số phút yêu cầu và trạng thái hoàn thành của từng bài;
- vị trí đang xem của video để mở lại đúng chỗ sau khi tải lại trang.

Tiện ích **không** đọc hay lưu mật khẩu, cookie, mã đăng nhập, điểm thi hay thông tin liên hệ. Bạn đăng nhập trực tiếp trên trang trường; tiện ích không có biểu mẫu nhập tài khoản.

## Dữ liệu được lưu ở đâu

Mọi dữ liệu trên được lưu trong bộ nhớ của Chrome trên máy bạn (`chrome.storage`). Dữ liệu không được gửi tới tác giả, máy chủ của tiện ích hay bất kỳ bên thứ ba nào. Tiện ích không dùng công cụ phân tích, quảng cáo hay theo dõi.

## Kết nối mạng

Kết nối duy nhất tiện ích tự thực hiện là tải file [`rules.json`](../rules.json) từ `raw.githubusercontent.com/VDtrunG-Dev/utt-tool-study-public` khi cài, khi mở Chrome và mỗi 6 giờ. File chứa bộ chọn giúp tìm các phần của trang UTT khi trường đổi giao diện; nó không chứa mã chạy được. Yêu cầu này không gửi kèm dữ liệu học tập hay cookie. Như mọi yêu cầu web, GitHub nhận được địa chỉ IP và thông tin trình duyệt theo [chính sách của GitHub](https://docs.github.com/site-policy/privacy-policies/github-general-privacy-statement).

## Chia sẻ và bán dữ liệu

Tiện ích không bán, chia sẻ hay chuyển dữ liệu người dùng cho bên thứ ba, và không dùng dữ liệu cho mục đích nào ngoài chức năng hiển thị và phát danh sách học.

## Xóa dữ liệu

Gỡ tiện ích tại `chrome://extensions` sẽ xóa toàn bộ dữ liệu tiện ích đã lưu. Số phút học trường đã ghi nhận vẫn do hệ thống của trường lưu giữ.

## Liên hệ

Câu hỏi về quyền riêng tư: [tạo issue trên GitHub](https://github.com/VDtrunG-Dev/utt-tool-study-public/issues/new/choose).

---

## Summary (English)

UTT E-learning Study Helper is an unofficial community extension that runs only on `hoctructuyen.utt.edu.vn`. It reads course names, lesson names, credited and required minutes, completion status and the current video position from those pages, and stores them locally with `chrome.storage`. No user data is transmitted to the developer or any third party; there is no analytics or advertising. The only network request the extension makes is a periodic download of a selector file (`rules.json`, data only, no executable code) from the project's GitHub repository, sent without cookies or user data. Uninstalling the extension deletes all stored data. Contact: GitHub issues at https://github.com/VDtrunG-Dev/utt-tool-study-public.
