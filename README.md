#DataBase Resuse Document
##1.使用准备
###1.1数据库
####      > 数据库：轻型数据库SQLite
####      > 安装地址：http://www.sqlite.org/download.html
####      > 安装方法：下载本机对应版本的压缩包，解压运行其中的sqlite3.exe

###1.2.Jar File：
#### > 从以下网址下载JAR包：<br>https://github.com/Wheellllll/Database/releases/download/V1.0/Datebase.jar

##2.DatabaseUtils内部接口
###2.1 内部方法
返回值 |方法
------ |-------
boolean|createAccount(String username, String password)
boolean|isValid(String username, String password)
boolean|isExist(String username)
###2.2方法细节
###### public static boolean **createAccount**(String username, String password)
      用以在数据库表application.db中创建该账号和密码<br>
      username-用户名<br>
      password-对应的密码<br>
###### public static boolean **isValid**(String username, String password)
      判断用户是否合法<br>
      username-获取的用户名<br>
      password-获取到的密码<br>

###### public static boolean **isExisted**(String username)
      判断用户是否存在<br>
      username-传入的用户名<br>
