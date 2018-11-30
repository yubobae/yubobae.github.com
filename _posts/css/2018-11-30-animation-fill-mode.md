---
layout: post
title: "CSS:animation-fill-mode
excerpt: ""
tags: 
  - css
  - animation-fill-mode
---

```
div {
    animation-fill-mode: forwards;
}
```
### CSS :animation-fill-mode

animation-fill-mode속성은 애니메이션이 재생되지 않을 때 (시작 전, 끝나기 전에 또는 둘 다) 요소의 스타일을 지정합니다.

CSS 애니메이션은 첫 번째 키 프레임이 재생되거나 마지막 키 프레임이 재생 된 후에 요소에 영향을주지 않습니다. animation-fill-mode속성은이 동작을 재정의 할 수 있습니다.

### 브라우저 지원
| property | 크롬 | IE | 파이어폭스 | 사파리 | 오페라 |
|:--------|:--------:|:--------:|:--------:|:--------:|:--------:|
| animation | 43.0, 4.0 -webkit- | 10.0 | 16.0, 5.0 -moz- | 9.0, 4.0 -webkit- | 30.0, 15.0 -webkit-, 12.0 -o- |

### 속성
`animation-fill-mode: none|forwards|backwards|both|initial|inherit;`

+ none :기본값. 애니메이션은 실행 전이나 실행 후에 요소에 스타일을 적용하지 않습니다.
+ forwards :요소는 마지막 키 프레임에 의해 설정된 스타일 값을 유지합니다(애니메이션 방향 및 애니메이션 입력 카운트에 따라 다름).
+ backwards :요소는 첫 번째 키 프레임에 의해 설정된 스타일 값을 얻고(애니메이션 방향에 따라 다름) 애니메이션 지연 기간 동안 이 값을 유지합니다.
+ both :애니메이션은 앞뒤로 규칙을 따라 애니메이션 속성을 양방향으로 확장합니다.
+ initial :기본속성을 가집니다.
+ inherit :속성을 상속 받습니다.
