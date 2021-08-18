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

> 웹페이지 구조 표시!!
> 
> 웹페이지 콘텐츠 표시!!
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

### HTML attribute
https://www.w3schools.com/html/html_attributes.asp


### HTML Heading
https://www.w3schools.com/html/html_headings.asp

### HTML Paragraph
https://www.w3schools.com/html/html_paragraphs.asp

### HTML HyperLINK
https://www.w3schools.com/html/html_links.asp

a : Anchor
href : Hypertext reference

### HTML URL
https://www.w3schools.com/html/html_urlencode.asp

인터넷 주소
- IP(Internet Protocol) 주소 : 192.168.0.1
- 도메인(Domain Name) 주소 : www.naver.com
- domain -> DNS(Domain Name Server/System) -> IP

URL(Uniform Resource Locator)
- 자세한 주소
- 도메인주소+ 해당 페이지 폴더 위치/파일 위치
- 인터넷 주소를 표현하는 가장 큰 범위
- 프로토콜 : http, https, ftp ...

### HTML File Path
https://www.w3schools.com/html/html_filepaths.asp

절대 경로
- 출발 지점에 상관없이 항상 같은 리소스를 찾을 수 있도록 표시하는 주소/경로
- 장점 : 항상 같은 자원의 위치로 찾아올 수 있음
- 단점 : 주소 표시 길이가 김
- EX) 도메인주소/파일(폴더)경로 (ex.https://~~~)

상대 경로
- 출발 지점을 기준으로 리소스 경로를 표시하는 주소/경로
- 장점 : 주쇼 표시 길이가 상대적으로 짧음
- 단점 : 기준에 따라서 표시 방식이 매번 달라짐
- EX) 파일(폴더)경로 : html/html_~~ , ../html/html_~~
- EX) 루트 상대 경로 : /html/html_~~

### HTML Table
https://www.w3schools.com/html/html_tables.asp

table generator
https://www.tablesgenerator.com/html_tables


### HTML List
https://www.w3schools.com/html/html_lists.asp

중첩 목록(Nested List) : 여러 수준(레벨)으로 구성된 목록


---상단은 텍스트를 구성하는 엘리먼트 중요한거 5가지


### HTML Images
https://www.w3schools.com/html/html_images.asp

alt : alternative


### HTML Video
https://www.w3schools.com/html/html5_video.asp

### HTML Youtube
https://www.w3schools.com/html/html_youtube.asp


--- 여기까지 콘텐츠를 꾸미는 

