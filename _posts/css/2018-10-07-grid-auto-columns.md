---
layout: post
title: "CSS:grid-auto-columns "
excerpt: ""
tags: 
  - css
  - grid-auto-columns
  - 그리드
  
---


### CSS : grid-auto-columns
```
.grid-container {
  display: grid;
  grid-auto-columns: 50px;
}

```
### 정의
이 grid-auto-columns 속성은 표 컨테이너의 열 크기를 설정합니다.
이 속성은 크기가 설정되지 않은 열에만 영향을 줍니다.
 
 현재 IE16 버전 이상에서만 지원하는 속성입니다.

grid-area속성은 또한 그리드 항목에 이름을 할당할 수 있습니다. 그런 다음 명명 된 그리드 항목은 grid-template-areas 속성에 의해 참조 될 수 있습니다.

### 속성
`grid-auto-columns: auto|max-content|min-content|length;`

+ auto : 열의 크기는 용기 크기에 따라 결정됩니다.
+ max-content : 열에서 가장 큰 항목에 따라 달라지는 각 열의 크기를 설정합니다.
+ min-content : 열에서 가장 큰 항목에 따라 달라지는 각 열의 크기를 설정합니다.
+ length : 길이 값을 사용하여 열의 크기를 설정합니다. 
