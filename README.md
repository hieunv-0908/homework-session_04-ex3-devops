# Báo cáo Bài tập 3: Cấu hình xác thực SSH và Đẩy dự án lên GitHub

## 1. Thông tin học viên
- **Họ và tên:** Nguyễn Văn A
- **Email cấu hình:** nn650370@gmail.com
- **Đường dẫn Repository GitHub:** https://github.com/YOUR_GITHUB_USERNAME/YOUR_REPOSITORY_NAME

---

## 2. Quá trình thực hiện

### Bước 1: Khởi tạo cặp khóa SSH bằng thuật toán Ed25519
Sử dụng thuật toán `ed25519` để khởi tạo cặp khóa xác thực an toàn:
```bash
ssh-keygen -t ed25519 -C "nn650370@gmail.com"