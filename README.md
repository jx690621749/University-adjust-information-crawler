# University-adjust-information-crawler
## 1. 项目介绍：
　　本项目为简单的网络定向爬虫，系本人在考研调剂期间为了方便查询各个大学研究生招生信息变化而编写（目前仅爬取了西电和哈工程的信息），可爬取指定大学研究生招生信息网最新的五条公告并以网页链接的形式展现在网页上，可实现网页跳转。
## 2. 技术路线：
　　基于flask框架，后端使用Python编写（requests库用来爬取html页面内容；beautifulsoup库用来对爬取内容进行处理，处理结果显示到前端html页面上）<br>
　　项目运行于阿里云服务器，使用Nginx+uWSGI部署web服务器，实现了简单的并发访问和负载均衡。感兴趣的同学可以点击链接[研究生调剂信息更新查询](http://39.106.197.151:5000)，页面很简陋，没有编写css样式。（网页现已失效）
## 3. 主要代码：
　　后端代码在helloworld.py中，前端代码在/templates下。
　　uwsgiconfig.ini是uWSGI配置文件。
