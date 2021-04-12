# list 태그

## ordered list

```html
<h2>김치찌개 재료</h2>
<ol>
    <li>김치</li>
    <li>물</li>
    <li>채소</li>
</ol>
```
- 순서가 없는 단순한 리스트를 감싸는 태그가 ol태그이다.

## un-ordered list

```html
<h2>사격 방법</h2>
<ul>
    <li>노리쇠 후퇴고정</li>
    <li>탄알집 장전</li>
    <li>노리쇠 전진</li>
    <li>조정간 단발</li>
    <li>격발</li>
</ul>
```
- 순서가 있는 리스트를 감싸는 태그가 ul 태그이다.

## 주의사항

- **ul과 ol태그의 직계자식태그로는 반드시 li태그만 올 수 있다!!**

## list 태그와 관련된 css속성

### list-style-type

- li들을 가르키는 점이나 숫자들의 마커를 변경할때 쓰는 속성이다.

```css
    .circle { list-style-type: circle; }
    .square { list-style-type: square; }
    .upperAlpha { list-style-type: upper-alpha; }
    .lowerRoman { list-style-type: lower-roman; }
```
  
### list-style-image

- li들을 가르키는 마커를 원하는 image로 변경할 수 있다.

```css
 .imageMarker {
     list-style-image: url("이미지 주소"); 
    }
```

### list-style-position

- li들의 위치를 조정한다.

```css
.position {
    .outside { 
        list-style-position: outside; 
        }
    .inside {
        list-style-position: inside; 
        }
}
```





