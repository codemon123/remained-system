﻿网页后台说明：

网页后台源代码存于“订餐后台”文件夹中，为搭载JAVA EE相关插件的Netbeans IDE 7.2下可直接打开的项目。

采用Apache tomcat 7.0.27.0 + Java server pages + mySQL架构开发。

页面及数据库编码utf-8, 服务器搭建成功后通过访问服务器地址及端口+/____manage/来访问网站登陆页面。详细路径可通过更改路径配置文档/web/META-INF/context.xml来改变。

/web：页面源文件目录
/src: 服务器后台JAVA源代码目录

/manageDB: 服务器端数据库create表单语句

/build: 项目可执行文件根目录，/build/web/DishImg 为管理员上传图片存储位置

/lib: 执行所需特殊库文件存储目录，包括Jzon相关库及上传图片所用commons fileupload相关库



手机客户端说明：
手机客户端的源代码存于压缩包的“BookFood”文件夹中，

/bin中为运行生成的二进制文件，其中BookFood.apk为android客户端的可执行安装文件；

/libs中为库文件；

/res中为资源文件，包括手机客户端的本地图片，UI布局文件，字符引用，颜色引用等；

/src中为源代码。





