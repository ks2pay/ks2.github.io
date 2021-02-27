#感谢您使用Ks2在线充值接口
## Ks2Pay官方网站：https://ks2.xyz
>* 1，插件版：面板服也可以轻松使用  
>* 2，RCON直连版：采用原生协议，本地不保存账号密码。适用于开了2个端口及以上的服务器

## 对接到插件版的使用说明
### 请求地址

>http://api.ks2.xyz/index.php

### 调用方式：HTTP Get

#### 请求参数:
|字段名称|字段说明|类型|必填|示例|
| -------------|:--------------:|:--------------:|:--------------:| ------:|
|ip|您的服务器ip|string|是|test.ks2.xyz|
|send|插件版填写plugins|string|是|plugins|
|key|您的服务器key|string|是|123456|
|command|需要发送的指令(不加/)|string|是|time set 999|
#### 请求示例(不能输入空格或输入空格指令错误的请将空格替换为%20)
>标准示例：http://api.ks2.xyz/index.php?ip=test.ks2.xyz&send=plugins&key=123456&command=time set 999

>替换空格示例：http://api.ks2.xyz/index.php?ip=test.ks2.xyz&send=plugins&key=123456&command=time%20set%20999

###请求返回结果:
|返回值|返回值说明|
| -------------|:--------------:|
|succ|指令发送成功|
|key err|服务器key填写错误|
|未授权|您未购买授权，购买地址buy.oa5.xyz|
***
##对接到RCON版的使用说明
### 请求地址

>http://api.ks2.xyz/index.php

### 调用方式：HTTP Get

#### 请求参数:
|字段名称|字段说明|类型|必填|示例|
| -------------|:--------------:|:--------------:|:--------------:| ------:|
|ip|您的服务器ip(数字)|string|是|123.456.789.000|
|port|RCON端口，不是游戏端口|string|是|25566|
|pass|RCON密码|string|是|123456|
|send|RCON版请填写rcon|string|是|rcon|
|command|需要发送的指令(不加/)|string|是|time set 999|
#### 请求示例(不能输入空格或输入空格指令错误的请将空格替换为%20)
>标准示例：http://api.ks2.xyz/index.php?ip=test.ks2.xyz&port=25566&pass=123456&send=rcon&command=time set 999

>替换空格示例：http://api.ks2.xyz/index.php?ip=test.ks2.xyz&port=25566&pass=123456&send=rcon&command=time%20set%20999

###请求返回结果:
|返回值|返回值说明|
| -------------|:--------------:|
|命令发送成功|指令发送成功|
|连接失败|服务器连接失败|
|未授权|您未购买授权，购买地址buy.oa5.xyz|
