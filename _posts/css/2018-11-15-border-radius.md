---
layout: post
title: "CSS:border-radius"
excerpt: ""
tags: 
  - css
  - border-radius
---

```
#example1 {
    border: 2px solid red;
    border-radius: 25px;
}

#example2 {
    border: 2px solid red;
    border-radius: 50px 20px;
}
```
### CSS :border-radius

border-radius 속성은 요소의 모서리 반경을 지정합니다.

이속성을 사용하면 둥근 모서리를 추가 할 수 있으며 1~4개의 값을 가질 수 있습니다.

+ 4 가지 값 - 경계선 반경 : 15px 50px 30px 5px; 첫 번째 값은 왼쪽 위 모서리에 적용되고 두 번째 값은 오른쪽 상단 모서리에 적용되고 세 번째 값은 오른쪽 하단 모서리에 적용되고 네 번째 값은 왼쪽 하단 모서리에 적용됩니다.
+ 3 가지 값 - 경계선 반경 : 15px 50px 30px; 첫 번째 값은 왼쪽 위 모서리에 적용되고 두 번째 값은 오른쪽 상단 및 왼쪽 하단 모서리에 적용되고 세 번째 값은 오른쪽 하단 모서리에 적용됩니다.
+ 두 값 - 경계 반경 : 15px 50px; (첫 번째 값은 왼쪽 위 및 오른쪽 하단 모서리에 적용되고 두 번째 값은 오른쪽 상단 및 왼쪽 하단 모서리에 적용됩니다).
+ 하나의 값 - 경계선 반경 : 15px; (이 값은 네 모퉁이에 동일하게 반올림 됨 :

### 속성
`border-radius: 1-4 length|% / 1-4 length|%|initial|inherit;`

+ length : 모서리의 모양을 정의 할 수 있습니다. 기본값은 0. 왼쪽 테두리의 두께를 정의합니다.
+ % :모퉁이의 모양을 %로 정의합니다.
+ initial :기본속성을 가집니다.
+ inherit :속성을 상속 받습니다.
