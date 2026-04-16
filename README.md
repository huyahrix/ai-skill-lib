# Copilot Skill Library

Thư viện mẫu prompt và skill phục vụ các tác vụ làm việc với GitHub Copilot.

## Mục tiêu

Repo này dùng để lưu trữ các ví dụ prompt thực tế, giúp:

- Tái sử dụng các mẫu prompt hiệu quả
- Chuẩn hóa cách nhập yêu cầu cho Copilot
- Tăng tốc các tác vụ viết nội dung kỹ thuật hoặc nghiệp vụ

## Cấu trúc hiện tại

```text
examples/
└── pr-description-to-upgrade-email.prompt.md
```

## Ví dụ hiện có

### 1. PR description to upgrade email

File: `examples/pr-description-to-upgrade-email.prompt.md`

Prompt này hỗ trợ chuyển nội dung mô tả pull request thành email thông báo nâng cấp gửi cho khách hàng hoặc đội vận hành.

Phù hợp cho các trường hợp:

- Tổng hợp nội dung fix lỗi
- Liệt kê cải tiến và tính năng mới
- Chuẩn hóa email thông báo release/nâng cấp

## Cách sử dụng

1. Mở file prompt mẫu trong thư mục `examples`
2. Thay nội dung đầu vào bằng thông tin PR thực tế
3. Gửi prompt cho GitHub Copilot Chat
4. Kiểm tra và chỉnh sửa lại nội dung đầu ra nếu cần

## Định hướng phát triển

Trong tương lai, repo có thể bổ sung thêm:

- Prompt viết release note
- Prompt tóm tắt pull request
- Prompt sinh email nội bộ
- Các skill chuyên biệt cho quy trình làm việc nhóm

## Đóng góp

Bạn có thể mở rộng repo bằng cách:

- Thêm prompt mới vào thư mục `examples`
- Đặt tên file rõ ràng theo mục đích sử dụng
- Ghi kèm ví dụ input/output để dễ tái sử dụng

## License

Nội bộ / tùy chỉnh theo nhu cầu sử dụng của nhóm.
