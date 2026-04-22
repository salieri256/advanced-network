# 🔀 BGP

## 🧪 実験環境

|![](./screenshots/topology.png)|
|:-:|
|トポロジー図|

|ネットワーク|概要|
|:-|:-|
|`10.0.1.0/24`|`PC1` - `RT1`|

|ノード|I/F|IPv4 アドレス|MAC アドレス|
|:-|:-|:-|:-|
|`PC1`|`eth1`|`10.0.1.1/24`|`0a:00:00:00:00:01`|

実験環境の構築:

```bash
containerlab deploy --reconfigure
```

## ✅ 動作確認
