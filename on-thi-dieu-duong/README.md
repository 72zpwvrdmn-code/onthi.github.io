# Ôn thi Điều dưỡng hạng III

Bộ website/PWA ôn tập từ đề cương Word.

## Cách dùng trên máy tính
- Mở qua máy chủ web nội bộ để app tải được dữ liệu câu hỏi.
- Trong phiên Codex hiện tại, server test đang chạy ở: http://127.0.0.1:8787/

## Cách dùng trên iPhone/iPad cùng Wi-Fi
- Đảm bảo iPhone/iPad và máy tính cùng mạng Wi-Fi.
- Mở Safari và thử địa chỉ: http://172.16.23.252:8787/
- Nếu không vào được, Windows Firewall hoặc mạng Wi-Fi có thể đang chặn truy cập từ thiết bị khác.

## Cách dùng mọi lúc mọi nơi
- Upload toàn bộ thư mục này hoặc file on-thi-dieu-duong.zip lên hosting tĩnh như Netlify, Vercel, GitHub Pages hoặc Firebase Hosting.
- Sau khi có link HTTPS, mở link trên Safari iPhone/iPad.
- Chọn Share > Add to Home Screen để dùng như app.
- Sau lần mở đầu, app có service worker để lưu cache các file cơ bản.

## Tính năng
- 94 câu có đáp án được trích từ đề cương.
- Mỗi lần tạo đề sẽ trộn câu hỏi và trộn thứ tự đáp án.
- Chọn số câu: 5, 10, 15, 20, 25, 30, 40, 50 hoặc tất cả.
- Chấm điểm, hiển thị đúng/sai và giải thích đối chiếu đáp án.
- Có tùy chọn làm lại đề, sang đề khác, hoặc kết thúc ôn.