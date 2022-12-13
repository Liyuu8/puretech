---
layout: iframe-right
url: https://codesandbox.io/embed/parallel-animation-icon-yos6oq?fontsize=10&hidenavigation=1&theme=dark
---
# [React Native]<br>ポジション移動 ＋<br>サイズ縮小 Animation

- サイズ変更とポジション移動のアニメーションの並列処理で移動先の座標の制御が思い通りにいかなかったので、調べてみた

- ポジション移動アニメーションのコンポーネント内にサイズ変更アニメーションのコンポーネントをネストすることで、移動先の座標を制御することができた