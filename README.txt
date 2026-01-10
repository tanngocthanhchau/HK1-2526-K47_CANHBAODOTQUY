Tân ngọc thanh châu _ MSSV: 2123060038
Hoàng ngọc bộ _ MSSV:2123060025

Khoa: Điện – Điện tử

Trường: Cao Đẳng Công Thương TP.HCM

Học kỳ:  Học kỳ 1 – Năm học 2025–2026

GVHD: Nguyễn Kim Suyên

###################################

HỆ THỐNG THEO DÕI SỨC KHỎE THÔNG MINH (IoT)

🧠 Mô tả ngắn dự án

Dự án xây dựng một hệ thống theo dõi sức khỏe thời gian thực sử dụng ESP32 kết hợp với các cảm biến sinh học và ứng dụng Flutter.
Hệ thống có khả năng:

Đo nhịp tim (BPM) và nồng độ oxy trong máu (SpO2)

Nhận diện trạng thái vận động (đứng yên, đi bộ, chạy, ngã)

Cảnh báo khẩn cấp qua nút SOS, còi và LED

Truyền dữ liệu real-time qua WebSocket lên điện thoại

Phù hợp cho người cao tuổi hoặc người cần theo dõi sức khỏe từ xa.



▶️ Hướng dẫn chạy code / app
1️⃣ Phần cứng

ESP32 Dev Kit

MAX30100 (nhịp tim & SpO2)

MPU6050 (gia tốc – phát hiện ngã)

OLED 0.96" I2C

LED + Buzzer + Button SOS

Kết nối I2C

SDA → GPIO 21

SCL → GPIO 22

2️⃣ Chạy code ESP32

Mở Arduino IDE

Cài thư viện:

Adafruit_MPU6050

Adafruit_SSD1306

MAX30100_PulseOximeter

WebSocketsServer

Nạp code vào ESP32

ESP32 phát WiFi:

SSID: ESP32_TheoDoiSucKhoe

📊 Kết quả chính

Nhịp tim & SpO2 hiển thị real-time

Phát hiện ngã dựa trên gia tốc G

Thời gian phản hồi SOS: < 100ms

Giao diện Flutter trực quan (Dashboard + biểu đồ)

OLED hiển thị trực tiếp trên thiết bị
Wifi: ESP32_TheoDoiSucKhoe
Password: 12345678
