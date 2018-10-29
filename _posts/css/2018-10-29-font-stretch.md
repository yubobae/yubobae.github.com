---
layout: post
title: "CSS:font-stretch"
excerpt: ""
tags: 
  - css
  - font-stretch
  - 폰트
  
---


### CSS : font-stretch
```
div {
    font-stretch: 0.58;
}
```
### font-stretch

font-stretch속성을 사용하면 텍스트가 넓게 또는 좁게 만들 수 있습니다.

이 font-stretch속성은 모든 글꼴에서 작동하지 않습니다! 폰트 패밀리의 너비가 다른면이있는 경우에만 작동합니다.

font-stretch 건물 자체는 글꼴을 스트레칭하지 않습니다.

### 속성 값

`font-stretch: ultra-condensed|extra-condensed|condensed|semi-condensed|normal|semi-expanded|expanded|extra-expanded|ultra-expanded|initial|inherit;`

+ ultra-condensed	 : 그 텍스트는 최대한 좁혀진다.
+ extra-condensed : 텍스트를 축약된 텍스트보다 좁게 만들지만 초응축 텍스트만큼 좁지는 않음
+ condensed	 : 텍스트의 범위를 반값 축약보다 좁게 만들지만 추가 축약만큼 좁지는 않습니다.
+ semi-condensed :  텍스트가 일반 텍스트보다 좁지만 축약된 텍스트만큼 좁지는 않음
+ normal :기본값. 글꼴 확장 안 함
+ semi-expanded	:텍스트가 일반 텍스트보다 넓지만 확장된 텍스트만큼 넓지 않음
+ expanded :텍스트를 반 확장자보다 넓지만 추가 확장자만큼 넓지 않음
+ extra-expanded :텍스트의 폭이 확대된 것보다 넓지만 극단적으로 확장된 텍스트만큼 넓지 않음
+ ultra-expanded :텍스트가 최대한 넓어짐
+ initial :이 속성을 기본값으로 설정합니다.
+ inherit :상위 요소에서 이 속성을 상속합니다.
