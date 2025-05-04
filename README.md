# BattleOfBuaa-Release
在这里你可以获取Battle of BUAA的最新Release版本，我们同样欢迎在此仓库提交issue，帮助我们完善游戏

## 在本地运行游戏服务
由于我们的服务器算力资源和网络带宽有限，在测试阶段，Battle of BUAA支持在测试模式本地运行游戏服务器，从而提供更加稳定的游戏体验。

为了在本地运行游戏服务，你需要一个人作为主机，以服务器模式运行Battle of BUAA，其他人通过命令行加入游戏，加入游戏后会跳过房间和组队，直接进入游戏。

### 服务器端
命令行运行
```
<Battle Of BUAA executable> --server --test --port=<port to run server> --playerNum=<player count>
```
其中，executable就是Battle of BUAA的可执行文件（windows下的exe文件，macos下app包中`Content/MacOS/`下的可执行文件。其中，`port`指定服务端运行的端口，`playerNum`指定玩家数量

### 客户端
命令行运行
```
<Battle Of BUAA executable> --test --ip=<ip of your server> --port=<port of the server>
```
其中，`ip`是运行服务端的主机公网ip地址，`port`是服务端运行端口
