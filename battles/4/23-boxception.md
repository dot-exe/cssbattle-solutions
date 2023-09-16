# Battle #4-23: Boxception

**Link:** [Here!](https://cssbattle.dev/play/23)
<br>
**Ratings:**
<br>
*Score: 600.31*
<br>
*Characters: 753*

![23-boxception](/battles/4/23-boxception/23-boxception-solution.png)
<sub>Photo with my score</sub>
<br>
<br>

```html
<div class="figure">
    <div class="part-1"></div>
    <div class="part-2"></div>
    <div class="part-3"></div>
    <div class="part-4"></div>
</div>
<style>
    body {
        background: #F3AC3C;
    }

    .figure {
        width: 200px;
        height: 200px;
        display: grid;
        grid-template: 50px 50px 50px 50px / 50px 50px 50px 50px;
        position: fixed;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%);
    }

    .part-1 {
        grid-row: 1 / 3;
        grid-column: 1 / 5;
        background: #1A4341;
    }

    .part-2 {
        grid-row: 3 / 5;
        grid-column: 3 / 5;
        background: #1A4341;
    }

    .part-3 {
        grid-row: 3 / 4;
        grid-column: 1 / 3;
        background: #998235;
    }

    .part-4 {
        grid-row: 4;
        grid-column: 1;
        background: #998235;
    }
</style>
```
<sub>Full code for my solution</sub>
<br>
<br>
**Ratings:**
<br>
*Score: 696.67*
<br>
*Characters: 149*

```html
<div class="figure">
</div>
<style>
  body {
    background: #F3AC3C;
  }
  .figure {
    width: 200px;
    height: 200px;
    position: fixed;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    background: #F3AC3C;
    box-shadow: inset -100px 100px #1A4341,
                inset 50px 150px #998235;
  }
</style>
```
<sub>Second solution</sub>

It took me a while to figure out how to shorten the code. The `grid` layout seemed to be more natural solution for this excercise, but `box-shadow` with `inset` parameter is much simplier. The HTML template is reduced to only one `div` and one CSS class, which massively improve the score (the code placed below has only 149 characters and scores at 696.67 points).

```html
<div><style>*{background:#F3AC3C}div{width:200;height:200;position:fixed;top:50;left:25%;box-shadow:inset -100px 100px#1A4341,inset 50px 150px#998235
```

or

```html
<div><style>*{background:#F3AC3C}div{width:50;height:50;position:fixed;top:200;left:150;box-shadow:-25px -25px 0 25px#998235,25px -75px 0 75px#1A4341
```

This code can run without `<div>`, but then `margin:0` is required.

```html
<style>*{background:#F3AC3C;margin:0;width:200;height:200;position:fixed;top:50;left:25%;box-shadow:inset -100px 100px#1A4341,inset 50px 150px#998235
```

or 

```html
<style>*{background:#F3AC3C;margin:0;width:50;height:50;position:fixed;top:200;left:150;box-shadow:-25px -25px 0 25px#998235,25px -75px 0 75px#1A4341
```