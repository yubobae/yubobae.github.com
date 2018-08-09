---
layout: post
title: "CSS: text-overflow "
excerpt: ""
tags: 
  - css
  - text
  - decoration
---
## CSS : text-overflow
```
text-overflow: clip|ellipsis|string|initial|inherit;
```
### 텍스트 넘침 효과 속성
이 'text-overflow'속성은  표시되지 않는 오버플로 된 콘텐츠를 사용자에게 알리는 방법을 지정합니다.
잘라내거나 줄임표(...)를 표시하거나 사용자 정의 문자열을 표시 할 수 있습니다.

텍스트 오버플로어에는 아래 두 속성이 모두 적용되어 있어야 합니다.
+ white-space : nowrap;
+ overflow : hidden;

### 속성값

+ clip : 텍스트를 자르고 보여줍니다. 
+ ellipsis : 자른 텍스트를 줄임표(...)로 보여줍니다.
+ string : 자른 텍스트를 지정한 문자열로 보여줍니다.
+ initial : 기본값
+ inherit : 상속값.
