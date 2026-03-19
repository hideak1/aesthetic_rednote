# 7.1 视频封面

## 先看效果：随机截帧 vs 设计封面

视频封面比图文封面更重要——因为视频在 feed 里默认显示封面缩略图。

<div class="phone-compare">
<div class="phone-wrapper">
<div class="phone-label bad">&#10007; 随机截帧当封面</div>
<div class="phone-mockup" style="width: 220px;">
<div class="phone-status-bar"><span class="phone-notch"></span></div>
<div class="phone-screen">
<div class="xhs-post">
  <div class="post-image" style="background: #8B7355; position: relative;">
    <div style="position: absolute; inset: 0; background: linear-gradient(45deg, #6B5B3E 30%, #9B8B6E 70%); opacity: 0.7;"></div>
    <div style="position: absolute; bottom: 35%; left: 20%; width: 50px; height: 35px; background: rgba(0,0,0,0.2); border-radius: 2px;"></div>
    <div style="position: absolute; top: 15%; right: 10%; width: 20px; height: 20px; background: rgba(255,255,255,0.15); border-radius: 50%;"></div>
    <div style="position: absolute; bottom: 8%; right: 8%; background: rgba(0,0,0,0.5); color: #fff; font-size: 0.375rem; padding: 0.1rem 0.25rem; border-radius: 2px;">01:23</div>
    <span class="label" style="color: #ccc;">模糊、看不出内容是什么</span>
  </div>
  <div class="post-meta">
    <div class="post-title">记录一下今天的日常</div>
    <div class="post-author">
      <span class="author-avatar" style="background: #ccc;"></span>
      <span>小红薯</span>
      <span class="post-likes">&#9825; 12</span>
    </div>
  </div>
</div>
</div>
</div>
</div>

<div class="phone-wrapper">
<div class="phone-label good">&#10003; 精心设计的视频封面</div>
<div class="phone-mockup" style="width: 220px;">
<div class="phone-status-bar"><span class="phone-notch"></span></div>
<div class="phone-screen">
<div class="xhs-post">
  <div class="post-image" style="background: linear-gradient(135deg, #0D1117, #1a1a2e); display: flex; align-items: center; justify-content: center; position: relative;">
    <div style="text-align: center; padding: 1rem;">
      <div style="font-size: 0.5rem; color: #58A6FF; letter-spacing: 0.1em; margin-bottom: 0.25rem;">VLOG</div>
      <div style="font-size: 1.125rem; font-weight: 700; color: #F0F6FC; line-height: 1.3;">程序员的<br>一天</div>
      <div style="width: 25px; height: 2px; background: #58A6FF; margin: 0.5rem auto;"></div>
      <div style="font-size: 0.4375rem; color: #8B949E;">coding · coffee · deploy</div>
    </div>
    <div style="position: absolute; bottom: 8%; right: 8%; background: rgba(0,0,0,0.6); color: #fff; font-size: 0.375rem; padding: 0.1rem 0.25rem; border-radius: 2px;">&#9654; 02:45</div>
  </div>
  <div class="post-meta">
    <div class="post-title">程序员的一天｜写代码·喝咖啡·上线</div>
    <div class="post-author">
      <span class="author-avatar" style="background: #58A6FF;"></span>
      <span>代码日记</span>
      <span class="post-likes">&#9825; 8.6k</span>
    </div>
  </div>
</div>
</div>
</div>
</div>
</div>

---

## 四种常见视频封面风格

<div class="phone-mockup" style="width: 320px; margin: 2rem auto;">
<div class="phone-status-bar"><span class="phone-notch"></span></div>
<div class="phone-screen">
<div class="xhs-feed">
  <div class="feed-card">
    <div class="feed-image" style="background: linear-gradient(180deg, #1a1a2e, #16213e); position: relative;">
      <div style="text-align: center; padding: 0.5rem;">
        <div style="font-size: 0.75rem; font-weight: 700; color: #fff;">独居女生<br>的周末</div>
        <div style="font-size: 0.375rem; color: #E8A0BF; margin-top: 0.25rem;">&#9729; a slow weekend</div>
      </div>
      <div style="position: absolute; bottom: 4%; right: 6%; background: rgba(0,0,0,0.5); color: #fff; font-size: 0.3125rem; padding: 0.0625rem 0.1875rem; border-radius: 2px;">&#9654; 3:21</div>
    </div>
    <div class="feed-info">
      <div class="feed-title">Vlog 风封面</div>
    </div>
  </div>
  <div class="feed-card">
    <div class="feed-image" style="background: #FCE4EC; position: relative;">
      <div style="text-align: center; padding: 0.5rem;">
        <div style="font-size: 1.25rem; font-weight: 800; color: #880E4F;">3步</div>
        <div style="font-size: 0.5rem; font-weight: 600; color: #AD1457; margin-top: 0.125rem;">学会调色</div>
      </div>
      <div style="position: absolute; bottom: 4%; right: 6%; background: rgba(0,0,0,0.5); color: #fff; font-size: 0.3125rem; padding: 0.0625rem 0.1875rem; border-radius: 2px;">&#9654; 1:45</div>
    </div>
    <div class="feed-info">
      <div class="feed-title">教程风封面</div>
    </div>
  </div>
  <div class="feed-card">
    <div class="feed-image" style="background: linear-gradient(90deg, #ddd 50%, #F8BBD0 50%); position: relative;">
      <div style="display: flex; height: 100%; align-items: center; justify-content: center;">
        <span style="font-size: 0.5rem; color: #999; padding-right: 0.25rem;">Before</span>
        <span style="font-size: 0.5rem; color: #880E4F; padding-left: 0.25rem; font-weight: 600;">After</span>
      </div>
      <div style="position: absolute; bottom: 4%; right: 6%; background: rgba(0,0,0,0.5); color: #fff; font-size: 0.3125rem; padding: 0.0625rem 0.1875rem; border-radius: 2px;">&#9654; 0:58</div>
    </div>
    <div class="feed-info">
      <div class="feed-title">变装/对比封面</div>
    </div>
  </div>
  <div class="feed-card">
    <div class="feed-image" style="background: linear-gradient(135deg, #FAF6F0, #F7E8C8); position: relative;">
      <div style="text-align: center; padding: 0.5rem;">
        <div style="width: 30px; height: 30px; background: #E8A0BF; border-radius: 50%; margin: 0 auto 0.25rem;"></div>
        <div style="font-size: 0.5rem; font-weight: 700; color: #333;">为什么你的<br>视频没人看？</div>
      </div>
      <div style="position: absolute; bottom: 4%; right: 6%; background: rgba(0,0,0,0.5); color: #fff; font-size: 0.3125rem; padding: 0.0625rem 0.1875rem; border-radius: 2px;">&#9654; 2:10</div>
    </div>
    <div class="feed-info">
      <div class="feed-title">口播风封面</div>
    </div>
  </div>
</div>
</div>
</div>

---

## 封面设计要点

- **视频封面 ≠ 随机截帧**，要单独设计
- **封面上加时间码标记**（让人知道是视频）
- **风格要和你的图文帖子统一**
