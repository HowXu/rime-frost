# 白霜拼音个人配置

Fork from [白霜拼音](https://github.com/gaboolic/rime-frost)  

改了一些快捷键，词库和主题。留作备份开箱即用。  

字体使用Maple Mono NF CN  

# Usage

安装Rime之后打开用户文件夹(C:\Users\ **Your User Name** \AppData\Roaming\Rime)。停止后台服务后删除Rime文件夹，在Roaming同层文件夹克隆本仓库并改名为Rime  

一步到位:  
```sh
git clone --depth=1 https://github.com/HowXu/rime-frost Rime
```

右键托盘重新部署后设定输入法即可

# 配置文件说明:

default.yaml 全局配置 含切换快捷键
rime_frost.dict.yaml 默认白霜拼音词库配置 删掉了一些细胞词库
weasel.yaml 主题和输入栏表现配置
rime_frost.schema.yaml 白霜拼音设置