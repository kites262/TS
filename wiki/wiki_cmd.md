

# wiki · 帮助文档 · command

```
< > 尖括号为必须参数 *<player> 指代玩家
[ ] 方括号为可选参数
( ) 圆括号为参数注释
A|B A等同于B
```

## Teleport

`/tpa <player>`					向一位玩家发起传送请求

`/tpaccept` | `/tpyes`			接受上个玩家发送的传送请求

`/tpdeny` | `/tpno`				拒绝上个玩家发送的传送请求

`/sethome [HomeTag]`			设置一个以[HomeTag]为名字的家 (最多拥有***1***个家)

`/home [HomeTag]`				传送至名字为[HomeTag]的家

`/back`										返回至上一个地点，包括但不限于**死亡， pvp， 世界传送**

`/tpr`											在世界中随机传送

## Infomation

`/getpos <player>`				获取一个玩家目前的位置，包括**世界 、坐标、视线角度、与ta的距离**

`/gc`											获取目前的服务器信息，包括**目前TPS、连续运行时间、内存统计、已加载的世界与世界区块加载量、实体加载量、tiles**

`/time`										获取目前世界的世界时间

## Multiverse

`/mv list`									列出所有已注册的世界

`/mv tp <world>` | `/mvtp <world>`	传送至一个世界

[^world]:	世界包括：re 主资源		world 主生存		redy 地狱资源  ???? 末地门被打开后开放资源末地

[^世界边界]:	*world* **3200**  *re* **32000**

## Functions

`/ptime <Value>`							修改客户端时间

`/afk`												进入挂机模式(无敌状态)，移动、攻击或输入/afk自动退出afk

`/music <ID>`									全服点歌(Id=网易云音乐分享链接)

`/music help`									查看全服点歌的其他功能

## CoreProtect

`/coreprotect inspect` | `/co i`	开启方块数据查询，左击或右击查看方块日志

[^方块日志]:	日志中包含了方块的历史数据  有玩家名、时间、操作等信息

[^co]:  View more, please move to  https://dev.bukkit.org/projects/coreprotect
