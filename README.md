#MOOC_test


## 一、实验说明


### 1. 环境
 
windows
pycharm Professional Edition
mysql for window
navicat for window
virtualenvwrapper-win

### 2. 环境介绍

本实验环境采windows环境

### 3. 环境使用

* 先安装 pycharm Professional Edition

* 安装 mysql ：username-xkn password-admin

* 安装navicat

* 使用CMD安装虚拟环境：

    1. Ubuntu系统
    `
    pip install virtualenvwrapper
    `

    2. windows 系统
    `
    pip install virtualenvwrapper-win
    `

* 创建虚拟环境,并自动进入

    `
    mkvirtualenv testvir2
    `

* 其他操作

    ```
    #退出虚拟环境
    deactivate
    
    #查看虚拟环境
    workon
    
    #进入**虚拟环境
    workon testvir2
    ```

* 安装Django1.9.8

    `
    pip install django==1.9.8
    `


### 4. mysql 新建数据库

* 字符集：`utf8 -- UTF-8 Unicode`

* 排序规则： `utf8_general_ci`



### 5. 使用pycharm

新建项目，选用django模板，选用虚拟环境

* 创建APP: Tools——>Run manage.py Task
 `startapp message`
 
 * 新建 static 【存放js,cs,jpeg静态文件】
 
 * 新建 log 【存放日志文件】
  
 * 新建 media 【存放上传文件】
 
 * 新建 apps 【存放所有app】 _将apps Mark为source root 作为可导入的包_
 
    再到setting 配置路径：`????`
 
   