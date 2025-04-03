# CoCoME

## 任务一：结构化自然语言建模

​	在本任务中，描述了作为客户的四种需求：浏览商品、添加商品、结账和退货；管理员的三种需求：管理退货、管理监控状态、分析销售数据；以及供应商的两种需求：接受采购订单和推荐新商品。满足**新增用户需求数量8条、系统需求数量15条**。

### ![image-20250401211033525](C:\Users\MiaJ\AppData\Roaming\Typora\typora-user-images\image-20250401211033525.png)

![image-20250401211606975](C:\Users\MiaJ\AppData\Roaming\Typora\typora-user-images\image-20250401211606975.png)

![image-20250401211731697](C:\Users\MiaJ\AppData\Roaming\Typora\typora-user-images\image-20250401211731697.png)

## 任务二：UML需求建模

### 1.用例图

​	**新增用户角色2个**：顾客和供应商。**新增用例9个**，分别是：管理员的analyzeSalesData、manageSurveillance、manageReturn；顾客的browseProducts、addProductsToCart、returnProducts、checkOut；供应商的recommendNewProducts、acceptPurchaseOrder。并且acceptPurchaseOrder里面include两个用例。

![image-20250401212117251](C:\Users\MiaJ\AppData\Roaming\Typora\typora-user-images\image-20250401212117251.png)

### 2.系统顺序图

​	**系统顺序图新增4个**，分别是acceptPurchaseOrder、checkOut、manageReturn、returnProducts。除此之外，还修改了原有的ProcessSale顺序图。相应的，**新增系统操作总数19个**，**新增系统合约数17个**。

![image-20250401212622151](C:\Users\MiaJ\AppData\Roaming\Typora\typora-user-images\image-20250401212622151.png)

![image-20250401212836172](C:\Users\MiaJ\AppData\Roaming\Typora\typora-user-images\image-20250401212836172.png)

![image-20250401212859750](C:\Users\MiaJ\AppData\Roaming\Typora\typora-user-images\image-20250401212859750.png)

![image-20250401212951731](C:\Users\MiaJ\AppData\Roaming\Typora\typora-user-images\image-20250401212951731.png)

![image-20250401213115255](C:\Users\MiaJ\AppData\Roaming\Typora\typora-user-images\image-20250401213115255.png)

### 3.概念类图

​	**新增类9个**，分别是ReturnRequest、SurveillanceDevice、SalesDataAnalysisResult、Customer、Alipayment、WechatPayment、Administrator、RecommendedProduct、PurchaseOrder。除此之外，还修改了若干类。

![image-20250401213704602](C:\Users\MiaJ\AppData\Roaming\Typora\typora-user-images\image-20250401213704602.png)

## 任务三：UML需求原型化与需求确认

​	原型化结果如下：

![image-20250331183600711](C:\Users\MiaJ\AppData\Roaming\Typora\typora-user-images\image-20250331183600711.png)