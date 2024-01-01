#MarkDown example
<h1> Basic of Markdown Language

<h2> 1. Header Sizes
<h3> Use <em>"h1~h6"</em> or <em>"#~######"</em>
<h4> H4 <h5> H5 <h6> H6 </h6>

<h2> 2. Emphasis
<h3>
<em> italic </em>
<strong> strong </strong>
<del>del</del>
<u> underline </u>
</h3>

<h2> 3. List</h2>
<h3>
<ol>. Orederd list
    <ol> 1.1 순서 필요 
        <ol> 1.1.1 순서 필요 </ol>
    </ol>
    <ol> 1.2 순서 필요? </ol>
</ol>

<ul> . Unorderd list
    <ul> * asterisks </ul>
    <ul> / hipen </ul>
    <ul> + sign  </ul>
</ul>
</h3>

<h2> 4. Links</h2>
<h3>
[GOOGLE](https://google.com)

[NAVER](https://naver.com "링크 설명(title).")

[Naver][참조 링크]

[Github][1]

[상대적 참조](../users/login)


[1]: https://github.com
[참조 링크]: http://naver.com "네이버로 이동"
</h3>

<h2> 5. Images</h2>

### Like links, but pre-fix "!"

![Text 입력](http://www.gstatic.com/webp/gallery/5.jpg "description")

![Kayak][Logo]

[Logo]: http://www.gstatic.com/webp/gallery/2.jpg "To go kayaking."

<h2> 6. Image & Link</h2>

[![Vue](/images/vue.png)](https://kr.vuejs.org/ "description2")

<h2> 7. Emphasis of code </h2>

<h3> 7.1 Inline 코드 강조 </h3>

`inline 코드 강조`

<h3> 7.2 Block 코드 강조 </h3>

```html
<a href="https://www.google.co.kr/" target="_blank">GOOGLE</a>
```

```css
.list > li {
  position: absolute;
  top: 40px;
}
```

```javascript
function func() {
  var a = 'AAA';
  return a;
}
```

```bash
$ vim ./~zshrc
```

```python
s = "Python syntax highlighting"
print s
```

```
No language indicated, so no syntax highlighting. 
But let's throw in a tag.
```

<h2> 8. Table </h2>

| col1 | col2 | col3 |
|---|:---:|---:|
| `static` | 유형(기준) 없음 / 배치 불가능 | `static` |
| `relative` | 요소 자신을 기준으로 배치 |  |
| `absolute` | 위치 상 부모(조상)요소를 기준으로 배치 |  |
| `fixed` | 브라우저 창을 기준으로 배치 |  |

| col1 | col2 | col3 |
|---|:---:|---:
 `static` | 유형(기준) 없음 / 배치 불가능 | `static` |
 `relative` | 요소 자신을 기준으로 배치 |  |
 `absolute` | 위치 상 부모(조상)요소를 기준으로 배치 |  |
 `fixed` | 브라우저 창을 기준으로 배치 |  |

 <h2> 9. BlockQuote(인용문) </h2>

 인용문(blockQuote)

> 남의 말이나 글에서 직접 또는 간접으로 따온 문장.
> _(네이버 국어 사전)_

BREAK!

> 인용문을 작성하세요!
>> 중첩된 인용문(nested blockquote)을 만들 수 있습니다.
>>> 중중첩된 인용문 1
>>> 중중첩된 인용문 2
>>> 중중첩된 인용문 3

 <h2> 10. 원시 HTML(Raw HTML) </h2>

 <u>마크다운에서 지원하지 않는 기능</u>을 사용할 때 유용하며 대부분 잘 동작합니다.

<img width="150" src="http://www.gstatic.com/webp/gallery/4.jpg" alt="Prunus" title="A Wild Cherry (Prunus avium) in flower">

![Prunus](http://www.gstatic.com/webp/gallery/4.jpg)

 <h2> 11. 수평선(Horizontal Rule) </h2>

---
 (Hyphens)

***
(Asterisks)

___
(Underscores)

<h2> 12. 줄바꿈(Line Breaks) </h2>
<!--띄어쓰기 2번 or <br>-->

동해물과 백두산이 마르고 닳도록  
하느님이 보우하사 우리나라 만세  
무궁화 삼천리 화려 강산<br>
대한 사람 대한으로 길이 보전하세

