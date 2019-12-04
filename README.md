# 豆组筛选
豆瓣小组爬虫微信小程序版本
* 支持添加任意小组（一般就用在租房小组）
* 多关键词置顶、过滤
* 中介过滤 40%+

![截屏](https://i.loli.net/2019/11/03/mRWHVG2NCilBwX1.jpg)<br/>
<img src="https://i.loli.net/2019/11/03/CZoJDXVwh4lAmdH.png" height="400" style="margin-right: 10px;" />
<img src="https://i.loli.net/2019/11/03/Y91QVhXxSFo3ypO.png" height="400" />


## 背景
* 豆瓣自带搜索功能太简单了
* 租房小组中介太多，没有自动过滤
* 其它工具会限定在某些小组里面，无法自定义


## Todo
* [x] 订阅小组管理
* [x] 置顶关键词
* [x] 屏蔽关键词
* [x] pages/帖子详情页
* [x] pages/帮助说明
* [x] 刷新列表
* [x] 加载下一页
* [ ] 中介过滤规则
  * [ ] 测试用例
  * [x] 名字、发帖数、回帖数
  * [ ] 豆瓣资料分析（中介可能性）
    * 注册时间
    * 常去小组
    * 发过的帖子
  * [ ] 贝叶斯垃圾邮件
  * [ ] 缓存中介信息
* [*] 一键导入小组:根据城市导入常用小组
* [*] 小组id显示为小组名称
* [ ] 订阅小组等Input组件交互优化
* [ ] [水木社区](http://www.newsmth.net/nForum/#!board/HouseRent)
* [ ] 分享
* [ ] 收藏


#### 其它
* 优化：信息过多时，点击“显示中介信息”会有1s的延迟


## 启动
* [安装Taro](https://nervjs.github.io/taro/docs/GETTING-STARTED.html)
* npm i
* npm run dev:weapp
* 微信开发者工具导入项目`./dist/weapp`


## 最后
本项目仅供学习使用，请勿商用，否则后果自负（狗头
