---
layout: post
title: "CSS:grid-template-columns "
excerpt: ""
tags: 
  - css
  - grid-template-columns
  - 그리드
  
---


### CSS : grid-template-columns
```
.grid-container {
  display: grid;
  grid-template-columns: auto auto auto auto;
}

```
### 정의
이 grid-template-columns속성은 그리드 레이아웃의 열 수 (및 너비)를 지정합니다.

값은 공백으로 구분 된 목록이며 각 값은 각 열의 크기를 지정합니다.

현재 IE16 버전 이상에서만 지원하는 속성입니다.

### 속성
`grid-template-columns: none|auto|max-content|min-content|length|initial|inherit;`

+ none : 기본값이 없습니다. 필요한 경우 열이 생성됩니다.	
+ auto	 : 열 크기는 컨테이너의 크기와 열에 있는 항목의 내용에 따라 결정됩니다.	
+ max-content : 열에서 가장 큰 항목에 따라 달라지는 각 열의 크기를 설정합니다.	
+ min-content : 열에서 가장 큰 항목에 따라 달라지는 각 열의 크기를 설정합니다.	
+ length : 길이 값을 사용하여 열의 크기를 설정합니다
+ initial	 :이 속성을 기본값으로 설정합니다.
+ inherit : 상위 요소에서 이 속성을 상속합니다. 
