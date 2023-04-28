# 搭建离线下载

Aria2+Rclone完全参考：https://p3terx.com/archives/offline-download-of-onedrive-gdrive.html

使用Aria2下载完自动使用Rclone上传方案，~~之前不是说serverless吗，你这还得server啊~~。考虑到BT下载版权问题，建议使用国内大带宽服务器，不建议使用境外VPS，~~不过想用也行~~。p3terx教程中脚本配置已经比较完美，只需自行微调部分参数，需要修改的部分也只有`/root/.aria2c/aria2.conf`和`/root/.aria2c/script.conf`。AriaNg管理前端也可以自由选择网页还是桌面应用程序，填写Aria2 RPC参数`IP地址和端口`、`RPC秘钥`即可以连接成功。

本部分可以使用其他类似方案实现例如qbittorrent。