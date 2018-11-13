---
layout: post
title: "CSS:border-image"
excerpt: ""
tags: 
  - css
  - border-image
---

```
#borderimg { 
    border-image: url(border.png) 30 round;
}
```
### CSS :border-image

border-image속성을 사용하면 요소 주위의 경계선으로 사용할 이미지를 지정할 수 있습니다.

border-image 속성은 다음에 대한 속기 속성입니다.


+ border-image-source
+ border-image-slice
+ border-image-width
+ border-image-outset
+ border-image-repeat


### 속성
`border-image: source slice width outset repeat|initial|inherit;`

+ border-image-source :보더로서 사용하는 이미지의 패스입니다.
+ border-image-slice :테두리 이미지를 분할하는 방법
+ border-image-width :테두리 이미지의 너비
+ border-image-outset :테두리 이미지 영역이 경계 상자를 넘어서 확장되는 양
+ border-image-repeat :테두리 이미지를 반복 할 것인지 둥근 것인지 스트레치 할 것인지 여부
+ initial :이 속성을 기본값으로 설정합니다.
+ inherit :부모 요소에서이 속성을 상속받습니다.

