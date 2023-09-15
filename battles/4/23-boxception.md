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
