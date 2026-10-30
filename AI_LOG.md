# AI LOG - BUỔI 7, TIẾT 3

## Thông tin sinh viên

- Họ và tên: Đỗ Trung Kiên
- Mã sinh viên - Lớp: 1771020780 - CNTT17-13
- Ngày thực hiện: 30/10/2026
- Link repository: https://github.com/Geinjr/1771020780_DoTrungKien_A22
- URL website: https://geinjr.github.io/1771020780_DoTrungKien_A22/
- Tình huống: [x] Website của tôi  [ ] Repo luyện của giảng viên

## 1. Nhận định của tôi trước khi hỏi AI

- Trang/thao tác gặp lỗi: GitHub Pages sau khi bật `main` + `/(root)`.
- Mong muốn và hiện tượng thực tế: muốn URL Pages mở portfolio nhưng trình duyệt trả 404.
- Dữ kiện đã kiểm tra: ở root repository lúc đó chỉ có một thư mục bao ngoài; `index.html` của portfolio nằm trong thư mục con nên Pages không tìm thấy file vào ở root.
- Tôi nghi nguyên nhân là: cấu trúc thư mục xuất bản chưa đúng với cấu hình `/(root)`.
- Vì sao tôi nhận định như vậy: GitHub Pages cần file `index.html` trong đúng thư mục nguồn đã chọn; root chưa có file này.

## 2. Tôi hỏi AI và nhận được gợi ý

- Nguồn: [x] Công cụ AI: ChatGPT  [ ] Phản hồi mẫu của giảng viên
- Câu hỏi/prompt tôi đã gửi: hỏi vì sao GitHub Pages deploy nhưng URL trả 404 và cách push lại để `index.html` nằm đúng root.
- Gợi ý chính của AI: đưa nội dung trong `portfolio-v5` ra root repository, giữ cấu hình Pages là `main` + `/(root)`, sau đó `git add`, commit, push và chờ deploy lại.

## 3. Quyết định của tôi

- [x] Chấp nhận gợi ý
- [ ] Chỉnh sửa gợi ý rồi áp dụng
- [ ] Bác bỏ gợi ý

- Tôi quyết định làm gì: copy nội dung website ra root để `index.html`, `css/`, `assets/` nằm đúng nguồn xuất bản.
- Lý do, dựa trên dữ kiện nào: cấu trúc root sau khi copy đã xuất hiện `index.html`, `ket-qua.html`, `css/`, `assets/`; phù hợp cấu hình Pages chọn `/(root)`.

## 4. Thực hiện và kiểm chứng

- Tệp/vị trí đã sửa: cấu trúc root repository; phiên bản v7 tiếp tục chuẩn hóa đường dẫn tài nguyên tương đối.
- Nội dung thay đổi hoặc cách xử lý khác: không dùng đường dẫn tuyệt đối theo ổ đĩa Windows; CSS được liên kết bằng `css/style.css`, ảnh bằng `assets/...`.
- Commit của bản sửa, nếu có: **Điền SHA sau khi commit/push bản v7 cuối**.
- Bản sửa đã deploy: [ ] Có  [x] Chưa  [ ] Không phát sinh bản sửa

| Nội dung kiểm tra | Trước xử lý | Sau xử lý/thử lại |
| --- | --- | --- |
| Request URL và Status của tài nguyên liên quan | URL Pages trả 404 theo quan sát thực tế | Chưa kiểm tra trên URL công khai của bản v7 |
| Giao diện/chức năng trên URL website | Không mở được trang chính | Local v7 mở được; URL công khai cần thử lại sau deploy |

- Cách thử lại và kết quả thực tế: local đã kiểm tra cấu trúc file và đường dẫn tương đối. Sau khi push cần chờ Pages deploy, mở cửa sổ riêng tư, kiểm tra URL và DevTools > Network.
- Căn cứ để đối chiếu: `index.html`, `css/style.css`, ảnh trong `assets/`, ảnh trong `minh-chung/` và commit cuối sau khi push.

## 5. Kết luận

- [ ] Đã xử lý được  [x] Xử lý được một phần  [ ] Chưa xử lý được
- Điều tôi rút ra hoặc việc cần làm tiếp: local đúng chưa đủ để kết luận deploy thành công. Cần xác nhận URL công khai, status tài nguyên và SHA commit đã deploy rồi mới chốt hồ sơ.
