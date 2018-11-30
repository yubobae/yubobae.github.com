---
layout: post
title: "CSS:transition
excerpt: ""
tags: 
  - css
  - transition
---

```
div {
    width: 100px;
    transition: width 2s;
}

div:hover {
    width: 300px;
}
```
### CSS :transition

이 transition속성은 다음에 대한 속기 속성입니다.
- transition-property
- transition-duration
- transition-timing-function
- transition-delay

### 브라우저 지원
| property | 크롬 | IE | 파이어폭스 | 사파리 | 오페라 |
|:--------|:--------:|:--------:|:--------:|:--------:|:--------:|
| transition | 26.0, 4.0 -webkit- | 10.0 | 16.0, 4.0 -moz- | 6.1, 3.1 -webkit- | 12.1,10.5 -o- |

### 속성
`transition: property duration timing-function delay|initial|inherit;`

+ transition-property :전환 효과가 사용될 CSS 속성의 이름을 지정합니다.
+ transition-duration :전환 효과를 완료하는 데 걸리는 시간(초 또는 밀리초)을 지정합니다.
+ transition-timing-function :전환 효과의 속도 곡선을 지정합니다.
+ transition-delay :전환 효과 시작 시기를 정의합니다.
+ initial :기본속성을 가집니다.
+ inherit :속성을 상속 받습니다.
