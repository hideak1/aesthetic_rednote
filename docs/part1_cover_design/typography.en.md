# 1.2 Typography

Composition builds the skeleton; text gives your cover its voice. On Xiaohongshu, cover text is far from optional — more often than not, it's that one punchy line on the cover that earns the tap. But poorly handled typography can just as easily tank the overall feel. In this chapter, we'll walk through font selection, sizing, and text layout from the ground up.

<div class="phone-compare">
<div class="phone-wrapper">
<div class="phone-label bad">✗ Chaotic fonts</div>
<div class="phone-mockup" style="width: 220px;">
<div class="phone-status-bar"><span class="phone-notch"></span></div>
<div class="phone-screen">
<div class="xhs-post">
  <div class="post-image" style="background: #f0f0f0; display: flex; align-items: center; justify-content: center;">
    <div style="text-align: center; padding: 1rem;">
      <div style="font-size: 1.1rem; font-family: cursive; color: red; transform: rotate(-5deg);">Must-Have Items!!!</div>
      <div style="font-size: 0.5rem; font-family: serif; color: blue; margin-top: 0.5rem;">These things are really great</div>
      <div style="font-size: 0.75rem; font-family: monospace; color: green; margin-top: 0.25rem; text-decoration: underline;">Click for details★</div>
    </div>
  </div>
  <div class="post-meta">
    <div class="post-title">Must-have items look here!!</div>
    <div class="post-author">
      <span class="author-avatar" style="background: #ccc;"></span>
      <span>New User</span>
      <span class="post-likes">♡ 8</span>
    </div>
  </div>
</div>
</div>
</div>
</div>

<div class="phone-wrapper">
<div class="phone-label good">✓ Unified fonts with hierarchy</div>
<div class="phone-mockup" style="width: 220px;">
<div class="phone-status-bar"><span class="phone-notch"></span></div>
<div class="phone-screen">
<div class="xhs-post">
  <div class="post-image" style="background: linear-gradient(180deg, #FAF6F0, #F7E8C8); display: flex; align-items: center; justify-content: center;">
    <div style="text-align: center; padding: 1.5rem;">
      <div style="font-size: 1.25rem; font-weight: 700; color: #333; letter-spacing: -0.02em;">Monthly Favorites</div>
      <div style="font-size: 0.625rem; color: #888; margin-top: 0.5rem; letter-spacing: 0.1em;">REPURCHASED 3+ TIMES</div>
      <div style="width: 30px; height: 1px; background: #C8B49A; margin: 0.5rem auto;"></div>
      <div style="font-size: 0.5625rem; color: #999;">5 items I keep coming back to</div>
    </div>
  </div>
  <div class="post-meta">
    <div class="post-title">Monthly favorites | Repurchased 3+ times</div>
    <div class="post-author">
      <span class="author-avatar" style="background: #F7E8C8;"></span>
      <span>Life Aesthetics</span>
      <span class="post-likes">♡ 6.7k</span>
    </div>
  </div>
</div>
</div>
</div>
</div>
</div>

## Choosing Fonts

Fonts have personalities. Pick the right one and your cover's tone clicks into place; pick the wrong one and no amount of rearranging will fix it.

### Serif vs. Sans-Serif

| Type | Characteristics | Best for | Examples |
|------|----------------|----------|----------|
| Serif | Decorative strokes at the ends of letters; feels traditional, elegant | Cultural content, literary vibes, luxury branding | Times New Roman, Playfair Display, Source Han Serif |
| Sans-serif | Clean, simple strokes; feels modern, approachable | Everyday sharing, tutorials, product recommendations | Helvetica, Montserrat, Source Han Sans |

### Popular Chinese Fonts for Xiaohongshu

- **Source Han Sans (思源黑体)** — Free for commercial use, available in multiple weights, and works for nearly everything. When in doubt, go with this one.
- **Zcool Happy Font (站酷快乐体)** — Rounded and playful; great for food, pets, and lifestyle content.
- **FangZheng LanTing (方正兰亭)** — Sleek and premium; ideal for skincare, fashion, and home decor content.

!!! tip "Mind the licensing"
    Xiaohongshu posts are public, so font licensing matters. Source Han Sans and Source Han Serif are open-source (by Google and Adobe) and safe for commercial use. Zcool fonts are also free. Some FangZheng fonts require a license — always double-check before publishing.

### Pairing Chinese and English Fonts

When mixing Chinese and English text, keep the style families consistent — pair sans with sans, serif with serif. Reliable combos include:

- Source Han Sans + Montserrat
- PingFang + SF Pro
- Source Han Serif + Playfair Display (for an elegant feel)

<figure style="margin: 1.5rem 0; text-align: center;">
  <img src="https://images.unsplash.com/photo-1586075010923-2dd4570fb338?w=400&h=500&fit=crop" alt="Typography example" loading="lazy" style="border-radius: 8px; max-width: 300px; width: 100%;">
  <figcaption style="font-size: 0.75rem; color: var(--text-muted); margin-top: 0.5rem;">Clean typography — unified fonts, clear hierarchy</figcaption>
</figure>

## Size Hierarchy

A typical cover carries 2-3 layers of text. The sizes need to be different enough that the viewer instantly knows what to read first.

| Level | Purpose | Size guideline | Weight |
|-------|---------|---------------|--------|
| Headline | The core message — seen first | Roughly 1/5 to 1/4 of the image width | Bold / Heavy |
| Subheading | Supporting info, adds context | 50%-60% of the headline size | Regular / Medium |
| Details | Tags, dates, minor info | 30%-40% of the headline size | Light / Regular |

<div class="typo-demo">
  <div class="demo-title">5 Tips to Make Your Cover 10x Better</div>
  <div class="demo-subtitle">From composition to color — all in one guide</div>
  <div class="demo-body">Master these fundamentals and your posts will look instantly more polished...</div>
</div>

!!! tip "The 1.5x rule"
    Keep at least a **1.5x size ratio** between your headline and subheading. Anything less and they look like they're competing at the same level.

<div class="compare-box">
  <div class="compare-item bad">
    <span class="compare-label">✗ Avoid</span>
    <div style="font-family: Comic Sans MS, cursive; font-size: 1.2rem; color: red;">Three fonts on one cover!!!</div>
    <div style="font-size: 0.6rem; color: blue; font-family: serif;">And yet another for the subtitle</div>
  </div>
  <div class="compare-item good">
    <span class="compare-label">✓ Recommended</span>
    <div style="font-size: 1.2rem; font-weight: 700;">Clean, bold headline</div>
    <div style="font-size: 0.8rem; color: #888;">Subtitle in the same font family</div>
  </div>
</div>

!!! warning "Avoid size chaos"
    Some covers end up with four or five different text sizes scattered around with no clear logic. Rule of thumb: **three size levels max**. Less is more.

## Text Layout

With fonts and sizes locked in, the next question is *where* and *how* to place the text.

### Alignment

- **Center-aligned** — Suits symmetrical compositions, poster-style covers, and formal content
- **Left-aligned** — The most natural reading direction; works well when there's a lot of text
- **Right-aligned** — Can feel distinctive in small doses, but avoid it as your primary alignment

!!! info "The golden rule of alignment"
    Whatever alignment you choose, **stick with one per cover**. Mixing center and left alignment is one of the most common beginner mistakes — it makes the entire layout feel disjointed.

### Line Spacing and Letter Spacing

- **Line spacing** — Set it to 1.2-1.5x the font size. Too tight feels cramped; too loose feels disconnected.
- **Letter spacing** — Default spacing is usually fine for body text. For headlines, slightly increased letter spacing adds breathing room and a premium feel.

## Text and Image Relationship

Cover text isn't a sticker. It needs to live *with* the image, not just sit on top of it.

### Place Text in Natural Whitespace

The ideal approach: plan for text placement when you shoot or select your image. Sky, walls, tabletops — these natural blank areas are your text's best friends.

### Semi-Transparent Backdrops

If the image doesn't offer clean whitespace, add a semi-transparent overlay behind the text:

- **White overlay** — Fits light, fresh aesthetics
- **Black overlay** — Suits dark, moody, or premium-feeling covers
- **Tinted overlay** — Matches the image's dominant color for a cohesive look

!!! tip "Opacity sweet spot"
    Aim for 50%-70% opacity. Too transparent and the text is hard to read; too opaque and it hides the image behind it.

## Common Mistakes to Avoid

!!! warning "Steer clear of these"
    - **More than 2 fonts** — One Chinese + one English is your maximum. More than that reads as chaotic, not creative.
    - **Unclear size hierarchy** — When every line of text is roughly the same size, nothing stands out.
    - **Over-decoration** — Outlines, drop shadows, gradients, 3D effects… skip them. Clean text ages best.
    - **Text covering the subject** — Words plastered over a face or product defeat the purpose of the image.
    - **Too many text colors** — Stick to two colors at most, both in harmony with the overall palette.

## Takeaways

Great typography on a cover boils down to three ideas:

1. **Match the font to the mood** — let the typeface reinforce the content's personality
2. **Create clear hierarchy** — size and weight should leave no doubt about what to read first
3. **Exercise restraint** — fewer fonts, fewer colors, fewer effects, always

Next up, we'll cover information hierarchy and layout — connecting composition and typography into a complete cover design.
