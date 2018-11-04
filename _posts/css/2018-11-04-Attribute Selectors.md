---
layout: post
title: "CSS:가상클래스"
excerpt: ""
tags: 
  - css
  - 속성선택자
  - 클래스
---
```
a[target] {
    background-color: yellow;
}
a[target="_blank"] { 
    background-color: yellow;
}
[title~="flower"] {
    border: 5px solid yellow;
}
[class|="top"] {
    background: yellow;
}
[class^="top"] {
    background: yellow;
}
[class$="test"] {
    background: yellow;
}
[class*="te"] {
    background: yellow;
}
```
### CSS : 속성선택자

특정 속성 또는 속성 값을 갖는 HTML 요소를 스타일화할 수 있습니다.

#### 1.`[속성]` 선택자

특정 속성을 가진 요소를 선택하는 데 사용된다.

`a[target] {}`

#### 2. `[속성 = 값]` 선택자

특정 속성 및 값을 가진 요소를 선택하는 데 사용된다.

`a[target="_blank"] {}`

#### 3. `[속성 ~ = "값"]` 선택자

특정 단어를 포함하는 속성 값을 가진 요소를 선택하는 데 사용된다.

`[title~="flower"] {}`

#### 4.`[속성 | = "값"] `선택자

지정된 값으로 시작하는 지정된 속성 요소를 선택하는 데 사용된다.

`[class|="top"] {}`

#### 5.  `[속성^ = "값"]`선택자 

속성 값이 지정된 값으로 시작 요소를 선택하는 데 사용된다.

`[class^="top"] {}`

#### 6. `[속성 $ = "값"] `선택자

선택기 속성 값이 지정된 값으로 끝나는 요소를 선택하는 데 사용된다.

`[class$="test"] {}`

#### 7.` [속성 * = "값"] `선택자

속성 값이 소정 값을 포함하는 요소를 선택하는 데 사용된다.

`[class*="te"] {}`

