---
layout: post
title: "CSS:user-select "
excerpt: ""
tags: 
  - css
  - user-select
---

```
div {
    -webkit-user-select: none; /* Safari 3.1+ */
    -moz-user-select: none; /* Firefox 2+ */
    -ms-user-select: none; /* IE 10+ */
    user-select: none; /* Standard syntax */
}
```
### CSS :user-select

user-select속성은 요소의 텍스트를 선택할 수 있는지 여부를 지정합니다.

웹 브라우저에서 일부 텍스트를 두 번 누르면 해당 텍스트가 선택 / 강조 표시됩니다. 이 속성은이 문제를 방지하는 데 사용할 수 있습니다.

### 속성
`user-select: auto|none|text|all;`

+ auto :기본값. 브라우저가 허용하는 경우 텍스트를 선택할 수 있음
+ none :텍스트 선택 방지
+ text :사용자가 텍스트를 선택할 수 있음
+ all :두 번 클릭하지 않고 한 번의 클릭으로 텍스트 선택
