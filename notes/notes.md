# Dev Notes

## Android studio

<details>
  <summary>Not auto open the last project</summary>

>File -> Settings -> Appearance & Behaviour -> System Settings then you have a checkbox Reopen last project on startup

![image info](1.PNG)

</details>

<details>
  <summary>Bỏ cái frame của máy ảo</summary>

![image info](2.PNG)

</details>

<details>
  <summary>Đường dẫn của java mặc định</summary>

> C:\Program Files\Android\Android Studio\jbr\bin  
> Lưu ý có \bin

</details>

<details>
  <summary>Cài đường dẫn java home</summary>

>C:\Program Files\Android\Android Studio\jbr
> Lưu ý không có \bin
![image info](3.PNG)
</details>

<details>
  <summary>Config máy ảo vào localhost</summary>

> Setting máy ảo như trong ảnh  
> Đổi endpoint về local host: <http://10.0.2.2>:[PORT]/
![image info](4.PNG)
</details>

## Git

<details>
  <summary>warning: in the working copy of 'pubspec.lock', LF will be replaced by CRLF the next time Git touches it</summary>

> git config --global core.autocrlf true  
> Sau đó cứ commit lên  
> Người khác lấy về sẽ thành crlf  
> Mình bỏ local commit rồi pull lại cũng thành crlf

</details>
