---
layout: post
title: "CSS:perspective "
excerpt: ""
tags: 
  - css
  - perspective
  - 원근감
  
---


### CSS : perspective
```
#div1 {
    -webkit-perspective: 100px; /* Safari 4-8 */
    perspective: 100px;
}
```
### 정의
perspective속성은 3D배치 요소에 일부 원근감을 부여하는 데 사용됩니다.
perspective속성은 객체가 사용자로부터 얼마나 멀리 떨어져 있는지 정의합니다.
따라서 값이 낮을수록 높은 값보다 집중적인 3D효과가 발생합니다.

perspective요소에 대한 속성을 정의 할때 요소 자체가 아니라 투시도 뷰를 가져오는것은 자식요소입니다.

### 속성값
`perspective: length|none;`
- length : 요소가 뷰에서 배치되는 거리. 
- none : 기본값이 없습니다.0과 같습니다.
- initial : 이 속성을 기본값으로 설정합니다.
- inherit : 부모 태그의 속성값을 상속받습니다.
