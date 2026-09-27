---
layout: post
title: "Bugku MISC ：闪的好快 Writeup"
date: 2026-09-27 20:27:00 
categories: [CTF, Writeup]
tags: [MISC, Bugku, GIF分帧]
---

## 前言

在 CTF（Capture The Flag）中，完成了一道 Bugku 平台上的 MISC 题——**“闪的好快”**。这道题关键在逐帧拆分GIF图片。

## 1. 题目信息

*   **题目名称**：闪的好快
*   **题目分类**：MISC
*   **题目提示**：key格式：SYC{}

## 2. 解题过程

打开.gif文件，发现是一个不断闪烁的二维码，利用在线GIF拆分工具，得到18张不同的二维码，依次扫码并拼接信息得到flag

### 2.1 初步分析
下载下来的是一个.gif文件,发现是一个不断闪烁的二维码,推测要进行逐帧拆解

### 2.3 拆解（关键）
*   使用在线GIF拆分工具打开.gif文件
*   得到18张不同的二维码，依次扫码并拼接信息得到flag
### 2.4 提取数据
将flag上传，完成题目

## 3. 答案

Flag: flag{F1aSh_so_f4sT}
