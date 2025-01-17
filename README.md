### One-click script for acme certificate request for VPS local IPs
-------------------------------------
### One-Click Scripts
```
bash <(curl -Ls https://gitlab.com/rwkgyg/acme-script/raw/main/acme.sh)
```
or
```
bash <(wget -qO- https://gitlab.com/rwkgyg/acme-script/raw/main/acme.sh 2> /dev/null)
```
---------------------------------------
#### Functions and Features：

1：Supports Pure IPV4, Pure IPV6, Dual Stack VPS

2：Support port 80 mode and DNS API mode, support for single domain name and pan-domain name

3：Support Cloudflare/Tencent DNSPod/Aliyun hosted resolution platform DNS API applications

4：Query, revoke and delete the currently applied domain name certificate. 

5: manually renew domain name certificates with one click or by designation

6: two certificate files are stored in the root/ygkkkca file

7: Has been integrated into the following proxy script (can share a certificate):

[sing-box-yg scripts](https://github.com/yonggekkk/sing-box-yg)

[x-ui-yg脚本](https://github.com/yonggekkk/x-ui-yg)

[naiveproxy-yg脚本](https://github.com/yonggekkk/NaiveProxy-yg)

[hysteria-yg脚本](https://github.com/yonggekkk/Hysteria-yg)(Discontinued, merged into sing-box-yg script)

[tuic-yg脚本](https://github.com/yonggekkk/Tuic-yg)(Discontinued, merged into sing-box-yg script)

#### Note: The use of port 80 mode will force the release of port 80, and it is not recommended to use with nginx, caddy applications with automatic application of certificates at the same time

---------------------------------------------

#### The script preview image is shown below:

![47d4c68b8200aff3d4c94288f9adf81](https://github.com/yonggekkk/acme-yg/assets/121604513/deb30cc7-5469-40b5-b747-0b1f481ec825)

---------------------------------------
#### Disclaimer:

#### This project uses base64 encryption, which can be decrypted by yourself, please don't use it if you mind, [reason for encryption here].(https://ygkkk.blogspot.com/2022/06/github.html)

#### All code from the Github community with the integration of ChatGPT; if you need the open source code, please mention Issues to leave your contact email address
