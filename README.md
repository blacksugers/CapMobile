# CapMobile
微协同
## 工作界面
### 1,待办数量接口
接口：personHomeQueryController/getToDoTasksNumsByUserId

参数：random：随机数
     userId:用户ID

返回：{"result":[{"num":"1","nums":0,"tasktype":"1"}],"flag":"1"}

### 2,云邮功能
需求：点进云邮界面之后，返回按钮直接返回到外层界面，不需要goBack，其他跳转不影响。

实现：监听跳转URL，如果URL中包含"mobileMailController"就是云邮界面，做相应处理即可。
