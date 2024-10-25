# なぜSuteraは仕様なのか？

Suteraの本体は、この文章が書かれている仕様書そのものであり、ある特定のソフトウェアではありません。
[Suteraの存在意義について](sutera/01-significance-of-sutera's-existence.md)にあるように、Suteraは持続的なSocial-VRの実現を目指しています。
そのためには特定の環境や実装に依存しないことが望ましいと私たちは考えており、Suteraを仕様書という抽象化された状態で公開し、誰でも実装できるようにしました。

## 拡張性の維持

"便利なSocial-VR"に求められる機能は、ユーザーによってニーズが異なったり、そのプラットフォームが汎用的であることから遠ざける要因になったりすることでしょう。
しかし、Suteraは公開された仕様書にすぎないため、コミュニティの中で実装が生まれていくことによって、Suteraという規格の持続性・汎用性を保ったまま、ユーザが望む形に沿ったSocial-VRを実現し続けることができます。
また、複数の実装が存在することでそれらの間に競争が生まれ、コミュニティがより活発になることも期待できるかもしれません。

## 公式による実装

以下は、Suteraチームが提供するSutera実装の一覧です。

- Bloom: [VanillaComponents](https://github.com/SuteraVR/VanillaComponents)
- Client: [VanillaClient](https://github.com/SuteraVR/VanillaClient)
