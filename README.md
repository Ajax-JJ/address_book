# address_book
学子天地通讯录系统
后台：阿集，彪叔
前端：子亮，飞鸿，伟志
Django版本：1.8.2
Python版本2.7.6
数据库信息：
成员类member
管理员类manager
功能：
登陆功能login，只能在数据库的Manager增加管理员，登陆后的session还未写
增加成员信息功能addMsg
搜索功能在main中，get方法为普通显示，post方法为搜索
更改成员信息功能msgUpdate
删除成员信息deleteMsg，还未写，应该在数据库加一个deleted信息来判断是否删除，不直接删除数据库信息
生日提醒功能birthdayTip，还未写
生成excel表格，还未写
写给金隆的接口，还未写（具体讨论）
还有很多坑没填，数据库感觉要加一个deleted属性，照片暂时先不弄，管理员登录和普通人没登陆的权限判断要弄，更新功能那里，把数据渲染到select里面不会写，感觉自己在坑自己。彪叔赶快来救我
