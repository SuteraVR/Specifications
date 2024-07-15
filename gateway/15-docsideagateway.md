# Gateway Component

# 概要
Sutera Networkにある各Bloomに割り当てられている公開鍵を認証し、接続先のエンドポイントを返す。

# 詳細
Sutera Networkのコンポーネントの一つに、Bloomというものがある。
このBloomへ接続する際に、Gatewayコンポーネントに公開鍵を渡して認証する必要がある。
無事認証が済めば、接続先のBloomに割り当てられているエンドポイント(IPとPort)を返す。

# 備考
各Bloomの公開鍵は、ED25519アルゴリズムによって求められるものである

# 例
Bloom_hogeというサーバーに接続する場合

Bloom_hogeの公開鍵を取得  
↓  
Gatewayに取得した公開鍵を投げる  
↓  
Bloom_hogeのエンドポイントを取得  

といった流れを踏む
