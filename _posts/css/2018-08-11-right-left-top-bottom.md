---
layout: post
title: "CSS: text-decoration "
excerpt: ""
tags: 
  - css
  - text
  - decoration
---

CSS : left,right,top,bottom

    div{
     postion:apsolute
     top:px|em|%|auto;
     left:px|em|%|auto;
     right:px|em|%|auto;
     bottom:px|em|%|auto;
     
      }

위치 지정 속성

left, right, top, bottom 속성은 요소의 위치를 원하는 곳에 위치 시킬 수 있습니다.
주로 postion 속성과 함께 사용하며 position 속성 값이 static 일 때는 위치 정보가 적용되지 않습니다.

각 위치 속성에 들어가는 값의 단위 중 `auto` 는 
기본값으로 브라우저 왼쪽 끝 위치로 셋팅 됩니다. 
4가지 속성 중 반대되는 left,right 와 top,bottom을 동시에 적용하면 나중에 선언한 값이 적용됩니다.

# 속성값

- left : 문서 좌측에서 태그 좌측 좌표 거리

- right : 문서 우측에서 태그 우측 좌표 거리

- top : 문서 상단에서 태그 상단 좌표 거리

- bottom : 문서 하단에서 태그 하단 좌표 거리
