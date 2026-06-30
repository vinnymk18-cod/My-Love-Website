<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>For My Baby Girl ❤️</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:'Trebuchet MS',sans-serif;
}

body{
    overflow:hidden;
}

.page{
    display:none;
    width:100vw;
    height:100vh;
    background-size:cover;
    background-position:center;
    background-repeat:no-repeat;
    position:absolute;
    top:0;
    left:0;
    justify-content:center;
    align-items:center;
}

.page.active{
    display:flex;
}

.overlay{
    width:100%;
    height:100%;
    background:linear-gradient(rgba(176,145,255,.35),rgba(150,110,255,.45));
    display:flex;
    justify-content:center;
    align-items:center;
}

.card{
    background:rgba(255,255,255,.93);
    padding:40px;
    width:85%;
    max-width:700px;
    border-radius:25px;
    text-align:center;
    box-shadow:0 0 35px rgba(120,0,255,.4);
}

.card h1,.card h2{
    color:#ff4fc3;
    text-shadow:
        0 0 8px #fff,
        0 0 15px #ff7bd8,
        0 0 25px #ff45b5;
    margin-bottom:30px;
}

.buttons{
    display:flex;
    justify-content:space-between;
    margin-top:30px;
}

.right{
    display:flex;
    justify-content:flex-end;
    margin-top:30px;
}

button{
    padding:15px 35px;
    border:none;
    border-radius:40px;
    cursor:pointer;
    font-size:18px;
    font-weight:bold;
    color:white;
    background:linear-gradient(45deg,#9b5cff,#7b68ee,#b36cff);
    box-shadow:0 0 15px rgba(255,255,255,.7);
    transition:.3s;
}

button:hover{
    transform:scale(1.08);
    box-shadow:0 0 25px hotpink;
}
</style>

</head>
<body>

<!-- HOME -->
<div class="page active" id="p1" style="background-image:url('https://images.unsplash.com/photo-1526045612212-70caf35c14df?auto=format&fit=crop&w=1500&q=80');">
<div class="overlay">
<div class="card">
<h1>Hey baby girl 😘❤️</h1>

<div class="buttons">
<button onclick="showPage('decline')">DECLINE💔</button>
<button onclick="showPage('p2')">Hi😊</button>
</div>

</div>
</div>
</div>

<!-- DECLINE -->
<div class="page" id="decline" style="background-image:url('https://images.unsplash.com/photo-1490750967868-88aa4486c946?auto=format&fit=crop&w=1500&q=80');">
<div class="overlay">
<div class="card">
<h1>💔💔💔🥺🥺</h1>

<div class="right">
<button onclick="showPage('p1')">Back</button>
</div>

</div>
</div>
</div>

<!-- PAGE 2 -->
<div class="page" id="p2" style="background-image:url('https://images.unsplash.com/photo-1468327768560-75b778cbb551?auto=format&fit=crop&w=1500&q=80');">
<div class="overlay">
<div class="card">
<h2>I knew you love me🫣</h2>

<div class="right">
<button onclick="showPage('p3')">Of course I do</button>
</div>

</div>
</div>
</div>

<!-- PAGE 3 -->
<div class="page" id="p3" style="background-image:url('https://images.unsplash.com/photo-1455656678494-4d1b5f3e7ad1?auto=format&fit=crop&w=1500&q=80');">
<div class="overlay">
<div class="card">
<h2>Can I tell you something?</h2>

<div class="right">
<button onclick="showPage('p4')">Okay🤗</button>
</div>

</div>
</div>
</div>

<!-- PAGE 4 -->
<div class="page" id="p4" style="background-image:url('https://images.unsplash.com/photo-1441974231531-c6227db76b6e?auto=format&fit=crop&w=1500&q=80');">
<div class="overlay">
<div class="card">
<h2>Remember the first day we physically met?🤔</h2>

<div class="right">
<button onclick="showPage('p5')">What about it?</button>
</div>

</div>
</div>
</div>

<!-- PAGE 5 -->
<div class="page" id="p5" style="background-image:url('https://images.unsplash.com/photo-1501004318641-b39e6451bec6?auto=format&fit=crop&w=1500&q=80');">
<div class="overlay">
<div class="card">
<h2>How I looked at you🫣?</h2>

<div class="right">
<button onclick="showPage('p6')">Mmmh?</button>
</div>

</div>
</div>
</div>

<!-- PAGE 6 -->
<div class="page" id="p6" style="background-image:url('https://images.unsplash.com/photo-1462275646964-a0e3386b89fa?auto=format&fit=crop&w=1500&q=80');">
<div class="overlay">
<div class="card">
<h2>Then you said your legs hurts and I offered you some massages?😊😊</h2>

<div class="right">
<button onclick="showPage('p7')">AND…??</button>
</div>

</div>
</div>
</div>

<!-- PAGE 7 -->
<div class="page" id="p7" style="background-image:url('https://images.unsplash.com/photo-1465146344425-f00d5f5c8f07?auto=format&fit=crop&w=1500&q=80');">
<div class="overlay">
<div class="card">
<h2>You smiled and said you love me❤️🥰</h2>

<div class="right">
<button onclick="showPage('p8')">And ....😂</button>
</div>

</div>
</div>
</div>

<!-- PAGE 8 -->
<div class="page" id="p8" style="background-image:url('https://images.unsplash.com/photo-1473773508845-188df298d2d1?auto=format&fit=crop&w=1500&q=80');">
<div class="overlay">
<div class="card">
<h2>I just realised or maybe I don't remember if I said I love you back😶😶</h2>

<div class="right">
<button onclick="showPage('p9')">...... Continue</button>
</div>

</div>
</div>
</div>

<!-- PAGE 9 -->
<div class="page" id="p9" style="background-image:url('https://images.unsplash.com/photo-1460533893735-45cea2212645?auto=format&fit=crop&w=1500&q=80');">
<div class="overlay">
<div class="card">
<h2>I want to be sure that it doesn't feel unnecessarily intentional not to say it</h2>

<div class="right">
<button onclick="showPage('p10')">So..??</button>
</div>

</div>
</div>
</div>

<!-- FINAL -->
<div class="page" id="p10" style="background-image:url('https://images.unsplash.com/photo-1490750967868-88aa4486c946?auto=format&fit=crop&w=1500&q=80');">
<div class="overlay">
<div class="card">
<h1>I love you🥺😘❤️<br><br>I love you Joy Wamuyu mwihoti ♥️❤️</h1>

<div class="right">
<button onclick="showPage('p1')">Start Again ❤️</button>
</div>

</div>
</div>
</div>

<script>
function showPage(id){
    document.querySelectorAll('.page').forEach(page=>{
        page.classList.remove('active');
    });

    document.getElementById(id).classList.add('active');
}
</script>

</body>
</html>
# My-Love-Website
