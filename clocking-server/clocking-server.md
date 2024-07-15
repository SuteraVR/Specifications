# Clocking Server
SuteraにはClocking Serverが存在します。
Clocking Serverは各インスタンスにおける同期処理を担当します。

## SuteraにおけるClocking serverの具体的役割
- インスタンス内のエンティティ(※1)の状態の同期をとる
- ボイスチャットの処理を行う
- メッセージの送受信処理を行う

※1: Clocking Serverは長いため、しばしばClockerと略されます。

※2: エンティティとは、SuteraVRにおける動的オブジェクトの総称です。アバターや、投げられたり、乗れたり、エフェクトを発生するようなオブジェクトを含みます。
