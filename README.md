# 基于Pomelo类棋牌游戏服务端

大致功能如下：
----
* 用户
  * 游客模式
  * 第三方登陆，只做了QQ，微信需要付费申请账号，暂时未实现，原理类似

* 大厅
  * 系统消息
  * 邮件
    * 每日登陆奖励
    * 游戏奖励
    * 抽奖
  * 排行榜
  * 反馈
  * 其他
* 房间
  * 创建房间/组队
  * 加入房间/队伍
    * 准备/坐下/开始游戏
    * 离开/解散房间
  * 快速开始
  * 内置房间模式
* 游戏
  * 游戏开始
    * 内置模式时游戏等待匹配
  * 游戏中
    * 游戏逻辑
    * 交换手
    * 落子/操作等
    * 投降
    * 游戏结束/结算等
    * 内置消息/声音
   * 断线重连
  
* 数据库
  * sql
  * redis
  
* 其他服务器配置
  * 服务器列表
  * 定时任务
  * ftp
  * 其他

说明
====
前几年写的项目，首次接触使用NodeJS，不完美的地方望见谅。由于项目已不做，现在放出来供大家参考、学习，有兴趣的可以自行优化、扩展。
----
任何问题联系：iniwaper@gmail.com / QQ:522765228   
更多细节，请查看客户端分支
