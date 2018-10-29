---
layout: post
title: "CSS:font-family"
excerpt: ""
tags: 
  - css
  - font-family
  - 미디아
  
---


### CSS : font-family
```
p.a {
    font-family: "Times New Roman", Times, serif;
}

p.b {
    font-family: Arial, Helvetica, sans-serif;
}
```
### font-family

이 font-family속성은 요소의 글꼴을 지정합니다.

이 font-family속성은 "대체 시스템"으로 여러 글꼴 이름을 포함 할 수 있습니다. 브라우저가 첫 번째 글꼴을 지원하지 않으면 다음 글꼴을 시도합니다.

글꼴 패밀리 이름에는 두 가지 유형이 있습니다.

family-name - "times", "courier", "arial"등과 같은 폰트 패밀리의 이름.

generic-family - "serif", "sans-serif", "필기체", "fantasy", "monospace"와 같은 일반 제품군 의 이름입니다.

다른 글꼴을 사용할 수없는 경우 브라우저에서 일반 글꼴로 비슷한 글꼴을 선택하도록 원하는 글꼴로 시작하고 항상 일반 글꼴로 끝냅니다.

글꼴 이름에 공백이 있으면 따옴표로 묶어야합니다. HTML의 "style"속성을 사용할 때는 작은 따옴표를 사용해야합니다.

### 속성 값
`font-family: family-name|generic-family|initial|inherit;`

+ family-name generic-family : 글꼴 패밀리 이름 및/또는 일반 패밀리 이름의 우선 순위 목록
+ initial : 이 속성을 기본값으로 설정합니다. 
+ inherit : 상위 요소에서 이 속성을 상속합니다.
