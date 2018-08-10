---
layout: post
title: "CSS: text-shadow "
excerpt: ""
tags: 
  - css
  - text
  - text-shadow
---
## CSS : text-shadow
```
div{
  text-shadow:h-shadow v-shadow blur color|none|initial|inherit;
  text-shadow:수평거리,수직거리,흐림정도,색상;
  }
```
### 텍스트 그림자 속성
'text-shadow'속성은 텍스트에 그림자를 추가합니다.
이속성은 그림자 문자열의 위치와 색상을 지정하는 4개의 값을 공백으로 구분하여 순서대로 나열합니다.

### 속성값

 -h-shadow : 필수 지정. 수평 그림자 위치를 지정합니다. 길이값(px,em 등...)
             양수 값을 지정하면 오른쪽에 그림자가 드리워지며, 음수 값은 왼쪽에 그림자가 드리워집니다.
 -v-shadow : 필수 지정. 수직 그림자 위치를 지정합니다. 길이값(px,em 등...)
             양수 값을 지정하면 위쪽에 그림자가 드리워지며, 음수 값은 아래쪽에 그림자가 드리워집니다.
 -blur : 선택지정. 그림자의 흐림 반경을 지정합니다. 길이값(px,em 등...)
         0으로 지정하면 그림자가 진하고, 숫자가 높아질수록 점점 흐릿해집니다.(양수값만 허용)
         기본으로 지정된 값은 0입니다.
 -color : 선택지정. 그림자 색을 지정합니다. ie9,firefox opera 기본값은 검은색이며, safari, 
         chrome은 color값은 미지정시 그림자가 생기지 않습니다.
 -none : 기본값으로, 그림자가 표시 되지 않습니다.
 - initial : 초기화
 - inherit : 상속
