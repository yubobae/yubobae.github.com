---
layout: post
title: "CSS:animation-timing-function"
excerpt: ""
tags: 
  - css
  - animation-timing-function
---

```
div {
    animation-timing-function: linear;
}
```
### CSS :animation-timing-function

animation-timing-function애니메이션의 속도 곡선을 지정한다.

속도 곡선은 애니메이션이 CSS 스타일 세트에서 다른 CSS 스타일로 변경하는 데 사용하는 TIME을 정의합니다.

속도 곡선은 변경을 부드럽게하는 데 사용됩니다.

### 브라우저 지원
| property | 크롬 | IE | 파이어폭스 | 사파리 | 오페라 |
|:--------|:--------:|:--------:|:--------:|:--------:|:--------:|
| transition | 43.0,4.0 -webkit- | 10.0 | 16.0, 5.0 -moz-|9.0,4.0 -webkit- | 30.0,15.0 -webkit-,12.0 -o- |

### 속성
`animation-timing-function: linear|ease|ease-in|ease-out|ease-in-out|step-start|step-end|steps(int,start|end)|cubic-bezier(n,n,n,n)|initial|inherit;`

+ ease :기본값. 애니메이션은 느리게 시작되며, 그 다음에는 빠르게 끝납니다.
+ linear :애니메이션의 속도는 처음부터 끝까지 동일합니다.
+ ease-in :애니메이션의 시작이 느리다.
+ ease-out :애니메이션의 끝이 느리다.
+ ease-in-out :애니메이션의 시작은 느리고 끝은 느립니다.
+ step-start :단계(1, 시작)와 같음
+ step-end :단계(1, 끝)와 같음
+ steps(int,start|end) :두 개의 파라미터를 사용하여 스테핑 기능을 지정합니다. 첫 번째 매개 변수는 함수의 간격 수를 지정합니다. 이 값은 양의 정수(0보다 큼)여야 합니다. 두 번째 파라미터(선택 사항)는 값 "시작" 또는 "끝" 중 하나이며 간격 내에 값의 변경이 발생하는 지점을 지정합니다. 두 번째 파라미터를 생략하면 "끝" 값이 지정됩니다.
+ cubic-bezier(n,n,n,n) :입방체 함수에서 자신의 값 정의 가능한 값은 0 ~ 1 사이의 숫자 값입니다.
+ initial :기본속성을 가집니다.
+ inherit :속성을 상속 받습니다.
