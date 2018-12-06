---
layout: post
title: "CSS:flex-shrink "
excerpt: ""
tags: 
  - css
  - flex-shrink 
---

```
/* Safari 6.1+ */
div:nth-of-type(2) {
    -webkit-flex-shrink: 3; 
} 

/* Standard syntax */
div:nth-of-type(2) {
    flex-shrink: 3;
}
```
### CSS :flex-shrink 

flex-shrink속성은 항목이 같은 컨테이너 내부의 플렉스 항목의 나머지 부분에 상대적으로 감소 할 방법을 지정합니다.

요소가 플렉스 항목이 아닌 경우이 flex-shrink속성은 아무 효과가 없습니다.

### 속성
`flex-shrink: number|initial|inherit;`

+ number : 나머지 플렉스 항목에 대해 항목이 축소되는 양을 지정하는 숫자. 기본값은 0
+ initial :	 속성을 기본값으로 설정
+ inherit :속성을 상속 받습니다.
