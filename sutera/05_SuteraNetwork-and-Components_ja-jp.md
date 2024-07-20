# Suteraネットワーク  
SuteraにはSuteraネットワークという構想が存在します。  
Suteraネットワークは、Bloomという独立した複数のサーバーからなる中央サーバーを持たないネットワークです。  

# Suteraネットワークの構成について  
Suteraネットワークは以下の構成で成り立っています。  
<pre>
Suteraネットワーク
└── Bloom
    ├── Gateway Component
    ├── Object-Storage Component
    └── Relay Component
</pre>
また、Suteraネットワークを構成する要素はすべてHTTPもしくはHTTPSによって通信されます。  

# それぞれのComponentについて  
Suteraネットワークを構成する要素であるそれぞれのComponentの概要について説明します。  
### Gateway  
接続先の公開鍵を入力するとIPアドレスとエンドポイントを返します。  
### Oject-Storage  
非ユーザー依存データの保持を行います。  
### Relay  
ユーザー動作の中継を行います。例えば、アバターデータの発信、フレンドへのアクションなどです。  

これらのComponentの役割をBloomに持たせ、独立した複数のサーバーからなる中央サーバーを持たないSuteraネットワークを構築していきます。  
