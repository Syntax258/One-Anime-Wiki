# One-Anime-Wiki
从零开始自建 全自动轻量且Serverless的番剧网站，下载aria2+Rclone，存储Onedrive，网站Vercel+Upshash，自动化推送Power Automate等

演示站点：https://oneanime.eu.org/

演示TG频道：https://t.me/One_Anime_CH

1. 首先需要云存储空间，参考[Onedrive.md](Onedrive.md)
2. 然后需要配置离线下载方案(唯一需要服务器的地方)，参考[Aria2&Rclone.md](Aria2&Rclone.md)
3. 然后配置自动下载方案，参考[Flexget.md](Flexget.md)
4. 网站搭建使用Vercel+Upshash，参考[onedrive-vercel-index.md](onedrive-vercel-index.md)
5. 自动化文件整理和推送工具使用Power Automate，参考[Power-Automate.md](Power-Automate.md)

最终效果虽然看上去比较简陋，但也基本满足了看番需求，更不需要像Flex/Emby等需要刮削占用服务器资源。
