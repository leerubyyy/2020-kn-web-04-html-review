# HTML, CSS, ES5, jQuery 에서 복습 및 배울것
	1. css FlexModel
	2. css Bootstrap
	3. Swiper Plugin
	4. Javascript 심도
	5. jQuery 리뷰

# jQuery 리뷰
## jQuery 는 함수(메서드)로 만들어져 있다.
```js
var $ = jQuery
jQuery(".wrap").hide();
$(".wrap").hide();

// 다음중 올바른 표현을 고르시오.
$(".a").hasClass("b").hide();
$(".a").append('<div>A</div>').hide(); //정답
$(".a").width().hide();
$(".a").attr("id").hide();
```

0. Selector(선택자)

1. Animation
```js
hide()
show()
fadeIn()
fadeOut()
slideUp()
slideDown()
toggle()
fadeToggle()
slideToggle()
animate()
```

2. DOM(Document Object Model)

3. Attribute

4. CSS

5. Dimension

6. Event

7. getter/setter
	- html(), text(), css(), attr(), 