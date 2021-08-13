# miniprogram

有感情日历、记事本（feeds）、postFeed、关键日期倒计时等

# 参考

开发指南
https://developers.weixin.qq.com/miniprogram/dev/framework/

微信小程序设计指南
https://developers.weixin.qq.com/miniprogram/design/

开发者资源 /HTTP API 文档 /数据库 /插入记录
https://developers.weixin.qq.com/minigame/dev/wxcloud/reference-http-api/database/databaseAdd.html

两年前花了一个周末写的，比较粗糙，可以看看👆的文档，比较友好

## 核心文件

1. app.json , 整体ui外框描述
2. app.js  ， wx.cloud.init  是云函数配置
3. functions 目录， 是云函数
4. page目录下，只各个页面，postList下面是帖子列表， postSend是发帖
5. 彩蛋，是播放有弹幕的视频，在memory/index.wsml   <video id="myVideo"


                                            
## db   
annivesary                                           
{
    "_id": "xxxxxxxxx",
    "marryBegin":
    {
        "$date": "2021-01-01T01:09:09Z"
    },
    "loveBegin":
    {
        "$date": "2021-01-01T21:20:00Z"
    },
    "loveId": "\"1\""
}

     

post   
{
"_id": "XCtnQXSWatl7",
"userInfo":
{
"country": "China",
"avatarUrl": "https://9KYhM4bic7Rick6UQyxAQ/132",
"nickName": "",
"gender": 1,
"language": "zh_CN",
"city": "Hangzhou",
"province": "Zhejiang"
},
"message": "加班做小程序",
"imageFileIDList":
[
"cloud://online-2071e6.6f6e-online-2071e6/2013418.png"
],
"createTime":
{
"$date": "2019-01-01T13:12:33.948Z"
},
"_openid": "o7sqe4kVvQUkv2fJgPxI"
}
