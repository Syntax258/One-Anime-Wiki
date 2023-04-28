# 获取Onedrive

所有资源存储于Onedrive中，获取Onedrive方式包含但不限于：Microsoft 365个人版(付费)、Microsoft 365 家庭版(付费)、教育版订阅(A1)、企业版订阅、开发者订阅(E3)。可以搜索`OFFICE365 A1 A1P E3 E5等版本区别`了解相关内容。考虑到教育/企业子账户数据安全问题，建议购买个人版/家庭版或者使用免费的E5开发者订阅保障全局权限，以下内容为注册Microsoft 365 开发人员计划(E5订阅)获取Onedrive。

Microsoft 365 开发人员计划(E5订阅)注册难度不高，网上教程有很多，关键在于帐号注册后的续期工作，因为订阅有效期为90天，需要微软检测到使用API才能续期。

Microsoft 365 开发人员计划注册地址(使用个人帐户登录)：https://developer.microsoft.com/zh-cn/microsoft-365/dev-program

主页 - Microsoft 365 admin center(使用E5管理员帐号登录，管理子账号)：https://admin.microsoft.com/Adminportal/Home#/homepage

SharePoint 管理中心(使用E5管理员帐号登录，设置OneDrive容量至5T)：https://admin.onedrive.com/?v=StorageSettings

按照网上教程(也可以不需要)与以上链接就可以获取Onedrive。

# 自动续订E5订阅

续订E5订阅方案较多，有TG bot、网页、软件等。根据对应方案教程自行操作即可，通用注意事项有：[关闭 E5 账户登录双重验证](https://account.activedirectory.windowsazure.com/UserManagement/MultifactorVerification.aspx)、[关闭 Azure 中 API 调用的双重验证](https://aad.portal.azure.com/#blade/Microsoft_AAD_IAM/ActiveDirectoryMenuBlade/Overview)、建议使用不使用的子号授权API。

软件方案和教程：https://e5renew.com/

还有Cloudflare KV加Github action方案较为复杂不再推荐，以及[e5.qyi.io](https://qyi.io/archives/687.html)网页方案因为同一IP大量调用导致大规模封号不再推荐。
