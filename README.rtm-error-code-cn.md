#RTM ERROR CODE#
[English Version](README.md)

##RTM 错误代码##

| 错误码 | 描述（同一个错误码描述可能些许不同） | 中文说明 |
|------|-------|-----|
| 0 | ok | 成功 | 
| 200001 | invalid pid or uid | 非法的项目id或者用户id | 
| 200002 | invalid pid or sign | 非法的项目id或者签名错误 | 
| 200003 | invalid file or sign or token | 非法的文件签名或者文件token错误 | 
| 200004 | attrs should contain sign and ext | 上传文件，属性字段应包含签名和扩展名 | 
| 200005 | invalid mtype, should be in [1-127] | mtype 取值范围 [1-127] | 
| 200010 | frequency limited | 接口调用频率限制 | 
| 200011 | refresh screen limited | 发送消息刷屏限制 | 
| 200020 | method forbidden | 禁止调用此方法 | 
| 200021 | permission denied | 非法的访问 | 
| 200022 | unauthorized  | 尚未登录 | 
| 200023 | auth already | 已经登录成功，重复验证登录 | 
| 200024 | auth denied | 拒绝登录，黑名单用户 | 
| 200025 | admin id can not login | 禁止管理员账号从客户端登录 | 
| 200026 | not admin user | 此操作需使用管理员账号 | 
| 200030 | too large msg or attrs | 消息体或者属性字段太长 | 
| 200031 | too large file or attrs | 文件或者属性字段太长 | 
| 200032 | parameter contain too many members | 列表字段包含的成员太多 | 
| 200033 | parameter is empty | 列表字段包含的成员为空 | 
| 200040 | not in room | 不在当前房间中 | 
| 200041 | not group member | 不是组成员 | 
| 200042 | exceed max group members | 组成员超过容许的最大值 | 
| 200043 | not friend | 不是好友，不能发消息 | 
| 200044 | banned in group | 禁止在当前组发言 | 
| 200045 | banned in room | 禁止在当前房间发言 | 
| 200046 | group member empty | 组成员为空 | 
| 200047 | enter too many rooms | 进入太多房间 | 
| 200048 | exceed max friends | 最大好友数量限制 | 
| 200050 | not supported translate lang | 不支持当前语言翻译 | 
| 200051 | translate text empty | 需要翻译的文本为空 | 
| 200052 | can not send to myself | 禁止给自己发消息 | 
| 200053 | duplcated mid | 重复的mid | 
| 200054 | sensitiveWords matched | 敏感词过滤限制 | 
| 200060 | need enable config in console | 需要在控制台开启此功能 | 
| 200099 | unknown error | 未知错误 | 
