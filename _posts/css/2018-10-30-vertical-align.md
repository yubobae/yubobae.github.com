---
layout: post
title: "CSS:vertical-align"
excerpt: ""
tags: 
  - css
  - vertical-align
  - 폰트
  
---


### CSS : vertical-align
```
img.a {
    vertical-align: baseline;
}

img.b {
    vertical-align: text-top;
}

img.c {
    vertical-align: text-bottom;
}

img.d {
    vertical-align: sub;
}

img.e {
    vertical-align: super;
}
```
### vertical-align

이 vertical-align속성은 요소의 세로 맞춤을 설정합니다.

### 속성 값

`vertical-align: baseline|length|sub|super|top|text-top|middle|bottom|text-bottom|initial|inherit;`

+ baseline :요소는 상위 기준선과 정렬됩니다. 기본값입니다.
+ length: 요소를 지정된 길이만큼 올리거나 내립니다. 음수 값은 허용됩니다.
+ % :"line-height" 속성의 백분율로 요소를 높이거나 내립니다. 음수 값은 허용됩니다.
+ sub :요소가 상위의 첨자 기준선에 맞춰져 있습니다.
+ super :요소가 상위 항목의 대문자 기준선에 정렬됩니다.
+ top :요소가 라인에서 가장 높은 요소의 상단과 정렬됩니다.
+ text-top :요소가 상위 요소의 글꼴 상단에 정렬됩니다.
+ middle :요소가 상위 요소의 중앙에 배치됩니다.
+ bottom :요소가 라인에서 가장 낮은 요소와 정렬됩니다.
+ text-bottom :요소가 상위 요소의 글꼴 하단과 정렬됩니다.
+ initial :이 속성을 기본값으로 설정합니다.
+ inherit :상위 요소에서 이 속성을 상속합니다.
