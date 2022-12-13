---
layout: image-right
image: https://m.media-amazon.com/images/I/91522-r+ysL.jpg
---
# JavaScript<br>関数型プログラミング

半分くらい読んで力尽きている状況。
考え方は結構好き。（後半は結構複雑で難解

- 文でなく、式・表でロジックを構成する
- 関数で表した式を合成してロジックを形成する方法など

---

# JavaScript関数型プログラミング

<div grid="~ cols-2 gap-2" m="-t-2">

  手続き型コード

  関数型コード

  ```js
  var array=[0,1,2,3,4,5,6,7,8,9];

  for (let i = 0; i < array.length; i++) {
    array[i] = Math.pow(array[i],2);
  }

  array;

  // [0,1,4,9,16,25,36,49,64,81]
  ```

  ```js
  [0,1,2,3,4,5,6,7,8,9].map(
    (num) => Math.pow(num,2)
  );

  // [0,1,4,9,16,25,36,49,64,81]

  ```

</div>
