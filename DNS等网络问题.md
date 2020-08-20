
DNS等网络问题

# github.io无法访问服务器Ip
+ 很可能是DNS污染
+ https://www.ipaddress.com/
+ Github.io resolves to the following 4 IPv4 addresses:
	+ 185.199.108.153
	+ 185.199.109.153
	+ 185.199.110.153
	+ 185.199.111.153
+ 使用ss的全局模式(非PAC模式)，即可正常访问