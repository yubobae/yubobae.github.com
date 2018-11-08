---
layout: post
title: "CSS:page-break-inside"
excerpt: ""
tags: 
  - css
  - page-break-inside
  - 페이지
---
```
@media print {
    pre, blockquote {page-break-inside: avoid;}
}
```
### CSS :page-break-inside

page-break-inside 속성은 지정된 요소 내부에서 나누기를 피할 것인지 여부를 설정합니다.

절대적으로 배치 된 요소에는 이 속성을 사용할 수 없습니다. 

### 속성
`page-break-inside: auto|avoid|initial|inherit;`

+ atuo : 기본값. 자동 페이지 나누기
+ avoid :요소 내부에서 페이지 나누기 방지 (가능한 경우)
+ initial :이 속성을 기본값으로 설정합니다.
+ inherit :부모 요소에서이 속성을 상속받습니다.

