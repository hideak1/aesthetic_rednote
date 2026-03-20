# 6.1 テック＆コーディング

## ビフォー＆アフター：テック投稿の違い

<div class="phone-compare">
<div class="phone-wrapper">
<div class="phone-label bad">&#10007; ありがちなテック投稿の失敗</div>
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
      <div style="font-size: 0.625rem; color: #333; margin-top: 0.5rem; font-weight: bold;">コード見てみて！！</div>
    </div>
  </div>
  <div class="post-meta">
    <div class="post-title">今日Pythonのコード書いた</div>
    <div class="post-author">
      <span class="author-avatar" style="background: #ccc;"></span>
      <span>newbie_dev</span>
      <span class="post-likes">&#9825; 5</span>
    </div>
  </div>
</div>
</div>
</div>
</div>

<div class="phone-wrapper">
<div class="phone-label good">&#10003; テック投稿もここまで映える</div>
<div class="phone-mockup" style="width: 220px;">
<div class="phone-status-bar"><span class="phone-notch"></span></div>
<div class="phone-screen">
<div class="xhs-post">
  <div class="post-image" style="background: linear-gradient(135deg, #0D1117, #161B22); display: flex; align-items: center; justify-content: center;">
    <div style="text-align: center; padding: 1.25rem;">
      <div style="font-size: 0.5rem; color: #58A6FF; font-family: monospace; letter-spacing: 0.05em; margin-bottom: 0.375rem;">OPEN SOURCE</div>
      <div style="font-size: 1.125rem; font-weight: 700; color: #F0F6FC; line-height: 1.3;">3日でAIツールを<br>作ってみた</div>
      <div style="width: 30px; height: 2px; background: #58A6FF; margin: 0.5rem auto;"></div>
      <div style="font-size: 0.5rem; color: #8B949E;">GitHub &#11088; 2.3k &middot; オープンソース</div>
      <div style="display: flex; gap: 0.25rem; justify-content: center; margin-top: 0.75rem;">
        <span style="background: #1F6FEB22; color: #58A6FF; font-size: 0.375rem; padding: 0.125rem 0.375rem; border-radius: 99px; border: 1px solid #1F6FEB44;">Python</span>
        <span style="background: #23883622; color: #3FB950; font-size: 0.375rem; padding: 0.125rem 0.375rem; border-radius: 99px; border: 1px solid #23883644;">Claude API</span>
      </div>
    </div>
  </div>
  <div class="post-meta">
    <div class="post-title">3日でAIツールを作った｜オープンソース ⭐2.3k</div>
    <div class="post-author">
      <span class="author-avatar" style="background: #58A6FF;"></span>
      <span>CodeAesthetics</span>
      <span class="post-likes">&#9825; 12.4k</span>
    </div>
  </div>
</div>
</div>
</div>
</div>
</div>

左は「開発者の自己満足」——白背景のスクリーンショットでデザインなし。フィードで誰もクリックしません。右はダーク背景＋太字タイトル＋テックタグで、**非エンジニアにもクールに見える**仕上がりです。

---

## フィードでのテック投稿の見え方

<div class="phone-mockup" style="width: 320px; margin: 2rem auto;">
<div class="phone-status-bar"><span class="phone-notch"></span></div>
<div class="phone-screen">
<div class="xhs-feed">
  <div class="feed-card">
    <div class="feed-image" style="background: linear-gradient(135deg, #0D1117, #1A1F2B);">
      <div style="text-align: center; padding: 0.5rem;">
        <div style="font-size: 0.5rem; color: #58A6FF; font-family: monospace;">$ vibe coding</div>
        <div style="font-size: 0.75rem; font-weight: 700; color: #F0F6FC; margin-top: 0.25rem;">プロンプト1つで<br>アプリを作る</div>
      </div>
    </div>
    <div class="feed-info">
      <div class="feed-title">Vibe Codingの実践</div>
      <div class="feed-author"><span class="feed-avatar" style="background: #58A6FF;"></span> DevProductivity</div>
    </div>
  </div>
  <div class="feed-card">
    <div class="feed-image" style="background: linear-gradient(135deg, #1a0533, #2D1B69);">
      <div style="text-align: center; padding: 0.5rem;">
        <div style="font-size: 0.5rem; color: #BD93F9;">&#9889; SIDE PROJECT</div>
        <div style="font-size: 0.75rem; font-weight: 700; color: #F8F8F2; margin-top: 0.25rem;">個人OSSで<br>月$700稼ぐ</div>
      </div>
    </div>
    <div class="feed-info">
      <div class="feed-title">個人開発のマネタイズ</div>
      <div class="feed-author"><span class="feed-avatar" style="background: #BD93F9;"></span> indie hacker</div>
    </div>
  </div>
  <div class="feed-card">
    <div class="feed-image" style="background: linear-gradient(135deg, #002B36, #073642);">
      <div style="text-align: center; padding: 0.5rem;">
        <div style="font-size: 0.375rem; color: #859900; font-family: monospace;">claude_agent_sdk</div>
        <div style="font-size: 0.75rem; font-weight: 700; color: #FDF6E3; margin-top: 0.25rem;">AIエージェント<br>フレームワーク<br>5つ比較</div>
      </div>
    </div>
    <div class="feed-info">
      <div class="feed-title">AIエージェント選定ガイド</div>
      <div class="feed-author"><span class="feed-avatar" style="background: #859900;"></span> AI Engineer</div>
    </div>
  </div>
  <div class="feed-card">
    <div class="feed-image" style="background: linear-gradient(135deg, #1E1E1E, #2D2D2D);">
      <div style="text-align: center; padding: 0.5rem;">
        <div style="font-size: 0.375rem; color: #569CD6; font-family: monospace;">VS Code</div>
        <div style="font-size: 0.75rem; font-weight: 700; color: #D4D4D4; margin-top: 0.25rem;">VS Code<br>必須拡張機能<br>10選</div>
      </div>
    </div>
    <div class="feed-info">
      <div class="feed-title">生産性を2倍にする拡張機能</div>
      <div class="feed-author"><span class="feed-avatar" style="background: #569CD6;"></span> ToolNerd</div>
    </div>
  </div>
</div>
</div>
</div>

4つのテック投稿スタイル：Vibe Coding、個人開発のマネタイズ、AIツール比較、開発者向け生産性ツール。共通点は1つ：**ダーク背景＋太字タイトル＋ミニマルレイアウト**。

---

## カバースタイル

コアの公式：ダーク背景＋明るい大きなタイトル＋テックタグ（言語/フレームワーク）。生のコードスクリーンショットをカバーにするのはNG——カバーにはプロセスではなく**成果物**を載せましょう。

---

## 配色

3つのクラシックなテックパレット——1つ選んで統一しましょう：

### GitHub Dark

<div class="color-palette">
  <div class="color-swatch">
    <span class="swatch-block" style="--swatch-color: #0D1117;"></span>
    <span class="swatch-label">Background #0D1117</span>
  </div>
  <div class="color-swatch">
    <span class="swatch-block" style="--swatch-color: #58A6FF;"></span>
    <span class="swatch-label">Accent #58A6FF</span>
  </div>
  <div class="color-swatch">
    <span class="swatch-block" style="--swatch-color: #F0F6FC;"></span>
    <span class="swatch-label">Text #F0F6FC</span>
  </div>
</div>

最も安全な選択で、オープンソースプロジェクトやGitHub関連コンテンツにぴったりです。ブルーのアクセントは自然と「プロフェッショナル＋信頼感」を伝えます。

### Dracula

<div class="color-palette">
  <div class="color-swatch">
    <span class="swatch-block" style="--swatch-color: #282A36;"></span>
    <span class="swatch-label">Background #282A36</span>
  </div>
  <div class="color-swatch">
    <span class="swatch-block" style="--swatch-color: #BD93F9;"></span>
    <span class="swatch-label">Accent #BD93F9</span>
  </div>
  <div class="color-swatch">
    <span class="swatch-block" style="--swatch-color: #F8F8F2;"></span>
    <span class="swatch-label">Text #F8F8F2</span>
  </div>
</div>

パープルはよりクリエイティブでパーソナルな印象。個人開発者、サイドプロジェクト、クリエイティブな開発コンテンツに最適です。

### Solarized

<div class="color-palette">
  <div class="color-swatch">
    <span class="swatch-block" style="--swatch-color: #002B36;"></span>
    <span class="swatch-label">Background #002B36</span>
  </div>
  <div class="color-swatch">
    <span class="swatch-block" style="--swatch-color: #859900;"></span>
    <span class="swatch-label">Accent #859900</span>
  </div>
  <div class="color-swatch">
    <span class="swatch-block" style="--swatch-color: #FDF6E3;"></span>
    <span class="swatch-label">Text #FDF6E3</span>
  </div>
</div>

グリーンのトーンはより「ギーク」な雰囲気。低レイヤーの技術、フレームワーク比較、ハードコアなチュートリアルに最適です。

---

## タイトルの公式

バズるテック系タイトルは常にプロセスではなく**成果**を強調します：

- 「XでYを作ってみた」 — *Claude APIで自動レポートツールを作ってみた*
- 「X日でYを開発」 — *3日でAIツールを作った、オープンソース化*
- 「このXがヤバすぎる」 — *このOSSツールがヤバすぎる*
- 「X vs Y、どっちがいい？」 — *React vs Vue、2025年はどっちを選ぶ？*

---

## 投稿構成

テック投稿のゴールデン構成——各セクションは短く：

1. **なぜ作ったか** — ストーリーを語る。ペインポイントを1〜2文で
2. **成果物を見せる** — スクリーンショット/GIF/動画、ここが最も重要
3. **技術スタック** — 使ったものを簡潔にリスト、チュートリアルではなく
4. **リンク** — GitHubのURL、ライブデモ

!!! tip "ポイント"
    小紅書はStack Overflowではありません。ユーザーはクールなものを発見しに来ているのであって、プログラミングを学びに来ているのではありません。**技術に詳しくない人にも理解でき、かっこいいと思ってもらうこと**が、テック投稿をバズらせる鍵です。
