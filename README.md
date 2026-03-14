<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Happy Birthday Meena 💖</title>

<style>
body{
margin:0;
font-family:'Comic Sans MS',cursive;
text-align:center;
color:white;
background:linear-gradient(45deg,#ff9a9e,#fad0c4,#ffdde1);
background-size:400% 400%;
animation:bg 10s infinite alternate;
}

@keyframes bg{
0%{background-position:left;}
100%{background-position:right;}
}

h1{
margin-top:40px;
font-size:40px;
animation:glow 2s infinite alternate;
}

@keyframes glow{
from{text-shadow:0 0 10px white;}
to{text-shadow:0 0 25px pink;}
}

.message{
padding:20px;
font-size:20px;
}

.cat-container{
display:flex;
flex-wrap:wrap;
justify-content:center;
}

.cat{
width:180px;
border-radius:20px;
margin:10px;
transition:0.5s;
}

.cat:hover{
transform:scale(1.1) rotate(5deg);
}

.heart{
font-size:35px;
animation:float 3s infinite;
}

@keyframes float{
0%{transform:translateY(0);}
50%{transform:translateY(-15px);}
100%{transform:translateY(0);}
}

/* popup */
.popup{
position:fixed;
top:50%;
left:50%;
transform:translate(-50%,-50%);
background:white;
color:#ff4d6d;
padding:25px;
border-radius:15px;
box-shadow:0 0 20px rgba(0,0,0,0.3);
display:none;
z-index:10;
}

.popup button{
margin-top:10px;
padding:8px 15px;
border:none;
background:#ff4d6d;
color:white;
border-radius:10px;
cursor:pointer;
}

footer{
margin:30px;
}
</style>
</head>

<body>

<h1>🎉 Happy Birthday MEENA 🎉</h1>

<div class="heart">💖 🐾 💖</div>

<p class="message">
Happy Birthday to the sweetest girl, <b>MEENA</b> 💖<br><br>
May your life be filled with happiness, love, and lots of cute cats 🐱✨<br>
You are special and you deserve all the joy in the world 🌸
</p>

<div class="cat-container">
<img class="cat" src="https://cdn.discordapp.com/attachments/1136284054833086504/1482260428582158376/da77d9abc83c947fbe9b7340864ec0e3.jpg?ex=69b64e19&is=69b4fc99&hm=1bdd5fbe750ef2b56a34b01b5f494a9d185c943456b4787a7ab3a221fed074e4&">
<img class="cat" src="https://cdn.discordapp.com/attachments/1136284054833086504/1482260435976851516/d7e2c2576131eda7ca73a8599f48d29a.jpg?ex=69b64e1b&is=69b4fc9b&hm=ed3b6fb2896344ffad1a443c989762580f6665fc2415f8afa3a0dc256e4b0189&">
<img class="cat" src="https://cdn.discordapp.com/attachments/1136284054833086504/1482260451139260496/a7a180e8c8f2979245d3df096a235263.jpg?ex=69b64e1e&is=69b4fc9e&hm=7e0dfbaacaf830f03064cb308297bd3d1863ef053d6b7d62d526ddec95d221da&">
<img class="cat" src="https://cdn.discordapp.com/attachments/1136284054833086504/1482260444088635422/e65045afce69bb4e072f1b370d1fc4bb.jpg?ex=69b64e1c&is=69b4fc9c&hm=4b65706e4a753b71cb75f7fc80f7dc627cae16464867be5495d30b20916f12d0&">
</div>

<footer>
Made with ❤️ for Meena
</footer>

<!-- popup -->
<div class="popup" id="lovePopup">
<h2>💌 A Message for Meena</h2>
<p>
Meena, you make life brighter and happier.  
I wish you endless smiles and beautiful moments.  
Happy Birthday 💖
</p>
<button onclick="closePopup()">Thank You ❤️</button>
</div>

<!-- music -->
<audio autoplay loop>
<source src="https://cdn.pixabay.com/download/audio/2022/03/15/audio_5f33c5f4b3.mp3?filename=happy-birthday-royalty-free-music-112194.mp3" type="audio/mpeg">
</audio>

<!-- confetti -->
<script src="https://cdn.jsdelivr.net/npm/canvas-confetti@1.6.0/dist/confetti.browser.min.js"></script>

<script>
window.onload = function() {

document.getElementById("lovePopup").style.display="block";

setInterval(()=>{

confetti({
particleCount:150,
spread:90,
origin:{y:0.6}
});

},3000);

}

function closePopup(){
document.getElementById("lovePopup").style.display="none";
}
</script>

</body>
</html>
