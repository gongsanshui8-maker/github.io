# github.io
    font-size:clamp(54px,8vw,108px);font-weight:300;line-height:.92;
    letter-spacing:-.055em;margin:0 0 34px;
  }
  .hero p{max-width:470px;font-size:15px;color:#67675f;margin:0}
  .hero-visual{
    height:66vh;min-height:520px;position:relative;overflow:hidden;
    background:#d9d0bf;
  }
  .hero-visual:before{
    content:"";position:absolute;inset:12% 15% 8% 18%;
    background:
      radial-gradient(circle at 30% 25%,#eee9dc 0 12%,transparent 13%),
      linear-gradient(145deg,#a9a28f,#d7d0bf 48%,#918d7c);
    filter:saturate(.5);
  }
  .hero-visual:after{
    content:"";position:absolute;width:70%;height:32%;
    left:10%;bottom:8%;border-radius:48%;
    background:repeating-linear-gradient(8deg,#b7ae9b 0 2px,#d8d1c1 2px 5px);
    transform:rotate(-8deg);opacity:.82;
  }
  .hero-label{
    position:absolute;left:22px;bottom:20px;font-size:9px;
    letter-spacing:.2em;color:#f5f2e9;z-index:2;
  }
  .section{padding:110px 7vw}
  .section-head{display:flex;justify-content:space-between;gap:40px;align-items:end;margin-bottom:55px}
  .section-number{font-size:11px;letter-spacing:.2em;color:#8a897f}
  h2{font-size:42px;font-weight:300;letter-spacing:-.035em;margin:8px 0 0}
  .intro{max-width:380px;color:#74736b;font-size:13px}
  .grid{display:grid;grid-template-columns:repeat(12,1fr);gap:18px}
  .card{position:relative;overflow:hidden;background:#ddd8ca;min-height:320px}
  .card.tall{min-height:520px}
  .card.wide{min-height:300px}
  .card span{position:absolute;left:18px;bottom:16px;color:#fff;font-size:9px;letter-spacing:.16em;z-index:2}
  .c1{grid-column:span 7}.c2{grid-column:span 5}.c3{grid-column:span 4}.c4{grid-column:span 8}
  .material{
    background:
      radial-gradient(circle at 65% 20%,#f4efe2 0 9%,transparent 10%),
      repeating-linear-gradient(18deg,#b8b09d 0 2px,#d8d0bd 2px 5px,#aaa18d 5px 7px);
  }
  .yarn{
    background:
      radial-gradient(ellipse at 48% 48%,#b9b09e 0 25%,#8c8779 26% 28%,#c9c1b0 29% 45%,#787568 46% 48%,#cfc7b7 49% 62%,#a29b8a 63%),
      #c7c0b1;
  }
  .fabric{
    background:
      repeating-linear-gradient(90deg,rgba(255,255,255,.2) 0 1px,transparent 1px 7px),
      repeating-linear-gradient(0deg,rgba(100,96,82,.16) 0 1px,transparent 1px 7px),
      linear-gradient(145deg,#dad2c1,#999485);
  }
  .garment{
    background:
      radial-gradient(ellipse at 50% 30%,#8d8b7d 0 18%,transparent 19%),
      linear-gradient(155deg,#c8c0ae,#77756a 60%,#aca492);
  }
  .life{
    background:
      radial-gradient(circle at 72% 28%,#eee9db 0 12%,transparent 13%),
      linear-gradient(135deg,#d8d1c2 0 42%,#969080 43% 68%,#c6bdab 69%);
  }
  .craft{
    background:
      repeating-linear-gradient(115deg,#817d6f 0 2px,#b8b09d 2px 5px,#716d61 5px 7px),
      #aaa292;
  }
  .manifesto{
    padding:125px 7vw;background:#2f302b;color:#eeece3;
    display:grid;grid-template-columns:1fr 1fr;gap:8vw;
  }
  .manifesto h2{font-size:56px;line-height:1.05}
  .manifesto p{color:#c5c3ba;font-size:14px;max-width:430px}
  .formula{
    border-top:1px solid #5b5b53;margin-top:45px;padding-top:20px;
    font-size:11px;letter-spacing:.14em;color:#c8c5ba;
  }
  .series{padding:110px 7vw}
  .series-list{border-top:1px solid #c9c7bd}
  .series-item{
    display:grid;grid-template-columns:70px 1fr 1fr 80px;gap:25px;
    padding:24px 0;border-bottom:1px solid #c9c7bd;align-items:center;
  }
  .series-item b{font-size:22px;font-weight:300}
  .series-item p{margin:0;font-size:12px;color:#77766e}
  .series-item i{font-style:normal;font-size:10px;letter-spacing:.15em;color:#88877e;text-align:right}
  .footer{
    padding:70px 7vw 90px;border-top:1px solid #d4d2c8;
    display:flex;justify-content:space-between;gap:30px;
    color:#77766d;font-size:10px;letter-spacing:.12em;
  }
  @media(max-width:760px){
    .nav{padding:0 20px}.hero{display:block;padding:55px 25px}
    .hero-visual{margin-top:50px;height:65vh;min-height:440px}
    .section,.series{padding:80px 25px}
    .section-head{display:block}.intro{margin-top:25px}
    .c1,.c2,.c3,.c4{grid-column:span 12}.card.tall{min-height:390px}
    .manifesto{grid-template-columns:1fr;padding:80px 25px}
    .series-item{grid-template-columns:45px 1fr;gap:10px}
    .series-item p{grid-column:2}.series-item i{display:none}
    .footer{padding:50px 25px;display:block}.footer span{display:block;margin-top:15px}
  }
</style>
</head>

<body>
<div class="page">

<header class="nav">
  <div class="brand">法布云端</div>
  <small>FABRICS CLOUD / MATERIAL EDITORIAL</small>
</header>

<main>

<section class="hero">
  <div>
    <div class="eyebrow">MATERIAL · YARN · FABRIC · GARMENT · LIFE</div>
    <h1>Material<br>in Life.</h1>
    <p>
      从天然纤维出发，穿过纱线、面料与成衣，
      进入真实生活。法布云端以材料为核心，
      建立属于纺织品牌自己的视觉档案与编辑语言。
    </p>
  </div>
  <div class="hero-visual">
    <div class="hero-label">FABRICS CLOUD / MATERIAL 01</div>
  </div>
</section>

<section class="section">
  <div class="section-head">
    <div>
      <div class="section-number">01 — ORIGIN</div>
      <h2>天然纤维，作为起点</h2>
    </div>
    <p class="intro">
      不追求夸张的产品展示，而是放大纤维本身的结构、
      触感与自然的不规则，让材料成为第一主角。
    </p>
  </div>

  <div class="grid">
    <div class="card c1 tall material"><span>RAW FIBER / NATURAL ORIGIN</span></div>
    <div class="card c2 yarn"><span>YARN / MATERIAL STUDY</span></div>
    <div class="card c3 fabric"><span>TEXTURE / WEAVE</span></div>
    <div class="card c4 craft"><span>CRAFT / TEXTILE ARCHIVE</span></div>
  </div>
</section>

<section class="manifesto">
  <div>
    <div class="section-number">FABRICS CLOUD</div>
    <h2>不是一张<br>漂亮的图片。</h2>
  </div>
  <div>
    <p>
      法布云端的视觉不以“产品摆拍”为终点。
      每一张图片都是材料故事的一帧：
      原料如何成为纱线，纱线如何形成织物，
      织物如何成为成衣，最后进入人的生活。
    </p>
    <div class="formula">
      MATERIAL → YARN → FABRIC → GARMENT → LIFE
    </div>
  </div>
</section>

<section class="section">
  <div class="section-head">
    <div>
      <div class="section-number">02 — YARN</div>
      <h2>纱线，是材料的语言</h2>
    </div>
    <p class="intro">
      让纱线筒不再是孤立的商品，而成为材料向面料、
      成衣转化的视觉起点。
    </p>
  </div>

  <div class="grid">
    <div class="card c2 tall yarn"><span>YARN SPOOL / DETAIL</span></div>
    <div class="card c1 tall fabric"><span>YARN → TEXTURE</span></div>
    <div class="card c4 wide material"><span>FIBER / YARN / FABRIC RELATIONSHIP</span></div>
    <div class="card c3 wide craft"><span>CRAFT / HAND / PROCESS</span></div>
  </div>
</section>

<section class="section">
  <div class="section-head">
    <div>
      <div class="section-number">03 — GARMENT</div>
