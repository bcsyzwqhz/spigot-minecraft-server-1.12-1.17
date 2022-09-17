# spigot-minecraft-server1.4-1.12

#### 介绍
1.4-1.12spigot服务器核心

#### 软件架构
java

#### 初衷
spigotMC官网在国内有时会登不上去，为保证有稳定的下载源和更方便的下载，创建了此仓库

#### 安装教程

1. 安装java
2. 选择版本并下载对应的服务器核心
3. 在本地新建一个文件夹用于存放服务器文件
4. 将服务器核心移至此文件夹
5. 创建一个start.bat(Linux为start.sh)输入以下代码：

```
java -jar <服务器jar包>.jar nogui
```
6.运行此脚本
7.当服务端出现finish的字样时，说明服务器加载好了

#### 使用说明

1. 1.7.10及以上版本首次运行时会报错，将文件夹内的eula.txt的eula项改为true即可
2. 首次运行后建议将server.properties改为：

```
spawn-protection=16    
generator-settings=
force-gamemode=false
allow-nether=true
gamemode=0
broadcast-console-to-ops=true
enable-query=false
player-idle-timeout=0
difficulty=1
spawn-monsters=true
op-permission-level=4
pvp=true
snooper-enabled=true
level-type=DEFAULT
hardcore=false
enable-command-block=false
max-players=20
network-compression-threshold=256
resource-pack-sha1=
max-world-size=29999984
server-port=25565
debug=false
server-ip=
spawn-npcs=true
allow-flight=true
level-name=world
view-distance=5
resource-pack=
spawn-animals=true
white-list=false
generate-structures=true
online-mode=false
max-build-height=256
level-seed=
prevent-proxy-connections=false
enable-rcon=false
motd=A Minecraft Server
```

3. 如要增加插件请将插件放入服务器文件夹里的plugins文件夹

#### 常用服务端指令（服务端内指令 **不用打** 斜杠）

1.  stop 关闭服务器
2.  op <玩家ID> 给谁管理员权限
3.  tps 查询服务器的TPS
4.  更多指令请于服务端用help查询

#### 写在最后
祝您玩得开心！
如觉得有用，可以star一下~


