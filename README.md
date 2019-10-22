# Pixiv_Downloader_Shell P站扒图神器 收集控必备!!!
### [QQ群:835058977](https://shang.qq.com/wpa/qunwpa?idkey=69768c27d90b3aa4550e63df7d8b1cd65c581663cd4858c0a0f8fbdc8553c174) [软件下载git根目录](https://github.com/sh2288/pixiv_downloader_shell/raw/master/Pixiv_Downloader_Shell-2019-06-10.zip)
![](img/P站扒图神器_封面.png)
>#### 最新消息
```
2019-10-22 用户配置编码问题,应统一UTF-8编码,可以解决中文路径问题
2019-10-14 用户配置更改,永久保留(版本更新,配置不变)
2019-10-14 添加p站反扒的cookies设置(目前不使用cookies无法登陆),不再使用用户登陆
```
>#### 软件特性:
```
1.依据图集id下载原始大图
2.一键批量下载自己收藏的图片(需要激活软件)
3.一键批量下载某画师的所有图片(需要激活软件)
4.支持下载动态图并转换动态图(测试,某些格式需要安装ffmpeg)
5.依据title标题批量下载整个套图(需要激活软件)
6.支持代理,格式如下http://127.0.0.1:1080或http://user:password@proxy:port
例如:公司内网代理格式如下:http://domain\user:password@proxyip:1080
如果不使用代理请在设置--代理设置--留空并保存设置
7.支持下列网址中所含ID的直接解析,也就是字符为id=数字的
https://www.pixiv.net/member.php?id=1819503
https://www.pixiv.net/artworks/77195575
```
>#### 使用说明
##### p站cookies查看及设置
![](img/pixiv_cookies_查看方法4.gif)
##### 下载演示
![](img/使用方法.gif)
```
1. 首先,设置页填写p站登录信息cookies,以及代理信息(不用代理请留空)http://127.0.0.1:1080 或其他地址
##### 如何查看P站已登录的cookies?
- 使用chrome核心的浏览器,登陆P站
- 按 F12,选择Application tab -> Storage -> Cookies
- 选择pixiv.net,复制PHPSESSID的值
2. 选择下载选项,填入相应id(画师id或图集id)或其他(title或标签)后按下载按钮即可
3. 建议先试用一下如果测试不能下载,请不要激活软件,没有问题后再考虑激活软件解锁全部功能(一些测试用的图集id,75034219,75148706),
4. 关于数据库,下载过的图片不会再次下载(很适合追某个画师的更新)除非删除data下的db.sqlite
```
>#### 注意:
##### p站有限制,同一ip下载数据量过大,可能会被屏蔽几小时,请勿过度使用此工具
##### 设置图片保存路径不能有中文或空格,请尽量用纯英文路径
![](img/图像%2021.png)
