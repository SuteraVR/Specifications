# Suteraネットワーク  

SuteraのサーバーサイドはSuteraネットワークという仕組みによって実現されています。
Suteraネットワークは、Bloomという独立した複数のサーバーからなる中央サーバーを持たないネットワークです。  

## Suteraネットワークの構成について  

Suteraネットワークは以下の構成で成り立っています。  
<pre>
Suteraネットワーク
└── Bloom
    ├── Gateway Component
    ├── Object-Storage Component
    └── Relay Component
</pre>
また、Suteraネットワークを構成する要素はすべてHTTPもしくはHTTPSによって通信されます。  
(参照: [SuteraがHTTPにこだわる理由](sutera/why-http.md))

## それぞれのComponentについて  

Suteraネットワークを構成する要素であるそれぞれのComponentの概要について説明します。  

### Gateway  

接続先の公開鍵を入力するとIPアドレスとエンドポイントを返します。  

### Oject-Storage  

非ユーザー依存データを保持します。  
(参照: [Object-Storage](object-storage/01-what-is-object-storage.md))

### Relay  

ユーザー動作の中継を行います。例えば、アバターデータの発信、フレンドへのアクションなどです。  

これらのComponentの役割をBloomに持たせ、独立した複数のサーバーからなる中央サーバーを持たないSuteraネットワークを構築していきます。  
