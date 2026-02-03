Index.html
<html lang="en">
<head>
<meta charset="UTF-8">
<title>For Prachi ❤️</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<style>
body{
  margin:0;
  font-family: Arial, sans-serif;
  background: linear-gradient(135deg,#ff9a9e,#fad0c4);
  display:flex;
  justify-content:center;
  align-items:center;
  height:100vh;
}
.card{
  background:white;
  padding:30px 25px;
  border-radius:18px;
  text-align:center;
  max-width:320px;
  box-shadow:0 10px 30px rgba(0,0,0,0.2);
}
h1{
  color:#e91e63;
  margin-bottom:10px;
}
p{
  color:#444;
  font-size:16px;
}
.heart{
  font-size:50px;
  animation:beat 1s infinite;
}
@keyframes beat{
  0%,100%{transform:scale(1);}
  50%{transform:scale(1.3);}
}
button{
  margin-top:15px;
  padding:12px 18px;
  border:none;
  border-radius:25px;
  background:#e91e63;
  color:white;
  font-size:16px;
  cursor:pointer;
}
button:hover{
  background:#d81b60;
}
#msg{
  margin-top:15px;
  font-weight:bold;
  color:#e91e63;
  display:none;
}
</style>
</head>
<body>

<div class="card">
  <div class="heart">❤️</div>
  <h1>Hi Prachi</h1>
  <p>
    From the first time I talked to you,  
    something felt special.
  </p>
  <p>
    I just wanted to ask you one simple thing…
  </p>

  <button onclick="showMsg()">Will you be my Valentine?</button>

  <div id="msg">
    You just made my day, Prachi 💖  
    – Ayush
  </div>
</div>

<script>
function showMsg(){
  document.getElementById("msg").style.display="block";
}
</script>

</body>
</html> 
￼