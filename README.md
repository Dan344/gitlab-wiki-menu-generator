# gitlab-wiki-menu-generator
commit時に自動でメニューを生成するgithooks

# usage
1. gitlabのwikiのgithooks用のディレクリに `pre-commit` を配置
1. `_sidebar.me` の差し込みたい位置に下記タグを入力

```html
<!-- menu start -->
<!-- menu end -->
```

以降はcommitする度にメニューが生成されて差し込まれる
