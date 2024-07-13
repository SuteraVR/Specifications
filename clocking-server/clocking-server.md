# Clocking Server
SuteraにはClocking server(長いため、しばしばClockerと略される)が存在します。
Clocking Serverは各インスタンスにおける同期処理を担当します。

## SuteraにおけるClocking serverの具体的役割
- インスタンス内の動的オブジェクト(エンティティ)の状態の動機をとる
    - エンティティにはアバター、投げられたり、乗れたり、エフェクトを発生するようなオブジェクトを含む。
- ボイスチャットの処理を行う
- メッセージの送受信処理を行う
