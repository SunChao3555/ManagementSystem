# Sunchao
# 大学课程教学过程管理系统

#### 项目介绍
系统主要功能包括， 院系管理员发布课程信息，教师选课，指定课程教材并编写教材大纲和学时数，然后根据教材编写每周教学内容；随后学生进行选课，其中学生选课是根据教师选课后的课程号进行选课，然后院系管理员进行排课，学生可进一步选择上课具体时间；教师发布作业并上传资源，学生提交作业后教师可在作业页面点击批改；另外，签到考勤，根据签到次数结合作业提交情况进行平时成绩统计；考试管理，教师上传试卷并经过院系三级审批通过后发布考试信息；成绩管理，根据平时成绩和考试成绩及其分别占比得到最终成绩，并在成绩单页面得到考试评价，即考试成绩综合情况。学生用户随后可查看成绩并和教师互动讨论。 

#### 软件架构
Python 版本：Python 3.0以上版本；
Django版本：Django2.0.2以上版本；
操作系统：Windows 10；
数据库：Mysql数据库；

#### 安装教程
连接Mysql数据库的配置信息Sun项目文件夹下Sun/settings.py文件内
  这里是主要部分代码配置：
   DATABASES = {
     'default': {
        'ENGINE': 'django.db.backends.mysql',
        'NAME':'test1',
        'USER':'root',
        'PASSWORD':'root',
        'HOST':'127.0.0.1',
        'PORT':'3306',
        'CHARSET':'utf-8'
      }
   }
  可参照上述作出修改。
另外，项目主要的配置修改基本是在settings.py文件中完成。
pycharm版本：pycharm2.7以上版本；
安装并配置好python环境后需要引入的依赖包在项文件夹Sun init/requirement.txt中；
数据库文件在项目文件夹Sun init/test1.sql文件内。

#### 使用说明
管理员登录
用户名：sunchao
密码：sunchaocc
若想要添加或修改用户信息可在管理员登陆系统后点击<用户信息>进行操作。
