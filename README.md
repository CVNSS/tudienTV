# CVNSS4.0 Core Dictionary — GitHub Pages Safe

Bản này sửa lỗi trắng trang khi đưa lên GitHub Pages bằng cách tách file:

- `index.html`: UI nhẹ, chỉ chứa HTML/CSS.
- `assets/data.js`: dữ liệu từ điển không nén runtime.
- `assets/app.js`: logic tìm kiếm/copy, có fallback báo lỗi nếu dữ liệu không nạp.
- `.nojekyll`: tắt Jekyll để GitHub Pages phục vụ asset nguyên trạng.
- `404.html`: fallback cùng UI.

Cách deploy: copy toàn bộ nội dung thư mục này lên root repo `tudientiengviet`, không chỉ copy riêng `index.html`.

Footer: Long Ngo thiết kế | Dự án CVNSS4.0 | Tài trợ NNC Trần Tư Bình
