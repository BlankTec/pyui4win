pyui4win
========

一个用python实现业务逻辑、用xml和html/css/js描述界面的windows程序的快速开发框架

# 原理：

1、界面事件和执行器发送过来的消息经过pyui4win运行环境转为pyui4win消息队列中的事件

2、事件分发器从消息队列中获取消息，并根据消息分类派发相应的处理例程

3、如果有对应的python例程处理，那么由python例程处理。否则由C++例程处理


# 推荐实践
用html/css/js写界面逻辑，用python写业务逻辑，简单快速
