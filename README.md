# 🌐 Website Portfolio - Nhóm 3

> **Báo cáo thực tập tốt nghiệp** - Đề tài: Quản lý mã nguồn với Git: Sử dụng Branching, Merging và Pull Request trên GitHub.
> **Trường Cao đẳng Nghề Thành phố Hồ Chí Minh** (Khoa CNTT - Nghề UDPM).

---

## 👥 Thành Viên Thực Hiện (Nhóm 3)
Dưới đây là danh sách thành viên và vai trò phân nhiệm trong dự án phát triển Website Portfolio:

| STT | Họ và Tên | Username GitHub | Vai Trò & Nhiệm Vụ Kỹ Thuật |
| :--- | :--- | :--- | :--- |
| 1 | **Nguyễn Phúc Hoài Nam** | [@binbintd667](https://github.com/binbintd667) | **Trưởng nhóm:** Khởi tạo tổ chức, phân quyền Collaborators, kiểm duyệt và hợp nhất mã nguồn. |
| 2 | **Nguyễn Nhựt Hào** | [@eds3lg](https://github.com/eds3lg) | **Developer:** Thiết lập bộ khung cấu trúc HTML/CSS ban đầu cho giao diện trang chủ (`feature-ui-hao`). |
| 3 | **Phạm Bình Minh Hiếu** | [@phambinhminhhieu1-commits](https://github.com/phambinhminhhieu1-commits) | **Developer:** Tối ưu hóa hiển thị Responsive tương thích thiết bị di động (`feature-responsive-hieu`). |
| 4 | **Nguyễn Anh Khoa** | [@khoaqtth](https://github.com/khoaqtth) | **Developer:** Tối ưu dung lượng hình ảnh sang `.webp` và cấu hình các thẻ meta SEO On-page (`feature-optimize-khoa`). |
| 5 | **Nguyễn Hà Minh Long** | [@minhlong013010](#) | **Tester / Project Manager:** Kiểm thử giao diện, phát hiện và phối hợp xử lý xung đột mã nguồn (Merge Conflict). |

---

## 🚀 Công Nghệ Sử Dụng
*   **Mã nguồn Website:** HTML5, CSS3, JavaScript.
*   **Quản lý phiên bản:** Git (Git CLI / Git Bash).
*   **Nền tảng cộng tác:** GitHub (Repository, Collaborators, Pull Requests, Merging).

---

## 🛠️ Quy Trình Phối Hợp Làm Việc Kênh Git (Git Workflow)

Dự án tuân thủ nghiêm ngặt quy trình quản lý mã nguồn phân nhánh để đảm bảo an toàn cho nhánh chính `main`:

### 1. Khởi tạo và Đồng bộ cấu trúc (Thành viên Hào)
```bash
git init
git add .
git commit -m "Khởi tạo website Portfolio"
git remote add origin [https://github.com/binbintd667/Website-Portfolio.git](https://github.com/binbintd667/Website-Portfolio.git)
git branch -M main
git push -u origin main
