# CV của Lưu Đức Mạnh

CV cá nhân dạng web tĩnh, có thể triển khai trực tiếp trên Cloudflare Pages.

## Chỉnh sửa nội dung

- Mở `index.html` và thay email, địa điểm, kinh nghiệm, dự án, kỹ năng và các liên kết mạng xã hội.
- Mở `style.css` nếu muốn thay đổi màu sắc hoặc bố cục.

## Triển khai trên Cloudflare Pages

1. Đẩy repository này lên GitHub hoặc GitLab.
2. Trong Cloudflare, mở **Workers & Pages** và chọn **Create application** > **Pages** > **Connect to Git**.
3. Chọn repository, đặt **Build command** trống và **Build output directory** là `/`.
4. Chọn **Save and Deploy**.

Cloudflare Pages sẽ tự động triển khai lại mỗi khi bạn push thay đổi lên nhánh đã chọn.