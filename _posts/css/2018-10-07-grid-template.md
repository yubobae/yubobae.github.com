---
layout: post
title: "CSS:grid-template "
excerpt: ""
tags: 
  - css
  - grid-template
  - 그리드
  
---


### CSS : grid-template
```
.grid-container {
  display: grid;
  grid-template: 150px / auto auto auto;
}
```
### 정의
이 grid-template속성은 다음 속성에 대한 속기 속성입니다.
  + grid-template-rows
  + grid-template-columns
  + grid-template-areas

현재 IE16 버전 이상에서만 지원하는 속성입니다.

### 속성
`grid-template: none|grid-template-rows / grid-template-columns|grid-template-areas|initial|inherit;`

+ none : 기본값이 없습니다. 열 또는 행의 구체적인 크기 조정 없음	
+ grid-template rows / grid-template-columns : 열 및 행의 크기를 지정함	
+ grid-template-areas : 명명된 항목을 사용하여 그리드 레이아웃을 지정합니다.	
+ initial : 이 속성을 기본값으로 설정합니다. 
+ inherit : 상위 요소에서 이 속성을 상속합니다. 
