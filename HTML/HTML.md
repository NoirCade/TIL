# HTML

    웹페이지를 구성하는 HTML, CSS, JavaScript 중에서 HTML은 페이지의 뼈대를 구성하는 역할을 하는 마크업 언어이다. 

실제 웹페이지에 보여지는 컨텐츠들을 작성하고, 구조를 잡는 역할을 한다.

## 웹의 동작방식

    클라이언트(브라우저)의 요청(주소 입력)에 대해서 서버에 준비된 html 페이지를 응답!
    응답받은 페이지를 다시 클라이언트가 렌더링하여 화면에 표시

## HTML 문서의 구성

    1. 머리에 <!DOCTYPE html>, <html> 이 붙어야하며, 끝에 </html>이 존재한다.
    2. 본문에 대한 설명부분인 헤더(<head></head>)와 실제 페이지에 노출되는 바디(<body></body>)가 존재한다.
    3. 헤더 부분에 <meta charset="UTF-8">이 존재해야 본문에 한국어를 사용할 수 있다.

## HTML 문법 유의사항

    <태그이름 세부속성="속성값"> 콘텐츠 </태그이름> 의 형식으로 작성한다

1. 해당 태그 사이의 전체를 '요소'라고 부르며, 태그를 열었다면 반드시 닫아야한다.
2. 중첩해서 태그 안에 다른 태그가 들어갈 수 있다.
3. 예외적으로 닫지 않는 태그도 있다. ex) '<img src="">'
4. 속성값을 입력할 때는 반드시 ""을 이용!

## HTML 주요 문법

> 제목 h1 ~ h6

    <h1>제목1</h1>
    <h2>제목2</h2>
    <h3>제목3</h3>
    <h4>제목4</h4>
    <h5>제목5</h5>
    <h6>제목6</h6>
<br>

> 문단 p

    <p>hello world</p>
<br>

> 앵커 a

    <a href="https://asdf.com">링크</a>

    이때, target="_blank 를 추가로 붙여서 새 창으로 열 수 있다

    <a href="https://asdf.com" target="_blank">새 창으로 링크</a>
<br>

> 이미지 img

    <img src="이미지 파일 주소>
<br>

> 리스트 ul, ol, li

    <ul>
        <li>순번 없는</li>
        <li>리스트</li>
    </ul>

    <ol>
        <li>순번 있는</li>
        <li>리스트</li>
    </ol>
<br>

> 표 table, thead, tbody, tfoot

    <table>
        <thead>
            <th>
                <td>1행 1열</td>
                <td>1행 2열</td>
            </th>
        <thead>
        <tbody>
            <tr>
                <td>2행 1열</td>
                <td>2행 2열</td>
            </tr>
        </tbody>
        <tfoot>
            <tr>
                <td>3행 1열</td>
                <td>3행 2열</td>
            </tr>
        </tfoot>
    </table>
<br>

그 밖에도 다양한 문법들이 존재

## 웹 표준

    검색 엔진 최적화(SEO)를 위하여 문법적 요소들을 잘 지켜주는 것이 좋다!
    W3C에서 웹표준에 대한 기준을 제시하고 있다