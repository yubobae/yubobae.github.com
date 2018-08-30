---
layout: post
title: "css: backgrond"
excerpt: ""
tags: 
  - background-blend-mode
  - 배경속성
  - markup
---

### CSS : background-blend-mode

```
   div { 

    background-repeat: no-repeat, repeat;
    background-image: url("img1.gif"), url("img2.gif");
    background-blend-mode: lighten;
    
    background-blend-mode: normal|multiply|screen|overlay|darken|lighten|color-dodge|saturation|color|luminosity;
}
```

### background-blend-mode 속성

이 background-blend-mode속성은 각 배경 레이어 (색상 및 / 또는 이미지)의 혼합 모드를 정의합니다.

아래 backgrpund 관련 여러 속성을 축약한 축약속성이며,

IE8이하 버전에서는 하나의 요소에 여려 배경이미지를 지원하지 않습니다.

- normal : 이 값은 기본값입니다. 혼합 모드를 정상으로 설정합니다.
- multiply : 혼합 모드를 곱하도록 설정합니다.	
- screen :혼합 모드를 화면으로 설정합니다.	
- overlay :요소 배경의 사이즈를 지정합니다.
- darken : 혼합 모드를 어둡게 설정합니다.	
- lighten : 혼합 모드를 불이 켜지도록 설정합니다.	
- color-dodge :  혼합 모드를 불이 켜지도록 설정합니다.	
- saturation : 혼합 모드를 포화 모드로 설정합니다.	
- color	 : 혼합 모드를 컬러로 설정합니다.	
- luminosity	 :혼합 모드를 휘도로 설정합니다.
