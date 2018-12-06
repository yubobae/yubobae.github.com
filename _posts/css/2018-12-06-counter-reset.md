---
layout: post
title: "CSS:counter-reset "
excerpt: ""
tags: 
  - css
  - counter-reset
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
### CSS :counter-reset

counter-reset속성을 만들거나 하나 개 이상의 CSS 카운터를 재설정합니다.

### 속성
`counter-reset: none|name number|initial|inherit;`

+ none :기본값. 카운터가 재설정되지 않음
+ id number :ID는 재설정할 카운터를 정의한다. 숫자는 셀렉터가 발생할 때마다 카운터가 재설정되는 값을 설정한다. 기본 번호 값은 0임
+ initial :	 속성을 기본값으로 설정
+ inherit :속성을 상속 받습니다.
