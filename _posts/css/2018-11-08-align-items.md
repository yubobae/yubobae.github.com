---
layout: post
title: "CSS:align-items"
excerpt: ""
tags: 
  - css
  - align-items
  - 페이지
---
```
div {
    display: -webkit-flex; /* Safari */
    -webkit-align-items: center; /* Safari 7.0+ */
    display: flex;
    align-items: center;
}
```
### CSS :align-items

align-items속성은 유연한 컨테이너 내부의 항목에 대한 기본 정렬을 지정합니다.

현재 IE11 이상 버전에서 지원하고 있습니다.

### 속성
`align-items: stretch|center|flex-start|flex-end|baseline|initial|inherit;`

+ stretch : 기본값. 컨테이너에 맞게 항목이 늘어납니다.
+ center :항목은 컨테이너의 가운데에 배치됩니다.
+ flex-start :항목은 컨테이너 시작 부분에 배치됩니다.
+ flex-end :항목은 컨테이너의 끝에 배치됩니다.
+ baseline :항목은 컨테이너의 기준선에 배치됩니다.
+ initial :이 속성을 기본값으로 설정합니다.
+ inherit :부모 요소에서이 속성을 상속받습니다.

