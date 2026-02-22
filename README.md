<!DOCTYPE html>
<html lang="uz">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>YFIX_UZ ULTIMATE PRO</title>

<link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@400;700&display=swap" rel="stylesheet">

<style>
*{margin:0;padding:0;box-sizing:border-box;}
body{
    font-family:'Orbitron',sans-serif;
    background:#0a0a0a;
    color:white;
    overflow-x:hidden;
}
header{
    background:linear-gradient(90deg,#00ffcc,#0066ff);
    padding:25px;
    text-align:center;
    font-size:28px;
    font-weight:bold;
    animation:glow 2s infinite alternate;
}
@keyframes glow{
    from{box-shadow:0 0 10px #00ffcc;}
    to{box-shadow:0 0 25px #0066ff;}
}
nav{
    display:flex;
    justify-content:center;
    gap:20px;
    padding:15px;
    background:#111;
}
nav button{
    padding:10px 20px;
    background:black;
    color:#00ffcc;
    border:2px solid #00ffcc;
    border-radius:8px;
    cursor:pointer;
}
nav button:hover{
    background:#00ffcc;
    color:black;
}
.section{
    display:none;
    padding:40px;
    text-align:center;
}
.active{display:block;}

.card{
    background:#111;
    margin:20px auto;
    padding:20px;
    width:90%;
    max-width:400px;
    border-radius:15px;
    box-shadow:0 0 15px #00ffcc;
    transition:0.3s;
}
.card:hover{
    transform:scale(1.05);
    box-shadow:0 0 25px #0066ff;
}
button.download{
    margin-top:15px;
    padding:10px 20px;
    background:#00ffcc;
    border:none;
    border-radius:8px;
    font-weight:bold;
    cursor:pointer;
}
input{
    padding:10px;
    margin:10px;
    width:250px;
    border-radius:8px;
    border:none;
}
footer{
    background:black;
    padding:20px;
    text-align:center;
    margin-top:40px;
}
</style>
</head>
<body>

<header>
🔥 YFIX_UZ ULTIMATE PRO 🔥
</header>

<nav>
<button onclick="show('home')">Home</button>
<button onclick="show('mods')">Mods</button>
<button onclick="show('skins')">Skins</button>
<button onclick="show('login')">Login</button>
<button onclick="show('admin')">Admin</button>
</nav>

<!-- HOME -->
<div id="home" class="section active">
<h2>Welcome Boss 😎</h2>
<p>Bu YFIX_UZ rasmiy mega Minecraft portali!</p>
</div>

<!-- MODS -->
<div id="mods" class="section">
<h2>🔥 TOP MODLAR</h2>

<div class="card">
<h3>⚡ FPS BOOSTER PRO</h3>
<p>Lagni yo‘q qiladi va FPS oshiradi.</p>
<button class="download" onclick="download()">Download</button>
</div>

<div class="card">
<h3>👑 VIP YFIX_UZ MOD</h3>
<p>Maxsus armor, qilich va kuchli effektlar.</p>
<button class="download" onclick="download()">Download</button>
</div>

</div>

<!-- SKINS -->
<div id="skins" class="section">
<h2>🎭 YFIX_UZ SKINS</h2>

<div class="card">
<h3>🖤 Masked Boss Skin</h3>
<p>Black & White split mask rasmiy skin.</p>
<button class="download" onclick="download()">Download</button>
</div>

</div>

<!-- LOGIN -->
<div id="login" class="section">
<h2>🔐 Login</h2>
<input type="text" placeholder="Username"><br>
<input type="password" placeholder="Password"><br>
<button class="download" onclick="login()">Login</button>
</div>

<!-- ADMIN -->
<div id="admin" class="section">
<h2>🛠 Admin Panel</h2>
<p>Yangi mod qo‘shish:</p>
<input type="text" id="modname" placeholder="Mod nomi">
<br>
<button class="download" onclick="addMod()">Qo‘shish</button>

<div id="newmods"></div>
</div>

<footer>
© 2026 YFIX_UZ | Ultimate Edition
</footer>

<script>
function show(section){
    document.querySelectorAll('.section').forEach(s=>s.classList.remove('active'));
    document.getElementById(section).classList.add('active');
}

function download(){
    alert("🔥 Yuklash boshlandi YFIX_UZ 🔥");
}

function login(){
    alert("Xush kelibsiz Boss 😎");
}

function addMod(){
    let name=document.getElementById("modname").value;
    if(name==="") return;
    let div=document.createElement("div");
    div.className="card";
    div.innerHTML="<h3>"+name+"</h3><p>Yangi qo‘shilgan mod</p>";
    document.getElementById("newmods").appendChild(div);
}
</script>

</body>
</html>
