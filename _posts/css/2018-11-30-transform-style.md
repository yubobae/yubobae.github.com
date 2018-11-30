---
layout: post
title: "CSS:transform-style"
excerpt: ""
tags: 
  - css
  - transform-style
---

```
div {
    transform: rotateY(60deg);
    transform-style: preserve-3d;
}
```
### CSS :transform-style

transform-style속성은 3D 공간에서 중첩 요소를 렌더링하는 방법을 지정합니다.

### 브라우저 지원
| property | 크롬 | IE | 파이어폭스 | 사파리 | 오페라 |
|:--------|:--------:|:--------:|:--------:|:--------:|:--------:|
| transform-style | 36.0, 4.0 -webkit- | 11.0 | 16.0, 10.0 -moz- | 9.0, 4.0 -webkit- | 23.0,15.0 -webkit-,10.5 -o- |

### 속성
`transform-style: flat|preserve-3d|initial|inherit;`

+ flat :하위 요소가 3D 위치를 유지하지 않도록 지정합니다. 기본값입니다.
+ preserve-3d :하위 요소가 3D 위치를 유지하도록 지정합니다.
+ initial :기본속성을 가집니다.
+ inherit :속성을 상속 받습니다.
