---
layout: post
title: "CSS:box-shadow"
excerpt: ""
tags: 
  - css
  - box-shadow
---

```
#example1 {
    box-shadow: 5px 10px;
}

#example2 {
    box-shadow: 5px 10px #888888;
}
```
### CSS :box-shadow

 box-shadow 속성은 하나 이상의 그림자를 요소에 첨부합니다.


### 속성
`box-shadow: none|h-offset v-offset blur spread color |inset|initial|inherit;`

+ none :기본값. 그림자가 표시되지 않음
+ h-offset :필수의 그림자의 수평 간격띄우기입니다. 양의 값은 상자의 오른쪽에 그림자를, 음의 값은 상자의 왼쪽에 그림자를 놓습니다.
+ v-offset :필수의 그림자의 수직 간격띄우기입니다. 양의 값은 상자 아래에 그림자를, 음의 값은 그림자를 상자 위에 놓습니다.
+ blur :선택적. 흐릿한 반지름. 숫자가 높을수록 그림자가 흐릿해질 것이다.
+ spread :선택적. 반경이 넓어 양의 값은 그림자의 크기를 증가시키고, 음의 값은 그림자의 크기를 감소시킵니다.
+ color :선택적. 그림자의 색. 기본값은 텍스트 색상입니다.
+ inset :선택적. 외부 그림자(출구)에서 내부 그림자로 그림자를 변경합니다.
+ initial :기본속성을 가집니다.
+ inherit :속성을 상속 받습니다.
