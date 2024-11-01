# test-github-pages-redirect

GitHub Pagesで任意のURLにリダイレクトを行うテスト。

## 概要

紙面にQRコードの印刷が必要となったが、直接リンクを掲載してしまうとリンク先が変わったタイミングで再度印刷が必要になってしまう。

そこで、そのQRコードのリンクをGitHub Pagesに向けて、GitHub Pagesでリダイレクト（`http-equiv`）を設定することで、QRコードを書き換えずにリダイレクト先を変更できるようにする。

## URL

- [https://itxryx.github.io/test-github-pages-redirect/](https://itxryx.github.io/test-github-pages-redirect/)
- [https://itxryx.github.io/test-github-pages-redirect/xxx](https://itxryx.github.io/test-github-pages-redirect/xxx)
  - 存在しないページに対しても同様にリダイレクト処理を行う