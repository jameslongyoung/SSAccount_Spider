# SSAccount_Spider
这是一个mac版shadowsocks账号爬虫工具，爬取ss.ishadowx.net的免费ss账号并导入到shadowsocks客户端<br>

使用方法：下载shadowsocks mac版客户端并安装，下载地址：https://github.com/shadowsocks/shadowsocks-iOS/releases<br>
依赖包：bs4，安装：pip install bs4<br>
timedTask.sh：每天0点，6点，12点，18点从网站上爬取并且更新账号<br>
运行定时任务：<br>
chmod +x timedTask.sh<br>
./timedTask.sh<br>
如果想爬取一次，则执行python Spider.py<br>
