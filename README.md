# Hướng dẫn cách cài đặt Git và sử dụng dịch vụ Github

### ✍️: [toantc1024](https://github.com/toantc1024/)

Git là một hệ thống kiểm soát phiên bản theo dõi các phiên bản của tệp. Chúng ta thường sử dụng nó để có thể phát triển dự án chung với nhau dễ dàng và thuận tiện hơn.

Github là một dịch vụ cung cấp kho lữu trữ mã nguồn Git trên đám mây.

`Ghi chú`: `Git != Github`

## Chuẩn bị trước khi tiến hành

- Tạo tài khoản Github và đăng nhập thành công
- Tải Git về máy của bạn [tại đây](https://git-scm.com/download/), nếu bạn chưa hiểu cách cài đặt có thể xem tại link sau nhe: [Windows](https://funix.edu.vn/chia-se-kien-thuc/cai-dat-git-va-git-bash-windows/) [Mac OS](https://www.codehub.com.vn/Huong-dan-cai-dat-Git-tren-macOS)

## Cấu hình Git

Giống như một cái máy Laptop mới mua bạn phải cấu hình tên của bạn, giống như vậy Git sau khi cài đặt chúng ta cần cấu hình tên và email của chúng ta.

Đầu tiên, bạn mở Git Bash

![alt text](image-1.png)

Để xem các cấu hình hiện tại bạn dùng lệnh

```sh
git config --list
```

![alt text](image-2.png)

Bây giờ chúng ta sẽ tiến hành cấu hình tên và email của chúng ta bằng 2 lệnh sau

```sh
git config --global user.name 'ten_cua_ban'
# Ví dụ: git config --global user.name 'Newbie Coder'
git config --global user.email 'email_cua_ban'
# Ví dụ: git config --global user.email 'tha
```
