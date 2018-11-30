---
layout: post
title: "CSS:transform-origin"
excerpt: ""
tags: 
  - css
  - transform-origin
---

```
div {
    transform: rotate(45deg);
    transform-origin: 20% 40%;
}
```
### CSS :transform-origin

이 transform-origin속성을 사용하면 변형 된 요소의 위치를 ​​변경할 수 있습니다.

2D 변환은 요소의 x 및 y 축을 변경할 수 있습니다. 3D 변형은 요소의 z 축을 변경할 수도 있습니다.

### 브라우저 지원
| property | 크롬 | IE | 파이어폭스 | 사파리 | 오페라 |
|:--------|:--------:|:--------:|:--------:|:--------:|:--------:|
| transform-origin(two-value syntax) | 36.0, 4.0 -webkit- | 10.0 ,9.0 -ms- | 16.0, 3.5 -moz- | 9.0, 3.2 -webkit- | 23.0,15.0 -webkit-,10.5 -o- |
| transform-origin(three-value syntax) | 36.0, 12.0 -webkit- | 10.0 | 10.0 | 9.0, 4.0 -webkit- | 23.0, 15.0 -webkit- |

### 속성
`transform-origin: x-axis y-axis z-axis|initial|inherit;`

+ x-axis :x축에서 뷰가 배치되는 위치를 정의합니다. (가능한 값:left, center, right, length, %)
+ y-axis :Y축에서 뷰가 배치되는 위치를 정의합니다. (가능한 값 :top, center, bottom, lenght, %)
+ z-axis :보기가 z축에 배치되는 위치를 정의합니다(3D 변환의 경우).[가능한 값 : length]
+ initial :기본속성을 가집니다.
+ inherit :속성을 상속 받습니다.
