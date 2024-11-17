##  ⚠ 背景
由于小米商城任务会变动，因此需要频繁更新任务列表。在本仓库的**issue**中“小米商城做任务”提交最新的任务列表。  
我写了自动化脚本获取评论中的最新的任务列表，每一个使用者都可以提交“**issue**”，也十分欢迎自己提交任务列表，注意是**提交issues**，（就是正常提问题，不需要fork仓库）。    
当你使用的“小米商城做任务”脚本提示“可能已刷新最新任务”时，请自己手动及时提交任务列表的响应体到**issue**中，因为如果不及时更新可能导致账号黑号等情况。

## 📌 提交最新的小米商城任务列表的步骤如下 
1. 抓取小米商城app，如下请求(点击“我的”-“米金”-“去完成”即可抓到此包)中的响应体
```
https://shop-api.retail.mi.com/mtop/navi/venue/batch 
```  

2. 将内容提交到**issue**中，标题为：抓包时间+任务列表响应（参考问题模板提交），如：“20241116任务列表响应”。  
如果你不能确定自己的响应体是不是正确的，可以看下issues模板的格式，基本一致就说明正确（特征是含有result_list）。  
格式如下：  
```json
{"traceId":"","code":0,"attachments":{"timestamp":""},"data":{"result_list":[{"amountTotal":760,"jumpUrl":"","tipList":["完成每日签到赚米金","积攒米金兑超级好物"],"waitArrival":0,"waitReceiveList":[],"waitReceiveTotal":0},{"components":[{"actId":"6706c0695404a23dfb5b2cab","taskId":"6706c0695243011f230d465d","taskName":"米金签到","taskDesc":"","taskType":200,"finishedNumber":0},{"actId":"6706c0695404a23dfb5b2cab","taskId":"6706edf30344c966c5b46681","taskName":"来会员中心 领专属好券","taskDesc":"浏览10秒+10米金","taskType":200,"finishedNumber":0},{"actId":"6706c0695404a23dfb5b2cab","taskId":"670f6baf1d65ee598c4fc39d","taskName":"新客专享福利","taskDesc":"浏览10秒+10米金","taskType":200,"finishedNumber":0},{"actId":"6706c0695404a23dfb5b2cab","taskId":"670fa2ba57e9a97a89265b63","taskName":"逛手机频道 选心动手机","taskDesc":"浏览10秒+10米金","taskType":200,"finishedNumber":0},{"actId":"6706c0695404a23dfb5b2cab","taskId":"6720abdc4015d32aaaa400bc","taskName":"Xiaomi 15系列 新品手机","taskDesc":"浏览10秒+10米金","taskType":200,"finishedNumber":0}]},{"components":[{"actId":"","taskId":"","taskName":"米金抽奖","taskDesc":"","taskType":128,"finishedNumber":0,"totalNumber":20,"startTime":1720000000000,"endTime":1730000000000,"status":2,"scores":0,"singleCostScores":30,"costType":2,"cycleTime":0,"taskRefreshWay":0,"upperLimit":20,"canDo":true}]}]},"message":"ok"}
```


## ✈️ 群和频道 
🔮 <a href="https://t.me/mokuchat">@mokuchat</a><br>
📻️ <a href="https://t.me/mokuchannel">@mokuchannel</a>

## 🍨 教程 
📖 <a href="https://jewel-pullover-9d0.notion.site/dfec17946a164658bb77e9682df954a2?pvs=4">艾默库教程</a>

