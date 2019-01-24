# 逃离北上广

>[项目主页](https://jiangwei1995910.github.io/getAwayBSG/)

## What!

如果你是一个正准备逃离北上广等一线城市却又找不到去处的IT人士，或许这个项目能给你点建议。

## Desc

或许你跟我一样困惑，为此我通过爬虫抓取了智联招聘跟链家这2个平台的全部数据。最终拿到了18W+全国各个城市的招聘数据与81W+全国各地的房屋成交记录数据。

其中，招聘数据我抓取了工作年限，公司名称，公司规模，公司类型，工作类型，创建时间，工作名称，结束时间，教育情况，薪资字段。

职位我使用了['php', 'java', 'python', 'c/c++', 'c#', 'mysql', 'oracle', 'javascript', 'linux', 'SQL', '软件', '程序员']作为关键词搜索。基本上涵盖了程序猿们绝大部分工作

对应房屋成交记录，我抓取了成交时间，成交价格，每平米均价，地址字段。

## 分析

### 薪资

首先，我计算了各个城市的平均薪资情况，为什么不包含博士学历呢？因为智联上面写明要博士的职位很少(硕士其实也不多，只有几百的量)，抓下来每个城市都是几十的量，这种数据不具有统计意义如下：

![](./docs/img/avg.png)

可见，硕士的薪资跟本科比并没多大差距。另外，别小看了拉萨，拉萨的薪资并不低，但是方差特别大，说明如果你愿意去拉萨，其实你的薪资会很高，平均薪资低是因为有很多1000 2000的工作拉下去的

其他都是意料之中的了


其实，平均值并没有多大参考意义，因为被平均的东西太多了，比如工龄就是很重要一个，于是我又取了各工龄的情况，如下

![](./docs/img/workTime.png)

### 房价

对于一个地方是否合适自己发展，房价非常重要，于是我也分析了各个城市的房价数据。





## 未完成 TODO
