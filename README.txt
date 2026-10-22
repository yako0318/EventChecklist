Event Checklist PWA - 初期パッケージ

内容
- index.html: 購入品リスト・予算管理
- manifest.json: ホーム画面追加用設定
- sw.js: アプリ本体のキャッシュ（Service Worker）
- icons/: アプリアイコン

重要
1. index.html を file:// で開いただけではPWAとして動作しません。
2. Service Workerの登録にはHTTPS、または開発用localhostが必要です。
3. file:// で使っていた購入データは、HTTPSで公開したアプリの保存領域とは別です。先に第1版からCSVを書き出してバックアップしてください。
4. HTTPSで公開したURLをオンライン状態で開き、完全に読み込ませてからホーム画面に追加してください。
5. iPhoneでホーム画面に追加した後、アプリを一度開いてから機内モードで起動テストしてください。
6. この版はCSVインポート/エクスポートに対応しています。Excel .xlsx の直接読み込みはまだ未対応です。
