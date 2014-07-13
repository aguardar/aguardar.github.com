---
date: 2014.7.13
layout: post
title: BeagleBone Black简介
categories: 硬件
tags:  硬件介绍
---
##BeagleBone Black简介

>BeagleBone Black是一个可以在十秒之内家在linux的DIY迷你主板其硬件配置包括1GHz ARM Cortex-A8 处理器，3D图形加速器，一副PRU 32位RISC CPU，2GB ROM，MicroSD卡槽和512MB RAM。同时，Beaglebone Black的接口也相当丰富，包括USB接口、以太网接口、Micro-HDMI接口和两个46针接口。默认的系统是Angstrom Linux

##BeagleBone Black使用方法
使用的方法总共有三种：
>* 串口通讯
>* USB模拟的网口通讯（默认地址192.168.7.2）
>* 接上hdmi鼠标键盘直接使用  


其中我比较喜欢的方式是USB模拟网口的通讯方式。直接SSH过去即可，默认登录用户名为root，无密码。如果不想使用SSH，那就直接在浏览器中输入192.168.7.2:3000 会出现cloud9的使用界面。如果你对node很熟悉，那么可以很方便的用javascript直接控制开发板开发各种好玩的东西了。如果想安装软件，那么先接上网线，然后使用opkg命令。例如：
> opkg update  
> opkg upgrade  
> opkg install   

官方网站会不定期升级系统，自己留意即可，至于如何更换操作系统，请直接参考官网，思路都大同小异，提取img文件，然后使用官网给的工具烧录到minisd卡中即可。

##BeagleBone编程
USB接上之后打开浏览器输入192.168.7.2然后回车，打开的网页中给出了javascript编程控制硬件各个接口的方式，线路连接也给了出来。教程很详细
