#                                                                         Git-Tutorial
---

## Lưu ý:

- Bạn phải cài đặt git trên máy tính 
- Có thể sử dụng Github Desktop dễ dàng hơn cách truyền thống.
- [Cách cài đặt Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
- [Tải Github Desktop](https://desktop.github.com/)

---
## Bắt đầu cài đặt và sử dụng Git

- Sau khi đã cài đặt Git :
### Bạn sử dụng 2 lệnh sau trên Terminal:
  ```sh
git config --global user.name "username"
git config --global user.email "email"
  ```
  Thay đổi 'username' ( tùy ý )
  Và 'email' là email github của bạn.
### Cài đặt SSH trên máy :
- [Tham Khảo Tại Đây](https://blog.nguyenary.dev/cach-tao-ssh-key-va-su-dung-no-voi-gitlab-va-github.html)
- Sau khi setup xong hết ví dụ :
![image](https://user-images.githubusercontent.com/70010376/229276698-a19b9c0c-1f62-4d29-aff1-84bd14b3713a.png)
- Bạn đã hoàn thành gần như 90%
---
## Sử dụng Github trên VSCODE:
- Bạn tạo 1 dự án sau đó copy mã SSH của dự án đó .
- Bạn dùng lệnh 'cd' để di chuyển đến thư mục bạn muốn
- Dùng lệnh :
```sh
git clone (mã SSH vừa copy ở dự án)
```
- Vậy là đã Pull dự án về.
- Sau khi hoàn thành code bên trong hoặc tạm thời bạn ấn commit ở góc trái VSCODE
![image](https://user-images.githubusercontent.com/70010376/229277235-a9dcdede-4545-4732-90ea-7951e1b5672f.png)
- Rồi di chuyển lên nút '---' phía trên và ấn Push thế là đã cập nhật file trên Github.
- Lưu ý trước khi muốn tiếp tục nên dùng Pull ở '---' rồi hoàn thành xong thì Push.
## Cách thêm teamwork vào dự án trên Github:
- Truy cập dự án -> Setting -> Collaborators -> Add People.
---
#END

