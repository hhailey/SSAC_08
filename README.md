# 프론트 엔드 개발


## 표기법
- 사용자가 이름을 지정하는 경우 
- 여러 단어를 사용해서 이름을 지정하는 경우


```

(일반적인 기준)
html-css : kebab case

html_css : snake case - Python

htmlCss : camel case - Javascript, JAVA, C, C++

HtmlCss : Pascal Case - Javascript, JAVA, C, C++ ( Class )

Front End(강사님 기준 : 상위 2개 / 정해진 규칙 : 하단 2개)
- HTML( class, id ) : kebab case
- File/Folder name : snake case
- Js : Camel case
- Js - Class : Pascal Case
```

## HTML

### HTML Introduction
https://www.w3schools.com/html/html_intro.asp

> 웹페이지 구조 표시
> 
> 웹페이지 콘텐츠 표시
> - 텍스트 콘탠츠
> - 멀티미디어 콘텐츠(텍스트 아닌 것들) : 이미지, 비디오, 오디오


`{backtick) : 보통 소스코드 넣는 박스 표시할때 사용


```
<tagname>CONTENTS</tagname>

**시작태그만 있는 Element : Empty element
```

### HTML element
https://www.w3schools.com/html/html_elements.asp

> 포함관계
> - 기준에 따라서 조상요소(Ancestor), 부모요소(Parent), 자식요소(Child), 자손요소(Descendant) 

```
<html>
  <body>
  <h1>Web page</h1>
  
  </body>
  
  * html : body의 부모요소, h1의 조상요소
  
  * body : html의 자식요소, h1의 부모요소
  
  * h1 : html의 자손요소, body의 자식요소
</html>
```
