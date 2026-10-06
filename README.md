# Happy-teachers-day-sir-jonas
Sir can you teach me more about coding
Here is a compact, short version with all core animations and the dedicated greeting for Sir Jonas:
```html
<!DOCTYPE html>
<html>
<head>
<title>Happy Teachers' Day Sir Jonas</title>
<style>
body{background:#fff7ed;font-family:Arial;text-align:center;padding-top:150px;margin:0}
h1{color:#92400e;font-size:42px;animation:pop 1s ease forwards}
p{color:#78350f;font-size:20px;opacity:0;animation:fade 1s ease forwards .8s}
@keyframes pop{from{transform:scale(0);opacity:0}to{transform:scale(1);opacity:1}}
@keyframes fade{to{opacity:1}}
.confetti{position:fixed;width:8px;height:8px;top:-10px;animation:fall 3s linear infinite}
@keyframes fall{to{transform:translateY(105vh) rotate(360deg)}}
</style>
</head>
<body>
<h1>Happy Teachers' Day Sir Jonas 🎉</h1>
<p>Thank you for all your guidance and patience!</p>
<script>for(let i=0;i<30;i++){let c=document.createElement('div');c.className='confetti';c.style.left=Math.random()100+'vw';c.style.background=['#f59e0b','#ef4444','#10b981'][Math.floor(Math.random()3)];c.style.animationDelay=Math.random()3+'s';document.body.appendChild(c)}</script>
</body>
</html>
```
