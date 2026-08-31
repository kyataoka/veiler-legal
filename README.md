# veiler-legal — 転送のみ

中身はここにはない。Veiler の公開サイトは **veiler.kyatatata.com** にあり、
このリポジトリはその旧アドレスを生かしておくためだけに存在する。

## なぜ空のまま残すのか

サイトは以前 `kyataoka.github.io/veiler-legal/` で公開していて、その4つの
URL が **出荷済みのアプリのバイナリに直接書かれている**（設定画面の
「プライバシーポリシー」「利用規約」、および初回同意画面）。App Store Connect
に登録したプライバシーポリシー URL も、配信中は変更できない。

GitHub はリポジトリ名を変えたとき、プロジェクトサイトの URL だけ
リダイレクトしない。中身を持つリポジトリを別名にした時点で
`kyataoka.github.io/veiler-legal/` はどのリポジトリにも対応しなくなり、
すでに配布した版からポリシーが開けなくなる。

だから同じ名前のリポジトリをここに置き直し、転送だけを担わせている。
**消してはいけない。** 消すと、手元にあるアプリのリンクが死ぬ。

## 中身

`/`, `/en/`, `/privacy/ja/`, `/privacy/en/`, `/terms/ja/`, `/terms/en/` の
6ページ。それぞれ canonical・meta refresh・`location.replace` の3段構えで
新ドメインの同じパスへ送る。
