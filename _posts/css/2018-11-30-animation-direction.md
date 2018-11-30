---
layout: post
title: "CSS:animation-direction"
excerpt: ""
tags: 
  - css
  - animation-direction
---

```
div {
    animation-direction: alternate;
}
```
### CSS :animation-direction

animation-direction속성은 애니메이션을 앞으로, 뒤로 또는 번갈아 재생해야하는지 여부를 정의합니다.

### 브라우저 지원
| property | 크롬 | IE | 파이어폭스 | 사파리 | 오페라 |
|:--------|:--------:|:--------:|:--------:|:--------:|:--------:|
| animation | 43.0, 4.0 -webkit- | 10.0 | 16.0, 5.0 -moz- | 9.0, 4.0 -webkit- | 30.0, 15.0 -webkit-, 12.0 -o- |

### 속성
`animation-direction: normal|reverse|alternate|alternate-reverse|initial|inherit;`

+ normal :기본값. 애니메이션은 정상(전방)으로 재생됩니다.
+ reverse :애니메이션은 역방향(후방)으로 재생됩니다.
+ alternate :애니메이션은 먼저 앞으로 재생된 다음 뒤로 재생됩니다.
+ alternate-reverse :애니메이션은 먼저 뒤로 재생된 다음 앞으로 재생됩니다.
+ initial :기본속성을 가집니다.
+ inherit :속성을 상속 받습니다.
