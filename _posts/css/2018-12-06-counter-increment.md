---
layout: post
title: "CSS:counter-increment "
excerpt: ""
tags: 
  - css
  - counter-increment
---

```
body {
    /* Set "my-sec-counter" to 0 */
    counter-reset: my-sec-counter;
}

h2::before {
    /* Increment "my-sec-counter" by 1 */
    counter-increment: my-sec-counter;
    content: "Section " counter(my-sec-counter) ". ";
} 
```
### CSS :counter-increment

counter-increment속성은 하나 이상의 CSS 카운터 값을 늘리거나 줄입니다.

### 속성
`counter-increment: none|id|initial|inherit;`

+ none :기본값. 카운터가 증가하지 않음
+ id number :D는 증가할 카운터를 정의한다. 숫자는 선택기가 발생할 때마다 카운터가 증가하는 양을 설정한다. 기본 증가량은 1이다. 음수 값은 허용된다. ID가 카운터 재설정에 의해 초기화되지 않은 카운터를 참조하는 경우 기본 초기값은 0임
+ initial :	 속성을 기본값으로 설정
+ inherit :속성을 상속 받습니다.
