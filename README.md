# 将棋戦法ドリル（PWA）

## GitHub Pages で公開する
1. GitHub で新しいリポジトリを作る（例: `shogi-senpo`、Public）
2. このフォルダの中身（index.html / manifest.webmanifest / sw.js / icons/）をそのままアップロード
3. リポジトリの Settings → Pages → Branch を `main` / `/ (root)` にして Save
4. 1〜2分後に `https://<ユーザー名>.github.io/shogi-senpo/` で開ける

## iPhone のホーム画面に追加
Safari で上の URL を開く → 共有ボタン → 「ホーム画面に追加」

## 更新するとき
ファイルを差し替えたら `sw.js` の `VERSION` を `senpo-v2` のように上げると、古いキャッシュが確実に消える。
