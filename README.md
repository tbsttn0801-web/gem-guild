# iPhoneだけで公開する手順
1. このzipを「ファイル」アプリで開き、展開する（worker.js と wrangler.jsonc の2つだけ）
2. Safariで github.com にログイン → 右上「＋」→ New repository → 名前を入れて作成
3. 作成後の画面の「uploading an existing file」→ 2ファイルを選択 → Commit changes
4. Safariで dash.cloudflare.com にログイン → Workers & Pages → Create → GitHubと連携してそのリポジトリを選択 → Deploy
5. 完了後に表示される ○○.workers.dev がゲームのURL
