# Nodejs

## Environment

<details>
  <summary>How to run it?</summary>

> Để chạy 1 file js thì ta cần gõ node filename.js  
> Nhưng trong node project thì có thể dùng npm.  
> Ở package.json cài đặt lệnh ở script. npm start là mặc định  
> Thêm lệnh thì dev thì cần npm run dev  
> nodemon dùng để auto run lại server khi sửa code  

![image info](1.PNG)

</details>

## Syntax

<details>
  <summary>Check undefined</summary>

> Kiểm tra 1 biến có undefined: name === undefined  
> Kiểm tra 1 object property có undefined: user.hasOwnProperty('name')  

</details>

## Router

<details>
  <summary>Get query</summary>

> localhost:3000/post?start=1&limit=10  
> start và limit là query.  
> Lấy ra bằng cách gọi req.query  

</details>

<details>
  <summary>Get param</summary>

> localhost:3000/post/:postId/comment/:commentId  
> postId và commentId là param.  
> Lấy ra bằng cách gọi req.params  

</details>

<details>
  <summary>Get body</summary>

> {
    "title": "In German City",
    "type": "video"
}  
> body sử dụng json  
> Lấy ra bằng cách gọi req.body

![image info](2.PNG)

</details>
