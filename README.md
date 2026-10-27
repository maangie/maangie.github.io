# [activeadmin.info](http://activeadmin.info) のコンテンツ

このリポジトリは [activeadmin.info](http://activeadmin.info) のコンテンツを収録しています。
サイトは [Jekyll](https://jekyllrb.com/) で生成する静的サイトで、GitHub Pages で公開されます。

## ディレクトリ構成

| パス | 内容 |
| --- | --- |
| `docs/` | ドキュメント本体(Markdown)と目次ページ `documentation.html` |
| `_layouts/` | ページ共通のレイアウト |
| `_includes/` | ヘッダー、フッター、目次、メニューなどの部品 |
| `images/` | 画像 |
| `stylesheets/` | スタイルシート |
| `index.html` | トップページ |
| `404.html` | 404 ページ |
| `CNAME` | 独自ドメイン(`activeadmin.info`)の設定 |
| `_config.yml` | Jekyll の設定(Markdown 処理は redcarpet、シンタックスハイライトは rouge) |

## ローカルでの確認方法

Ruby と Bundler が必要です。

```sh
bundle install
bundle exec jekyll serve
```

起動後、<http://localhost:4000> で表示を確認できます。

## コントリビュート

ドキュメントの内容を更新したい場合は、このリポジトリではなく
[activeadmin/activeadmin](https://github.com/activeadmin/activeadmin) にコントリビュートしてください。

このリポジトリには、リンク切れや誤字の修正、サイトのレイアウトに関する修正を送ってください。
