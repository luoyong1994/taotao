# taotao
## 分布式商城项目,taotao-parent为父工程,管理所有jar包的版本号

### 功能描述
- 后台管理系统：管理商品、订单、类目、商品规格属性、用户管理以及内容发布等功能。
- 前台系统：用户可以在前台系统中进行注册、登录、浏览商品、首页、下单等操作。
- 会员系统：用户可以在该系统中查询已下的订单、收藏的商品、我的优惠券、团购等信息。
- 订单系统：提供下单、查询订单、修改订单状态、定时处理订单。
- 搜索系统：提供商品的搜索功能。
- 单点登录系统：为多个系统之间提供用户登录凭证以及查询登录用户的信息。
 
### 分布式系统架构
 ![](https://github.com/YYKI/pictures/blob/master/taotao.png?raw=true)
### 技术选型（主要技术）
- Spring、SpringMVC、Mybatis
- JSP、JSTL、jQuery、jQuery plugin、EasyUI、KindEditor（富文本编辑器）、CSS+DIV
- Redis（缓存服务器）
- Solr（搜索）
- httpclient（调用系统服务）
- Mysql
- Nginx（web服务器）
