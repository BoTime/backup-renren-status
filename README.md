# 用途:

备份人人网的状态（及评论）

p.s.: 不知道还有多少人还在用人人网，突然有一天翻了翻自己的人人，看了看状态还都是大学本科时的，就想着有空写个爬虫把自己的状态抓下来做个备份，万一哪天人人挂了，还能给自己的大学生活留个念想……

# 使用方法

运行环境：Python3，安装Requests库

在终端运行
```bash
python brs.py
```
按指示做即可，运行结果保存在当前目录下的 renren_status 文件中

如需获得他人状态，只需修改parse_html中请求的用户ID，在此之前仍需要用自己的账户登录，主要是为了获取Cookie，不带Cookie的请求会跳转到登录页面
