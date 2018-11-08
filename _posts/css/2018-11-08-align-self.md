---
layout: post
title: "CSS:align-self"
excerpt: ""
tags: 
  - css
  - align-self
  - 페이지
---
```
#myBlueDiv {
    -webkit-align-self: center; /* Safari 7.0+ */
    align-self: center;
}
```
### CSS :align-self

align-self속성은 플렉시블 컨테이너에서 선택한 항목의 정렬을 지정합니다.

현재 IE11 이상 버전에서 지원하고 있습니다.

### 속성
`align-self: auto|stretch|center|flex-start|flex-end|baseline|initial|inherit;`

+ auto : 기본값. 요소는 부모 컨테이너의 align-items 속성을 상속 받거나 부모 컨테이너가없는 경우 "stretch"를 상속합니다.
+ stretch : 요소가 컨테이너에 맞게 배치됩니다.
+ center :요소는 컨테이너의 가운데에 배치됩니다.
+ flex-start :요소는 컨테이너의 시작 부분에 배치됩니다.
+ flex-end :요소는 컨테이너의 끝에 배치됩니다.
+ baseline :요소는 컨테이너의 기준선에 배치됩니다.
+ initial :이 속성을 기본값으로 설정합니다.
+ inherit :부모 요소에서이 속성을 상속받습니다.

