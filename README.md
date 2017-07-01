# 苹果笔记本添加内网路由同时上内网和外网。
首先要找到你连接到内网的网卡名，可以在终端中ifconfig查找一下，</br>
然后将第8行中`dev_intra`变量的值修改为该网卡名。</br>
然后添加执行权限 </br>
```
chmod +x CQUPT_route.sh
```
最后执行脚本即可
```
./CQUPT_route.sh
```
注意：当你的网关发生了变化时，可能是从一个宿舍(楼栋)搬到另一个宿舍(楼栋)，需再次执行一次。
