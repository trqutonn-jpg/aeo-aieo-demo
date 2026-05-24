# English Learning Hub

Website tĩnh đơn giản bằng HTML, CSS, JavaScript cho chủ đề học tiếng Anh dành cho học sinh, sinh viên.

## 1. Mục tiêu project

- Cung cấp nội dung học tiếng Anh rõ ràng, dễ áp dụng.
- Trả lời nhanh các câu hỏi thường gặp.
- Tối ưu để công cụ tìm kiếm và hệ thống AI dễ hiểu nội dung.

## 2. Kỹ thuật AEO/AIEO đã áp dụng

### AEO
- Nội dung dạng hỏi đáp.
- Câu trả lời ngắn, rõ ràng.
- Cấu trúc heading hợp lý với H1, H2, H3.
- Thêm FAQ Schema (`FAQPage`) trong `faq.html`.

### AIEO
- Thêm WebSite Schema trong `index.html`.
- Thêm Organization Schema trong `about.html`.
- Nội dung rõ nghĩa, không nhồi từ khóa.
- Có `robots.txt` và `sitemap.xml` để hỗ trợ crawl/index.
- Mỗi trang có meta title và meta description riêng.

## 3. Cách chạy website

Mở trực tiếp `index.html` bằng trình duyệt, hoặc dùng local server tĩnh:

```bash
# Python
python -m http.server 5500
```

Sau đó truy cập `http://localhost:5500`.

## 4. Cách deploy lên GitHub Pages

1. Push toàn bộ file lên repo GitHub.
2. Vào `Settings` -> `Pages`.
3. Ở `Build and deployment`:
- Source: `Deploy from a branch`
- Branch: `main`
- Folder: `/ (root)`
4. Nhấn `Save` và chờ 1-3 phút.
5. Mở link Pages:

`https://trqutonn-jpg.github.io/aeo-aieo-demo/`

## 5. Cấu trúc thư mục

- `index.html`
- `faq.html`
- `about.html`
- `style.css`
- `robots.txt`
- `sitemap.xml`
- `README.md`
