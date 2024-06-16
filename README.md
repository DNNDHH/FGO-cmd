FGO-CMD  
=====
* v3.7
----------------
# 注意事项
* 2024年5月7日起 连接绑定 Aniplex Online 后的游戏账号文件 可以继续使用！没有影响！


导入账号
=============

* 移动账号文件 54cc790bf952ea710ed7e8be08049531 文件 到 FGO-CMD/账号/ 任意ABCDEFG文件夹中！点击对应的按钮 即可自动解密导入账号！
* 账号文件文件路径：
```console
/storage/emulated/0/Android/data/com.aniplex.fategrandorder/files/data/`可能需要Root
```  
* ADB命令复制到 下载 目录中 即 Download（可跳过部分系统的Root要求）
```console
adb shell cp /storage/emulated/0/Android/data/com.aniplex.fategrandorder/files/data/54cc790bf952ea710ed7e8be08049531 /storage/emulated/0/Download/
```  
-----------------

![](https://i.imgur.com/SRoEVkV.png)




战斗POST
===========

* 自定义 战斗POST （ 使用 FGO-CMD客户端 列出全部好友 功能查看好友的 助战ID ）
* 剩余AP显示
* 设置战斗次数，想刷几次刷几次！（别忘了选AP恢复方式）
* 自动AP恢复功能（吞石头 吃什么苹果 随你选择）
* 新增加 显示 战斗结算奖励 伴 御主EXP 礼装EXP 
* 新增加 显示 战斗结算 掉落物品素材 和 QP点
---------------------

![](https://i.imgur.com/zUlhthm.png)
![](https://i.imgur.com/1A6fiCO.png)
![](https://i.imgur.com/wY710Eh.png)




一键过章
=========
* 搁置中………过章暂停开发…目前位于 主线 2.1 永久凍土帝国 アナスタシア
---------------------------------------------
![](https://i.imgur.com/qnhWoMi.png)
![](https://i.imgur.com/0isByGn.png)



抽卡
===========

* 快速抽卡
* 抽卡结果显示
* 出货检测
* 自定义抽卡池
-------------------
![](https://i.imgur.com/ShFZRoY.png)


刷友情点
==========
* 这里要填写 （友情点受益方） 的 助战ID！ （ 使用 FGO-CMD客户端 列出全部好友 功能查看好友的 助战ID ）
* 选择AP自动恢复方式
* 设置刷图次数
--------
![](https://i.imgur.com/2klbQ4p.png)



其它功能
===========
* 查询 好友助战ID ，你需要输入好友的朋友码 
* 不知道好友的朋友码，那就直接 列出全部好友 （这个比较方便实用）
* 添加好友 并 锁定（有效解决助战列表刷不出来指定好友的问题）
* 全局助战职介设定，就是选择用哪个职介的助战（此处设定影响全部战斗功能）
* 链接Atlas Academy数据库
------------

![](https://i.imgur.com/N8StD8q.png)




⭐特别鸣谢
=====

❤️大感谢 hexstr 大佬对加解密数据的直接帮助🫡
---------------
https://github.com/hexstr

❤️大感谢 Atlas Academy 的 @Neo大佬的帮助🫡
-----------------------------------------------------------


⭐未来计划
========
- [ ] 添加自动选择助战 好友&非好友 功能 (默认不添加好友)
- [ ] 在CMD终端命令行补充显示 在登陆时&战斗结算时 的 AP/苹果/石头/电池/友情点 剩余量
- [ ] 重新美化程序的 UI界面/CMD输出显示UI（审美又变了2333。。。）
- [ ] 咕咕咕。。。。。
--------------------------------------------------------------
