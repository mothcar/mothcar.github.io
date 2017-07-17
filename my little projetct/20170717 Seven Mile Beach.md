## Start
layout  
> 최초로 `layout.pug`를 불러오기위해
```pug
extends node_modules/pug-bootstrap/layouts/starter

append body
	.container
    		h1 Seven Mile Beach
```
로 했으나 Error!  
이유는 path 문제와  
그다음은 화면에서 add 개념임  
그래서 다음과 같이 수정
```pug
extends ../node_modules/pug-bootstrap/layouts/starter

block body
	.container
		h1 Seven Mile Beach
```

## main.pug 만들기
```pug
extends layout

block footer
	h1 footer
```
Error : there is no footer block  
> 그래서 `node_modules/pug-boostrap/_boostrap.pug`에  
```pug
		block footer
```
추가

