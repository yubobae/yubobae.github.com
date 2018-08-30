---
layout: post
title: "css: background-clip"
excerpt: ""
tags: 
  - background
  - 배경속성
  - markup
---

### CSS : background-clip
```
    iv {
    border: 10px dotted black;
    padding: 15px;
    background: lightblue;
    background-clip: padding-box;
    
    
    background-clip: border-box|padding-box|content-box|initial|inherit;
}
```
### background-clip 속성

이 background-clip속성은 배경 (색상 또는 이미지)이 요소 내에서 연장되어야하는 거리를 정의합니다.


- border-box : 기본값. 
- padding-box :  배경이 테두리의 안쪽 가장자리로 확장됩니다.	
- content-box :요소 배경의 위치를 지정합니다.
- background-size :상자 배경이 내용 상자의 가장자리로 확장됩니다.	
- initial	: 이 속성을 기본값으로 설정합니다. 
- inherit : 상위 요소에서 이 속성을 상속합니다. 
