# Domain

## Mua domain

[Mua từ tenten](https://tenten.vn)

<details>
  <summary>Setup</summary>

>B1: Tạo cloudflare account.  
>B2: Cài đặt NS của domain về cloudflare server.  
>B3: Vào Cloudflare-> DNS:
>B4: setup A stream.io.vn 216.24.57.1 để khi truy cập vào domain thì sẽ được điều hướng tới server của mình  
>B5: setup CNAME www stream.io.vn để khi người dùng thêm www vào thì ta cũng điều hướng tới stream.io.vn  
>B6: Nếu ta có nhiều server với ip khác nhau. Có thể cài sub domain cho từng server. (ví dụ CNAME info 64.1.57.12) (Ghi info là được, không cần viết cả domain)  
B7: Nếu có nhiều project chạy chung trên 1 server. Có thể config cho mỗi sub domain 1 project. Cứ trỏ tất sub domain về domain. Rồi nginx sẽ điều tướng từng sub domain sang các port khác nhau.  

</details>

<details>
  <summary>Lấy chứng chỉ ssl/tls</summary>

>B1: vào Cloudflare set SSL/TLS encryption mode is Full
>B2: Vào Edge certificates -> Always use https -> Enable

</details>
