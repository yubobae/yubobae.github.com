---
layout: post
title: "CSS:flex-direction"
excerpt: ""
tags: 
  - css
  - flex-direction
---

```
div {
    display: -webkit-flex; /* Safari */
    -webkit-flex-direction: row-reverse; /* Safari 6.1+ */
    display: flex;
    flex-direction: row-reverse; 
}
```
### CSS :flex-direction

이 flex-direction속성은 유연한 항목의 방향을 지정합니다.

요소가 유연한 항목이 아닌 경우이 flex-direction속성은 아무 효과가 없습니다.


### 속성
`flex-direction: row|row-reverse|column|column-reverse|initial|inherit;`

+ row :기본값. 신축성 있는 항목은 수평으로 행으로 표시된다.
+ row-reverse :행과 동일하지만 역순으로
+ column :플렉스 항목은 세로로 컬럼으로 표시된다.
+ column-reverse :열과 동일하지만 역순으로
+ initial :	 속성을 기본값으로 설정
+ inherit :속성을 상속 받습니다.
