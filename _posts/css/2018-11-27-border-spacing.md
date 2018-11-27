---
layout: post
title: "CSS:border-spacing"
excerpt: ""
tags: 
  - css
  - border-spacing
---

```
#table1 {
    border-collapse: separate;
    border-spacing: 15px;
}

#table2 {
    border-collapse: separate;
    border-spacing: 15px 50px;
}
```
### CSS :border-spacing

border-spacing 속성은 인접한 셀의 경계 사이의 거리를 설정합니다.


### 속성
border-spacing: length|initial|inherit;`

+ length : px, cm 등의 인접 셀 경계 사이의 거리를 지정합니다. 음수 값은 허용되지 않습니다.
 - 한 값이 지정된 경우 셀 사이의 수평 및 수직 간격을 모두 정의합니다.
 - 두 값이 지정된 경우 첫 번째 값은 수평 간격을 설정하고 두 번째 값은 수직 간격을 설정합니다.
+ % :모퉁이의 모양을 %로 정의합니다.
+ initial :기본속성을 가집니다.
+ inherit :속성을 상속 받습니다.
