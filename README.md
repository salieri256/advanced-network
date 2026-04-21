# ざっくりわかる動的経路制御

[![Open in GitHub Codespaces][codespaces-icon]][codespaces-url]

[codespaces-icon]: https://github.com/codespaces/badge.svg
[codespaces-url]: https://codespaces.new/salieri256/advanced-network

## 📌 チャプター

- 🔰 第1章 - L2 パケット転送
- [🔀 第2章 - スタティックルーティング](./Static/)
- [🔀 第3章 - OSPF](./OSPF/)
- 🔀 第4章 - BGP
- 🌐 第5章 - 動的経路制御
- [🔤 ざっくりわかる用語集](./Glossary.md)

## 🧪 実験環境

実験環境の構築:

```bash
containerlab deploy --reconfigure
```

実験環境の削除:

```bash
containerlab destroy --cleanup
```

## なぜ動的経路制御が必要か

- パケットが経由する経路を適切に選択するため
- 回線や機器が停止した際に通信経路を迂回して通信を継続させるため

## 📖 参考文献

- [上級ネットワーク技術者になる本 ゼロから分かる動的経路制御](https://bookplus.nikkei.com/atcl/catalog/25/07/25/02129/)

## 🤝 ライセンス

MIT。詳細は [LICENSE](./LICENSE) を参照してください。
