# 🤖 AI Terminal CLI

> Trợ lý AI chạy trực tiếp trên dòng lệnh (Terminal). Hỏi đáp mọi thứ về code, Linux, sửa lỗi mà không cần mở trình duyệt!

![AI](https://img.shields.io/badge/AI-Powered-blueviolet)
![Termux](https://img.shields.io/badge/Termux-Ready-green)
![License](https://img.shields.io/badge/license-MIT-blue)

## ✨ Tính năng
- Hỏi đáp trực tiếp trên Terminal mà không cần mở web.
- Đọc file log, báo lỗi và gợi ý cách sửa code cực nhanh.
- Dịch thuật, giải thích đoạn code lạ.
- Hoạt động mượt mà trên Android (Termux), Linux, macOS.

## ⚡ Hướng dẫn cài đặt (Cầm tay chỉ việc)

**Bước 1: Cài đặt các tool cần thiết**
Mở Termux và chạy lệnh sau (nếu dùng Linux thì dùng lệnh sudo apt install curl jq):
pkg install curl jq -y

**Bước 2: Tải tool về máy**
git clone https://github.com/MD03-dev/ai-terminal-cli.git
cd ai-terminal-cli
chmod +x ask
cp ask $PREFIX/bin/

**Bước 3: Lấy API Key (Miễn phí)**
Tool này sử dụng AI của Groq (tốc độ siêu nhanh, miễn phí).
1. Truy cập: https://console.groq.com
2. Đăng nhập bằng tài khoản Google.
3. Bấm Create API Key, đặt tên bất kỳ và copy chuỗi key đó lại.

**Bước 4: Chạy thử**
Gán API Key vào biến môi trường (thay key_cua_ban bằng key vừa copy):
export AI_API_KEY="key_cua_ban"

Giờ thì hỏi AI bất cứ điều gì:
ask "Làm sao để nén file trong linux?"
ask "Giải thích đoạn code này giúp tôi: print('Hello')"

## 🤝 Đóng góp
Mọi ý tưởng và PR đều được hoan nghênh. Đừng quên để lại 1 Star ⭐ nếu bạn thấy tool hữu ích!
