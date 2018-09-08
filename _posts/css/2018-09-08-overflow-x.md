---
layout: post
title: "CSS:overflow-x "
excerpt: ""
tags: 
  - css
  - 오버플로우
  - overflow-x
  
---


### CSS : overflow-x
```
div.ex1 {
    overflow-x: scroll;
}

div.ex2 {
    overflow-x: hidden;
}

div.ex3 {
    overflow-x: auto;
}

div.ex4 {
    overflow-x: visible;
}
```
### 오버플로우x 설정

 overflow-x속성은왼쪽 및 오른쪽 가장자리에서 오버플로 될 때 콘텐츠를 클립하거나, 
 스크롤 막대를 추가하거나, 블록 수준 요소의 오버플로 콘텐츠를 표시할지 여부를 지정합니다.

### 속성값
`overflow-x: visible|hidden|scroll|auto|initial|inherit;`
- visible :내용은 잘리지 않으며 왼쪽 및 오른쪽 가장자리 밖으로 렌더링될 수 있습니다. 기본값입니다.	
- hidden :숨겨진 오버플로가 잘리고 스크롤이 생기지 않습니다.
- scroll :스크롤 컨텐츠가 클리핑되고 스크롤이 생깁니다.
- auto :자동로 인해 오버플로우 박스에 대한 스크롤이 제공되어야 합니다.	
- initial : 이 속성을 기본값으로 설정합니다.
- inherit : 부모 태그의 속성값을 상속받습니다.
