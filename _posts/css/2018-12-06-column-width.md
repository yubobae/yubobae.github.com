---
layout: post
title: "CSS:column-width   "
excerpt: ""
tags: 
  - css
  - column-span 
---

```
div {
    -webkit-column-width: 100px; /* Chrome, Safari, Opera */
    -moz-column-width: 100px; /* Firefox */
    column-width: 100px;
}
```
### CSS :column-width 

column-width속성은 열 너비를 지정합니다.

열의 수는 요소 전체의 모든 내용을 표시하는 데 필요한 최소 열 수입니다.

column-width 유연한 속성입니다. 

브라우저에 대한 최소 너비 제안 column-width 으로 생각하십시오 .

브라우저가 지정된 너비에 적어도 두 개의 열을 맞출 수 없으면 열이 중지되어 단일 열로 떨어집니다.

### 속성
`column-width: auto|length|initial|inherit;`

+ auto :기본값. 열 너비는 브라우저에 의해 결정된다.
+ length :열의 너비를 지정하는 길이. 열의 수는 요소 전체에 걸쳐 모든 내용을 표시하는 데 필요한 최소 열의 수가 될 것이다.
+ initial :	 속성을 기본값으로 설정
+ inherit :속성을 상속 받습니다.
