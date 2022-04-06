# Javaweb-SMBMS

#### 介绍
基于JAVAWEB的超市订单管理系统SMBMS

一.功能分析

- 用户管理：数据库增删改查
- 订单管理：数据库增删改查
- 供应商管理：数据库增删改查

二.开发环境

    Windows 10，IntelliJ IDEA 2020.2，mysql5.5
	
三.项目结构设计

- java目录：java类文件，用于接受前端请求、后端逻辑控制等
- resources目录：database.properties数据库连接池信息
- pom.xml文件：基于maven管理的jar包

四.数据库smbms设计：
					
- 用户信息表smbms_user
- 供应商信息表smbms_provider
- 订单信息表smbms_bill
- 订货联系人地址表smbms_address
- 用户角色表smbms_role

五.项目讲解博客

https://blog.csdn.net/qq_39144436/article/details/123136150

六.其他项目仓库链接

1.基于微服务架构，包括网上预约挂号业务和肺癌风险评估业务，旨在缓解挂号难、看病难的就医难题。
https://github.com/CONTINUE12/PMP

2.基于Spring Boot、Mybatis、MySQL、Lombok、Web Bluetooth API、Thymeleaf、AdminLTE3、JqGrid 的RIREE交互系统 
https://github.com/CONTINUE12/RIREE

3.基于SpringBoot2.0+Mybatis的学生成绩管理系统 
https://github.com/CONTINUE12/SpringBoot_StudentManagerSystem

4.基于Spring+SpringMVC+Mybatis的图书管理系统 
https://github.com/CONTINUE12/SSM_LibrarySystem

5.基于AWT和Swing及MYSQL开发的学校教务系统 
https://github.com/CONTINUE12/JavaSE_School_Management_System
