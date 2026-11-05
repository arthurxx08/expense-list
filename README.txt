# 費用一覧アプリ

## ファイル
- index.html: アプリ本体
- manifest.webmanifest: ホーム画面追加用設定
- sw.js: オフライン表示用
- icon.svg: アプリアイコン

## 公開方法（GitHub Pagesの例）
1. GitHubにログインし、新しいPublicリポジトリを作成。
2. このZIPを展開し、4ファイルをリポジトリ直下にアップロード。
3. Settings → Pages → Deploy from a branch → `main` / `/(root)` を選択して保存。
4. 発行された `https://ユーザー名.github.io/リポジトリ名/` をiPhoneのSafariで開く。
5. Safariの共有ボタン →「ホーム画面に追加」。

## 注意
- データはIndexedDBに保存され、サーバーには送信されません。
- SafariのWebサイトデータ削除、端末故障、アプリ関連データの消失に備え、設定画面からJSONバックアップを定期的に保存してください。
- CSVはUTF-8 BOM付きで、1行につき1件です。
- バックアップ復元は現在のデータを置き換えます。
- このアプリは個人利用向けの試作版です。重要なデータは必ず別途バックアップしてください。
