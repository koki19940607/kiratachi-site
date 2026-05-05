# キラキラ橘商店街 モック

スマホで見られる簡易Webモックです。GitHub Pages でそのまま公開しやすいように、最小構成にしています。

## ファイル構成

- `index.html` : モック本体
- `shops.json` : 店舗データの正本（サイトが直接読む）
- `shops.md` : 店舗一覧メモ・調査メモ
- `OPERATIONS.md` : 今後の更新手順・運用メモ
- `koutei1.md` : 工程1確定版
- `koutei2.md` : 工程2たたき台

## 公開方法（GitHub Pages想定）

1. GitHub にこの `kiratachi/` ディレクトリ内容を置く
2. リポジトリの Settings → Pages を開く
3. Branch を `main` / Folder を `/root` に設定
4. 数分待つと公開URLが発行される

## 備考

- 現在の `index.html` はモック版です
- 一部の店舗情報は `調査中` を含みます
- 営業中判定は `shops.json` の営業時間・定休日をもとに行います
- 今後の更新は `shops.json` を起点にする運用を推奨します
- 本番公開前に営業時間・定休日・掲載許可の確認が必要です
