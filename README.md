<!DOCTYPE html>
<html lang="tr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Kafe Menü</title>
<style>
body{
  font-family: Arial;
  margin:0;
  background:#f5f5f5;
}
header{
  background:#222;
  color:white;
  padding:20px;
  text-align:center;
  font-size:24px;
}
.menu{
  padding:20px;
}
.item{
  background:white;
  margin-bottom:10px;
  padding:15px;
  border-radius:10px;
  display:flex;
  justify-content:space-between;
}
.price{
  font-weight:bold;
}
</style>
</head>
<body>

<header>☕ Kafe Menü</header>

<div class="menu">

  <div class="item">
    <span>Türk Kahvesi</span>
    <span class="price">60₺</span>
  </div>

  <div class="item">
    <span>Latte</span>
    <span class="price">90₺</span>
  </div>

  <div class="item">
    <span>Çay</span>
    <span class="price">20₺</span>
  </div>

  <div class="item">
    <span>Cheesecake</span>
    <span class="price">120₺</span>
  </div>

</div>

</body>
</html>
