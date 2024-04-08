# SuteraVR/Specifications (開発中)
SuteraVRは、分散・分散型VRプラットフォームを構成するプロトコルであり、下の仕様定義によって構成されています：
<dl>
<dt>Glossary</dt>
<dd>仕様の記述内で使用する用語をより厳密に定義するための仕様。</dd>
<dt>Client</dt>
<dd>SuteraVRネットワークに参加し、仮想世界を描画、接触するためのアプリケーションが従うべき仕様。</dd>
<dt>Bloom</dt>
<dd>クライアント間の通信を仲介したり、永続アセットを分散して保存したりするためのサーバーが従うべき仕様。</dd>
<dt>Costume</dt>
<dd>SuteraVRネットワークによって配布されるコスチュームが従うべき仕様。</dd>
<dt>World</dt>
<dd>SuteraVRネットワークによって配布されるワールドが従うべき仕様。</dd>
</dl>

<br />

## 🚨 注意

このプロトコルは**開発段階**にあり、正式にリリースされていません。
もしこのプロジェクトに興味があれば、ぜひ[公式Discordサーバー]((https://discord.gg/pTjBHkVQbT)!)に参加しましょう！

また、私たちはあなたのコントリビュートを待っています！[Issueを開く](https://github.com/SuteraVR/Specifications/issues/new/choose) / [PRを開く](https://github.com/SuteraVR/Specifications/compare)

## 🎮 SuteraVRのはじめかた
SuteraVRは仕様の集合体のようなもので、ある特定のソフトやアプリ、ソースコードではありません。  
例えば、同じバージョンの仕様`SuteraVR/Specifications/Client`に従うソフトであれば、どんなものでもSuteraVRネットワークに参加できます。  
このように、SuteraVRの特定の仕様を満たすソフトウェアをSuteraVRの「実装」といいます。

以下は、よく利用されているSuteraVRの実装の一覧です。

### よく知られたSuteraVRの実装
**SuteraVR/Specifications/Client**
  - SuteraVR/Godot-Client (SuteraVR Team, **開発中で、使用できません**)

**SuteraVR/Specifications/Bloom**
  - SuteraVR/sutera-bloom-rs (SuteraVR Team, **開発中で、使用できません**)

## 🧭 コンセプト

- **分散型 & 非中央集権**
  - メタバースを現実と同じくらい確かなものにするためには、特定の企業やプラットフォームに依存する脆弱なものであってはいけません。仮想世界よ、永遠に。
 
## ✨ 設計

- **Bloom**
  - 誰でもBloomを作成することができます。Bloomとは独立したVR-Socialプラットフォームとして機能し、フレンドと遊んだりワールドやアイテムをアップロードすることができるものです。全てのBloomは互いに通信し、他のBloomのコンテンツにアクセスすることができます。
- **サンドボックス環境**
  - サンドボックス環境でデータ処理を完結させます。ウイルスや悪意のあるスクリプトがサンドボックスの外に影響を及ぼすのを防ぎます。
- **SuteraVR SDK**
  - アバターやワールド、アイテムをアップロードすることができ、あなたがコーディングした機能を追加することができます。

## 🌼 名前の由来

"Sutera"が"Stella"の誤字ではないかと心配されることがよくありますが、バコパとしても知られるゴマノハグサ科のお花の名前です。

## 💡 インスパイアを受けたプロジクト

- ActivityPubソフトウェア: Misskey, Mastodon, etc
- メタバースプラットフォーム: VRChat, Resonite, etc
