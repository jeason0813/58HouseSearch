### 58同城品牌公寓爬虫


### 2016.09.11
1. 重构搜索页面请求，改为JS异步请求数据
2. 改进上次重构的JS结构


### 2016.08.25
1. 上线步行导航,满足需要步行上班的狼友们
2. 辣鸡前端代码等待重构，实在没法看下去了


### 2016.08.24
1. 58品牌公寓、58诚信租房完成页面改造
2. 自动加载前20页数据，按价格区间显示


### 2016.08.24
1. 去除互助租房页面价格标签，改用价格区间图标
2. 新增价格区间图标，第一版为渐变色，效果还好
3. 薪资价格区间相关数据，下版本完成其余页面改造


### 2016.08.23
TODO:
1. 新增问题反馈,邮件服务?限制IP？JSON记录？
2. 侧边栏调整，移动地图的时候不是很方便

### 2016.08.23
1. 新增侧边栏功能，页面初始化打开侧边栏，点击其余页面收起侧边栏(感觉也不是很好,回头优化一下)
2. 优化前台CSS代码（其实只是收成了一个CSS文件，逃...
3. 价格标签过多之后密集恐惧症发作的小伙伴等下一次更新（明天？


### 2016.08.22
1. 互助租房页面新增价格标签，地图上可直接显示价格
2. 为了避免缩放工具栏挡住导航信息，调整导航栏位置
TODO：优化58同城查询速度，新增价格标签，互助租房新增价格过滤



### 2016.08.21
1. 新增“上海互助租房数据”，此项目房源基本真实可靠，无中介。详情见微博：http://weibo.com/u/5389952376
2. 优化获取互助租房数据，200条数据基本在1秒内可以拿的到
3. 由于数据时效性问题，互助租房数据原则上只取前200条数据
4. TODO：互助租房价格过滤（互助租房不提供过滤，只能自己做）？非上海互助租房数据（感觉没有...）？
5. 感谢互助租房项目（http://www.huzhumaifang.com/）。



### 2016.08.21
1. 修复一个获取数据正常，地图无法显示数据的bug（衣衣重构代码弄出来的...）
2. 经测试后发现，某些地图没有诚信房源数据（考虑这种情况是否直接取个人出租信息）


### 2016.08.20
1. 继续感谢衣衣重构的代码，广告数据也基本过滤了
2. 地图房源显示直接附上租金，更换房源链接之后实现直接定位到具体房源
3. 去除不必要的JS文件，使得两个页面使用同一个JS


### 2016.08.20
1. 新增“58同城诚信房源”（PS：看了下房源，感觉一点都不诚信...只能祝好运了。）
2. 有点想去抓微博某账号数据，不过微博这种鬼...想放着吧。
3. TODO：优化一下查询速度（感觉可以并发请求页面，不过我的辣鸡服务器是否扛得住是个问题）；去除页面广告数据


#### 2016.08.13
1. 更新后同步挂载于： http://codelover.link:8080
2. 下一步准备加入更多的房源信息(PS:只是准备...)
3. 知乎专栏无耻求赞（ https://zhuanlan.zhihu.com/p/21998221）

#### 2016.08.13
1. 加入城市名匹配58同城城市简称功能，去除城市名转拼音导致无法准确定位城市问题
2. 继续感谢衣衣姐去除58同城广告数据的commit


##### 2016.08.13
1. 去除输入城市名定位问题，改为移动地图直接获取地图中心所在城市
2. 下一步准备构建城市名-城市简称字典，用于快速匹配正常的58同城地址
3. 修复已知bug...

##### 2016.08.12
1. 感谢衣姐的重构代码的commit
2. 修复输入城市中文名导致地图房子位置点击后跳转页面错误问题
3. 输入城市名无法直接定位到城市这个问题正在解决


##### 2016.08.08
1. 完成指定城市名定位
2. 修复上版本bug
3. 更正为全国版


##### 2016.08.7
1. 改版于 https://zhuanlan.zhihu.com/p/21883516
2. 使用高德地图API
3. 挂载于 http://codelover.link:8080
4. 手动输入城市名还有点bug，暂时无法正常使用