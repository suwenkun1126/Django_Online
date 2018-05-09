# 1、创建项目

## (1)、建立Django工程

在虚拟环境下运行

```
pip install django #用于安装Django

pip install pymysql

django-admin start project Django_Online #用于创建Django项目文件
```

## (2)、修改settings.py文件

```
settings.py/

LANGUANGE_CODE = 'zh-hans'
TIME_ZONE = 'Asia/Shanghai'

import pymysql
pymysql.intall_as_MySQLdb()
DATABASES={
  'default':{
    'ENGINE':'django.db.backends.mysql',
    'NAME':'django_online',
    'USER':'root',
    'PASSWORD':'root',
    'HOST':'127.0.0.1',
    'PORT':''3306
  }
}

```
