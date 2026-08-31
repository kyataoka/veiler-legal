# veiler-legal — 転送専用

Veiler の公開サイトは **<https://veiler.kyatatata.com>** にあります。
このリポジトリは、サイトが以前使っていたアドレスを引き続き有効に保つためだけの
ものです。文書の本体は
[kyataoka/veiler-lp](https://github.com/kyataoka/veiler-lp) にあります。

*Redirects only. The site itself lives at veiler.kyatatata.com; its source is in
[kyataoka/veiler-lp](https://github.com/kyataoka/veiler-lp).*

## このリポジトリを削除しないでください

サイトは以前 `kyataoka.github.io/veiler-legal/` で公開しており、そのうち
プライバシーポリシーと利用規約の4つの URL は、**配布済みのアプリから直接
開かれます**（設定画面および初回起動時の同意画面）。プライバシーポリシーの URL は
App Store Connect にも登録されており、配信中のバージョンについては変更できません。

GitHub はリポジトリ名を変更したとき、プロジェクトサイトの URL だけ
リダイレクトしません（[Renaming a repository][rn]）。そのため文書を持つ
リポジトリを改名した時点で、旧アドレスはどのリポジトリにも対応しなくなります。
同じ名前のリポジトリをここに置き直しているのは、その転送を担わせるためです。

このリポジトリを削除すると、すでにお使いのアプリからプライバシーポリシーと
利用規約を開けなくなります。

[rn]: https://docs.github.com/en/repositories/creating-and-managing-repositories/renaming-a-repository

## 内容

`/`, `/en/`, `/privacy/ja/`, `/privacy/en/`, `/terms/ja/`, `/terms/en/` の6ページ。
それぞれ canonical リンク・`meta refresh`・`location.replace` の3通りで、
新しいアドレスの同じパスへ転送します。
