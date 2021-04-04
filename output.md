## output

- <output> 태그는 스크립트 등에 의해 수행된 계산의 결과나 사용자의 액션에 의한 결과를 나타낼 때 사용한다.
  
```html
<form action="/examples/media/action_target.php" oninput="result.value=parseInt(a.value)+parseInt(b.value)">
    <input type="number" id="a" name="a" value="20"> + 
    ( 0 <input type="range" id="b" name="b" value="0"> 100 )=
    <output name="result" for="a b"></output><br>
    <input type="submit">
</form>
```

- 연산의 결과값이 출력된다.