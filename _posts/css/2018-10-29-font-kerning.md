---
layout: post
title: "CSS:font-kerning"
excerpt: ""
tags: 
  - css
  - font-kerning
  - 미디아
  
---


### CSS : font-kerning
```
div { 
    font-kerning: normal;
}
```
### font-kerning

font-kerning 속성은 글꼴에 저장되어있는 커닝 정보의 사용을 제어합니다.

커닝은 글자의 간격을 정의합니다.

커닝 (kerning) 데이터가 포함되지 않은 글꼴의 경우이 속성은 눈에 띄는 효과가 없습니다.

font-kerning은 크롬32.0버전 이상에서 지원하며 webkit접두어를 사용합니다.

### 속성 값

`font-kerning: auto|normal|none;`

+ auto : 브라우저는 글꼴 연산을 적용할지 여부를 결정합니다.default값
+ normal : 글꼴 연출을 적용하도록 지정합니다.
+ none	 : 글꼴 연장이 적용되지 않도록 지정
