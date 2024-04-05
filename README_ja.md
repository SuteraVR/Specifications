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

## SuteraVRのはじめかた
SuteraVRは仕様の集合体のようなもので、ある特定のソフトやアプリ、ソースコードではありません。  
例えば、同じバージョンの仕様`SuteraVR/Specifications/Client`に従うソフトであれば、どんなものでもSuteraVRネットワークに参加できます。  
このように、SuteraVRの特定の仕様を満たすソフトウェアをSuteraVRの「実装」といいます。

以下は、よく利用されているSuteraVRの実装の一覧です。

### よく知られたSuteraVRの実装
**SuteraVR/Specifications/Client**
  - SuteraVR/Godot-Client (SuteraVR Team, **開発中で、使用できません**)

**SuteraVR/Specifications/Bloom**
  - SuteraVR/sutera-bloom-rs (SuteraVR Team, **開発中で、使用できません**)
