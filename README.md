##  👑 背景
由于小米商城任务会变动，因此需经常更新任务列表。  
当你的“小米商城做任务”脚本提示“**可能已刷新最新任务**”时，请手动提交任务列表到**Issues**中，因为若不及时更新可能导致黑号等情况。  
我制作了机器人每2小时同步**Issues**中最新的任务列表，同步成功后脚本即可运行最新的任务。  
每一位使用者都可以往**Issues**提交，也十分欢迎提交任务列表（注意是**提交Issues**，就是正常提问题，不需要fork仓库）。    

## 🐳 提交最新的小米商城任务列表的步骤如下 
1. 抓取小米商城app如下请求的**响应体**(点击“我的”-“米金”-“去完成”即可抓到此包)
```
https://shop-api.retail.mi.com/mtop/navi/venue/batch 
```  

2. 将**响应体**内容提交到**Issues**中（点击“Issues”-“New Issue”-“Get started”，即可按照模板进行提交）  
标题为：抓包时间+任务列表响应，如：“20241117任务列表响应”。内容为：步骤1的响应体。  
如果你不确定自己的响应体是否正确，可以看下Issues模板的格式，基本一致就说明正确（特征是含有result_list）。    
响应体例子如下：  
```json
{"traceId":"","code":0,"attachments":{"timestamp":""},"data":{"result_list":[{"amountTotal":760,"jumpUrl":"","tipList":["完成每日签到赚米金","积攒米金兑超级好物"],"waitArrival":0,"waitReceiveList":[],"waitReceiveTotal":0},{"components":[{"actId":"6706c0695404a23dfb5b2cab","taskId":"6706c0695243011f230d465d","taskName":"米金签到","taskDesc":"","taskType":110,"finishedNumber":0},{"actId":"6706c0695404a23dfb5b2cab","taskId":"6706edf30344c966c5b46681","taskName":"来会员中心 领专属好券","taskDesc":"浏览10秒+10米金","taskType":200,"finishedNumber":0},{"actId":"6706c0695404a23dfb5b2cab","taskId":"670f6baf1d65ee598c4fc39d","taskName":"新客专享福利","taskDesc":"浏览10秒+10米金","taskType":200,"finishedNumber":0},{"actId":"6706c0695404a23dfb5b2cab","taskId":"670fa2ba57e9a97a89265b63","taskName":"逛手机频道 选心动手机","taskDesc":"浏览10秒+10米金","taskType":200,"finishedNumber":0},{"actId":"6706c0695404a23dfb5b2cab","taskId":"6720abdc4015d32aaaa400bc","taskName":"Xiaomi 15系列 新品手机","taskDesc":"浏览10秒+10米金","taskType":200,"finishedNumber":0}]},{"components":[{"actId":"","taskId":"","taskName":"米金抽奖","taskDesc":"","taskType":128,"finishedNumber":0,"totalNumber":20,"startTime":1720000000000,"endTime":1730000000000,"status":2,"scores":0,"singleCostScores":30,"costType":2,"cycleTime":0,"taskRefreshWay":0,"upperLimit":20,"canDo":true}]}]},"message":"ok"}
```

## ✈️ 群和频道 
🔮 <a href="https://t.me/mokuchat">@mokuchat</a><br>
📻️ <a href="https://t.me/mokuchannel">@mokuchannel</a>

## 🍨 教程 
📖 <a href="https://jewel-pullover-9d0.notion.site/dfec17946a164658bb77e9682df954a2?pvs=4">艾默库教程</a>

