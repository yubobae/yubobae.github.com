---
layout: post
title: "CSS:transition-timing-function"
excerpt: ""
tags: 
  - css
  - transition-timing-function
---

```
div {
    transition-timing-function: linear;
}
```
### CSS :transition-timing-function

transition-timing-function속성은 전환 효과의 속도 곡선을 지정합니다.

이 속성을 사용하면 전환 효과에서 지속 시간 동안 속도를 변경할 수 있습니다.

### 브라우저 지원
| property | 크롬 | IE | 파이어폭스 | 사파리 | 오페라 |
|:--------|:--------:|:--------:|:--------:|:--------:|:--------:|
| transition | 26.0, 4.0 -webkit- | 10.0 | 16.0, 4.0 -moz- | 6.1, 3.1 -webkit- | 12.1,10.5 -o- |

### 속성
`transition-timing-function: linear|ease|ease-in|ease-out|ease-in-out|step-start|step-end|steps(int,start|end)|cubic-bezier(n,n,n,n)|initial|inherit;`

+ ease :기본값. 느린 시작, 빠른 시작, 서서히 종료되는 전환 효과를 지정합니다(0.25,0.1,0.25,1)
+ linear :시작부터 끝까지 동일한 속도로 전환 효과를 지정합니다(0,0,1,1)
+ ease-in :느린 시작에 대한 전환 효과를 지정합니다(0.42,0,1,1)
+ ease-out :저속 엔드로 전환 효과를 지정합니다(0,0.58,1)
+ ease-in-out :느린 시작과 끝의 전환 효과를 지정합니다(0.42,0,0.58,1)
+ step-start :단계(1, 시작)와 같음
+ step-end :단계(1, 끝)와 같음
+ steps(int,start|end) :두 개의 파라미터를 사용하여 스테핑 기능을 지정합니다. 첫 번째 매개 변수는 함수의 간격 수를 지정합니다. 이 값은 양의 정수(0보다 큼)여야 합니다. 두 번째 파라미터(선택 사항)는 값 "시작" 또는 "끝" 중 하나이며 간격 내에 값의 변경이 발생하는 지점을 지정합니다. 두 번째 파라미터를 생략하면 "끝" 값이 지정됩니다.
+ cubic-bezier(n,n,n,n) :입방체 함수에서 자신의 값을 정의합니다. 가능한 값은 0 ~ 1 사이의 숫자 값입니다.
+ initial :기본속성을 가집니다.
+ inherit :속성을 상속 받습니다.
