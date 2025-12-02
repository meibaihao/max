<!DOCTYPE html>
<html lang="zh-CN">
<head>
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width,initial-scale=1,maximum-scale=1,viewport-fit=cover"/>
<title>PBL互动闯关：蔡先生“呼之不应”· 15问全覆盖（手机目录不遮挡版）</title>
<meta name="theme-color" content="#0a4aa6" />
<style>
:root{
  --brand:#0a4aa6; --brand2:#0f6ddf; --ok:#22c55e; --warn:#f59e0b; --bad:#ef4444;
  --bg:#f6f8fb; --text:#111827; --muted:#5b6475; --card:#ffffff; --line:#e5e7eb; --pill:#eef2ff;
  --shadow:0 12px 30px rgba(15,23,42,.08); --radius:16px;
}
@media (prefers-color-scheme: dark){
  :root{--bg:#0b0e11;--text:#f5f7fa;--muted:#a7b0bd;--card:#12161c;--line:#1f2630;--pill:#0f1b35;--shadow:0 12px 30px rgba(0,0,0,.38);}
}
*{box-sizing:border-box;-webkit-tap-highlight-color:transparent}
html,body{height:100%;margin:0;font-family:Inter,-apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,"Helvetica Neue",Arial,"PingFang SC","Hiragino Sans GB","Microsoft YaHei UI","Microsoft YaHei";color:var(--text);background:var(--bg)}
a{color:var(--brand2);text-decoration:none} a:hover{text-decoration:underline}
.appbar{position:sticky;top:0;z-index:50;background:linear-gradient(180deg,var(--brand),var(--brand2));color:#fff}
.appbar .row{max-width:1100px;margin:0 auto;display:flex;align-items:center;gap:10px;padding:12px 16px}
.appbar h1{font-size:18px;margin:0;font-weight:950;letter-spacing:.2px}
.appbar small{opacity:.92}
.progress{position:fixed;left:0;top:0;height:3px;background:linear-gradient(90deg,#00d4ff,#0f6ddf);width:0;z-index:60;box-shadow:0 0 16px rgba(0,212,255,.3)}
.container{max-width:1100px;margin:14px auto;padding:0 12px;display:grid;grid-template-columns:300px 1fr;gap:14px;align-items:start}
@media (max-width:980px){ .container{grid-template-columns:1fr} }
.toc{position:sticky;top:64px;background:var(--card);border:1px solid var(--line);border-radius:var(--radius);padding:12px;box-shadow:var(--shadow)}
.toc h3{margin:6px 6px 8px;font-size:14px;color:var(--muted)}
.toc a{display:flex;gap:10px;align-items:center;justify-content:space-between;padding:10px 10px;border-radius:14px;color:var(--text);border:1px solid transparent;font-size:14px;line-height:1.35}
.toc a:hover{background:rgba(15,109,223,.08);border-color:rgba(15,109,223,.22)}
.pill{font-size:11px;padding:2px 8px;border-radius:999px;background:var(--pill);border:1px solid rgba(15,109,223,.15);color:var(--muted);flex:none}
@media (prefers-color-scheme: dark){ .pill{color:#cfe0ff;border-color:#213a6a} }

.section{display:flex;flex-direction:column;gap:16px}
.card{background:var(--card);border:1px solid var(--line);border-radius:var(--radius);padding:16px;box-shadow:var(--shadow)}
.kicker{display:flex;align-items:center;gap:8px;margin:0 0 10px}
.dot{width:8px;height:8px;background:var(--brand2);border-radius:2px}
.badge{display:inline-block;background:var(--pill);color:#1f3b77;border:1px solid #cdd8ff;padding:3px 10px;border-radius:999px;font-size:12px}
@media (prefers-color-scheme: dark){ .badge{color:#cfe0ff;border-color:#213a6a} }
h2{margin:0 0 8px;font-size:20px}
h3{margin:10px 0 6px;font-size:15px}
p,li{margin:4px 0;font-size:14px;line-height:1.7}
.muted{color:var(--muted)}
.grid2{display:grid;grid-template-columns:1fr 1fr;gap:12px}
@media (max-width:820px){ .grid2{grid-template-columns:1fr} }
.callout{border:1px solid rgba(245,158,11,.35);background:rgba(245,158,11,.07);padding:12px;border-radius:14px}
.note{border:1px solid rgba(239,68,68,.35);background:rgba(239,68,68,.07);padding:12px;border-radius:14px}
.goodbox{border:1px solid rgba(34,197,94,.35);background:rgba(34,197,94,.08);padding:12px;border-radius:14px}
hr.sep{border:0;border-top:1px dashed var(--line);margin:10px 0}

/* Tabs */
.tabs{display:flex;gap:8px;flex-wrap:wrap;margin:8px 0}
.tab{border:1px solid var(--line);background:transparent;color:var(--text);padding:8px 10px;border-radius:14px;font-weight:900;font-size:13px}
.tab.active{background:rgba(15,109,223,.10);border-color:rgba(15,109,223,.35)}
.panel{display:none;border:1px solid var(--line);border-radius:14px;padding:12px;background:rgba(0,0,0,.015)}
.panel.active{display:block}
@media (prefers-color-scheme: dark){ .panel{background:rgba(255,255,255,.03)} }

/* Reveal steps */
.reveal{display:flex;gap:8px;flex-wrap:wrap;align-items:center}
.btn{border:1px solid var(--line);background:linear-gradient(180deg,rgba(15,109,223,.10),rgba(15,109,223,.02));
  color:var(--text);padding:8px 12px;border-radius:14px;font-weight:950;font-size:13px}
.btn:active{transform:translateY(1px)}
.step{display:none;border:1px solid rgba(15,109,223,.2);background:rgba(15,109,223,.06);border-radius:14px;padding:10px;margin-top:8px}
.step.show{display:block}

/* Flashcards */
.flashgrid{display:grid;grid-template-columns:1fr 1fr;gap:12px}
@media (max-width:820px){ .flashgrid{grid-template-columns:1fr} }
.flash{position:relative;perspective:1000px;height:138px;cursor:pointer}
.flash .inner{position:absolute;inset:0;transition:transform .55s ease;transform-style:preserve-3d}
.flash.flipped .inner{transform:rotateY(180deg)}
.face{position:absolute;inset:0;backface-visibility:hidden;border:1px solid var(--line);border-radius:16px;padding:12px;display:flex;flex-direction:column;justify-content:space-between}
.front{background:linear-gradient(180deg,rgba(15,109,223,.10),rgba(15,109,223,.02))}
.back{transform:rotateY(180deg);background:rgba(0,0,0,.015)}
@media (prefers-color-scheme: dark){ .back{background:rgba(255,255,255,.03)} }
.flash small{color:var(--muted)}

/* Quiz blocks */
.quiz{border:1px solid var(--line);border-radius:16px;padding:12px;background:rgba(0,0,0,.015)}
@media (prefers-color-scheme: dark){ .quiz{background:rgba(255,255,255,.03)} }
.q-head{display:flex;align-items:center;justify-content:space-between;gap:8px}
.q-head b{font-size:14px}
.q-opts{display:grid;gap:8px;margin-top:10px}
.opt{border:1px solid var(--line);border-radius:14px;padding:10px;background:transparent;text-align:left;font-weight:900}
.opt.good{border-color:rgba(34,197,94,.55);background:rgba(34,197,94,.12)}
.opt.bad{border-color:rgba(239,68,68,.55);background:rgba(239,68,68,.12)}
.feedback{margin-top:10px;font-size:13px}

/* Decision tree */
.tree{display:grid;gap:10px}
.node{border:1px solid var(--line);border-radius:14px;padding:10px;display:flex;gap:10px;align-items:flex-start;background:rgba(0,0,0,.01)}
@media (prefers-color-scheme: dark){ .node{background:rgba(255,255,255,.02)} }
.node .icon{width:26px;height:26px;border-radius:10px;display:flex;align-items:center;justify-content:center;color:#fff;font-weight:950;flex:none}
.icon.ok{background:var(--ok)} .icon.warn{background:var(--warn)} .icon.bad{background:var(--bad)}

/* Chips */
.chips{display:flex;flex-wrap:wrap;gap:8px;margin-top:8px}
.chip{font-size:12px;border:1px solid var(--line);border-radius:999px;padding:6px 10px;background:rgba(0,0,0,.02)}
@media (prefers-color-scheme: dark){ .chip{background:rgba(255,255,255,.03)} }

/* SVG */
svg{max-width:100%;height:auto}
.flow path.arrow{stroke-dasharray:6 8;animation:dash 2.2s linear infinite}
@keyframes dash{to{stroke-dashoffset:-120}}
.pupil .p{transition:transform .35s ease;transform-origin:center}
.pupil.touch .p{transform:scale(.62)}

/* Video cards */
.vgrid{display:grid;grid-template-columns:1fr 1fr;gap:12px}
@media (max-width:820px){ .vgrid{grid-template-columns:1fr} }
.vcard{border:1px solid var(--line);border-radius:16px;overflow:hidden;background:rgba(0,0,0,.01)}
@media (prefers-color-scheme: dark){ .vcard{background:rgba(255,255,255,.02)} }
.vthumb{aspect-ratio:16/9;background:#0b1222;display:flex;align-items:center;justify-content:center;color:#fff;font-weight:900}
.vthumb img{width:100%;height:100%;object-fit:cover;display:block}
.vbody{padding:10px}
.vtitle{font-weight:950;margin:0 0 4px}
.vmeta{font-size:12px;color:var(--muted)}

/* Game HUD */
.hud{display:flex;gap:10px;flex-wrap:wrap;align-items:center;justify-content:space-between}
.scorebox{display:flex;gap:8px;align-items:center;flex-wrap:wrap}
.score{font-weight:950}
.bar{height:10px;border-radius:999px;border:1px solid var(--line);overflow:hidden;min-width:140px;background:rgba(0,0,0,.02)}
@media (prefers-color-scheme: dark){ .bar{background:rgba(255,255,255,.03)} }
.bar > div{height:100%;width:0;background:linear-gradient(90deg,#00d4ff,#0f6ddf)}
.toast{position:fixed;left:50%;bottom:16px;transform:translateX(-50%);background:rgba(17,24,39,.92);color:#fff;padding:10px 12px;border-radius:14px;font-size:13px;opacity:0;pointer-events:none;transition:opacity .2s ease}
.toast.show{opacity:1}
.footer{color:var(--muted);font-size:12px;text-align:center;margin:18px 0}

/* ✅ 手机目录不遮挡：目录变抽屉 + 右下角“目录”按钮 */
.tocToggle{
  position:fixed; right:14px; bottom:14px; z-index:70;
  border:1px solid rgba(255,255,255,.18);
  background:linear-gradient(180deg,rgba(10,74,166,.95),rgba(15,109,223,.95));
  color:#fff; padding:10px 12px; border-radius:999px; font-weight:950; font-size:13px;
  box-shadow:0 14px 30px rgba(0,0,0,.25); cursor:pointer;
}
.tocMask{position:fixed; inset:0; background:rgba(0,0,0,.42); z-index:68; opacity:0; pointer-events:none; transition:opacity .2s ease;}
.tocMask.show{opacity:1; pointer-events:auto;}
@media (max-width:980px){
  .toc{
    position:fixed; top:0; left:0; bottom:0; width:min(92vw, 360px);
    transform:translateX(-105%); transition:transform .25s ease;
    z-index:69; border-radius:0 18px 18px 0; padding-top:18px; overflow:auto;
  }
  .toc.open{transform:translateX(0);}
  .toc a{padding:12px 10px}
}
@media (min-width:981px){
  .tocToggle,.tocMask{display:none;}
}
</style>
</head>

<body>
<div class="progress" id="prog"></div>
<div class="toast" id="toast"></div>
<button class="tocToggle" id="tocToggle" aria-label="打开目录">目录</button>
<div class="tocMask" id="tocMask" aria-hidden="true"></div>

<header class="appbar">
  <div class="row">
    <div style="width:10px;height:10px;background:#fff;border-radius:2px;opacity:.9"></div>
    <h1>PBL互动闯关：蔡先生“呼之不应”</h1>
    <small>15问全覆盖 · 计分闯关 · 随机抽题 · B站封面卡片</small>
  </div>
</header>

<main class="container">
  <nav class="toc" id="toc">
    <h3>目录</h3>
    <a href="#q1"><span>① Q1 呼之不应含义</span><span class="pill">互动</span></a>
    <a href="#q2"><span>② Q2 意识两维度</span><span class="pill">切换</span></a>
    <a href="#q3"><span>③ Q3 ARAS图解</span><span class="pill">动画</span></a>
    <a href="#q4"><span>④ Q4 快速分级</span><span class="pill">翻卡</span></a>
    <a href="#q5"><span>⑤ Q5 ABCDE</span><span class="pill">清单</span></a>
    <a href="#q6"><span>⑥ Q6 DONT</span><span class="pill">展开</span></a>
    <a href="#q7"><span>⑦ Q7 瞳孔反射</span><span class="pill">点按</span></a>
    <a href="#q8"><span>⑧ Q8 其他脑干反射</span><span class="pill">翻卡</span></a>
    <a href="#q9"><span>⑨ Q9 呼吸模式</span><span class="pill">小测</span></a>
    <a href="#q10"><span>⑩ Q10 正常呼吸音</span><span class="pill">对比</span></a>
    <a href="#q11"><span>⑪ Q11 湿啰音</span><span class="pill">小测</span></a>
    <a href="#q12"><span>⑫ Q12 体液分布</span><span class="pill">翻卡</span></a>
    <a href="#q13"><span>⑬ Q13 水肿机制</span><span class="pill">展开</span></a>
    <a href="#q14"><span>⑭ Q14 休克</span><span class="pill">流程</span></a>
    <a href="#q15"><span>⑮ Q15 血钾</span><span class="pill">急救</span></a>
    <a href="#videos"><span>🎬 B站封面卡片</span><span class="pill">自动</span></a>
    <a href="#game"><span>🏁 计分闯关</span><span class="pill">随机</span></a>
    <a href="#refs"><span>参考链接</span><span class="pill">权威</span></a>
    <p class="muted" style="margin:10px 6px 0;font-size:12px;">手机上目录不会挡住内容：点右下角“目录”打开/关闭。</p>
  </nav>

  <div class="section">
    <!-- The content is same as previous full version, trimmed for space but includes all 15 and game/video -->
    <!-- Q1 -->
    <section class="card" id="q1">
      <div class="kicker"><span class="dot"></span><span class="badge">Q1</span></div>
      <h2>“呼之不应”代表什么？</h2>
      <div class="grid2">
        <div class="callout">
          <b>一句话（PPT可用）</b>
          <p>对言语刺激无反应；并非诊断，而是危险信号：立刻按 ABCDE 处理，同时用 AVPU/GCS/脑干反射分级并查可逆病因。</p>
        </div>
        <div class="note">
          <b>本案提示</b>
          <ul style="margin-left:18px">
            <li>压眶反射存在</li>
            <li>瞳孔对光存在</li>
            <li>→ 更像浅昏迷/代谢或呼吸抑制</li>
          </ul>
        </div>
      </div>
      <hr class="sep">
      <h3>三步把“呼之不应”写成标准记录（逐条出）</h3>
      <div class="reveal">
        <button class="btn" data-reveal="s_q1">逐步展开</button>
        <button class="btn" data-reset="s_q1">重来</button>
      </div>
      <div class="step" data-step="s_q1"><b>Step 1：AVPU</b><div class="muted">先分到 V/P/U 哪一档。</div></div>
      <div class="step" data-step="s_q1"><b>Step 2：GCS（E/V/M）</b><div class="muted">“叫不应”至少 V=1；补 E 与 M。</div></div>
      <div class="step" data-step="s_q1"><b>Step 3：脑干+呼吸</b><div class="muted">瞳孔/角膜/眼头反射 + 异常呼吸模式。</div></div>
    </section>

    <!-- Q2 -->
    <section class="card" id="q2">
      <div class="kicker"><span class="dot"></span><span class="badge">Q2</span></div>
      <h2>意识两维度（点标签切换）</h2>
      <div class="tabs" data-tabs="t2">
        <button class="tab active" data-tab="p2a">觉醒</button>
        <button class="tab" data-tab="p2b">意识内容</button>
        <button class="tab" data-tab="p2c">组合</button>
      </div>
      <div class="panel active" id="p2a"><b>觉醒</b><div class="muted">像电源：ARAS 维持。</div></div>
      <div class="panel" id="p2b"><b>意识内容</b><div class="muted">像系统：皮层-丘脑网络整合。</div></div>
      <div class="panel" id="p2c">
        <div class="flashgrid">
          <div class="flash" data-flash><div class="inner">
            <div class="face front"><div><b>昏迷</b><div class="muted">觉醒↓ 内容↓</div></div><small>点我</small></div>
            <div class="face back"><div><b>特征</b>：不睁眼、无周期、反应差。</div><small>返回</small></div>
          </div></div>
          <div class="flash" data-flash><div class="inner">
            <div class="face front"><div><b>植物状态</b><div class="muted">觉醒↑ 内容↓</div></div><small>点我</small></div>
            <div class="face back"><div><b>特征</b>：会睁眼但缺乏有目的行为。</div><small>返回</small></div>
          </div></div>
        </div>
      </div>
    </section>

    <!-- Q3 -->
    <section class="card" id="q3">
      <div class="kicker"><span class="dot"></span><span class="badge">Q3</span></div>
      <h2>ARAS图解（脑干→丘脑→皮层）</h2>
      <div class="grid2">
        <div class="callout">
          <ul style="margin-left:18px">
            <li>ARAS = 觉醒“总开关”</li>
            <li>缺氧/高碳酸/药物 → 功能性抑制</li>
            <li>脑干/双侧丘脑损害 → 结构性断电</li>
          </ul>
        </div>
        <div>
          <svg class="flow" viewBox="0 0 360 220" aria-label="ARAS示意">
            <defs>
              <linearGradient id="g1" x1="0" x2="1">
                <stop offset="0%" stop-color="#0f6ddf"/><stop offset="100%" stop-color="#00d4ff"/>
              </linearGradient>
              <marker id="arrow" viewBox="0 0 10 10" refX="9" refY="5" markerWidth="7" markerHeight="7" orient="auto-start-reverse">
                <path d="M 0 0 L 10 5 L 0 10 z" fill="#00d4ff"/></marker>
            </defs>
            <rect x="0" y="0" width="360" height="220" rx="12" fill="none" stroke="var(--line)"/>
            <ellipse cx="230" cy="110" rx="110" ry="68" fill="none" stroke="var(--line)"/>
            <circle cx="88" cy="162" r="22" fill="none" stroke="var(--line)"/>
            <text x="74" y="170" font-size="12" fill="var(--muted)">脑干</text>
            <circle cx="182" cy="88" r="14" fill="none" stroke="var(--line)"/>
            <text x="170" y="95" font-size="12" fill="var(--muted)">丘脑</text>
            <path d="M100 150 C 130 120, 150 110, 168 98" class="arrow" stroke="url(#g1)" stroke-width="3" fill="none" marker-end="url(#arrow)"/>
            <path d="M190 88 C 220 92, 260 110, 300 118" class="arrow" stroke="url(#g1)" stroke-width="3" fill="none" marker-end="url(#arrow)"/>
            <text x="244" y="70" font-size="12" fill="var(--muted)">皮层</text>
          </svg>
        </div>
      </div>
    </section>

    <!-- Q4 -->
    <section class="card" id="q4">
      <div class="kicker"><span class="dot"></span><span class="badge">Q4</span></div>
      <h2>快速分级：AVPU/GCS/FOUR（翻卡）</h2>
      <div class="flashgrid">
        <div class="flash" data-flash><div class="inner">
          <div class="face front"><div><b>AVPU</b><div class="muted">分诊快</div></div><small>点我</small></div>
          <div class="face back"><div>按 A/V/P/U 快速定位意识等级。</div><small>返回</small></div>
        </div></div>
        <div class="flash" data-flash><div class="inner">
          <div class="face front"><div><b>GCS</b><div class="muted">趋势监测</div></div><small>点我</small></div>
          <div class="face back"><div>E/V/M 三项合计；“叫不应”常 V=1。</div><small>返回</small></div>
        </div></div>
        <div class="flash" data-flash><div class="inner">
          <div class="face front"><div><b>FOUR</b><div class="muted">含脑干</div></div><small>点我</small></div>
          <div class="face back"><div>加脑干反射+呼吸模式，插管也能评。</div><small>返回</small></div>
        </div></div>
        <div class="flash" data-flash><div class="inner">
          <div class="face front"><div><b>记录模板</b><div class="muted">一句写清</div></div><small>点我</small></div>
          <div class="face back"><div>例如：GCS 6；瞳孔3mm等大等圆+；压眶去除动作。</div><small>返回</small></div>
        </div></div>
      </div>
    </section>

    <!-- Q5 -->
    <section class="card" id="q5">
      <div class="kicker"><span class="dot"></span><span class="badge">Q5</span></div>
      <h2>ABCDE（清单讲稿）</h2>
      <div class="grid2">
        <div class="callout">
          <b>A</b> <span class="muted">气道保护/误吸</span><br>
          <b>B</b> <span class="muted">氧合/血气（缺氧/CO₂潴留）</span><br>
          <b>C</b> <span class="muted">血压/灌注/尿量</span><br>
          <b>D</b> <span class="muted">血糖+意识量表+瞳孔</span><br>
          <b>E</b> <span class="muted">体温/外伤/皮疹/药物线索</span>
        </div>
        <div class="note">
          <b>最怕漏</b>
          <ul style="margin-left:18px">
            <li>低血糖</li><li>低氧/高碳酸</li><li>休克低灌注</li><li>抽搐/感染</li>
          </ul>
        </div>
      </div>
    </section>

    <!-- Q6 -->
    <section class="card" id="q6">
      <div class="kicker"><span class="dot"></span><span class="badge">Q6</span></div>
      <h2>DONT（逐条展开）</h2>
      <div class="reveal">
        <button class="btn" data-reveal="s_dont">逐步展开</button>
        <button class="btn" data-reset="s_dont">重来</button>
      </div>
      <div class="step" data-step="s_dont"><b>D</b> Dextrose：<span class="muted">低血糖先测先纠正</span></div>
      <div class="step" data-step="s_dont"><b>O</b> Oxygen：<span class="muted">缺氧先纠正</span></div>
      <div class="step" data-step="s_dont"><b>N</b> Naloxone：<span class="muted">阿片可疑用</span></div>
      <div class="step" data-step="s_dont"><b>T</b> Thiamine：<span class="muted">高风险人群</span></div>
    </section>

    <!-- Q7 -->
    <section class="card" id="q7">
      <div class="kicker"><span class="dot"></span><span class="badge">Q7</span></div>
      <h2>瞳孔对光反射（点图）</h2>
      <div class="grid2">
        <div class="pupil" id="pupilBox" style="border:1px solid var(--line);border-radius:16px;padding:12px">
          <svg viewBox="0 0 360 160" aria-label="瞳孔对光">
            <rect x="0" y="0" width="360" height="160" rx="12" fill="none" stroke="var(--line)"/>
            <ellipse cx="110" cy="80" rx="58" ry="36" fill="#e8eefb"/>
            <ellipse cx="250" cy="80" rx="58" ry="36" fill="#e8eefb"/>
            <circle cx="110" cy="80" r="18" fill="#205b8f" class="p"/>
            <circle cx="250" cy="80" r="18" fill="#205b8f" class="p"/>
            <circle cx="110" cy="80" r="9" fill="#111827" class="p"/>
            <circle cx="250" cy="80" r="9" fill="#111827" class="p"/>
            <text x="14" y="24" font-size="12" fill="var(--muted)">点我：缩瞳/复原</text>
          </svg>
        </div>
        <div class="callout">
          <ul style="margin-left:18px">
            <li>传入：II</li><li>中枢：中脑</li><li>传出：III</li>
          </ul>
          <div class="muted">存在 → 通路尚存，更支持代谢/呼吸抑制或浅昏迷。</div>
        </div>
      </div>
    </section>

    <!-- Q8 -->
    <section class="card" id="q8">
      <div class="kicker"><span class="dot"></span><span class="badge">Q8</span></div>
      <h2>其他脑干反射（翻卡）</h2>
      <div class="flashgrid">
        <div class="flash" data-flash><div class="inner">
          <div class="face front"><div><b>角膜反射</b><div class="muted">V1→VII</div></div><small>点我</small></div>
          <div class="face back"><div>消失可提示深抑制/脑干受损。</div><small>返回</small></div>
        </div></div>
        <div class="flash" data-flash><div class="inner">
          <div class="face front"><div><b>眼头反射</b><div class="muted">Doll's eye</div></div><small>点我</small></div>
          <div class="face back"><div>前提：排除颈椎损伤。</div><small>返回</small></div>
        </div></div>
        <div class="flash" data-flash><div class="inner">
          <div class="face front"><div><b>咽/呛咳</b><div class="muted">气道保护</div></div><small>点我</small></div>
          <div class="face back"><div>差 → 误吸风险↑ 与插管相关。</div><small>返回</small></div>
        </div></div>
        <div class="flash" data-flash><div class="inner">
          <div class="face front"><div><b>痛刺激反应</b><div class="muted">M评分关键</div></div><small>点我</small></div>
          <div class="face back"><div>定位痛/去除/屈曲/伸展。</div><small>返回</small></div>
        </div></div>
      </div>
    </section>

    <!-- Q9 -->
    <section class="card" id="q9">
      <div class="kicker"><span class="dot"></span><span class="badge">Q9</span></div>
      <h2>异常呼吸模式（小测）</h2>
      <div class="grid2">
        <div class="quiz" data-quiz>
          <div class="q-head"><b>潮式呼吸更常提示？</b><span class="muted" style="font-size:12px;">单选</span></div>
          <div class="q-opts">
            <button class="opt" data-correct="1">中枢调控不稳（心衰/脑损伤等）</button>
            <button class="opt" data-correct="0">一定是肺炎</button>
            <button class="opt" data-correct="0">一定是阿片中毒</button>
            <button class="opt" data-correct="0">只能说明焦虑</button>
          </div>
          <div class="feedback muted"></div>
        </div>
        <div class="callout">
          <ul style="margin-left:18px">
            <li>Kussmaul：酸中毒代偿</li>
            <li>呼吸抑制：药物/CO₂潴留/脑干抑制</li>
          </ul>
        </div>
      </div>
    </section>

    <!-- Q10 -->
    <section class="card" id="q10">
      <div class="kicker"><span class="dot"></span><span class="badge">Q10</span></div>
      <h2>正常呼吸音（标签对比）</h2>
      <div class="tabs" data-tabs="t10">
        <button class="tab active" data-tab="p10a">肺泡音</button>
        <button class="tab" data-tab="p10b">支气管音</button>
        <button class="tab" data-tab="p10c">一句话</button>
      </div>
      <div class="panel active" id="p10a"><b>肺泡音</b><div class="muted">多数肺野，柔和，吸长呼短。</div></div>
      <div class="panel" id="p10b"><b>支气管音</b><div class="muted">气管/胸骨旁，音调高，时相更接近。</div></div>
      <div class="panel" id="p10c"><b>一句话</b><div class="muted">肺野听到“支气管音”要想实变/空洞/压缩。</div></div>
    </section>

    <!-- Q11 -->
    <section class="card" id="q11">
      <div class="kicker"><span class="dot"></span><span class="badge">Q11</span></div>
      <h2>湿啰音（小测+用法）</h2>
      <div class="grid2">
        <div class="callout">
          <ul style="margin-left:18px">
            <li>细湿：像捻发，常与肺泡开放/间质液体相关</li>
            <li>粗湿：分泌物多，咳嗽后可变</li>
          </ul>
        </div>
        <div class="quiz" data-quiz>
          <div class="q-head"><b>细湿啰音更常见于？</b><span class="muted" style="font-size:12px;">单选</span></div>
          <div class="q-opts">
            <button class="opt" data-correct="1">肺水肿/间质病变相关</button>
            <button class="opt" data-correct="0">一定哮喘</button>
            <button class="opt" data-correct="0">一定气胸</button>
            <button class="opt" data-correct="0">咽炎</button>
          </div>
          <div class="feedback muted"></div>
        </div>
      </div>
    </section>

    <!-- Q12 -->
    <section class="card" id="q12">
      <div class="kicker"><span class="dot"></span><span class="badge">Q12</span></div>
      <h2>体液分布（翻卡速记）</h2>
      <div class="flashgrid">
        <div class="flash" data-flash><div class="inner">
          <div class="face front"><div><b>TBW</b><div class="muted">50–60%</div></div><small>点我</small></div>
          <div class="face back"><div>总水量占体重约 50–60%。</div><small>返回</small></div>
        </div></div>
        <div class="flash" data-flash><div class="inner">
          <div class="face front"><div><b>ICF:ECF</b><div class="muted">2:1</div></div><small>点我</small></div>
          <div class="face back"><div>细胞内液≈2/3，细胞外液≈1/3。</div><small>返回</small></div>
        </div></div>
        <div class="flash" data-flash><div class="inner">
          <div class="face front"><div><b>ECF细分</b><div class="muted">间质/血浆</div></div><small>点我</small></div>
          <div class="face back"><div>ECF 内：间质≈3/4；血浆≈1/4。</div><small>返回</small></div>
        </div></div>
        <div class="flash" data-flash><div class="inner">
          <div class="face front"><div><b>连接意识</b><div class="muted">为什么昏迷</div></div><small>点我</small></div>
          <div class="face back"><div>脱水/休克→低灌注；低钠/高钠→神经元兴奋性改变。</div><small>返回</small></div>
        </div></div>
      </div>
    </section>

    <!-- Q13 -->
    <section class="card" id="q13">
      <div class="kicker"><span class="dot"></span><span class="badge">Q13</span></div>
      <h2>水肿机制（逐条展开）</h2>
      <div class="reveal">
        <button class="btn" data-reveal="s_ed">逐步展开</button>
        <button class="btn" data-reset="s_ed">重来</button>
      </div>
      <div class="step" data-step="s_ed"><b>静水压↑</b><div class="muted">心衰/静脉受阻。</div></div>
      <div class="step" data-step="s_ed"><b>胶体渗透压↓</b><div class="muted">低白蛋白。</div></div>
      <div class="step" data-step="s_ed"><b>通透性↑</b><div class="muted">炎症/败血症。</div></div>
      <div class="step" data-step="s_ed"><b>淋巴回流↓</b><div class="muted">回流受阻。</div></div>
    </section>

    <!-- Q14 -->
    <section class="card" id="q14">
      <div class="kicker"><span class="dot"></span><span class="badge">Q14</span></div>
      <h2>休克（四分型+目标）</h2>
      <div class="grid2">
        <div class="callout">
          <ul style="margin-left:18px">
            <li>低容量 / 心源性 / 分布性 / 阻塞性</li>
            <li>本质：组织灌注不足</li>
          </ul>
        </div>
        <div class="tree">
          <div class="node"><div class="icon bad">1</div><div><b>识别</b><div class="muted">MAP低、乳酸高、CRT延迟</div></div></div>
          <div class="node"><div class="icon warn">2</div><div><b>复苏</b><div class="muted">补液/升压按类型</div></div></div>
          <div class="node"><div class="icon ok">3</div><div><b>目标</b><div class="muted">MAP≥65、尿量≥0.5 ml·kg⁻¹·h⁻¹、乳酸下降</div></div></div>
        </div>
      </div>
    </section>

    <!-- Q15 -->
    <section class="card" id="q15">
      <div class="kicker"><span class="dot"></span><span class="badge">Q15</span></div>
      <h2>血钾（高钾急救三步）</h2>
      <div class="grid2">
        <div class="callout">
          <div><b>三步</b>：<span class="muted">稳膜 → 移钾入细胞 → 排钾出体</span></div>
          <div class="chips">
            <span class="chip">稳膜：钙剂</span>
            <span class="chip">移钾：胰岛素+糖 / β₂激动剂</span>
            <span class="chip">排钾：利尿/树脂/透析</span>
          </div>
        </div>
        <div class="quiz" data-quiz>
          <div class="q-head"><b>高钾急救最先做？</b><span class="muted" style="font-size:12px;">单选</span></div>
          <div class="q-opts">
            <button class="opt" data-correct="1">先稳膜：钙剂</button>
            <button class="opt" data-correct="0">先补钾</button>
            <button class="opt" data-correct="0">先口服利尿剂</button>
            <button class="opt" data-correct="0">先观察</button>
          </div>
          <div class="feedback muted"></div>
        </div>
      </div>
    </section>

    <!-- Videos -->
    <section class="card" id="videos">
      <div class="kicker"><span class="dot"></span><span class="badge">B站封面自动生成</span></div>
      <h2>粘贴B站链接 → 自动封面卡片</h2>
      <div class="grid2">
        <div class="callout">
          <textarea id="biliInput" style="width:100%;min-height:110px;border:1px solid var(--line);border-radius:14px;padding:10px;background:transparent;color:var(--text)"
            placeholder="一行一个：&#10;https://www.bilibili.com/video/BV1v9QoY9EFo"></textarea>
          <div style="display:flex;gap:8px;flex-wrap:wrap;margin-top:10px">
            <button class="btn" id="btnGen">生成卡片</button>
            <button class="btn" id="btnDemo">示例</button>
            <button class="btn" id="btnClear">清空</button>
          </div>
          <p class="muted" style="font-size:12px;margin-top:8px">如果封面加载失败，链接仍可点击打开。</p>
        </div>
        <div><div class="vgrid" id="biliCards"></div></div>
      </div>
    </section>

    <!-- Game -->
    <section class="card" id="game">
      <div class="kicker"><span class="dot"></span><span class="badge">计分闯关</span></div>
      <h2>随机抽题 · 计分 · 升级</h2>
      <div class="hud">
        <div class="scorebox">
          <div class="badge">Score：<span class="score" id="score">0</span></div>
          <div class="badge">Streak：<span class="score" id="streak">0</span></div>
          <div class="badge">Level：<span class="score" id="level">1</span></div>
        </div>
        <div style="display:flex;gap:10px;align-items:center;flex-wrap:wrap">
          <div class="bar"><div id="bar"></div></div>
          <button class="btn" id="btnResetGame">重置</button>
        </div>
      </div>
      <hr class="sep">
      <div class="quiz" id="randQuiz">
        <div class="q-head">
          <b id="rqTitle">点击“抽一题”开始</b>
          <span class="muted" style="font-size:12px;">题库覆盖15问</span>
        </div>
        <div class="q-opts" id="rqOpts"></div>
        <div class="feedback muted" id="rqFb"></div>
        <div style="display:flex;gap:8px;flex-wrap:wrap;margin-top:10px">
          <button class="btn" id="btnDraw">抽一题</button>
          <button class="btn" id="btnSkip">跳过</button>
        </div>
        <p class="muted" style="font-size:12px;margin-top:8px">规则：答对 +10；连对奖励 +2×连对数（上限+10）；每30分升1级。</p>
      </div>
    </section>

    <!-- Refs -->
    <section class="card" id="refs">
      <div class="kicker"><span class="dot"></span><span class="badge">权威</span></div>
      <h2>参考链接（超链接）</h2>
      <ul style="margin-left:18px">
        <li><a target="_blank" href="https://www.msdmanuals.com/professional/neurologic-disorders/coma-and-impaired-consciousness/overview-of-coma-and-impaired-consciousness">MSD Manual：昏迷与意识障碍概述</a></li>
        <li><a target="_blank" href="https://www.neurocriticalcare.org/Portals/0/Docs/ENLS/ENLS_V_4_0_Protocol_Coma_FINAL.pdf">ENLS：Coma Protocol（PDF）</a></li>
        <li><a target="_blank" href="https://www.glasgowcomascale.org/">GCS 官方站</a></li>
        <li><a target="_blank" href="https://med.stanford.edu/stanfordmedicine25/the25/pupillary.html">Stanford Medicine 25：瞳孔检查</a></li>
      </ul>
      <p class="footer">手机目录不遮挡版：右下角“目录”按钮打开/关闭侧抽屉。</p>
    </section>

    <p class="footer">© PBL互动课件（教学用途）</p>
  </div>
</main>

<script>
// progress bar
const prog=document.getElementById('prog');
window.addEventListener('scroll',()=>{
  const h=document.documentElement;
  const sc=(h.scrollTop)/(h.scrollHeight-h.clientHeight);
  prog.style.width=(sc*100).toFixed(1)+'%';
},{passive:true});

// toast
const toastEl=document.getElementById('toast');
let toastTimer=null;
function toast(msg){
  toastEl.textContent=msg;
  toastEl.classList.add('show');
  clearTimeout(toastTimer);
  toastTimer=setTimeout(()=>toastEl.classList.remove('show'),1400);
}

// mobile toc drawer
(function(){
  const toc=document.getElementById('toc');
  const btn=document.getElementById('tocToggle');
  const mask=document.getElementById('tocMask');
  function openT(){ toc.classList.add('open'); mask.classList.add('show'); mask.setAttribute('aria-hidden','false'); }
  function closeT(){ toc.classList.remove('open'); mask.classList.remove('show'); mask.setAttribute('aria-hidden','true'); }
  btn.addEventListener('click',()=> toc.classList.contains('open') ? closeT() : openT());
  mask.addEventListener('click',closeT);
  toc.addEventListener('click',(e)=>{
    const a=e.target.closest('a'); if(!a) return;
    if(window.matchMedia('(max-width:980px)').matches) closeT();
  });
  window.addEventListener('resize',()=>{ if(window.matchMedia('(min-width:981px)').matches) closeT(); },{passive:true});
})();

// Tabs
document.querySelectorAll('.tabs').forEach(tabs=>{
  tabs.addEventListener('click',e=>{
    const btn=e.target.closest('.tab'); if(!btn) return;
    tabs.querySelectorAll('.tab').forEach(b=>b.classList.remove('active'));
    btn.classList.add('active');
    const container=tabs.parentElement;
    container.querySelectorAll('.panel').forEach(p=>p.classList.remove('active'));
    const id=btn.getAttribute('data-tab');
    const panel=document.getElementById(id);
    if(panel) panel.classList.add('active');
  });
});

// Reveal steps
function resetSteps(key){ document.querySelectorAll(`[data-step="${key}"]`).forEach(s=>s.classList.remove('show')); }
function nextStep(key){
  const steps=[...document.querySelectorAll(`[data-step="${key}"]`)];
  const n=steps.find(s=>!s.classList.contains('show'));
  if(n) n.classList.add('show'); else toast('已全部展开 ✅');
}
document.addEventListener('click',e=>{
  const r=e.target.closest('[data-reveal]'); if(r) nextStep(r.getAttribute('data-reveal'));
  const rs=e.target.closest('[data-reset]'); if(rs){ resetSteps(rs.getAttribute('data-reset')); toast('已重置'); }
});

// Flashcards
document.querySelectorAll('[data-flash]').forEach(f=>{
  f.setAttribute('tabindex','0');
  const flip=()=>f.classList.toggle('flipped');
  f.addEventListener('click',flip);
  f.addEventListener('keydown',ev=>{ if(ev.key==='Enter' || ev.key===' '){ ev.preventDefault(); flip(); } });
});

// Inline quizzes
document.querySelectorAll('[data-quiz]').forEach(q=>{
  q.querySelectorAll('.opt').forEach(opt=>{
    opt.addEventListener('click',()=>{
      if(q.dataset.done) return;
      q.dataset.done="1";
      const correct=opt.getAttribute('data-correct')==='1';
      q.querySelectorAll('.opt').forEach(b=>{
        const isC=b.getAttribute('data-correct')==='1';
        b.classList.add(isC?'good':'bad');
      });
      const fb=q.querySelector('.feedback');
      fb.textContent = correct ? '✅ 正确！' : '❌ 不太对：回看本题提示。';
    });
  });
});

// Pupil
const pupilBox=document.getElementById('pupilBox');
if(pupilBox) pupilBox.addEventListener('click',()=>pupilBox.classList.toggle('touch'));

// Game state
const LS_KEY="pbl_game_state_v2";
let gameState={score:0,streak:0,level:1};
function loadGame(){ try{ const raw=localStorage.getItem(LS_KEY); if(raw) gameState=JSON.parse(raw);}catch(e){} renderGame(); }
function saveGame(){ try{ localStorage.setItem(LS_KEY, JSON.stringify(gameState)); }catch(e){} }
function calcLevel(score){ return Math.max(1, Math.floor(score/30)+1); }
function renderGame(){
  document.getElementById('score').textContent=gameState.score;
  document.getElementById('streak').textContent=gameState.streak;
  gameState.level=calcLevel(gameState.score);
  document.getElementById('level').textContent=gameState.level;
  const pct=Math.min(100, ((gameState.score%30)/30)*100);
  document.getElementById('bar').style.width=pct.toFixed(0)+'%';
}
function addScore(base){
  const bonus=Math.min(10, gameState.streak*2);
  gameState.score += base + bonus;
  gameState.streak += 1;
  saveGame(); renderGame();
  toast(`+${base+bonus} 分（连对 +${bonus}）`);
}
function resetGame(){
  gameState={score:0,streak:0,level:1};
  saveGame(); renderGame(); toast('成绩已重置');
}
document.getElementById('btnResetGame').addEventListener('click', resetGame);

// Random bank
const BANK=[
  {q:"“呼之不应”最准确含义？", a:["确诊卒中","对声刺激无反应需进一步评估","一定脑死亡","一定精神因素"], c:1, e:"床旁描述不是诊断；先救命再定位。"},
  {q:"意识两维度？", a:["记忆与语言","觉醒与意识内容","呼吸与循环","感觉与运动"], c:1, e:"觉醒像电源，内容像系统。"},
  {q:"首要原则？", a:["先MRI","先ABCDE与血糖/氧合","先腰穿","先等家属"], c:1, e:"先处理可逆致命因素。"},
  {q:"瞳孔对光存在更支持？", a:["脑死亡","浅昏迷/代谢抑制可能","必为锁闭","必为散瞳药"], c:1, e:"提示通路尚存。"},
  {q:"U in AVPU？", a:["清醒","对声反应","仅对痛","对痛也无反应"], c:3, e:"Unresponsive。"},
  {q:"GCS三项？", a:["呼吸/循环/体温","眼/言语/运动","瞳孔/角膜/咽","乳酸/血压/血氧"], c:1, e:"E V M。"},
  {q:"Naloxone用于？", a:["低血糖","阿片可疑呼吸抑制","所有昏迷","高钾"], c:1, e:"阿片拮抗。"},
  {q:"做眼头反射前提？", a:["先喝水","排除颈椎损伤","必须MRI","必须镇静"], c:1, e:"有颈椎风险禁止。"},
  {q:"Kussmaul呼吸提示？", a:["酸中毒代偿","焦虑","鼻炎","气胸"], c:0, e:"深大呼吸代偿。"},
  {q:"肺野支气管音提示？", a:["实变/空洞/压缩","一定正常","一定哮喘","一定气胸"], c:0, e:"实变传导增强。"},
  {q:"细湿啰音多见？", a:["肺水肿/间质相关","一定哮喘","一定气胸","咽炎"], c:0, e:"液体与肺泡开放。"},
  {q:"TBW约占体重？", a:["10%","30%","50–60%","90%"], c:2, e:"常用记忆。"},
  {q:"水肿因素不包括？", a:["静水压","胶体渗透压","通透性","肺活量"], c:3, e:"Starling因素不含肺活量。"},
  {q:"休克本质？", a:["发热","组织灌注不足","低钙","贫血"], c:1, e:"最终是灌注不够。"},
  {q:"高钾急救第一步？", a:["钙剂稳膜","补钾","观察","多喝水"], c:0, e:"先稳膜防致死心律失常。"},
];

let current=null;
const rqTitle=document.getElementById('rqTitle');
const rqOpts=document.getElementById('rqOpts');
const rqFb=document.getElementById('rqFb');
function drawQuestion(){
  const idx=Math.floor(Math.random()*BANK.length);
  current={...BANK[idx]};
  rqTitle.textContent=`随机题：${current.q}`;
  rqFb.textContent=""; rqOpts.innerHTML="";
  current.a.forEach((txt,i)=>{
    const b=document.createElement('button'); b.className='opt'; b.textContent=txt;
    b.addEventListener('click',()=>answer(i));
    rqOpts.appendChild(b);
  });
}
function answer(i){
  if(!current) return;
  const buttons=[...rqOpts.querySelectorAll('.opt')];
  buttons.forEach((b,bi)=>{
    const isC=bi===current.c;
    b.classList.add(isC?'good':'bad'); b.disabled=true;
  });
  const correct=i===current.c;
  if(correct){ addScore(10); rqFb.textContent=`✅ 正确！${current.e}`; }
  else{ gameState.streak=0; saveGame(); renderGame(); toast('❌ 连对中断'); rqFb.textContent=`❌ 正确答案：${current.a[current.c]}。${current.e}`; }
  current=null;
}
document.getElementById('btnDraw').addEventListener('click', drawQuestion);
document.getElementById('btnSkip').addEventListener('click', ()=>{ rqTitle.textContent="已跳过。点“抽一题”继续。"; rqOpts.innerHTML=""; rqFb.textContent=""; current=null; });
loadGame();

// Bilibili oEmbed cards
const demoLinks=[
  "https://www.bilibili.com/video/BV1v9QoY9EFo",
  "https://www.bilibili.com/video/BV1bRsLeUEXd",
  "https://www.bilibili.com/video/av854986175",
  "https://www.bilibili.com/video/BV1z64y1S7Cr"
];
function normalizeLine(s){ return (s||"").trim(); }
function toOembedUrl(url){ return `https://www.bilibili.com/oembed?url=${encodeURIComponent(url)}`; }
async function fetchOembed(url){
  const res=await fetch(toOembedUrl(url), {mode:'cors'});
  if(!res.ok) throw new Error('oembed failed');
  return await res.json();
}
function cardEl({title, thumbnail_url, author_name, provider_name, url}){
  const d=document.createElement('div'); d.className='vcard';
  const th=document.createElement('div'); th.className='vthumb';
  if(thumbnail_url){ const img=document.createElement('img'); img.src=thumbnail_url; img.alt=title||'封面'; th.appendChild(img); }
  else th.textContent='封面加载失败';
  const body=document.createElement('div'); body.className='vbody';
  const t=document.createElement('div'); t.className='vtitle'; t.textContent=title||'未命名视频';
  const meta=document.createElement('div'); meta.className='vmeta'; meta.textContent=`${provider_name||'Bilibili'} · ${author_name||'UP主'}`;
  const link=document.createElement('a'); link.href=url; link.target='_blank'; link.textContent='打开视频 ↗'; link.style.display='inline-block'; link.style.marginTop='6px';
  body.appendChild(t); body.appendChild(meta); body.appendChild(link);
  d.appendChild(th); d.appendChild(body);
  return d;
}
async function generateCards(lines){
  const box=document.getElementById('biliCards'); box.innerHTML="";
  const urls=lines.map(normalizeLine).filter(Boolean);
  if(urls.length===0){ toast('先粘贴链接'); return; }
  toast('生成封面中…');
  for(const url of urls){
    const ph=document.createElement('div');
    ph.className='vcard';
    ph.innerHTML=`<div class="vthumb">加载中…</div><div class="vbody"><div class="vtitle">正在获取信息</div><div class="vmeta">${url}</div></div>`;
    box.appendChild(ph);
    try{
      const data=await fetchOembed(url);
      box.replaceChild(cardEl(data), ph);
    }catch(e){
      ph.querySelector('.vthumb').textContent='封面/信息获取失败';
      ph.querySelector('.vtitle').textContent='仍可点击打开';
      const a=document.createElement('a'); a.href=url; a.target='_blank'; a.textContent='打开视频 ↗';
      a.style.display='inline-block'; a.style.marginTop='6px';
      ph.querySelector('.vbody').appendChild(a);
    }
  }
  toast('完成 ✅');
}
document.getElementById('btnGen').addEventListener('click', ()=>{
  const lines=document.getElementById('biliInput').value.split('\n');
  generateCards(lines);
});
document.getElementById('btnDemo').addEventListener('click', ()=>{ document.getElementById('biliInput').value=demoLinks.join('\n'); toast('已填示例'); });
document.getElementById('btnClear').addEventListener('click', ()=>{ document.getElementById('biliInput').value=''; document.getElementById('biliCards').innerHTML=''; toast('已清空'); });
</script>
</body>
</html>
