# CTF摸鱼writeup

## Jarvis OJ

### 190925

#### 握手包

搞到rockyou.txt，据说是kali的自带字典，有点东西嗷。

然后用aircrack-ng 指定字典破解。

```bash
aircrack-ng wifi.cap.d4e4d22bc8fe925bf0ccb9382056ce8e -w rockyou.txt
```

#### 