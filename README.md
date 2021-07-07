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
### 1.6_이미지
   *	src 속성 : 출력하고자 하는 이미지의 경로
   *	alt 속성 : 해당이미지의 설명(이미지 출력 실패시 대신 출력됨)
   *	width 속성 : 해당 이미지의 너비 조절
   *	height 속성 : 해당 이미지의 높이 조절
```C
<img src="../assets/image/dog1.jpg" alt="강아지1">
```
### 1.7_테이블
   *	table : 표의 범위를 설정하는 태그
   *	tr : table row, 표에 한 줄을 추가하는 태그
   *	h : table header, 해당 줄에 제목 칸을 추가하는 태그(이때 글씨는 자동 굵어지고 가운데정렬로 됨)
   *	colspan 속성 : 열(가로)를 합치는 속성
   *	td : table data, 해당 줄에 데이터 칸을 추가하는 태그
   *	rowspan 속성 : row(행, 세로)를 합치는 속성
### 1.8_목록
   *	ul : unordered list : 순서 없는 리스트
   *	li : list item
   *	ol : ordered list : 순서 있는 리스트
   *	dl : 설명이 있는 리스트(dd : 들여쓰기 기능, dt : 설명할 텍스트)
### 1.9_입력
#### INPUT태그를 이용해 사용자로부터 다양한 입력을 받을 수 있다.
   *	Text : 일반적인 텍스트를 입력받는 칸
   *	Password : 텍스트를 가려주는 입력칸
   *	Radio : 여러가지 중 하나만 선택할 수 있는 버튼(이때 name 속성으로 카테고리를 지정해줘야 함 또한 label 속성을 통해 텍스트를 클릭해도 해당 개체가 클릭할 수 있게 할 수 있음)
   *	Checkbox : 여러가지 항목 중 여러 개를 선택할 수 있는 버튼
   *	Date : 날짜를 입력받는 칸
   *	Email : 이메일을 입력받는 칸, 약간의 이메일 형식 검사를 해준다
   *	Color : 컬러를 입력할 수 있는 칸
   *	textarea : 아주 긴 내용의 텍스트를 입력할 수 있다
   *	select : 사용자가 여러 옵션 중 하나를 선택할 수 있다.(option 태그를 통해 옵션을 추가할 수 있음)
 

