---
layout: post
title: "CSS:transform"
excerpt: ""
tags: 
  - css
  - transform
---

```
div.a {
    transform: rotate(20deg);
}

div.b {
    transform: skewY(20deg);
}

div.c {
    transform: scaleY(1.5);
}
```
### CSS :transform

transform속성은 2D 또는 3D 변형을 요소에 적용합니다. 

이 속성을 사용하면 요소를 회전, 크기 조절, 이동, 기울이기 등의 작업을 할 수 있습니다.

### 브라우저 지원
| property | 크롬 | IE | 파이어폭스 | 사파리 | 오페라 |
|:--------|:--------:|:--------:|:--------:|:--------:|:--------:|
| transform (2D) | 36.0, 4.0 -webkit- | 10.0 ,9.0 -ms- | 16.0, 3.5 -moz- | 9.0, 3.2 -webkit- | 23.0,15.0 -webkit-,10.5 -o- |
| transform (3D) | 36.0, 12.0 -webkit- | 12.0 | 10.0 | 9.0, 4.0 -webkit- | 23.0, 15.0 -webkit- |

### 속성
`transform: none|transform-functions|initial|inherit;`

+ none :변환이 없어야 함을 정의합니다.
+ matrix(n,n,n,n,n,n) :6개 값의 매트릭스를 사용하여 2D 변환을 정의합니다.
+ matrix3d(n,n,n,n,n,n,n,n,n,n,n,n,n,n,n,n) :16개 값의 4x4 매트릭스를 사용하여 3D 변환을 정의합니다.
+ translate(x,y) :2D 변환 정의
+ translate3d(x,y,z) :3D 변환 정의
+ translateX(x) :X축의 값만 사용하여 변환을 정의합니다.
+ translateY(y) :Y축 값만 사용하여 변환을 정의합니다.
+ translateZ(z) :Z축 값만 사용하여 3D 변환을 정의합니다.
+ scale(x,y) :2D 스케일 변환을 정의합니다.
+ scale3d(x,y,z) :3D 스케일 변환을 정의합니다.
+ scaleX(x) :X축에 대한 값을 지정하여 축척 변환을 정의합니다
+ scaleY(y) :Y축에 대한 값을 제공하여 척도 변환을 정의합니다.
+ scaleZ(z) :Z축에 대한 값을 제공하여 3D 스케일 변환을 정의합니다.
+ rotate(angle) :2D 회전을 정의합니다. 각도는 파라미터에 지정됩니다.
+ rotate3d(x,y,z,angle) :3D 회전 정의
+ rotateX(angle) :X축을 따라 3D 회전 정의
+ rotateY(angle) :Y축을 따라 3D 회전을 정의합니다.
+ rotateZ(angle) :Z축을 따라 3D 회전 정의
+ skew(x-angle,y-angle) :X축 및 Y축을 따라 2D 스큐 변환을 정의합니다.
+ skewX(angle) :X축을 따라 2D 스큐 변환을 정의합니다.
+ skewY(angle) :Y축을 따라 2D 스큐 변환을 정의합니다.
+ perspective(n) :3D 변환된 요소의 뷰 뷰를 정의합니다.
+ initial :기본속성을 가집니다.
+ inherit :속성을 상속 받습니다.
