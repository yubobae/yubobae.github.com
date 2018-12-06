---
layout: post
title: "CSS:column-count "
excerpt: ""
tags: 
  - css
  - column-count
---

```
div {
    -webkit-column-count: 3; /* Chrome, Safari, Opera */
    -moz-column-count: 3; /* Firefox */
    column-count: 3;
}
```
### CSS :column-count

column-count속성은 요소가 분할되어야하는 열의 수를 지정합니다.

### 속성
`column-count: number|auto|initial|inherit;`

+ auto : 기본값. 열의 수는 다음과 같은 다른 속성에 의해 결정된다. "column-width"
+ number :요소의 내용이 흐를 최적의 열 수
+ initial :	 속성을 기본값으로 설정
+ inherit :속성을 상속 받습니다.
