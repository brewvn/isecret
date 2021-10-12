# Cài đặt môi trường phát triển react-native trên windows

## Cài đặt các phần mềm chính
- Nodejs 14 (lts), cài độc lập, không sử dụng Chocolatey. Sử dụng các tùy chọn mặc định, không chọn cài các tool bổ sung.
Nên cài nodejs vào thư mục không có dấu cách ở đường dẫn, ví dụ: E:\nodejs. 
Cần đảm bảo thư mục cache cũng không có dấu cách trong đường dẫn. Nếu cần thì đổi với lệnh: npm config set cache "E:\nodejs\npm-cache" --global.
Cần đảm bảo người dùng hiện thời có đủ quyền trên thư mục cache này.
- Jdk 11 (lts), cài độc lập, không sử dụng Chocolatey.
- Android studio. Khi cài sdk cần chọn folder không có dấu cách ở đường dẫn, ví dụ: "E:\Android\Sdk".
Cài đặt biến môi trường ANDROID_HOME và bổ sung vào PATH: %ANDROID_HOME%\platform-tools.


## Tạo một project mới
- Tạo folder chứa dự án: D:\Working\Personal\iSecret
- Tạo dự án mobile tên i5ecret, được thư mục project i5ecret trong thư muc iSecret:
```
npx react-native init i5ecret --template react-native-template-native-base-typescript
```

