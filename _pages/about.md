---
permalink: /
title: "Vincent's Home"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I'm currently in my third year of graduate studies in Software Engineering at China University of Mining and Technology, supervised by Liu Bing. I did my undergraduate studies at Hohai University (Nanjing) in the School of Computer and Information.

---
Recent trends
---
> 
> 2026-2-26 One paper is accepted by TOSEM!
>
> 2026-1-12 One paper is accepted by TCSVT!
>
> 2025-6-29 One paper is accepted by TOMM!
>
> 2021-5-21 One paper is accepted by TNNLS!
> 

---
Selected Papers
---

<!-- 论文列表样式 -->
<style>
/* 论文列表容器：控制整体宽度、间距 */
.papers-list {
  max-width: 950px;
  margin: 2rem auto;
  display: flex;
  flex-direction: column;
  gap: 1.5rem; /* 论文条目之间的间距 */
}

/* 单条论文条目：左图右文核心布局 */
.paper-item {
  display: flex;
  align-items: center;
  gap: 2rem; /* 图和文字的间距 */
  padding: 1rem 1.5rem;
  background: #f8f9fa;
  border-radius: 8px;
  box-shadow: 0 1px 4px rgba(0,0,0,0.08);
  flex-wrap: wrap; /* 移动端自动换行 */
}

/* 左侧缩略图列：固定宽度，不拉伸 */
.paper-thumbnail {
  flex: 0 0 180px; /* 缩略图宽度，可调整 */
  min-width: 150px; /* 移动端最小宽度 */
  height: 160px; /* 缩略图高度，统一尺寸 */
}

.paper-thumbnail img {
  width: 100%;
  height: 100%;
  object-fit: cover; /* 保持图片比例，裁剪多余部分 */
  border-radius: 6px;
  border: 1px solid #eee;
}

/* 右侧论文信息列：占满剩余宽度 */
.paper-info {
  flex: 1;
  min-width: 280px; /* 移动端最小宽度 */
}

/* 论文信息文字样式 */
.paper-title {
  font-size: 1.15rem;
  font-weight: 600;
  color: #2c3e50;
  margin: 0 0 0.6rem 0;
}

.paper-meta {
  color: #555;
  line-height: 1.7;
  font-size: 0.95rem;
  margin: 0.4rem 0;
}

.paper-meta strong {
  color: #2c3e50;
}
</style>

<!-- 论文列表容器 -->
<div class="papers-list">
  <!-- 论文1条目 -->
  <div class="paper-item">
    <!-- 左侧缩略图 -->
    <div class="paper-thumbnail">
      <img src="/images/papers/framework.png" alt="论文1缩略图">
    </div>
    <!-- 右侧信息 -->
    <div class="paper-info">
      <h4 class="paper-title">Evolving Trends in Cleanliness of Open Source Projects</h4>
      <p class="paper-meta">作者：Dapeng Yan, <strong>Wenjie Yang,</strong> et al.</p>
      <p class="paper-meta"><strong>发表期刊/会议：ACM TOSEM</strong>（CCF A类）</p>
    </div>
  </div>

  <!-- 论文2条目（复制即可新增） -->
  <div class="paper-item">
    <div class="paper-thumbnail">
      <img src="/images/papers/fig3.png" alt="论文2缩略图">
    </div>
    <div class="paper-info">
      <h4 class="paper-title">Retrieval-augmented Pseudo-image Guided Alignment and Text Domain-aware Memory Recall for Continual Zero-shot Captioning</h4>
      <p class="paper-meta">作者：Bing Liu; <strong>Wenjie Yang</strong>, et al.</p>
      <p class="paper-meta"><strong>发表期刊/会议：IEEE TCSVT</strong>（CCF B类）</p>
    </div>
  </div>

  <!-- 新增论文：直接复制上面的paper-item模块，替换内容即可 -->
  <div class="paper-item">
    <div class="paper-thumbnail">
      <img src="/images/papers/framework_p.png" alt="论文3缩略图">
    </div>
    <div class="paper-info">
      <h4 class="paper-title">Syntactic-Conditional Diffusion Networks for Controllable Image Captioning</h4>
      <p class="paper-meta">作者：Bing Liu; <strong>Wenjie Yang,</strong> et al.</p>
      <p class="paper-meta"><strong>发表期刊/会议：ACM TOMM</strong>（CCF B类）</p>
    </div>
  </div>
  <!-- 新增论文：直接复制上面的paper-item模块，替换内容即可 -->
  <div class="paper-item">
    <div class="paper-thumbnail">
      <img src="/images/papers/cnn.png" alt="论文3缩略图">
    </div>
    <div class="paper-info">
      <h4 class="paper-title">A Survey of Convolutional Neural Networks:
Analysis, Applications, and Prospects</h4>
      <p class="paper-meta">作者：Zewen Li , Fan Liu, <strong>Wenjie Yang,</strong> et al. </p>
      <p class="paper-meta"><strong>发表期刊/会议：IEEE TNNLS</strong>（CCF B类）</p>
    </div>
  </div>
</div>