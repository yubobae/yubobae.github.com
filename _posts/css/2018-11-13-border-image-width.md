---
layout: post
title: "CSS:border-image-width"
excerpt: ""
tags: 
  - css
  - border-image-width
---

```
#borderimg {
    border-image-source: url(border.png);
    border-image-width: 10px;
}
```
### CSS :border-image-width

이 border-image-width속성은 테두리 이미지의 너비를 지정합니다.

### 속성
`border-image-width: number|%|auto|initial|inherit;`

border-image-width 속성은 1 ~ 4 개의 값 (위, 오른쪽, 아래, 왼쪽 측면)에서 걸릴 수 있습니다. 네 번째 값이 생략되면 두 번째 값과 같습니다. 

세 번째도 생략되면 첫 번째 것과 동일합니다. 두 번째도 생략 된 경우 첫 번째 것과 동일합니다.

+ length:
테두리로 사용되는 이미지의 경로 테두리 너비의 크기를 지정하는 길이 단위 (px)
+ number: 기본값 1. 대응하는 border-width의 배수를 나타냅니다.
+ %: 경계 이미지 영역의 크기를 참조하십시오 : 수평 오프셋의 영역 폭, 수직 오프셋의 높이
+ auto: 지정된 경우 폭은 해당 이미지 슬라이스의 본질적인 너비 또는 높이입니다
+ initial :이 속성을 기본값으로 설정합니다.
+ inherit :부모 요소에서이 속성을 상속받습니다.

