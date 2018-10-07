---
layout: post
title: "CSS:grid-column "
excerpt: ""
tags: 
  - css
  - grid-column
  - 그리드
  
---


### CSS : grid-column
```
.item1 {
  grid-column: 1 / span 2;
}
```
### 정의
이 grid-column속성은 모눈 레이아웃에서 grid 항목의 크기와 위치를 지정하며 다음 속성에 대한 속기 속성입니다.

+ grid-column-start
+ grid-column-end

현재 IE16 버전 이상에서만 지원하는 속성입니다.

### 속성
`grid-column: grid-column-start / grid-column-end;`

+ grid-column-start : 항목을 표시할 열을 지정합니다.
+ grid-column-end : 항목 표시를 중지할 열 줄 또는 포함할 열 수를 지정합니다.
