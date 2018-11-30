---
layout: post
title: "CSS:animation-play-state
excerpt: ""
tags: 
  - css
  - animation-play-state
---

```
div {
    animation-play-state: paused;
}
```
### CSS :animation-play-state

animation-play-state속성은 애니메이션 실행 여부 또는 일시 중지 여부를 지정합니다.

 JavaScript의이 속성을 사용하면 순환 도중에 애니메이션을 일시 중지 할 수 있습니다.

### 브라우저 지원
| property | 크롬 | IE | 파이어폭스 | 사파리 | 오페라 |
|:--------|:--------:|:--------:|:--------:|:--------:|:--------:|
| animation | 43.0, 4.0 -webkit- | 10.0 | 16.0, 5.0 -moz- | 9.0, 4.0 -webkit- | 30.0, 15.0 -webkit-, 12.0 -o- |

### 속성
`animation-play-state: paused|running|initial|inherit;`

+ paused :애니메이션을 일시 중지하도록 지정합니다.
+ running :기본값. 애니메이션이 실행 중임을 지정합니다.
+ initial :기본속성을 가집니다.
+ inherit :속성을 상속 받습니다.
