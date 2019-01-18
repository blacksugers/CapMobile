# CapMobile
微协同
### 2018-11-29
    工作界面
    1,待办数量接口
    添加邮件未读数量  以及弹性显示其他功能数量
    接口：/mobileBpmController//mobileBpmController/findTaskNum
    参数：
    userId:用户ID
    返回：[{"taskId":"4123dasdsa2asd12","taskNum":1},{"taskId":"asdasdqwda123123","taskNum":11}]
    taskId 功能ID
    taskNum 功能未读数量

    2,云邮功能
    需求：点进云邮界面之后，返回按钮直接返回到外层界面，不需要goBack，其他跳转不影响。
    实现：监听跳转URL，如果URL中包含"mobileMailController"就是云邮界面，做相应处理即可。

    3.APP名称 logo展示根据系统更改
    app消息界面名称 
    app登录界面logo
    
    4.云盘与文件系统大修改
    聊天界面
    长按文件消息的提示菜单增加“云盘”菜单，可以把当前文件存到云盘的“个人网盘”里；图片等，文件形式的消息
### 2018-12-24
    1.APP涉及到人员的功能点,提供岗位信息,有主岗位和辅岗位一并标识
    实现：通讯录接口添加岗位，是否是兼职岗位 字段
    
    2.消息界面 审批消息更名为“事项审批”
    
    3.审批提交建议默认勾选第一条，可以建议一次点击操作
    
### 2019-01-07
    添加工作圈未读图标功能
    添加到接口：/mobileBpmController//mobileBpmController/findTaskNum中
