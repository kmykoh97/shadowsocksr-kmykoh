# shadowsocksR-refined version by kmykoh97
## Guide to break China Firewall using VPS
![China firewall](images/chinaFirewall.jpeg)

*In this guide, I will show you how to build your own SSR server. Beginners, please read these steps carefully.*

### Steps for building your own VPS server
1. Sign up for a new account for any vps provider you like such as aliyun, bandwagon, Vultr... In this guide, I will use [Vultr](www.vultr.com) for example
2. Follow instruction to top up your account. If you only want to try, feel free to top up just the bare minimum. You can use credit card, Paypal, Alipay...
3. Set up a server... Choose any country you like. Recommended server: Japan, Miami, Singapore, Silicon Valley..
4. Server type, choose centos6 x64. Centos7 has inbuilt firewall which might block your server. Deploy the server.
5. If you are using windows, use any software to set up ur SSR. For example popular ones are putty, xshell... Elif you are using Linux or Mac, open up terminal, run command "ssh root@<ip-address>"
4. your username will be root for most Linux servers. Password and ip could be found in you vultr webpage. You just have to do a little navigation to view it.
5. In Linux terminal page: copy, paste and run:
```linux
yum -y install wget

wget --no-check-certificate https://raw.githubusercontent.com/teddysun/shadowsocks_install/master/shadowsocksR.sh

chmod +x shadowsocksR.sh

./shadowsocksR.sh 2>&1 | tee shadowsocksR.log

```
6. Follow instructions to set up your server. Values I used: 

### Free shadowsocksr account:
server: 45.77.118.131
location: Miami
VPS: [Vultr](www.vultr.com)



please use them wisely

by kmykoh97
