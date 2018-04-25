# Huawei LiteOS对接第三方云平台

本仓库将作为 **寻找IoT达人第一期——LiteOS对接云平台** 活动的代码及文档提交仓库。

本文作为参赛者作品提交guideline，请详细阅读，包含源码及手册模板下载地址、作品提交方式、以及作品评判规则等说明。

## 活动主题：Huawei LiteOS对接云平台

本次活动是 **寻找IoT达人** 系列活动的第一期，参赛达人需完成Huawei LiteOS与第三方云平台的对接，所使用开发板种类不限，并在规定时间内，将源码和文档上传至GitHub，审核通过即可获取精美礼品，最终将结合代码质量以及基于云平台开发的应用等方面进行综合评比，优胜者将有机会赢取大奖！

活动介绍请参考论坛帖：http://developer.huawei.com/ict/forum/thread-48733.html

## 提交作品说明

参赛者的作品提交须同时包含源码、手册、视频。其中源码和手册需上传至GitHub，对接云平台过程及应用演示的视频录制，需上传到社区，同时需要将作品使用的硬件（除F429主板外）寄回，以供技术人员验证，验证后会及时寄还。验证完成后，请先与活动工作人员取得联系，确定作品上传内容及需要寄回的硬件后，再寄出。

### 一. 源码提交

- 参赛者需将源码提交至活动对应的GitHub仓库，目录已按照云平台划分，请参赛者在所选云平台对应的目录下，创建自己的目录，并将自己的代码上传至对应目录下，GitHub仓库地址：https://github.com/LITEOS/LiteOS_Connect_to_3rd_Cloud  
  以OneNET为例，在 *liteos_to_onenet* 目录下创建自己的目录，命名格式为 “**liteos_onenet_作品名**”，然后将代码提交到该目录下。

- 请遵循Hawei LiteOS编码规范，具体可参考：https://github.com/xiaoyusu/LiteOS_Connect_to_3rd_Cloud/blob/master/Coding_Style.md

### 二. 手册上传

对接云平台的项目说明手册请按照模板填写，最终同代码一并提交到github对应目录下即可，模板获取链接：https://github.com/xiaoyusu/LiteOS_Connect_to_3rd_Cloud/blob/master/LiteOS_Connect_to_3rd_Cloud_Developer_Guide.md

### 三. 视频上传

参赛者需要录制编译、烧写、对接平台、数据上传及下发操作演示的流程视频，录制方法不限，需要体现主要操作步骤，清晰完整地介绍一整套流程，本地压缩后上传到LiteOS论坛，地址：
1. 在华为开发者论坛的Huawei LiteOS板块下，发布新帖
2. 帖子命名格式：【寻找IoT达人】LiteOS对接云平台作品展示，xxxxx作品名
   举例：【寻找IoT达人】LiteOS对接云平台作品展示，智能温湿度中控
3. 视频压缩后作为附件上传

### 四. 硬件寄回

参赛者需要将作品使用的硬件（除F429主板以外），寄回给主办方验证，验证后会及时寄还。请参赛者完成作品后，先与活动工作人员取得联系，确定作品上传内容及需要寄回的硬件后，再寄出到指定地址。


## 评分标准

对于参赛者提交的作品，主办方将从代码质量、对接工作量、应用场景、作品完整性等方面综合考量。
- **代码质量** ：占比30%，主要从代码本身的质量出发，考核是否遵循Huawei LiteOS编码规范，并从代码简洁性、逻辑性、算法复杂度等方面综合考量。
- **应用场景** ：占比30%，在完成云平台对接的基础上，考核参赛者开发应用的实用性、完成度、创新性、商业价值等方面。
- **对接工作量** ：占比20%，因为所选平台、对接方式、协议的不同，对接工作量可能有少量或是较大差异，所以该项也会作为重要参考，纳入考核维度之一。
- **作品完整性** ：占比20%，主要考核提交作品中是否包含了源码、手册、视频三部分内容，以及各项内容的完成度。  

完成LiteOS和云平台对接，并且提交的作品完整包含源码、手册、视频，都将获得主办方提供的开发板一套（F429），以及精美礼品一份（小天鹅音响或荣耀手环任选一件）；在完成对接基础上，还将基于上述四个维度，从中评选出优胜的一等奖1名（获赠Huawei nova手机一部），二等奖2名（分别获赠华为B3手环一个）。  

开发时间为20天，从接收到板子开始计时，需在规定时间内完成。
