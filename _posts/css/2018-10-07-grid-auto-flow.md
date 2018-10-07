---
layout: post
title: "CSS:grid-auto-flow "
excerpt: ""
tags: 
  - css
  - grid-auto-flow
  - 그리드
  
---


### CSS : grid-auto-flow
```
.grid-container {
  display: grid;
  grid-auto-flow: column;
}

```
### 정의
이 grid-auto-flow 속성은 자동 배치 된 항목이 격자에 삽입되는 방법을 제어합니다.
그리드의 모든 구멍을 채우기 위해 dense값을 추가하십시오.
 
현재 IE16 버전 이상에서만 지원하는 속성입니다.

### 속성
`grid-auto-flow: row|columns|row dense|column dense;`

+ row : 각 행을 채워 자동 배치 항목 삽입
+ column : 각 열을 채워 자동 배치 항목 삽입.
+ row dense : 각 행을 채워 자동 배치 항목 삽입 및 그리드의 구멍채우기
+ column dense : 각 열을 채워 자동 배치 항목 삽입 및 그리드의 구멍채우기.
