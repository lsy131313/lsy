<!DOCTYPE html>
<html>
  <head>
    <title>내 첫 웹페이지</title>
  </head>
  <body>
    <h1>안녕하세요!</h1>
  </body>
</html>
<div style="border: 1px solid;">
  <h1>1</h1>
</div>
<div style="border: 1px dashed;">
  <h2>2</h2>
</div>
<div style="border: 1px dotted;">
  <h3>3</h3>
</div>
<div style="border: 1px double;">
  <h4>4</h4>
</div>
<div style="border: 1px groove;">
  <h5>5</h5>
</div>
<div class="outer">
  <div class="box">
    <div class="content">content</div>
  </div>
</div>

<!-- HTML: 박스 3개를 감싸는 부모 -->
<div class="container">
  <div>박스1</div>
  <div>박스2</div>
  <div>박스3</div>
</div>

/* CSS: 부모에게 flex 지시 */
.container {
  display: flex;
  justify-content: center;
  gap: 12px;
}
