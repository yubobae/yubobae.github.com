---
layout: post
title: "CSS: background-origin "
excerpt: ""
tags: 
  - css
  - 배경속성
  - background-origin
---


### CSS : background-origin

```
    div{
         background-origin: content-box;
         
         background-origin: padding-box|border-box|content-box|initial|inherit;
      }
```
### 위치 지정 속성

이 'position' 속성은 요소에 사용되는 위치 지정 방법의 유형(정적,상대,절대,고정)을 지정합니다.

### 속성값

- padding-box : 기본값. 배경 이미지는 패딩 모서리의 왼쪽 상단 모서리에서 시작합니다.	
- border-box : 배경 이미지는 경계의 왼쪽 상단 모서리에서 시작합니다.	
- content-box : 배경 이미지는 컨텐츠의 왼쪽 상단 모서리에서 시작합니다.	
- initial : 이 속성을 기본값으로 설정합니다.
- inherit : 상위 요소에서 이 속성을 상속합니다.

