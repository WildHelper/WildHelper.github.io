---
layout: default
permalink: /index.html
---

野生助手是学校教务小助手，支持查分、查课表、查考试、出分提醒。专供指定校在校生和已毕业校友使用。

本项目是在 [GNU Affero GPL v3.0](https://github.com/WildHelper/WildHelper.github.io/raw/master/LICENSE) 协议下开源的项目，任何人都可以在协议的约束下，自由的修改、重新分发本项目下的软件。若修改本程序并在网络上提供服务，必须使用相同协议公开修改后的完整源代码。

本项目希望提升学生在移动端的教务体验；但在适用法律允许的范围内，本项目不担保任何责任，使用者需自行承担全部风险，详情请参见 [GNU Affero GPL v3.0](https://github.com/WildHelper/WildHelper.github.io/raw/master/LICENSE)

<img src="https://user-images.githubusercontent.com/6601455/87389305-18a0fc00-c5d9-11ea-8329-028038f6668d.PNG" width="200" />
<img src="https://user-images.githubusercontent.com/6601455/87389413-48500400-c5d9-11ea-84f5-24d8fb8480af.PNG" width="200" />
<img src="https://user-images.githubusercontent.com/6601455/87389498-6c134a00-c5d9-11ea-88cc-5c378fe2b105.PNG" width="200" />
<img src="https://user-images.githubusercontent.com/6601455/87389508-6fa6d100-c5d9-11ea-9d65-1a8d2a772a64.PNG" width="200" />
<img src="https://user-images.githubusercontent.com/6601455/87389513-71709480-c5d9-11ea-8869-ec8adcb31124.PNG" width="200" />
<img src="https://user-images.githubusercontent.com/6601455/87389522-733a5800-c5d9-11ea-99a8-2681f5afa489.PNG" width="200" />
<img src="https://user-images.githubusercontent.com/6601455/87389527-76354880-c5d9-11ea-8f70-244c7809faf8.PNG" width="200" />
<img src="https://user-images.githubusercontent.com/6601455/87389532-77ff0c00-c5d9-11ea-96cf-df8c1cc257b0.PNG" width="200" />

## 现有项目

+ [WildHelper](https://github.com/WildHelper): GitHub 项目首页
  + [MiniProgram](https://github.com/WildHelper/MiniProgram): 小程序
  + [Server-PHP](https://github.com/WildHelper/Server-PHP): 后端 - PHP 版
  + [WildHelper.github.io](https://github.com/WildHelper/WildHelper.github.io): 官网

## 核心功能

+ **查分:** 自动计算各学期、辅修/双学位、第一学位的加权平均分、GPA、课程数、总学分、通过率等信息，自动处理重修、补考、不及格等特殊情况；分组展示成绩详情，可显示教师、课程种类、课程编号、课程学分，并支持排序和搜索；支持分数分享
+ **查课表:** 自动根据当前周数高亮显示课程；支持学期选择；支持课表分享
+ **查考试:** 在考试周会显示考试科目、考试时间、考试地点
+ **选课指导:** 通过大数据，显示每门课的平均分、平均绩点等基本信息；自动绘制课程分数分布直方图；支持按照课程种类等维度筛选，按成绩等指标排序，按课程名称等属性搜索
+ **分数推送:** 支持订阅后分数推送，出分后学生第一时间收到出分提醒

一些学校可能只开放部分功能

## 技术亮点

+ **前后端完全分离**，通用 RESTful API
+ 使用**原生**小程序开发，支持微信数据**预加载**、**周期性**更新
+ 与学校对接实现数据实时自动获取
+ 支持**校友认证**，100%保证用户真实，比学信网更简单易用
+ 用户直方图使用**Canvas2D**自动绘制
+ 灰度功能**开关**
+ 错误日志**自动上报**、微信群预警，方便紧急维护
+ 用户反馈按钮随时接入客服
+ 使用了**端到端加密**（AES-256-GCM），中间人（包括微信）不可拿到任何用户数据
+ 非选课周用户只能看到自己选择的课程
+ 服务器**永不存储用户密码**
+ **撤销授权机制**，用户可随时彻底删除所有数据
