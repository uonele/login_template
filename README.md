# 用Django、xadmin和mysql写的一个基本模板

功能如下

- 用户注册（使用邮箱验证）
- 用户登录
- 用户登出
- 用户修改头像
- 用户修改密码
- 用户填写个人信息
- 用户修改个人信息


运行之前  makemigrations + migrate，生成数据库表

用命令行输入"python manage.py createsuperuser"，来创建一个超级用户，用于登录后台xamin
