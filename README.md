# MeowLingo Android

Ứng dụng Android thử nghiệm “phiên dịch” tiếng mèo ↔ người theo hướng giải trí, có phân tích tín hiệu âm thanh cơ bản và tạo mẫu tiếng mèo tổng hợp.

## Microphone
App xin quyền `RECORD_AUDIO` và cấp quyền thu âm cho WebView ở origin nội bộ `https://meowlingo.local`, tránh lỗi `content://` / insecure-origin khi mở HTML trực tiếp trên Android.

## Build APK
GitHub Actions sẽ tự build khi push lên nhánh `main`, hoặc có thể chạy thủ công workflow **Build APK**.

APK debug nằm trong artifact **MeowLingo-APK** và đường dẫn build là `app/build/outputs/apk/debug/app-debug.apk`.

> Lưu ý: phần “dịch tiếng mèo” chỉ là ước đoán vui dựa trên cao độ, âm lượng và thời lượng, không phải hệ thống giải mã ngôn ngữ động vật đã được khoa học xác nhận.
