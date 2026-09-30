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

/* 일부러 극단적으로 키운 값 */
.box {
  width: 120px;
  padding: 40px;              /* 매우 두꺼운 안쪽 여백 */
  border: 10px dashed #FF6B57; /* 두껍고 색이 튀는 테두리 */
  margin: 50px;              /* 매우 넓은 바깥 여백 */
  background: #FFF3E9;       /* padding 영역 색 */
}
.content {
  background: #0EA5C4;       /* content 영역 색 */
  color: #fff;
  text-align: center;
  padding: 14px 0;
}
.outer {
  background: #F1F5FB;       /* margin 영역은 이 배경이 그대로 비쳐 보임 */
}
