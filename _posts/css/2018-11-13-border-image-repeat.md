---
layout: post
title: "CSS:border-image-repeat"
excerpt: ""
tags: 
  - css
  - border-image-repeat
---

```
#borderimg {
   #borderimg {
    border-image-source: url(border.png);
    border-image-repeat: repeat;
}
}
```
### CSS :border-image-outset

이 border-image-repeat속성은 테두리 이미지를 반복하거나 반올림하거나 늘릴 지 여부를 지정합니다.

### 속성
`order-image-repeat: stretch|repeat|round|initial|inherit;`

+ stretch:기본값. 영역을 채우기 위해 이미지가 늘어납니다.
+ repeat:이미지가 바둑판 식으로 배열되어 반복됩니다.
+ round:이미지가 바둑판 식으로 배열되어 반복됩니다. 타일의 전체 개수로 영역을 채우지 않으면 이미지 크기가 맞게 조정됩니다.
+ space:이미지가 바둑판 식으로 배열되어 반복됩니다. 타일의 전체 개수로 영역을 채우지 않으면 여분의 공간이 타일 주위에 분산됩니다.
+ initial :이 속성을 기본값으로 설정합니다.
+ inherit :부모 요소에서이 속성을 상속받습니다.

