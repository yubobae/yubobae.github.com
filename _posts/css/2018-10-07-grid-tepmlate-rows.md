---
layout: post
title: "CSS:grid-template-rows "
excerpt: ""
tags: 
  - css
  - grid-template-rows
  - 그리드
  
---


### CSS : grid-template-rows
```
.grid-container {
  display: grid;
  grid-template-rows: 100px 300px;
}

```
### 정의
이 grid-template-rows속성은 그리드 레이아웃에서 행의 수 (및 높이)를 지정합니다.

값은 공백으로 구분 된 목록이며 각 값은 해당 행의 높이를 지정합니다.

현재 IE16 버전 이상에서만 지원하는 속성입니다.

### 속성
`grid-template-rows: none|auto|max-content|min-content|length|initial|inherit;`

+ none : 크기가 설정되지 않았습니다. 필요한 경우 행이 작성됩니다.	
+ auto	 : 행의 크기는 컨테이너의 크기와 행에 있는 항목의 내용에 따라 결정됩니다.	
+ max-content : 행에서 가장 큰 항목에 따라 달라지는 각 행의 크기를 설정합니다.	
+ min-content : 행에서 가장 큰 항목에 따라 달라지는 각 행의 크기를 설정합니다.	
+ length : 길이 값을 사용하여 행의 크기를 설정합니다. 
