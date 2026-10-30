# Portfolio v7 - Đỗ Trung Kiên

Bài đánh giá **A2.2 - FIT4014: Triển khai và bàn giao Portfolio v7 trên GitHub Pages**.

## 1. Thông tin sinh viên

- Họ và tên: **Đỗ Trung Kiên**
- MSSV: **1771020780**
- Lớp: **CNTT17-13**
- Quê quán: **Hưng Yên**
- Repository dự kiến: <https://github.com/Geinjr/1771020780_DoTrungKien_A22>
- GitHub Pages dự kiến: <https://geinjr.github.io/1771020780_DoTrungKien_A22/>

> URL công khai và SHA cuối cần được xác nhận lại sau lần push/deploy cuối. Không coi URL là đã kiểm chứng chỉ vì local chạy đúng.

## 2. Mô tả sản phẩm

Portfolio v7 phát triển từ các bài Lab trước, tập trung vào:

- HTML5 ngữ nghĩa và cấu trúc rõ ràng.
- CSS3 với Flexbox/Grid và responsive design.
- Trạng thái hover, active, focus-visible và focus-within.
- Form HTML5 có ràng buộc `required`, `type=email`, `minlength`, `maxlength`.
- Khả năng truy cập cơ bản: skip link, focus rõ, alt cho ảnh, hỗ trợ `prefers-reduced-motion`.
- Hồ sơ bàn giao gồm README, AI_LOG, RELEASE_NOTES và CHECKLIST_KIEM_CHUNG.

## 3. Cấu trúc thư mục

```text
/
├── index.html
├── ket-qua.html
├── css/
│   └── style.css
├── assets/
│   ├── avatar.svg
│   ├── du-an-1.svg
│   ├── du-an-2.svg
│   └── du-an-3.svg
├── minh-chung/
│   ├── before.png
│   ├── after-desktop.png
│   ├── after-mobile.png
│   └── responsive-768.png
├── README.md
├── AI_LOG.md
├── RELEASE_NOTES.md
└── CHECKLIST_KIEM_CHUNG.md
```

## 4. Cách chạy local

Không cần cài thư viện hoặc framework.

1. Clone/download repository.
2. Mở thư mục dự án.
3. Mở `index.html` trực tiếp bằng trình duyệt, hoặc dùng Live Server trong VS Code.
4. Kiểm tra `ket-qua.html` bằng cách nhập dữ liệu giả hợp lệ vào form.

## 5. Cách kiểm tra nhanh

- Desktop: menu ngang, hero 2 cột, skill/project 3 cột.
- Tablet: card chuyển 2 cột, nội dung không tràn ngang.
- Mobile: card 1 cột, menu wrap, form vừa màn hình.
- Dùng `Tab`/`Shift+Tab`: focus phải nhìn rõ.
- Form rỗng/email sai/nội dung ngắn: trình duyệt phải chặn gửi.
- Dữ liệu hợp lệ: chuyển tới `ket-qua.html`.
- Trên GitHub Pages: mở DevTools > Network và kiểm tra `index.html`, `css/style.css`, ảnh SVG đều trả status thành công.

## 6. Nguồn xuất bản

- Nhánh dự kiến: `main`
- Thư mục dự kiến: `/ (root)`
- File vào: `index.html`

## 7. Hồ sơ bàn giao

- [AI_LOG.md](AI_LOG.md)
- [RELEASE_NOTES.md](RELEASE_NOTES.md)
- [CHECKLIST_KIEM_CHUNG.md](CHECKLIST_KIEM_CHUNG.md)
- [Minh chứng cải tiến giao diện](minh-chung/)

## 8. Khai báo sử dụng AI

AI được sử dụng để hỗ trợ đọc yêu cầu, rà soát cấu trúc hồ sơ, gợi ý cách tổ chức nội dung, CSS và quy trình chẩn đoán lỗi GitHub Pages. Các nội dung phải kiểm chứng bằng URL/SHA được đánh dấu rõ là **chưa kiểm tra** cho đến khi sinh viên tự push, deploy và thử lại trên URL công khai.

Chi tiết quyết định và tình huống xử lý được ghi trong [AI_LOG.md](AI_LOG.md).
