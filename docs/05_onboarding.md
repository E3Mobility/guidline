# 初期セットアップ／オンボーディング手順

## PCセットアップ
**支給PCはWindows 11 Proが標準。社内標準セキュリティ設定・ポリシーを適用する**
必要なアプリケーション（VSCode, Git, Microsoft Teams, Outlook, OneDrive, Loop等）のインストール
必ず最新版を公式サイトから取得
不明点は社内ナレッジまたは管理者に相談

## 開発環境構築
**VSCodeは公式ダウンロード版を推奨（Microsoft Store版は非推奨）**
社内標準の拡張機能・プロファイルを導入
推奨拡張例：GitHub Pull Requests and Issues, Copilot, Python/Docker他
**Microsoftアカウント（@e3mobility.jp）でVSCode設定同期を推奨**
個人アカウント同期やローカル独自設定は極力避ける
**GitHubアカウント連携を必須**
Push/CloneにはPersonal Access TokenまたはSSH認証を利用

## 権限・アカウント払い出し
必要なAWS・GitHub・Teams等のアカウントを人事/管理者が発行
アカウントの利用目的・権限範囲も記録
社内イントラやドキュメント管理（Loop/SharePoint）へのアクセスも準備

## 初期トラブル対応
**VSCodeやGitHub拡張が認証できない場合は「サインイン」操作で再認証する**
Push/CloneエラーはTokenやSSHの再設定で解決
Copilot等のAI系拡張が動作不調な場合はVSCode再インストール（ダウンロード版で上書き）が最速解決
