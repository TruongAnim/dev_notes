# Linux

## Common cmd

[Command instruction](https://www.hostinger.com/tutorials/linux-commands)

```Start wsl with specific user: wsl --user truonganim```

<details>
  <summary>Shortcut</summary>

>ctrl+A: Đưa pointer về đầu lệnh  
>ctrl+E: Đưa pointer về cuối lệnh  
>sudo apt install nodejs: Cài thêm package nào đó  
>sudo chỉ là để lấy quyền root  

</details>

<details>
  <summary>apt</summary>

>sudo apt update: lấy thông tin các package (phần mềm)  
>sudo apt upgrade: update các package lên bản mới  
>sudo apt install nodejs: Cài thêm package nào đó  
>sudo chỉ là để lấy quyền root  

</details>

<details>
  <summary>ls</summary>

>ls: Show all folders and files  
>ls -l: Show details  
>File ẩn thì bắt đầu bằng dấu .
>ls -a: show cả các file ẩn

</details>

<details>
  <summary>cd</summary>

>cd folder: đi vào thư mục con  
>cd tab tab: đang định đi vào nhưng k nhớ tên thư mục. Tab tab để nó hiện gợi ý lên.  
>cd folder tab: đang gõ tên thư mục thì gõ tab để nó auto điền nốt.
>cd ..: Back ra thư mục cha  
>cd -: Back ra thư mục trước đó
>cd /: Back ra thư mục root
>cd /home/truong: Nhảy trực tiếp vào thư mục tính từ root mà không phải tính từ thư mục hiện tại.  
>cd: Nhảy ra thư mục account đang đăng nhập.

</details>

<details>
  <summary>mkdir rmdir</summary>

>mkdir folder: Tạo folder với tên  
>mkdir -p folder/sub: Tạo folder và các folder con  
>rmdir folder: Xóa thư mục trống
>rm -r folder: Xóa cả thư mục và các con của nó
>rm test.html: Xóa file  

</details>

<details>
<summary>touch</summary>

>touch test.html: Tạo ra file  

</details>

<details>
<summary>vim editor</summary>

>vim: Mở vim  
>:q: Thoát vim  
>vim test.html: Tạo ra file giống touch hoặc mở file có sẵn  
>Đang mở file để sửa thì ấn insert  
>Để thôi sửa thì ấn ESC  
>Để thoát và không lưu thì :q!  
>Để lưu thì :w  
>Để lưu và thoát thì :wq or :x  

</details>

<details>
<summary>cat</summary>

>cat file.txt: print ra nội dung file  
>cat file1.txt file2.txt: print ra nội dung nhiều file
>cat file1.txt file2.txt > output.txt: đưa nội dung vào output thay vì in ra.  

</details>

<details>
<summary>echo</summary>

>echo "Hello world" > file.txt: đưa nội dung vào file tương tự như cat.  
>Lưu ý là nó sẽ ghi đè chứ không ghi tiếp.  
>Để ghi tiếp vào cuối file thì đổi dấu '>' thành '>>'  
</details>

<details>
<summary>tail</summary>

>tail file.txt: đọc ra nội dung file giống cat nhưng chỉ đọc 10 dòng cuối.  
>tail -n 20 file.txt: tăng số lượng dòng đọc ra lên  
>tail -f file.txt: Đọc ra nội dung file và update realtime mỗi khi file thay đổi. Ctrl+C để thoát.  
</details>

<details>
<summary>cp</summary>

>cp file.txt new_file.txt: copy ra thêm 1 file mới
>cp file.txt folder/: copy vào thư mục con (có thể k cần tên file)  
>cp -r folder other/abc: copy cả thư mục
</details>

<details>
<summary>mv</summary>

>mv thì giống cp nhưng thay vì copy thì là move
</details>

<details>
<summary>man</summary>

>man [command]: xem intruction về lệnh linux.  
</details>

<details>
<summary>wget</summary>

>wget <https://image.com/1.png>: tải file về thư mục hiện tại  
</details>

<details>
<summary>ps</summary>

>ps aux: Lấy danh sách các tiến trình đang chạy  
>kill id: Terminate một process đang chạy  
>kill -9 id: Kill một process đang chạy (Force close)  
</details>

<details>
<summary>ping</summary>

>ping <url or ip>: Thử kết nối đến server xem còn sống không?  
</details>

<details>
<summary>uname</summary>

>uname -a: Lấy ra phiên bản của os đang chạy  
</details>

<details>
<summary>passwd</summary>

>passwd:  Đổi mật khẩu của user hiện tại  
</details>

<details>
<summary>top</summary>

>top: Lấy ra chi tiết process giống task manager  
>htop: Cũng thế nhưng fancy hơn  
</details>

<details>
<summary>df</summary>

>df -h: Lấy ra thông tin các disk trong máy  
</details>

<details>
<summary>free</summary>

>free -h: Lấy ra thông tin về ram  
</details>
