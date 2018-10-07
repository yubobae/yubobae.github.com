---
layout: post
title: "CSS:grid-column-end "
excerpt: ""
tags: 
  - css
  - grid-column-end
  - 그리드
  
---


### CSS : grid-column-end
```
.item1 {
  grid-column-end: span 3;
}
```
### 정의
이 grid-column-end속성은 항목이 확장 될 열 수를 정의하거나 항목이 끝나는 열 행을 정의합니다

현재 IE16 버전 이상에서만 지원하는 속성입니다.

### 속성
`grid-column-end: auto|column-line|span n;`

+ auto : 항목은 한 열에 걸쳐 있습니다.	
+ span n :  항목이 포함할 열의 수를 지정합니다.
+ column-line :  항목 표시를 종료할 열을 지정합니다.
