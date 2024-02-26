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

[W3Schools website tutorial](https://www.w3schools.com/jquery/jquery_hide_show.asp)   
[my attempt](https://www.w3schools.com/jquery/tryit.asp?filename=tryjquery_hide_show)

<!-- 
* Links you used today (websites, videos, etc)
* Things you tried, progress you made, etc
* Challenges, a-ha moments, etc
* Questions you still have
* What you're going to try next
-->
