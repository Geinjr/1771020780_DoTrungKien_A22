# CHECKLIST KIỂM CHỨNG LOCAL - REPO - URL

> Chỉ đánh dấu `[x]` khi đã thực sự kiểm tra. Những mục phụ thuộc GitHub sau lần push cuối hiện để `[ ]`.

## 1. Local

- [x] `index.html` nằm ở root của bộ mã bàn giao.
- [x] `css/style.css` dùng đường dẫn tương đối.
- [x] Ảnh trong `assets/` dùng đường dẫn tương đối.
- [x] Trang chính mở local và hiển thị CSS.
- [x] Responsive được kiểm tra ở 1280px, 768px và 390px bằng ảnh minh chứng.
- [x] Form có ràng buộc HTML5 và trang `ket-qua.html` tồn tại.
- [x] Không dùng JavaScript/framework cho các chức năng đang có.

## 2. Repository

- [ ] Đã copy bộ v7 vào repository thật.
- [ ] `git status` sạch sau commit cuối.
- [ ] Repository có ít nhất 3 commit có ý nghĩa thể hiện tiến trình.
- [ ] `git log --oneline` hiển thị đúng các commit cần nộp.
- [ ] SHA local khớp SHA trên GitHub.

**SHA local cuối:** `CHUA_KIEM_TRA`

**SHA repo cuối:** `CHUA_KIEM_TRA`

## 3. Bản triển khai GitHub Pages

- [ ] Deploy thành công từ nhánh `main`, thư mục `/(root)`.
- [ ] URL mở được trong cửa sổ riêng tư/tài khoản khác.
- [ ] `index.html` trả status thành công.
- [ ] `css/style.css` trả status thành công.
- [ ] Các ảnh `assets/*.svg` tải thành công.
- [ ] Menu điều hướng đúng section.
- [ ] Form hợp lệ chuyển được tới `ket-qua.html`.

**URL kiểm tra:** https://geinjr.github.io/1771020780_DoTrungKien_A22/

**Commit của lần deploy thành công:** `CHUA_KIEM_TRA`

## 4. Đối chiếu cùng phiên bản

- [ ] Nội dung tên “Đỗ Trung Kiên” trên URL khớp `index.html` trong repo.
- [ ] Màu/giao diện trên URL khớp ảnh `minh-chung/after-desktop.png`.
- [ ] SHA bản nộp là commit đang được Pages deploy.
- [ ] Nếu sửa sau kiểm chứng, đã kiểm tra lại URL phiên bản mới.

## 5. Căn cứ/minh chứng

- `minh-chung/before.png`: giao diện đầu vào trước cải tiến.
- `minh-chung/after-desktop.png`: bản v7 desktop.
- `minh-chung/responsive-768.png`: bản v7 tablet.
- `minh-chung/after-mobile.png`: bản v7 mobile.
- `AI_LOG.md`: tình huống chẩn đoán 404 và quyết định xử lý.
- `RELEASE_NOTES.md`: thay đổi, lỗi sửa và hạn chế.

## 6. Kết luận hiện tại

Local v7 đã được chuẩn bị và kiểm tra về cấu trúc/giao diện. Phần repository, SHA và URL công khai **chưa được đánh dấu hoàn tất** vì phải kiểm tra trên GitHub sau khi sinh viên push bản cuối.
