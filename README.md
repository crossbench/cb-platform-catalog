# cb-platform-catalog

ゲームプラットフォームアプリ向けのゲームカタログです。GitHub Pages で公開されます。

- `manifest.json` — ゲーム一覧（タイトル、バージョン、パッケージURL、sha256、サイズ）
- `packages/<id>-<version>.zip` — ゲーム本体（game.json + index.html + アセット）

アプリは manifest.json を取得し、ゲームをダウンロード・検証（sha256）してから端末内でオフライン再生します。
