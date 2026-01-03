# Tanvir-Vai-2.0
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Tanvir Vai 2.0</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<style>
*{box-sizing:border-box;}
body{
    margin:0;
    font-family:Arial,sans-serif;
    background:#0a0a0a;
    color:white;
    text-align:center;
    overflow-x:hidden;
}

/* ===== TEXT SHADOW RGB ANIMATION ===== */
@keyframes textGlow {
    0%{text-shadow:0 0 5px red,0 0 10px orange,0 0 15px yellow;}
    16%{text-shadow:0 0 5px orange,0 0 10px yellow,0 0 15px lime;}
    33%{text-shadow:0 0 5px yellow,0 0 10px lime,0 0 15px cyan;}
    50%{text-shadow:0 0 5px lime,0 0 10px cyan,0 0 15px blue;}
    66%{text-shadow:0 0 5px cyan,0 0 10px blue,0 0 15px magenta;}
    83%{text-shadow:0 0 5px blue,0 0 10px magenta,0 0 15px red;}
    100%{text-shadow:0 0 5px magenta,0 0 10px red,0 0 15px orange;}
}

.rgb-text{
    animation:textGlow 3s linear infinite;
}

/* ===== TITLE ===== */
h1{
    margin-top:40px;
    font-size:42px;
    letter-spacing:5px;
}
.subtitle{
    opacity:0.85;
    margin-bottom:25px;
}

/* ===== FLOATING CARD ===== */
.container{
    width:90%;
    max-width:460px;
    margin:30px auto;
    padding:26px;
    border-radius:22px;
    background:#0c0c0c;
    transform:perspective(1200px) rotateX(4deg);
    animation:float 3.5s ease-in-out infinite;
    box-shadow:0 0 30px rgba(255,255,255,0.1);
}

@keyframes float{
    0%{transform:perspective(1200px) rotateX(4deg) translateY(0);}
    50%{transform:perspective(1200px) rotateX(4deg) translateY(-12px);}
    100%{transform:perspective(1200px) rotateX(4deg) translateY(0);}
}

/* ===== INFO ROW ===== */
.row{
    display:flex;
    justify-content:space-between;
    padding:10px 0;
    font-size:15px;
    border-bottom:1px solid rgba(255,255,255,0.12);
}
.row:last-child{border-bottom:none;}
.label{
    color:#ff5cff;
}

/* ===== BUTTONS RGB ===== */
.btn{
    width:90%;
    max-width:400px;
    padding:16px;
    margin:18px auto;
    border-radius:50px;
    font-size:18px;
    text-decoration:none;
    display:block;
    color:white;
    background:linear-gradient(90deg, red, orange, yellow, lime, cyan, blue, violet);
    background-size:400% 400%;
    animation:gradientBG 5s ease infinite;
    box-shadow:0 0 20px rgba(255,255,255,0.2);
    transition:transform 0.3s, box-shadow 0.3s;
}
.btn:hover{
    transform:scale(1.08);
    box-shadow:0 0 40px rgba(255,255,255,0.5);
}

@keyframes gradientBG{
    0%{background-position:0% 50%;}
    50%{background-position:100% 50%;}
    100%{background-position:0% 50%;}
}

/* ===== PLAY MUSIC BUTTON ===== */
#playMusicBtn{
    width:90%;
    max-width:400px;
    padding:16px;
    margin:20px auto;
    font-size:18px;
    border:none;
    border-radius:50px;
    color:white;
    background:linear-gradient(90deg, #ff0000, #ff9900, #ffff00, #33cc33, #00ffff, #0066ff, #cc00ff);
    background-size:400% 400%;
    animation:gradientBG 5s ease infinite;
    cursor:pointer;
    box-shadow:0 0 20px rgba(255,255,255,0.2);
    transition:transform 0.3s, box-shadow 0.3s;
}
#playMusicBtn:hover{
    transform:scale(1.08);
    box-shadow:0 0 40px rgba(255,255,255,0.5);
}

/* ===== FOOTER ===== */
.footer{
    margin:35px 0;
    font-size:14px;
    animation:textGlow 4s linear infinite;
}

</style>
</head>

<body>

<h1 class="rgb-text">Tanvit Vai</h1>
<p class="subtitle rgb-text"></p>

<!-- PLAY MUSIC BUTTON -->
<button id="playMusicBtn">🎵 Click to Play Music</button>

<audio id="myAudio" loop>
    <source src="<audio autoplay loop>
    <source src="Sundari_-_Slowed___Reverb___Sanju_Rathod___G-Spark___Lofi___Trending_Song___Hit_Song___Romantic_Song(256k).mp3" type="audio/mpeg">
</audio>
</audio>

<div class="container">
    <div class="title rgb-text">My About 👇</div>

    <div class="row"><div class="label rgb-text">NAME:</div><div class="rgb-text">TANVIR</div></div>
    <div class="row"><div class="label rgb-text">AGE:</div><div class="rgb-text">13-14</div></div>
    <div class="row"><div class="label rgb-text">CLASS:</div><div class="rgb-text">6</div></div>
    <div class="row"><div class="label rgb-text">GROUP:</div><div class="rgb-text">SCIENCE</div></div>
    <div class="row"><div class="label rgb-text">ROLL</div><div class="rgb-text">3</div></div>
    <div class="row"><div class="label rgb-text">RELIGION:</div><div class="rgb-text">ISLAM</div></div>
    <div class="row"><div class="label rgb-text">HOBBY:</div><div class="rgb-text">GAMING</div></div>
    <div class="row"><div class="label rgb-text">COUNTRY:</div><div class="rgb-text">BANGLADESH</div></div>
    <div class="row"><div class="label rgb-text">STATUS:</div><div class="rgb-text">STUDENT</div></div>
    <div class="row"><div class="label rgb-text">FAVOURITE COLOR:</div><div class="rgb-text">RED AND BLACK</div></div>
    <div class="row"><div class="label rgb-text">LOCATION:</div><div class="rgb-text">BANGLADESH</div></div>
    <div class="row"><div class="label rgb-text">FAV GAME:</div><div class="rgb-text">FREE FIRE</div></div>
    <div class="row"><div class="label rgb-text">DEVICE:</div><div class="rgb-text">OPPO A55</div></div>

</div>

<a href="https://www.tiktok.com/@ns.tanvir6" class="btn">🎵 TIKTOK</a>
<a href="https://www.youtube.com/@Sketchware-Master" class="btn">🔺 YOUTUBE</a>
<a href="https://t.me/freepa63" class="btn">✈ TELEGRAM</a>

<div class="footer rgb-text">
    Tanvit Vai 2.0
</div>

<script>
// Toggle Music Play / Pause
const btn = document.getElementById('playMusicBtn');
const audio = document.getElementById('myAudio');

btn.addEventListener('click', function(){
    if(audio.paused){
        audio.play();
        btn.textContent = "⏸️ Click to Pause Music";
    } else {
        audio.pause();
        btn.textContent = "🎵 Click to Play Music";
    }
});
</script>

</body>
</html>
