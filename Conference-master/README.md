# Conference
###主要文件
tab-dash.html 界面
service.js  各类factory
controller.js  各类controller

###函数(controller文件) 需要修改 add标识
requestMeeting()
获取后端会议 并绑定于前端meeting_info
传给后端参数:会议开始时间（start.）结束时间（end.） 持续时长（long.）主题(meeting.theme) 与会人员（需要验证）

getImportantPeople()
获取所有人员名单 
人员参数包含id、name、choose(用于复选框验证，是否选中，默认为false)


###函数(controller文件) 可能需要修改
getChoose()
复选框操作 对于人员choose属性（true/false）
可能有更方便的方法进行验证
