---
layout: post
title: "CSS:background-repeat "
excerpt: ""
tags: 
  - css
  - 배경속성
  - background-repeat
---


### CSS : background-repeat
```
   body {
    background-image: url("paper.gif");
    background-repeat: repeat-y;
    
    background-repeat: repeat|repeat-x|repeat-y|no-repeat|initial|inherit;
}
```
### 배경이미지 반복 속성

이 background-repeat속성은 배경 이미지가 반복되는 경우 / 방법을 설정합니다.

기본적으로 배경 이미지 는 세로 및 가로로 반복됩니다.

배경 이미지는 background-position 속성 에 따라 배치됩니다 . 배경 위치를 지정하지 않으면 이미지는 항상 요소의 왼쪽 상단에 배치됩니다.

### 속성값

- repeat : 이미지는 수직 및 수평 방향으로 반복됩니다. 기본값입니다.	
- repeat-x : 이미지는 수평으로만 반복됩니다.	
- repeat-y : 이미지는 수직으로만 반복됩니다.	
- no-repeat : 이미지는 반복되지 않습니다. 이미지는 한 번만 표시됩니다.	
- space : 이미지를 양방향으로 배열합니다.첫 번째 및 마지막 이미지가 요소의 양쪽에 고정되고 공백이 이미지 간에 고르게 분산됩니다.	
- round : 이미지를 양방향으로 배열합니다.이미지는 공간을 채우기 위해 반복되고 스퀴즈되거나 늘어납니다(간격 없음).	
- initial : 이 속성을 기본값으로 설정합니다.
- inherit : 부모 태그의 속성값을 상속받습니다.
