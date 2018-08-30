---
layout: post
title: "CSS: background-position "
excerpt: ""
tags: 
  - css
  - 배경속성
  - background-position
---


### CSS : background-position

    div{
      background-image: url('w3css.gif');
      background-repeat: no-repeat;
      background-attachment: fixed;
      background-position: center; 
      
      background-position: value;
      }

### 배경 위치 속성

이 background-position속성은 배경 이미지의 시작 위치를 설정합니다.

기본적으로 배경 이미지 는 요소의 왼쪽 위 모서리에 배치되고 세로 및 가로로 반복됩니다.

### 속성값

- left top,

  left center,
  
  left bottom,
  
  right top,
  
  right center,
  
  right bottom,
  
  center top,
  
  center center,
  
  center bottom : 바닥	키워드를 하나만 지정하면 다른 값은 "중심"이 됩니다.
- x% y% : 첫 번째 값은 수평 위치이고 두 번째 값은 수직입니다. 왼쪽 상단 모서리는 0% 0%입니다. 오른쪽 하단 모서리는 100%입니다. 하나의 값만 지정하면 다른 값은 50%가 됩니다. 기본값은 0% 0%입니다.	
- value : 	첫 번째 값은 수평 위치이고 두 번째 값은 수직입니다. 왼쪽 위 모서리는 0입니다. 단위는 픽셀(0px 0px) 또는 다른 모든 CSS 단위일 수 있습니다. 하나의 값만 지정하면 다른 값은 50%가 됩니다. %와 위치를 혼합할 수 있습니다.	
-fixed : 스크롤과 상관없이 항상 문서 최 좌측상단을 기준으로 좌표를 고정합니다.
-initial : 이 속성을 기본값으로 설정합니다
-inherit : 상위 요소에서 이 속성을 상속합니다. 
   


