---
layout: post
title: "CSS:perspective-origin "
excerpt: ""
tags: 
  - css
  - perspective
  - 원근감
  
---


### CSS : perspective-origin
```
#div1 {
    -webkit-perspective: 100px; /* Safari 4-8 */
    -webkit-perspective-origin: left; /* Safari 4-8 */
    perspective: 100px;
    perspective-origin: left;
}
```
### 정의
이 perspective-origin속성은 사용자가 3D 위치 요소를보고있는 위치를 정의합니다.

perspective-origin요소에 대한 속성을 정의 할 때 요소 자체가 아니라 효과를 얻는 요소가 CHILD입니다.

### 속성값
`perspective-origin: x-axis y-axis|initial|inherit;`
- x-axis : x축으로 배치되는 위치 정의
  + 가능한 값:left, center,  right, lenght, %
  + 기본값 : 50%
- y-axis : y축으로 배치되는 위치 정의
  + 가능한 값:top, center,  bottom, lenght, %
  + 기본값 : 50%
- initial : 기본값으로 설정합니다.
- inherit : 이 속성을 상속합니다.
