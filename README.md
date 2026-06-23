# ChineseStyleHomestayManagementSystem
中式民宿管理系统  民宿管理系统 

所有源码均本人开发，项目是前后端分离的，所有的项目都具备了完整的业务逻辑，不仅仅局限于基础的增删改查（CRUD）操作，系统亮点众多。

本文注重于计算机毕业设计选题指导，列出题目均有源码， 大家可以去【公众号】(毕业终点站)获取或者加我【qq】(2112698948)提意见(别忘记Star哟)。备注：git

声明：仅用于学习使用，请勿用于任何商业行为！

1.系统非商用，非开源，非无偿。

2.由本人开发，如需源码，请联系以下方式，qq:2112698948。

3.项目有很多，并未全部上传，如果未找到想要的，可直接咨询。

<font style="color:rgb(17, 124, 238);">🎈</font><font style="color:rgb(17, 124, 238);">系统亮点：AI问答、协同过滤算法、Echarts图形化分析；</font>

# <font style="color:rgb(72, 179, 120);">一.系统开发工具与环境搭建</font>
## <font style="color:rgb(38, 38, 38);">1.系统设计开发工具</font>
<font style="color:rgb(38, 38, 38);">  
</font><font style="color:rgb(38, 38, 38);">后端使用Java编程语言的Spring boot框架</font><font style="color:rgb(38, 38, 38);">  
</font><font style="color:rgb(38, 38, 38);">项目架构：B/S架构</font><font style="color:rgb(38, 38, 38);">  
</font><font style="color:rgb(38, 38, 38);">运行环境：win10/win11、jdk17</font>

<font style="color:rgb(38, 38, 38);"></font>



<font style="color:rgb(72, 179, 120);">前端：</font><font style="color:rgb(38, 38, 38);">  
</font><font style="color:rgb(38, 38, 38);">技术：框架Vue3 ；UI库：Element-Plus；   
</font><font style="color:rgb(38, 38, 38);">开发工具：Visual Studio Code；</font>

---

<font style="color:rgb(38, 38, 38);">  
</font><font style="color:rgb(72, 179, 120);">后端:</font><font style="color:rgb(38, 38, 38);">  
</font><font style="color:rgb(38, 38, 38);">技术：Java语言、mybatis-plus、Spring boot框架；   
</font><font style="color:rgb(38, 38, 38);">开发工具：IDEA 2025版本；</font>

---

<font style="color:rgb(38, 38, 38);">  
</font><font style="color:rgb(72, 179, 120);">数据库：</font><font style="color:rgb(38, 38, 38);">  
</font><font style="color:rgb(38, 38, 38);">数据库：mysql5.7/8.0 </font><font style="color:rgb(38, 38, 38);">  
</font><font style="color:rgb(38, 38, 38);">数据库工具：Navicat12版本；</font>

---

# <font style="color:rgb(72, 179, 120);">二.系统实现（部分截图）</font>
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1782188576045-ccc599b5-057c-4949-8c8c-23907387a1ad.png)

## 2.1 用户
### 2.1.1 首页
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/jpeg/45326128/1782188579457-230580a2-95b3-4d59-80e5-143ee3c33f71.jpeg)

### 2.1.2 民宿详情
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/jpeg/45326128/1782188582719-b2b22d51-519e-4209-80f4-731d3b81dbb1.jpeg)

### 2.1.3 立即预订
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1782188587873-ff79b34c-31d1-412c-9bf4-7d64f5e02d77.png)

### 2.1.4 我的订单
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1782188590604-10f450cb-482e-487e-8667-4ffc1871e8a3.png)

### 2.1.5 民宿列表
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1782188593755-a9ac9762-7990-442c-a4f7-83c17329f8e5.png)

### 2.1.6 智能搜索
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/jpeg/45326128/1782188603300-3e7c02db-8b17-4e5f-994c-c645f98eb928.jpeg)

### 2.1.7 我的收藏
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1782188607826-296f2f5c-b244-4875-8fc5-6167cb678f44.png)

### 2.1.8 平台公告
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1782188610011-f1661744-8c34-496c-a5fe-f89dacb1f45f.png)

### 2.1.9 意见反馈
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1782188612805-9342d96e-7081-4fa4-8f4f-28cee65c794a.png)

### 2.1.10 个人中心
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1782188615425-8a59946d-9b63-48ab-a350-bed299a22e98.png)

## 2.2 民宿房东
### 2.2.1 控制台
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1782188618128-1493f31b-c74f-488b-a3b5-28f88aee1701.png)

### 2.2.2 民宿信息
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1782188620755-5b25d6ae-2a2c-44fa-9308-c609754265e0.png)

### 2.2.3 房源信息
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1782188623043-44675a78-da2d-4466-9855-247f4a1a5811.png)

### 2.2.4 房态设置
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1782188625520-856d272e-f5fd-4451-b41e-22f08c46822a.png)

### 2.2.5 预定订单
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1782188628295-994627d2-0259-4a38-9dc1-9e70f2521770.png)

### 2.2.6 退订订单
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1782188631752-20e906a9-5ed6-41fa-a22a-6abd7ece5d03.png)

### 2.2.7 评价管理
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1782188634324-49edf70f-92b8-4ef4-bb8b-ef5100752dce.png)

### 2.2.8 经营统计
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1782188637159-2a14dff3-a496-4abb-8786-2b8934f33c8e.png)

### 2.2.9 客户消息
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1782188639540-a8e7ca71-b568-411b-991a-4f6a4d28d1da.png)

## 2.3 管理员
### 2.3.1 账号管理
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1782188643731-4538990e-bd11-4ba9-8480-7fad8eb21a55.png)

### 2.3.2 房源分类
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1782188646639-74a26bd8-c550-47ac-ba76-7534ea62ff68.png)

### 2.3.3 轮播图管理
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1782188649229-3507718f-775a-4521-81f4-f98e1e4ea42f.png)

### 2.3.4 公告管理
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1782188652222-c62f3f97-edfe-4385-a913-6f82d41e8bf3.png)

### 2.3.5 房东管理
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1782188654926-1f12809d-3ea4-47e4-a235-e7e3e8efcd8e.png)

### 2.3.6 投诉处理
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1782188657543-3e2446cb-79cb-4e6c-bfa6-59ae479a5576.png)

### 2.3.7 意见反馈
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1782188660387-c4314734-8a81-4b55-aa85-6e2bd88ed176.png)

### 2.3.8 统计与结算
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1782188663157-600af51b-4f9e-4717-a854-c6bcb0bd672f.png)

# <font style="color:rgb(72, 179, 120);">三.系统代码结构截图</font>
## <font style="color:rgb(38, 38, 38);">3.1 前端</font>
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1782188666533-372c304a-4713-4f7d-8391-b2e613d5086e.png)

## 3.2 后端
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1782191519537-b7d59a1d-a34e-4102-9f82-fc0322ba6692.png)

## 3.3 数据库
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1782191522089-bf714559-b78b-48cf-bc8d-3ab2b3fc61b8.png)

# <font style="color:rgb(72, 179, 120);">四.</font><font style="color:rgb(26, 173, 25);">源码获取</font>
<font style="color:rgb(0, 0, 0);">1.原创系统非商用，非开源，非无偿。</font>

<font style="color:rgb(0, 0, 0);">2.项目有很多，并未全部上传，如果未找到想要的，可直接咨询。</font>

