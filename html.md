#### Q. html에서 line break (br을 쓰지않고 pre태그로 하는방법)이 있는가?

A. You can use the <pre> tag to keep the line breaks.

<pre>
lorem ipsum
lorem ipsum
lorem ipsum
</pre>

#### Q.html로 시멘틱 웹페이지의 구체적인 예가 무엇인가? 

A. 답변 준비 중

#### Q. HTML에 LABEL은 왜 쓰고 FOR어트리뷰트는 왜 쓰는가?

A. 답변 준비 중

#### Q. 메타 엘리먼트가 무엇인가?

A. html의 메타 정보를 담은 엘리먼트를 메타 엘리먼트라고 한다. 대략 아래와 같다
<meta http-equiv="origin-trial" content="{Replace with origin trial token}">
https://developer.mozilla.org/ko/docs/Web/HTML/Element/meta

#### Q. META 엘리먼트에서 viewport가 무엇인가?

A. 답변 준비 중

#### Q. META 엘리먼트에서 content가 무엇인가?

A. content는 viewport와 함께 사용되는 것으로 보인다

#### Q. meta 엘리먼트에서 어트리뷰트로 `name="viewport"`라고 적는 경우가 있는데 이게 무슨 뜻인가 ?

A. <meta name="viewport" content="width=device-width, initial-scale=1.0" />
이걸 말하는 건가 ?

#### Q. html 에서 폰트 불러올때 as font로 불러오는 이유는 무엇인가 ?

A. The as="font" type="font/woff2" attributes tell the browser to download this resource as a font and helps in prioritization of the re­source queue.

#### Q. 왜 사람들은 div엘리먼트의 사용을 꺼리는가?

A. 두가지 이유가 있다
첫쨰로 nested div는 함수 컴포넌트를 더럽게 한다
둘째로 무분별한 div의 사용은 html의 시멘틱적인 이해를 이해하기 어렵게 만든다

#### Q. 인용문을 표기하고 싶을 때는 어떤 html 엘리먼트를 사용하는가 ?

A. q(quote)태그를 사용한다. 상세는 https://developer.mozilla.org/ko/docs/Web/HTML/Element/q 를 참조하시오

#### Q. svg 엘리먼트란 무엇인가?

A. svg 엘리먼트는 일반적으로 도형을 그리는데 사용된다. 이 때 비트맵을 이용하지 않아 용량적인 관점에서 유리하다\
svg 엘리먼트는 비트맵 이미지를 SVG 객체와 함께 표시할 수 있도록 해 준다. 예를 들어 아래와 같다

<svg width="5cm" height="4cm" version="1.1"
     xmlns="http://www.w3.org/2000/svg" xmlns:xlink= "http://www.w3.org/1999/xlink">
	<image xlink:href="firefox.jpg" x="0" y="0" height="50px" width="50px"/>
</svg>


#### Q. `<noscript/>` 엘리먼트가 무엇인가?

아래의 예시를 참조하라
```html
<link rel="preload" href="style.css" as="style">
<noscript><link rel="styleshet" href="style.css"> </noscript>
```

---

# 기타

#### table 엘리먼트는 폰트정보를 오버라이딩 한다