## 起源
起初是给**广西科技大学**易班发展中心的光棍节活动开发的一个网站，活动结束后发现效果还不错，同学们的响应很热烈，而且在广西内的高校内也是好评不断。

于是，我就把此网站开源了，希望能对同学们有帮助。

## 链接
https://pingxonline.com/app/saylove/

## 主要特性
- 发起表白
- 查看表白
- 搜索某人的表白
- 点赞
- 分享
- 评论
- 猜名字
- 性别区分
- 邮件通知被表白者

## 目的
脱单神器助你早日脱单。

## 快速使用
1. 导入该项目中的saylovewall.sql数据库文件。

2. 修改数据库链接配置:
      修改connect.php中的
      
  
<code>        
$host = '127.0.0.1'; // 数据库地址
	

$user = 'root';  // 数据库用户名字


$pass = '';   // 数据连接密码


$db_name = 'wishingwall'; // 链接的数据的名字


</code>
			
   
3. 邮件服务配置： email.php ,修改成QQ邮箱和独立密码。(需要QQ邮箱开启相关邮件服务和设置一个独立密码，使用独立密码进行登录)。此邮件服务效果并不乐观，因为QQ限制最大发邮件数量，短时间内大量邮件发送出去会被退回。建议使用第三方邮件平台，付费服务。



这个网站会有许许多多的BUG，欢迎大家一起来完善。

## 更新历史
2017-10-19

1.优化UI
2. 完善代码注释
## 支持
基于jQuery Mobile开发。

## 界面

![](https://pingxonline.com/wp-content/uploads/2017/08/1.png)

![](https://pingxonline.com/wp-content/uploads/2017/08/2.png)

![](https://pingxonline.com/wp-content/uploads/2017/08/3.png)
