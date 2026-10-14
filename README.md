# Responsive Grid Sass

Bài CodeGym 1515.

## Chạy
`npm ci`, `npm run build`, sau đó mở index.html. `npm run build:min` tạo CSS nén; `npm run watch` theo dõi thay đổi. PowerShell có thể dùng npm.cmd.

## Tái cấu trúc
Nguồn: https://github.com/codegym-vn/responsive-grid. Giữ nguyên 12 cột, các lớp overlay, màu và tỷ lệ của responsive_grid.htm; chuyển CSS nội bộ và inline thành class + SCSS. Biến cho màu/chiều cao và Mixin cho cột/trang trí. Bản gốc kèm theo trong original.html và source/.

Dùng @use để gộp partials. CSS đã biên dịch được commit để có thể mở trang ngay.

## Đối chiếu
Mở original.html để xem bản CSS ban đầu. Kết quả biên dịch tại build-validation.json; kiểm tra computed styles và bố cục trước/sau tại validation.json.
