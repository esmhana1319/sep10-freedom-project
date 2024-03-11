# Tool Learning Log

Tool: **JQery**

---

2/26/24:

In my fourth blog I talked my experience tinkering with Jquery, my decision process, along with how I learned how to use it. The specific event I learned how to use was hide and although its very cool, I dont see much of a use for it within my project. Moreover i want to try something more of the opposite where my audience can interact with my wepage to reveal certain parts of it. Which is lucky for me because JQuery promotes that exact function

```html
<script>
$("#show").click(function(){
  $("p").show();
});
</script>
```

By using the event "show", you can reveal a certain HTML element when you do a specific action. In this example when you click something, the paragraphs reveal themselves.


```html
<script>
$(selector).hide(speed,callback);
$(selector).show(speed,callback);
});
</script>
```

This code snippet is used to measure the amount of speed the event is. This only plays after the event is completed***

3/4/24:

The two functions I will show today are more of additions to the ones Ive previously written about, hide and show. This first one is called callback, which rather than making your element "poof" or suddenly dissapear it makes a more smoother transition.

```html
<script>
$(document).ready(function(){
  $("button").click(function(){
    $("p").hide("slow", function(){
      alert("The paragraph is now hidden");
    });
  });
});
</script>
```
by adding "slow" to your hide function, it makes a transition similar to that of a curtain raising upwards, or a slideshow esque feel. Now because i was a bit curious, i changed slow to "fast" to see if anything would happenm, and surprisingly it did.

```html
<script>
$(document).ready(function(){
  $("button").click(function(){
    $("p").hide("fast", function(){
      alert("The paragraph is now hidden");
    });
  });
});
</script>
```

by adding fast to your hide function, you have a more quicker transition that wraps up nicely. This can be used in demos of my freedom projects content, and could be used to display or hide content like images and captions.

```html
<script>
$("#flip").click(function(){
  $("#panel").slideDown();
});
</script>
```
The function above, slidedown makes an element slide down when a certain action is performed on it. The example I have shown is a slidedown event that happens when you click on a banner, that causes a panel to cascade.

3/11/24

The function below is a slidedown and slideup jquery event with css attatched to it causing it to turn the selected element red. The way this function works is that a javascript event is made and it enables css onto an element when an action is performed, which in this case its when a button is clicked

```html
<head>
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.7.1/jquery.min.js"></script>
<script>
$(document).ready(function(){
  $("button").click(function(){
    $("#p1").css("color", "red").slideUp(2000).slideDown(2000);
  });
});
</script>
</head>
<body>

<p id="p1"> this is a jquery event haha :D </p>

<button> Click me if u like red </button>

</body>
```

This function below is called fade, which includes multiple variations and levels of fade. This event executes after the action click is performed.

```html
<head>
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.7.1/jquery.min.js"></script>
<script>
$(document).ready(function(){
  $("button").click(function(){
    $("#div1").fadeIn();
    $("#div2").fadeIn("slow");
    $("#div3").fadeIn(3000);
  });
});
</script>
</head>
<body>

<p>Different types of fade</p>

<button>click me to execute</button><br><br>

<div id="div1" style="width:80px;height:80px;display:none;background-color:orange;"></div><br>
<div id="div2" style="width:80px;height:80px;display:none;background-color:pink;"></div><br>
<div id="div3" style="width:80px;height:80px;display:none;background-color:yellow;"></div>

</body>
```



[W3Schools website tutorial](https://www.w3schools.com/jquery/jquery_hide_show.asp)

<!--
* Links you used today (websites, videos, etc)
* Things you tried, progress you made, etc
* Challenges, a-ha moments, etc
* Questions you still have
* What you're going to try next
-->
