---
layout: post
title: "CSS:column-fill  "
excerpt: ""
tags: 
  - css
  - column-fill 
---

```
.newspaper1 {
    -moz-column-fill: auto; /* Firefox */
    column-fill: auto;
}

.newspaper2 {
    -moz-column-fill: balance; /* Firefox */
    column-fill: balance;
}
```
### CSS :column-fill 

column-fill속성은 열을 채우는 방법을 지정합니다.

다중 열 요소에 높이를 추가하면 내용이 열을 채우는 방식을 제어 할 수 있습니다.

내용은 균형을 이루거나 순차적으로 채울 수 있습니다.

### 속성
`column-fill: balance|auto|initial|inherit;`

+ auto : 높이가 될 때까지 각 열을 채우고 내용물이 부족해질 때까지(따라서 이 값이 모든 열을 반드시 채우고 균일하게 채우는 것은 아님)
+ balance :기본값. 각 열에 거의 동일한 양의 콘텐츠를 채워 넣지만, 기둥이 높이보다 커지는 것을 허용하지 않는다(따라서, 브라우저가 콘텐츠를 수평으로 분포할 때 기둥이 높이보다 짧을 수 있음).
+ initial :	 속성을 기본값으로 설정
+ inherit :속성을 상속 받습니다.
