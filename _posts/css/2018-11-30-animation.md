---
layout: post
title: "CSS:animation"
excerpt: ""
tags: 
  - css
  - animation
---

```
div {
    animation: mymove 5s infinite;
}
```
### CSS :animation

animation속성은 다음에 대한 속기 속성입니다.

+ animation-name
+ animation-duration
+ animation-timing-function
+ animation-delay	
+ animation-iteration-count
+ animation-direction
+ animation-fill-mode
+ animation-play-state


### 브라우저 지원
| property | 크롬 | IE | 파이어폭스 | 사파리 | 오페라 |
|:--------|:--------:|:--------:|:--------:|:--------:|:--------:|
| animation | 43.0, 4.0 -webkit- | 10.0 | 16.0, 5.0 -moz- | 9.0, 4.0 -webkit- | 30.0, 15.0 -webkit-, 12.0 -o- |

### 속성
`animation: name duration timing-function delay iteration-count direction fill-mode play-state;`

+ animation-name :선택기에 바인딩할 키 프레임의 이름을 지정합니다.
+ animation-duration :애니메이션 완료에 걸리는 시간(초 또는 밀리초)을 지정합니다.
+ animation-timing-function :애니메이션의 속도 곡선을 지정합니다.
+ animation-delay	:애니메이션을 시작하기 전에 지연을 지정합니다.
+ animation-iteration-count :애니메이션을 재생할 횟수를 지정합니다.
+ animation-direction :대체 사이클에서 애니메이션의 역회전 재생 여부를 지정합니다.
+ animation-fill-mode :실행 시간 외에 애니메이션에 적용할 값을 지정합니다.
+ animation-play-state :애니메이션 실행 여부를 지정합니다.
+ initial :기본속성을 가집니다.
+ inherit :속성을 상속 받습니다.
