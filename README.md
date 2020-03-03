# btpanel-ss
宝塔Linux面板shadowsocks可视化管理插件

# 请遵守当地法律,仅供研究学习技术交流，在试用后24小时内删除。如产生任何纠纷，与本人无关。  

<h2>前置条件</h2>
<p>依赖主体：宝塔Linux面板</p>
<p>操作系统：Centos/Ubuntu</p>

<h2>安装</h2>
<p>git clone https://github.com/insoxin/btpanel-ss</p>
<p>cd btpanel-ss</p>
<p>bash install.sh install</p>

<h2>卸载</h2>
<p>先在可视化界面中删除所有用户端口,再执行以下命令</p>
<p>cd btpanel-ss</p>
<p>bash install.sh uninstall</p>

<h2>使用</h2>
<p>直接登陆宝塔Linux面板 >> 打开软件列表页面 >> 转到列表最后一页即可看到新安装的shadowsocks插件</p>


![](https://i.loli.net/2019/04/19/5cb9df2230a35.png)
![](https://i.loli.net/2019/04/19/5cb9df6d5b2fd.png)
![](https://i.loli.net/2019/04/19/5cb9e1dda576b.png)
### 查看端口情况

netstat  -antu 


### 致谢列表
https://blog.isoyu.com/archives/bt-ss-udp53.html

https://www.bennythink.com/udp53.html

https://github.com/BennyThink/UDP53-Filter-Type

https://github.com/shadowsocks

https://github.com/Liang2580/btpanel-ss
