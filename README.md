
**郑重声明：项目经过本地测试，确保可以运行。项目仅供学习和毕业设计参考~**

![输入图片说明](qrcode_for_gh_1266b4b5294a_258.jpg) 扫码→源码商城获取完整源码和示例

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
![1](https://github.com/user-attachments/assets/42cdebe1-b67b-4568-a659-412130aceb28)
![2](https://github.com/user-attachments/assets/3e20009b-89da-4d56-b71c-45ed133d22f7)
![3](https://github.com/user-attachments/assets/f882467b-431e-4e81-996d-55afd9396994)
![4](https://github.com/user-attachments/assets/af2a3d51-5520-4a89-86e5-65585a3c81bf)
![5](https://github.com/user-attachments/assets/5309725a-7e22-44c2-9e6d-71dc9697e3ea)
![6](https://github.com/user-attachments/assets/1357691d-9236-4040-a917-50f0efb921c3)
![7](https://github.com/user-attachments/assets/9c197249-fba8-47c6-95d9-334cdc10d86b)
![8](https://github.com/user-attachments/assets/71f3f5f9-f027-49d2-ab34-9cf5993b7a98)
![9](https://github.com/user-attachments/assets/364ee3c4-3a2d-4408-bd54-276137bea218)
