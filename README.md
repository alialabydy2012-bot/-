<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>متجر عليوه العبيدي</title>

<style>
body{
    margin:0;
    font-family:Arial;
    background:linear-gradient(135deg,#0f172a,#1e293b);
    color:white;
}

header{
    padding:20px;
    text-align:center;
    font-size:24px;
    font-weight:bold;
    background:#111827;
}

.container{
    max-width:400px;
    margin:30px auto;
    background:#1f2937;
    padding:20px;
    border-radius:15px;
    box-shadow:0 0 20px rgba(0,255,150,0.3);
}

input, select{
    width:100%;
    padding:10px;
    margin:8px 0;
    border-radius:8px;
    border:none;
    font-size:14px;
}

button{
    width:100%;
    padding:12px;
    background:#00ff99;
    border:none;
    border-radius:10px;
    font-size:16px;
    font-weight:bold;
    cursor:pointer;
}

button:hover{
    background:#00cc77;
}

footer{
    text-align:center;
    margin-top:20px;
    padding:15px;
    font-size:13px;
    opacity:0.7;
}
</style>
</head>

<body>

<header>
🔥 متجر عليوه العبيدي 🔥
</header>

<div class="container">

<h3>طلب خدمة</h3>

<select id="service">
<option>رشق متابعين</option>
<option>لايكات</option>
<option>مشاهدات</option>
<option>شحن ألعاب</option>
</select>

<input type="text" id="link" placeholder="حط رابط الحساب أو الفيديو">

<input type="number" id="qty" placeholder="اكتب الكمية">

<button onclick="sendOrder()">إرسال الطلب</button>

</div>

<footer>
© 2026 جميع الحقوق محفوظة | متجر عليوه العبيدي
</footer>

<script>
function sendOrder(){
let service=document.getElementById("service").value;
let link=document.getElementById("link").value;
let qty=document.getElementById("qty").value;

let message="طلب جديد:%0Aالخدمة: "+service+"%0Aالرابط: "+link+"%0Aالكمية: "+qty;

window.location.href="https://wa.me/218930674822?text="+message;
}
</script>

</body>
</html>
echo "# -" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/alialabydy2012-bot/-.git
git push -u origin main
