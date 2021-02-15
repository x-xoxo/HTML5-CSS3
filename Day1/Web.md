# HTML5 & CSS3

## HTML5

### Text tag
- p  단락을 만드는 태그  
- b, strong  텍스트 굵게  
- table  표 만들기  // 게시판
- mark  형광펜으로 그은 것처럼 표시  
- em, i  이탤릭체 표시  
- ul, ol, li  목록을 만드는 태그  
___
- h  제목태그 h1 ~ h6  
- br   개행태그 = \n
- hr  줄바꿈인데 직선이 하나 그어짐
- blockquote  인용문 넣기
- pre  원래 그대로 쓰기
- q  쌍따옴표 쓰는 태그  

### table Tag
- tr : 행
- td : 셀
- th : 행의 헤더
```html
<table>
    <tr>
        <th></th>
        <td></td>
    </tr>
</table>

```
### img Tag  
- img : 이미지를 삽입하는 태그  
- figcaption : 이미지를 설명하는 태그  
- a : 링크를 만드는 태그  
- target : 링크를 새창, 새탭에서 열기위한 `<a>` 태그의 속성
- map : 이미지 맵을 만드는 태그  
Useage :
```html
<img src="a.png" alt="No images"> <!-- 이미지 없을 경우 alt 출력 -->
```
HTML에서 사용할수 있는 이미지파일형식
- JPG  
- JPEG  
- PNG  
- GIF  
### `<a>` Tag  
- href : 링크한 문서나 사이트의 주소를 입력  
- target : 현재 창인이 새창인지 선택
    - _blank(새창)  
    - _self(내창)  
    - _parent(부모창)  
    - _top(최상위창)  
- download, rel, hreflang, type 
### `<map>` Tag  
- area