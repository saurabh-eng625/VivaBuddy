<!DOCTYPE html>
<html lang="en"><head><meta charset="UTF-8"><meta name="viewport" content="width=device-width, initial-scale=1"><title>VivaBuddy | Your Personal Viva Practice Partner</title>
<link rel="preconnect" href="https://fonts.googleapis.com"><link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600&family=Poppins:wght@600;700&family=Noto+Sans+Devanagari:wght@400;600&display=swap" rel="stylesheet">
<style>
:root{color-scheme:dark;--navy:#101827;--blue:#2563EB;--pur:#8B5CF6;--teal:#14B8A6;--w:#F8FAFC;--mute:#9aa7bd;--glass:rgba(255,255,255,.06);--gb:rgba(255,255,255,.13);--H:"Poppins","Inter",system-ui,sans-serif;--B:"Inter","Noto Sans Devanagari",system-ui,sans-serif}
{box-sizing:border-box}html{scroll-behavior:smooth}
body{margin:0;background:var(--navy);color:var(--w);font:400 16px/1.6 var(--B);overflow-x:hidden}
.bg{position:fixed;inset:0;z-index:-1;overflow:hidden;background:radial-gradient(900px 600px at 85% -10%,rgba(37,99,235,.28),transparent 60%),radial-gradient(700px 500px at 0% 35%,rgba(139,92,246,.22),transparent 60%),var(--navy)}
.bg i{position:absolute;border-radius:50%;filter:blur(80px);opacity:.3;animation:fl 18s ease-in-out infinite alternate}
.bg i:nth-child(1){width:340px;height:340px;background:var(--blue);left:-90px;top:20%}.bg i:nth-child(2){width:300px;height:300px;background:var(--pur);right:-70px;top:55%;animation-delay:-7s}.bg i:nth-child(3){width:240px;height:240px;background:var(--teal);left:42%;bottom:-110px;animation-delay:-12s}
.bg:after{content:"";position:absolute;inset:0;background-image:linear-gradient(rgba(255,255,255,.035) 1px,transparent 1px),linear-gradient(90deg,rgba(255,255,255,.035) 1px,transparent 1px);background-size:56px 56px;-webkit-mask-image:radial-gradient(circle at 50% 25%,#000,transparent 75%);mask-image:radial-gradient(circle at 50% 25%,#000,transparent 75%)}
@keyframes fl{to{transform:translate(40px,-50px) scale(1.15)}}
.top{position:sticky;top:0;z-index:20;-webkit-backdrop-filter:blur(14px);backdrop-filter:blur(14px);background:rgba(16,24,39,.72);border-bottom:1px solid var(--gb)}
.top>div{max-width:1100px;margin:auto;padding:12px 20px;display:flex;align-items:center;gap:22px}
.logo{display:flex;align-items:center;gap:10px;font:700 20px var(--H);cursor:pointer}
.logo i{display:grid;place-items:center;width:36px;height:36px;border-radius:11px;background:linear-gradient(135deg,var(--blue),var(--pur));font-style:normal;font-size:19px}
.lnk{color:var(--mute);font:500 14px var(--B);cursor:pointer;transition:color .2s}.lnk:hover{color:var(--w)}.sp{flex:1}
main{max-width:1100px;margin:0 auto;padding:20px 20px 80px}.nw{max-width:780px;margin:0 auto}
.g{background:var(--glass);border:1px solid var(--gb);border-radius:20px;-webkit-backdrop-filter:blur(14px);backdrop-filter:blur(14px);box-shadow:0 24px 50px -32px #000;padding:24px;margin-bottom:16px;transition:transform .25s,border-color .25s}
.lift:hover{transform:translateY(-4px);border-color:rgba(139,92,246,.55)}
button{font:600 15px var(--B);color:var(--w);background:var(--glass);border:1px solid var(--gb);padding:11px 20px;border-radius:12px;cursor:pointer;transition:transform .2s,box-shadow .2s,background .2s}
button:hover{transform:translateY(-2px);background:rgba(255,255,255,.11)}button:focus-visible,textarea:focus-visible{outline:2px solid var(--teal);outline-offset:2px}
button.pri{background:linear-gradient(135deg,var(--blue),var(--pur));border:0;box-shadow:0 12px 30px -12px rgba(37,99,235,.9)}button.pri:hover{box-shadow:0 16px 36px -10px rgba(139,92,246,.9)}
button.tl{background:rgba(20,184,166,.14);border-color:rgba(20,184,166,.5);color:#5eead4}
button:disabled{opacity:.55;cursor:not-allowed;transform:none}button.rec{background:rgba(244,63,94,.18);border-color:#f43f5e;color:#fda4af}
.row{display:flex;gap:10px;flex-wrap:wrap;align-items:center;margin-top:14px}.nav{display:flex;justify-content:space-between;gap:10px;flex-wrap:wrap;margin-top:6px}
.hint{font-size:13px;color:var(--mute)}.hidden{display:none!important}
h1.t,h2.t{font:700 clamp(26px,4.5vw,36px)/1.15 var(--H);margin:6px 0 8px;letter-spacing:-.5px}p.lead{color:var(--mute);margin:0 0 20px}
.slide{display:none}.slide.active{display:block;animation:inn .45s ease}@keyframes inn{from{opacity:0;transform:translateY(16px)}to{opacity:1;transform:none}}
.rv{opacity:0;transform:translateY(22px);transition:opacity .7s,transform .7s}.rv.in{opacity:1;transform:none}
.hero{display:grid;grid-template-columns:1.1fr .9fr;gap:40px;align-items:center;padding:46px 0 24px}
.pill{display:inline-block;background:rgba(139,92,246,.16);border:1px solid rgba(139,92,246,.45);color:#c4b5fd;padding:6px 14px;border-radius:99px;font:600 13px var(--B)}
.hero h1{font:700 clamp(34px,6vw,58px)/1.08 var(--H);letter-spacing:-1.5px;margin:18px 0 10px}
.ln{display:block;overflow:hidden}.ln span{display:block;animation:up .9s cubic-bezier(.2,.8,.2,1) both}@keyframes up{from{transform:translateY(110%)}to{transform:none}}
.grad{background:linear-gradient(90deg,#60a5fa,#a78bfa,#2dd4bf);-webkit-background-clip:text;background-clip:text;color:transparent}
.hero h2{font:600 clamp(18px,2.5vw,24px) var(--H);margin:0 0 12px;color:#dbe4f5}.hero p{color:var(--mute);font-size:17px;max-width:520px}
.sub{margin-top:18px;font:500 14px var(--B);color:#7dd3c8}
.prev{position:relative;animation:flt 6s ease-in-out infinite alternate}@keyframes flt{to{transform:translateY(-12px)}}
.av{display:inline-grid;place-items:center;width:42px;height:42px;border-radius:50%;background:linear-gradient(135deg,var(--blue),var(--pur));font-size:20px}
.ph{display:flex;align-items:center;gap:12px}.ph small{display:block;color:var(--mute);font-size:12px}
.pq{font:600 20px/1.4 var(--H);margin:16px 0}
.fch{position:absolute;background:rgba(16,24,39,.9);border:1px solid var(--gb);border-radius:12px;padding:7px 12px;font:600 13px var(--B);animation:flt 5s ease-in-out infinite alternate}
.feat,.how{display:grid;grid-template-columns:repeat(3,1fr);gap:16px}.sec{padding:46px 0 10px;scroll-margin-top:76px}
.ic{display:grid;place-items:center;width:46px;height:46px;border-radius:14px;font-size:22px;margin-bottom:12px;background:linear-gradient(135deg,rgba(37,99,235,.35),rgba(139,92,246,.35));border:1px solid var(--gb)}
.feat h3,.how h3{font:600 17px var(--H);margin:0 0 6px}.feat p,.how p{margin:0;color:var(--mute);font-size:14.5px}
.num{font:700 30px var(--H);background:linear-gradient(90deg,var(--blue),var(--teal));-webkit-background-clip:text;background-clip:text;color:transparent}
#dots{display:flex;justify-content:center;gap:10px;margin:6px 0 22px}#dots i{flex:0 0 64px;height:6px;border-radius:6px;background:rgba(255,255,255,.14);position:relative;transition:.3s}#dots i:first-child{display:none}
#dots i:after{content:attr(data-l);position:absolute;top:10px;left:0;right:0;text-align:center;font:500 11px var(--B);color:var(--mute);font-style:normal}
#dots i.on{background:linear-gradient(90deg,var(--blue),var(--pur))}#dots i.done{background:var(--teal)}
#drop{border:2px dashed rgba(255,255,255,.25);border-radius:18px;padding:34px 18px;text-align:center;cursor:pointer;transition:.2s;background:rgba(255,255,255,.03)}#drop:hover,#drop.over{border-color:var(--teal);background:rgba(20,184,166,.08)}
#drop .big{font-size:38px}#drop b{display:block;font:600 17px var(--H);margin:6px 0 2px}
#fileCard{display:flex;gap:14px;align-items:center;border:1px solid var(--gb);border-radius:16px;padding:14px;background:rgba(255,255,255,.04)}#fileCard.ok{border-color:rgba(20,184,166,.6)}#fileCard>div{flex:1;min-width:0}
#fName{font-weight:600;overflow:hidden;text-overflow:ellipsis;white-space:nowrap;display:block}.pb{height:8px;background:rgba(255,255,255,.12);border-radius:8px;overflow:hidden;margin:8px 0 4px}.pb i{display:block;height:100%;width:0;border-radius:8px;background:linear-gradient(90deg,var(--blue),var(--teal));transition:width .3s}
label,.lbl{font:600 14px var(--B);display:block;margin-bottom:8px;color:#dbe4f5}
textarea{width:100%;border:1px solid var(--gb);border-radius:14px;padding:14px;font:400 16px/1.55 var(--B);background:rgba(8,13,24,.55);color:var(--w);resize:vertical;min-height:130px}textarea:focus{outline:0;border-color:var(--pur)}
.langs{display:grid;grid-template-columns:repeat(3,1fr);gap:12px}.lg{text-align:left;border:2px solid var(--gb);border-radius:16px;padding:18px;font:700 22px var(--H);background:var(--glass)}.lg small{display:block;font:400 13px var(--B);color:var(--mute);margin-top:4px}.lg.sel{border-color:var(--pur);background:rgba(139,92,246,.16)}
.qb{display:flex;align-items:center;gap:14px;margin-bottom:14px;font:600 14px var(--B)}.qb .pb{flex:1;margin:0}.tm{font:600 14px var(--B);color:#5eead4;white-space:nowrap}
.ex{background:linear-gradient(135deg,rgba(37,99,235,.28),rgba(139,92,246,.28));border-color:rgba(139,92,246,.5)}
.q{font:600 clamp(21px,3.6vw,28px)/1.35 var(--H);margin:16px 0}.me{border-color:rgba(20,184,166,.5)}.me .av{background:linear-gradient(135deg,var(--teal),var(--blue))}
.mq{font-size:13px;color:var(--mute);margin-bottom:12px}
.score{font:700 60px/1 var(--H);color:#5eead4}.score small{font:500 18px var(--B);color:var(--mute)}.score.mid{color:#fbbf24}.score.lo{color:#fb7185}
.fb h3{font:600 15px var(--H);margin:16px 0 4px}.fb .g1{color:#5eead4}.fb .r1{color:#fda4af}.fb p{margin:0}
.fup{background:rgba(251,191,36,.09);border:1px dashed rgba(251,191,36,.5);border-radius:14px;padding:12px 14px;margin-top:16px}
.dash{display:grid;grid-template-columns:repeat(2,1fr);gap:16px}.dash .g{margin:0}.full{grid-column:1/-1}
.ring{position:relative;width:150px;height:150px;margin:0 auto 10px}.ring svg{width:100%;height:100%}.ring circle{fill:none;stroke-width:9}
.rb{stroke:rgba(255,255,255,.12)}.rf{stroke:url(#gr);stroke-linecap:round;stroke-dasharray:326.7;stroke-dashoffset:326.7;transform:rotate(-90deg);transform-origin:60px 60px;transition:stroke-dashoffset 1.3s cubic-bezier(.2,.8,.2,1)}
.ring div{position:absolute;inset:0;display:grid;place-content:center;text-align:center;font:700 32px var(--H)}.ring small{font:500 12px var(--B);color:var(--mute)}
.mt{margin:0 0 14px}.mt div:first-child{display:flex;justify-content:space-between;font-size:14px;margin-bottom:6px}.mt .pb{margin:0;height:10px}.mt .pb i{transition:width 1.2s cubic-bezier(.2,.8,.2,1)}
.item{border-left:3px solid;border-radius:10px;padding:8px 12px;margin:10px 0;background:rgba(255,255,255,.04)}.item b{display:block;font:600 14.5px var(--H)}.item span{display:block;font-size:14px;color:#c8d3e6}.item .y{color:var(--mute)}
.ok{border-color:var(--teal)}.bad{border-color:#fb7185}.rev{border-color:var(--pur)}
.hist{display:flex;justify-content:space-between;gap:12px;padding:10px 0;border-top:1px solid var(--gb);font-size:14.5px}.hist:first-child{border-top:0}.hist b{font:600 14px var(--H);background:rgba(255,255,255,.1);padding:1px 12px;border-radius:99px;white-space:nowrap}
.err{background:rgba(244,63,94,.15);border:1px solid rgba(244,63,94,.5);color:#fecdd3;border-radius:12px;padding:11px 15px;margin:0 0 14px}
.spin{display:inline-block;width:14px;height:14px;border:3px solid rgba(255,255,255,.35);border-top-color:#fff;border-radius:50%;animation:s .8s linear infinite;vertical-align:-2px;margin-right:8px}@keyframes s{to{transform:rotate(360deg)}}
footer{text-align:center;color:var(--mute);font-size:14px;padding:30px 0 0}
@media(max-width:900px){.feat{grid-template-columns:repeat(2,1fr)}}
@media(max-width:820px){.hero{grid-template-columns:1fr;padding-top:26px}.top .lnk{display:none}.how,.dash,.langs{grid-template-columns:1fr}}
@media(max-width:560px){.feat{grid-template-columns:1fr}.g{padding:18px}#dots i{flex-basis:48px}}
@media(prefers-reduced-motion:reduce){{animation:none!important;transition:none!important}.rv{opacity:1;transform:none}}
</style></head>
<body>
<div class="bg"><i></i><i></i><i></i></div>
<header class="top"><div><div class="logo" data-go="1"><i>🎓</i>VivaBuddy</div><span class="sp"></span><a class="lnk" data-nav="features">Features</a><a class="lnk" data-nav="how">How it works</a><button class="pri" data-go="2" type="button">Start Your Viva</button></div></header>
<main>
<div id="dots" class="hidden"><i></i><i data-l="Notes"></i><i data-l="Language"></i><i data-l="Viva"></i><i data-l="Report"></i></div>
<div id="err" class="err hidden nw" role="alert"></div>
<section class="slide active" id="s1">
<div class="hero"><div>
<span class="pill">Viva ka darr, ab hoga Choomantarrr!</span>
<h1><span class="ln"><span>Viva ka darr,</span></span><span class="ln"><span style="animation-delay:.15s">ab hoga <b class="grad">khatam!</b></span></span></h1>
<h2>Your Personal Viva Practice Partner</h2>
<p>Turn your study material into a personalized viva experience. Practice with a virtual examiner, test your understanding, and discover where you need to improve.</p>
<div class="row" style="margin-top:22px"><button class="pri" data-go="2" type="button">Start Your Viva</button><button data-nav="features" type="button">Explore Features</button></div>
<div class="sub">Prepare smarter, practice confidently, and perform better in every viva.</div>
</div>
<div class="prev g"><div class="ph"><span class="av">🎓</span><div><b>Your Virtual Examiner</b><small>Example question</small></div></div><p class="pq">“Why does a transformer work only on AC?”</p><div class="row"><span class="pill">🎙 Answer by voice</span><span class="pill">⌨ Or type</span></div>
<span class="fch" style="right:-8px;top:-18px">📄 Your notes</span><span class="fch" style="left:-10px;bottom:-16px;animation-delay:-2s">📊 Your report</span></div></div>
<div class="sec" id="features"><h2 class="t rv">Everything you need to practice a viva</h2><p class="lead rv">One place to prepare, practice and improve.</p>
<div class="feat">
<div class="g lift rv"><div class="ic">📄</div><h3>Your own material</h3><p>Upload a PDF or paste notes. Questions come only from what you studied.</p></div>
<div class="g lift rv"><div class="ic">🧑‍🏫</div><h3>Virtual examiner</h3><p>One focused question at a time, getting deeper as you go, like a real board.</p></div>
<div class="g lift rv"><div class="ic">🎙</div><h3>Voice or text</h3><p>Speak your answers and hear the questions read out, or simply type.</p></div>
<div class="g lift rv"><div class="ic">🌐</div><h3>English, हिन्दी, Hinglish</h3><p>Choose the examiner’s language and answer in whichever you are comfortable with.</p></div>
<div class="g lift rv"><div class="ic">💬</div><h3>Instant feedback</h3><p>See what you got right, what you missed, plus a follow-up question.</p></div>
<div class="g lift rv"><div class="ic">📊</div><h3>Performance report</h3><p>Scores, strengths, mistakes explained and topics to revise.</p></div>
</div></div>
<div class="sec" id="how"><h2 class="t rv">How it works</h2>
<div class="how"><div class="g rv"><div class="num">01</div><h3>Add your notes</h3><p>Upload a PDF or paste text from any subject.</p></div><div class="g rv"><div class="num">02</div><h3>Face the examiner</h3><p>Answer five questions by voice or text.</p></div><div class="g rv"><div class="num">03</div><h3>Review your report</h3><p>Know exactly what to revise before the real viva.</p></div></div>
<div class="row" style="justify-content:center;margin-top:24px"><button class="pri" data-go="2" type="button">Start Your Viva</button></div></div>
<footer>Prepare smarter, practice confidently, and perform better in every viva.</footer>
</section>
<section class="slide" id="s2"><div class="nw">
<h2 class="t">Start With Your Study Material</h2><p class="lead">Upload your notes or PDF and prepare for your personalized viva. Works for any subject.</p>
<div class="g">
<input type="file" id="file" accept=".pdf,.txt" class="hidden">
<div id="drop"><div class="big">📄</div><b>Drag and drop your PDF here</b><span class="hint">PDF or TXT, up to 40 pages</span><div class="row" style="justify-content:center"><button id="fileBtn" class="pri" type="button">Browse Files</button></div></div>
<div id="fileCard" class="hidden"><div class="av">📄</div><div><span id="fName"></span><span class="hint" id="fSize"></span><div class="pb"><i id="fpBar"></i></div><span class="hint" id="fpTxt"></span></div><button id="fRemove" type="button">Remove</button></div>
<label for="notes" style="margin-top:18px">Or paste your notes</label>
<textarea id="notes" placeholder="Paste your notes here..."></textarea>
<div class="row"><span class="hint">Try demo notes:</span><button class="tl demo" data-d="phy" type="button">Physics</button><button class="tl demo" data-d="ele" type="button">Electrical</button><button class="tl demo" data-d="che" type="button">Chemistry</button><button class="tl demo" data-d="dbms" type="button">DBMS</button><span class="hint" id="count"></span></div>
</div>
<div class="nav"><button data-go="1" type="button">Back</button><button id="to3" class="pri" type="button">Next</button></div>
</div></section>
<section class="slide" id="s3"><div class="nw">
<h2 class="t">Choose the examiner’s language</h2><p class="lead">Questions and feedback will be in this language. You can answer in English, Hindi or Hinglish.</p>
<div class="g"><div class="langs" id="langs">
<button class="lg sel" data-l="en" type="button">English<small>Questions and feedback in English</small></button>
<button class="lg" data-l="hi" type="button">हिन्दी<small>सवाल और फ़ीडबैक हिन्दी में</small></button>
<button class="lg" data-l="hx" type="button">Hinglish<small>Hindi + English mix, Roman script</small></button></div></div>
<div class="nav"><button data-go="2" type="button">Back</button><button id="start" class="pri" type="button">Start the viva</button></div>
</div></section>
<section class="slide" id="s4"><div class="nw">
<h2 class="t">Your Virtual Examiner</h2>
<div class="qb"><span id="qmeta"></span><div class="pb"><i id="qbar"></i></div><span class="tm timer">00:00</span><button class="timerBtn" type="button" style="padding:6px 12px;font-size:12px">Hide timer</button></div>
<div class="g ex"><div class="ph"><span class="av">🎓</span><div><b>Examiner</b><small>Viva Board</small></div></div><div class="q" id="qtext"></div><div class="row"><button id="speak" type="button">🔊 Listen to question</button></div></div>
<div class="nav"><span></span><button data-go="5" class="pri" type="button">Answer this</button></div>
</div></section>
<section class="slide" id="s5"><div class="nw">
<div class="qb"><span class="hint">Your answer</span><span class="sp"></span><span class="tm timer">00:00</span></div>
<div class="g me"><div class="ph"><span class="av">🧑‍🎓</span><div><b>You</b><small>Student</small></div></div>
<div class="mq" id="qmini" style="margin-top:12px"></div>
<label for="ans" class="hidden">Your answer</label>
<textarea id="ans" placeholder="Type your answer, or tap the mic and speak..." style="min-height:140px"></textarea>
<div class="row"><button id="mic" type="button">Answer by voice</button></div><div class="hint" id="micMsg"></div></div>
<div class="nav"><button data-go="4" type="button">Back to question</button><button id="submit" class="pri" type="button">Submit Answer</button></div>
</div></section>
<section class="slide" id="s6"><div class="nw">
<div class="g fb"><div class="score"><span id="sc">0</span><small> / 10</small></div>
<h3 class="g1">What you got right</h3><p id="sahi"></p><h3 class="r1">What you missed</h3><p id="miss"></p>
<div class="fup"><b>Follow-up question:</b> <span id="fup"></span></div><div class="row"><button id="speakFb" type="button">🔊 Listen to feedback</button></div></div>
<div class="nav"><button id="useFup" type="button">Answer the follow-up</button><button id="next" class="pri" type="button">Next Question</button></div>
</div></section>
<section class="slide" id="s7">
<h2 class="t">Your Viva Report</h2><p class="lead">Based on your actual answers in this session.</p>
<div class="dash">
<div class="g"><div class="ring"><svg viewBox="0 0 120 120"><defs><linearGradient id="gr" x1="0" y1="0" x2="1" y2="1"><stop offset="0" stop-color="#2563EB"/><stop offset=".6" stop-color="#8B5CF6"/><stop offset="1" stop-color="#14B8A6"/></linearGradient></defs><circle class="rb" cx="60" cy="60" r="52"/><circle class="rf" id="ringOv" cx="60" cy="60" r="52"/></svg><div><span id="avg">0</span><small>out of 10</small></div></div><p id="sum" class="hint" style="text-align:center;margin:0"></p></div>
<div class="g"><span class="lbl">Performance</span>
<div class="mt"><div><span>Answer accuracy (answers scoring 7+)</span><b id="mAccV">0%</b></div><div class="pb"><i id="mAcc"></i></div></div>
<div class="mt"><div><span>Concept understanding</span><b id="mConV">0</b></div><div class="pb"><i id="mCon"></i></div></div>
<div class="mt"><div><span>Communication quality</span><b id="mComV">0</b></div><div class="pb"><i id="mCom"></i></div></div>
<span class="hint">Communication is judged from your answer text; speech delivery is not measured.</span></div>
<div class="g"><span class="lbl">Strengths</span><div id="strong"></div></div>
<div class="g"><span class="lbl">Recommended topics for revision</span><div id="weak"></div></div>
<div class="g full"><span class="lbl">Incorrect answers and explanations</span><div id="wrong"></div></div>
<div class="g full"><span class="lbl">Score by question</span><div id="hist"></div></div>
</div>
<div class="row" style="justify-content:center;margin-top:20px"><button id="again" class="pri" type="button">Practice again</button></div>
</section>
</main>
<script src="https://cdnjs.cloudflare.com/ajax/libs/pdf.js/3.11.174/pdf.min.js"></script>
<script>
const $=id=>document.getElementById(id),TOTAL=5;
const LN={en:"English",hi:"Hindi (Devanagari script)",hx:"Hinglish (Hindi-English mix in Roman script)"},TTS={en:"en-IN",hi:"hi-IN",hx:"en-IN"};
let S={lang:"en",notes:"",asked:[],history:[],round:0,q:"",ev:null,pending:null};
const DEMO=`Normalization: a database design process that organizes tables to reduce redundancy and avoid insert, update and delete anomalies.
1NF: every column holds atomic (single) values and there are no repeating groups.
2NF: table is in 1NF and no non-key attribute depends on only part of a composite primary key (no partial dependency).
3NF: table is in 2NF and no non-key attribute depends on another non-key attribute (no transitive dependency).
BCNF: for every functional dependency X->Y, X must be a super key.
ACID: Atomicity (all or nothing), Consistency (database stays valid), Isolation (transactions do not interfere), Durability (committed data is permanent).
Primary key: uniquely identifies each row and cannot be NULL. Foreign key refers to the primary key of another table.
Joins: INNER JOIN returns only matching rows. LEFT JOIN returns all left rows, with NULL where the right side has no match.
Indexing: an index (such as a B-tree) speeds up queries but slows inserts and updates slightly and uses extra space.`;
const DEMOS={dbms:DEMO,
phy:`Interference: superposition of two coherent waves gives alternating bright and dark fringes. In Young's double slit experiment, fringe width = lambdaD/d.
Diffraction: bending of light around obstacles or slits; it is significant when the slit width is comparable to the wavelength.
Polarization: restricting light vibrations to one plane; it proves light is a transverse wave. Malus' law: I = I0 cos^2(theta).
Laser: Light Amplification by Stimulated Emission of Radiation. It needs population inversion, a pumping source and an optical resonator. Laser light is monochromatic, coherent and highly directional.
Total internal reflection: happens when light goes from a denser to a rarer medium at an angle greater than the critical angle; it is used in optical fibres.`,
ele:`Ohm's law: V = IR at constant temperature. Kirchhoff's current law: the sum of currents at a node is zero. Kirchhoff's voltage law: the sum of voltages around a closed loop is zero.
Transformer: works on mutual induction and only on AC. Voltage ratio V1/V2 = N1/N2. A step-up transformer has more secondary turns. Losses: copper loss and iron loss (hysteresis and eddy current).
DC motor: follows Fleming's left-hand rule. Back EMF Eb = V - IaRa. Torque is proportional to flux and armature current.
Power factor: cos(phi) = real power / apparent power. A low power factor means higher current and more losses; it is improved using capacitors.
Three-phase supply: three voltages 120 degrees apart. In a star connection, line voltage = root 3 times phase voltage.`,
che:`Hardness of water: caused by dissolved calcium and magnesium salts. Temporary hardness is due to bicarbonates and is removed by boiling. Permanent hardness is due to chlorides and sulphates.
EDTA method: estimates total hardness by complexometric titration using Eriochrome Black-T indicator at pH 10. The colour changes from wine red to blue.
Corrosion: destruction of a metal by chemical or electrochemical reaction. Rusting needs oxygen and moisture. It is prevented by coatings, galvanizing and cathodic protection.
pH = -log[H+]. Buffer solutions resist a change in pH when small amounts of acid or base are added.
Polymers: large molecules made of repeating units. Addition polymerization gives polyethylene. Condensation polymerization gives nylon-6,6 and releases small molecules like water.`};
function go(n){try{speechSynthesis.cancel()}catch(e){}document.querySelectorAll(".slide").forEach((e,i)=>e.classList.toggle("active",i+1===n));
const d=n<=3?n-1:n<=6?3:4;document.querySelectorAll("#dots i").forEach((e,i)=>{e.className=i===d?"on":i<d?"done":""});window.scrollTo(0,0);err("");onSlide(n)}
function err(m){const e=$("err");e.textContent=m;e.classList.toggle("hidden",!m)}
function busy(b,on,t){b.disabled=on;if(on){b.dataset.t=b.textContent;b.innerHTML='<span class="spin"></span>'+t}else b.textContent=b.dataset.t||b.textContent}
document.querySelectorAll("[data-go]").forEach(b=>b.onclick=()=>{if(b.dataset.go==="4"||b.dataset.go==="1"||true){stopMic();go(+b.dataset.go)}});
document.querySelectorAll(".lg").forEach(b=>b.onclick=()=>{S.lang=b.dataset.l;document.querySelectorAll(".lg").forEach(x=>x.classList.toggle("sel",x===b))});
async function aiShim(p){
let r;try{r=await fetch("/api/ai",{method:"POST",headers:{"Content-Type":"application/json"},body:JSON.stringify({prompt:p})})}catch(e){throw new Error("Could not reach the server. Check your internet and try again.")}
const d=await r.json().catch(()=>({}));
if(!r.ok){const e=new Error(d.error||"Server error. Please try again.");if(r.status===429)e.code="rate_limited";throw e}
return{text:d.text||""}}
function dictationShim(){return Promise.resolve((()=>{
const SR=window.SpeechRecognition||window.webkitSpeechRecognition;if(!SR)return null;
let r=null,P=()=>{},Fn=()=>{},St=()=>{};
return{onPartial:f=>{P=f},onFinal:f=>{Fn=f},onState:f=>{St=f},
start(){return new Promise((res,rej)=>{r=new SR();r.lang=({en:"en-IN",hi:"hi-IN",hx:"en-IN"})[S.lang]||"en-IN";r.interimResults=true;r.continuous=true;
r.onresult=e=>{let i="",f="";for(let k=e.resultIndex;k<e.results.length;k++){const t=e.results[k][0].transcript;if(e.results[k].isFinal)f+=t;else i+=t}if(f)Fn({text:f});P({text:i})};
r.onerror=e=>{St({state:"idle"});if(e.error==="not-allowed")rej({code:"not_granted"})};r.onend=()=>St({state:"idle"});
try{r.start();St({state:"listening"});res()}catch(x){rej(x)}})},
stop(){try{r&&r.stop()}catch(e){}}}})())}
const N=n=>(n||"").slice(0,12000);
function pj(t){const m=t.match(/{[\s\S]}/);if(!m)throw new Error("Could not read the examiner\u2019s reply. Please try again.");return JSON.parse(m[0])}
async function api(path,b){
let sample=null;sample=aiShim;
if(!sample)throw new Error("Could not reach Claude. Open this page while logged in to claude.ai and allow the permission.");
const L="Write ALL text values in "+LN[S.lang]+". The student may answer in English, Hindi or Hinglish; accept any. ",J=" Reply with ONLY one valid JSON object (keys in English), no markdown, no extra text.";
try{
if(path==="q"){const t=await sample("You are an external examiner taking a college viva voce. It can be ANY subject (engineering, science, maths, commerce, medical, law, arts, etc). Detect the subject from the notes and ask ONLY from the given notes. Ask exactly ONE short, direct, spoken-style question (max 20 words, single part, never two questions in one) the way a real examiner asks. Vary the type: definition, why/how, formula, unit or key term (only if relevant), real-life application, and what-if. Start easy and go slightly deeper as the question number rises. This is question "+(b.asked.length+1)+" of 5. "+L+"Output only the question.
Notes:
"+N(b.notes)+"
Already asked:
"+(b.asked.join("
")||"none")+"
Ask a NEW question on a different topic from the notes.",{cache:false});return t.text.trim()}
if(path==="e"){const t=await sample("You are a viva examiner. Judge the student's answer ONLY against the notes. "+L+'Be short and encouraging. JSON keys: "score" (integer 0-10), "sahi" (what was correct), "miss" (what was missing or wrong), "topic" (2-4 word topic name), "followup" (one deeper follow-up question), "concept" (integer 0-10: depth of conceptual understanding shown), "clarity" (integer 0-10: how clearly and well-structured the answer was communicated).'+J+"
Notes:
"+N(b.notes)+"
Question: "+b.question+"
Student answer: "+b.answer,{cache:false});const o=pj(t.text);o.score=Math.max(0,Math.min(10,parseInt(o.score)||0));for(const k of["concept","clarity"]){const v=parseInt(o[k]);o[k]=isNaN(v)?null:Math.max(0,Math.min(10,v))}return o}
const t=await sample("You are a study coach. From these viva results write a short report. "+L+'JSON keys: "summary" (2 sentences), "weak_topics" (list of up to 4 objects with "topic" and "padho" = what exactly to revise).'+J+"
Results:
"+JSON.stringify(b.history),{cache:false});return pj(t.text);
}catch(e){
if(e&&e.code==="not_granted")throw new Error("Please allow the permission so the examiner can work.");
if(e&&e.code==="rate_limited")throw new Error("Too many requests. Wait 20 seconds and try again.");
throw new Error((e&&e.message)||"Something went wrong. Please try again.")}
}
$("notes").addEventListener("input",()=>{$("count").textContent=$("notes").value.length+" characters"});
document.querySelectorAll(".demo").forEach(b=>b.onclick=()=>{$("notes").value=DEMOS[b.dataset.d];$("notes").dispatchEvent(new Event("input"))});
$("fileBtn").onclick=()=>$("file").click();
function fmt(b){return b>1048576?(b/1048576).toFixed(1)+" MB":Math.max(1,Math.round(b/1024))+" KB"}
function fprog(p,t,ok){$("fpBar").style.width=p+"%";$("fpTxt").textContent=t;$("fileCard").classList.toggle("ok",!!ok)}
function clearFile(){$("notes").value="";$("count").textContent="";$("fileCard").classList.add("hidden");$("drop").classList.remove("hidden");$("file").value=""}
async function loadFile(f){err("");$("drop").classList.add("hidden");$("fileCard").classList.remove("hidden");$("fName").textContent=f.name;$("fSize").textContent=fmt(f.size);fprog(6,"Reading your file...");
try{let t="";
if(f.name.toLowerCase().endsWith(".pdf")){
if(!window.pdfjsLib)throw new Error("PDF reader did not load (check internet). Please paste your notes instead.");
pdfjsLib.GlobalWorkerOptions.workerSrc="https://cdnjs.cloudflare.com/ajax/libs/pdf.js/3.11.174/pdf.worker.min.js";
const pdf=await pdfjsLib.getDocument({data:await f.arrayBuffer()}).promise,np=Math.min(pdf.numPages,40);
for(let i=1;i<=np;i++){const c=await (await pdf.getPage(i)).getTextContent();t+=c.items.map(x=>x.str).join(" ")+"
";fprog(6+i/np90,"Reading page "+i+" of "+np)}
}else t=await f.text();
if(t.trim().length<50)throw new Error("No text found (maybe a scanned PDF). Please paste your notes instead.");
$("notes").value=t.trim();$("notes").dispatchEvent(new Event("input"));fprog(100,"Uploaded successfully. Your notes are ready.",true)
}catch(x){clearFile();err(x.message)}}
$("file").onchange=e=>{const f=e.target.files[0];if(f)loadFile(f);e.target.value=""};
$("fRemove").onclick=clearFile;
const dz=$("drop");["dragenter","dragover"].forEach(v=>dz.addEventListener(v,e=>{e.preventDefault();dz.classList.add("over")}));
["dragleave","drop"].forEach(v=>dz.addEventListener(v,e=>{e.preventDefault();dz.classList.remove("over")}));
dz.addEventListener("drop",e=>{const f=e.dataTransfer.files[0];if(f)loadFile(f)});
dz.onclick=e=>{if(e.target.id!=="fileBtn")$("file").click()};
$("to3").onclick=()=>{if($("notes").value.trim().length<80){err("Please add a few lines of notes first.");return}S.notes=$("notes").value.trim();go(3)};
$("start").onclick=async()=>{S.asked=[];S.history=[];S.round=0;S.pending=null;await nextQ($("start"),"Preparing question...")};
async function nextQ(btn,txt){busy(btn,true,txt);
try{const q=S.pending||await api("q",{notes:S.notes,asked:S.asked});
S.round++;S.q=q;S.asked.push(q);S.pending=null;
$("qtext").textContent=q;$("qmini").textContent="Q"+S.round+": "+q;$("qmeta").textContent="Question "+S.round+" of "+TOTAL;
$("ans").value="";speechSynthesis.cancel();go(4);say(q);startTimer();qProg()}catch(e){err(e.message)}
busy(btn,false)}
$("submit").onclick=async()=>{const a=$("ans").value.trim();if(!a){err("Write or speak your answer first.");return}
stopMic();busy($("submit"),true,"Checking...");
try{const ev=await api("e",{notes:S.notes,question:S.q,answer:a});S.ev=ev;
S.history.push({question:S.q,answer:a,score:ev.score,topic:ev.topic||"General",sahi:ev.sahi,miss:ev.miss,concept:ev.concept,clarity:ev.clarity});
$("sc").textContent=ev.score;$("sc").parentElement.className="score "+(ev.score>=7?"":ev.score>=4?"mid":"lo");
$("sahi").textContent=ev.sahi||"-";$("miss").textContent=ev.miss||"-";$("fup").textContent=ev.followup||"-";
$("useFup").classList.toggle("hidden",!ev.followup||S.round>=TOTAL);
$("next").textContent=S.round>=TOTAL?"See my report":"Next question";stopTimer();go(6)}catch(e){err(e.message)}
busy($("submit"),false)};
$("next").onclick=()=>{if(S.round>=TOTAL)return finish();S.pending=null;nextQ($("next"),"Preparing question...")};
$("useFup").onclick=()=>{S.pending=S.ev.followup;nextQ($("useFup"),"One second...")};
const el=(t,c,x)=>{const e=document.createElement(t);if(c)e.className=c;if(x!=null)e.textContent=x;return e};
function meter(id,p,t){$(id).style.width=p+"%";$(id+"V").textContent=t}
function fill(id,list,empty){const b=$(id);b.innerHTML="";if(!list.length){if(empty)b.append(el("p","hint",empty));return}list.forEach(x=>b.append(x))}
async function finish(){const btn=$("next");busy(btn,true,"Building your report...");
const h=S.history,n=h.length,avg=h.reduce((s,x)=>s+x.score,0)/n,acc=Math.round(h.filter(x=>x.score>=7).length/n100);
const mean=k=>{const v=h.map(x=>x[k]).filter(x=>x!=null);return v.length?v.reduce((a,b)=>a+b,0)/v.length:null},con=mean("concept"),cla=mean("clarity");
$("avg").textContent=avg.toFixed(1);
fill("strong",h.filter(x=>x.score>=7&&x.sahi).slice(0,4).map(x=>{const d=el("div","item ok");d.append(el("b",null,x.topic),el("span",null,x.sahi));return d}),"No answer scored 7 or above yet. Keep practising!");
fill("wrong",h.filter(x=>x.score<7).map(x=>{const d=el("div","item bad");d.append(el("b",null,x.question),el("span","y","Your answer: "+x.answer),el("span",null,"Explanation: "+(x.miss||"-")));return d}),"No incorrect answers. Great job!");
fill("hist",h.map(x=>{const d=el("div","hist");d.append(el("span",null,x.question),el("b",null,x.score+"/10"));return d}));
let rep;try{rep=await api("r",{history:h})}catch(e){rep={summary:"The summary could not be generated, but your results are shown here.",weak_topics:h.filter(x=>x.score<6).map(x=>({topic:x.topic,padho:x.miss}))}}
$("sum").textContent=rep.summary||"";
fill("weak",(rep.weak_topics||[]).map(t=>{const d=el("div","item rev");d.append(el("b",null,t.topic),el("span",null,t.padho||""));return d}),"No major weak topics found.");
$("ringOv").style.strokeDashoffset=326.7;["mAcc","mCon","mCom"].forEach(i=>$(i).style.width="0");
busy(btn,false);go(7);
setTimeout(()=>{$("ringOv").style.strokeDashoffset=326.7(1-avg/10);meter("mAcc",acc,acc+"%");meter("mCon",con==null?0:con10,con==null?"Not available":con.toFixed(1)+" / 10");meter("mCom",cla==null?0:cla10,cla==null?"Not available":cla.toFixed(1)+" / 10")},150)}
$("again").onclick=()=>go(2);
let dic=null,listening=false,base="";
function ui(){$("mic").textContent=listening?"Tap to stop":"Answer by voice";$("mic").classList.toggle("rec",listening)}
function stopMic(){if(listening&&dic){try{dic.stop()}catch(e){}}listening=false;ui()}
try{dictationShim().then(d=>{
if(!d){$("mic").classList.add("hidden");$("micMsg").textContent="Voice is not available in this browser (try Chrome). You can type instead.";return}
dic=d;d.onPartial(({text})=>{if(listening)$("ans").value=base+text});d.onFinal(({text})=>{base+=text+" ";$("ans").value=base});
d.onState(({state})=>{listening=state==="listening";ui();$("micMsg").textContent=listening?"Listening... speak now.":""});
}).catch(()=>$("mic").classList.add("hidden"))}catch(e){$("mic").classList.add("hidden")}
$("mic").onclick=()=>{if(!dic)return;if(listening){stopMic();return}base=$("ans").value?$("ans").value.trim()+" ":"";
dic.start().catch(e=>{$("micMsg").textContent=(e&&e.code==="not_granted")?"Mic permission denied. You can type instead.":"Could not start the mic."})};
function pickVoice(){
const vs=speechSynthesis.getVoices(),F=/neerja|heera|kalpana|swara|veena|priya|lekha|aditi|raveena|female|zira|hazel|susan/i,M=/prabhat|ravi|hemant|madhur|rishi|kabir|aarav|naveen|male/i;
const want=S.lang==="hi"?["hi-in","en-in"]:["en-in","hi-in"];
for(const l of want){const c=vs.filter(v=>v.lang.replace("_","-").toLowerCase()===l);
const m=c.find(v=>M.test(v.name)&&!/female/i.test(v.name));if(m)return{v:m,male:true};
const n=c.find(v=>!F.test(v.name));if(n)return{v:n,male:false};if(c[0])return{v:c[0],male:false}}
return{v:null,male:false}}
function say(t){if(!("speechSynthesis" in window)||!t)return;
try{speechSynthesis.cancel();const p=pickVoice(),u=new SpeechSynthesisUtterance(t);
if(p.v){u.voice=p.v;u.lang=p.v.lang}else u.lang=TTS[S.lang];
u.rate=.92;u.pitch=p.male?.95:.7;speechSynthesis.speak(u)}catch(e){}}
if("speechSynthesis" in window)speechSynthesis.onvoiceschanged=()=>{};
$("speak").onclick=()=>say(S.q);
$("speakFb").onclick=()=>{const e=S.ev||{};say("Your score is "+e.score+" out of 10. "+(e.sahi||"")+" "+(e.miss||"")+" "+(e.followup||""))};
let tmI=null,t0=0,tOn=true;
function tick(){const s=Math.floor((Date.now()-t0)/1000),t=String(Math.floor(s/60)).padStart(2,"0")+":"+String(s%60).padStart(2,"0");document.querySelectorAll(".timer").forEach(e=>e.textContent=t)}
function stopTimer(){clearInterval(tmI);tmI=null}
function startTimer(){stopTimer();t0=Date.now();tick();tmI=setInterval(tick,1000)}
document.querySelectorAll(".timerBtn").forEach(b=>b.onclick=()=>{tOn=!tOn;document.querySelectorAll(".timer").forEach(e=>e.classList.toggle("hidden",!tOn));document.querySelectorAll(".timerBtn").forEach(x=>x.textContent=tOn?"Hide timer":"Show timer")});
function qProg(){$("qbar").style.width=((S.round-1)/TOTAL100)+"%"}
function onSlide(n){document.body.dataset.s=n;$("dots").classList.toggle("hidden",n===1)}
document.querySelectorAll("[data-nav]").forEach(a=>a.onclick=()=>{stopMic();go(1);setTimeout(()=>{const t=$(a.dataset.nav);if(t)t.scrollIntoView({behavior:"smooth"})},60)});
const io=new IntersectionObserver(es=>es.forEach(e=>{if(e.isIntersecting){e.target.classList.add("in");io.unobserve(e.target)}}),{threshold:.1});
document.querySelectorAll(".rv").forEach(x=>io.observe(x));
go(1);
</script>
</body></html>



