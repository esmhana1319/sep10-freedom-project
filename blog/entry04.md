# Entry 4
##### 2/24/24

# My tool & descision process

When introduced with the tentative tools we would be using for this segment of the freedom project, I was stuck between two choices. Jquery and Jekyll. Originially, I chose against Jquery because I found that it relied mainly on Javascript shortcuts, which I decided would be best to try later once I broaden my understanding. I tinkered with Jekyll by following the steps of installation on their website and found that Jekyll uses shortcuts like Jekyll serve and Jekyll build which are similar in format to the commands we were taught this unit, and have the function of building html websites and templating them. But ultimately, I faced errors with installing jekyll on multiple operating systems and decided Jquery would be my best option.

# Jquering or Tinkering with JQuery

```html
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.7.1/jquery.min.js"></script>
```
This link is used to run Jquery on your website, specifically through a CDN like google. In order to execute this function I pasted in the html and css of an old web page project I made.

```html
<script>
$(document).ready(function(){

  // jQuery methods go here...

});
</script>
```

Jquery methods are used to select certain aspects of your webpage, and then perform a specific action on them. They would normally go in this, which is called a document ready event that prevents these actions from happening before the page is loaded

```html
<script>
$(function(){

  // jQuery methods go here...

});
</script>
```

This is another document ready event that is shorter and quicker to use. Some examples of methods shown on W3Schools (the source im using to learn) include,

```html
<script>
$(this).hide() - hides the current element.
</script>
```
```html
<script>
$("p").hide() - hides all <p> elements.
</script>
```
```html
<script>
$(".test").hide() - hides all elements with class="test".
</script>
```
```html
<script>
$("#test").hide() - hides the element with id="test".
</script>
```

The example they showed in their tutorial was a button function, so to process this properly I will be using this event.

```html
<script>
$(document).ready(function(){
  $("button").click(function(){
    $("p").hide();
  });
});
</script>
```

After adding a button to my webpage and the function above within the script tag, Jquery hides all the paragraph elements in my HTML, making my website ‘slightly?’ interactive.
Of course there are more aspects of JQuery, such as clicks, double clicks, mouseenter (pointer hovers above an element), on (which attaches multiple events) etc.

There is actually so much opportunity within using JQuery for interactive and fun websites, and I'm glad I gave it a chance!

# Sources

In order to tinker with Jquery, I used HTML and CSS from an old project of mine, along with the W3Schools website to get started on introducing myself to the basics.

[link to my the revised project with JQuery](https://musical-dollop-pjrvr9g97p7whr9-8080.app.github.dev/index.html)

[link to the old project I used to tinker](https://replit.com/@esmhana/minions-color-lesson#index.html)

[W3Schools intro to JQuery](https://www.w3schools.com/jquery/jquery_intro.asp)

# Skills

Through this learning process, I had to know when to quit on certain things that just werent working for me (cough cough jekyll) and start anew with something else, which bettered my decision making and my ability to just give up and start again
```
developed skill *-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*
  using decision making to find better options lvl 4
-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-
```

Also through my process in learning Jquery, I pre-documented my process as I was tinkering with it, which made finalizing my blog quicker and easier.
```
developed skill *-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*
  Planning my work and documenting my progress lvl 7 
-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-
```


[Previous](entry03.md) | [Next](entry05.md)

[Home](../README.md)
