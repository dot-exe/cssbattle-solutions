# Battle #4-25: Blossom

**Link:** [Here!](https://cssbattle.dev/play/25)
<br>
**Ratings:**
<br>
*Score: ???*
<br>
*Characters: 1307*

![25-blossom](/battles/4/25-blossom/25-blossom-solution.png)
<sub>Photo with my score</sub>
<br>
<br>

```html
<div class="figure">
  <div class="p1"></div>
  <div class="p2"></div>
  <div class="p3"></div>
  <div class="p4"></div>
</div>
<style>
  body {
    background: #998235;
  }
  .figure {
    width: 180px;
    height: 180px;
    position: fixed;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    display: flex;
    flex-direction: column;
    flex-wrap: wrap;
    justify-content: space-between;
    align-content: space-between;
  }

  .p1 {
    width: 80px;
    height: 100px;
    background: #1A4341;
    border-radius: 0px 50px;
  }
  .p2 {
    width: 80px;
    height: 60px;
    background: #F3AC3C;
    border-radius: 0px 50px;
  }

  .p3 {
    width: 80px;
    height: 60px;
    background: #F3AC3C;
    border-radius: 50px 0px;
  }
  .p4 {
    width: 80px;
    height: 100px;
    background: #1A4341;
    border-radius: 50px 0px;
  }
</style>
```
<sub>Full code for my solution</sub>
