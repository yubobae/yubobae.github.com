---
layout: post
title: "CSS:grid-template-areas "
excerpt: ""
tags: 
  - css
  - grid-template-areas
  - 그리드
  
---


### CSS : grid-template-areas
```
.item1 {
  grid-area: myArea;
}
.grid-container {
  display: grid;
  grid-template-areas: "myArea myArea . . .";
}
```
### 정의
이 grid-template-areas속성은 그리드 레이아웃 내의 영역을 지정합니다.

그리드 영역 속성 을 사용하여 그리드 항목 의 이름을 지정한 다음 grid-template-areas 속성 의 이름을 참조 할 수 있습니다.

현재 IE16 버전 이상에서만 지원하는 속성입니다.

### 속성
`grid-template-areas: none|itemnames;`

+ none : 기본값이 없습니다. 지정된 그리드 영역 없음	
+ itemnames	 : 각 열과 행이 표시되는 방법을 지정하는 시퀀스


