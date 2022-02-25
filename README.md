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
