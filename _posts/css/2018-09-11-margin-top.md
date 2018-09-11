---
layout: post
title: "CSS:margin-top "
excerpt: ""
tags: 
  - css
  - margin-top
  - 마진
  
---


### CSS : margin-top
```
p {
    margin-top: 35px;
}
```
### 마진속성
margin-top속성은 요소의 위쪽 여백을 설정하며
음수 값이 허용됩니다.


### 여백축소

요소의 위쪽 및 아래쪽 여백은 두 개의 여백 중 가장 큰 것과 동일한 단일 여백으로 축소 됩니다.
수평(왼쪽 및 오른쪽)여백에서는 발생하지 않습니다.
###EX)
```
p.a {
    margin: 30px 0;
}

p.b {
    margin: 20px 0;
}

```
위의 예에서 <p class = "a"> 요소의 상단 및 하단 여백은 30px입니다. <p class = "b"> 요소의 상단 및 하단 여백은 20px입니다.

즉 <p class = "a">와 <p class = "b"> 사이의 수직 여백은 50px (30px + 20px) 여야합니다. 그러나 마진 붕괴로 인해 실제 마진은 30px가됩니다!

### 속성값
`margin-top: length|initial|inherit;`
- length : px, pt, cm 등의 위쪽 여백을 지정합니다. 기본값은 0입니다.음수값은 허용됩니다.
- % :포함 요소 폭의 위쪽 여백을 지정합니다.
- auto : 브라우저는 위쪽 마진을 계산합니다.
- initial : 이 속성을 기본값으로 설정합니다.
- inherit : 부모 태그의 속성값을 상속받습니다.
