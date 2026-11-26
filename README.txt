TRAVEL ENGLISH — bản chạy thử
Cần Python 3.10+; không cần cài thư viện ngoài.
1. Giải nén ZIP, mở Terminal trong thư mục travel-english.
2. Chạy python app.py (Windows có thể dùng py app.py).
3. Mở http://127.0.0.1:8000 trên trình duyệt.
4. Để bật AI thật, trước khi chạy máy chủ, đặt biến môi trường OPENAI_API_KEY bằng khóa API của bạn. Windows PowerShell: $env:OPENAI_API_KEY="YOUR_KEY". macOS/Linux: export OPENAI_API_KEY="YOUR_KEY". Không gửi khóa cho người khác. Có thể đặt OPENAI_MODEL để đổi model mặc định gpt-4.1-mini. API tính phí riêng.
Micro và giọng đọc phụ thuộc trình duyệt, quyền micro, kết nối và giọng có sẵn. Dùng Chrome hoặc Edge để thử. Nhận diện chỉ hiển thị văn bản, không chấm âm vị. Tiến độ lưu trên trình duyệt, không đồng bộ thiết bị.
Máy chủ chỉ nghe localhost. Để dùng trên điện thoại qua Internet cần triển khai HTTPS, thêm xác thực, giới hạn yêu cầu, bảo vệ khóa và kiểm soát chi phí. Không công khai máy chủ mẫu trực tiếp. Hội thoại gửi văn bản tới API; nhận diện giọng nói có thể do nhà cung cấp trình duyệt xử lý.
