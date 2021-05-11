项目流程（新建项目）
    1.准备数据库表
    2.新建项目/clone项目
    3.配置git/svn
    4.修改web.xml文件版本
    5.pom文件

    6.创建service dao
    7.spring配置文件
    8.springmvc配置文件
    9.mybatis配置文件
    10.jdbc配置文件
    11.web.xml配置文件
    12.配置监听器 使spring容器在项目启动创建且只创建一次

    13.路径（请求相关）
       绝对路径  其中的  /项目名  会使用el表达式${pageContext.request.contextPath}代替
                       /资源路径是以webapp为起点
            欢迎页面 资源路径
            超链接   /项目名/资源路径
            表单提交 /项目名/资源路径
            web.xml配置servlet路径 /资源路径
            转发   /资源路径
            重定向 /项目名/资源路径
       相对路径
            项目中相对路径会使用base标签
             <base href="http://ip:端口号/项目名/">
             <base href="http://ip:端口号/项目名/">
             ${pageContext.request.scheme}:// ${pageContext.request.serverName}:
             ${pageContext.request.serverPort} ${pageContext.request.contextPath}/


    14.解决乱码
        服务器<---->浏览器<---->数据库
        三者之间交互设置字符编码集

    注意事项
        1.普通字符串与标识符相同时 注意是否有引号


    未练习
        1.注解的方式使用spring容器管理对象







