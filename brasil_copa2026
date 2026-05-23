<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Brasil na Copa 2026 — A fé supera qualquer ranking!</title>
  <link href="https://fonts.googleapis.com/css2?family=Bebas+Neue&family=Nunito:wght@400;600;700;800&display=swap" rel="stylesheet" />
  <style>
    *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

    :root {
      --verde: #009c3b;
      --amarelo: #ffdf00;
      --azul: #002776;
      --branco: #ffffff;
      --cinza-claro: #f4f6f0;
      --cinza-medio: #e0e5d8;
      --texto: #1a1f14;
      --texto-sec: #4a5240;
      --radius: 14px;
      --radius-sm: 8px;
    }

    body {
      font-family: 'Nunito', sans-serif;
      background: var(--cinza-claro);
      color: var(--texto);
      line-height: 1.7;
    }

    /* ── HERO ── */
    .hero {
      background: var(--azul);
      padding: 70px 24px 60px;
      text-align: center;
      position: relative;
      overflow: hidden;
    }
    .hero::before {
      content: '';
      position: absolute;
      inset: 0;
      background: repeating-linear-gradient(
        135deg,
        transparent,
        transparent 40px,
        rgba(255,223,0,0.04) 40px,
        rgba(255,223,0,0.04) 80px
      );
    }
    .hero-badge {
      display: inline-block;
      background: var(--amarelo);
      color: var(--azul);
      font-size: 12px;
      font-weight: 800;
      letter-spacing: 0.12em;
      text-transform: uppercase;
      padding: 5px 16px;
      border-radius: 20px;
      margin-bottom: 20px;
    }
    .hero h1 {
      font-family: 'Bebas Neue', sans-serif;
      font-size: clamp(42px, 8vw, 88px);
      color: var(--amarelo);
      line-height: 1;
      letter-spacing: 0.02em;
      position: relative;
    }
    .hero h1 span { color: var(--branco); }
    .hero-sub {
      font-size: clamp(15px, 2.5vw, 19px);
      color: rgba(255,255,255,0.75);
      max-width: 560px;
      margin: 18px auto 0;
      position: relative;
    }

    /* ── CONTAINER ── */
    .container {
      max-width: 860px;
      margin: 0 auto;
      padding: 0 20px;
    }

    /* ── SECTIONS ── */
    section { padding: 56px 0; }
    section + section { border-top: 1.5px solid var(--cinza-medio); }

    .section-eyebrow {
      display: inline-flex;
      align-items: center;
      gap: 8px;
      font-size: 11px;
      font-weight: 800;
      letter-spacing: 0.12em;
      text-transform: uppercase;
      color: var(--verde);
      margin-bottom: 12px;
    }
    .section-eyebrow::before {
      content: '';
      display: inline-block;
      width: 20px;
      height: 3px;
      background: var(--verde);
      border-radius: 2px;
    }

    h2 {
      font-family: 'Bebas Neue', sans-serif;
      font-size: clamp(30px, 5vw, 46px);
      color: var(--azul);
      line-height: 1.05;
      margin-bottom: 16px;
    }

    p { font-size: 16px; color: var(--texto-sec); margin-bottom: 16px; }
    p:last-child { margin-bottom: 0; }

    strong { color: var(--texto); font-weight: 700; }

    .highlight-box {
      background: var(--azul);
      border-radius: var(--radius);
      padding: 28px 32px;
      margin: 28px 0;
      position: relative;
      overflow: hidden;
    }
    .highlight-box::after {
      content: '🇧🇷';
      position: absolute;
      right: 24px;
      top: 50%;
      transform: translateY(-50%);
      font-size: 56px;
      opacity: 0.15;
    }
    .highlight-box p {
      color: rgba(255,255,255,0.85);
      font-size: 17px;
      margin: 0;
    }
    .highlight-box strong { color: var(--amarelo); }

    .fe-box {
      background: var(--amarelo);
      border-radius: var(--radius);
      padding: 28px 32px;
      margin: 28px 0;
    }
    .fe-box p {
      color: var(--azul);
      font-size: 17px;
      margin: 0;
      font-weight: 700;
    }

    /* ── CARDS DE STATS ── */
    .stats-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(160px, 1fr));
      gap: 12px;
      margin: 28px 0;
    }
    .stat-card {
      background: var(--branco);
      border-radius: var(--radius-sm);
      padding: 18px 16px;
      border: 1.5px solid var(--cinza-medio);
      text-align: center;
    }
    .stat-val {
      font-family: 'Bebas Neue', sans-serif;
      font-size: 38px;
      color: var(--azul);
      line-height: 1;
      margin-bottom: 4px;
    }
    .stat-val.verde { color: var(--verde); }
    .stat-lbl { font-size: 12px; color: var(--texto-sec); font-weight: 600; }

    /* ── PAINÉIS INTERATIVOS ── */
    .panel-section {
      background: var(--branco);
      border-radius: var(--radius);
      border: 1.5px solid var(--cinza-medio);
      padding: 28px;
      margin: 28px 0;
    }
    .panel-title {
      font-family: 'Bebas Neue', sans-serif;
      font-size: 22px;
      color: var(--azul);
      margin-bottom: 4px;
    }
    .panel-desc { font-size: 13px; color: var(--texto-sec); margin-bottom: 20px; }

    /* grupos */
    .match-card {
      background: var(--cinza-claro);
      border-radius: var(--radius-sm);
      padding: 14px 16px;
      margin-bottom: 10px;
      border: 1px solid var(--cinza-medio);
    }
    .match-header { display: flex; justify-content: space-between; align-items: center; margin-bottom: 10px; }
    .match-date { font-size: 11px; color: var(--texto-sec); font-weight: 600; }
    .match-badge { font-size: 10px; padding: 2px 9px; border-radius: 20px; font-weight: 700; }
    .teams-row { display: flex; align-items: center; gap: 10px; margin-bottom: 12px; }
    .team-block { flex: 1; text-align: center; }
    .team-flag-big { font-size: 28px; display: block; margin-bottom: 3px; }
    .team-name { font-size: 13px; font-weight: 700; color: var(--texto); }
    .team-pts { font-size: 11px; color: var(--texto-sec); }
    .vs-block { font-size: 14px; color: var(--texto-sec); font-weight: 800; }
    .prob-row { display: flex; align-items: center; gap: 8px; margin-bottom: 5px; }
    .prob-label { font-size: 12px; color: var(--texto-sec); min-width: 80px; font-weight: 600; }
    .prob-bar-outer { flex: 1; height: 8px; background: var(--cinza-medio); border-radius: 6px; overflow: hidden; }
    .prob-bar-inner { height: 100%; border-radius: 6px; transition: width 0.4s ease; }
    .prob-val { font-size: 12px; font-weight: 700; min-width: 38px; text-align: right; }

    /* mata-mata */
    .mata-card {
      background: var(--cinza-claro);
      border-radius: var(--radius-sm);
      border: 1.5px solid var(--cinza-medio);
      padding: 14px 16px;
      margin-bottom: 10px;
    }
    .mata-card.destaque { border-color: var(--verde); }
    .mata-card.final { border-color: var(--amarelo); border-width: 2px; }
    .mata-header { display: flex; justify-content: space-between; align-items: center; margin-bottom: 8px; }
    .mata-phase { font-size: 11px; font-weight: 800; color: var(--azul); text-transform: uppercase; letter-spacing: 0.05em; }
    .mata-badge { font-size: 10px; padding: 2px 8px; border-radius: 20px; font-weight: 700; }
    .mteam { display: flex; align-items: center; gap: 8px; padding: 3px 0; }
    .mteam-flag { font-size: 16px; }
    .mteam-name { font-size: 13px; font-weight: 700; color: var(--texto); flex: 1; }
    .mteam-bar-outer { width: 44px; height: 5px; background: var(--cinza-medio); border-radius: 3px; overflow: hidden; }
    .mteam-bar-inner { height: 100%; border-radius: 3px; }
    .mteam-prob { font-size: 11px; font-weight: 700; }
    .mata-footer { display: flex; justify-content: space-between; align-items: center; margin-top: 8px; padding-top: 8px; border-top: 1px solid var(--cinza-medio); font-size: 11px; color: var(--texto-sec); }

    /* controles */
    .control-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(180px, 1fr)); gap: 10px; margin-bottom: 20px; }
    .control-item label { font-size: 11px; font-weight: 700; color: var(--texto-sec); display: block; margin-bottom: 5px; text-transform: uppercase; letter-spacing: 0.05em; }
    select, input[type=range] { width: 100%; font-family: 'Nunito', sans-serif; }
    select { font-size: 13px; padding: 7px 10px; border-radius: var(--radius-sm); border: 1.5px solid var(--cinza-medio); background: var(--branco); color: var(--texto); font-weight: 600; }
    .slider-row { display: flex; align-items: center; gap: 8px; }
    .slider-val { font-size: 13px; font-weight: 700; color: var(--azul); min-width: 40px; }
    input[type=range] { accent-color: var(--verde); }

    /* summary metrics */
    .metrics-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(130px, 1fr)); gap: 10px; margin-bottom: 20px; }
    .metric-card { background: var(--cinza-claro); border-radius: var(--radius-sm); padding: 12px 14px; border: 1px solid var(--cinza-medio); }
    .metric-val { font-family: 'Bebas Neue', sans-serif; font-size: 28px; color: var(--azul); line-height: 1; margin-bottom: 2px; }
    .metric-lbl { font-size: 11px; color: var(--texto-sec); font-weight: 600; }
    .metric-card.destaque { border-color: var(--verde); background: #f0faf4; }
    .metric-card.destaque .metric-val { color: var(--verde); }

    /* ── FOOTER ── */
    footer {
      background: var(--azul);
      color: rgba(255,255,255,0.6);
      text-align: center;
      padding: 36px 20px;
      font-size: 13px;
    }
    footer strong { color: var(--amarelo); }

    /* ── ANIMATIONS ── */
    @keyframes fadeUp {
      from { opacity: 0; transform: translateY(24px); }
      to   { opacity: 1; transform: translateY(0); }
    }
    .hero > * { animation: fadeUp 0.6s ease both; }
    .hero-badge { animation-delay: 0.1s; }
    .hero h1    { animation-delay: 0.2s; }
    .hero-sub   { animation-delay: 0.35s; }
  </style>
</head>
<body>

<!-- HERO -->
<div class="hero">
  <div class="hero-badge">Copa do Mundo 2026 · EUA, Canadá e México</div>
  <h1>Brasil na Copa:<br><span>A Fé</span> Não Tem Ranking</h1>
  <p class="hero-sub">Os números dizem uma coisa. O coração verde-amarelo diz outra. A gente acredita assim mesmo — e isso, meu amigo, não tem ciência de dados que explique.</p>
</div>

<!-- SEÇÃO 1: CONTEXTO -->
<section>
  <div class="container">
    <div class="section-eyebrow">O panorama</div>
    <h2>Vamos ser honestos: não estamos no topo</h2>

    <p>
      Olha, a gente tem que admitir. O ranking FIFA de abril de 2026 coloca o Brasil na <strong>6ª posição</strong>, com 1.761 pontos. Lá na frente estão França, Espanha e Argentina, quase empatadas no topo, com menos de 3 pontos de diferença entre elas. É um pelotão de elite que a gente vai precisar superar para levantar a taça.
    </p>

    <p>
      A Copa de 2026 é diferente de tudo que já vimos. Pela primeira vez na história são <strong>48 seleções</strong>, 12 grupos e um mata-mata de 5 fases. Mais jogos, mais surpresas, mais chances de zebra. E sabe o que isso significa? Que até chegar na final, o Brasil pode cruzar com adversários pesados em cada fase. O caminho não é fácil — mas quando foi?
    </p>

    <div class="stats-grid">
      <div class="stat-card">
        <div class="stat-val">6º</div>
        <div class="stat-lbl">Brasil no ranking FIFA (abril 2026)</div>
      </div>
      <div class="stat-card">
        <div class="stat-val">1761</div>
        <div class="stat-lbl">Pontos FIFA do Brasil</div>
      </div>
      <div class="stat-card">
        <div class="stat-val verde">5x</div>
        <div class="stat-lbl">Campeão mundial — mais que qualquer outro</div>
      </div>
      <div class="stat-card">
        <div class="stat-val">48</div>
        <div class="stat-lbl">Seleções na Copa 2026</div>
      </div>
    </div>

    <p>
      O modelo matemático que construímos aqui usa a própria fórmula da FIFA — o sistema <strong>SUM</strong> — para calcular a probabilidade de vencer cada jogo. A lógica é simples: quanto maior a diferença de pontos entre dois times, maior a chance do mais forte vencer. Justo. Mas futebol, como todo brasileiro sabe, não funciona sempre assim.
    </p>

    <div class="highlight-box">
      <p>
        <strong>O grupo do Brasil (Grupo C)</strong> é considerado um dos mais difíceis da Copa. Marrocos (8º no mundo, 1.755 pontos) está logo atrás de nós no ranking — é quase um mata-mata disfarçado de fase de grupos. Escócia e Haiti completam a chave. <strong>Primeira rodada já é decisão.</strong>
      </p>
    </div>
  </div>
</section>

<!-- PAINEL 1: FASE DE GRUPOS -->
<section>
  <div class="container">
    <div class="section-eyebrow">Ciência de dados</div>
    <h2>Jogo a jogo: o que dizem os números</h2>
    <p>Usando a fórmula real da FIFA (sistema SUM), calculamos a probabilidade do Brasil vencer cada jogo da fase de grupos. Use o slider para simular diferentes formas do time.</p>

    <div class="panel-section">
      <div class="panel-title">Fase de grupos — Grupo C</div>
      <p class="panel-desc">Probabilidades baseadas nos pontos FIFA reais de cada seleção (abril 2026).</p>

      <div class="control-grid">
        <div class="control-item">
          <label>Forma recente do Brasil</label>
          <div class="slider-row">
            <input type="range" min="-80" max="80" step="1" value="0" id="g-forma" oninput="renderGrupos()">
            <span class="slider-val" id="g-forma-out">0 pts</span>
          </div>
        </div>
      </div>

      <div id="grupos-matches"></div>
    </div>
  </div>
</section>

<!-- SEÇÃO 2: A FÉ -->
<section>
  <div class="container">
    <div class="section-eyebrow">O lado que os números não capturam</div>
    <h2>Mas a gente acredita. E muito.</h2>

    <p>
      Probabilidade de 10%? Tudo bem. A gente já viu seleções com ranking pior do que o nosso levantar a taça. Marrocos foi à semifinal em 2022. A Argentina ficou fora em 2002. O futebol tem um gosto todo especial de virar a mesa quando a ciência aponta para o outro lado.
    </p>

    <p>
      O Brasil é o único pentacampeão do mundo. Fomos à Copa de 2026 com uma geração nova, com fome de título, com a pressão de uma nação inteira nas costas — e sabe de uma coisa? A gente carrega esse peso com orgulho. É pesado, mas é nosso.
    </p>

    <div class="fe-box">
      <p>💚 "A gente não vai porque os números mandam. A gente vai porque é o Brasil. E o Brasil sempre acredita."</p>
    </div>

    <p>
      Claro que gostaríamos de estar no top 3 do ranking. Claro que um caminho mais fácil seria bem-vindo. Mas o destino quis colocar Marrocos na nossa estreia, uma possível Argentina na semi e uma provável França ou Espanha na final. Sabe o que isso quer dizer? Que quando a gente levantar a taça, ninguém vai poder dizer que foi fácil. E vai ser ainda mais bonito.
    </p>

    <p>
      Então pode continuar, modelo matemático. Pode mostrar seus 10%, seus 8%, seus "Brasil não é favorito". A gente vai lá de qualquer jeito. Com a camisa, com o coração e com aquela fé irracional que só quem é brasileiro entende.
    </p>
  </div>
</section>

<!-- PAINEL 2: MATA-MATA -->
<section>
  <div class="container">
    <div class="section-eyebrow">Simulação do mata-mata</div>
    <h2>Caminho do Brasil até a final</h2>
    <p>Monte o cenário que você acredita. Escolha os adversários de cada fase e veja como as probabilidades se acumulam — e torça para que a fé supere a matemática!</p>

    <div class="panel-section">
      <div class="panel-title">Da fase de 16 avos à final</div>
      <p class="panel-desc">Probabilidades calculadas pela fórmula SUM da FIFA. Cada fase multiplica a anterior.</p>

      <div class="control-grid">
        <div class="control-item">
          <label>16 avos — Grupo F</label>
          <select id="m-16" onchange="renderMata()">
            <option value="1660,Japão,🇯🇵">🇯🇵 Japão (1660)</option>
            <option value="1550,Tunísia,🇹🇳">🇹🇳 Tunísia (1550)</option>
            <option value="1757,Holanda,🇳🇱">🇳🇱 Holanda (1757)</option>
          </select>
        </div>
        <div class="control-item">
          <label>Oitavas — Grupo A</label>
          <select id="m-8" onchange="renderMata()">
            <option value="1681,México,🇲🇽">🇲🇽 México (1681)</option>
            <option value="1588,Coreia do Sul,🇰🇷">🇰🇷 Coreia do Sul (1588)</option>
          </select>
        </div>
        <div class="control-item">
          <label>Quartas — Grupo L</label>
          <select id="m-4" onchange="renderMata()">
            <option value="1825,Inglaterra,🏴󠁧󠁢󠁥󠁮󠁧󠁿">🏴󠁧󠁢󠁥󠁮󠁧󠁿 Inglaterra (1825)</option>
            <option value="1717,Croácia,🇭🇷">🇭🇷 Croácia (1717)</option>
          </select>
        </div>
        <div class="control-item">
          <label>Semifinal — Grupo J</label>
          <select id="m-2" onchange="renderMata()">
            <option value="1874,Argentina,🇦🇷">🇦🇷 Argentina (1874)</option>
            <option value="1593,Áustria,🇦🇹">🇦🇹 Áustria (1593)</option>
          </select>
        </div>
        <div class="control-item">
          <label>Final — Grupos H/I</label>
          <select id="m-1" onchange="renderMata()">
            <option value="1877,França,🇫🇷">🇫🇷 França (1877)</option>
            <option value="1876,Espanha,🇪🇸">🇪🇸 Espanha (1876)</option>
            <option value="1688,Senegal,🇸🇳">🇸🇳 Senegal (1688)</option>
            <option value="1673,Uruguai,🇺🇾">🇺🇾 Uruguai (1673)</option>
          </select>
        </div>
        <div class="control-item">
          <label>Forma do Brasil</label>
          <div class="slider-row">
            <input type="range" min="-80" max="80" step="1" value="0" id="m-forma" oninput="renderMata()">
            <span class="slider-val" id="m-forma-out">0</span>
          </div>
        </div>
      </div>

      <div class="metrics-grid" id="mata-metrics"></div>
      <div id="mata-matches"></div>
    </div>
  </div>
</section>

<!-- SEÇÃO FINAL: CONCLUSÃO -->
<section>
  <div class="container">
    <div class="section-eyebrow">Conclusão</div>
    <h2>A matemática tem seus limites. A torcida, não.</h2>

    <p>
      Fizemos as contas. Usamos o ranking FIFA, a fórmula SUM, probabilidades acumuladas e tudo mais. O resultado honesto é que o Brasil não é o maior favorito desta Copa — França, Espanha e Argentina, tecnicamente, saem na frente.
    </p>

    <p>
      Mas aqui está o detalhe que nenhum modelo captura: <strong>a seleção que entra em campo não é feita só de pontos no ranking.</strong> É feita de história, de raça, de uma torcida que acredita mesmo quando não deveria. São 215 milhões de pessoas parando tudo às 12h, às 15h ou às 18h para torcer juntas.
    </p>

    <p>
      Os dados nos deram o diagnóstico. Agora é com o coração. E o coração verde-amarelo? Esse nunca duvidou.
    </p>

    <div class="fe-box" style="text-align:center; padding: 36px;">
      <p style="font-size: 22px; font-family: 'Bebas Neue', sans-serif; letter-spacing: 0.05em;">
        🇧🇷 Hexa em 2026. A fé não tem ranking. 🇧🇷
      </p>
    </div>
  </div>
</section>

<footer>
  <p>Feito com dados reais do <strong>Ranking FIFA (abril 2026)</strong> e muito amor pela seleção 💚💛</p>
  <p style="margin-top:8px;">Fórmula SUM da FIFA · Dados: FIFA.com · Grupos sorteados em dezembro de 2025</p>
</footer>

<script>
const BRASIL_BASE = 1761;

function We(a, b) {
  return 1 / (Math.pow(10, -(a - b) / 400) + 1);
}

function matchProb(ptsBrasil, ptsAdv) {
  const we = We(ptsBrasil, ptsAdv);
  const adj = 0.18;
  const total = we + (1 - we) + adj;
  const pV = we / total;
  const pD = (1 - we) / total;
  const pE = 1 - pV - pD;
  return {
    v: Math.max(0.03, Math.min(0.93, pV)),
    e: Math.max(0.03, pE),
    d: Math.max(0.03, Math.min(0.93, pD))
  };
}

function ptoColor(pct) {
  if (pct >= 65) return { bg: '#eafaf1', txt: '#1a7a45', bar: '#009c3b' };
  if (pct >= 48) return { bg: '#fffbea', txt: '#8a6400', bar: '#ffdf00' };
  return { bg: '#fef0f0', txt: '#992222', bar: '#cc3333' };
}

const gruposAdv = [
  { nome: 'Marrocos', flag: '🇲🇦', pts: 1755, data: '13 jun', local: 'Nova Jersey', rank: '8º', dif: 'alta' },
  { nome: 'Haiti',    flag: '🇭🇹', pts: 1350, data: '19 jun', local: 'Filadélfia',  rank: '84º', dif: 'baixa' },
  { nome: 'Escócia',  flag: '🏴󠁧󠁢󠁳󠁣󠁴󠁿', pts: 1520, data: '24 jun', local: 'Miami',       rank: '36º', dif: 'media' },
];
const difLabel  = { alta: 'Difícil', media: 'Moderado', baixa: 'Fácil' };
const difStyle  = {
  alta:  'background:#fef0f0; color:#992222;',
  media: 'background:#fffbea; color:#8a6400;',
  baixa: 'background:#eafaf1; color:#1a7a45;'
};

function renderGrupos() {
  const forma = parseInt(document.getElementById('g-forma').value);
  document.getElementById('g-forma-out').textContent = (forma >= 0 ? '+' : '') + forma + ' pts';
  const ptsBrasil = BRASIL_BASE + forma;
  const container = document.getElementById('grupos-matches');
  container.innerHTML = '';

  gruposAdv.forEach(adv => {
    const p = matchProb(ptsBrasil, adv.pts);
    const pct = Math.round(p.v * 100);
    const pctAdv = Math.round(p.d * 100);
    const pctEmp = Math.round(p.e * 100);
    const c = ptoColor(pct);
    const div = document.createElement('div');
    div.className = 'match-card';
    div.innerHTML = `
      <div class="match-header">
        <span class="match-date">📅 ${adv.data} · ${adv.local}</span>
        <span class="match-badge" style="${difStyle[adv.dif]}">${difLabel[adv.dif]}</span>
      </div>
      <div class="teams-row">
        <div class="team-block">
          <span class="team-flag-big">🇧🇷</span>
          <div class="team-name">Brasil</div>
          <div class="team-pts">${ptsBrasil} pts FIFA</div>
        </div>
        <div class="vs-block">×</div>
        <div class="team-block">
          <span class="team-flag-big">${adv.flag}</span>
          <div class="team-name">${adv.nome}</div>
          <div class="team-pts">${adv.pts} pts · ${adv.rank} mundo</div>
        </div>
      </div>
      <div class="prob-row">
        <span class="prob-label">Brasil vence</span>
        <div class="prob-bar-outer"><div class="prob-bar-inner" style="width:${pct}%; background:#002776;"></div></div>
        <span class="prob-val" style="color:#002776;">${pct}%</span>
      </div>
      <div class="prob-row">
        <span class="prob-label">Empate</span>
        <div class="prob-bar-outer"><div class="prob-bar-inner" style="width:${pctEmp}%; background:#888;"></div></div>
        <span class="prob-val" style="color:#888;">${pctEmp}%</span>
      </div>
      <div class="prob-row">
        <span class="prob-label">${adv.nome} vence</span>
        <div class="prob-bar-outer"><div class="prob-bar-inner" style="width:${pctAdv}%; background:#cc3333;"></div></div>
        <span class="prob-val" style="color:#cc3333;">${pctAdv}%</span>
      </div>
      <div style="margin-top:10px; padding-top:8px; border-top:1px solid var(--cinza-medio); font-size:11px; color:var(--texto-sec);">
        Resultado esperado pela FIFA (We): ${(p.v * 100).toFixed(1)}% · Diferença: ${ptsBrasil - adv.pts > 0 ? '+' : ''}${ptsBrasil - adv.pts} pts
      </div>
    `;
    container.appendChild(div);
  });
}

function parseAdv(id) {
  const v = document.getElementById(id).value.split(',');
  return { pts: parseInt(v[0]), nome: v[1], flag: v[2] };
}

function renderMata() {
  const forma = parseInt(document.getElementById('m-forma').value);
  document.getElementById('m-forma-out').textContent = (forma >= 0 ? '+' : '') + forma + ' pts';
  const ptsBrasil = BRASIL_BASE + forma;

  const fases = [
    { label: '16 avos', data: '29 jun', adv: parseAdv('m-16') },
    { label: 'Oitavas', data: '5 jul',  adv: parseAdv('m-8') },
    { label: 'Quartas', data: '11 jul', adv: parseAdv('m-4') },
    { label: 'Semifinal', data: '15 jul', adv: parseAdv('m-2') },
    { label: 'Final 🏆', data: '19 jul', adv: parseAdv('m-1') },
  ];

  const probs = fases.map(f => matchProb(ptsBrasil, f.adv.pts));
  const cumul = [];
  let acc = 1;
  probs.forEach(p => { acc *= p.v; cumul.push(acc); });

  const pCamp = (cumul[4] * 100).toFixed(1);
  const pFinal = (cumul[3] * 100).toFixed(1);
  const pSemi  = (cumul[2] * 100).toFixed(1);
  const m = document.getElementById('mata-metrics');
  m.innerHTML = `
    <div class="metric-card"><div class="metric-lbl">Brasil pts FIFA</div><div class="metric-val">${ptsBrasil}</div></div>
    <div class="metric-card"><div class="metric-lbl">P(chegar à semi)</div><div class="metric-val">${pSemi}%</div></div>
    <div class="metric-card"><div class="metric-lbl">P(chegar à final)</div><div class="metric-val">${pFinal}%</div></div>
    <div class="metric-card destaque"><div class="metric-lbl">P(ser campeão) 🏆</div><div class="metric-val">${pCamp}%</div></div>
  `;

  const container = document.getElementById('mata-matches');
  container.innerHTML = '';

  fases.forEach((f, i) => {
    const p = probs[i];
    const pct = Math.round(p.v * 100);
    const pctAdv = Math.round(p.d * 100);
    const pctEmp = Math.round(p.e * 100);
    const cumulPct = (cumul[i] * 100).toFixed(1);
    const chegouPct = i === 0 ? '~95' : (cumul[i-1] * 100).toFixed(1);
    const isFinal = i === fases.length - 1;
    const c = ptoColor(pct);

    const div = document.createElement('div');
    div.className = 'mata-card' + (isFinal ? ' final' : ' destaque');
    div.innerHTML = `
      <div class="mata-header">
        <span class="mata-phase">${f.label} · ${f.data}</span>
        <span class="mata-badge" style="background:${c.bg}; color:${c.txt};">Brasil vence: ${pct}%</span>
      </div>
      <div class="mteam">
        <span class="mteam-flag">🇧🇷</span>
        <span class="mteam-name">Brasil</span>
        <div class="mteam-bar-outer"><div class="mteam-bar-inner" style="width:${pct}%; background:#002776;"></div></div>
        <span class="mteam-prob" style="color:#002776;">${pct}%</span>
      </div>
      <div style="height:1px; background:var(--cinza-medio); margin:4px 0;"></div>
      <div class="mteam">
        <span class="mteam-flag">${f.adv.flag}</span>
        <span class="mteam-name" style="color:var(--texto-sec);">${f.adv.nome} · ${f.adv.pts} pts</span>
        <div class="mteam-bar-outer"><div class="mteam-bar-inner" style="width:${pctAdv}%; background:#cc3333;"></div></div>
        <span class="mteam-prob" style="color:#cc3333;">${pctAdv}%</span>
      </div>
      <div class="mata-footer">
        <span>Empate/prorrogação: ${pctEmp}%</span>
        <span>P(chegar aqui): <strong>${chegouPct}%</strong> · P(passar): <strong style="color:${isFinal?'#8a6400':'#009c3b'}">${cumulPct}%</strong></span>
      </div>
    `;
    container.appendChild(div);
  });
}

renderGrupos();
renderMata();
</script>
</body>
</html>
