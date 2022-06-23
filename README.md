# w_971
以厘php框架 v10.0.5
<br/></br>
[下载地址](https://www.uuid2.com/971.html "下载地址")
<br/></br>
<h3>源码简介：</h3>
<p>以厘php框架是一个支持阿里云(函数计算)，腾讯(函数计算)，swoole(webserver模式) 的云php框架，系统自带管理后台方便快速的进行开发。<p>
<p>前端以layui，jquery为基础，还包括了kindeditor 富文本编辑器、echarts 图表绘制!
原创前端快速表单函数，jsfrom 快速生成表单修改新增数据!
极简路由模式，根据url访问对应的类调用对应的函数!
每个功能以插件形式集成，使得每个插件都是相互独立，又能相互关联，强大又灵活!
特有的插件函数 Construct 没有找到的类函数，直接会调用这里，方便开发多功能系统!
特有的url只能以小写函数名访问，大写函数名只能通过内部调用!
总结：小巧，灵活，强大，方便，支持云的php框架。<p>
<p>系统注意：
需要伪静态支持，php 7+系列直接安装即可；
直接导入ELikj.sql
登陆账号：admin 登陆密码：qqqqaa<p>
<p>阿里云部署：
函数入口aliyun.handler
手工导入数据库 ELikj.sql<p>
<p>腾讯云部署：
执行方法 tencent.main_handler
手工导入数据库 ELikj.sql<p>
<p>swool部署：
shell 执行 php swoole.php<p>
<p>插件开发说明：
插件开发注意
插件所有公用功能建议写在插件类，方便其他插件调用！
插件存放目录/ELikj/Controller/插件名字小写.Class.php；
插件的扩展、后台渲染和数据处理，存放到/Tpl/插件目录/；
ELitpl函数，加载其他扩展；
插件的扩展中，调用自己的函数，使用 $THIS 调用来调用。<p>
<h3>截图：</h3>
<img src="https://www.uuid2.com/wp-content/uploads/img/202105/b0f30e4125.gif" alt="以厘php框架 v10.0.5">
