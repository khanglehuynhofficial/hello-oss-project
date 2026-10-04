cd ~/hello-oss-doc

cat << 'EOF' > CONTRIBUTING.md
# Hướng dẫn đóng góp (Contributing Guide)

Cảm ơn bạn đã quan tâm và muốn đóng góp cho dự án **Hello-OSS-PROJECT**! Để đảm bảo dự án hoạt động nhất quán, vui lòng đọc và làm theo các hướng dẫn bên dưới.

## Cách báo lỗi (Issue)
Nếu bạn phát hiện ra lỗi hoặc muốn đề xuất tính năng mới, hãy tạo một **Issue** trên GitHub theo các bước:
1. Truy cập tab **Issues** của repository này.
2. Nhấn nút **New Issue**.
3. Mô tả rõ ràng:
   - Lỗi xảy ra là gì? (Đính kèm ảnh chụp màn hình hoặc log lỗi nếu có).
   - Các bước để tái hiện lại lỗi.
   - Kết quả mong muốn và kết quả thực tế nhận được.

## Cách gửi Pull Request (PR)
Để đóng góp mã nguồn hoặc sửa đổi tài liệu, vui lòng thực hiện quy trình sau:
1. **Fork** repository này về tài khoản cá nhân của bạn.
2. **Clone** repository đã fork về máy và tạo một nhánh (branch) mới:
   ```bash
   git checkout -b feature/ten-tinh-nang-moi
   # Hoặc nếu sửa lỗi:
   git checkout -b fix/ten-loi
   ```
3. Tiến hành chỉnh sửa code hoặc tài liệu trên máy của bạn.
4. Commit và Push nhánh đó lên GitHub cá nhân của bạn.
5. Truy cập repository gốc này, bạn sẽ thấy gợi ý tạo **Pull Request**. Nhấn vào và mô tả chi tiết những gì bạn đã thay đổi, sau đó gửi yêu cầu review.

## Quy tắc đặt tên Commit
Chúng tôi áp dụng chuẩn **Conventional Commits** để lịch sử chỉnh sửa rõ ràng. Tin nhắn commit (Commit Message) nên tuân theo cấu trúc: `<type>: <mô tả ngắn bằng tiếng Anh hoặc tiếng Việt>`

**Các loại (`type`) thông dụng:**
- `feat`: Thêm một tính năng mới (ví dụ: `feat: add clear screen option`).
- `fix`: Sửa một lỗi (ví dụ: `fix: correct typo in print statement`).
- `docs`: Chỉnh sửa tài liệu như README, CONTRIBUTING (ví dụ: `docs: update build instructions`).
- `style`: Thay đổi định dạng code (khoảng trắng, dấu chấm phẩy) không làm thay đổi logic code.

**Ví dụ commit hợp lệ:**
```bash
git commit -m "docs: add README and CONTRIBUTING documentation"
```
EOF
