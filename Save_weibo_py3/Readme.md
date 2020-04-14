使用Python3下载所有微博内容到本地
-----
**`需要安装Python3 谷歌浏览器` **  
[点击下载Python3.8.1](https://npm.taobao.org/mirrors/python/3.8.1/python-3.8.1.exe)   [点击下载谷歌浏览器](https://www.google.cn/chrome/)

首次安装Python3注意 ： 安装界面需要勾选App Path就可以不用手动配置环境变量可以直接使用Python   
本程序需要使用 requests selenium PyQuery tkinter 四个模块，程序自带此四个模块 不用重新安装   

安装好Python3和谷歌浏览器后需要下载 **匹配谷歌浏览器版本的 ChromeDriver**  
 1.谷歌浏览器版本查询操作 [打开谷歌浏览器 - 右上角三个点 - 设置 - 关于Chrome] 就可以看到谷歌版本号  
 2.[点击去下载ChromeDriver](https://npm.taobao.org/mirrors/chromedriver/)  打开此链接后找到和谷歌浏览器一样版本的链接 **若没有一样的版本 请选择相近的版本**  
 3.打开chromedriver_win32.zip压缩包将chromedriver.exe解压到Python3目录即可  Python3目录一般为**C:\Users\电脑用户名\AppData\Local\Programs\Python\你的python版本号\**

完成以上步骤即可使用 [点我下载微博保存.Py](https://eastifs.wzey.cn/prm_public/SaveAllWeibo.pyc.zip)
关于 **微博保存程序压缩包**
**test.pyc是测试文件 请先打开此文件测试 测试通过即可打开weibo-res.pyc来保存微博内容**

程序介绍：输入微博ID自动下载全部微博内容并保存到本地
---
如何获得微博ID？
![如何查看微博ID](https://github.com/shangchen0/scopublic/blob/master/Save_weibo_py3/getweiboid.png)
