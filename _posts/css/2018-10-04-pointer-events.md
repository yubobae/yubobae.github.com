---
layout: post
title: "CSS:pointer-events "
excerpt: ""
tags: 
  - css
  - pointer-events
  - 원근감
  
---

### CSS : pointer-events
```
div.ex1 {
    pointer-events: none;
}

div.ex2 {
    pointer-events: auto;
}
```
### 정의
이 pointer-events속성은 요소가 포인터 이벤트에 반응할지 여부를 정의합니다.

IE11버전 이상에서 지원가능합니다.

### 속성값
`pointer-events: auto|none;`
- auto : hover와 같은 포인터 이벤트에 반응합니다. 기본값입니다.
- none : 요소가 포인터 이벤트에 반응하지 않습니다.
- initial : 기본값으로 설정합니다.
- inherit : 이 속성을 상속합니다.
