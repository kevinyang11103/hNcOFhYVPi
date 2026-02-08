## 前言

在当今社会，随着经济的发展，家庭财务管理变得越来越重要。为了帮助用户更好地管理家庭收支，我们设计并实现了一款基于SSM框架的家庭记账本系统。本文将详细介绍家庭记账本的设计与实现过程，以及项目中使用到的相关技术。

## 内容介绍

家庭记账本是一款简单实用的财务管理系统，旨在帮助用户记录日常生活中的收入和支出。通过该系统，用户可以方便地查询自己的消费记录，对家庭财务状况进行实时监控。此外，系统还提供了图表展示功能，让用户能够更直观地了解自己的财务状况。

## 技术介绍

本项目采用以下技术栈：

- **语言：** Java
- **使用框架：** Spring、Spring MVC、MyBatis、微信小程序
- **前端技术：** JS、Vue、CSS3、Uniapp
- **开发工具：** IDEA/Eclipse、Uniapp
- **数据库：** MySQL 5.7/8.0
- **数据库管理工具：** phpstudy/Navicat
- **JDK版本：** jdk1.8
- **Maven：** apache-maven 3.8.1-bin
- **前端环境：** Node.Js 12\14\16

## 核心代码

以下为项目中的一部分核心代码，展示了如何实现记账本的添加功能：

```java
// 家庭记账本Controller层
@RestController
@RequestMapping("/familyAccount")
public class FamilyAccountController {

    @Autowired
    private FamilyAccountService familyAccountService;

    // 添加记账本
    @PostMapping("/add")
    public ResponseEntity<String> addFamilyAccount(@RequestBody FamilyAccount familyAccount) {
        boolean result = familyAccountService.addFamilyAccount(familyAccount);
        if (result) {
            return new ResponseEntity<>("添加成功", HttpStatus.OK);
        } else {
            return new ResponseEntity<>("添加失败", HttpStatus.INTERNAL_SERVER_ERROR);
        }
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

## 项目截图
![封面图片](https://img11.360buyimg.com/ddimg/jfs/t1/349892/2/2824/157154/68c4cddfFf86fd0f2/640d8ff960bd43ba.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/331724/11/12647/16768/68c4cdb6F1f8d8d12/1608ddee523adc6e.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/329153/1/12653/14239/68c4cdb7Fdc762dfe/4215d22c0c432566.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/346124/35/2740/110359/68c4cdb7F16b8a8e5/27cf20eeabcbe050.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/324837/35/19260/22194/68c4cdb7F75cbd404/5133266474b94ae2.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/349266/20/2805/16812/68c4cdb7F90a678cd/0e7d31199a96a0e6.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/330690/9/12754/16979/68c4cdb7F1ccf2a88/683243cdeb68f02c.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/339613/22/10202/26203/68c4cdb7F9bf136a2/79e883f8472f5b17.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/332817/23/12697/21390/68c4cdb8F1f5aed2d/134abf7ecc25e1b3.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/323402/39/19766/39138/68c4cdb8Fa8ca976d/9cd738c0dc0cb091.jpg)


## 万字文档
![文档介绍](https://img14.360buyimg.com/ddimg/jfs/t1/338393/1/3576/156947/68b1ad0cF74dc525c/ff9cd6c574295685.jpg)
