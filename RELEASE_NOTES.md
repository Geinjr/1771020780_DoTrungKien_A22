# RELEASE NOTES - Portfolio v7

## Phiên bản

- Tên phiên bản: **Portfolio v7 - A2.2**
- Sinh viên: **Đỗ Trung Kiên - 1771020780**
- Ngày cập nhật: **30/10/2026**
- Nguồn xuất bản dự kiến: `main` / `/(root)`

## Thay đổi chính

1. Cá nhân hóa toàn bộ portfolio theo thông tin Đỗ Trung Kiên.
2. Sửa đường dẫn CSS từ đường dẫn tuyệt đối Windows sang `css/style.css` để chạy được trên máy khác và GitHub Pages.
3. Chuẩn hóa toàn bộ ảnh về đường dẫn tương đối trong `assets/`.
4. Nâng giao diện v7: hệ màu hồng, hero mới, card kỹ năng/dự án, timeline học tập và form liên hệ thống nhất.
5. Cải thiện responsive cho desktop, tablet và mobile.
6. Bổ sung trạng thái focus rõ, skip link và `prefers-reduced-motion`.
7. Bổ sung hồ sơ bàn giao: README, AI_LOG, RELEASE_NOTES, CHECKLIST_KIEM_CHUNG và minh chứng trước/sau.

## Lỗi đã sửa

- **Lỗi triển khai/khả chuyển:** file HTML đầu vào dùng đường dẫn CSS tuyệt đối theo ổ đĩa Windows. Cách sửa: chuyển sang đường dẫn tương đối.
- **Lỗi nhận diện:** bản đầu vào là portfolio của sinh viên khác. Cách sửa: thay toàn bộ tên, MSSV, lớp, quê quán và nội dung dự án theo hồ sơ Đỗ Trung Kiên.
- **Lỗi Pages 404 đã từng gặp trong quá trình Lab 5:** root chưa có `index.html` khi Pages cấu hình `/(root)`. Cách xử lý: đảm bảo `index.html` nằm ngay nguồn xuất bản.

## Commit liên quan

Điền sau khi thực hiện các commit thật trên repository:

- Commit mã nguồn v7: `CHUA_DIEN_SHA`
- Commit hồ sơ bàn giao: `CHUA_DIEN_SHA`
- Commit kiểm chứng cuối sau deploy (nếu có sửa): `CHUA_DIEN_SHA`

## Hạn chế còn lại

- Form là form thực hành phía client, không gửi email và không lưu dữ liệu máy chủ.
- URL GitHub Pages và status Network của bản v7 chưa thể khẳng định trước lần push/deploy cuối.
- Video demo khoảng 2 phút cần sinh viên tự quay nếu lớp yêu cầu.

## Cách tiếp tục kiểm tra/bàn giao

1. Push mã nguồn lên repository.
2. Xác nhận Pages lấy nguồn `main` + `/(root)`.
3. Chờ deploy thành công.
4. Mở URL trong cửa sổ riêng tư.
5. Kiểm tra CSS, ảnh, menu, form và tài nguyên trong Network.
6. Ghi SHA commit đã deploy vào hồ sơ nộp LMS và cập nhật các vị trí `CHUA_DIEN_SHA` nếu cần.
