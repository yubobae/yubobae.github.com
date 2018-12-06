---
layout: post
title: "CSS:column-rule "
excerpt: ""
tags: 
  - css
  - column-rule 
---

```
div {
    -webkit-column-rule: 4px double #ff00ff; /* Chrome, Safari, Opera */
    -moz-column-rule: 4px double #ff00ff; /* Firefox */
    column-rule: 4px double #ff00ff;
}
```
### CSS :column-rule 

column-rule 속성은 열 사이의 규칙의 너비, 스타일, 색상을 설정합니다.

이 속성은 다음에 대한 속기 속성입니다.

+ column-rule-width
+ column-rule-style (필수)
+ column-rule-color 

### 속성
`column-rule: column-rule-width column-rule-style column-rule-color|initial|inherit;`

+ column-rule-width :열 사이의 규칙 너비를 설정하십시오. 기본값: medium
+ column-rule-style :열 사이에 규칙의 스타일을 설정하십시오. 기본값은 none
+ column-rule-color :열 사이의 규칙 색상을 설정하십시오. 기본값은 요소의 색상
+ initial :	 속성을 기본값으로 설정
+ inherit :속성을 상속 받습니다.
