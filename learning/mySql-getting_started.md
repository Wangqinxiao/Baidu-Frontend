＊适用于macbook
＊因为比较懒，所以尽量简单
＊如有不懂之处请联系QQ／微信1347580417 ；微博：超级无敌王勤晓

1. 访问www.mysql.com

2. Downloads，底部Community Edition(GPL)，进入下载dmg（会让登录，直接选择最下面的跳过的登录，直接下载）；

3. 正常安装即可；(安装过程中，会弹出一个对话框，记住里面的初始密码)

4. 系统偏好设置，mysql，启动server

5. 终端：
PATH="$PATH":/usr/local/mysql/bin

6. mysql -u root -p     （root用户登录，输入刚才记住的初始密码）

7. ALTER USER 'root'@'localhost' IDENTIFIED BY 'Qq123456';   （修改root用户的初始密码）

8. SELECT VERSION(), CURRENT_DATE;    （测试是否成功）

＊ 进一步尝试可以访问官方文档里的快速入门部分，很好的教程https://dev.mysql.com/doc/refman/5.7/en/tutorial.html
HAVE FUN！
