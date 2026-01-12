---
layout: archive
title: "Albums"
permalink: /gallery/
author_profile: true
---
<style>
  /* 1. 容器设置：使用 Flex 布局实现自适应和居中 */
  .button-center-container {
    display: flex;
    flex-direction: row;      /* 横向排列 */
    flex-wrap: wrap;          /* 屏幕太窄时自动换行 */
    justify-content: center;  /* 水平居中 */
    align-items: center;      /* 垂直居中 */
    gap: 15px;                /* 按钮之间的间距，替代 margin */
    margin: 40px auto;        /* 上下留白，容器水平居中 */
    width: 100%;
    max-width: 900px;         /* 限制最大容器宽度 */
  }

  /* 2. 响应式镂空按钮样式 */
  .btn-outline {
    /* 核心修改：长度微调逻辑 */
    flex: 1 1 220px;          /* 基础宽度 220px，有空间时等分剩余空间，空间不足时缩小 */
    max-width: 280px;         /* 限制单个按钮最大长度，防止只有 1-2 个按钮时太长 */
    min-width: 180px;         /* 确保在小屏上也有一定宽度 */
    
    padding: 14px 0;          /* 既然宽度由 flex 控制，左右 padding 设为 0 */
    
    /* 背景与边框 */
    background-color: transparent !important; 
    border: 2px solid #003366 !important;    /* 深蓝色边框 */
    border-radius: 8px;       
    
    /* 字体设置 */
    color: #494e52 !important; 
    font-size: 1.2em !important; 
    font-weight: bold !important; 
    text-decoration: none !important;
    
    /* 文字居中 */
    text-align: center;
    line-height: 1.2;
    transition: all 0.3s ease;
    cursor: pointer;
  }

  /* 3. 悬停效果 */
  .btn-outline:hover {
    background-color: #f0f7ff !important; 
    border-color: #001a33 !important;     
    transform: translateY(-3px);         /* 悬停上浮感 */
    box-shadow: 0 4px 10px rgba(0,0,0,0.1); /* 增加投影增加浮空感 */
    text-decoration: none !important;
    color: #003366 !important;           
  }

  /* 4. 移动端微调：针对屏幕非常窄的情况（如手机竖屏） */
  @media (max-width: 480px) {
    .btn-outline {
      flex: 1 1 100%;        /* 在极窄屏幕下，每个按钮占满一行 */
      max-width: 100%;
      font-size: 1.1em !important;
    }
  }
</style>

<div class="button-center-container">
  <a href="{{ '/gallery/research_events/' | relative_url }}" class="btn-outline">Research Events</a>
  <a href="{{ '/gallery/group_photos/' | relative_url }}" class="btn-outline">Group Photos</a>
  <a class="btn-outline">Others</a>
</div>


