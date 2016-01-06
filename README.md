# wechat-deleted-friends
查看被删的微信好友

使用方法
在终端中执行:
git  clone  https://github.com/0x5e/wechat-deleted-friends.git
cd  wechat-deleted-friends
python  wdf.py
然后按照提示操作就可以了.
完成之后手动删除生成的一个群聊, 不要在里面说话, 不说话好友们是不知情的. 

友情提示
该脚本十分高能, 幼小的心灵会受到灼伤, 玻璃心请绕行.

原理
利用微信网页版的接口, 将好友35人拉入一个群聊, 再移出, 反复进行多组, 无法成功拉入则说明他把你拉黑了. 

用的是微信网页版的接口

查询结果可能会引起一些心理上的不适,请小心使用..(逃

还有些小问题:

结果好像有疏漏一小部分,原因不明..

最终会遗留下一个只有自己的群组,需要手工删一下

没试过被拉黑的情况

Mac OS用法:
启动Terminal

`$ python wdf.py`

按指示做即可
