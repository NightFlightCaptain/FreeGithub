# FreeGithub
自动获取github相关网站的ip地址，解决github链接不畅通的问题，该项目的README会自动更新，大家可以直接复制使用。
在workflows/freegithub.yml文件中可以设置自动更新的时间，本代码设置的是一个月自动更新一次。大家可以按照自己的需求改写cron表达式

## hosts列表
```base
#Github Host Start
github.githubassets.com 54.165.242.31
camo.githubusercontent.com 3.236.227.46
github.map.fastly.net 3.230.154.141
github.global.ssl.fastly.net 44.198.186.243
github.com 44.197.131.181
api.github.com 44.198.186.243
raw.githubusercontent.com 18.206.194.198
favicons.githubusercontent.com 34.207.248.206
avatars5.githubusercontent.com 54.86.230.221
avatars4.githubusercontent.com 54.163.29.143
avatars3.githubusercontent.com 18.206.194.198
avatars2.githubusercontent.com 54.89.231.40
avatars1.githubusercontent.com 35.175.120.159
avatars0.githubusercontent.com 34.235.150.65
# Github Host End
```

更新时间：2021-11-01 08:23:16

## 修改本机的hosts文件
### 存放位置
* Windows 系统：C:\Windows\System32\drivers\etc\hosts
* Linux 系统：/etc/hosts
* Mac（苹果电脑）系统：/etc/hosts

### 生效
* Windows：在 CMD 窗口输入：ipconfig /flushdns
* Linux 命令：sudo rcnscd restart
* Mac 命令：sudo killall -HUP mDNSResponder