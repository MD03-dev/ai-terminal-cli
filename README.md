# 🤖 AI Terminal CLI

> Trợ lý AI chạy trực tiếp trên dòng lệnh (Terminal). Hỏi đáp mọi thứ về code, Linux, sửa lỗi mà không cần mở trình duyệt!

![AI](https://img.shields.io/badge/AI-Powered-blueviolet)
![Termux](https://img.shields.io/badge/Termux-Ready-green)
![License](https://img.shields.io/badge/license-MIT-blue)

## Tính năng
- Hỏi đáp trực tiếp trên Terminal.
- Đọc file log, báo lỗi và gợi ý cách sửa.
- Dịch thuật, giải thích đoạn code lạ.
- Hoạt động mượt mà trên Android (Termux), Linux, macOS.

## Cài đặt
Yêu cầu: curl, jq và một API Key (Ví dụ: lấy miễn phí tại console.groq.com).

Bước 1: Clone repo và cấp quyền
git clone https://github.com/MD03-dev/ai-terminal-cli.git
cd ai-terminal-cli
chmod +x ask
cp ask $PREFIX/bin/

Bước 2: Cài đặt API Key và sử dụng
export AI_API_KEY="your_api_key_here"
ask "Làm sao để đổi tên hàng loạt file trong linux?"

## Đóng góp
Mọi ý tưởng và PR đều được hoan nghênh. Đừng quên để lại 1 Star ⭐!
