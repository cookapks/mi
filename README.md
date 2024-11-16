##  ⚠ 背景
由于小米商城任务会变动，因此需要频繁更新任务列表。  
本仓库用于使用了自动做“小米商城做任务”的用户上传最新的任务列表。每一个使用者都可以上传，也十分欢迎自己提交任务列表。  
当你使用的“小米商城做任务”脚本提示“可能已刷新最新任务”时，请自己手动及时提交任务列表的响应体到本仓库，因为如果不及时更新可能导致账号黑号等情况。

## 📌 本仓库用于上传最新的小米商城任务
使用方法如下：  
1. 抓取小米商城app，如下请求(点击“我的”-“米金”-“去完成”即可抓到此包)中的响应体
```
https://shop-api.retail.mi.com/mtop/navi/venue/batch 
```  

2. 将响应体全部进行提交到mi.txt文件中，等审核通过能用了。如果你不能确定自己的响应体是不是正确的，可以看下mi.txt中的格式，基本一致就说明正确。  
mi.txt格式如下：  
```json
{"traceId":"","code":0,"attachments":{"timestamp":""},"data":{"result_list":[{"amountTotal":760,"jumpUrl":"","tipList":["完成每日签到赚米金","积攒米金兑超级好物"],"waitArrival":0,"waitReceiveList":[],"waitReceiveTotal":0},{"components":[{"actId":"6706c0695404a23dfb5b2cab","taskId":"6706c0695243011f230d465d","taskName":"米金签到","taskDesc":"","taskType":200,"finishedNumber":0},{"actId":"6706c0695404a23dfb5b2cab","taskId":"6706edf30344c966c5b46681","taskName":"来会员中心 领专属好券","taskDesc":"浏览10秒+10米金","taskType":200,"finishedNumber":0},{"actId":"6706c0695404a23dfb5b2cab","taskId":"670f6baf1d65ee598c4fc39d","taskName":"新客专享福利","taskDesc":"浏览10秒+10米金","taskType":200,"finishedNumber":0},{"actId":"6706c0695404a23dfb5b2cab","taskId":"670fa2ba57e9a97a89265b63","taskName":"逛手机频道 选心动手机","taskDesc":"浏览10秒+10米金","taskType":200,"finishedNumber":0},{"actId":"6706c0695404a23dfb5b2cab","taskId":"6720abdc4015d32aaaa400bc","taskName":"Xiaomi 15系列 新品手机","taskDesc":"浏览10秒+10米金","taskType":200,"finishedNumber":0}]},{"components":[{"actId":"","taskId":"","taskName":"米金抽奖","taskDesc":"","taskType":128,"finishedNumber":0,"totalNumber":20,"startTime":1720000000000,"endTime":1730000000000,"status":2,"scores":0,"singleCostScores":30,"costType":2,"cycleTime":0,"taskRefreshWay":0,"upperLimit":20,"canDo":true}]}]},"message":"ok"}
```

## 🚚 其他
提交方法简述：和正常提交代码一样，先fork本仓库，然后在fork的仓库中提交即可（提交有两步，第一步的提交时提交到的是你自己的仓库，第二步是需要在pull requests中提交，此时主仓库就能看到了。可以参考这个链接的提交教程（这里是使用命令提交的，不会使用命令的可以直接在github网页上修改提交，效果是一样的）：https://blog.csdn.net/m0_72619231/article/details/131501772），注意是修改mi.txt文件，其他文件不需要管。  
如果你不知道如何使用github提交，请先先抓取上述的响应体，并将内容提交到issue中，备注上抓包的时间方便确认是否时最新的任务。等待其他使用者看到后会帮忙提交的。  



## ✈️ 群和频道 
🔮 <a href="https://t.me/mokuchat">@mokuchat</a><br>
📻️ <a href="https://t.me/mokuchannel">@mokuchannel</a>

## 🍨 教程 
📖 <a href="https://jewel-pullover-9d0.notion.site/dfec17946a164658bb77e9682df954a2?pvs=4">艾默库教程</a>

