---
layout: post
title: "CSS:가상클래스"
excerpt: ""
tags: 
  - css
  - 가상클라스
  - 클래스
---
```
/* unvisited link */
a:link {
    color: #FF0000;
}

/* visited link */
a:visited {
    color: #00FF00;
}

/* mouse over link */
a:hover {
    color: #FF00FF;
}

/* selected link */
a:active {
    color: #0000FF;
}
```
### CSS : 가상클래스

가상 클래스는 요소의 특수 상태를 정의하는 데 사용됩니다.
예를 들어~

+ 사용자가 마우스를 올리면 요소의 스타일을 지정합니다.
+ visited  스타일과 unvisited 스타일이 다르게 적용됩니다.
+ 포커스를 얻으면 요소의 스타일을 지정합니다.

### 가상클래스 종류

+ :active :활성 링크를 선택합니다. / 	a:active
+ :checked :선택한 모든 input 요소를 선택합니다. / input:checked	
+ :disabled : 비활성화된 모든 input 요소를 선택합니다. / input:disabled
+ :empty : 자녀가 없는 모든 p 요소를 선택합니다. / p:empty
+ :enabled : 활성화된 모든 input 요소를 선택합니다. /	input:enabled
+ :first-child : 부모의 첫 번째 자식인 모든 p 요소를 선택합니다. / p:first-child
+ :first-of-type : 상위 항목의 첫 번째 p 요소인 모든 p 요소를 선택합니다. / p:first-of-type
+ :focus :	포커스가 있는 input/a 요소를 선택합니다. / input:focus
+ :hover : 마우스의 링크를 선택합니다. /	a:hover	
+ :in-range : 값이 지정된 범위 내에 있는 input 요소를 선택합니다.
+ :invalid : 잘못된 값을 가진 모든 input 요소를 선택합니다.
+ :lang(language)	 :"language"로 시작하는 Lang 속성 값으로 모든 p 요소를 선택합니다.
+ :last-child :부모의 마지막 자식인 모든 p 요소를 선택합니다.
+ :last-of-type : 상위 항목의 마지막 p 요소인 모든 p 요소를 선택합니다.
+ :link : 방문하지 않은 모든 링크를 선택합니다. / a:link
+ :not(selector) : p 요소가 아닌 모든 요소를 선택합니다. / :not(p)
+ :nth-child(n) : 부모의 n 번째 자식인 모든 p 요소를 선택합니다.
+ :nth-last-child(n): 부모의 두 번째 자식인 모든 p 요소를 마지막 자식에서 카운트하여 선택합니다.
+ :nth-last-of-type(n) : 부모의 두 번째 p 요소인 모든 p 요소를 마지막 하위 요소에서 카운트하여 선택합니다.
+ :nth-of-type(n)	:상위 항목의 두 번째 p 요소인 모든 p 요소를 선택합니다.
+ :only-of-type : 상위 요소 중 유일한 p 요소인 모든 p 요소를 선택합니다.
+ :only-child :부모의 유일한 자식인 모든 p 요소를 선택합니다.
+ :optional : "required" 특성이 없는 input 요소를 선택합니다. / input:optional
+ :out-of-range : 값이 지정된 범위를 벗어나는 input 요소를 선택합니다.
+ :read-only :"읽기 전용" 특성이 지정된 "input" 요소를 선택합니다.
+ :read-write : "읽기 전용" 특성이 없는 input 요소를 선택합니다.
+ :required : "required" 특성이 지정된 input 요소를 선택합니다. / input:required
+ :root : 문서의 루트 요소를 선택합니다.
+ :target : 현재 활성된 요소를 선택합니다(해당 앵커 이름이 포함된 URL 클릭).
+ :valid : 유효한 값을 가진 모든 input 요소를 선택합니다.
+ :visited : 방문한 모든 링크를 선택합니다.


### 기타 가상클래스 요소

+ ::after :모든 p 요소 다음에 내용 삽입
+ ::before :모든 p 요소 앞에 내용 삽입
+ ::first-letter : 모든 p 요소의 첫 번째 문자를 선택합니다.
+ ::first-line :모든 p 요소의 첫 번째 라인을 선택합니다.
+ ::selection :사용자가 선택한 요소의 일부를 선택합니다.
