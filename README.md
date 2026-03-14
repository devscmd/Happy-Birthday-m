<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Happy Birthday Meena ❤️</title>
<style>

body{
    margin:0;
    font-family: 'Segoe UI', sans-serif;
    background: linear-gradient(270deg,#ff9a9e,#fad0c4,#fbc2eb,#a6c1ee);
    background-size: 800% 800%;
    animation: gradientMove 10s ease infinite;
    text-align:center;
    color:white;
}

@keyframes gradientMove{
    0%{background-position:0% 50%;}
    50%{background-position:100% 50%;}
    100%{background-position:0% 50%;}
}

.container{
    padding:40px;
}

h1{
    font-size:50px;
    animation: glow 2s infinite alternate;
}

@keyframes glow{
    from{ text-shadow:0 0 10px white;}
    to{ text-shadow:0 0 25px pink;}
}

.message{
    font-size:22px;
    max-width:700px;
    margin:auto;
    margin-top:20px;
}

.cats{
    margin-top:40px;
}

.cats img{
    width:150px;
    border-radius:20px;
    margin:10px;
    transition:0.4s;
}

.cats img:hover{
    transform:scale(1.2) rotate(5deg);
}

.footer{
    margin-top:40px;
    font-size:18px;
}

.heart{
    animation: heartbeat 1s infinite;
}

@keyframes heartbeat{
    0%{transform:scale(1);}
    50%{transform:scale(1.2);}
    100%{transform:scale(1);}
}

</style>
</head>

<body>

<div class="container">

<h1>🎉 Happy Birthday Meena 🎉</h1>

<div class="message">
<p>
Dear <b>Meena</b>,  
On your special day I wish you happiness, love, success, and endless smiles.  
May your life be filled with beautiful moments and dreams come true.  

You are amazing and deserve all the happiness in the world. ✨
</p>

<p class="heart">🤍 Sending you lots of love and blessings 🤍</p>
</div>

<div class="cats">
<h2>🐱 Cute Cats for You 🐱</h2>

<img src="https://cataas.com/cat">
<img src="https://cataas.com/cat/sleepy">
<img src="https://cataas.com/cat/cute">
<img src="https://cataas.com/cat/playful">

</div>

<div class="footer">
<p>Made with love by someone who cares about you 💖</p>
</div>

</div>

</body>
</html>
