---
layout: archive
title: "Albums"
permalink: /gallery/
author_profile: true
---
<style>
  /* 1. 容器居中 */
  .button-center-container {
    text-align: center; /* 让内部的元素水平居中 */
    margin: 40px 0;     /* 增加上下留白，让页面更有呼吸感 */
    width: 100%;
    display: block;
  }

  /* 2. 镂空按钮样式 */
  .btn-outline {
    display: inline-block;
    padding: 12px 35px;        /* 增加左右长度 */
    margin: 10px;              /* 按钮之间的间距 */
    
    /* 背景与边框 */
    background-color: transparent !important; 
    border: 2px solid #003366 !important;    /* 深蓝色边框 */
    border-radius: 6px;       
    
    /* 字体设置 */
    color: #494e52 !important; /* 字体颜色 */
    font-size: 1.25em !important; /* 字体调大 3 个号 */
    font-weight: bold !important; 
    text-decoration: none !important;
    
    /* 对齐与平滑过渡 */
    text-align: center;
    line-height: 1.5;
    transition: all 0.3s ease;
    cursor: pointer;
  }

  /* 3. 悬停效果 */
  .btn-outline:hover {
    background-color: #f0f7ff !important; /* 悬停时淡淡的浅蓝底色 */
    border-color: #001a33 !important;     /* 边框颜色加深 */
    transform: translateY(-2px);         /* 轻微上浮 */
    text-decoration: none !important;
    color: #003366 !important;           /* 悬停时文字稍微变蓝，增加互动感 */
  }
</style>

<div class="button-center-container">
  <a href="{{ '/gallery/laboratory/' | relative_url }}" class="btn-outline">Research Events</a>
  <a href="{{ '/gallery/conference/' | relative_url }}" class="btn-outline">Group Photos</a>
  <a class="btn-outline">Others</a>
</div>


