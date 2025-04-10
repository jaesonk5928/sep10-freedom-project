# Entry 5
##### 4/11/25

### Content
While writing this blog, I've been learning my tool [animate.css](https://animate.style/) for a while now and learned many things from the website, including (X = numbers):
* `@keyframes` -> This makes it so using animations doesn't interfere with the **HTML** code, rather you code it in **CSS** section. It's all up to preference.
* `class="animate__(anything)"` or `animation: (anything);` -> This is the proper code to animate **HTML/CSS** elements classes. It is cool to watch too/recommended.
* `animate__delay-(X)s` or `--animate-delay: (X)s;` -> This code allows animations to not play for a specific amount of time, then plays the animation after. It's good for elements to no load all at once, rather have something play first.
* `animate__slow(er)/fast(er)` and `--animate-duration: X(s)` -> This property allows animations to animate either slower or faster. It depends how you want it. Also, animation duration makes animation last longer/shorter.
* `animate__(repeat-X)/(infinite)` -> This property allows animations to repeat _x_ amount of times or infinite. This is a very "questionable", as people don't usually like repeating animations.

### More Content
After learning a lot from [animate.css](https://animate.style/), I started being productive and tinkered some of the _animation properties_ that it offered. I even included **Bootstrap** components to animate them. Here is the code that I tinkered with in my _IDE_:

```HTML

<div class="container">
 <div class="row">
  <div class="col-12">
    <p id="1st" class="animate__animated animate__pulse animate__slow animate__repeat-3">LOREM IPSUM TEXT</p>
<div class="container">
 <div class="row">
  <div class="col-12">
    <p id="2nd" class="animate__animated animate__pulse animate__slow animate__repeat-3">LOREM IPSUM TEXT</p>
<div class="container">
 <div class="row">
  <div class="col-12">
    <p id="3rd" class="animate__animated animate__pulse animate__fast">LOREM IPSUM TEXT</p> <br>
</div>
 </div>
  </div>
</div>
 </div>
  </div>
</div>
 </div>
  </div>
```



[Previous](entry04.md) | [Next](entry06.md)

[Home](../README.md)
