## Ứng Dụng Hiển Thị Thời Gian (Capacitor)

Ứng dụng React + Capacitor hiển thị thời gian hiện tại và hỗ trợ:
- Thông báo cục bộ (Local Notifications)
- Chia sẻ thời gian (Share API)
- Chụp màn hình ứng dụng

### Cách Cài Đặt & Chạy Ứng Dụng

```sh
# Clone dự án
git clone https://github.com/your-repo/time-app.git
cd time-app

# Cài đặt dependencies
npm install

# Thêm nền tảng Android
npx cap add android

# Build & đồng bộ
npm run build
npx cap sync

# Chạy trên Android
npx cap open android
```

Mở **Android Studio** và nhấn **Run** để chạy ứng dụng.

### Công Nghệ Sử Dụng
- React + Capacitor  
- Capacitor Plugins: Local Notifications, Share API, Screenshot  


