---
layout: post
title: "CSS:transition-property"
excerpt: ""
tags: 
  - css
  - transition-property
---

```
div {
    transition-property: width;
}

div:hover {
    width: 300px;
}
```
### CSS :transition-property

transition-property속성은 전환 효과가 적용되는 CSS 속성의 이름을 지정합니다 (지정된 CSS 속성이 변경 될 때 전환 효과가 시작됩니다).

### 브라우저 지원
| property | 크롬 | IE | 파이어폭스 | 사파리 | 오페라 |
|:--------|:--------:|:--------:|:--------:|:--------:|:--------:|
| transition | 26.0, 4.0 -webkit- | 10.0 | 16.0, 4.0 -moz- | 6.1, 3.1 -webkit- | 12.1,10.5 -o- |

### 속성
`transition-property: none|all|property|initial|inherit;`

+ none :어떤 속성도 전환 효과를 얻지 못합니다.
+ all :기본값. 모든 속성이 전환 효과를 가져옵니다.
+ property :전환 효과가 있는 CSS 속성 이름의 쉼표로 구분된 목록을 정의합니다.
+ initial :기본속성을 가집니다.
+ inherit :속성을 상속 받습니다.
