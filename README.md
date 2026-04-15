# Arduino LM35 Temperature Monitor

## 📖 Mô tả
Dự án đo nhiệt độ bằng cảm biến LM35, hiển thị dữ liệu qua Serial và định dạng JSON để dễ dàng tích hợp với các ứng dụng IoT.

## ✨ Tính năng
- Đọc dữ liệu từ nhiều kênh cảm biến LM35.
- Xuất dữ liệu dưới dạng JSON.
- Tương thích với Arduino IDE.

## 🔧 Phần cứng
| Thiết bị        | Số lượng | Ghi chú              |
|-----------------|----------|----------------------|
| Arduino Uno     | 1        | Board chính          |
| LM35            | 3        | Cảm biến nhiệt độ    |
| Dây jumper      | Nhiều    | Kết nối              |

## 🚀 Hướng dẫn sử dụng
1. Clone repo về máy.
2. Mở project bằng Arduino IDE.
3. Upload code lên Arduino.
4. Mở Serial Monitor để xem dữ liệu JSON.

## 📂 Cấu trúc thư mục
Arduino_LM35_TempMonitor/
├── src/           # Mã nguồn chính
├── docs/          # Tài liệu hướng dẫn
└── README.md      # Giới thiệu dự án
## 👥 Thành viên nhóm
- SV A – Phụ trách đọc dữ liệu cảm biến.
- SV B – Phụ trách định dạng JSON và giao tiếp.
- SV C – Tích hợp và kiểm thử.