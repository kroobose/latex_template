# LaTeX Templete

## このレポジトリについて
- このレポジトリは, vscode の devcontainer を利用し, コンテナ内で LaTeX 執筆をするためのテンプレートです
- ローカルの Docker を使わず, サーバの Docker で実装し, ローカル側の vscode で編集することもできます
- `git`, `docker`, `docker compose` が必要です

## 使い方
1. このテンプレートレポジトリを利用し, 新しいレポジトリを作る
2. 必要に応じ, `.devcontainer` を書き換える
3. `git clone <新規作成したレポジトリ>` でローカルにダウンロード
4. vscode でそのフォルダを開き, reopen in devcontainer で編集する

### 追加でマウントしたい場合
- マウントするファイル・フォルダを `.devcontainer` の一番下に記入する.
