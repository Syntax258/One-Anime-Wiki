# 自动化文件整理和推送

Power Automate我使用时间不多，而且需要根据需求出发编写和使用脚本，所以方案并不适合每个人。

我的方案是每小时检查文件夹中的文件是否包含没有归档整理的番剧文件，然后重命名后移动到对应文件夹，然后通过TG bot向频道推送信息。其中TG bot推送信息需要HTTP连接器以及高级许可证，这里通过[Power Apps开发人员计划](https://powerapps.microsoft.com/zh-cn/developerplan/)注册嫖到部分高级特性从而免费使用(暂不清楚是否受750次/月的流限制)。可以通过[Power Platform admin center](https://admin.powerplatform.microsoft.com/analytics/flow)使用E5管理员帐号登录查看Power Automate分析报表。

TG bot推送自定义连接器代码：[通过Microsoft Power Automate构建自己的Telegram Bot实时推送教程](https://www.microcharon.top/tech/152.html)

他人使用邮件推送方案：[让 Outlook 使用 Mipush/Server 酱 推送邮件 - V2EX](https://www.v2ex.com/t/742914)、[Microaoft Power Automate + Telegram Bot制作个简易推送](https://blog.lijiakaijun.cyou/posts/30283)

使用TG bot的教程，包含发送消息格式：[Telegram机器人 · Devops Roadmap](https://gitbook.curiouser.top/origin/telegram-Bot%E6%9C%BA%E5%99%A8.html)

获取TG频道的ID可能遇到的问题：[Telegram BOT 在频道/群组 报错 400：Bad Request: chat not found 的 解决方案](https://www.blueskyxn.com/202103/4369.html)

演示TG频道：https://t.me/One_Anime_CH