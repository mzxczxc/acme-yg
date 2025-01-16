### One-click script for acme certificate request for VPS local IPs
-------------------------------------
### One-click script
``
bash <(curl -Ls https://gitlab.com/rwkgyg/acme-script/raw/main/acme.sh)
```
or
```
bash <(wget -qO- https://gitlab.com/rwkgyg/acme-script/raw/main/acme.sh 2> /dev/null)
```
---------------------------------------
#### Functions and features:
1: Support pure IPV4, pure IPV6, dual-stack VPS

2：Support port 80 mode and DNS API mode, support single domain name and generic domain name.

3：Support Cloudflare/Tencent DNSPod/Aliyun hosted resolution platform DNS API applications

4：Query, revoke and delete the currently applied domain name certificate. 

5: manually renew domain name certificates with one click or by designation

6：The two certificate files are stored in the root/ygkkkca file

7: Has been integrated into the following proxy script (can share a certificate):

[sing-box-yg script](https://github.com/yonggekkk/sing-box-yg)

[x-ui-yg script](https://github.com/yonggekkk/x-ui-yg)

[naiveproxy-yg script](https://github.com/yonggekkk/NaiveProxy-yg)

[hysteria-yg script](https://github.com/yonggekkk/Hysteria-yg) (defunct, merged into sing-box-yg script)

[tuic-yg script](https://github.com/yonggekkk/Tuic-yg) (defunct, merged into sing-box-yg script)

#### Note: When using port 80 mode, it will release port 80 forcibly, and it is not recommended to use it with nginx, caddy and other apps with auto-request certificates.

---------------------------------------------

#### The preview image of the script is shown below:

! [47d4c68b8200aff3d4c94288f9adf81](https://github.com/yonggekkk/acme-yg/assets/121604513/deb30cc7-5469-40b5-b747-0b1f481ec825)

---------------------------------------
#### Statement:

#### This project uses base64 encryption, you can decrypt it by yourself, please don't use it if you mind, [encryption reason here](https://ygkkk.blogspot.com/2022/06/github.html)
#### All code from Github community and ChatGPT integration; if you need open source code, please mention Issues to leave your contact email address!
