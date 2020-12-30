https://takagotch.github.io/page448/

```
public/ というディレクトリを生成し、その下に自動でhtmlファイルを生成してくれる。便利。

ただし、Github Pagesでwebページを公開する場合には、 public/ ではなく docs/ 以下にhtmlを設置しておくルールとなっている（HugoではなくGitHub側のルールらしい）。GitHub Pagesは Hugoのレポジトリの中の docs/ フォルダを探し、その下にあるhtmlファイルをレンダリングしてくれる。

どうやって publicフォルダではなくdocs以下にhtmlファイルを設置するかというと、config.tomlファイルにpublishDir = "docs"の1行を追加するだけ。これだけでhugoコマンドを実行したときにHugo側で自動で publicではなくdocsフォルダを作ってその下にhtmlを生成してくれる。便利。
```

