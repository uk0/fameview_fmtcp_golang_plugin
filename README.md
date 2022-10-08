### 北京杰控 FameView FMTCP大数据接口插件


#### 问题

1. 在不升级FameView授权的情况下更方便的使用FMTCP数据接口获取数据（没有速率限制）
2. fmtcp 对业务人员不友好。


#### 解决方案以及实现

1. 实现FMtcp 的Golang 客户端（纯go），未来可以打包dll so dylib等库进行给其他语言使用。
2. 实现了Fmtcp 90%以上的API（获取数据，修改数据，批量获取数据，批量修改数据，变动上报等关键数据接口，效率还可以）

#### 相关

  * 北京杰控 FameView http://www.fameview.com/ (老板是技术流程序写的非常棒，可以运行在XP，2000，2003等机器上)