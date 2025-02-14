## 项目简介

本项目是一个基于知识图谱的旅游推荐系统，旨在整合旅游相关数据，并利用知识图谱技术来提供个性化、智能化的旅游推荐服务。系统结合了爬虫技术、图数据库（Neo4j）以及自然语言处理技术，为用户打造一个全方位的旅游服务平台。

## 主要功能

- 数据爬取与初始化：利用爬虫技术从携程等旅游网站爬取景点数据，并存入本地文件。
- 用户登录注册：提供标准的用户登录注册功能，确保用户信息的安全性与准确性。
- 日本景点列表展示：用户登录后，可在首页查看景点列表，包括景点图片、开园时间等信息。
- 景点详情查看：用户可以点击某个景点，查看其详细信息，如景点介绍、位置、开放时间等。
- 景点评分与评论：用户可以在景点详情页对景点进行打分和评论，为其他用户提供参考。
- 推荐功能：系统会根据用户的评分历史和偏好，利用Neo4j图数据库进行协同过滤推荐，展示相似的旅游景点。
- 美食与购物推荐：在景点详情页，系统会推荐附近的美食和购物场所，为用户提供更全面的旅游体验。
- 知识图谱可视化：利用echarts等技术，展示旅游相关的知识图谱，帮助用户更直观地了解旅游景点的关联信息。


## 技术架构

- **后端框架:** Django框架
- **图数据库:** Neo4j
- **爬虫技术:** [待补充具体技术信息]
- **自然语言处理:** jieba分词
- **前端技术:** HTML5、CSS3、JavaScript、echarts

## 使用说明

1. 登录系统并登录账号。
2. 在首页可以查看日本景点列表和详细信息。
3. 可以对景点进行评分和评论。
4. 系统会根据用户的评分和偏好提供推荐。

## 联系方式

微信号：zt745324325