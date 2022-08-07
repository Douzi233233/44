# elm-release
 饿了么吃货豆工具
 
 ![GitHub Repo stars](https://img.shields.io/github/stars/zelang/elm-release)
 ![GitHub release (latest by date)](https://img.shields.io/github/downloads/zelang/elm-release/latest/total)

![elm.png](https://raw.githubusercontent.com/zelang/elm-release/main/elm.png)

# 使用说明

1. 请在 [Releases](https://github.com/zelang/elm-release/releases) 根据你的设备下载二进制文件
2. 解压文件
3. 修改config.yaml配置文件(注意格式 - auth: 后面有个空格)
4. 可选参数 -debug 将日志输出到本目录下的文件，方便调试 -task 手动执行任务 (默认执行定时任务，需要将程序挂在后台)

# 目前已实现功能

1. 支持多个cookie执行任务
2. 支持自动更新cookie(需要有登录状态下的cookie)
3. 支持手动/定时执行任务
4. 支持每日签到、自动获取任务列表、自动获取远程隐藏任务列表
5. 目前每天可获取吃货豆100-200+

# To do list

1. 吃货豆兑换红包
2. 任务执行消息通知
3. ....
