---
layout: post
title: "CSS:animation-iteration-count
excerpt: ""
tags: 
  - css
  - animation-iteration-count
---

```
div {
    animation-iteration-count: 2;
}
```
### CSS :animation-iteration-count

animation-iteration-count속성은 애니메이션을 재생해야하는 횟수를 지정합니다.

### 브라우저 지원
| property | 크롬 | IE | 파이어폭스 | 사파리 | 오페라 |
|:--------|:--------:|:--------:|:--------:|:--------:|:--------:|
| animation | 43.0, 4.0 -webkit- | 10.0 | 16.0, 5.0 -moz- | 9.0, 4.0 -webkit- | 30.0, 15.0 -webkit-, 12.0 -o- |

### 속성
`animation-iteration-count: number|infinite|initial|inherit;`

+ number :애니메이션 재생 횟수를 정의하는 숫자입니다. 기본값은 1입니다.
+ infinite :애니메이션을 (영원히) 무한대로 재생하도록 지정합니다.
+ initial :기본속성을 가집니다.
+ inherit :속성을 상속 받습니다.
