---
layout: post
title: "CSS:flex-basis"
excerpt: ""
tags: 
  - css
  - flex-basis
---

```
div:nth-of-type(2) {
    -webkit-flex-basis: 100px; /* Safari 6.1+ */
    flex-basis: 100px;
}
```
### CSS :float-basis

flex-basis 속성은 유연한 항목의 초기 길이를 지정합니다.

요소가 유연한 항목이 아닌 경우이 flex-basis속성은 아무 효과가 없습니다.

### 속성
`flex-basis: number|auto|initial|inherit;`

+ number :유연한 항목의 초기 길이를 지정하는 길이 단위
+ auto :기본값. 길이는 유연한 품목의 길이와 같다. 품목의 길이가 지정되지 않은 경우, 길이는 그 내용에 따른다.
+ initial :	 속성을 기본값으로 설정
+ inherit :속성을 상속 받습니다.
