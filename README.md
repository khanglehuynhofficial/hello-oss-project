# hello-oss-project
Một dự án mẫu viết bằng ngôn ngữ C nhằm mục đích làm quen với quy trình mã nguồn mở (OSS).

## Giới thiệu ngắn gọn về dự án
Mô phỏng cấu trúc quản lý mã nguồn tiêu chuẩn kết hợp với hệ thống tài liệu kiểm soát cấu trúc pháp lý bản quyền dựa trên giấy phép Apache 2.0.

## Mục tiêu của dự án
- Thực hành thành thạo các thao tác lệnh trên nền tảng Git và đám mây GitHub.
- Chuẩn hóa hệ thống tài liệu kỹ thuật cốt lõi (`README.md`, `CONTRIBUTING.md`) cho sản phẩm phần mềm.
- Làm quen và áp dụng quy trình đóng góp mã nguồn thông qua luồng Pull Request.

## Hướng dẫn build và chạy chương trình
Hệ thống yêu cầu máy tính cài đặt sẵn trình biên dịch C (`gcc` hoặc `clang`).

### Các bước thực hiện:
1. Di chuyển vào thư mục dự án và khởi tạo mã nguồn thật `main.c`:
```bash
cat << 'EOF' > main.c
#include <stdio.h>
int main() {
    printf("Hello Open Source\n");
    return 0;
}
EOF
```
2. Biên dịch chương trình (Build):
```bash
gcc main.c -o hello
```
3. Chạy chương trình:
```bash
./hello
```
**Kết quả kỳ vọng:** `Hello Open Source`