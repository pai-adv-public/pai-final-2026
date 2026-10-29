# ロボットは、カメラに映っていない物を掴めるのか？

学習済みのロボット AI（π0.5）を追加学習なしで使い、カメラに映っていない物（かごの裏に隠れたスープ缶）を、人間が大まかな方向を逐一教えることで見つけて掴ませるデモ。人間の指示は Flow Reversal Steering（FRS, arXiv:2606.13675）で π0.5 自身の動きに変換する。Physical AI 応用1講座 最終課題。

## 実行方法

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pai-adv-public/pai-final-2026/blob/main/notebook/frs_blindspot_search.ipynb)

1. 上のボタンで Notebook を Google Colab で開く
2. ランタイムのタイプで GPU（T4）を選ぶ
3. 上から順に実行する（アカウントや認証情報は不要。インストールを含めて約 25 分）

## ライセンス

- コード: MIT（[LICENSE](LICENSE)）
- `assets/paligemma_tokenizer/`: Gemma 利用規約（[NOTICE](assets/paligemma_tokenizer/NOTICE.md)）
- 使用モデル `lerobot/pi05_libero_finetuned` は Gemma ライセンス、LeRobot は Apache-2.0、LIBERO は MIT
