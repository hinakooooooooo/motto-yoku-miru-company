# もっとよくみる｜会社に行く（v12）

「大変よく頑張りました展」の3D体験を GitHub Pages で公開します。

## アップロードと公開

1. このリポジトリの **Add file → Upload files** を開きます。
2. `motto-yoku-miru-company-github-pages-easy.zip` を **解凍せず、そのまま**アップロードし、`Commit changes` を押します。
3. **Settings → Pages → Build and deployment → Source: GitHub Actions** を選びます。
4. **Actions** タブの `Publish company exhibition` の実行が緑のチェックになることを確認してください。必要に応じて `Run workflow` で再実行します。
5. 公開URL: https://hinakooooooooo.github.io/motto-yoku-miru-company/

ZIPの中身には、単独動作する `index.html` とライセンスが含まれています。ワークフローは `_site/` にZIPを展開して Pages に公開します。

> GitHub Pages が有効になるまで、公開URLは404になる場合があります。ZIP名は正確に一致させてください。
