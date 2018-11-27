---
layout: post
title: "CSS:visibility"
excerpt: ""
tags: 
  - css
  - visibility
---

```
h2.a {
    visibility: visible;
}

h2.b {
    visibility: hidden;
}
```
### CSS :visibility

 visibility속성은 요소가 표시되는지 여부를 지정합니다.


### 속성
`visibility: visible|hidden|collapse|initial|inherit;`

+ visible :기본값. 요소가 표시됩니다.
+ hidden :요소가 숨겨져 있지만 공간을 차지합니다.
+ collapse :테이블 행(tr), 행 그룹(tody), 열(col), 열 그룹(colgroup)에만 해당됩니다. 이 값은 행 또는 열을 제거하지만 테이블 레이아웃에는 영향을 주지 않습니다. 행 또는 열이 차지하는 공간은 다른 콘텐츠에 사용할 수 있습니다.
다른 요소에 접힌 경우 "숨겨진"으로 렌더링합니다.
+ initial :기본속성을 가집니다.
+ inherit :속성을 상속 받습니다.
