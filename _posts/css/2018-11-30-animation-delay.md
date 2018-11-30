---
layout: post
title: "CSS:animation-delay"
excerpt: ""
tags: 
  - css
  - animation-delay
---

```
div {
    animation-delay: 2s;
}
```
### CSS :animation-delay

animation-delay속성은 애니메이션의 시작에 대한 지연을 지정합니다.

애니메이션 지연 값은 초 또는 밀리 초 (ms)로 정의됩니다.

### 브라우저 지원
| property | 크롬 | IE | 파이어폭스 | 사파리 | 오페라 |
|:--------|:--------:|:--------:|:--------:|:--------:|:--------:|
| animation | 43.0, 4.0 -webkit- | 10.0 | 16.0, 5.0 -moz- | 9.0, 4.0 -webkit- | 30.0, 15.0 -webkit-, 12.0 -o- |

### 속성
`animation-delay: time|initial|inherit;`

+ time :선택적. 애니메이션이 시작되기 전 대기할 시간(초) 또는 밀리초(ms)를 정의합니다. 기본값은 0입니다. 음수 값은 허용됩니다. 음수 값을 사용하면 이미 N초/밀리초 동안 재생된 것처럼 애니메이션이 시작됩니다.
+ initial :기본속성을 가집니다.
+ inherit :속성을 상속 받습니다.
