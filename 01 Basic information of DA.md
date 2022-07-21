# Chapter1 Basic information of DA
## 数据分析3软件
SQL -- data extraction; Tableau/PowerBI -- data visualization; Python -- analysis and automation.

## 业务思路
### 1、取数需求  
### 2、异动归因  
报表中监测的指标发生异常，业务方会把这个问题报给数据分析组，需要数据分析师去排查原因；  
不同渠道对同一指标的数据不一致，也需要数据分析组排查原因；  
或者在用户的日常行为数据中发现异常数据，对可能存在的作弊用户进行封禁。   

https://github.com/zzx66699/Data-analytics-pre/blob/main/06%20异动归因.md
### 3、指标体系搭建  
一般搭建指标体系的核心思路是先选择北极星指标，将用户的生命周期路径与维度拆解结合起来，共同完成与业务紧密相连的指标体系搭建工作。  
指标体系是按照什么思路搭建的？  
### 4、埋点  
这个工作一般配合新的app版本上线、ab test实验进行的，主要目的是为了确保数据的准确性和数据的可利用性。  
一般数据分析师的主要工作内容是，根据需求的要求，结合埋点规范，确认action、page、dwell等关键字段的具体内容，将详细的日志文档字段整理好，提交给评审，然后由开发完成。  
### 5、ABtest  
一般是在工作中发现问题，分析问题，提出解决方案的过程中，对实际的解决措施的有效性提供检验，证明解决方案带来的实际收益并非偶然现象造成的。  
AB实验你们是如何做的？如何评估？  
### 6、报表  
一般做报表的目的有两种：一种是为了对指标体系进行监控；一种是对为了满足业务方日常常用取数的需求。  
一般是写SQL脚本，定期执行，将数据存入到本地mysql数据库，再通过可视化软件，进行报表的展示。  
日常监控异常维度是如何挖掘的？  

## 误差
### 幸存者误差
<img width="700" alt="image" src="https://user-images.githubusercontent.com/105503216/180243192-d6110514-e6d8-49ef-bb1f-f2b1d62769e5.png">

<img width="726" alt="image" src="https://user-images.githubusercontent.com/105503216/180241808-08686c29-fc41-458a-8ade-8def26090c34.png">   
重点：流失前行为识别、流失用户的事后调研  
<img width="713" alt="image" src="https://user-images.githubusercontent.com/105503216/180242675-f4f3ddc3-af4c-469e-a98c-9491d36d39db.png">  
重点：采用含有量级的衡量指标去评判

#### 如何避免
<img width="722" alt="image" src="https://user-images.githubusercontent.com/105503216/180243824-b4c3723c-122f-4e42-b37a-5a4093284416.png">





