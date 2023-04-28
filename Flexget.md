# Flexget自动下载

有了离线下载工具后已经可以手动添加下载并自动上传，距离全自动化只剩下自动添加下载任务，可以使用Flexget和RSS订阅实现。

Flexget参考：https://www.lilyblessing.tk/2021/10/18/%E5%85%A8%E8%87%AA%E5%8A%A8%E4%B8%8B%E8%BD%BD%E5%BD%93%E5%AD%A3%E6%96%B0%E7%95%AA/

RSS使用Mikan：https://mikanani.me/

下载什么，怎么下载取决于用户需求，初步入手可以使用Mikan提供的RSS订阅，后续可以自行编写代码/参数等设计RSS筛选器等，自由度非常高。比如我在国内的服务器为Mikan域名指定IPv6的host来避免Cloudflare CDN可能的网络问题，使用Python预处理xml订阅文件再使用本地Nginx为flexget提供订阅等，最终实现每十分钟自动下载订阅中更新的番剧且长时间无故障。