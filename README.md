# veiler-legal — 転送専用（1.0.2 配信後に削除予定）

Veiler の公開サイトは **<https://veiler.kyatatata.com>** にあります。
このリポジトリは、サイトが以前使っていたアドレスを一時的に有効に保つための
ものです。文書の本体は
[kyataoka/veiler-lp](https://github.com/kyataoka/veiler-lp) にあります。

*Redirects only, and temporary. The site itself lives at veiler.kyatatata.com;
its source is in [kyataoka/veiler-lp](https://github.com/kyataoka/veiler-lp).*

## なぜ一時的に必要なのか

サイトは以前 `kyataoka.github.io/veiler-legal/` で公開しており、そのうち
プライバシーポリシーと利用規約の4つの URL は、配布済みのアプリから直接
開かれます（設定画面および初回起動時の同意画面）。プライバシーポリシーの URL は
App Store Connect にも登録されており、配信中のバージョンについては変更できません。

GitHub はリポジトリ名を変更したとき、プロジェクトサイトの URL だけ
リダイレクトしません（[Renaming a repository][rn]）。そのため文書を持つ
リポジトリを改名した時点で、旧アドレスはどのリポジトリにも対応しなくなります。
同じ名前のリポジトリをここに置き直しているのは、その転送を担わせるためです。

[rn]: https://docs.github.com/en/repositories/creating-and-managing-repositories/renaming-a-repository

## 削除の条件

1.0.2 でアプリ内の URL と App Store Connect の登録内容の双方を新しい
アドレスへ切り替え、その配信が完了した時点でこのリポジトリを削除します。
それ以前に削除すると、配信中のバージョンからプライバシーポリシーと利用規約を
開けなくなります。

## 内容

`/`, `/en/`, `/privacy/ja/`, `/privacy/en/`, `/terms/ja/`, `/terms/en/` の6ページ。
それぞれ canonical リンク・`meta refresh`・`location.replace` の3通りで、
新しいアドレスの同じパスへ転送します。
