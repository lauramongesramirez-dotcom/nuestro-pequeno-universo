<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>LA CASA DE LAS PIEDRAS - SERIE COMPLETA 16 CAPS</title>
<style>
  @import url('https://fonts.googleapis.com/css2?family=Cinzel:wght@700&family=Inter:wght@400;700&display=swap');
  body{margin:0;background:#050508;color:white;font-family:'Inter',sans-serif}
 .chapter{min-height:100vh;display:flex;flex-direction:column;justify-content:center;align-items:center;padding:30px 20px;text-align:center;border-bottom:1px solid #222;position:relative}
 .char-img{width:300px;height:300px;border-radius:50%;object-fit:cover;border:4px solid;box-shadow:0 0 50px currentColor;animation:float 3s ease-in-out infinite}
  @keyframes float{0%,100%{transform:translateY(0)}50%{transform:translateY(-12px)}}
  h1{font-family:'Cinzel',serif;font-size:2.5em;margin:15px 0 0 0;letter-spacing:3px}
 .subtitle{color:#a0a0ff;letter-spacing:4px;font-size:0.85em;margin-top:5px}
 .dialogue-box{background:rgba(255,255,255,0.08);backdrop-filter:blur(12px);border:1px solid rgba(255,255,255,0.15);border-radius:22px;padding:28px;max-width:540px;margin-top:22px;line-height:1.7;font-size:1.1em}
 .char-name{font-weight:800;letter-spacing:2px;font-size:0.8em;margin-bottom:8px;display:block}
 .cap-label{position:absolute;top:20px;left:20px;background:white;color:black;padding:6px 14px;border-radius:20px;font-size:0.7em;font-weight:800}
 .controls{position:fixed;bottom:15px;right:15px;z-index:999;display:flex;gap:8px}
  button{background:white;color:black;border:none;padding:12px 18px;border-radius:50px;font-weight:800;cursor:pointer;font-size:0.85em}
 .progress{position:fixed;top:0;left:0;height:5px;background:linear-gradient(90deg,#a0a0ff,#ff6b9d);width:0%;z-index:1000;transition:width 0.4s}
 .zafiro{object-position:15% center; border-color:#6bb5ff; color:#6bb5ff}
 .rubi{object-position:33% center; border-color:#ff2a5a; color:#ff2a5a}
 .diamante{object-position:50% center; border-color:#d0f0ff; color:#d0f0ff}
 .onix{object-position:68% center; border-color:#a0a0ff; color:#a0a0ff}
 .cuarzo{object-position:85% center; border-color:#ffb6d9; color:#ffb6d9}
 .season{background:#ff6b9d;color:white;padding:40px 20px;text-align:center;font-family:'Cinzel',serif;letter-spacing:5px;font-size:1.2em}
</style>
</head>
<body>
<div class="progress" id="progress"></div>
<div class="controls">
  <button onclick="toggleVoice()" id="voiceBtn">🔊 VOZ ON</button>
  <button onclick="nextChapter()">SIG ➜</button>
</div>

<div class="season">TEMPORADA 1 - LA IMPOSTORA</div>

<div class="chapter" id="cap1" style="background:radial-gradient(circle,#151a2e,#050508)"><span class="cap-label">CAP 1 / 16 - LA FUGA</span><img src="personajes.png" class="char-img zafiro"><h1>LA FUGA</h1><div class="dialogue-box"><span class="char-name" style="color:#6bb5ff">ZAFIRO</span>En mi familia, si no brillas, no vales. Mi hermana Diamante era la que más brillaba, por eso le exigían todo. Anoche dijo "Ya no puedo más". A la mañana su caja estaba vacía. Todos creen que está enferma. Mentira. Ella huyó.</div></div>

<div class="chapter" id="cap2" style="background:radial-gradient(circle,#2e1515,#050508)"><span class="cap-label">CAP 2 / 16 - EL COMPLOT</span><img src="personajes.png" class="char-img rubi"><div class="dialogue-box"><span class="char-name" style="color:#ff2a5a">RUBÍ</span>Si papá se entera que Diamante se fue, perdemos la mina. Solo necesito una semana.<br><br><span class="char-name" style="color:#a0a0ff">ÓNIX</span>Puedo crear otra Diamante. Pero quiero la mitad de la mina cuando esto acabe.</div></div>

<div class="chapter" id="cap3" style="background:radial-gradient(circle,#2e1525,#050508)"><span class="cap-label">CAP 3 / 16 - LA IMPOSTORA</span><img src="personajes.png" class="char-img cuarzo"><div class="dialogue-box"><span class="char-name" style="color:#ffb6d9">CUARZO</span>¿Yo puedo ser Diamante? Siempre fui invisible...<br><br><span class="char-name" style="color:#a0a0ff">ÓNIX</span>Te voy a pulir. Vas a ser perfecta. Solo obedece.</div></div>

<div class="chapter" id="cap4" style="background:radial-gradient(circle,#152e2e,#050508)"><span class="cap-label">CAP 4 / 16 - SOSPECHA</span><img src="personajes.png" class="char-img zafiro"><div class="dialogue-box"><span class="char-name" style="color:#6bb5ff">ZAFIRO</span>Esa no es mi hermana. Volvió, pero no brilla igual. Mi hermana nunca temblaba cuando mentía. Esta tiene miedo.</div></div>

<div class="chapter" id="cap5" style="background:radial-gradient(circle,#1a1a2e,#050508)"><span class="cap-label">CAP 5 / 16 - LA PRUEBA</span><img src="personajes.png" class="char-img onix"><div class="dialogue-box"><span class="char-name" style="color:white">PAPÁ</span>Mañana es la Ceremonia de la Luz. Solo la verdadera Diamante puede encender la mina. Si falla, sabré que nos engañaron.</div></div>

<div class="chapter" id="cap6" style="background:radial-gradient(circle,#2e1a2e,#050508)"><span class="cap-label">CAP 6 / 16 - FINAL T1</span><img src="personajes.png" class="char-img diamante"><h1>¿DÓNDE ESTÁ?</h1><div class="dialogue-box"><span class="char-name" style="color:#d0f0ff">DIAMANTE REAL - LEJOS</span>Me fui para ser libre. Pero escucho que mi familia me necesita. Volveré. Y alguien dejará de brillar para siempre.</div></div>

<div class="season">TEMPORADA 2 - DOS DIAMANTES</div>

<div class="chapter" id="cap7" style="background:radial-gradient(circle,#1a2e2e,#050508)"><span class="cap-label">CAP 7 / 16 - EL REGRESO</span><img src="personajes.png" class="char-img diamante"><div class="dialogue-box"><span class="char-name" style="color:#d0f0ff">DIAMANTE</span>Volví. Estuve escondida en la vieja cantera, aprendiendo a brillar por mí, no por ellos. Pero ahora hay otra con mi cara en mi casa. ¿Quién es?</div></div>

<div class="chapter" id="cap8" style="background:radial-gradient(circle,#2e2e15,#050508)"><span class="cap-label">CAP 8 / 16 - CARA A CARA</span><img src="personajes.png" class="char-img cuarzo"><div class="dialogue-box"><span class="char-name" style="color:#ffb6d9">CUARZO (llorando)</span>¡Tú eres la real! Yo no quería esto, me obligaron. Ónix me dijo que si no lo hacía, me iba a triturar.<br><br><span class="char-name" style="color:#d0f0ff">DIAMANTE</span>Tranquila. No eres mi enemiga. Ellas sí.</div></div>

<div class="chapter" id="cap9" style="background:radial-gradient(circle,#2e1515,#050508)"><span class="cap-label">CAP 9 / 16 - EL PLAN</span><img src="personajes.png" class="char-img rubi"><div class="dialogue-box"><span class="char-name" style="color:#ff2a5a">RUBÍ</span>¡No puede haber dos Diamantes! Papá viene en dos horas.<br><br><span class="char-name" style="color:#a0a0ff">ÓNIX</span>Entonces haremos que una desaparezca. La falsa es desechable.</div></div>

<div class="chapter" id="cap10" style="background:radial-gradient(circle,#152e1a,#050508)"><span class="cap-label">CAP 10 / 16 - ALIANZA</span><img src="personajes.png" class="char-img zafiro"><div class="dialogue-box"><span class="char-name" style="color:#6bb5ff">ZAFIRO</span>¡Hermana! Sabía que volverías. Cuarzo me contó todo. Tenemos un plan: en la ceremonia, haré que las dos entren al mismo tiempo. Que papá vea la verdad.</div></div>

<div class="chapter" id="cap11" style="background:radial-gradient(circle,#1a1a3a,#050508)"><span class="cap-label">CAP 11 / 16 - CEREMONIA</span><img src="personajes.png" class="char-img diamante"><div class="dialogue-box"><span class="char-name" style="color:white">PAPÁ</span>¡Qué significa esto! ¡Dos Diamantes!<br><br><span class="char-name" style="color:#d0f0ff">DIAMANTE REAL</span>Papá, yo soy tu hija. Ella es una víctima de Rubí y Ónix. Pídele que haga la prueba de luz. Solo yo puedo encender la mina.</div></div>

<div class="chapter" id="cap12" style="background:radial-gradient(circle,#000,#050508)"><span class="cap-label">CAP 12 / 16 - LA LUZ</span><img src="personajes.png" class="char-img cuarzo"><div class="dialogue-box"><span class="char-name" style="color:#ffb6d9">CUARZO</span>Yo... yo no puedo. No brillo. ¡Perdón! Ellas me obligaron.<br><br><span class="char-name" style="color:#d0f0ff">DIAMANTE REAL (brillando)</span><b style="font-size:1.4em">*LA MINA SE ENCIENDE ENTERA*</b></div></div>

<div class="season">TEMPORADA 3 - EL FINAL</div>

<div class="chapter" id="cap13" style="background:radial-gradient(circle,#2e1515,#050508)"><span class="cap-label">CAP 13 / 16 - CASTIGO</span><img src="personajes.png" class="char-img rubi"><div class="dialogue-box"><span class="char-name" style="color:#ff2a5a">RUBÍ</span>Papá, yo solo quería proteger la familia...<br><br><span class="char-name" style="color:white">PAPÁ</span>¡Silencio! Por tu envidia casi destruyes nuestro legado. Te quedarás sin nada. Limpiarás la mina por un año.</div></div>

<div class="chapter" id="cap14" style="background:radial-gradient(circle,#1a0a2e,#050508)"><span class="cap-label">CAP 14 / 16 - LA VILLANA CAE</span><img src="personajes.png" class="char-img onix"><div class="dialogue-box"><span class="char-name" style="color:#a0a0ff">ÓNIX</span>¡Ustedes
