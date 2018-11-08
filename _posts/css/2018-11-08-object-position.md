---
layout: post
title: "CSS:object-position"
excerpt: ""
tags: 
  - css
  - object-position
---
```
img.a {
    width: 200px;
    height: 400px;
    object-fit: none;
    object-position: 5px 10%;
    border: 5px solid red;
}
```
### CSS :object-position

object-position속성은 물체 맞춤과 함께 `<img>` 또는 `<video>`가 "자신의 콘텐츠 상자"안에 x / y 좌표로 배치되어야하는 방법을 지정하는 데 사용됩니다.

현재 IE16 이상의 브라우저에 지원하고 있습니다.

### 속성
`object-fit: position|initial|inherit;`

+ position : 내용 상자 안의 이미지 또는 비디오의 위치를 지정합니다. 첫 번째 값은 x-asis를 제어하고 두 번째 값은 y- 축을 제어합니다. 문자열 (왼쪽, 가운데 또는 오른쪽) 또는 숫자 (px 또는 %)가 될 수 있습니다. 음수 값은 허용됩니다.
+ initial :이 속성을 기본값으로 설정합니다.
+ inherit :부모 요소에서이 속성을 상속받습니다.

