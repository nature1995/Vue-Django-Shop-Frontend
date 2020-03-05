# Vue-Django-Shop-Frontend（生鲜超市前端代码）

[![python3](https://img.shields.io/badge/python-3-blue.svg)](https://www.python.org/downloads/)
[![django3.0.0](https://img.shields.io/badge/django-3.0.0-brightgreen.svg)](https://www.djangoproject.com/)

-------------------------------------------------------------------

#### 前端：
- Vue 

#### 后端：
- Python 3.6, 3.7 and 3.8
- Django 1.11, 2.1, 2.2 and 3.0
- Django Rest Framework 3.9, 3.10 and 3.11

#### 提升与改进
1. 使用最新的django-rest-framework-simplejwt代替django-rest-framework-jwt，由于原作者已不再维护该项目。
2. 加入腾讯云短信发送相关代码
3. 配合django-rest-framework-simplejwt修复第三方登录时，用户前端显示bug。
4. 修复alipay密钥存储格式导致的Incorrect padding问题
5. 修复热门搜索接口
6. 修复部分前端问题。

#### 项目资源
[Vue前端代码](https://github.com/nature1995/Vue-Django-Shop-Frontend)    
[Django后端代码](https://github.com/nature1995/Vue-Django-Shop-Website)

项目视频与原版文件: 链接:https://pan.baidu.com/s/1elQ0DJ-b0hB6W4ihJcK3mQ  密码:ndzt

#### Vue环境搭建
**国内:**
1. node.js
https://nodejs.org/

2. cnpm
```
npm install -g cnpm --registry=https://registry.npm.taobao.org
```

3. 安装依赖
```
cnpm install
```

4. 运行
```
cnpm run dev
```

**国外:**
1. node.js
https://nodejs.org/

2. 安装依赖
```
npm install
```

3. 运行
```
npm run dev
```

## 参考文档
Django3.0: https://docs.djangoproject.com/zh-hans/3.0/  
Django REST framework: https://www.django-rest-framework.org/     
DRF-extensions: http://chibisov.github.io/drf-extensions/docs/  
django-rest-framework-simplejwt: https://github.com/davesque/django-rest-framework-simplejwt    
django-social-auth: https://github.com/omab/django-social-auth  
xadmin: https://xadmin.readthedocs.io/en/docs-chinese/  
支付宝沙箱：https://openhome.alipay.com/platform/appDaily.htm  
腾讯云发送短信API: https://cloud.tencent.com/document/api/382/38778  
django-redis 中文文档: https://django-redis-chs.readthedocs.io/zh_CN/latest/#  
Python Social Auth: https://python-social-auth.readthedocs.io/en/latest/  
redis数据库安装参考: https://www.jianshu.com/p/035be70daf2d

