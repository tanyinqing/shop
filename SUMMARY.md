* [导读](README.md)



* 后台管理员模块
     * [后台管理员实体类](/src/cn/itcast/shop/adminuser/vo/AdminUser.java)
	 * [后台管理员的映射文件](/src/cn/itcast/shop/adminuser/vo/AdminUser.hbm.xml)
	 * [后台管理员的action层](/src/cn/itcast/shop/adminuser/action/AdminUserAction.java)
	 * [后台管理员Service层](/src/cn/itcast/shop/adminuser/service/AdminUserService.java)
	 * [后台管理员Dao层](/src/cn/itcast/shop/adminuser/dao/AdminUserDao.java)
* 前台购物车模块
 	 * [前台购物车实体类](/src/cn/itcast/shop/cart/vo/Cart.java) 	
	 * [前台购物车实体类的映射文件](/src/cn/itcast/shop/cart/vo/CartItem.java)
	 * [前台购物车的action层](/src/cn/itcast/shop/cart/action/CartAction.java)
	 * [前台购物车Service层]()
	 * [前台购物车Dao层]()

* 前台一级分类模块
 	 * [前台一级分类实体类](/src/cn/itcast/shop/category/vo/Category.java) 	
	 * [前台一级分类实体类的映射文件](/src/cn/itcast/shop/category/vo/Category.hbm.xml)
	 * [前台一级分类的action层](/src/cn/itcast/shop/category/action/CategoryAction.java)
	 * [前台一级分类Service层](/src/cn/itcast/shop/category/service/CategoryService.java)
	 * [前台一级分类Dao层](/src/cn/itcast/shop/category/dao/CategoryDao.java)
	 * [前台一级分类后台管理的action层](/src/cn/itcast/shop/category/adminaction/AdminCategoryAction.java)

* 前台二级分类模块
 	 * [前台二级分类实体类](/src/cn/itcast/shop/categorysecond/vo/CategorySecond.java) 	
	 * [前台二级分类实体类的映射文件](/src/cn/itcast/shop/categorysecond/vo/CategorySecond.hbm.xml)
	 * [前台二级分类的action层]()
	 * [前台二级分类Service层](/src/cn/itcast/shop/categorysecond/service/CategorySecondService.java)
	 * [前台二级分类Dao层](/src/cn/itcast/shop/categorysecond/dao/CategorySecondDao.java)
	 * [二级分类后台管理的action层](/src/cn/itcast/shop/categorysecond/adminaction/AdminCategorySecondAction.java)
	 * [后台二级分类的列表页面](/WebRoot/admin/categorysecond/list.jsp)
	 * [添加二级分类的页面](/WebRoot/admin/categorysecond/add.jsp)

* 前台商品管理模块  
	 * [前台商品的实体对象](/src/cn/itcast/shop/product/vo/Product.java)
	 * [前台商品的映射文件](/src/cn/itcast/shop/product/vo/Product.hbm.xml)
	 * [前台前台商品的Action对象](/src/cn/itcast/shop/product/action/ProductAction.java)
	 * [后台商品管理的Action](/src/cn/itcast/shop/product/adminaction/AdminProductAction.java)	
	 * [前台商品信息的数据持久层](/src/cn/itcast/shop/product/dao/ProductDao.java)
	 * [前台商品的业务层代码](/src/cn/itcast/shop/product/service/ProductService.java)	
	 * [后台商品列表页面](/WebRoot/admin/product/list.jsp)
	 * [后台商品信息修改的页面](/WebRoot/admin/product/edit.jsp)
* 前台订单管理模块  
	 * [前台订单信息的数据持久层](/src/cn/itcast/shop/order/dao/OrderDao.java)
	 * [前台订单的业务层](/src/cn/itcast/shop/order/service/OrderService.java)
	 * [前台订单管理的action层](/src/cn/itcast/shop/order/action/OrderAction.java)
	 * [后台订单管理的action层](/src/cn/itcast/shop/order/adminaction/AdminOrderAction.java)
	 * [后台订单列表](/WebRoot/admin/order/list.jsp)
	 * [后台订单详情的列表项](/WebRoot/admin/order/orderItem.jsp)
	 * [前台订单实体类](/src/cn/itcast/shop/order/vo/Order.java) 	
	 * [前台订单实体类的映射文件](/src/cn/itcast/shop/order/vo/Order.hbm.xml)
	 * [前台订单项实体类](/src/cn/itcast/shop/order/vo/OrderItem.java) 	
	 * [前台订单项实体类的映射文件](/src/cn/itcast/shop/order/vo/OrderItem.hbm.xml)

* 前台访问首页模块
 	 * [模板实体类]() 	
	 * [模板实体类的映射文件]()
	 * [前台访问首页的action层](/src/cn/itcast/shop/index/action/IndexAction.java)
	 * [模板Service层]()
	 * [模板Dao层]()
	 * [模板后台管理的action层]()
	 * [后台的权限拦截器](/src/cn/itcast/shop/interceptor/PrivilegeInterceptor.java)

* 前台用户模块
 	 * [前台用户实体类](/src/cn/itcast/shop/user/vo/User.java) 	
	 * [前台用户实体类的映射文件](/src/cn/itcast/shop/user/vo/User.hbm.xml)
	 * [前台用户的action层](/src/cn/itcast/shop/user/action/UserAction.java)
	 * [前台用户Service层](/src/cn/itcast/shop/user/service/UserService.java)
	 * [前台用户Dao层](/src/cn/itcast/shop/user/dao/UserDao.java)
	 * [前台用户后台管理的action层](/src/cn/itcast/shop/user/adminaction/UserAdminAction.java)
	 * [验证码Action类](/src/cn/itcast/shop/user/action/CheckImgAction.java)
	 * [校验用户信息](/src/cn/itcast/shop/user/action/UserAction-user_regist-validation.xml)

* 工具类	 
	 * [分页类的封装](/src/cn/itcast/shop/utils/PageBean.java)
	 * [分页的回调方法](/src/cn/itcast/shop/utils/PageHibernateCallback.java)  
	 * [权限拦截器](/src/cn/itcast/shop/interceptor/PrivilegeInterceptor.java)	
	 * [发送邮件的工具类](/src/cn/itcast/shop/utils/MailUitls.java)
	 * [生成随机字符串的工具类](/src/cn/itcast/shop/utils/UUIDUtils.java)  


* 搭建开发环境:     
     * [applicationContext全局变量的配置](/src/applicationContext.xml) 	
	 * [ 数据库的连接信息](/src/jdbc.properties)
	 * [log4j的配置](/src/log4j.properties)
	 * [struts配置action和service和dao](/src/struts.xml)
	 * [web的配置](/WebRoot/WEB-INF/web.xml)
	
* 首页页面
    
     * [菜单的通用静态页面 好几个页面都需要](/WebRoot/WEB-INF/jsp/menu.jsp)
     * [注册的静态页面](/WebRoot/WEB-INF/jsp/regist.jsp)
     * [注册成功的回显页面](/WebRoot/WEB-INF/jsp/msg.jsp) 
     * [首页](/WebRoot/WEB-INF/jsp/index.jsp)
     * [登录页面](/WebRoot/WEB-INF/jsp/login.jsp)  
     * [商品详情展示的页面](/WebRoot/WEB-INF/jsp/product.jsp)
     * [分类的商品列表](/WebRoot/WEB-INF/jsp/productList.jsp)
     * [购物车对应的页面](/WebRoot/WEB-INF/jsp/cart.jsp)
     * [默认的首页  根目录下](/WebRoot/WEB-INF/jsp/index.jsp)
     * [订单对应的页面](/WebRoot/WEB-INF/jsp/order.jsp)
     * [我的订单的显示，就是遍历订单](/WebRoot/WEB-INF/jsp/orderList.jsp) 
     * [后台管理页面登录](/WebRoot/admin/index.jsp)
     * [后台管理主页面](/WebRoot/admin/home.jsp)
     * [后台一级分类列表](/WebRoot/admin/category/list.jsp)
     * [后台一级分类添加](/WebRoot/admin/category/add.jsp)
     * [后台一级分类编辑](/WebRoot/admin/category/edit.jsp)     




* 模板模块
 	 * []() 	
	 * []()
	 * []()
	 * []()
	 * []()
	 * []()

模板实体类
模板实体类的映射文件
模板的action层
模板Service层
模板Dao层
模板后台管理的action层
 	 
	

	 

	 



   
     
  

