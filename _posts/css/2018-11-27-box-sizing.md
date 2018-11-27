---
layout: post
title: "CSS:box-sizing"
excerpt: ""
tags: 
  - css
  - box-sizing
---

```
#example1 {
    box-sizing: border-box;
}
```
### CSS :box-sizing

 box-sizing속성은 요소의 너비와 높이를 계산하는 방법을 정의합니다. 요소에 여백과 테두리를 포함할지 여부를 정의합니다.


### 속성
`box-sizing: content-box|border-box|initial|inherit;`

+ content-box :default값. 너비 및 높이 특성(및 최소/최대 속성)은 내용만 포함합니다. 테두리 및 패딩은 포함되지 않습니다.
+ border-box :폭 및 높이 특성(및 최소/최대 속성)에는 내용, 패딩 및 테두리가 포함됩니다.
+ initial :기본속성을 가집니다.
+ inherit :속성을 상속 받습니다.
