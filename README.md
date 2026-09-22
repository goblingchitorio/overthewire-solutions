# overthewire-solutions
Overthewire - writeups CTF
- **challenge**: bandit overthewire level 1->34
- **category**: basic linux
- **Difficulty**: easy
- **source** : [bandit overthewire](https://overthewire.org/wargames/bandit/)

**Note**: Đây là ```write up``` đầu tiên của mình trên hành trình ```ctf``` đặc biệt là ```puwable```. Trong bài viết này mình sẽ chia sẽ về hành trình chinh phục 34 level của ```command linux``` trên ```bandit overthewire```.Các game của bandit là các thử thách cơ bản về các câu lệnh cơ  linux giúp chúng ta có một cái nhìn khách quan về ```CTF```. Vì đây là bài viết đầu tiên của mình nên có gì sai sót mong mọi người góp ý.  

## level 0
Ở level 0 đề yêu cầu mình sữu dụng ```SSH``` .Máy chủ mà mình phải kết nối là ```bandit.labs.overthewire.org```, trên cổng ```2220``` .Tên đăng nhập và mật khẩu là ```bandit0```.

![](./img1)
#### Solution
Để kết nối vào sever với cổng 2220, ta cần thêm option ```-p 2220```` (-p nghĩa là port).


Lệnh input terminal: ```SSH bandit.labs.overthewire.org -p 2220 -l bandit0```.


Sau khi nhập input thì màn hình sẽ hiện ra yêu cầu nhập password và khi đó ta cần nhập mật khẩu  ```bandit0``` là sẽ vào được sever.

![]()



  






