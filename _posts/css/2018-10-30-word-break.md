---
layout: post
title: "CSS:word-break"
excerpt: ""
tags: 
  - css
  - word-break
  - 폰트
  
---


### CSS : word-break
```
p.a {
    word-break: break-all;
}
```
### word-break

이 word-break속성은 줄 끝까지 도달 할 때 단어가 끊기는 방식을 지정합니다.

### 속성 값

`word-break: normal|break-all|keep-all|break-word|initial|inherit;`

+ normal : 기본값. 기본 줄 바꿈 규칙 사용
+ break-all: 오버플로어를 방지하기 위해 단어가 어느 문자에서나 끊길 수 있습니다.
+ keep-all  :중국어/일본/한국어(CJK) 텍스트에는 단어 구분을 사용해서는 안 됩니다. 비 CJK 텍스트 동작은 값 "normal"과 동일합니다.
+ break-word :오버플로를 방지하기 위해 임의 시점에서 단어가 파손될 수 있습니다.
+ initial :이 속성을 기본값으로 설정합니다.
+ inherit :상위 요소에서 이 속성을 상속합니다.
