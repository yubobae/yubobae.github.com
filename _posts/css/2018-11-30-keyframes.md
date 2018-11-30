---
layout: post
title: "CSS:keyframes"
excerpt: ""
tags: 
  - css
  - keyframes
---

```
@keyframes mymove {
    from {top: 0px;}
    to {top: 200px;}
}
```
### CSS :`@keyframes`

`@keyframes`규칙은 애니메이션 코드를 지정합니다.

애니메이션은 점차적으로 CSS 스타일 세트에서 다른 CSS 스타일 세트로 변경됩니다.

애니메이션을하는 동안 CSS 스타일 세트를 여러 번 변경할 수 있습니다.

스타일 변경이 퍼센트로 이루어 지거나 "from"과 "to"로 0 %와 100 %와 같은 키워드를 사용하여 지정하십시오. 0 %는 애니메이션의 시작 부분이고, 100 %는 애니메이션이 끝난 시점입니다.

최상의 브라우저 지원을 위해 항상 0 % 및 100 % 선택기를 정의해야합니다.

애니메이션 속성을 사용하여 애니메이션의 모양을 제어하고 애니메이션을 선택기에 바인딩합니다.

`! important `규칙은 키 프레임에서 무시됩니다

### 속성
`@keyframes animationname {keyframes-selector {css-styles;}}`

+ animationname :필수의 애니메이션의 이름을 정의합니다.
+ keyframes-selector :필수의 애니메이션 기간의 백분율입니다.[값 : 0-100%, from(0%와 동일한), to(100%와 동일)]
+ css-styles :필수의 하나 이상의 법적 CSS 스타일 속성
