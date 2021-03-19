## table 태그2


### td와 th태그의 속성

#### rowspan

- 해당 셀을 **수직**으로 병합한다.

#### colspan

- 해당 셀을 **수평**으로 병합한다.


### th코드의 속성 scope

- scope속성의 값 row와 col을 통해서 해당 th태그가 행과 열중 무엇을 대표하는지 명확하게 나타낼 수 있다. 


### 위 설명의 예시코드

```html
<table>
        <tr>
            <th></th>
            <th scope="col">월</th>
            <th scope="col">화</th>
            <th scope="col">수</th>
            <th scope="col">목</th>
            <th scope="col">금</th>
        </tr>
        <tr>
            <th scope="row">1교시</th>
            <td rowspan="2">왕초보 HTML and CSS</td>
            <td>모각코</td>
            <td rowspan="2">왕초보 HTML and CSS</td>
            <td>모각코</td>
            <td rowspan="2">왕초보 HTML and CSS</td>
        </tr>
        <tr>
            <th scope="row">2교시</th>
            <!-- 이미 두번째 줄의 2번째 셀이 차지함 -->
            <td rowspan="2">JavaScript 스킬업</td>
            <!-- 이미 두번째 줄의 4번째 셀이 차지함 -->
            <td rowspan="2">JavaScript 스킬업</td>
            <!-- 이미 두번째 줄의 6번째 셀이 차지함 -->
        </tr>
        <tr>
            <th scope="row">3교시</th>
            <td>JavaScript 시작반</td>
            <!-- 이미 세번째 줄의 세번째 셀이 차지함 -->
            <td>JavaScript 시작반</td>
            <!-- 이미 세번째 줄의 세번째 셀이 차지함 -->
            <td>JavaScript 시작반</td>
        </tr>
        <tr>
            <td colspan="6">점심시간</td>
        </tr>
    </table>
```

- rowspan과 colspan으로 인해 데이터들이 병합되면 병합된 데이터의 자리는 이미 찼기 떄문에 따로 적어주지 않는다.