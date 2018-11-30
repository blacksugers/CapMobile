# CapMobile
微协同
## 2018-11-29
### 工作界面
### 1,待办数量接口
    接口：personHomeQueryController/getToDoTasksNumsByUserId
    参数：
    random:随机数
    userId:用户ID
    返回：{"result":[{"num":"1","nums":0,"tasktype":"1"}],"flag":"1"}
    num：为需要的待办数量值
### 2,云邮功能
    需求：点进云邮界面之后，返回按钮直接返回到外层界面，不需要goBack，其他跳转不影响。
    实现：监听跳转URL，如果URL中包含"mobileMailController"就是云邮界面，做相应处理即可。
## 我的界面
    
    
    
    
# 需求
## 2018-11-29
### APP名称 logo展示根据系统更改
    app消息界面名称 
    app登录界面logo
    
### 云盘与文件系统大修改
    聊天界面
    长按文件消息的提示菜单增加“云盘”菜单，可以把当前文件存到云盘的“个人网盘”里；图片等，文件形式的消息
