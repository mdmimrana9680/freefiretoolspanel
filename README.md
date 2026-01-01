<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Demo Wallet UI</title>
<style>
body{margin:0;font-family:sans-serif;background:#f5f7fa;}
.header{padding:20px;}
.balance{font-size:40px;font-weight:bold;}
.sub{color:#00b894;}
.buttons{display:flex;gap:10px;margin-top:10px;}
.btn{flex:1;padding:12px;border-radius:20px;background:#00c2ff;color:#fff;text-align:center;}
.card{background:#fff;border-radius:16px;padding:15px;margin:15px;}
.row{display:flex;justify-content:space-between;padding:10px 0;border-bottom:1px solid #eee;}
.footer{position:fixed;bottom:0;width:100%;background:#fff;display:flex;justify-content:space-around;padding:10px 0;border-top:1px solid #ddd;}
.tab{color:#888;}
.active{color:#000;font-weight:bold;}
</style>
</head>
<body>

<div class="header">
  <div>My wallet</div>
  <div class="balance">$0.11</div>
  <div class="sub">+0.40% Today</div>

  <div class="buttons">
    <div class="btn">Send</div>
    <div class="btn">Receive</div>
    <div class="btn">History</div>
    <div class="btn">More</div>
  </div>
</div>

<div class="card">
  <div style="font-weight:bold;margin-bottom:10px;">Tokens</div>
  <div class="row"><span>BNB</span><span>0.0001</span></div>
  <div class="row"><span>ETH</span><span>0.0000</span></div>
  <div class="row"><span>USDT</span><span>0.00</span></div>
  <div class="row"><span>USDC</span><span>0.00</span></div>
</div>

<div class="card">
  <div class="btn" style="margin-bottom:10px;">Create New Wallet</div>
  <div class="row" style="font-size:12px;">0x21811049eD82433500e9583934213CD003258fA6</div>
  <div class="row" style="font-size:12px;">0x3af75462f3bc767c5a6321a9ca86d7596433e192302923bc2e</div>
</div>

<div class="footer">
  <div class="tab active">Home</div>
  <div class="tab">Markets</div>
  <div class="tab">Trade</div>
  <div class="tab">Discover</div>
  <div class="tab">Wallet</div>
</div>

</body>
</html>
