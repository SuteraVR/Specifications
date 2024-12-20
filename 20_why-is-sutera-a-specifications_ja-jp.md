# なぜSuteraは仕様なのか？

Suteraの本体は、この文章が書かれている仕様書そのものであり、ある特定のソフトウェアではありません。
[Suteraの存在意義について](sutera/01-significance-of-sutera's-existence.md)にあるように、Suteraは持続的なSocial-VRの実現を目指しています。
そのため、特定の団体や人への依存をできる限り回避しようと試みており、これはSutera開発チームへの依存ですら例外ではありません。
仮にSuteraがソフトウェアとして存在していた場合、たとえば利用者のコミュニティでは受け入れられないような変更が提案された時、コミュニティによる意思決定でその変更を止めることはできません。オープンソース・プロジェクトとしてSuteraがGitHub上に公開されていたとしても、その変更を承認するかは事実上そのリポジトリのメンテナに委ねられているからです。
これはSuteraというソフトウェアが、結局Sutera開発チームに振り回されており、依存していることを意味します。
そのような場合にSuteraというソフトウェアをフォークして解決しようとするのは、現実的には互換性の観点から非常に困難です。
Suteraのフォークソフトウェア間、あるいは大本のSuteraとの通信に互換性がなければ、「Suteraというソフトウェアを使っている人同士でも通信できない」とった事態が生じ、やがてまた特定のフォークが支配的となり、ただコミュニティの体力を削りとっていくだけに終わります。

この問題を回避するため、SuteraをSuteraたらしめる、通信における規則や仕様やアイデア等のみを仕様書として中心で管理し、仕様書に従っている限りどんなソフトウェアの間でも通信をできるように設計しています。
これにより、Suteraに複数の実装がコミュニティにより出現しても、常にそれらの互換性が保たれ、「特定の団体に依存したソフトウェアを使うしかない」といった状況を軽減します。

またソフトウェアを制作するあたってはライブラリなど依存関係を多く持つ必要がある一方、仕様としてのSuteraはHTTPプロトコル, TCP/IPプロトコル, JSON, 公開鍵暗号などの既に十分多くの箇所で使用されている安定で持続的、オープンなプロトコルのみに依存しているため、この点でもSutera本体がソフトウェアではなく仕様であることが持続性に貢献しています。

## 拡張性の維持

"便利なSocial-VR"に求められる機能は、ユーザーによってニーズが異なったり、そのプラットフォームが汎用的であることから遠ざける要因になったりすることでしょう。
しかし、Suteraは公開された仕様書にすぎないため、コミュニティの中で実装が生まれていくことによって、Suteraという規格の持続性・汎用性を保ったまま、ユーザが望む形に沿ったSocial-VRを実現しつづけることができます。

## 公式による実装

以下は、Suteraチームが提供するSutera実装の一覧です。

- Bloom: [VanillaComponents](https://github.com/SuteraVR/VanillaComponents)
- Client: [VanillaClient](https://github.com/SuteraVR/VanillaClient)
