<!DOCTYPE html>
<html lang="vi">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Website Xịn Của Minh</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:'Segoe UI',sans-serif;
}

body{
    background:linear-gradient(135deg,#667eea,#764ba2);
    color:white;
    transition:0.4s;
}

.dark{
    background:#111;
}

header{
    padding:60px 20px;
    text-align:center;
    animation:fadeIn 1.5s ease-in-out;
}

h1{
    font-size:3rem;
}

p{
    opacity:0.9;
}

.btn{
    margin-top:20px;
    padding:12px 25px;
    border:none;
    border-radius:30px;
    background:white;
    color:#333;
    font-weight:bold;
    cursor:pointer;
    transition:0.3s;
}

.btn:hover{
    transform:scale(1.1);
    background:#ffcc00;
}

section{
    padding:60px 20px;
    text-align:center;
}

.card{
    background:rgba(255,255,255,0.1);
    backdrop-filter:blur(10px);
    padding:30px;
    border-radius:20px;
    max-width:400px;
    margin:20px auto;
    transition:0.3s;
}

.card:hover{
    transform:translateY(-10px);
}

.toggle{
    position:fixed;
    top:20px;
    right:20px;
    background:black;
    color:white;
    border:none;
    padding:10px 15px;
    border-radius:20px;
    cursor:pointer;
}

footer{
    padding:20px;
    text-align:center;
    opacity:0.8;
}

@keyframes fadeIn{
    from{opacity:0; transform:translateY(-20px);}
    to{opacity:1; transform:translateY(0);}
}
</style>
</head>

<body>

<button class="toggle" onclick="toggleDark()">Dark Mode</button>

<header>
    <h1>Xin Chào, Tôi Là Minh 🚀</h1>
    <p>Website cá nhân xịn sò của tôi</p>
    <button class="btn" onclick="alert('Cảm ơn bạn đã ghé thăm 😎')">Khám Phá</button>
</header>

<section>
    <div class="card">
        <h2>Về Tôi</h2>
        <p>Tôi đang học lập trình web và đây là phiên bản nâng cấp của trang web đầu tiên.</p>
    </div>

    <div class="card">
        <h2>Kỹ Năng</h2>
        <p>HTML • CSS • JavaScript</p>
    </div>
</section>

<footer>
    © 2026 Minh | Designed with 🔥
</footer>

<script>
function toggleDark(){
    document.body.classList.toggle("dark");
}
</script>

</body>
</html>
