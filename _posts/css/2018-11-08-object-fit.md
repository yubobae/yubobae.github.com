---
layout: post
title: "CSS:object-fit"
excerpt: ""
tags: 
  - css
  - object-fit
---
```
img.a {
    width: 200px;
    height: 400px;
    object-fit: cover;
}
```
### CSS :object-fit

object-fit속성은 컨테이너에 맞게 <img> 또는 <video>의 크기를 조정하는 방법을 지정하는 데 사용됩니다.

이 속성은 내용을 다양한 방법으로 컨테이너에 채 웁니다.

현재 IE16 이상의 브라우저에 지원하고 있습니다.

### 속성
`object-fit: fill|contain|cover|scale-down|none|initial|inherit;`

+ fill : 기본값입니다. 대체 된 내용은 요소의 내용 상자를 채울 수있는 크기입니다. 필요한 경우 대상체가 늘어나거나 찌그러져 맞춰집니다.
+ contain : 대체 된 내용은 요소의 내용 상자에 맞춰 가로 세로 비율을 유지하도록 크기가 조절됩니다.
+ cover : 대체 된 내용은 요소의 전체 내용 상자를 채우면서 종횡비를 유지할 수있는 크기입니다. 개체가 잘려서 잘립니다.
+ none : 대체 된 콘텐츠의 크기가 조정되지 않습니다.
+ scale-down : 내용은 크기가 지정되지 않았거나 포함되어있는 것처럼 크기가 지정됩니다 (콘크리트 객체 크기가 작아짐)
+ initial :이 속성을 기본값으로 설정합니다.
+ inherit :부모 요소에서이 속성을 상속받습니다.

