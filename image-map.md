## Image - Map

- 이미지맵은 우리가 정한 이미지의 특정 부분을 링크처리하는 것이다.

### 예시 코드

```html
<img src="./mountain-477832_640.jpg" alt="산 이미지" usemap="#mountain">
    <map name="mountain">
        <area shape="rect" coords="0,0,200,200" href="https://ko.wikipedia.org/wiki/%EC%82%B0" alt="https://ko.wikipedia.org/wiki/%EC%82%B0">    
    </map>
```

1. img 태그에 usemap 속성을 사용하여 map을 사용한다고 지정한다.

1. map태그의 name속성값을 usemap 값과 연결 시킨다.

1. area 태그 안에 속성 shape(링크 모양), coords(링크 좌표), href, alt 값을 작성해준다.
  


