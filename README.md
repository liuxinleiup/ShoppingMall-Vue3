# 基于Vue3购物商场
# 一：技术工具环境
>技术：create-vue、Pinia、ElementPlus、Vue-Router、html5、css3、js、jq   
>工具：vscode   
>环境：node.js、chrome   
# 二：项目功能
 首页模块、分类模块、商品详情模块、登录模块、购物车模块、填写订单模块、支付模块、用户中心 
 ***
	1.首页模块：分类数据渲染、轮播图业务实现 、面板业务组件封装、推荐业务实现、图片懒加载指令实现  
	2.分类模块：  
		商品一级分类模块：面包屑导航功能实现、Banner轮播图功能实现、分类列表功能实现  
		   	路由缓存问题解决 （key + onBeforeRouteUpdate）、基于业务逻辑的函数拆分(useBanner + useCategory)   
		商品二级分类模块：基础列表渲染、筛选功能实现、无限滚动分页功能实现、定制router scrollBehavior  
	3.商品详情模块：组件和路由配置、基础业务内容渲染、图片预览组件封装、热榜组件封装实现（prop + 常量数据适配）、sku组件熟悉使用、通用型组件插件化统一注册  
	4.登录模块：整体业务认识和路由配置、表单校验实现、基础登录业务实现、pinia管理用户数据、pinia数据持久化(pinia-plugin-persistedstate)、退出登录实现  
	5.购物车模块：合并删除修改加入购物车、获取购物车列表  
	6.填写订单模块：添加删除修改获取收货地址、生成获取支付提交订单  
	7.支付模块：支付功能实现、支付结果展示、useCountDown逻辑函数封装  
	8.用户中心：三级路由拆分、个人中心、我的订单  


# 三：界面展示
## 1.首页
<span style="color:#333333"><img src="https://s1.imagehub.cc/images/2023/06/07/553681fc399e4ed5bb951cccc5abf9bf.png" width="50%"></span>
## 2.分类
<span style="color:#333333"><img src="https://s1.imagehub.cc/images/2023/06/07/3b1955e5890d51aa73cff79fbff365bb.png" width="50%"></span>
## 3.商品详细
<span style="color:#333333"><img src="https://s1.imagehub.cc/images/2023/06/07/052d6459f9d5937c99d832bca0932524.png" width="50%"></span>
<span style="color:#333333"><img src="https://s1.imagehub.cc/images/2023/06/07/acbb40626f91a2bb3d3c97e5d4307026.png" width="50%"></span>
## 4.登陆
<span style="color:#333333"><img src="https://s1.imagehub.cc/images/2023/06/07/0d3e63c8425e07bec485ab81afb47d5b.png" width="50%"></span>
## 5.购物车
<span style="color:#333333"><img src="https://s1.imagehub.cc/images/2023/06/07/befff64f988cda8928af002989d87d5a.png" width="50%"></span>
## 6.填写订单
<span style="color:#333333"><img src="https://s1.imagehub.cc/images/2023/06/07/eacd382b99105e26368508c329381afe.png" width="50%"></span>
<span style="color:#333333"><img src="https://s1.imagehub.cc/images/2023/06/07/be87e272c627d67d38fd8d6954471af8.png" width="50%"></span>
## 7.支付
<span style="color:#333333"><img src="https://s1.imagehub.cc/images/2023/06/07/U7IOAEZIBSFNY15G6V9.png" width="50%"></span>
<span style="color:#333333"><img src="https://s1.imagehub.cc/images/2023/06/07/da44344e1a0e030de073ca6219c3b88d.png" width="50%"></span>
<span style="color:#333333"><img src="https://s1.imagehub.cc/images/2023/06/07/NLSX9QFJSRRWU10EMT.png" width="50%"></span>

# 四：接口文档
[接口](https://www.apifox.cn/apidoc/shared-c05cb8d7-e591-4d9c-aff8-11065a0ec1de/api-67132167)

# 五：账号密码
    登陆：12056258282                   hm#qd@23!    
    支付：jfjbwb4477@sandbox.com        111111   
# 六：运行
    第一步：在vscode打开项目
    第二步：终端执行下面代码    
            npm i   
            npm run dev     
    第三步：点击Local后面的地址，鼠标ctrl+鼠标左击	    
