## 用来下载全民K歌好友作品的PHP脚本
1、该PHP脚本为临时使用开发，所以功能简单，操作简单

2、get.php为主程序，可以直接命令行方式运行 也可将程序放在网站目录下以web方式运行

3、程序使用简单的请求头模拟和正则匹配拿到网页内容中的音频文件 原理简单

### 使用方法
- 在全民K歌软件中将作品分享到QQ，这样我们在QQ中就可以拿到作品的网页链接
- 将网页链接复制到url.txt文本中，如有多个链接，每行一个
- 运行get.php文件，会将作品以m4a音频的方式保存在当前目录