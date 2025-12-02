# ForwardMail
> 一个基于Cloudflare workers 的邮件转发系统
> 
> 提供一个临时邮箱，并将所有收到的邮件都转发至你注册时的真实邮箱里。
> 

## 安装

KV空间：
```
TM_KV
```
域名->电子邮件路由 -> catch-all ->指向此workers


![1](https://github.com/Y560H/ForwardMail/blob/main/img/1.jpeg)
![2](https://github.com/Y560H/ForwardMail/blob/main/img/2.jpeg)
![3](https://github.com/Y560H/ForwardMail/blob/main/img/3.jpeg)
