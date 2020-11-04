### 标准订单下单

介绍如何通过华峰氨纶CRM将标准订单下达到SAP中。

### 文档记录

| 修改日期 | 修改人 | 修改内容 |
| :--- | :--- | :--- |
| 2018-08-15 | 窦卫征 | 新建 |

### 涉及岗位

> 内勤、业务员、办事处主任、营销部长、营销副总、经销商

### 概念解释

| 术语 | 解释 |
| :--- | :--- |
|  |  |

### 业务处理索引

1. APP端下单
2. PC端下单

### 业务处理详细步骤

#### 1.APP端下单：

APP端下单过程为：

> A.选择客户  
> B.选择产品加入购物车  
> C.购物车结算并填写订单  
> D.提交订单

下面为具体操作过程

业务员在APP中首页点击右下角+号，选择新订单，进入如下界面

![](/assets/selectcust.png)

自动带出可见范围客户，选择客户后进入 到选择产品界面

![](/assets/app112244.png)

可以通过批号、规格、产地来搜索产品，输入数量后点击购物车将产品加入购物车，

![](/assets/appdsrlsl1111.png)

> 1.  支持手工输入数量
> 2. 或者点击上面的计算器根据件重，件数计算数量，如下图
>
> ![](/assets/appjsjjjaz18822.png)

之后点击购物车按钮，

![](/assets/1111sdfjalalalxxx.png)



点击右上角我的购物车

![](/assets/appmycartbtn.png)

可以进行结算，进入如下界面

![](/assets/appordersubmit.png)

输入订单类型、请求交货日期、收货地址（如果没有收获地址，可以在此处直接添加新收货地址）等信息，

![](/assets/appaddshdz11.png)

在已选购产品清单处可以左滑删除产品，如下图

![](/assets/apporderitemdel.png)

也可以直接点击某个产品项目进入到编辑界面

![](/assets/apporderitemedit.png)

在此处可以修改产品等级、用途、单价，数量，需要注意：

> * 除非做了特价申请，否则单价低于指导价下限会触发营销部长和营销副总审批
> * 本月订单发货数量如果超出计划量，无法提交订单，需要发起计划外要货申请流程审批后方可下单
> * 单价低于指导价下限，需要选择特批订单类型，并输入订单原因

如果确认无误，就可以提交审批

如果额度不足，提交订单会提示

![](/assets/apporderyebuzu.png)

仍然可以提交订单，但订单提交后会被冻结发货。我们这里确认提交订单，订单提交后会自动跳转到手机端订单中心

![](/assets/appordercenter.png)

如上，我们看到第一个订单就是我们刚刚做的订单，点击进去可以看到详情

![](/assets/pcorderdetail.png)

下方可以看到客户总欠款，到期欠款，信用额度，可用额度等信息

![](/assets/appcustaccount.png)

最下面是订单的日志信息\(包括订单提交、审核、发货等业务日志）

![](/assets/apporderlogs.png)

订单提交后，办事处主任可以在APP端进行审核，

![](/assets/appbsczrspdd1211.png)

点击订单号，查看订单详情，可以看到

![](/assets/appaprovalbtn.png)

点击审核通过订单,

> 对于标准订单办事处主任审批后直接写入SAP
>
> 对于有特价申请的特批订单，办事处主任审批后也会直接写入SAP

写入SAP中的订单会有SAP订单号

![](/assets/approval.png)

写入SAP后，订单状态变为待发货

![](/assets/apporderstatuschanged.png)

#### 2.PC端下单：

在PC端下单，点击左侧在线下单菜单，进入下面界面

![](/assets/pcordersubmit11.png)

对于有业务员且有SAP客户号的客户，可以看到客户后面是有选中按钮的，我们选择一个客户进去

![](/assets/pcchooseprod.png)

输入数量，加入购物车

![](/assets/pcaddmycart11.png)

加入购物车后，可以看到右上角的我的购物车后面的数量会发生变化

![](/assets/pcmycart11.png)

> 区别于APP，PC端我的购物车后面显示的是公斤数

点击我的购物车，进入订单结算页面

![](/assets/pcordersubmit111.png)

可手工调整销售组织、渠道、订单类型、交货日期、产品、收货地址等信息，如果没有问题可以提交订单

> 如果产品表中任何一行单价低于指导价下限，就必须输入低价原因，并设置订单类型为特批订单，否则无法提交

I.如果可用额度不足，会提示

![](/assets/pcordersbmitedbz.png)

II.如果超出计划，会提示

![](/assets/pcjhwsqtx.png)

订单提交后可以在订单中心看到订单信息![](/assets/pcordercenter111.png)

可以在订单中心根据多种条件组合筛选；

可以直接在PC端查看订单详情

![](/assets/pcorderdetail111.png)办事处主任登陆后，可以审批订单

![](/assets/pcbscorderapproved.png)标准订单在办事处主任审批后会自动生成SAP订单号

#### ![](/assets/pcsapordernumbersaved.png)



