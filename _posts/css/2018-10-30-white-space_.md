---
layout: post
title: "CSS:white-space"
excerpt: ""
tags: 
  - css
  - white-space
  - 폰트
  
---


### CSS : white-space
```
p.a {
    white-space: nowrap;
}

p.b {
    white-space: normal;
}

p.c {
    white-space: pre;
}
```
### white-space

이 white-space속성은 요소 내부의 스페이스와 탭, 줄바꿈, 자동줄바꿈을 어떻게 처리할지 정하는 속성입니다.

### 속성 값

`white-space: normal|nowrap|pre|pre-line|pre-wrap|initial|inherit;`

+ normal : 기본값입니다.자동으로 줄바꿈되며 콘텐츠가 요소의 너비를 넘쳤을 경우 줄바꿈됩니다.
+ no-wrap	: 줄바꿈이 실행되지 않습니다.
+ pre : pre 태그와 같은 기능을 가집니다.엔터로 줄바꿈 한것 만 적용이 되고 넘어가는 것에는 줄바꿈 하지 않습니다.
+ pre-line : 줄바꿈이 유지됩니다.
+ pre-wrap : 연속 공백은 그대로 유지됩니다. 줄 바꿈은 박스를 채우기 위해 필요한 경우에 실행합니다.
+ initial :이 속성을 기본값으로 설정합니다.
+ inherit :상위 요소에서 이 속성을 상속합니다.
