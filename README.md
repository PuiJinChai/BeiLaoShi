[Y6Lesson2.html](https://github.com/user-attachments/files/22995574/Y6Lesson2.html)# BeiLaoShi
Bandar Chung Hwa Upper Primary 6 Chinese Vocabulary. Help students prepare for spelling and study independently without parental assistance.
汶莱中华中学 高小组华文 听写巩固练习[Y6Lesson1.html](https://github.com/user-attachments/files/22995571/Y6Lesson1.html)
<!DOCTYPE html>
<html lang="zh">
<head>
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width,initial-scale=1.0"/>
<title>第一课 一道成语题｜听写生词字卡</title>
<style>
:root{
  --bg1: #e8f9e9;
  --bg2: #f6fff6;
  --card-bg-front: #e6fff1;
  --card-bg-back: #ffffff;
  --accent: #2e5f49;
  --btn-bg: #1e90ff;
  --btn-text: #fff;
}
*{box-sizing:border-box}
html,body{
  height:100%;
  margin:0;
  font-family: "PingFang SC","Hiragino Sans GB","Helvetica Neue","Microsoft YaHei","Arial", sans-serif;
  background: linear-gradient(180deg,var(--bg1),var(--bg2));
  color: #233;
}
.header{
  background:#b8e4c9;
  color:var(--accent);
  text-align:center;
  padding:14px 12px;
  font-size:18px;
  box-shadow:0 2px 6px rgba(0,0,0,0.08);
  font-weight:600;
}
.wrapper{
  min-height: calc(100vh - 140px);
  display:flex;
  align-items:center;
  justify-content:center;
  padding:16px;
  padding-bottom:140px;
}
.card-area{
  width:92%;
  max-width:460px;
  display:flex;
  justify-content:center;
  align-items:center;
}
.card{
  width:100%;
  max-width:420px;
  height:320px;
  perspective:1200px;
  position:relative;
  user-select:none;
}
.inner{
  width:100%;
  height:100%;
  position:relative;
  transition: transform 0.75s cubic-bezier(.2,.9,.3,1);
  transform-style: preserve-3d;
}
.card.flipped .inner{
  transform: rotateY(180deg) scale(1.05);
}
.card.flip-animate{
  animation: bounceFlip 0.4s ease;
}
@keyframes bounceFlip{
  0% {transform: scale(1);}
  50% {transform: scale(1.08);}
  100% {transform: scale(1);}
}
.face{
  position:absolute;
  inset:0;
  border-radius:20px;
  box-shadow: 0 8px 20px rgba(0,0,0,0.12);
  display:flex;
  flex-direction:column;
  align-items:center;
  justify-content:center;
  padding:18px;
  backface-visibility: hidden;
  -webkit-backface-visibility: hidden;
  overflow:hidden;
}
.front{
  background: var(--card-bg-front);
}
.back{
  background: var(--card-bg-back);
  transform: rotateY(180deg);
}
.pinyin{
  font-size:48px;
  line-height:1.0;
  color:#2a9d66;
  letter-spacing:2px;
  text-align:center;
  word-break:break-word;
  padding:6px 8px;
  font-weight:600;
}
.speaker-btn{
  margin-top:10px;
  background:transparent;
  border:none;
  width:44px;
  height:44px;
  display:inline-flex;
  align-items:center;
  justify-content:center;
  border-radius:50%;
  cursor:pointer;
}
.speaker-btn:active{transform:scale(0.98)}
.speaker-icon{
  width:26px;height:26px;
  fill: #1e90ff;
}
.lesson{
  position:absolute;
  right:14px;
  bottom:12px;
  font-size:13px;
  color:#666;
}
.word{
  font-family: "KaiTi","SimKai","楷体", serif;
  font-size:34px;
  color:#111;
  margin-bottom:6px;
  text-align:center;
  word-break:break-word;
}
.meaning{
  font-size:20px;
  color:green;
  margin-bottom:10px;
  text-align:center;
}
.sentence{
  font-family:"KaiTi","SimKai","楷体",serif;
  font-size:17px;
  color:#333;
  text-align:center;
  padding:0 8px;
  line-height:1.35;
}
.sentence .speak-inline{
  margin-left:8px;
  vertical-align:middle;
}
.translation{
  margin-top:6px;
  font-size:15px;
  color:#555;
  text-align:center;
}
.nav{
  position:fixed;
  left:0;
  right:0;
  bottom:18px;
  display:flex;
  flex-direction:column;
  justify-content:center;
  pointer-events: auto;
}
.nav-inner{
  display:flex;
  gap:20px;
  align-items:center;
  justify-content:center;
  background:rgba(255,255,255,0.0);
  padding:6px 12px;
}
.nav button{
  background:var(--btn-bg);
  color:var(--btn-text);
  border:none;
  padding:12px 22px;
  border-radius:12px;
  font-size:16px;
  box-shadow:0 6px 16px rgba(30,144,255,0.18);
  cursor:pointer;
}
.nav button:active{transform:translateY(1px)}
.counter{
  margin-top:6px;
  text-align:center;
  font-size:13px;
  color:#444;
}
.dots span{
  display:inline-block;
  width:10px;
  height:10px;
  margin:0 4px;
  border-radius:50%;
  background:#c0c0c0;
  transition:all 0.3s;
}
.dots span.active{
  background:#1e90ff;
  transform:scale(1.3);
}
@media(max-width:420px){
  .card { height:360px; border-radius:18px; }
  .pinyin { font-size:54px; }
  .word { font-size:36px; }
  .meaning { font-size:18px; }
  .sentence { font-size:18px; }
  .nav button { padding:12px 18px; font-size:17px; border-radius:14px; }
  .header { font-size:16px; padding:12px 8px; }
  .dots span { width:12px; height:12px; margin:0 3px; }
}
</style>
</head>
<body>
<div class="header">第一课 一道成语题｜听写生词字卡</div>
<div class="wrapper">
  <div class="card-area" aria-live="polite">
    <div class="card" id="card" role="button" aria-pressed="false" tabindex="0" aria-label="单张字卡，点击翻面">
      <div class="inner" id="inner"></div>
    </div>
  </div>
</div>

<div class="nav" role="navigation" aria-label="卡片导航">
  <div class="nav-inner">
    <button id="prevBtn" aria-label="上一页">⬅ 上一张</button>
    <div class="counter" id="counter">1 / 19</div>
    <button id="nextBtn" aria-label="下一页">下一张 ➡</button>
  </div>
  <div class="dots" id="dotsContainer"></div>
</div>

<script>
const words = [
{word:"绞尽脑汁", pinyin:"jiǎo jìn nǎo zhī", meaning:"rack one's brain", sentence:"他为了想出一个好办法，绞尽脑汁。", en:"He racked his brain to find a good idea."},
{word:"了解", pinyin:"liǎo jiě", meaning:"understand", sentence:"我了解老师的意思。", en:"I understand what the teacher means."},
{word:"掌握", pinyin:"zhǎng wò", meaning:"grasp", sentence:"他已经掌握了新的知识。", en:"He has mastered the new knowledge."},
{word:"情况", pinyin:"qíng kuàng", meaning:"situation", sentence:"做决定前，我们要先了解情况。", en:"Before making a decision, we must first understand the situation."},
{word:"课外", pinyin:"kè wài", meaning:"extracurricular", sentence:"我喜欢参加课外活动。", en:"I like to join extracurricular activities."},
{word:"材料", pinyin:"cái liào", meaning:"materials", sentence:"老师给了我们新的学习材料。", en:"The teacher gave us new study materials."},
{word:"挑选", pinyin:"tiāo xuǎn", meaning:"choose", sentence:"妈妈帮我挑选了一本好书。", en:"Mom helped me choose a good book."},
{word:"恰当", pinyin:"qià dàng", meaning:"proper / suitable", sentence:"你用的词很恰当。", en:"The word you used is very suitable."},
{word:"平时", pinyin:"píng shí", meaning:"usually", sentence:"他平时很早起床。", en:"He usually gets up early."},
{word:"原汁原味", pinyin:"yuán zhī yuán wèi", meaning:"authentic", sentence:"我喜欢妈妈做的菜，很原汁原味。", en:"I like the dishes my mother makes; they are authentic."},
{word:"自信", pinyin:"zì xìn", meaning:"self-confidence", sentence:"她说话很有自信。", en:"She speaks with confidence."},
{word:"自然而然", pinyin:"zì rán ér rán", meaning:"naturally", sentence:"我们一起学习，自然而然成了朋友。", en:"We studied together and naturally became friends."},
{word:"结束", pinyin:"jié shù", meaning:"the end / finish", sentence:"篮球比赛结束了。", en:"The basketball game is over."},
{word:"试卷", pinyin:"shì juàn", meaning:"examination paper", sentence:"我把试卷交给老师了。", en:"I handed my exam paper to the teacher."},
{word:"正确", pinyin:"zhèng què", meaning:"correct", sentence:"你的答案是正确的。", en:"Your answer is correct."},
{word:"答案", pinyin:"dá àn", meaning:"answer", sentence:"我知道这个问题的答案。", en:"I know the answer to this question."},
{word:"新鲜", pinyin:"xīn xiān", meaning:"fresh", sentence:"这些水果很新鲜。", en:"These fruits are very fresh."},
{word:"快人快语", pinyin:"kuài rén kuài yǔ", meaning:"outspoken person", sentence:"在会议上，他快人快语地说出了自己的想法。", en:"At the meeting, he spoke out his ideas directly."},
{word:"不假思索", pinyin:"bù jiǎ sī suǒ", meaning:"without thinking", sentence:"他不假思索地回答了老师的问题。", en:"He answered the teacher's question without thinking."}
];

const inner = document.getElementById('inner');
const cardEl = document.getElementById('card');
const prevBtn = document.getElementById('prevBtn');
const nextBtn = document.getElementById('nextBtn');
const counter = document.getElementById('counter');
const dotsContainer = document.getElementById('dotsContainer');

let current = 0;
let isBack = false;

function renderCard(i){
  const w = words[i];
  counter.textContent = `${i+1} / ${words.length}`;
  inner.innerHTML = `
    <div class="face front" data-face="front">
      <div class="pinyin" id="pinyinText">${w.pinyin}</div>
      <button class="speaker-btn" id="pinyinSpeak" aria-label="播放中文读音">
        <svg class="speaker-icon" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
          <path d="M3 10v4h4l5 4V6L7 10H3z"></path>
        </svg>
      </button>
      <div class="lesson">第一课 一道成语题 (${i+1}/19)</div>
    </div>
    <div class="face back" data-face="back">
      <div class="word">${w.word}</div>
      <div class="meaning">${w.meaning}</div>
      <div class="sentence">
        <span id="sentenceText">${w.sentence}</span>
        <button class="speaker-btn speak-inline" id="sentenceSpeak" aria-label="播放造句">
          <svg class="speaker-icon" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
            <path d="M3 10v4h4l5 4V6L7 10H3z"></path>
          </svg>
        </button>
      </div>
      <div class="translation">${w.en}</div>
    </div>
  `;
  cardEl.classList.remove('flipped');
  isBack = false;

  const pSpeak = document.getElementById('pinyinSpeak');
  const sSpeak = document.getElementById('sentenceSpeak');
  if(pSpeak) pSpeak.addEventListener('click', (e)=>{
    e.stopPropagation();
    playChineseText(w.word, 0.5);
  });
  if(sSpeak) sSpeak.addEventListener('click', (e)=>{
    e.stopPropagation();
    playChineseText(w.sentence, 0.6);
  });
}

function playChineseText(text, rate=0.6){
  if(!('speechSynthesis' in window)) return alert('您的浏览器不支持语音合成，请使用新版浏览器播放。');
  window.speechSynthesis.cancel();
  const u = new SpeechSynthesisUtterance(text);
  u.lang = 'zh-CN';
  u.rate = rate;
  window.speechSynthesis.speak(u);
}

function playFlipSound(){
  try{
    const ctx = new (window.AudioContext||window.webkitAudioContext)();
    const buffer = ctx.createBuffer(1, ctx.sampleRate*0.08, ctx.sampleRate);
    const data = buffer.getChannelData(0);
    for(let i=0;i<data.length;i++){
      const env=Math.pow(1-i/data.length,2.2);
      data[i]=(Math.random()*2-1)*0.15*env;
    }
    const source = ctx.createBufferSource();
    source.buffer=buffer;
    const filter = ctx.createBiquadFilter();
    filter.type='highpass';
    filter.frequency.value=1000;
    const gain=ctx.createGain();
    gain.gain.value=0.9;
    source.connect(filter).connect(gain).connect(ctx.destination);
    source.start(0);
    source.stop(ctx.currentTime+0.09);
  }catch(e){console.warn(e);}
}

cardEl.addEventListener('click', function(e){
  if(e.target.closest('button') || e.target.tagName === 'BUTTON' || e.target.closest('svg')) return;
  toggleFlip();
});
cardEl.addEventListener('keydown', (e)=>{
  if(e.key === 'Enter' || e.key === ' ') { e.preventDefault(); toggleFlip(); }
});
function toggleFlip(){
  playFlipSound();
  cardEl.classList.add('flip-animate');
  setTimeout(()=> cardEl.classList.remove('flip-animate'),400);
  cardEl.classList.toggle('flipped');
  isBack = !isBack;
}

function goTo(index){
  if(index<0) index=words.length-1;
  if(index>=words.length) index=0;
  current=index;
  cardEl.classList.add('flip-animate');
  setTimeout(()=>{
    renderCard(current);
    cardEl.classList.remove('flip-animate');
  },300);
  updateDots();
}

prevBtn.addEventListener('click', ()=>{ goTo(current-1); });
nextBtn.addEventListener('click', ()=>{ goTo(current+1); });
window.addEventListener('keydown', (e)=>{
  if(e.key==='ArrowRight') goTo(current+1);
  if(e.key==='ArrowLeft') goTo(current-1);
});
prevBtn.addEventListener('click',(e)=>{e.stopPropagation();});
nextBtn.addEventListener('click',(e)=>{e.stopPropagation();});

function renderDots(){
  dotsContainer.innerHTML='';
  for(let i=0;i<words.length;i++){
    const span=document.createElement('span');
    if(i===current) span.classList.add('active');
    dotsContainer.appendChild(span);
  }
}
function updateDots(){
  const spans=dotsContainer.querySelectorAll('span');
  spans.forEach((s,i)=> s.classList.toggle('active', i===current));
}

renderCard(current);
renderDots();
updateDots();
</script>
</body>
</html>

[Up<!DOCTYPE html>
<html lang="zh">
<head>
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width,initial-scale=1.0"/>
<title>第二课 戴花脸的乐趣｜听写生词字卡</title>
<style>
:root{
  --bg1: #e8f9e9;
  --bg2: #f6fff6;
  --card-bg-front: #e6fff1;
  --card-bg-back: #ffffff;
  --accent: #2e5f49;
  --btn-bg: #1e90ff;
  --btn-text: #fff;
}
*{box-sizing:border-box}
html,body{
  height:100%;
  margin:0;
  font-family: "PingFang SC","Hiragino Sans GB","Helvetica Neue","Microsoft YaHei","Arial", sans-serif;
  background: linear-gradient(180deg,var(--bg1),var(--bg2));
  color: #233;
}
.header{
  background:#b8e4c9;
  color:var(--accent);
  text-align:center;
  padding:14px 12px;
  font-size:18px;
  box-shadow:0 2px 6px rgba(0,0,0,0.08);
  font-weight:600;
}
.wrapper{
  min-height: calc(100vh - 140px);
  display:flex;
  align-items:center;
  justify-content:center;
  padding:16px;
  padding-bottom:140px;
}
.card-area{
  width:92%;
  max-width:460px;
  display:flex;
  justify-content:center;
  align-items:center;
}
.card{
  width:100%;
  max-width:420px;
  height:320px;
  perspective:1200px;
  position:relative;
  user-select:none;
}
.inner{
  width:100%;
  height:100%;
  position:relative;
  transition: transform 0.75s cubic-bezier(.2,.9,.3,1);
  transform-style: preserve-3d;
}
.card.flipped .inner{
  transform: rotateY(180deg) scale(1.05);
}
.card.flip-animate{
  animation: bounceFlip 0.4s ease;
}
@keyframes bounceFlip{
  0% {transform: scale(1);}
  50% {transform: scale(1.08);}
  100% {transform: scale(1);}
}
.face{
  position:absolute;
  inset:0;
  border-radius:20px;
  box-shadow: 0 8px 20px rgba(0,0,0,0.12);
  display:flex;
  flex-direction:column;
  align-items:center;
  justify-content:center;
  padding:18px;
  backface-visibility: hidden;
  -webkit-backface-visibility: hidden;
  overflow:hidden;
}
.front{
  background: var(--card-bg-front);
}
.back{
  background: var(--card-bg-back);
  transform: rotateY(180deg);
}
.pinyin{
  font-size:48px;
  line-height:1.0;
  color:#2a9d66;
  letter-spacing:2px;
  text-align:center;
  word-break:break-word;
  padding:6px 8px;
  font-weight:600;
}
.speaker-btn{
  margin-top:10px;
  background:transparent;
  border:none;
  width:44px;
  height:44px;
  display:inline-flex;
  align-items:center;
  justify-content:center;
  border-radius:50%;
  cursor:pointer;
}
.speaker-btn:active{transform:scale(0.98)}
.speaker-icon{
  width:26px;height:26px;
  fill: #1e90ff;
}
.lesson{
  position:absolute;
  right:14px;
  bottom:12px;
  font-size:13px;
  color:#666;
}
.word{
  font-family: "KaiTi","SimKai","楷体", serif;
  font-size:34px;
  color:#111;
  margin-bottom:6px;
  text-align:center;
  word-break:break-word;
}
.meaning{
  font-size:20px;
  color:green;
  margin-bottom:10px;
  text-align:center;
}
.sentence{
  font-family:"KaiTi","SimKai","楷体",serif;
  font-size:17px;
  color:#333;
  text-align:center;
  padding:0 8px;
  line-height:1.35;
}
.sentence .speak-inline{
  margin-left:8px;
  vertical-align:middle;
}
.translation{
  margin-top:6px;
  font-size:15px;
  color:#555;
  text-align:center;
}
.nav{
  position:fixed;
  left:0;
  right:0;
  bottom:18px;
  display:flex;
  flex-direction:column;
  justify-content:center;
  pointer-events: auto;
}
.nav-inner{
  display:flex;
  gap:20px;
  align-items:center;
  justify-content:center;
  background:rgba(255,255,255,0.0);
  padding:6px 12px;
}
.nav button{
  background:var(--btn-bg);
  color:var(--btn-text);
  border:none;
  padding:12px 22px;
  border-radius:12px;
  font-size:16px;
  box-shadow:0 6px 16px rgba(30,144,255,0.18);
  cursor:pointer;
}
.nav button:active{transform:translateY(1px)}
.counter{
  margin-top:6px;
  text-align:center;
  font-size:13px;
  color:#444;
}
.dots span{
  display:inline-block;
  width:10px;
  height:10px;
  margin:0 4px;
  border-radius:50%;
  background:#c0c0c0;
  transition:all 0.3s;
}
.dots span.active{
  background:#1e90ff;
  transform:scale(1.3);
}
@media(max-width:420px){
  .card { height:360px; border-radius:18px; }
  .pinyin { font-size:54px; }
  .word { font-size:36px; }
  .meaning { font-size:18px; }
  .sentence { font-size:18px; }
  .nav button { padding:12px 18px; font-size:17px; border-radius:14px; }
  .header { font-size:16px; padding:12px 8px; }
  .dots span { width:12px; height:12px; margin:0 3px; }
}
</style>
</head>
<body>
<div class="header">第二课 戴花脸的乐趣｜听写生词字卡</div>
<div class="wrapper">
  <div class="card-area" aria-live="polite">
    <div class="card" id="card" role="button" aria-pressed="false" tabindex="0" aria-label="单张字卡，点击翻面">
      <div class="inner" id="inner"></div>
    </div>
  </div>
</div>

<div class="nav" role="navigation" aria-label="卡片导航">
  <div class="nav-inner">
    <button id="prevBtn" aria-label="上一页">⬅ 上一张</button>
    <div class="counter" id="counter">1 / 16</div>
    <button id="nextBtn" aria-label="下一页">下一张 ➡</button>
  </div>
  <div class="dots" id="dotsContainer"></div>
</div>

<script>
const words = [
{word:"春节", pinyin:"chūn jié", meaning:"Chinese New Year", sentence:"我们非常期待春节到来。", en:"We are really looking forward to Chinese New Year."},
{word:"年货", pinyin:"nián huò", meaning:"goods for Chinese New Year", sentence:"妈妈买了很多年货准备过年。", en:"Mom bought many goods for Chinese New Year."},
{word:"惊喜", pinyin:"jīng xǐ", meaning:"surprise/pleasant surprise", sentence:"今天是小明的生日，我们要给他一个惊喜！", en:"Today is Xiaoming's birthday, we are going to give him a surprise!"},
{word:"与众不同", pinyin:"yǔ zhòng bù tóng", meaning:"out of the ordinary", sentence:"她的衣服很与众不同。", en:"Her clothes are out of the ordinary."},
{word:"咄咄逼人", pinyin:"duō duō bī rén", meaning:"aggressive (in words)", sentence:"他的态度有点咄咄逼人。", en:"His attitude is a bit aggressive."},
{word:"爱不释手", pinyin:"ài bú shì shǒu", meaning:"love something too much to part with it", sentence:"这个玩具让我爱不释手。", en:"I love this toy too much to put it down."},
{word:"主角", pinyin:"zhǔ jué", meaning:"main character/leading role", sentence:"她在话剧里是主角。", en:"She is the main character in the play."},
{word:"全副武装", pinyin:"quán fù wǔ zhuāng", meaning:"full armor/be fully armed", sentence:"士兵全副武装出发了。", en:"The soldiers set off fully armed."},
{word:"羡慕", pinyin:"xiàn mù", meaning:"envy", sentence:"我很羡慕他的画画能力。", en:"I envy his drawing skills."},
{word:"摇晃", pinyin:"yáo huàng", meaning:"shake", sentence:"那棵树在风中摇晃。", en:"The tree is shaking in the wind."},
{word:"肩膀", pinyin:"jiān bǎng", meaning:"shoulder", sentence:"他拍拍我的肩膀说：“别放弃！”", en:"He patted my shoulder and said: 'Don't give up!'"},
{word:"拜年", pinyin:"bài nián", meaning:"make/pay a New Year visit", sentence:"我们去爷爷家拜年。", en:"We went to Grandpa's house to pay a New Year visit."},
{word:"衣服", pinyin:"yī fu", meaning:"clothes", sentence:"她的新衣服很漂亮。", en:"Her new clothes are very beautiful."},
{word:"哄堂大笑", pinyin:"hōng táng dà xiào", meaning:"the whole room bursting into laughter", sentence:"老师讲笑话时，大家哄堂大笑。", en:"Everyone burst into laughter when the teacher told a joke."},
{word:"神气", pinyin:"shén qì", meaning:"energetic", sentence:"弟弟穿着童军制服，看起来很神气。", en:"My little brother looks very energetic in his scout uniform."},
{word:"张牙舞爪", pinyin:"zhāng yá wǔ zhǎo", meaning:"be fierce-looking", sentence:"小猫看到老鼠便张牙舞爪地扑了过去。", en:"The kitten saw the mouse and pounced fiercely."}
];

const inner = document.getElementById('inner');
const cardEl = document.getElementById('card');
const prevBtn = document.getElementById('prevBtn');
const nextBtn = document.getElementById('nextBtn');
const counter = document.getElementById('counter');
const dotsContainer = document.getElementById('dotsContainer');

let current = 0;
let isBack = false;

function renderCard(i){
  const w = words[i];
  counter.textContent = `${i+1} / ${words.length}`;
  inner.innerHTML = `
    <div class="face front" data-face="front">
      <div class="pinyin" id="pinyinText">${w.pinyin}</div>
      <button class="speaker-btn" id="pinyinSpeak" aria-label="播放中文读音">
        <svg class="speaker-icon" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
          <path d="M3 10v4h4l5 4V6L7 10H3z"></path>
        </svg>
      </button>
      <div class="lesson">第二课 戴花脸的乐趣 (${i+1}/${words.length})</div>
    </div>
    <div class="face back" data-face="back">
      <div class="word">${w.word}</div>
      <div class="meaning">${w.meaning}</div>
      <div class="sentence">
        <span id="sentenceText">${w.sentence}</span>
        <button class="speaker-btn speak-inline" id="sentenceSpeak" aria-label="播放造句">
          <svg class="speaker-icon" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
            <path d="M3 10v4h4l5 4V6L7 10H3z"></path>
          </svg>
        </button>
      </div>
      <div class="translation">${w.en}</div>
    </div>
  `;
  cardEl.classList.remove('flipped');
  isBack = false;

  const pSpeak = document.getElementById('pinyinSpeak');
  const sSpeak = document.getElementById('sentenceSpeak');
  if(pSpeak) pSpeak.addEventListener('click', (e)=>{
    e.stopPropagation();
    playChineseText(w.word, 0.5);
  });
  if(sSpeak) sSpeak.addEventListener('click', (e)=>{
    e.stopPropagation();
    playChineseText(w.sentence, 0.6);
  });
}

function playChineseText(text, rate=0.6){
  if(!('speechSynthesis' in window)) return alert('您的浏览器不支持语音合成，请使用新版浏览器播放。');
  window.speechSynthesis.cancel();
  const u = new SpeechSynthesisUtterance(text);
  u.lang = 'zh-CN';
  u.rate = rate;
  window.speechSynthesis.speak(u);
}

function playFlipSound(){
  try{
    const ctx = new (window.AudioContext||window.webkitAudioContext)();
    const buffer = ctx.createBuffer(1, ctx.sampleRate*0.08, ctx.sampleRate);
    const data = buffer.getChannelData(0);
    for(let i=0;i<data.length;i++){
      const env=Math.pow(1-i/data.length,2.2);
      data[i]=(Math.random()*2-1)*0.15*env;
    }
    const source = ctx.createBufferSource();
    source.buffer=buffer;
    const filter = ctx.createBiquadFilter();
    filter.type='highpass';
    filter.frequency.value=1000;
    const gain=ctx.createGain();
    gain.gain.value=0.9;
    source.connect(filter).connect(gain).connect(ctx.destination);
    source.start(0);
    source.stop(ctx.currentTime+0.09);
  }catch(e){console.warn(e);}
}

cardEl.addEventListener('click', function(e){
  if(e.target.closest('button') || e.target.tagName === 'BUTTON' || e.target.closest('svg')) return;
  toggleFlip();
});
cardEl.addEventListener('keydown', (e)=>{
  if(e.key === 'Enter' || e.key === ' ') { e.preventDefault(); toggleFlip(); }
});
function toggleFlip(){
  playFlipSound();
  cardEl.classList.add('flip-animate');
  setTimeout(()=> cardEl.classList.remove('flip-animate'),400);
  cardEl.classList.toggle('flipped');
  isBack = !isBack;
}

function goTo(index){
  if(index<0) index=words.length-1;
  if(index>=words.length) index=0;
  current=index;
  cardEl.classList.add('flip-animate');
  setTimeout(()=>{
    renderCard(current);
    cardEl.classList.remove('flip-animate');
  },300);
  updateDots();
}

prevBtn.addEventListener('click', ()=>{ goTo(current-1); });
nextBtn.addEventListener('click', ()=>{ goTo(current+1); });
window.addEventListener('keydown', (e)=>{
  if(e.key==='ArrowRight') goTo(current+1);
  if(e.key==='ArrowLeft') goTo(current-1);
});
prevBtn.addEventListener('click',(e)=>{e.stopPropagation();});
nextBtn.addEventListener('click',(e)=>{e.stopPropagation();});

function renderDots(){
  dotsContainer.innerHTML='';
  for(let i=0;i<words.length;i++){
    const span=document.createElement('span');
    if(i===current) span.classList.add('active');
    dotsContainer.appendChild(span);
  }
}
function updateDots(){
  const spans=dotsContainer.querySelectorAll('span');
  spans.forEach((s,i)=> s.classList.toggle('active', i===current));
}

renderCard(current);
renderDots();
updateDots();
</script>
</body>
</html>
loading Y6Lesson2.html…]()

[Y6Lesson3.html](https://github.com/user-attachments/files/22995575/Y6Lesson3.html)
<!DOCTYPE html>
<html lang="zh">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>第三课 火烧云｜听写生词字卡</title>
<style>
:root{
  --bg1: #e8f9e9;
  --bg2: #f6fff6;
  --card-bg-front: #e6fff1;
  --card-bg-back: #ffffff;
  --btn-bg: #1e90ff;
  --btn-text: #fff;
}
*{box-sizing:border-box;}
html,body{margin:0;height:100%;font-family:"PingFang SC","Hiragino Sans GB","Microsoft YaHei",sans-serif;background:linear-gradient(180deg,var(--bg1),var(--bg2));color:#233;}
.header{text-align:center;padding:14px 12px;font-size:18px;background:#b8e4c9;font-weight:600;box-shadow:0 2px 6px rgba(0,0,0,0.08);}
.wrapper{min-height:calc(100vh - 140px);display:flex;align-items:center;justify-content:center;padding:16px;padding-bottom:140px;}
.card-area{width:92%;max-width:460px;display:flex;justify-content:center;align-items:center;}
.card{width:100%;max-width:420px;height:320px;perspective:1200px;position:relative;user-select:none;}
.inner{width:100%;height:100%;position:relative;transition:transform 0.75s cubic-bezier(.2,.9,.3,1);transform-style: preserve-3d;}
.card.flipped .inner{transform: rotateY(180deg) scale(1.05);}
.face{position:absolute;inset:0;border-radius:20px;box-shadow:0 8px 20px rgba(0,0,0,0.12);display:flex;flex-direction:column;align-items:center;justify-content:center;padding:18px;backface-visibility:hidden;-webkit-backface-visibility:hidden;overflow:hidden;}
.front{background: var(--card-bg-front);}
.back{background: var(--card-bg-back);transform: rotateY(180deg);}
.pinyin{font-size:48px;line-height:1.0;color:#2a9d66;letter-spacing:2px;text-align:center;word-break:break-word;padding:6px 8px;font-weight:600;}
.speaker-btn{margin-top:10px;background:transparent;border:none;width:44px;height:44px;display:inline-flex;align-items:center;justify-content:center;border-radius:50%;cursor:pointer;}
.speaker-btn:active{transform:scale(0.98);}
.speaker-icon{width:26px;height:26px;fill: #1e90ff;}
.lesson{position:absolute;right:14px;bottom:12px;font-size:13px;color:#666;}
.word{font-family:"KaiTi","SimKai","楷体";font-size:34px;color:#111;margin-bottom:6px;text-align:center;word-break:break-word;}
.meaning{font-size:20px;color:green;margin-bottom:10px;text-align:center;}
.sentence{font-family:"KaiTi","SimKai","楷体";font-size:17px;color:#333;text-align:center;padding:0 8px;line-height:1.35;}
.sentence .speak-inline{margin-left:8px;vertical-align:middle;}
.translation{margin-top:6px;font-size:15px;color:#555;text-align:center;}
.nav{position:fixed;left:0;right:0;bottom:18px;display:flex;flex-direction:column;justify-content:center;pointer-events: auto;}
.nav-inner{display:flex;gap:20px;align-items:center;justify-content:center;background:rgba(255,255,255,0.0);padding:6px 12px;}
.nav button{background:var(--btn-bg);color:var(--btn-text);border:none;padding:12px 22px;border-radius:12px;font-size:16px;box-shadow:0 6px 16px rgba(30,144,255,0.18);cursor:pointer;}
.nav button:active{transform:translateY(1px);}
.counter{margin-top:6px;text-align:center;font-size:13px;color:#444;}
.dots span{display:inline-block;width:10px;height:10px;margin:0 4px;border-radius:50%;background:#c0c0c0;transition:all 0.3s;}
.dots span.active{background:#1e90ff;transform:scale(1.3);}
@media(max-width:420px){
  .card { height:360px; border-radius:18px; }
  .pinyin { font-size:54px; }
  .word { font-size:36px; }
  .meaning { font-size:18px; }
  .sentence { font-size:18px; }
  .nav button { padding:12px 18px; font-size:17px; border-radius:14px; }
  .dots span { width:12px; height:12px; margin:0 3px; }
  .header { font-size:16px; padding:12px 8px; }
}
</style>
</head>
<body>
<div class="header">第三课 火烧云｜听写生词字卡</div>
<div class="wrapper">
  <div class="card-area" aria-live="polite">
    <div class="card" id="card" role="button" aria-pressed="false" tabindex="0" aria-label="单张字卡">
      <div class="inner" id="inner"></div>
    </div>
  </div>
</div>
<div class="nav" role="navigation" aria-label="卡片导航">
  <div class="nav-inner">
    <button id="prevBtn" aria-label="上一页">⬅ 上一张</button>
    <div class="counter" id="counter">1 / 19</div>
    <button id="nextBtn" aria-label="下一页">下一张 ➡</button>
  </div>
  <div class="dots" id="dotsContainer"></div>
</div>

<script>
const words=[
{word:"火烧云", pinyin:"huǒ shāo yún", meaning:"evening fiery clouds", sentence:"傍晚的天空出现了美丽的火烧云。", en:"Beautiful fiery clouds appeared in the evening sky."},
{word:"胡子", pinyin:"hú zi", meaning:"mustache", sentence:"爷爷的胡子很长。", en:"Grandpa's mustache is very long."},
{word:"笑眯眯", pinyin:"xiào mī mī", meaning:"smiling", sentence:"奶奶笑眯眯地看着我。", en:"Grandma looked at me with a smiling face."},
{word:"红彤彤", pinyin:"hóng tóng tóng", meaning:"bright red", sentence:"苹果红彤彤的，很好看。", en:"The apple is bright red and very pretty."},
{word:"寺庙", pinyin:"sì miào", meaning:"temple", sentence:"我们去寺庙参观。", en:"We visited the temple."},
{word:"一模一样", pinyin:"yì mú yí yàng", meaning:"exactly the same", sentence:"他们穿了一模一样的衣服。", en:"They wore exactly the same clothes."},
{word:"模糊", pinyin:"mó hu", meaning:"not clear", sentence:"远处的山看起来很模糊。", en:"The mountains in the distance look unclear."},
{word:"等待", pinyin:"děng dài", meaning:"waiting", sentence:"我们在车站等待巴士。", en:"We are waiting for the bus at the station."},
{word:"福如东海寿比南山", pinyin:"fú rú dōnghǎi shòu bǐ nánshān", meaning:"long life and boundless happiness", sentence:"我们祝爷爷福如东海，寿比南山。", en:"We wish Grandpa long life and boundless happiness."},
{word:"惊奇", pinyin:"jīng qí", meaning:"surprised/amazed", sentence:"小朋友对魔术表演感到惊奇。", en:"The kids were amazed by the magic show."},
{word:"好像", pinyin:"hǎo xiàng", meaning:"seem/be like", sentence:"天空好像下雨了。", en:"It seems like it's going to rain."},
{word:"颜色", pinyin:"yán sè", meaning:"colour", sentence:"这幅画的颜色很漂亮。", en:"The colors in this painting are very beautiful."},
{word:"寻找", pinyin:"xún zhǎo", meaning:"look for", sentence:"小猫在寻找它的尾巴。", en:"The kitten is looking for its tail."},
{word:"尾巴", pinyin:"wěi bā", meaning:"tail", sentence:"小狗的尾巴摇来摇去。", en:"The puppy's tail is wagging."},
{word:"脖子", pinyin:"bó zi", meaning:"neck", sentence:"她脖子上戴着一条项链。", en:"She is wearing a necklace on her neck."},
{word:"偏偏", pinyin:"piān piān", meaning:"against all odds", sentence:"下雨了，我偏偏忘了带雨伞。", en:"It rained, and against all odds, I forgot to bring my umbrella."},
{word:"镇静", pinyin:"zhèn jìng", meaning:"calm", sentence:"遇到问题时，他很镇静。", en:"He stays calm when facing problems."},
{word:"似乎", pinyin:"sì hū", meaning:"seems like/as if", sentence:"他似乎不太舒服，脸色有些苍白。", en:"He seems unwell; his face looks a bit pale."},
{word:"从天而降", pinyin:"cóng tiān ér jiàng", meaning:"come down from the sky", sentence:"看着从天而降的雨水，他突然有了灵感。", en:"Watching the rain come down from the sky, he suddenly got an idea."}
];

let currentIndex=0;
const card=document.getElementById("card");
const inner=document.getElementById("inner");
const counter=document.getElementById("counter");
const dotsContainer=document.getElementById("dotsContainer");

function renderCard(){
  const w=words[currentIndex];
  inner.innerHTML=`
    <div class="face front">
      <div class="pinyin">${w.pinyin}</div>
      <button class="speaker-btn" onclick="speakPinyin('${w.word}', event)">
        <svg class="speaker-icon" viewBox="0 0 24 24"><path d="M5 9v6h4l5 5V4l-5 5H5z"/></svg>
      </button>
      <div class="lesson">第三课 火烧云</div>
    </div>
    <div class="face back">
      <div class="word">${w.word}</div>
      <div class="meaning">${w.meaning}</div>
      <div class="sentence">${w.sentence}<button class="speaker-btn speak-inline" onclick="speakSentence('${w.sentence}', event)">
        <svg class="speaker-icon" viewBox="0 0 24 24"><path d="M5 9v6h4l5 5V4l-5 5H5z"/></svg>
      </button></div>
      <div class="translation">${w.en}</div>
      <div class="lesson">第三课 火烧云</div>
    </div>
  `;
  updateCounter();
}

function updateCounter(){
  counter.textContent=`${currentIndex+1} / ${words.length}`;
  dotsContainer.innerHTML=words.map((_,i)=>`<span class="${i===currentIndex?'active':''}"></span>`).join('');
}

function nextCard(){currentIndex=(currentIndex+1)%words.length;renderCard();}
function prevCard(){currentIndex=(currentIndex-1+words.length)%words.length;renderCard();}
document.getElementById("nextBtn").addEventListener("click",nextCard);
document.getElementById("prevBtn").addEventListener("click",prevCard);

// 点击空白翻面
card.addEventListener("click",(e)=>{
  if(!e.target.closest(".speaker-btn")){
    card.classList.toggle("flipped");
  }
});

// 播放拼音中文朗读
function speakPinyin(text,event){
  if(event) event.stopPropagation();
  const utter=new SpeechSynthesisUtterance(text);
  utter.lang="zh-CN";utter.rate=0.5;speechSynthesis.speak(utter);
}

// 播放造句中文朗读
function speakSentence(text,event){
  if(event) event.stopPropagation();
  const utter=new SpeechSynthesisUtterance(text);
  utter.lang="zh-CN";utter.rate=0.6;speechSynthesis.speak(utter);
}

renderCard();
</script>
</body>
</html>
