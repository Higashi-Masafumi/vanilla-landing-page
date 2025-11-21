# Receipt Share - Landing Page

<div align="center">
  <h3>割り勘をもっとスマートに。</h3>
  <p>レシートを撮るだけ。自動で読み取り、グループで共有、瞬時に割り勘。</p>
</div>

---

## 📖 概要

**Receipt Share (レシートシェア)** は、レシートの自動スキャン、OCR、グループ共有、割り勘計算を行うモバイルアプリケーションのランディングページです。

このランディングページは、アプリの価値提案を明確に伝え、ユーザーにダウンロードを促すことを目的としています。

### 🎯 ターゲットユーザー
- 一緒に旅行する友人
- 共同生活をするルームメイト
- 共同で家計を管理するカップル
- イベント主催者

---

## ✨ 主な機能

### アプリの機能
1. **高精度OCRスキャン** - 最新のAI技術でレシートを正確に読み取り
2. **リアルタイム共有** - グループメンバー全員がリアルタイムで確認可能
3. **自動割り勘計算** - 誰が誰にいくら払うべきか一瞬で算出

### ランディングページの特徴
- **モダンでクリーンなデザイン** - 白と青を基調とした洗練されたUI
- **リッチなアニメーション** - Three.jsを使用した没入感のある3D背景エフェクト
- **モバイルファースト** - レスポンシブデザインで全デバイスに対応
- **SEO最適化** - 適切なメタタグと構造化データ

---

## 🛠 技術スタック

### フロントエンド
- **HTML5** - セマンティックなマークアップ
- **CSS3** - カスタムプロパティとモダンなレイアウト（Flexbox/Grid）
- **Vanilla JavaScript** - フレームワークレスの軽量実装

### ライブラリ
- **Three.js** - 3D背景エフェクト（CDN経由）

### フォント
- **Inter** - 英数字用
- **Noto Sans JP** - 日本語用

---

## 📁 ディレクトリ構造

```
vanilla-landing-page/
├── assets/              # 画像・アイコンなどの静的アセット
│   ├── iPhone 16 Pro - 1.png
│   ├── iPhone 16 Pro - 2.png
│   ├── iPhone 16 Pro - 3.png
│   ├── iPhone 16 Pro - 4.png
│   ├── step-1.png
│   ├── step-2.png
│   ├── step-3.png
│   ├── avatar-1.png
│   └── avatar-2.png
├── css/
│   └── style.css        # メインスタイルシート
├── js/
│   ├── main.js          # メインJavaScript（モバイルメニューなど）
│   └── three-bg.js      # Three.js 3D背景エフェクト
├── PRD/                 # プロダクト要件定義
│   ├── abstract.md
│   └── pages/
│       └── index.md
├── docs/                # ドキュメント
└── index.html           # メインHTMLファイル
```

---

## 🚀 セットアップ

### 前提条件
- モダンなWebブラウザ（Chrome, Firefox, Safari, Edge）
- ローカル開発サーバー（オプション）

### インストール手順

1. **リポジトリのクローン**
   ```bash
   git clone https://github.com/Higashi-Masafumi/vanilla-landing-page.git
   cd vanilla-landing-page
   ```

2. **ローカルサーバーの起動**

   **オプション1: Python（Python 3がインストールされている場合）**
   ```bash
   python3 -m http.server 8000
   ```

   **オプション2: Node.js（npxが使える場合）**
   ```bash
   npx http-server -p 8000
   ```

   **オプション3: VS Code Live Server**
   - VS Codeの拡張機能「Live Server」をインストール
   - `index.html`を右クリックして「Open with Live Server」を選択

3. **ブラウザでアクセス**
   ```
   http://localhost:8000
   ```

---

## 🎨 デザインシステム

### カラーパレット
```css
--primary-color: #007AFF;      /* メインブルー */
--primary-dark: #0051D5;       /* ダークブルー */
--text-dark: #1d1d1f;          /* ダークテキスト */
--text-light: #86868b;         /* ライトテキスト */
--bg-light: #f5f5f7;           /* ライト背景 */
--white: #ffffff;              /* ホワイト */
```

### タイポグラフィ
- **見出し**: Inter / Noto Sans JP (700)
- **本文**: Inter / Noto Sans JP (400)
- **ボタン**: Inter / Noto Sans JP (600)

### ブレークポイント
- **モバイル**: 〜768px
- **タブレット**: 768px〜1024px
- **デスクトップ**: 1024px〜

---

## 📱 主要セクション

### 1. ヘッダー
- ロゴ
- ナビゲーションメニュー（機能、使い方、利用者の声）
- ダウンロードボタン
- モバイルメニュートグル

### 2. ヒーローセクション
- キャッチコピー
- アプリ説明
- App Storeダウンロードボタン
- iPhone 16 Proモックアップ
- Three.js 3D背景エフェクト

### 3. 問題提起・解決セクション
- ユーザーの課題を明確化
- ソリューションの提示

### 4. 機能セクション
- 高精度OCRスキャン
- リアルタイム共有
- 自動割り勘計算
- 各機能のビジュアル付き説明

### 5. 使い方セクション
- 3ステップの使い方ガイド
- イラスト付きステップカード

### 6. 利用者の声
- ユーザーレビュー
- アバター付きテスティモニアル

### 7. フッター
- リンク（プライバシーポリシー、利用規約、お問い合わせ）
- コピーライト

---

## 🔧 カスタマイズ

### 色の変更
`css/style.css`のCSS変数を編集：
```css
:root {
  --primary-color: #your-color;
  --primary-dark: #your-dark-color;
}
```

### コンテンツの変更
`index.html`の該当セクションを編集してください。

### 3D背景エフェクトの調整
`js/three-bg.js`でパーティクルの数、色、動きなどをカスタマイズできます。

---

## 🌐 デプロイ

### Netlify
1. Netlifyにログイン
2. 「New site from Git」を選択
3. リポジトリを接続
4. デプロイ設定:
   - **Build command**: （空欄）
   - **Publish directory**: `/`
5. 「Deploy site」をクリック

### Vercel
1. Vercelにログイン
2. 「New Project」を選択
3. リポジトリをインポート
4. 設定はデフォルトのまま「Deploy」をクリック

### GitHub Pages
1. リポジトリの Settings → Pages
2. Source: `main` ブランチ
3. Folder: `/ (root)`
4. 「Save」をクリック

---

## 📝 ライセンス

© 2024 Receipt Share. All rights reserved.

---

## 🤝 コントリビューション

プルリクエストを歓迎します！大きな変更の場合は、まずissueを開いて変更内容を議論してください。

---

## 📧 お問い合わせ

質問や提案がある場合は、[お問い合わせフォーム](#)からご連絡ください。

---

## 🎯 今後の予定

- [ ] ダークモード対応
- [ ] 多言語対応（英語版）
- [ ] アニメーションのパフォーマンス最適化
- [ ] Google Playストアリンクの追加
- [ ] FAQセクションの追加

---

<div align="center">
  Made with ❤️ for Receipt Share
</div>
