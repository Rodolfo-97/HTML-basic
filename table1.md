## table

### table 태그

    - tr과 td 그리고 th태그 등 table의 구성요소 전체를 감싼다.
    - table의 시작을 알린다고 생각하면 된다.

### tr 태그

    - table의 가로 줄을 나타낸다.
    - th태그나 td태그로 줄의 구성 요소를 정한다.

### th 태그(Table Head)

    - 데이터의(보통 가장 윗줄)을 나타낸다.

### td 태그(Table Data)

    - th태그에 알맞은 데이터를 나타낸다.

### thead 태그

    - th태그가 있지만 thead태그로 tr태그를 감싸주면서 표의 헤드에 관한 내용이라는 것을 더 명확하게 할 수 있다. 

### tbody 태그

    - 표의 제목에 해당하는 데이터(td태그)들을 감싼다.

### tfoot 태그
    
    - 영수증의 마지막에 나오는 최종합계와 비슷한 데이터들을 감싼다. 

### 주의사항

- th태그의 수와 td태그의 수는 항상 일치해야한다.
    - 아래의 코드를 보면 수를 맞추려 아무 내용도 없는 td태그를 넣어줬음을 알 수 있다.


### 예시 코드

```html
<table>
        <thead>
            <tr>
                <th>이름</th>
                <th>id</th>
                <th>개발분야</th>
                <th>기타</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Rodolfo</td>
                <td>Rodolfo-97</td>
                <td>프론트엔드</td>
                <td></td>
            </tr>
            <tr>
                <td>Ruis</td>
                <td>ru9095</td>
                <td>풀스택</td>
                <td></td>
            </tr>
        </tbody>
    </table>
```
