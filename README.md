# httpdLinuxC
Linux C http文件下载服务器

#2016/12/28 12:23:19 
今天要做的功能：


- 将显示根目录文件内容改为显示指定docroot目录里的内容
- 点击文件可以传送文件流进行下载

> 2016/12/28 14:50:16 
> 今天完成了指定文件根目录显示它下面的文件列表，并且点击连接可以通过multipart/form-data 发送给流量器。现在还出现的问题是中文的文件名不能正常下载，zip的格式也不能正常的下载。。。。orz明天再弄拉！！