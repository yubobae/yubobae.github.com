---
layout: post
title: "CSS:border-color "
excerpt: ""
tags: 
  - css
  - 태두리속성
  - border-color
  
---


### CSS : border-color
```
div {border-color: coral;}
```
### 태두리색상 설정

 border-color속성은 요소의 네 가지 테두리 색을 설정합니다. 이 속성은 1-4 개의 값을 가질 수 있습니다.

* border-color 속성에 네 개의 값이있는 경우 :

  - 테두리 색상 : 빨강 녹색 파랑 분홍색;
    + 위쪽 테두리가 빨간색입니다.
    + 오른쪽 테두리는 녹색입니다.
    + 아래쪽 테두리는 파란색
    + 왼쪽 테두리는 핑크색이다.

* border-color 속성에 세 개의 값이있는 경우 :

  - 테두리 색 : 빨강 녹색 파랑;
    + 위쪽 테두리가 빨간색입니다.
    + 오른쪽 및 왼쪽 테두리는 녹색입니다.
    + 아래쪽 테두리는 파란색

* border-color 속성에 두 개의 값이있는 경우 :

  - 테두리 색 : 빨간색 녹색;
    + 상단 및 하단 테두리가 빨간색입니다.
    + 오른쪽 및 왼쪽 테두리는 녹색입니다.

* border-color 속성에 하나의 값이있는 경우 :

  - 국경 색깔 : 빨강;
    + 네 테두리 모두 빨간색
    
항상 속성 앞에 border-style 또는 border-bottom-style 속성을 선언하십시오 border-bottom-color .

색상을 변경하려면 요소에 테두리가 있어야합니다.

### 속성값

- color :색상을 지정합니다. 가능한 색상 값의 전체 목록은 CSS 색상 값을 참조하십시오. 기본 색상은 요소의 색입니다.	
- transparent :테두리 색이 투명해야 함을 지정합니다.	
- initial : 이 속성을 기본값으로 설정합니다.
- inherit : 부모 태그의 속성값을 상속받습니다.
