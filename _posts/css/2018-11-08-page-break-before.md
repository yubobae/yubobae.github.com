---
layout: post
title: "CSS:page-break-before"
excerpt: ""
tags: 
  - css
  - page-break-before
  - 페이지
---
```
@media print {
    footer {page-break-before: always;}
}
```
### CSS :page-break-before

page-break-before 속성은 지정된 요소 앞에 페이지 나누기를 추가합니다.

빈 `<div>` 또는 절대 배치 된 요소에는이 속성을 사용할 수 없습니다.

### 속성
`page-break-after: auto|always|avoid|left|right|initial|inherit;`

+ atuo : 기본값. 자동 페이지 나누기
+ always :요소 앞에 항상 페이지 나누기를 삽입
+ avoid :요소 이전에 페이지 나누기 방지 (가능한 경우)
+ left:요소 앞에 페이지 나누기를 삽입하면 다음 페이지가 왼쪽 페이지로 서식이 지정됩니다.
+ right :요소 앞에 페이지 나누기를 삽입하면 다음 페이지가 올바른 페이지로 서식이 지정됩니다.
+ initial :이 속성을 기본값으로 설정합니다.
+ inherit :부모 요소에서이 속성을 상속받습니다.

