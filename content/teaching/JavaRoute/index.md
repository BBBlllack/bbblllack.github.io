---
title: Java后端开发学习资料
summary: "我自己是主要从事java开发工作, 开发过数个应用系统, 整理了一份资料, 供学弟学妹使用"
date: 2024-06-01
type: docs
math: true
tags:
  - Java
  
---

>本文档适用于大一大二想从事java开发的同学使用

### JavaSE基础
[JavaSE基础 - 视频](https://www.bilibili.com/video/BV1Cv411372m/?spm_id_from=333.337.search-card.all.click&vd_source=974a0f9e05eeec234ded4107f30a1a94)  
如果时间比较紧张的话可以大概看到面向对象之后去看javaweb，如果web中用到了一些se基础例如文件流的知识可以回头来看。

### JavaWeb基础1
[JavaWeb基础1 - 视频](https://www.bilibili.com/video/BV1Qf4y1T7Hx/?spm_id_from=333.337.search-card.all.click)  
这个视频讲了数据库的基础和javaweb的初步知识和原理，以及java程序员必须掌握的前端知识。要全部看完并且理解。

### JavaWeb基础2
[JavaWeb基础2 - 视频](https://www.bilibili.com/video/BV1qv4y1o79t/?spm_id_from=333.337.search-card.all.click&vd_source=974a0f9e05eeec234ded4107f30a1a94)  
这个课程和javaweb基础1互为补充，这个课程是比较老的一些课程，但是讲的比1深，透彻，并且还介绍了一些linux的相关知识，如果看完javaweb基础1直接跳过这个也没问题，如果想多学一些可以补充着看。

### JavaWeb基础3
[JavaWeb基础3 - 视频](https://www.bilibili.com/video/BV1m84y1w7Tb/?spm_id_from=333.337.search-card.all.click)  
这个课程是黑马最新的javaweb课程，但是不推荐看，这个课程直接使用了开发框架，会导致web开发变得很简单，因为这个课程学完之后可能不太清楚web的一些原理，除了问题可能也不会自己排查，仅仅停留在会用的阶段。

### 开发框架1
[开发框架1 - 视频](https://www.bilibili.com/video/BV1Fi4y1S7ix/?spm_id_from=333.337.search-card.all.click&vd_source=974a0f9e05eeec234ded4107f30a1a94)  
可以看完javaweb基础1之后直接看这个框架1，在做web开发时，会有一些常见的配置项目，和一些依赖比较繁琐，学完框架之后，我们会将更多的精力放在业务逻辑上，简化配置，这里的框架是spring + springmvc + mybatis，spring简化了java开发， springmvc简化了javaweb开发，mybatis简化了数据库中jdbc的操作。最后稍微介绍了一下springboot。要看完，最好理解。

### 开发框架2
[开发框架2 - 视频](https://www.bilibili.com/video/BV15b4y1a7yG/?spm_id_from=333.337.search-card.all.click)  
这个开发框架就讲了springboot和他的一些组件，springboot进一步简化了ssm的开发，使得web开发更为简洁方便。同时在此，会学习到一些springboot的其他组件，开发中很常用，例如缓存springcache。因为东西太多，大概之后有这个就行，用到了可以现查api。

### 使用框架开发项目
[使用框架开发项目 - 视频](https://www.bilibili.com/video/BV13a411q753/?spm_id_from=333.337.search-card.all.click)  
这个使用了springboot+vue+vantui开发的一个小型项目，可以巩固学习到的开发，并且此时就会开始学习项目在linux系统的部署。不用跟着作完，大概看看linux和git还有redis那几块就行。

### 微服务分布式
[微服务分布式 - 视频](https://www.bilibili.com/video/BV1kH4y1S7wz/?vd_source=974a0f9e05eeec234ded4107f30a1a94)  
单体项目不足以支撑高并发和高可用，所以需要考虑架构的问题，在此会学习分布式开发框架springcloud，和它的一些组件，此时算真正的会做项目了。

### 前端服务器nginx
[前端服务器nginx - 视频](https://www.bilibili.com/video/BV1ov41187bq/?spm_id_from=333.337.search-card.all.click)  
后端有服务器，前端也有服务器，一般开发中和前后端的服务器不会用一个，所以前端项目也要部署在服务器上，常用的就是nginx，nginx在实现分布式系统会起到一个很重要的作用，但是这个课很长，也不用看完，只要需要nginx的知识就可以来这里补，或者网上查询也行，因为如果学到了需要使用nginx的时候，此时也具备了看文档学习的能力。

### 基础前端知识html，css，js，vue，react，elementui
[基础前端知识 - 视频](https://www.bilibili.com/video/BV1Tt4y1772f/?spm_id_from=333.337.search-card.all.click)  
这个视频会讲一些前端的开发知识，后端程序员也要会一些前端，这里做了一个精简，不太够，哪不够现查就行。