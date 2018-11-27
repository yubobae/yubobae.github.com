---
layout: post
title: "CSS:table-layout"
excerpt: ""
tags: 
  - css
  - table-layout
---

```
table.a {
    table-layout: auto;
    width: 180px; 
}

table.b {
    table-layout: fixed;
    width: 180px; 
}
```
### CSS :table-layout

table-layout속성은 테이블 셀, 행 및 열을 배치하는 데 사용되는 알고리즘을 정의합니다.


### 속성
`table-layout: auto|fixed|initial|inherit;`

+ auto :브라우저는 자동 테이블 레이아웃 알고리즘을 사용합니다. 열 너비는 셀에서 가장 넓은 깨지지 않는 내용에 의해 설정됩니다. 내용이 레이아웃을 지정한다.
+ fixed :고정 테이블 레이아웃 알고리즘을 설정합니다. 테이블과 열 너비는 테이블과 콜의 폭 또는 셀의 첫 번째 행의 너비로 설정됩니다. 다른 행의 셀은 열 너비에 영향을 주지 않습니다. 첫 번째 행에 너비가 없을 경우, 열 너비는 셀 내부의 내용에 관계없이 테이블로 동일하게 분할됩니다.
+ initial :기본속성을 가집니다.
+ inherit :속성을 상속 받습니다.
