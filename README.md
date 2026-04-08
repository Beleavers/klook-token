<!DOCTYPE html>
<html>
<head>
<title>KLOOK Token</title>
<meta name="viewport" content="width=device-width, initial-scale=1">

<style>
body{
  margin:0;
  font-family:Arial;
  background:#000;
  color:#fff;
  text-align:center;
}
h1{color:#00ff88;}
section{padding:80px 20px;}
.btn{
  display:inline-block;
  padding:12px 25px;
  margin:10px;
  background:#00ff88;
  color:#000;
  border-radius:8px;
}
.buy{
  background:#ffcc00;
}
.box{
  background:#071a12;
  padding:20px;
  margin:20px auto;
  max-width:500px;
  border-radius:10px;
}
</style>
</head>

<body>

<section>
  <h1>🐒 KLOOK TOKEN</h1>
  <p>If you buy, you will be a MONKEY like me 🐒🔥</p>

  <a class="btn buy" href="https://pump.tires/token/0x0ef424d3d5d67bd2774b556d138be44e833541ac" target="_blank">
    BUY $KLOOK
  </a>

  <br>

  <a class="btn" href="#details">Token Details</a>
  <a class="btn" href="#community">Join</a>
</section>

<section id="details">
  <h1>Token Details</h1>

  <div class="box">
    <p><b>Name:</b> KLOOK</p>
    <p><b>Ticker:</b> $KLOOK</p>
    <p><b>Contract:</b></p>
    <p id="c">0x0ef424d3d5d67bd2774b556d138be44e833541ac</p>
    <button onclick="copy()">Copy</button>
  </div>
</section>

<section>
  <h1>About</h1>
  <div class="box">
    KLOOK is a fun community token on PulseChain 🐒🔥
  </div>
</section>

<section id="community">
  <h1>Join Community</h1>

  <a class="btn" href="https://t.me/Klook88888">Telegram</a>
  <a class="btn" href="https://discord.gg/WMk7aMzZY">Discord</a>
</section>

<script>
function copy(){
  let text=document.getElementById("c").innerText;
  navigator.clipboard.writeText(text);
  alert("Copied!");
}
</script>

</body>
</html>
