---
layout: post
title: "CSS:border-image-slice"
excerpt: ""
tags: 
  - css
  - border-image-slice
---

```
#borderimg { 
    border-image-slice: 30%;
}
```
### CSS :border-image-slice

이 border-image-slice속성은 border-image-source로 지정된 이미지를 슬라이스하는 방법을 지정합니다 .

이미지는 항상 네 개의 모서리, 네 개의 모서리 및 중간의 9 개의 섹션으로 슬라이스됩니다.

fill 키워드가 설정되어 있지 않으면 "중간"부분이 완전히 투명하게 처리됩니다.

### 속성
`border-image-slice: number|%|fill|initial|inherit;`

+ number:숫자는 래스터 이미지의 픽셀 또는 벡터 이미지의 좌표를 나타냅니다.
+ %:백분율은 이미지의 높이 또는 너비에 상대적입니다.
+ fill:이미지의 중간 부분이 표시되도록합니다.
+ initial :이 속성을 기본값으로 설정합니다.
+ inherit :부모 요소에서이 속성을 상속받습니다.

