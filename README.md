# 美大就活ナビ

美大生のための就活情報まとめアプリ。200社の採用情報を業界別・人気スコア順で確認できる。

## GitHub Pagesでの公開手順

1. GitHubで新しいリポジトリを作成（名前例: `job-nav`）
2. このフォルダ内のファイルをすべてアップロード
3. リポジトリの「Settings」→「Pages」→「Branch: main」→「Save」
4. `https://ユーザー名.github.io/job-nav` でアクセス可能

## スマホへのインストール（PWA）

### iPhone/iPad
1. Safariでアプリを開く
2. 画面下の共有ボタン（□↑）をタップ
3. 「ホーム画面に追加」をタップ

### Android
1. Chromeでアプリを開く
2. アドレスバー右のメニュー（⋮）をタップ
3. 「ホーム画面に追加」をタップ

## ファイル構成

- `index.html` — メインアプリ
- `manifest.json` — PWA設定
- `sw.js` — オフライン対応
- `icon-192.svg` / `icon-512.svg` — アプリアイコン
