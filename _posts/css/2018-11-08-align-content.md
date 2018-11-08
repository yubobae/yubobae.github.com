---
layout: post
title: "CSS:align-content"
excerpt: ""
tags: 
  - css
  - align-content
  - 페이지
---
```
div {
    width: 70px;
    height: 300px;
    border: 1px solid #c3c3c3;
    display: -webkit-flex;
    display: flex;
    -webkit-flex-wrap: wrap;
    flex-wrap: wrap;
    -webkit-align-content: center;
    align-content: center;
}
```
### CSS :align-content
align-content속성은 flex-wrap속성의 동작을 수정합니다. 이는 align-items와 유사 하지만 플렉스 항목을 정렬하는 대신 플렉스 선을 정렬합니다.

이 속성을 적용하려면 여러 줄의 항목이 있어야 합니다.

현재 IE11 이상 버전에서 지원하고 있습니다.

### 속성
`align-content: stretch|center|flex-start|flex-end|space-between|space-around|initial|inherit;`

+ stretch : 기본값. 줄이 늘어나 나머지 공간을 차지합니다.
+ center :라인은 플렉스 컨테이너의 중심을 향해 포장됩니다.
+ flex-start :라인은 플렉스 컨테이너의 시작 부분을 향해 포장됩니다.
+ flex-end :라인은 플렉스 컨테이너의 끝쪽으로 포장됩니다.
+ spase-between :라인은 플렉스 컨테이너에 고르게 분포되어 있습니다.
+ space-around :라인은 플렉스 컨테이너에 고르게 분포되어 있으며 양쪽 끝에 절반 크기의 공백이 있습니다
+ initial :이 속성을 기본값으로 설정합니다.
+ inherit :부모 요소에서이 속성을 상속받습니다.

