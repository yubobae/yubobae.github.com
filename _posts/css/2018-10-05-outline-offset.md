---
layout: post
title: "CSS:outline-offset "
excerpt: ""
tags: 
  - css
  - outline-offset
  - 원근감
  
---


### CSS : outline-offset
```
div {
    outline: 4px solid red;
    outline-offset: 15px;
}

```
### 정의
이 outline-offset 속성은 outline과 요소의 가장자리 또는 경계사이에 간격을 추가합니다.

요소와 그 outline 사이의 공간은 투명합니다.

outline은 세가지 방법으로 테두리와 다릅니다.

  + outline은 테두리 가장자리 외부의 요소 주위에 그려진 선입니다
  + 개요가 공간을 차지하지 않습니다.
  + outline은 직사각형이 아닐 수 있습니다.
  
 이 속성은 IE15버전 이상 에서만 지원합니다.
 
### 속성
`outline-offset: length|initial|inherit;`

+ length: 외곽선 모서리에서 외곽선까지의 거리입니다.기본값은 0입니다.
+ initial : 이 속성을 기본값으로 설정합니다. 
+ inherit : 상위요소에서 이속성을 상속합니다.
