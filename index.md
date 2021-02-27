#感谢您使用Ks2在线充值接口
## Ks2Pay官方网站：https://ks2.xyz
>* 1，插件版：面板服也可以轻松使用  
>* 2，RCON直连版：采用原生协议，本地不保存账号密码。适用于开了2个端口及以上的服务器

## 对接到插件版的使用说明
### 请求地址

>http://api.ks2.xyz/index.php

### 调用方式：HTTP Get

#### 请求参数:
![avatar](http://hkimg.oa5.xyz/jk-1.png)
#### 请求示例(不能输入空格或输入空格指令错误的请将空格替换为%20)
>标准示例：http://api.ks2.xyz/index.php?ip=test.ks2.xyz&send=plugins&key=123456&command=time set 999

>替换空格示例：http://api.ks2.xyz/index.php?ip=test.ks2.xyz&send=plugins&key=123456&command=time%20set%20999


###请求返回结果:

![avatar](http://hkimg.oa5.xyz/jk-2.png)

----------------------------

##对接到RCON版的使用说明
### 请求地址

>http://api.ks2.xyz/index.php

### 调用方式：HTTP Get

#### 请求参数:
![avatar](http://hkimg.oa5.xyz/jk-3.png)
#### 请求示例(不能输入空格或输入空格指令错误的请将空格替换为%20)
>标准示例：http://api.ks2.xyz/index.php?ip=test.ks2.xyz&port=25566&pass=123456&send=rcon&command=time set 999

>替换空格示例：http://api.ks2.xyz/index.php?ip=test.ks2.xyz&port=25566&pass=123456&send=rcon&command=time%20set%20999


###请求返回结果:

![avatar](http://hkimg.oa5.xyz/jk-4.png)

