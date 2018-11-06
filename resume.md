[toc]
## 联系方式

- 手机：17691345411 
- 邮箱：failymao@live.com
- QQ/微信：991378415


## 个人信息

- 姓名/性别/年龄：毛义飞/男/1990
- 湖北汽车工业学院   2011年毕业
- 工作年限：2年
- 职位：python/golang/区块链开发
- 期望城市： 西安
- 目前状态：正在找工作（1周内可上岗）
- 博客: [Blog](https://www.cnblogs.com/failymao/)
- Github: [https://github.com/evilmao](https://github.com/evilmao)
- 区块链社区: ![](http://ww1.sinaimg.cn/large/8599e4cfly1fwyft76dd1j2076076glt.jpg)

## 工作经验

###  **西安哈希码科技有限公司**    (2018.2--2018.11)

#### * 项目一：Etherum_Dapp_Wallet 
> * 项目地址：[Wallet](https://github.com/evilmao/Ethereum-dapp-wallet)
> * 项目时间：2018.5-2018.7
> * 项目简介：基于以太坊Ethereum公链,使用solidity语言开发一套游戏币, 采用 mysql +Redis方式存储账户代币信息, 用户信息私钥完全客户端用户自己保留, 中心化mysql只实现交易流水记录; 所有交易记录上链,redis用于缓存用户信息,达到快速响应. 通过封装的rpc接口实现交易查询操作. 
  * 职责指责：
  ```json
    1.详设文档及接口文档设计；
    2.代币智能合约编写；
    3.公链节点搭建与测试；
    4.数据库模块编写；
    5.交易模块代码编写；
    6.性能测试
  ```
  
#### * 项目二：Haxicode
> * 项目地址：[Haxicode](https://github.com/xianhashchain)
> * 项目时间：2018.7-2018.11
> * 项目简介：基于以太坊，新增Dpos共识机制的公链 -----> 完全移除原Pow算法,结合EOS的dpos的原理, 修改Ethereum源码, 嵌入Dpos算法, 同时使各其他参数以创世块配置的方式达到灵活调整出块间隔及节点数量.方便私链调试!

职责指责：
``` json
  1.环境搭建;
  2.Dpos算法逻辑代码编写
  3.p2p模块维护
  4.bug修复
  5.测试用例匹配
  6.性能测试
```

###  **摩石环球科技**    (2017.02--2018.02)

#### * 项目一： 鑫圣金业积分商城
> * 项目时间：2017.11-2018.02
> * 项目简介：根据公司产品需求为公司搭建的积分兑换电商网站，使用 Django 框架实现。 该项目主要包括用户模块，商品信息模块，购物车模块，订单管理模块，商品搜索， 订单支付模块等。使用Redis 对查询的数据进行缓存。比如分页的数据，采用缓存进行预先查询，减少数据库的交互。

职责指责：
``` json
 1.用户模块：用户注册、登陆，个人信息修改与完善。 
 2.商品模块：展示网站首页、分类页、商品详情页的商品。 
 3.购物车模块：完成商品的添加、删除、修改、购买等操作。 
 4.使用 Redis 对查询的数据进行缓存。
```
#### * 项目二：Flask_InfluxDB_API
> * 项目地址:[Flask_InfluxDB_API](https://github.com/evilmao/Flask_InfluxDB_API)
> * 项目时间：2017.07-2017.11
> * 项目简介：基于Flask框架，结合基本的认证机制，设计API接口，接收从开发服务器获取的所有信息，插入到运维部本地InfluxBD数据库，结合本机监控软件（类似Grafanna）获取相关错误信息。

职责指责：
```json
内部使用:完全独立开发
```

#### * 项目三: Dingding_robot
> * 项目地址:[Dingding_robot](https://github.com/evilmao/Dingding_robot)
> * 项目时间：2017.06-2018.2017.07
> * 项目简介：运维自动化监控工具, 基于requests+钉钉机器人+JIRA+influxDB监控自动发送到相关负责人

职责指责：
```json
内部使用:完全独立开发
```
###  **开源项目**   (2017.04--2017.07)
> * 项目地址:[MS_AutoTest](https://github.com/evilmao/python_auto_test/tree/master/XSTZ_Test_framework)
> * 项目简介: 有效解决运维监控长期处于被动监控的局面！被动监控往往通过研发团队给予指定的参数，通过API接口获取到服务器数据！被动监控存在一定的盲区：服> 务器正常，但是客户在前端使用产品时，出现功能故障，出现页面崩溃，js加载超时，连接失效，超时等现象，MS_AutoTest项目通过python+selenium模拟用户行为> 通过监控html/wap/app功能对应元素在设置时间内（超时时间）是否成功加载，从而判断产品某项功能，是否正常；结合Jenkins+Git持续集成，根据产品迭代频率，> 设置定时任务实现7*24主动监控；当监控出错误时触发截屏，并实时插入html文档，并通过Nginx发布至局域网内，测试完毕后将触发钉钉机器人发送监控报告，同时> > 将收集错误数据插入influxDB，结合Grafana将重点bug展示，从而及时优化产品质量
> * 项目过程: 基于unitest单元测试框架，web端使用selenium，移动app端使appium，模拟用户对产品进行点击操作，从而实现UI自动化测试功能，项目难点一：支付通道验为动态验证点，无法确定某时某刻支付通道个数和每个支付通道跳转后的预期验证点；采用ddt数据驱动模型，先从支付页面获得当前支付通道明细，读取excel
预设验证点，构建ddt原始数据，从而极大减少了代码重复；难点二，验证错误时无法时事截图，并插入到html文档中，通过装饰器，将每个测试函数作为内部函数，当 生异常时处罚截图；通过抛出异常将当前截图路径发送至HTMLRunner.py基础数据中，插入到当前测试点上.

### **业余项目**
- 数据分析 :爬虫
  - [selenium_spider](https://github.com/evilmao/Python_Selenium_Spider)
    - 结合selenium+PantomJs/Chrome+MongoDB爬取淘宝搜索相关宝贝信息
  - [Scrapy_spider](https://github.com/evilmao/scrapy_spider)
     - 使用scrapy + mongodb + redis 爬取阿里巴巴国际网站亿万数据
- 小工具: 性能测试
  - [loading_test](https://github.com/evilmao/XSTZ_loading_test)
    - 基于python开发的一套服务器性能测试通用脚本工具

  <br>
  <br>
  <br>

## 经历
[♥ 不管人生怎么走，都需要实时回头看看 ♥](http://www.cnblogs.com/failymao/p/8699180.html)
**&emsp;上帝不是傻子,努不努力,他一眼就看透了,所以,别骗自己!**<br>


<br>

<br>

<br>

## 技能清单

- Web开发: python （熟练）,Go(熟练) 
- Web框架：Django（熟练）,Bin/Bengo(熟悉)
- 数据库：MySQL/SQLite/Redis（熟练）
- 前端框架：bootstrap3/HTLM5/CSS/JS 
- 数据分析处理：Beautifulsoup,scrapt框架
- 区块链: Ethereum. BTC. Eos, Cardano
- 智能合约: solidity(熟悉)
- 版本管理： Git/SVN/Gitlab熟练
- 单元/集成测试：unitest/JIRA/Jenkins（熟练）
- 运维部署：熟悉Nginx、uwsgi、Docker、Celery
- 开发环境： Centos/ubuntu
## 语言能力

- 英语（听说读写熟练） CET4
- 普通话（流利）

## 兴趣爱好

- 爱好写作，看书
- 喜欢吉他
- 撸代码

## 致谢
**非常感谢您花时间阅读我的简历，期待能有机会和您共事,并希望能给出宝贵的意见！**
<hr>








