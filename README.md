Flask_ihome

#### 介绍
有家租客项目是大学的自己写的第一个项目

#### 软件架构
软件架构说明


#### 安装教程

数据库迁移命令：1.进入到项目文件夹下和manage.py同级
              2.执行命令Python manage.py db init   生成一个迁移仓库migirations
              3.执行命令Python manage.py db migrate -m init_tables  生成迁移文件
              4.执行命令Python manage.py db upgrade 执行迁移文件
执行迁移脚本的是manage.py文件，所以在manage.py文件中导入模型类文件，才能执行生成迁移文件的命令
#### 使用说明

1.  xxxx
2.  xxxx
3.  xxxx

#### 参与贡献

1.  Fork 本仓库
2.  新建 Feat_xxx 分支
3.  提交代码
4.  新建 Pull Request
