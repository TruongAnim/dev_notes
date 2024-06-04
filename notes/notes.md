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

# Flutter

<details>
  <summary>Cài flutter bằng fvm</summary>

> Cài choco  
> Cài fvm qua choco
> Danh sách flutter version: fvm list  
> Sử dụng flutter version cho project hiện tại: fvm use 3.22.0  
> Sử dụng flutter version cho global: fvm global 3.22.0
</details>

# Git

<details>
  <summary>warning: in the working copy of 'pubspec.lock', LF will be replaced by CRLF the next time Git touches it</summary>

> git config --global core.autocrlf true  
> Sau đó cứ commit lên  
> Người khác lấy về sẽ thành crlf  
> Mình bỏ local commit rồi pull lại cũng thành crlf

</details>

# Firebase

<details>
  <summary>Setup</summary>

> Cần cài nodejs để có npm  
> Sau đó cài Firebase CLI = npm install -g firebase-tools  
> Sau đó là: firebase login
> Sau đó: dart pub global activate flutterfire_cli  
> Tạo project trên firebase  
> Cuối cùng là config: flutterfire configure
> Chọn cái project đã tạo là file firebase_options được tạo ra  
> Trong này có DefaultFirebaseOption để init.

</details>
