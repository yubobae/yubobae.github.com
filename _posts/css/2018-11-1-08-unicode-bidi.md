---
layout: post
title: "CSS:unicode-bidi"
excerpt: ""
tags: 
  - css
  - unicode-bidi
---
```
div {
    direction: rtl;
    unicode-bidi: bidi-override;
}
```
### CSS :unicode-bidi
unicode-bidi속성은 direction 속성 과 함께 사용되어 동일한 문서에서 여러 언어를 지원하도록 텍스트를 재정의해야하는지 여부를 설정하거나 반환합니다.

### 속성
`unicode-bidi: normal|embed|bidi-override|initial|inherit;`

+ normal :요소가 추가 수준의 삽입을 열지 않습니다. 기본값입니다.
+ embed :인라인 요소의 경우이 값은 추가 수준의 포함을 엽니 다.
+ bidi-override :인라인 요소의 경우 재정의가 만들어집니다. 블록 요소의 경우 다른 블록 요소가 아닌 인라인 수준의 하위 항목에 대한 재정의가 만들어집니다.
+ isolate : 요소는 형제와 격리되어 있습니다.
+ initial :이 속성을 기본값으로 설정합니다.
+ inherit :부모 요소에서이 속성을 상속받습니다.

