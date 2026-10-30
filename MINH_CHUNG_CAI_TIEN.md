# MINH CHỨNG CẢI TIẾN GIAO DIỆN - BUỔI 5–6

## Vấn đề ban đầu

Bản đầu vào có nhận diện của sinh viên khác, đường dẫn CSS tuyệt đối theo ổ đĩa Windows và giao diện chưa thể hiện rõ tiến trình bài của Đỗ Trung Kiên. Đường dẫn tuyệt đối làm giảm khả năng chạy trên máy khác/GitHub Pages.

## Tiêu chí đánh giá

- Tính nhất quán về màu, typography, khoảng cách và card.
- Responsive không tràn ngang.
- Focus bàn phím nhìn rõ.
- Tài nguyên dùng đường dẫn tương đối để deploy được.
- Nội dung cá nhân khớp người nộp.

## Cách sửa

- Thiết kế lại hero, skill/project card, timeline và form theo cùng một hệ màu.
- Dùng `clamp()` cho tiêu đề, Grid chuyển 3 → 2 → 1 cột theo vùng nhìn.
- Bổ sung `:focus-visible`, `:focus-within`, skip link và `prefers-reduced-motion`.
- Chuyển CSS/ảnh về đường dẫn tương đối.
- Cá nhân hóa toàn bộ nội dung sang Đỗ Trung Kiên.

## Bằng chứng trước/sau

- Trước: `minh-chung/before.png`
- Sau desktop: `minh-chung/after-desktop.png`
- Tablet: `minh-chung/responsive-768.png`
- Mobile: `minh-chung/after-mobile.png`

## Kết quả thử local

Bản v7 hiển thị CSS đúng, bố cục không tràn ngang ở các kích thước minh chứng và các card chuyển cột theo không gian. Focus được làm rõ bằng viền màu vàng.

## Hạn chế và phương án cải tiến

- Chưa có backend cho form; có thể bổ sung dịch vụ form/server ở học phần sau.
- Chưa có kiểm thử tự động; có thể bổ sung Lighthouse/axe hoặc CI ở phiên bản tiếp theo.
- URL công khai cần được kiểm tra lại sau lần deploy cuối để xác nhận local–repo–URL cùng một bản mã.
