# 6.1 技术 & 编程

## 先看效果：技术帖的 Before vs After

<div class="phone-compare">
<div class="phone-wrapper">
<div class="phone-label bad">&#10007; 技术帖常见翻车</div>
<div class="phone-mockup" style="width: 220px;">
<div class="phone-status-bar"><span class="phone-notch"></span></div>
<div class="phone-screen">
<div class="xhs-post">
  <div class="post-image" style="background: #fff; display: flex; align-items: center; justify-content: center;">
    <div style="padding: 0.75rem; width: 100%;">
      <div style="font-size: 0.5rem; font-family: monospace; color: #333; background: #f5f5f5; padding: 0.5rem; border-radius: 4px; line-height: 1.4; overflow: hidden;">
        def hello():<br>
        &nbsp;&nbsp;print("hello")<br>
        &nbsp;&nbsp;return True<br>
        # TODO: fix this<br>
        import os, sys<br>
        x = 1 + 2
      </div>
      <div style="font-size: 0.625rem; color: #333; margin-top: 0.5rem; font-weight: bold;">看看我写的代码！！</div>
    </div>
  </div>
  <div class="post-meta">
    <div class="post-title">今天写了一段python代码</div>
    <div class="post-author">
      <span class="author-avatar" style="background: #ccc;"></span>
      <span>小红薯</span>
      <span class="post-likes">&#9825; 5</span>
    </div>
  </div>
</div>
</div>
</div>
</div>

<div class="phone-wrapper">
<div class="phone-label good">&#10003; 技术帖也能很好看</div>
<div class="phone-mockup" style="width: 220px;">
<div class="phone-status-bar"><span class="phone-notch"></span></div>
<div class="phone-screen">
<div class="xhs-post">
  <div class="post-image" style="background: linear-gradient(135deg, #0D1117, #161B22); display: flex; align-items: center; justify-content: center;">
    <div style="text-align: center; padding: 1.25rem;">
      <div style="font-size: 0.5rem; color: #58A6FF; font-family: monospace; letter-spacing: 0.05em; margin-bottom: 0.375rem;">OPEN SOURCE</div>
      <div style="font-size: 1.125rem; font-weight: 700; color: #F0F6FC; line-height: 1.3;">我用 3 天<br>做了一个<br>AI 工具</div>
      <div style="width: 30px; height: 2px; background: #58A6FF; margin: 0.5rem auto;"></div>
      <div style="font-size: 0.5rem; color: #8B949E;">GitHub &#11088; 2.3k &middot; 已开源</div>
      <div style="display: flex; gap: 0.25rem; justify-content: center; margin-top: 0.75rem;">
        <span style="background: #1F6FEB22; color: #58A6FF; font-size: 0.375rem; padding: 0.125rem 0.375rem; border-radius: 99px; border: 1px solid #1F6FEB44;">Python</span>
        <span style="background: #23883622; color: #3FB950; font-size: 0.375rem; padding: 0.125rem 0.375rem; border-radius: 99px; border: 1px solid #23883644;">Claude API</span>
      </div>
    </div>
  </div>
  <div class="post-meta">
    <div class="post-title">3天肝了一个AI工具｜已开源&#11088;2.3k</div>
    <div class="post-author">
      <span class="author-avatar" style="background: #58A6FF;"></span>
      <span>代码美学</span>
      <span class="post-likes">&#9825; 12.4k</span>
    </div>
  </div>
</div>
</div>
</div>
</div>
</div>

左边是"程序员自嗨型"——白底截图 + 无排版，在信息流里完全不会有人点。右边用暗色背景 + 大标题 + 技术标签，**让非技术用户也觉得酷**。

---

## 技术帖在信息流里长什么样

<div class="phone-mockup" style="width: 320px; margin: 2rem auto;">
<div class="phone-status-bar"><span class="phone-notch"></span></div>
<div class="phone-screen">
<div class="xhs-feed">
  <div class="feed-card">
    <div class="feed-image" style="background: linear-gradient(135deg, #0D1117, #1A1F2B);">
      <div style="text-align: center; padding: 0.5rem;">
        <div style="font-size: 0.5rem; color: #58A6FF; font-family: monospace;">$ vibe coding</div>
        <div style="font-size: 0.75rem; font-weight: 700; color: #F0F6FC; margin-top: 0.25rem;">一句话写完<br>整个 App</div>
      </div>
    </div>
    <div class="feed-info">
      <div class="feed-title">Vibe Coding 实战</div>
      <div class="feed-author"><span class="feed-avatar" style="background: #58A6FF;"></span> 效率开发者</div>
    </div>
  </div>
  <div class="feed-card">
    <div class="feed-image" style="background: linear-gradient(135deg, #1a0533, #2D1B69);">
      <div style="text-align: center; padding: 0.5rem;">
        <div style="font-size: 0.5rem; color: #BD93F9;">&#9889; SIDE PROJECT</div>
        <div style="font-size: 0.75rem; font-weight: 700; color: #F8F8F2; margin-top: 0.25rem;">我的开源项目<br>月入 &#165;5000</div>
      </div>
    </div>
    <div class="feed-info">
      <div class="feed-title">独立开发变现之路</div>
      <div class="feed-author"><span class="feed-avatar" style="background: #BD93F9;"></span> indie hacker</div>
    </div>
  </div>
  <div class="feed-card">
    <div class="feed-image" style="background: linear-gradient(135deg, #002B36, #073642);">
      <div style="text-align: center; padding: 0.5rem;">
        <div style="font-size: 0.375rem; color: #859900; font-family: monospace;">claude_agent_sdk</div>
        <div style="font-size: 0.75rem; font-weight: 700; color: #FDF6E3; margin-top: 0.25rem;">5 个 AI Agent<br>框架对比</div>
      </div>
    </div>
    <div class="feed-info">
      <div class="feed-title">AI Agent 选型指南</div>
      <div class="feed-author"><span class="feed-avatar" style="background: #859900;"></span> AI 工程师</div>
    </div>
  </div>
  <div class="feed-card">
    <div class="feed-image" style="background: linear-gradient(135deg, #1E1E1E, #2D2D2D);">
      <div style="text-align: center; padding: 0.5rem;">
        <div style="font-size: 0.375rem; color: #569CD6; font-family: monospace;">VS Code</div>
        <div style="font-size: 0.75rem; font-weight: 700; color: #D4D4D4; margin-top: 0.25rem;">10 个必装<br>VS Code 插件</div>
      </div>
    </div>
    <div class="feed-info">
      <div class="feed-title">开发效率翻倍的插件</div>
      <div class="feed-author"><span class="feed-avatar" style="background: #569CD6;"></span> 工具控</div>
    </div>
  </div>
</div>
</div>
</div>

四种技术帖风格：Vibe Coding 实战、独立开发变现、AI 工具对比、开发效率工具。它们有一个共同点：**暗色背景 + 大字标题 + 极简排版**。

---

## 封面风格

核心公式：暗色背景 + 亮色大标题 + 技术标签（语言/框架）。不要截代码图当封面，把"结果"而不是"过程"放在封面上。

---

## 配色方案

三套经典技术配色，选一个坚持用就好：

### GitHub Dark

<div class="color-palette">
  <div class="color-swatch">
    <span class="swatch-block" style="--swatch-color: #0D1117;"></span>
    <span class="swatch-label">背景 #0D1117</span>
  </div>
  <div class="color-swatch">
    <span class="swatch-block" style="--swatch-color: #58A6FF;"></span>
    <span class="swatch-label">强调 #58A6FF</span>
  </div>
  <div class="color-swatch">
    <span class="swatch-block" style="--swatch-color: #F0F6FC;"></span>
    <span class="swatch-label">文字 #F0F6FC</span>
  </div>
</div>

最安全的选择，适合开源项目、GitHub 相关内容。蓝色强调色天然传递"专业+可信"。

### Dracula

<div class="color-palette">
  <div class="color-swatch">
    <span class="swatch-block" style="--swatch-color: #282A36;"></span>
    <span class="swatch-label">背景 #282A36</span>
  </div>
  <div class="color-swatch">
    <span class="swatch-block" style="--swatch-color: #BD93F9;"></span>
    <span class="swatch-label">强调 #BD93F9</span>
  </div>
  <div class="color-swatch">
    <span class="swatch-block" style="--swatch-color: #F8F8F2;"></span>
    <span class="swatch-label">文字 #F8F8F2</span>
  </div>
</div>

紫色系更有个性和创造力感，适合 indie hacker、side project、创意开发类内容。

### Solarized

<div class="color-palette">
  <div class="color-swatch">
    <span class="swatch-block" style="--swatch-color: #002B36;"></span>
    <span class="swatch-label">背景 #002B36</span>
  </div>
  <div class="color-swatch">
    <span class="swatch-block" style="--swatch-color: #859900;"></span>
    <span class="swatch-label">强调 #859900</span>
  </div>
  <div class="color-swatch">
    <span class="swatch-block" style="--swatch-color: #FDF6E3;"></span>
    <span class="swatch-label">文字 #FDF6E3</span>
  </div>
</div>

绿色调更"极客"，适合底层技术、框架对比、硬核教程。

---

## 标题公式

技术帖爆款标题都在讲**成果**而不是过程：

- "我用 X 做了 Y" — *我用 Claude API 做了一个自动写周报的工具*
- "X 天做了一个 Y" — *3天肝了一个AI工具，已开源*
- "这个 X 也太 Y 了" — *这个开源工具也太好用了吧*
- "X vs Y，选哪个？" — *React vs Vue，2025 年选哪个？*

---

## 正文结构

技术帖的正文黄金结构，每一段都要短：

1. **为什么做** — 讲故事，一两句话说清痛点
2. **成果展示** — 截图/GIF/视频，这是最重要的部分
3. **技术栈** — 简单列出用了什么，不要写教程
4. **链接** — GitHub 地址、在线 Demo

!!! tip "记住"
    小红书不是 CSDN。用户来这里是被"种草"的，不是来学编程的。**让非技术人也能看懂、觉得酷**，才是技术帖出圈的关键。
