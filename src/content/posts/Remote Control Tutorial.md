---
title: 远程控制 教程
published: 2025-11-23
tags:
  - 远程控制
  - Python
draft: false
image: https://ysy.spacjoy.top/bz/hp/bz_044.png
category: 教程
---
# 远程控制程序教程

*本次教程使用2.3.8版本，后续版本升级可能有所变动*

## 首先需要准备好以下材料

1. 巴法云账号
2. 米家APP
3. 小爱同学/小爱音箱
4. PC（Windows10 以上官方系统）
5. 良好的互联网连接
## 一、第一步安装Remote Control
1. 打开项目网址[Remote-Controls](https://github.com/SpacJoy/Remote-Controls)
   ![](../assets/images/项目发布页.png)
2. 选择带 Installer 的下载，如果打不开github可以试试[备用链接](https://ysy.spacjoy.top/file/Remote-Controls-Installer-2.3.8.exe)下载
   ![](../assets/images/下载项.png)
3. 打开/运行**安装包**
   ![](../assets/images/打开安装包.png)
4. 同意开源协议
   ![](../assets/images/同意开源协议.png)
5. 按需勾选可选项
   ![](../assets/images/可选项.png)
6. 确认可选项信息并**安装**
   ![](../assets/images/确认信息.png)
7. 勾选启动托盘并点击**完成**
   ![](../assets/images/安装完成.png)
## 二、配置Remote Control
1. 根据提示**打开Gui**
   
   ![](../assets/images/打开GUI.png)
1. 打开巴法云**控制台**
   ![](../assets/images/控制台.png)
2. 点击左上角小眼睛展开**密钥**
   ![](../assets/images/密钥.png)
3. 切换配置到 **MQTT**
   ![](../assets/images/切换MQTT.png)
4. 点击**添加设备**
   ![](../assets/images/添加设备.png)
5. 以内置主题**计算机**为例，选择**开关**类型
   ![](../assets/images/选择类型.png)
6. 点击即可**复制主题**，点击 **昵称** 修改备注（我的是*PC*）**后面要用**
   ![](../assets/images/复制主题.png)
7. 在**GUI**填写网站、端口、密钥
   ![](../assets/images/端口信息.png)
   ![](../assets/images/填写信息.png)
8. 点击**更多**可修改内置主题配置
   ![](../assets/images/点击更多.png)
9. 可修改 **计算机** 主题预设为 **锁定电脑** 
   ![](../assets/images/修改内置主题预设.png)
10. 点击**添加**可添加**自定义主题**
   ![](../assets/images/自定义主题.png)
11. 切换 **状态** 可控制开关 **主题** ，关闭预设可以**自定义** 
    ![](../assets/images/自定义主题控制.png)
12. 配置完后可**保存配置**文件
    ![](../assets/images/保存配置.png)
13. 右键托盘可 **重启主程序** 应用配置
    ![](../assets/images/重启主程序.png)
# 三、接入米家
1. 打开并登录**小米账号**
2. 右上角添加设备
   ![](../assets/images/米家添加设备.png)
3. 选择其他平台设备
   ![](../assets/images/其他平台.png)
4. 搜索巴法云并登录巴法云账号
   ![](../assets/images/链接巴法云.png)
# 四、接入小爱同学

**要先接入米家才能接入小爱同学哦！**

有两个方法接入小爱同学，首先是 **有 小爱音箱**、**无小爱同学APP**

## 第一种（有小爱音箱）
1. 添加**手动控制**
   ![](../assets/images/添加手动控制.png)
2. 输入**语音指令**
   ![](../assets/images/自定义的指令.png)
3. 选择**家具设备**
   ![](../assets/images/选择家具设备.png)
4. 选择**小爱音箱**
   ![](../assets/images/选择小爱音箱.png)
5. 选择**执行文本指令** 输入“关闭 **PC**（上文巴法云设置的昵称）”，勾选静默执行
   ![](../assets/images/输入指令.png)
6. 点击完成
   ![](../assets/images/点击完成.png)![](../assets/images/点击创建.png)
7. 唤醒小爱音箱说 “**锁定电脑**” 即可根据配置执行锁定电脑的操作了
## 第二种（无小爱音箱）
1. 唤醒小爱同学并进入**主界面**（APP打开即可）
   ![](../assets/images/进入小爱同学.png)
2. 点击右上角**更多**
   ![](../assets/images/小爱同学更多.png)
3. 找到**训练计划**
   ![](../assets/images/小爱同学训练计划.png)
4. 点击个人训练
   ![](../assets/images/小爱同学个人训练.png)
5. 点击右下角加号**添加**
   ![](../assets/images/小爱同学添加个人训练.png)
6. 点击添加说法设置**锁定电脑**
   ![](../assets/images/小爱同学添加说法.png)
7. 点击**添加操作**
   ![](../assets/images/小爱同学添加操作.png)
8. 选择**设备控制**
   ![](../assets/images/小爱同学选择设备控制.png)
9. 点击巴法云上对应的**昵称**
   ![](../assets/images/小爱同学巴法云昵称.png)
10. 选择对应的**选项**
    ![](../assets/images/小爱同学对应的选项.png)
11. 下方设置像我这样设置即可
    ![](../assets/images/小爱同学其他设置-1.png)
 12. 点击右上角**完成**
    ![](../assets/images/小爱同学右上角完成.png)
13. 唤醒小爱同学说 “**锁定电脑**” 即可根据配置执行锁定电脑的操作了
# 好了，至此教程结束！