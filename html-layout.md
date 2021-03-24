## HTML - Layout


![HTML - sectioning elements](https://www.w3schools.com/html/img_sem_elements.gif)


### HTML sectioning elements

- **sectioning element들은 반드시 heading 태그로 각 section의 제목을 정의해 주어야 한다.**

- &lt;nav&gt;: HTML 문서의 탐색 링크를 정의함 ex) 메뉴.

- &lt;section&gt;: HTML 문서에서 섹션(section) 부분을 정의함.
div로 나눠주는 것보다 시멘틱하게 할 수 있음.

- &lt;article&gt;: HTML 문서에서 독립적인 하나의 글(article) 부분을 정의함 ex) 기사, 블로그.

- &lt;aside&gt;: 논리적으로는 완결되었지만 HTML 문서에서 페이지 부분 이외의 콘텐츠(content)를 정의함. 


## sectioning element는 아니지만 문서의 구조를 잡을 때 쓰는 태그


### header

- &lt;header&gt;: HTML 문서나 섹션(section) 부분에 대한 헤더(header)를 정의함.
    
    - 도입부 정도로 생각하면 된다.


### main

- &lt;main&gt; 태그는 해당 문서의 &lt;body&gt; 요소의 중요한 주 콘텐츠(main content)를 정의할 때 사용.
    - 따라서 하나의 문서에는 단 하나의 main 요소만이 존재해야 한다.

- main 태그는 sectioning element가 아니다.
    
    - 반드시 heading 태그를 쓸 필요는 없다.

- sectioning element들을 감싸기 때문에 내부에는 존재할 수 없다.


### footer

- &lt;footer&gt;: HTML 문서나 섹션(section) 부분에 대한 푸터(footer)를 정의함.
        