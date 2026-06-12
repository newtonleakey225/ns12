<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8"/>
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>
<title>Your Dashboard 👀</title>
<link href="https://fonts.googleapis.com/css2?family=Caveat:wght@400;600;700&family=DM+Sans:wght@300;400;500&display=swap" rel="stylesheet"/>
<style>
*,*::before,*::after{box-sizing:border-box;margin:0;padding:0}
body{background:#0a0118;min-height:100vh;font-family:'DM Sans',sans-serif;color:#f0e6ff}
.lock-screen{position:fixed;inset:0;background:#0a0118;z-index:999;display:flex;align-items:center;justify-content:center;flex-direction:column;gap:1.2rem;padding:2rem}
.lock-screen.hidden{display:none}
.lock-icon{font-size:3.5rem;animation:pulse 2s ease-in-out infinite}
@keyframes pulse{0%,100%{transform:scale(1)}50%{transform:scale(1.1)}}
.lock-title{font-family:'Caveat',cursive;font-size:2rem;color:#f9c8ff;text-align:center}
.lock-sub{color:#8b6fa8;font-size:.88rem;text-align:center}
.lock-input{background:rgba(255,255,255,.08);border:1.5px solid rgba(255,255,255,.15);border-radius:1rem;padding:.7rem 1.2rem;color:#fff;font-size:1rem;text-align:center;outline:none;width:100%;max-width:280px;letter-spacing:.2em}
.lock-input:focus{border-color:#7c3aed}
.lock-btn{background:#7c3aed;color:#fff;border:none;border-radius:1rem;padding:.65rem 2rem;font-family:'Caveat',cursive;font-size:1.2rem;cursor:pointer;width:100%;max-width:280px;transition:opacity .2s}
.lock-btn:hover{opacity:.85}
.lock-error{color:#e879a0;font-size:.85rem;min-height:1.2rem;text-align:center}
.dashboard{padding:1.5rem 1rem 4rem;max-width:650px;margin:0 auto}
.header{text-align:center;padding:1rem 0 1.2rem}
.header h1{font-family:'Caveat',cursive;font-size:2.2rem;background:linear-gradient(135deg,#f9c8ff,#f5c842);-webkit-background-clip:text;-webkit-text-fill-color:transparent;background-clip:text}
.header p{color:#8b6fa8;font-size:.85rem;margin-top:.3rem}
.top-bar{display:flex;gap:.6rem;justify-content:center;margin-bottom:1.2rem;flex-wrap:wrap}
.refresh-btn{background:rgba(124,58,237,.3);border:1.5px solid rgba(124,58,237,.5);color:#c4a0e8;border-radius:2rem;padding:.4rem 1.2rem;font-size:.85rem;cursor:pointer;transition:all .2s}
.refresh-btn:hover{background:rgba(124,58,237,.5);color:#fff}
.live-dot{display:flex;align-items:center;gap:.4rem;font-size:.8rem;color:#7ecba1;background:rgba(126,203,161,.1);border:1px solid rgba(126,203,161,.2);border-radius:2rem;padding:.4rem 1rem}
.dot{width:8px;height:8px;background:#7ecba1;border-radius:50%;animation:blink 1.5s ease-in-out infinite}
@keyframes blink{0%,100%{opacity:1}50%{opacity:.2}}
.stats-row{display:grid;grid-template-columns:repeat(3,1fr);gap:.8rem;margin-bottom:1.4rem}
.stat-box{background:rgba(255,255,255,.05);border:1.5px solid rgba(255,255,255,.08);border-radius:1rem;padding:.9rem;text-align:center}
.stat-num{font-family:'Caveat',cursive;font-size:2rem;font-weight:700;color:#f9c8ff}
.stat-label{font-size:.72rem;color:#8b6fa8;text-transform:uppercase;letter-spacing:.06em;margin-top:.2rem}
.cheatsheet{background:rgba(245,200,66,.07);border:1.5px solid rgba(245,200,66,.2);border-radius:1rem;padding:1rem 1.2rem;margin-bottom:1.4rem}
.cheatsheet h3{font-family:'Caveat',cursive;font-size:1.1rem;color:#f5c842;margin-bottom:.6rem}
.pw-row{display:flex;justify-content:space-between;align-items:center;padding:.35rem 0;border-bottom:1px solid rgba(255,255,255,.05);font-size:.85rem}
.pw-row:last-child{border-bottom:none}
.pw-label{color:#c4a0e8}.pw-value{color:#f5c842;font-family:'Caveat',cursive;font-size:1rem}
.pw-status{font-size:.7rem;padding:.15rem .5rem;border-radius:1rem;background:rgba(126,203,161,.15);color:#7ecba1}
.pw-status.locked{background:rgba(255,255,255,.06);color:#6b4fa0}
.section{margin-bottom:1.4rem}
.sec-head{font-family:'Caveat',cursive;font-size:1.3rem;color:#f9c8ff;margin-bottom:.7rem;padding-bottom:.4rem;border-bottom:1px solid rgba(255,255,255,.08);display:flex;align-items:center;justify-content:space-between}
.sec-count{font-size:.75rem;background:rgba(124,58,237,.25);color:#c4a0e8;border-radius:1rem;padding:.15rem .6rem}
.log-item{background:rgba(255,255,255,.04);border:1px solid rgba(255,255,255,.07);border-radius:.9rem;padding:.8rem 1rem;margin-bottom:.6rem;display:flex;gap:.8rem;align-items:flex-start;animation:fadeUp .3s ease}
@keyframes fadeUp{from{opacity:0;transform:translateY(8px)}to{opacity:1;transform:translateY(0)}}
.log-icon{font-size:1.2rem;flex-shrink:0;margin-top:.1rem}
.log-body{flex:1;min-width:0}
.log-title{font-size:.88rem;color:#e2b8ff;font-weight:500;line-height:1.4}
.log-detail{font-size:.78rem;color:#7a5fa0;margin-top:.2rem;font-style:italic;word-break:break-word}
.log-time{font-size:.68rem;color:#5a4070;margin-top:.3rem}
.tag{display:inline-block;font-size:.65rem;padding:.15rem .5rem;border-radius:1rem;font-weight:600;margin-right:.3rem}
.tag-truth{background:#dbeafe;color:#1d4ed8}.tag-dare{background:#fce7f3;color:#9d174d}.tag-action{background:#d1fae5;color:#065f46}
.tag-match{background:rgba(124,200,66,.2);color:#7ecba1}.tag-nomatch{background:rgba(232,121,160,.15);color:#e879a0}
.tag-unlocked{background:rgba(245,200,66,.2);color:#f5c842}.tag-wrong{background:rgba(224,90,122,.2);color:#e05a7a}
.wyr-row{background:rgba(255,255,255,.04);border:1px solid rgba(255,255,255,.07);border-radius:.9rem;padding:.8rem 1rem;margin-bottom:.6rem}
.wyr-q{font-size:.78rem;color:#8b6fa8;margin-bottom:.35rem}
.wyr-picks{display:flex;gap:.5rem;align-items:center;font-size:.88rem;flex-wrap:wrap}
.her-pick{color:#e879a0;font-weight:500}.my-pick-lbl{color:#f5c842;font-weight:500}
.empty-state{text-align:center;padding:2rem 1rem;color:#5a4070}
.empty-state .e-icon{font-size:2.5rem;margin-bottom:.5rem}
.empty-state p{font-family:'Caveat',cursive;font-size:1.1rem}
.new-badge{display:inline-block;background:#e879a0;color:#fff;font-size:.65rem;font-weight:700;padding:.1rem .45rem;border-radius:1rem;margin-left:.4rem;vertical-align:middle}
</style>
</head>
<body>

<div class="lock-screen" id="lockScreen">
  <div class="lock-icon">🔐</div>
  <div class="lock-title">your eyes only 👀</div>
  <div class="lock-sub">enter your secret password to open the dashboard</div>
  <input class="lock-input" type="password" id="lockInput" placeholder="password" maxlength="30"/>
  <button class="lock-btn" id="lockBtn">enter 🔑</button>
  <div class="lock-error" id="lockError"></div>
</div>

<div class="dashboard" id="dashboard" style="display:none">
  <div class="header">
    <h1>👀 Your Dashboard</h1>
    <p>everything May~Cee does — live from Supabase 🔥</p>
  </div>
  <div class="top-bar">
    <div class="live-dot"><div class="dot"></div>live — updates every 10s</div>
    <button class="refresh-btn" onclick="loadAll()">↻ refresh now</button>
  </div>
  <div class="stats-row">
    <div class="stat-box"><div class="stat-num" id="statTotal">—</div><div class="stat-label">total actions</div></div>
    <div class="stat-box"><div class="stat-num" id="statCards">—</div><div class="stat-label">cards flipped</div></div>
    <div class="stat-box"><div class="stat-num" id="statSpins">—</div><div class="stat-label">spins</div></div>
  </div>
  <div class="section">
    <div class="cheatsheet">
      <h3>🔑 Vault Passwords — drip slowly 😏</h3>
      <div class="pw-row"><span class="pw-label">💛 Golden Memory</span><span class="pw-value">sana</span><span class="pw-status locked" id="pw0">locked</span></div>
      <div class="pw-row"><span class="pw-label">🥺 The Real One</span><span class="pw-value">maycee</span><span class="pw-status locked" id="pw1">locked</span></div>
      <div class="pw-row"><span class="pw-label">✨ Future Us</span><span class="pw-value">next time</span><span class="pw-status locked" id="pw2">locked</span></div>
      <div class="pw-row"><span class="pw-label">🔥 The Secret</span><span class="pw-value">star</span><span class="pw-status locked" id="pw3">locked</span></div>
    </div>
  </div>
  <div class="section"><div class="sec-head">🌟 Page Visits <span class="sec-count" id="countOpen">0</span></div><div id="openLog"><div class="empty-state"><div class="e-icon">🌟</div><p>waiting for her to open the page…</p></div></div></div>
  <div class="section"><div class="sec-head">🎴 Cards Flipped <span class="sec-count" id="countCards">0</span></div><div id="cardsLog"><div class="empty-state"><div class="e-icon">🎴</div><p>no cards flipped yet</p></div></div></div>
  <div class="section"><div class="sec-head">🔐 Vault Activity <span class="sec-count" id="countVault">0</span></div><div id="vaultLog"><div class="empty-state"><div class="e-icon">🔒</div><p>no vault attempts yet</p></div></div></div>
  <div class="section"><div class="sec-head">💌 Letters Opened <span class="sec-count" id="countLetters">0</span></div><div id="lettersLog"><div class="empty-state"><div class="e-icon">💌</div><p>no letters opened yet</p></div></div></div>
  <div class="section"><div class="sec-head">🎰 Wheel Spins <span class="sec-count" id="countWheel">0</span></div><div id="wheelLog"><div class="empty-state"><div class="e-icon">🎰</div><p>no spins yet</p></div></div></div>
  <div class="section"><div class="sec-head">💭 Would You Rather <span class="sec-count" id="countWyr">0</span></div><div id="wyrLog"><div class="empty-state"><div class="e-icon">💭</div><p>no picks yet</p></div></div></div>
  <div class="section"><div class="sec-head">🧩 Puzzle Progress <span class="sec-count" id="countPuzzle">0</span></div><div id="puzzleLog"><div class="empty-state"><div class="e-icon">🧩</div><p>puzzle not started yet</p></div></div></div>
  <div class="section"><div class="sec-head">📋 Full Timeline <span class="sec-count" id="countAll">0</span></div><div id="fullLog"><div class="empty-state"><div class="e-icon">📋</div><p>nothing yet — send her the link!</p></div></div></div>
</div>

<script>
const SUPABASE_URL='https://djufwrhguiiizecjiybo.supabase.co';
const SUPABASE_KEY='eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJzdXBhYmFzZSIsInJlZiI6ImRqdWZ3cmhndWlpaXplY2ppeWJvIiwicm9sZSI6ImFub24iLCJpYXQiOjE3ODEyNzAyMzIsImV4cCI6MjA5Njg0NjIzMn0.TF7MnOBkiBU3ebGo6UF11OvugOD6GcvKYjgVvbDQD34';
const DASHBOARD_PASSWORD='maycee123';

const lockInput=document.getElementById('lockInput');
const lockError=document.getElementById('lockError');
document.getElementById('lockBtn').addEventListener('click',tryUnlock);
lockInput.addEventListener('keydown',e=>{if(e.key==='Enter')tryUnlock()});
function tryUnlock(){
  if(lockInput.value===DASHBOARD_PASSWORD){
    document.getElementById('lockScreen').classList.add('hidden');
    document.getElementById('dashboard').style.display='block';
    loadAll();
  } else {
    lockError.textContent='wrong password bro 😅';lockInput.value='';
    setTimeout(()=>lockError.textContent='',2500);
  }
}

async function fetchLogs(){
  const res=await fetch(`${SUPABASE_URL}/rest/v1/logs?order=created_at.desc&limit=300`,{
    headers:{'apikey':SUPABASE_KEY,'Authorization':`Bearer ${SUPABASE_KEY}`}
  });
  return await res.json();
}

function timeAgo(iso){
  const diff=(Date.now()-new Date(iso))/1000;
  if(diff<60)return Math.floor(diff)+'s ago';
  if(diff<3600)return Math.floor(diff/60)+'m ago';
  if(diff<86400)return Math.floor(diff/3600)+'h ago';
  return new Date(iso).toLocaleDateString();
}
function isNew(iso){return(Date.now()-new Date(iso))/1000<120}
function nb(){return'<span class="new-badge">NEW</span>'}

let lastCount=0;

async function loadAll(){
  let logs;
  try{logs=await fetchLogs();}catch(e){console.error(e);return;}
  if(!Array.isArray(logs))return;

  if(lastCount>0&&logs.length>lastCount){
    document.title=`🔴 ${logs.length-lastCount} new! — Dashboard`;
    setTimeout(()=>document.title='Your Dashboard 👀',5000);
  }
  lastCount=logs.length;

  document.getElementById('statTotal').textContent=logs.length;
  document.getElementById('statCards').textContent=logs.filter(l=>l.type==='card_flip').length;
  document.getElementById('statSpins').textContent=logs.filter(l=>l.type==='wheel_spin').length;
  document.getElementById('countAll').textContent=logs.length;

  // vault status
  const unlocked=logs.filter(l=>l.type==='vault_unlocked').map(l=>l.data?.vault||'');
  ['Golden Memory','The Real One','Future Us','The Secret'].forEach((name,i)=>{
    const el=document.getElementById('pw'+i);
    if(unlocked.some(u=>u.includes(name))){el.textContent='🔓 unlocked';el.className='pw-status';}
  });

  const opens=logs.filter(l=>l.type==='page_open');
  document.getElementById('countOpen').textContent=opens.length;
  render('openLog',opens,l=>`<div class="log-item"><div class="log-icon">🌟</div><div class="log-body"><div class="log-title">she opened the page${isNew(l.created_at)?nb():''}</div><div class="log-time">${timeAgo(l.created_at)}</div></div></div>`,'🌟','waiting for her to open the page…');

  const cardLogs=logs.filter(l=>l.type==='card_flip');
  document.getElementById('countCards').textContent=cardLogs.length;
  render('cardsLog',cardLogs,l=>`<div class="log-item"><div class="log-icon">${l.data?.type==='truth'?'🤔':l.data?.type==='dare'?'🔥':'⚡'}</div><div class="log-body"><div class="log-title"><span class="tag tag-${l.data?.type}">${l.data?.type}</span>${l.data?.text||''}${isNew(l.created_at)?nb():''}</div><div class="log-time">${timeAgo(l.created_at)}</div></div></div>`,'🎴','no cards flipped yet');

  const vaultLogs=logs.filter(l=>l.type==='vault_attempt'||l.type==='vault_unlocked');
  document.getElementById('countVault').textContent=vaultLogs.length;
  render('vaultLog',vaultLogs,l=>{
    if(l.type==='vault_unlocked')return`<div class="log-item"><div class="log-icon">🔓</div><div class="log-body"><div class="log-title"><span class="tag tag-unlocked">UNLOCKED</span>${l.data?.vault||''}${isNew(l.created_at)?nb():''}</div><div class="log-time">${timeAgo(l.created_at)}</div></div></div>`;
    return`<div class="log-item"><div class="log-icon">${l.data?.correct?'✅':'❌'}</div><div class="log-body"><div class="log-title"><span class="tag ${l.data?.correct?'tag-unlocked':'tag-wrong'}">${l.data?.correct?'correct':'wrong'}</span>${l.data?.vault||''}${isNew(l.created_at)?nb():''}</div><div class="log-detail">she tried: "${l.data?.attempt||''}"</div><div class="log-time">${timeAgo(l.created_at)}</div></div></div>`;
  },'🔒','no vault attempts yet');

  const letterLogs=logs.filter(l=>l.type==='letter_opened');
  document.getElementById('countLetters').textContent=letterLogs.length;
  render('lettersLog',letterLogs,l=>`<div class="log-item"><div class="log-icon">💌</div><div class="log-body"><div class="log-title">${l.data?.title||''}${isNew(l.created_at)?nb():''}</div><div class="log-time">${timeAgo(l.created_at)}</div></div></div>`,'💌','no letters opened yet');

  const wheelLogs=logs.filter(l=>l.type==='wheel_spin');
  document.getElementById('countWheel').textContent=wheelLogs.length;
  render('wheelLog',wheelLogs,l=>`<div class="log-item"><div class="log-icon">🎰</div><div class="log-body"><div class="log-title">${l.data?.result||''}${isNew(l.created_at)?nb():''}</div><div class="log-detail">${l.data?.full||''}</div><div class="log-time">${timeAgo(l.created_at)}</div></div></div>`,'🎰','no spins yet');

  const wyrLogs=logs.filter(l=>l.type==='wyr_pick');
  document.getElementById('countWyr').textContent=wyrLogs.length;
  if(wyrLogs.length===0){document.getElementById('wyrLog').innerHTML='<div class="empty-state"><div class="e-icon">💭</div><p>no picks yet</p></div>';}
  else{document.getElementById('wyrLog').innerHTML=wyrLogs.map(l=>`<div class="wyr-row"><div class="wyr-q">${l.data?.question||''}${isNew(l.created_at)?nb():''}</div><div class="wyr-picks"><span class="her-pick">she: ${l.data?.picked||''}</span><span style="color:#5a4070;font-size:.8rem">vs</span><span class="my-pick-lbl">you: ${l.data?.myPick||''}</span><span class="tag ${l.data?.matched?'tag-match':'tag-nomatch'}">${l.data?.matched?'✅ match':'❌ diff'}</span></div><div class="log-time">${timeAgo(l.created_at)}</div></div>`).join('');}

  const puzzleLogs=logs.filter(l=>['puzzle_start','puzzle_piece','puzzle_complete'].includes(l.type));
  document.getElementById('countPuzzle').textContent=puzzleLogs.length;
  if(puzzleLogs.length===0){document.getElementById('puzzleLog').innerHTML='<div class="empty-state"><div class="e-icon">🧩</div><p>puzzle not started yet</p></div>';}
  else{
    const pieces=puzzleLogs.filter(l=>l.type==='puzzle_piece').length+(puzzleLogs.find(l=>l.type==='puzzle_start')?1:0);
    const done=puzzleLogs.find(l=>l.type==='puzzle_complete');
    document.getElementById('puzzleLog').innerHTML=`<div class="log-item"><div class="log-icon">🧩</div><div class="log-body"><div class="log-title">${done?'🎉 puzzle complete!!':pieces+' / 9 pieces revealed'}${isNew(puzzleLogs[0].created_at)?nb():''}</div><div class="log-detail">${done?'she finished everything 🎉':'still going…'}</div><div class="log-time">${timeAgo(puzzleLogs[0].created_at)}</div></div></div>`;
  }

  const icons={page_open:'🌟',card_flip:'🎴',vault_attempt:'🔐',vault_unlocked:'🔓',letter_opened:'💌',wheel_spin:'🎰',puzzle_start:'🧩',puzzle_piece:'🧩',puzzle_complete:'🎉',wyr_pick:'💭',tab_visit:'👆'};
  if(logs.length===0){document.getElementById('fullLog').innerHTML='<div class="empty-state"><div class="e-icon">📋</div><p>nothing yet — send her the link!</p></div>';}
  else{document.getElementById('fullLog').innerHTML=logs.map(l=>`<div class="log-item"><div class="log-icon">${icons[l.type]||'📌'}</div><div class="log-body"><div class="log-title">${l.type.replace(/_/g,' ')}${isNew(l.created_at)?nb():''}</div><div class="log-detail">${JSON.stringify(l.data||{}).replace(/[{}"]/g,'').replace(/,/g,' · ').substring(0,120)}</div><div class="log-time">${timeAgo(l.created_at)}</div></div></div>`).join('');}
}

function render(elId,items,tmpl,emptyIcon,emptyMsg){
  document.getElementById(elId).innerHTML=!items||items.length===0?`<div class="empty-state"><div class="e-icon">${emptyIcon}</div><p>${emptyMsg}</p></div>`:items.map(tmpl).join('');
}

setInterval(loadAll,10000);
</script>
</body>
</html>
