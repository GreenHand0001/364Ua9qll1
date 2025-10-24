## 前言

高校毕业与学位资格审核系统是一款基于Java技术，采用Spring Boot框架开发，前端技术包括JS、Vue和CSS3，数据库使用MySQL 5.7/8.0，适用于高校学生毕业与学位资格审核的信息管理系统。本系统旨在为高校提供一个高效、便捷、准确的毕业与学位资格审核平台，通过互联网技术实现学生信息的录入、审核、统计等功能，简化工作流程，提高工作效率。

## 内容介绍

高校毕业与学位资格审核系统主要包括学生信息管理、毕业审核管理、学位资格审核管理、数据统计与报表等功能模块。学生信息管理模块用于录入、修改和查询学生基本信息，毕业审核管理模块对学生提交的毕业申请进行审核，学位资格审核管理模块负责学位申请的审核，数据统计与报表模块可以生成各种统计报表，如录取率、各省份录取人数等。系统采用B/S架构，用户可通过浏览器访问系统，实现远程操作和管理。

## 技术介绍

语言：Java  
使用框架：Spring Boot  
前端技术：JS、Vue、CSS3  
开发工具：IDEA/Eclipse  
数据库：MySQL 5.7/8.0  
数据库管理工具：phpstudy/Navicat  
JDK版本：jdk1.8  
Maven: apache-maven 3.8.1-bin  
前端环境：Node.js 12/14/16

## 核心代码

```java
@RestController
@RequestMapping("/api/graduation")
public class GraduationController {

    @Autowired
    private GraduationService graduationService;

    @PostMapping("/apply")
    public Response applyForGraduation(@RequestBody GraduationApply apply) {
        return graduationService.applyForGraduation(apply);
    }

    @GetMapping("/review")
    public Response reviewGraduation(@RequestParam("studentId") Long studentId) {
        return graduationService.reviewGraduation(studentId);
    }

    @PostMapping("/result")
    public Response setGraduationResult(@RequestBody GraduationResult result) {
        return graduationService.setGraduationResult(result);
    }

}
```

## 免费源码获取

```
5000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)

# 项目截图

![封面图片](https://img11.360buyimg.com/ddimg/jfs/t1/309421/33/26526/87904/689e0c32Fac375704/4c3e247df0f93cf4.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/291265/26/25833/21488/689e0c10Fc5e170a8/8818b7d5c07eb951.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/324262/8/4659/23313/689e0c10F6e1cb220/fe18f0cec0c2940e.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/309748/29/26126/21799/689e0c11Faa7c2772/1572d0b81069e15d.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/307960/13/26324/22280/689e0c11Fd0f43528/a0f4626d4faa17d7.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/316769/8/24727/18979/689e0c12F67d01609/ee1746829603decf.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/286148/4/22133/21003/689e0c12Fe06a3ecb/89ae576fc8b8b6ea.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/288036/7/25052/21417/689e0c12Fe1cc15b6/52c5347c97323ac5.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/308318/28/26456/18513/689e0c13F42e83bea/e7d7d72df346be36.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/317152/27/24987/18933/689e0c14Fc15b957c/74a9d25a14499786.jpg)


## 万字文档
![文档介绍](https://img14.360buyimg.com/ddimg/jfs/t1/338393/1/3576/156947/68b1ad0cF74dc525c/ff9cd6c574295685.jpg)
