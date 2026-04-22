# 🔤 ざっくり用語解説集

## AD

Administrative Distance の略。

## ARP

Address Resolution Protocol の略。

## AS

Autonomous System の略。
特定の管理組織が特定のポリシーの下で管理するネットワークの範囲のこと。

## ASBR

Autonomous System Boundary Router の略。

## ASBR Summary LSA

## AS external LSA

## ASN

Autonomous System Number の略。
[AS](#as) 番号。
従来は 2 オクテット (16 ビット = 65,536 通り) の表現ができた。
現在は 4 オクテット (32 ビット = 約 43 億通り) の表現ができるよう拡張されている。

## AS_PATH プリペンド

BGP の UPDATE メッセージにおける NLRI のパス属性に関する用語。
自身の AS 番号を意図的に複数追加することによって、経路を遠く見せかける手法のこと。

## BDR

Backup Designated Router の略。

## BGP

Border Gateway Protocol の略。
動的経路制御のひとつで、[EGP](#egp) に分類される。

## BGP ケイパビリティー

各 BGP スピーカーが対応可能な機能のこと。
BGP ピアを確立する初期段階で、OPEN メッセージにて通知する。

## BGP スピーカー

BGPが動作しているルーターのこと。

## BGP ピア

BGP スピーカー同士の接続関係のこと。

## BGP メッセージ

BGP スピーカー同士が交わす通信内容のこと。
TCP 179 番ポートで送信、受信する。

## CIDR

Classless Inter-Domain Routing の略。

## DBD

Database Description の略。

## DR

Designated Router の略。

## eBGP

external Border Gateway Protocol の略。

## eBGP ピア

異なる AS 間の BGP スピーカーとの接続関係のこと。

## ECMP

Equal Cost Multi Path の略。
OSPF において、メトリックの合計値が同じ経路が複数存在する場合、分散してパケットを振り分けて送り出せる機能。

## EGP

Exterior Gateway Protocol の略。
一般に AS 間で使う動的経路制御プロトコルの総称。
代表的なものは [BGP](#bgp) がある。
EGP の要求は次の2点である:

- AS 間で経路情報を適切に交換できること
- AS で使う経路制御に関する特定のポリシーを表せること

## EIGRP

Enhanced Interior Gateway Routing Protocol の略。
動的経路制御のひとつで、[IGP](#igp) に分類される。

## FIB

Forwarding Information Base の略。

## iBGP

internal Border Gateway Protocol の略。

## iBGP ピア

同一 AS の BGP スピーカー同士の接続関係のこと。

## IGP

Interior Gateway Protocol の略。
一般に AS 内部でのみ使う動的経路制御プロトコルの総称。
代表的なものは [RIP](#rip), [OSPF](#ospf), [EIGRP](#eigrp), [IS-IS](#is-is) がある。
IGP の要求は次の 2 点である:

- 効率の良い通信経路を計算できること
- ネットワークの変化に応じて経路を素早く再計算できること

## Integrated IS-IS

## IP

Internet Protocol の略。

## ISP

Internet Service Provider の略。
インターネット接続事業者。

## IS-IS

Intermediate System to Intermediate System の略。
動的経路制御のひとつで、[IGP](#igp) に分類される。

## LSA

Link State Advertisement の略。

## LSAck

Link State Acknowledgement の略。

## LSDB

Link State Database の略。
ネットワーク全体の地図のようなもの。
OSPF ルーターが収集する [LSA](#lsa) の集合で、ルーティングテーブルの生成に使う。
同一エリア内の OSPF ルーターであれば同じ内容になる。

## LSR

Link State Request の略。

## LSU

Link State Update の略。

## Multiprotocol Extensions

BGP スピーカーが IPv4 以外の経路情報を伝播できるようにするための機能のこと。

## Network LSA

## Network Summary LSA

## NLRI

Network Layer Reachability Information の略。
BGP の UPDATE メッセージにおいて、宛先ネットワークのアドレスを示す情報。

## OSI

Open Systems Interconnection の略。

## OSPF

Open Shortest Path First の略。
動的経路制御のひとつで、[IGP](#igp) に分類される。
経路上のリンク一つ一つについて、選択の優先度を示す指標（メトリック値）を設定する。
ルーターから見てパケットの出口側のメトリック値を加算し、合計値が小さい経路を優先して選ぶ。

## passive-interface

## RFC

Request for Comments の略。

## RIB

Routing Information Base の略。

## RIP

Routing Information Protocol の略。
動的経路制御のひとつで、[IGP](#igp) に分類される。

## Route Refresh

BGP スピーカーが経路情報の再送信を要求するための機能のこと。

## Router-ID

OSPF におけるルーターの識別子。
ルーターが保持する IP アドレスのうち1つを設定する。

## Router LSA

## Support for 4-Octet AS Number

BGP スピーカーが 4 オクテットの AS 番号を扱う機能のこと。

## TCP

Transmission Control Protocol の略。

## TCP/IP

## TTL

Time To Live の略。

## WITHDRAWN

BGP の UPDATE メッセージにおいて、利用できなくなった経路を伝えるための情報。

## アジャセンシー

OSPF において、接続情報を交換すべき相手のこと。

## イーサネットフレーム

## エリア

## コスト

⇒ [メトリック](#メトリック)

## スタティックルーティング

⇒ [静的経路制御](#静的経路制御)

## 静的経路制御

宛先ネットワークと転送先を固定して設定する経路選択方式のこと。
スタティックルーティング。

## 帯域

帯域幅、Bandwidth とも。

## ダイナミックルーティング

⇒ [動的経路制御](#動的経路制御)

## ディスタンスベクタ型ルーティングプロトコル

## デフォルトゲートウェイ

## デフォルトルート

## 動的経路制御

ルーターが状況に応じて動的に通信経路を変更する経路制御技術。
ダイナミックルーティング。

## ネイバー

## バックボーン

## バックボーンエリア

## パケット

## パスベクタ型ルーティングプロトコル



## マルチキャストアドレス

## メトリック

OSPF において、通信経路の負担の度合いのこと。
デフォルト値はネットワークインタフェースの帯域によって計算される。

## リンク

インタフェースに接続された通信回線のこと。

## リンクステート型ルーティングプロトコル

効率のよい通信経路を算出でき、ネットワークの状態変化に応じて迅速に経路を再計算できることが特徴。

## ルーティング

パケットを転送する際の最適な経路を決める仕組み。

## ループバックアドレス

## ループバックインタフェース

## ロンゲストマッチ
