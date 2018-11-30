---
layout: post
title: "CSS:animation-name"
excerpt: ""
tags: 
  - css
  - animation-name
---

```
div {
    animation-name: mymove;
}
```
### CSS :animation-name

animation-name속성은 `@keyframes` 애니메이션 의 이름을 지정합니다 .

### 브라우저 지원
| property | 크롬 | IE | 파이어폭스 | 사파리 | 오페라 |
|:--------|:--------:|:--------:|:--------:|:--------:|:--------:|
| animation | 43.0, 4.0 -webkit- | 10.0 | 16.0, 5.0 -moz- | 9.0, 4.0 -webkit- | 30.0, 15.0 -webkit-, 12.0 -o- |

### 속성
`animation-name: keyframename|none|initial|inherit;`

+ keyframename :선택기에 바인딩할 키 프레임의 이름을 지정합니다.
+ none :기본값. 애니메이션이 없음을 지정합니다(캐스케이드에서 가져온 애니메이션을 재정의하는 데 사용할 수 있음).
+ initial :기본속성을 가집니다.
+ inherit :속성을 상속 받습니다.
