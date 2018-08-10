# P2P Study
Study the P2P technology based on pjnath library.

## Compile pjnath library

```shell
git clone https://github.com/pjsip/pjproject.git
./configure --prefex=`pwd`/out
make dep
make
make install
```

## P2P documents

[Introduction to WebRTC protocols](https://developer.mozilla.org/en-US/docs/Web/API/WebRTC_API/Protocols)

[WebRTC data channels](https://www.html5rocks.com/en/tutorials/webrtc/datachannels/)

[ICE协议下NAT穿越的实现（STUN&TURN）](https://www.jianshu.com/p/84e8c78ca61d)

[webrtc教程](https://blog.csdn.net/kl222/article/details/17198873)

## Server resources

STUN servers

| Address                          | Port  | Status |
| -------------------------------- | ----- | ------ |
| stun.l.google.com                | 19302 |        |
| stun.ideasip.com                 | 3478  | OK     |
| s1.taraba.net 203.183.172.196    | 3478  |        |
| s2.taraba.net 203.183.172.196    | 3478  |        |
| s1.voipstation.jp 113.32.111.126 | 3478  |        |
| s2.voipstation.jp 113.32.111.127 | 3478  |        |

TURN servers

| Address          | Port | Username            | Password                     | Status |
| ---------------- | ---- | ------------------- | ---------------------------- | ------ |
| 192.158.29.39    | 3478 | 28224511:1379330808 | JZEOEt2V3Qb0y27GRntt2u2PAYA= |        |
| numb.viagenie.ca | 3478 | webrtc@live.com     | muazkh                       | OK     |
