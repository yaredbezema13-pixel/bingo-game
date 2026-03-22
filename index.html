<<!DOCTYPE html>
<html lang="am">
<head>
<meta charset="UTF-8">
<title>🇪🇹 ኢትዮጵያዊ ቢንጎ 🎱</title>
<style>
body { text-align:center; font-family:Arial; background:#111; color:white;}
h1{margin-top:15px; color:#ffed4a;}
#number{font-size:60px; margin:15px; color:#22c55e;}
.board{display:grid; grid-template-columns:repeat(5,60px); gap:8px; justify-content:center; margin-top:15px;}
.cell{width:60px; height:60px; background:#1e293b; display:flex; align-items:center; justify-content:center; border-radius:10px; font-weight:bold;}
.marked{background:linear-gradient(45deg,#22c55e,#facc15,#ef4444); color:black; font-weight:bold;}
button, select{padding:8px; margin:4px; border-radius:8px; border:none;}
button{background:#22c55e; color:white; cursor:pointer;}
</style>
</head>
<body>

<h1>🇪🇹 ኢትዮጵያዊ ቢንጎ</h1>

<div id="number">--</div>

<button onclick="startGame()">▶ ጀምር (ድምፅ ON)</button>
<button onclick="drawNumber()">⏺ ቁጥር ማውጣት</button>
<button onclick="startAuto()">▶ ራሱ ይወጣ (Auto Draw)</button>
<button onclick="stopAuto()">⏹ ማቆም</button>

<br>

<select id="speed">
  <option value="3000">3 ሰከንድ</option>
  <option value="5000" selected>5 ሰከንድ</option>
  <option value="8000">8 ሰከንድ</option>
</select>

<button onclick="generateBoard()">🔄 አዲስ ካርድ</button>

<div class="board" id="board"></div>

<audio id="bgMusic" loop>
  <source src="https://www.soundhelix.com/examples/mp3/SoundHelix-Song-1.mp3" type="audio/mpeg">
</audio>

<script>
let usedNumbers = [];
let autoInterval = null;
let soundEnabled = false;

function startGame(){
  soundEnabled = true;
  document.getElementById("bgMusic").play().catch(()=>{});
  drawNumber(); 
}

function toAmharic(num){
  const ones=["","አንድ","ሁለት","ሶስት","አራት","አምስት","ስድስት","ሰባት","ስምንት","ዘጠኝ"];
  const tens=["","አስር","ሃያ","ሰላሳ","አርባ","ሃምሳ","ስልሳ","ሰባ","ሰማንያ","ዘጠና"];
  if(num<10) return ones[num];
  if(num<20) return "አስራ "+ones[num-10];
  let t=Math.floor(num/10);
  let o=num%10;
  return o===0?tens[t]:tens[t]+" "+ones[o];
}

function speak(letter,num){
  if(!soundEnabled) return;
  let text = letter + " ... " + toAmharic(num);
  let url = "https://translate.google.com/translate_tts?ie=UTF-8&q=" + encodeURIComponent(text) + "&tl=am&client=tw-ob";
  let audio = new Audio(url);
  audio.play();
}

function getLetter(num){
  if(num<=15) return "B";
  if(num<=30) return "I";
  if(num<=45) return "N";
  if(num<=60) return "G";
  return "O";
}

function generateBoard(){
  usedNumbers=[];
  let board=document.getElementById("board");
  board.innerHTML="";
  let nums = [];
  while(nums.length<25){
    let n=Math.floor(Math.random()*75)+1;
    if(!nums.includes(n)) nums.push(n);
  }
  nums.forEach(num=>{
    let div=document.createElement("div");
    div.className="cell";
    div.innerText=num;
    div.id="cell-"+num;
    board.appendChild(div);
  });
}

function drawNumber(){
  if(usedNumbers.length>=75){ alert("🎉 ጨዋታ ተጠናቀቀ!"); stopAuto(); return; }
  let num;
  do{ num=Math.floor(Math.random()*75)+1; } while(usedNumbers.includes(num));
  usedNumbers.push(num);
  let letter=getLetter(num);
  document.getElementById("number").innerText=letter+" "+num;
  speak(letter,num);
  let cell=document.getElementById("cell-"+num);
  if(cell) cell.classList.add("marked");
  checkBingo();
}

function startAuto(){
  let speed=document.getElementById("speed").value;
  stopAuto();
  autoInterval=setInterval(drawNumber, speed);
}
function stopAuto(){ clearInterval(autoInterval); }

function checkBingo(){
  let board = [];
  let allCells = document.querySelectorAll(".board .cell");
  for(let i=0;i<5;i++){
    board[i]=[];
    for(let j=0;j<5;j++){
      board[i][j] = allCells[i*5+j].classList.contains("marked")?1:0;
    }
  }
  for(let i=0;i<5;i++) if(board[i].reduce((a,b)=>a+b,0)==5){ alert("🎉 Bingo! መስመር ሙሉ ተሞላ!"); return true; }
  for(let j=0;j<5;j++) if(board.reduce((sum,row)=>sum+row[j],0)==5){ alert("🎉 Bingo! አንድ መስመር ሙሉ ተሞላ!"); return true; }
  if(board.reduce((sum,row,i)=>sum+row[i],0)==5 || board.reduce((sum,row,i)=>sum+row[4-i],0)==5){ alert("🎉 Bingo! አንድ diagonal ሙሉ ተሞላ!"); return true; }
  return false;
}

generateBoard();
</script>
</body>
</html>DOCTYPE html>

<html>
<head>
  <meta http-equiv="CONTENT-TYPE" content="text/html; charset=UTF-8">
  <title>Hello, World!</title>
</head>
<body>
  <h1>
    Hello, World!
  </h1>
</body>
</html>
https://t.me/bulehorabingo_bot
