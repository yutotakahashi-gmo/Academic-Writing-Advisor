# Academic Writing Advisor

英検1級・アカデミックライティング向けの語彙トレーナー (単一HTMLファイル)。

## 機能

- **5モード**: フラッシュカード / 4択クイズ (パラフレ / 基本語) / タイピング / 一覧 / 📝 英検1級
- **5フィルター**: モード × ソース × トピック × 品詞 × レベル
- **1,500+語彙**:
  - パラフレ 74カテゴリ (動詞・名詞・形容詞・副詞)
  - 英検1級 過去問 508語 (2023-3 ～ 2025-2)
  - トピック別 964語 (27分野)
- **キーボード操作**: A/B/C/D, 1-4, →/Enter, ←, 0, R, M
- **進捗保存**: localStorage に自動保存

## デプロイ

GitHub Pages で公開する場合:

1. `vocab_quiz.html` を `index.html` にリネーム
2. このリポジトリの全ファイルをルートに配置
3. Settings → Pages → Source を `main` ブランチに設定
4. `https://<user>.github.io/<repo>/` でアクセス可能

## ファイル構成

```
.
├── index.html              # メインアプリ (HTML/CSS/JS全部入り)
├── favicon.ico             # 旧式ブラウザ用
├── favicon.svg             # モダンブラウザ用ベクター
├── favicon-16x16.png       # 標準小
├── favicon-32x32.png       # 標準
├── favicon-48x48.png       # ICO 内包
├── apple-touch-icon.png    # iOS/macOS Safari (180x180)
├── safari-pinned-tab.svg   # macOS Safari ピン留めタブ
├── icon-192.png            # PWA / Androidホーム画面
├── icon-512.png            # PWA高解像度
└── site.webmanifest        # PWAマニフェスト
```

## ローカル実行

`index.html` をブラウザで直接開くだけ。サーバー不要。

## ライセンス

私的学習用途。
