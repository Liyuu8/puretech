---
theme: seriph
background: https://source.unsplash.com/collection/94734566/1920x1080
class: 'text-center'
# https://sli.dev/custom/highlighters.html
highlighter: shiki
lineNumbers: false
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
# persist drawings in exports and build
drawings:
  persist: false
css: unocss
---

# PureTech

今年個人的に勉強したことまとめ

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    Press Space for next page <carbon:arrow-right class="inline"/>
  </span>
</div>

<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->

---

# Topic

- 読んだ本・ハンズオンで触ったものとか
  - 🎨 **Three.js** - JavaScript 3D Library
  - 📗 **JavaScript関数型プログラミング**
  - 📘 **良いコード／悪いコードで学ぶ設計入門**
- 業務関係 - React Native
  - 🤹 **ポジション移動 ＋ サイズ縮小 の並列アニメーション**
  - 🛠 **ScrollView + 2次元配列のView で FlatList を代替する**
- ライフハック関連
  - 🖥 **Zapier, IFTTT でサービス連携してみた**

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

<!--
Here is another comment.
-->

---
src: ./pages/hands_on/three_js.md
---

---
src: ./pages/books/js_functional_programming.md
---

---
src: ./pages/books/good_code_bad_code.md
---

---
src: ./pages/works/parallel_animation_icon.md
---

---
src: ./pages/works/multi_column_display_without_flatlist.md
---

---
src: ./pages/life_hack/zapier_ifttt.md
---
