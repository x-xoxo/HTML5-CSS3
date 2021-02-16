## 복습  

    <p> / <table> / <ul>, <ol>, <li>  
Useable Image format
-> PNG, JPEG, JPG, GIF / 웹에따라 Vector Image ex) VSG  

## 폼 관련 태그

    <input> - type / <button>  

`<form>` Tag
쓰는 이유  
-> `<form>`을 사용함으로써 View에서 받은 정보들을 Control로 내려보낼 수 있음  

속성  
- ★ Method  
    - get 방식 : 입력내용이 그대로 나옴.  
    - post 방식 : 입력내용이 드러나지 않음.  
- name, target  
- ★ action  

`<label>` Tag  
form 태그에 라벨 붙임
예를들어
```html
<label><input type="radio" name="subject" value="jp">일어회화</label>
```
이런 식으로 붙히면 글씨 부분을 클릭해도 체크박스가 선택됨

## CSS  
```css
* {} /* 전체 css 적용 */
Tagname {} /* 특정 태그 css 적용 */
.Stylename {} /* class 스타일이름에 css 적용 */
#Stylename {} /* ID 스타일이름에 css 적용 */
name1, name2 ... {} /* 여러 항목에 css 적용 */
```
CSS 적용 우선 순위
1. inline 스타일
2. id 스타일
3. class 스타일
4. tag 스타일  

CSS 브라우저 접두사(prefix)
- Safari, Chrome : -webkit-
- Mozila, Firefox : -moz-
- Opera : -o-
- Microsoft : -ms-  

Text 관련 method  
- font-family : 글꼴 지정
- font-size : 글자 크기
    - em : 반응형
    - ex : 해당 글꼴 소문자의 높이를 기준으로 크기를 조절
    - px : pixel
    - pt : point
- text-align : 문자 정렬
- font-weight : 폰트 굵기
- color : 폰트 컬러
- line-height : 줄 간격  