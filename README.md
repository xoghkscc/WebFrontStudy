# 1.HTML
### 1.1_HTML이란
  * HyperText Markup Language
  * 웹 페이지의 생김새를 표현하는 마크업 언어
  * 마크업 언어: 여는 태그와 닫는 태그로 영역을 구분하는 언어
```
head : HTML의 머리부분, 현재 페이지의 설정을 정의하는 곳
body : 현재 웹 페이지의 화면에 보여지는 내용을 채우는 곳
title : 현재 웹 페이지의 제목, 웹 브라우저의 탭 이름으로 사용된다.
```
### 1.2_제목과 문단
  * 줄이 자동으로 바뀌는 태그 : 블록 요소
  * 줄이 바뀌지 않는 태그 : 인라인 요소

```
<p> : 블록 요소
<b> :인라인 요소
```
### 1.3_요소
   *	여는 태그와 닫는 태그와 그 사이의 내용을 모두 통틀어서 HTML요소라고 부른다
   *	br, hr처럼 닫는 태그를 생략 가능한 태그들도 있다
```
&lt; : 여는 태그
&gt; : 닫는 태그
i 태그 : 기울인 글꼴
b 태그 : 굵은 글씨
```
### 1.4_속성
   *	모든 요소는 속성을 가질 수 있다
   *	속성은 해당 요소의 여는 태그에 정의해야 한다
   *	속성을 통해 해당 요소의 추가적인 정보를 묘사할 수 있다
   *	대부분의 속성은 속성 이름과 속성 값이 짝을 이룬다
### 1.5_링크
   *	외부 페이지에 링크 걸기
```C
<a href="http://naver.com">네이버로</a>
<a href="http://comic.naver.com">네이버 웹툰으로</a>
```
* 페이지의 특정 부분으로 링크 걸기
  * 페이지 내부 원하는 요소의 ID속성을 이용하면 그 요소가 보이는 화면으로 링크를 걸 수 있다	
```C
<a href="#chap01">챕터1</a> <br>
```
