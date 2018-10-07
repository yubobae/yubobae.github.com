---
layout: post
title: "CSS:grid-auto-rows "
excerpt: ""
tags: 
  - css
  - grid-auto-rows
  - 그리드
  
---


### CSS : grid-auto-rows
```
.grid-container {
  display: grid;
  grid-auto-rows: 150px;
}
```
### 정의
이 grid-auto-rows 표컨테이너의 행의 크기를 설정합니다.
이 속성은 크기가 설정되지 않은 행에만 영향을 줍니다.
현재 IE16 버전 이상에서만 지원하는 속성입니다.

### 속성
`grid-auto-columns: auto|max-content|min-content|length;`

+ auto : 행의 크기는 행에서 가장 큰 항목의 크기에 따라 결정됩니다.
+ max-content : 행에서 가장 큰 항목에 따라 달라지는 각 행의 크기를 설정합니다.
+ min-content : 행에서 가장 작은 항목에 따라 달라지는 각 행의 크기를 설정합니다.
+ length : 길이 값을 사용하여 행의 크기를 설정합니다.
