
**郑重声明：项目经过本地测试，确保可以运行。由于精力有限，远程调试服务需要提前联系，50一次。项目仅供学习和毕业设计参考~**
![输入图片说明](qrcode_for_gh_1266b4b5294a_258.jpg) wx扫码发送“BS030”获取完整源码和示例

#### 1.项目介绍

技术栈+环境：SpringBoot + BootStrap + MySQL5.7 + Maven3 + jdk8 + idea2022 + navicat

系统角色：普通用户 + 管理员

系统介绍：普通用户（个人信息、新闻评论、动物信息查看、公益项目捐赠、登录注册等）、管理员（志愿者管理、评论管理、公益进度管理、公益项目管理等）

#### 2.系统部署

- 首先你要创建数据库，可以利用navicat将sql文件导入

- 使用idea将项目打开

##### 1.后端管理平台部署

- TheCharityAdmin模块

- 打开src/main/resources/application.yml，根据你本地数据库环境，修改 3-6行

- 打开src/main/java/com/wht/AdminApplication.java，点击运行

- http://localhost:8082/Admin/   账号/密码：admin01/123456

- 或者查看user表

##### 2.门户

- thecharityQT模块

-  打开src/main/resources/application.yml，根据你本地数据库环境，修改 3-6行

- 打开src/main/java/com/wht/TheCharityApplication.java 点击运行即可

- http://localhost:8081/TheCharity/  账号/密码：test/23456

- 或者查看user表
