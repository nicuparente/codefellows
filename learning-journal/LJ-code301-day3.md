# LJ Code 301 - Day 3

We covered a lot in JQUERY in the last two days from selecting elements, adding simple animations and of course event handling.

**Callbacks** were also discussed which in my experience is probably one of the most important concepts to understand in JavaScript. I had a hard time understanding this concept before but I ended up summarizing it as "it's passing a function and it runs that function after the main function is finished executing"


### Event Listener Sample
```javascript
$('.hamburger-menu').on('click', function(){

 $('.main-nav').css(
   { 'display': 'block',
     'font-size': '3em'
   });
});

```


### Removing a class from a sub set of elements from original query
```javascript

var $pragraphs = $('.main-body');

$pargraphs.find('p').removeClass('active');

```
