<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>YFIX_UZ | Minecraft Mods & Skins</title>

<style>
body{
margin:0;
font-family:Arial, sans-serif;
background:linear-gradient(135deg,#0f0f0f,#1a1a1a,#000000);
color:white;
text-align:center;
}

header{
padding:40px;
font-size:40px;
font-weight:bold;
background:linear-gradient(90deg,green,lime);
-webkit-background-clip:text;
color:transparent;
animation:glow 2s infinite alternate;
}

@keyframes glow{
from{ text-shadow:0 0 10px lime;}
to{ text-shadow:0 0 30px green;}
}

.section{
padding:40px;
}

.card{
background:#111;
margin:20px auto;
padding:20px;
width:80%;
border-radius:15px;
box-shadow:0 0 15px green;
transition:0.3s;
}

.card:hover{
transform:scale(1.05);
box-shadow:0 0 25px lime;
}

button{
padding:15px 30px;
background:green;
border:none;
color:white;
font-size:18px;
border-radius:10px;
cursor:pointer;
transition:0.3s;
}

button:hover{
background:lime;
color:black;
}

footer{
padding:20px;
background:black;
margin-top:40px;
font-size:14px;
color:gray;
}
</style>

<script>
function downloadMod(mod){
alert("🔥 " + mod + " downloaded successfully! 🔥");
}

function proMode(){
alert("🚀 YFIX_UZ PRO MODE ACTIVATED 🚀");
}
</script>

</head>
<body>

<header>YFIX_UZ OFFICIAL MINECRAFT HUB</header>

<div class="section">
<h2>🔥 Exclusive Mods</h2>

<div class="card">
<h3>Ultra FPS Booster Mod</h3>
<p>This mod increases FPS dramatically, reduces lag and makes gameplay smooth even on low-end devices.</p>
<button onclick="downloadMod('Ultra FPS Booster Mod')">Download</button>
</div>

<div class="card">
<h3>Shadow Power Shader Lite</h3>
<p>Beautiful lighting, realistic shadows and optimized performance for 4GB devices.</p>
<button onclick="downloadMod('Shadow Power Shader Lite')">Download</button>
</div>

<div class="card">
<h3>YFIX_UZ PvP Enhancer</h3>
<p>Improves combat animations, faster hit response and clean PvP experience.</p>
<button onclick="downloadMod('YFIX_UZ PvP Enhancer')">Download</button>
</div>

</div>

<div class="section">
<h2>🧑‍🎮 Premium Skins</h2>

<div class="card">
<h3>YFIX_UZ Shadow Suit</h3>
<p>Black and white split mask skin with premium suit design. Legendary style.</p>
<button onclick="downloadMod('YFIX_UZ Shadow Suit Skin')">Download</button>
</div>

<div class="card">
<h3>Neon Hacker Skin</h3>
<p>Green neon lines with futuristic hacker look.</p>
<button onclick="downloadMod('Neon Hacker Skin')">Download</button>
</div>

</div>

<div class="section">
<h2>🚀 Activate Pro Mode</h2>
<p>Unlock secret animations and hidden features!</p>
<button onclick="proMode()">Activate PRO</button>
</div>

<footer>
© 2026 YFIX_UZ Official Minecraft Mods & Skins Website. All rights reserved.
</footer>

</body>
</html>
