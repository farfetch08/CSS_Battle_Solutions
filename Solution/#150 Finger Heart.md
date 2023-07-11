<div class="square"></div>
<div class="finger f1"></div>
<div class="finger f2"></div>
<style>
  * {
    background: #1038BF;
    margin: 0;
  }
  body {
    background: #4F77FF;
  }
  .square {
    width: 150px;
    height: 150px;
  }
  .finger {
    height: 50px;
    width: 50px;
    border-radius: 0 50% 50% 0;
    position: absolute;
  }
  .f1 { 
    transform: rotate(90deg);
    top: 150px;
    left: 100px;
  }
  .f2 {
    left: 150px;
    top: 100px;
  }
</style>
