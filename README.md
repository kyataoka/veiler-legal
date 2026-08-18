# veiler-legal

Veiler のプライバシーポリシーと利用規約。**ここが唯一の原本**で、
GitHub Pages がそのまま公開している。

- プライバシーポリシー: https://kyataoka.github.io/veiler-legal/privacy/ja/
- 利用規約: https://kyataoka.github.io/veiler-legal/terms/ja/

以前は Google Sites に手で貼っていた。掲載物とリポジトリが3回ズレて、
そのうち1回は「広告 SDK を一切組み込んでいません」と書いたまま広告付きで
出しかけた。コピーを2つ持たないのがその修正である。

## 変更するときに合わせるもの

利用規約の **最終改定日** を変えたら、アプリ側の `kTermsVersion`
（`lib/core/legal_urls.dart`）も同じ値にする。アプリは初回起動時の同意で
この値を端末に記録するため、食い違うと「何に同意したか」が答えられなくなる。
