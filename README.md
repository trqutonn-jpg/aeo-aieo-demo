# English Learning Hub - AEO/AIEO Focus

Website tĩnh cho chủ đề học tiếng Anh, tối ưu chủ yếu theo kỹ thuật triển khai AEO và AIEO.

## Mục tiêu project

- Tạo nội dung trả lời nhanh cho người học (AEO).
- Tạo cấu trúc dữ liệu rõ ràng để hệ thống AI hiểu đúng ngữ cảnh (AIEO).
- Dùng website như một template thực hành để tái sử dụng cho dự án khác.

## Kỹ thuật AEO đã áp dụng

- Nội dung hỏi đáp, câu trả lời ngắn 1-3 câu.
- Cấu trúc heading chuẩn H1 -> H2 -> H3.
- FAQ có thể mở/đóng và tìm kiếm để người dùng truy cập nhanh câu trả lời.
- FAQ Schema (`FAQPage`) trong `faq.html`.

## Kỹ thuật AIEO đã áp dụng

- WebSite Schema trong `index.html`.
- Organization Schema trong `about.html`.
- Meta title + meta description riêng cho từng trang.
- `robots.txt` và `sitemap.xml` để hỗ trợ crawl/index.
- Liên kết nội bộ rõ ràng giữa 3 trang.

## Cách chạy website

Mở trực tiếp `index.html` hoặc chạy local server:

```bash
python -m http.server 5500
```

Mở: `http://localhost:5500`

## Deploy GitHub Pages

1. Upload tất cả file lên repo GitHub.
2. Vào `Settings` -> `Pages`.
3. Chọn:
- Source: `Deploy from a branch`
- Branch: `main`
- Folder: `/ (root)`
4. Save và chờ 1-3 phút.
5. Truy cập:

`https://trqutonn-jpg.github.io/aeo-aieo-demo/`

## Cấu trúc thư mục

- `index.html`
- `faq.html`
- `about.html`
- `style.css`
- `robots.txt`
- `sitemap.xml`
- `README.md`
