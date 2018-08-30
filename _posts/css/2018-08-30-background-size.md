---
layout: post
title: "CSS:background-size "
excerpt: ""
tags: 
  - css
  - 배경속성
  - background-size
---


### CSS : background-size
```
   #example2 {
    background: url(mountain.jpg);
    background-repeat: no-repeat;
    background-size: 300px 100px;

}
```
### 배경이미지 크기 속성

이 background-size속성은 배경 이미지의 크기를 지정합니다.

이 속성과 함께 사용할 수있는 구문에는 키워드 구문 ( "auto", "cover"및 "contains"), 하나의 값 구문 (이미지의 너비를 높이 ( "auto"가 됨), 두 값 구문 (첫 번째 값 : 이미지의 너비, 두 번째 값 : 높이) 및 여러 배경 구문 (쉼표로 구분).

### 속성값

- auto : 기본값. 배경 이미지가 원래 크기로 표시됩니다.	
- length :  배경 이미지의 너비와 높이를 설정합니다. 첫 번째 값은 폭을 설정하고 두 번째 값은 높이를 설정합니다. 값이 하나만 주어진 경우 두 번째 값은 "자동"으로 설정됩니다.
- percentage : 배경 이미지의 너비와 높이를 상위 요소의 백분율로 설정합니다. 첫 번째 값은 폭을 설정하고 두 번째 값은 높이를 설정합니다. 값이 하나만 주어진 경우 두 번째 값은 "자동"으로 설정됩니다.	
- cover : 이미지를 늘리거나 가장자리 중 하나를 약간 잘라야 하는 경우에도 전체 컨테이너를 포함하도록 배경 이미지 크기를 조정합니다.	
- contain : 이미지가 완전히 보이도록 배경 이미지 크기 조정		
- initial : 이 속성을 기본값으로 설정합니다.
- inherit : 부모 태그의 속성값을 상속받습니다.
