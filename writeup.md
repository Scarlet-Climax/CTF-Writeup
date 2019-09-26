# CTF摸鱼writeup

## 加密套路

-   base64
-   vigenere
-   rot13

## Jarvis OJ

### 握手包

搞到rockyou.txt，据说是kali的自带字典，有点东西嗷。

然后用aircrack-ng 指定字典破解。

```bash
aircrack-ng wifi.cap.d4e4d22bc8fe925bf0ccb9382056ce8e -w rockyou.txt
```

## picoCTF

### Forensics Warmup 2

把png变成jpg

### net cat

`nc 2018shell.picoctf.com 49387`

### HEEEEEEERE’S Johnny

passws shadow

`john shadow -show`

### strings

`stirngs` 解包

### pipe

grep

### Inspect Me

检查HTML CSS Javascript

### grep 2

grep查目录

### Aca-Shell-A

-   echo 
-   rm
-   ./
-   cp

### Client Side is Still Bad

前端检查密码

### Logon

更改cookies登录

### Reading Between the Eyes

图片隐写

用stegsolve，LSB，RGB末尾

### Recovering From the Snap

binwalk查看二进制包

foremost解包



