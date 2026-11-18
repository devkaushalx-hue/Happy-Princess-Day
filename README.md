
<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8"><meta name="viewport" content="width=device-width,initial-scale=1">
<meta name="theme-color" content="#f7dce5">
<title>Happy Princess Day! 💖</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=DM+Sans:wght@400;500;600;700&family=Parisienne&family=Playfair+Display:wght@500;600;700&display=swap" rel="stylesheet">
<style>
:root{--pink:#f5cbd8;--rose:#c86b86;--deep:#7c344e;--cream:#fff8f1;--gold:#c9a45d;--ink:#573747;--sage:#a9b99e;--shadow:0 18px 55px #713b5120}
*{box-sizing:border-box}html{scroll-behavior:smooth}body{margin:0;background:radial-gradient(circle at 12% 8%,#fff 0 2px,transparent 3px),linear-gradient(135deg,#fff8f2,#f9e2e9 55%,#f5d5df);color:var(--ink);font-family:"DM Sans",sans-serif;min-height:100vh;overflow-x:hidden}
button,input,textarea{font:inherit}button{cursor:pointer}.app{max-width:1120px;margin:auto;padding:22px 18px 90px;position:relative}.topbar{display:flex;justify-content:space-between;align-items:center;gap:12px;margin-bottom:18px;flex-wrap:wrap}.brand{font-family:Parisienne,cursive;font-size:30px;color:var(--deep)}.top-controls{display:flex;gap:8px;align-items:center;flex-wrap:wrap}.pill{border:1px solid #d9a6b6;background:#fff9f6b8;color:var(--deep);border-radius:999px;padding:9px 14px;font-size:12px;transition:.2s}.pill:hover{background:#fff;transform:translateY(-1px)}
.scene{display:none;animation:sceneIn .75s cubic-bezier(.2,.8,.2,1) both}.scene.active{display:block}@keyframes sceneIn{from{opacity:0;transform:translateY(22px) scale(.985)}to{opacity:1;transform:none}}
.panel{background:#fffaf6d9;border:1px solid #fff;box-shadow:var(--shadow);border-radius:28px;padding:clamp(22px,4vw,42px);position:relative;overflow:hidden}.panel:before{content:"";position:absolute;inset:10px;border:1px dashed #d8a7b6;border-radius:21px;pointer-events:none;opacity:.7}
.eyebrow{text-transform:uppercase;letter-spacing:.22em;color:var(--rose);font-size:10px;font-weight:700}.hero{text-align:center;min-height:580px;display:grid;place-items:center}.hero-inner{position:relative;z-index:1;max-width:740px}.hero h1{font:clamp(44px,8.5vw,86px)/1.02 "Playfair Display",serif;color:var(--deep);margin:14px 0}.script{font:clamp(28px,4.5vw,44px) Parisienne,cursive;color:var(--rose)}.hero p{max-width:580px;line-height:1.85;margin:18px auto 26px;font-size:15.5px}.floral{font-size:38px;letter-spacing:8px;animation:float 4s ease-in-out infinite}.btn{border:0;border-radius:999px;padding:13px 24px;background:linear-gradient(135deg,#b95777,#873d59);color:white;box-shadow:0 9px 22px #8d405a35;font-weight:700;transition:.25s}.btn:hover{transform:translateY(-3px);box-shadow:0 14px 28px #8d405a45}.btn.secondary{background:#fff;color:var(--deep);border:1px solid #d9a6b6;box-shadow:none}.btn.secondary:hover{background:#fff5f8}.btn.small{padding:9px 15px;font-size:12px}.actions{display:flex;gap:10px;justify-content:center;flex-wrap:wrap;margin-top:20px}
h2{font:clamp(32px,5vw,48px) "Playfair Display",serif;color:var(--deep);margin:8px 0 12px}h3{font:22px "Playfair Display",serif;color:var(--deep);margin:0 0 10px}.intro{line-height:1.7;max-width:680px}.center{text-align:center}.grid{display:grid;grid-template-columns:1fr 1fr;gap:20px;align-items:center}.studio-grid{display:grid;grid-template-columns: minmax(240px,.9fr) minmax(280px,1.1fr);gap:22px;margin-top:20px}

/* Penguin Preview & Fixed Accessories */
.preview{min-height:360px;border-radius:24px;background:radial-gradient(circle,#fff 0 18%,#f9e1e9 19% 60%,#f4cbd8 61%);display:grid;place-items:center;position:relative;overflow:hidden;border:1px solid #f1d1da}.preview:after{content:"✦  ✧  ✦";position:absolute;top:18px;right:20px;color:#c79a50;letter-spacing:12px;animation:twinkle 2s infinite alternate}
.penguin{width:190px;height:255px;position:relative;filter:drop-shadow(0 14px 12px #66344725);transform-origin:50% 90%;transition:transform .4s;cursor:pointer}
.penguin svg{width:100%;height:100%;overflow:visible}
.p-accessory{position:absolute;top:8px;left:50%;transform:translateX(-50%);font-size:38px;line-height:1;filter:drop-shadow(0 4px 4px #5a263333);z-index:3;pointer-events:none;transition:transform .3s}
.p-extra{position:absolute;top:52px;right:6px;font-size:30px;line-height:1;filter:drop-shadow(0 4px 6px #8d405a35);z-index:4;pointer-events:none;animation:floatExtra 2.6s ease-in-out infinite}
@keyframes floatExtra{0%,100%{transform:translateY(0) rotate(-6deg) scale(1)}50%{transform:translateY(-8px) rotate(8deg) scale(1.12)}}
.p-name{position:absolute;bottom:15px;left:50%;transform:translateX(-50%);background:#fffc;border:1px solid #fff;padding:5px 15px;border-radius:20px;font-size:12px;font-weight:700;color:var(--deep);white-space:nowrap;box-shadow:0 4px 12px #7c344e15}

.controls{background:#fffdfb;border:1px solid #f1d9df;border-radius:22px;padding:20px}.field{margin:13px 0}.field label{display:block;font-size:12px;font-weight:700;color:#865064;margin-bottom:7px}.field input,.field textarea{width:100%;border:1px solid #e7c5cf;border-radius:12px;padding:11px;background:#fff9f8;color:var(--ink)}.choices{display:flex;gap:8px;flex-wrap:wrap}.choice{border:1px solid #e7c5cf;background:#fff;border-radius:12px;padding:9px 11px;color:var(--ink);font-size:12px;transition:.2s}.choice:hover{border-color:#c86b86}.choice.selected{border-color:#a64e6b;background:#fbe7ed;box-shadow:inset 0 0 0 1px #a64e6b;font-weight:600}.swatch{width:30px;height:30px;border-radius:50%;border:2px solid white;box-shadow:0 0 0 1px #d8bdc5;transition:.2s}.swatch:hover{transform:scale(1.1)}.swatch.selected{box-shadow:0 0 0 3px #9b4b67;transform:scale(1.1)}
.scene-nav{display:flex;justify-content:space-between;align-items:center;margin:18px 3px}.dots{display:flex;gap:6px}.dot{width:8px;height:8px;border-radius:50%;background:#d8a8b7;cursor:pointer;transition:.3s}.dot.on{width:24px;border-radius:8px;background:#9e4d69}

/* Interactive Floating Companion */
.companion{position:fixed;right:18px;bottom:15px;z-index:30;width:96px;height:128px;pointer-events:auto;cursor:pointer;transition:all .5s}
.companion .penguin{width:92px;height:122px}
.companion .p-accessory{font-size:20px;top:3px}
.companion .p-extra{font-size:16px;top:24px;right:2px}
.companion .p-name{font-size:8px;bottom:0;padding:3px 8px}
.companion .penguin svg{width:100%;height:100%}
.speech-bubble{position:absolute;bottom:125px;right:4px;background:#fff;border:1px solid #e7c5cf;color:var(--deep);padding:8px 13px;border-radius:16px 16px 4px 16px;font-size:12px;font-weight:600;white-space:nowrap;box-shadow:0 8px 20px #7c344e20;opacity:0;transform:translateY(8px) scale(.9);transition:.3s;pointer-events:none}
.speech-bubble.show{opacity:1;transform:translateY(0) scale(1)}

/* Interactive Garden */
.garden-stage{display:flex;justify-content:center;gap:clamp(14px,3vw,28px);flex-wrap:wrap;padding:28px 10px}
.garden-item{font-size:clamp(54px,11vw,88px);background:#fff;border:1px solid #f2d5de;border-radius:24px;padding:16px 20px;cursor:pointer;transition:.3s;box-shadow:0 10px 24px #8d405a12;user-select:none;animation:float 4s ease-in-out infinite;position:relative}
.garden-item:nth-child(even){animation-delay:.7s}
.garden-item:hover{transform:translateY(-8px) scale(1.08);border-color:#c86b86;box-shadow:0 15px 30px #8d405a25}
.garden-item.collected{background:#fff3f7;border-color:#c86b86}
.wish-box{min-height:62px;background:#fff;border:1px dashed #d8a7b6;border-radius:18px;padding:14px 22px;max-width:560px;margin:10px auto 0;font-family:"Playfair Display",serif;font-size:17px;line-height:1.5;color:var(--deep);display:grid;place-items:center}

/* Letter & Customizer */
.letter-stage{min-height:430px;display:grid;place-items:center;perspective:1000px}.envelope{width:min(450px,92%);height:275px;position:relative;cursor:pointer;filter:drop-shadow(0 15px 18px #7b405322);margin:45px auto 20px}.env-back{position:absolute;inset:0;background:#d88fa7;border-radius:12px}.env-front{position:absolute;inset:0;background:linear-gradient(145deg,#f3c4d2,#d98da7);clip-path:polygon(0 0,50% 58%,100% 0,100% 100%,0 100%);border-radius:12px;z-index:3}.env-flap{position:absolute;inset:0;background:#e9aec0;clip-path:polygon(0 0,100% 0,50% 62%);transform-origin:top;transition:transform .8s ease;z-index:4;filter:drop-shadow(0 4px 3px #8a4560)}.seal{position:absolute;z-index:5;left:50%;top:54%;transform:translate(-50%,-50%);width:46px;height:46px;border-radius:50%;background:#fff0e8;border:2px solid #c58c4d;color:#a74c69;display:grid;place-items:center;font-size:20px;transition:.3s;box-shadow:0 4px 10px #7c344e25}.letter{position:absolute;z-index:2;left:5%;width:90%;height:118%;bottom:4%;background:#fffdf8;border:1px solid #e9d7bd;padding:24px 22px;text-align:center;transition:transform 1s cubic-bezier(.2,.8,.2,1),opacity .5s;opacity:.08;transform:translateY(65px);overflow:auto;border-radius:12px}.letter.open{opacity:1;transform:translateY(-150px);z-index:6;box-shadow:0 16px 38px #57374728}.envelope.open .env-flap{transform:rotateX(180deg);z-index:1}.envelope.open .seal{opacity:0}.letter p{line-height:1.72;font:15px/1.75 "Playfair Display",serif;margin:10px 0}.hint{font-size:12px;color:#9a6275;text-align:center}
.note-editor{max-width:460px;margin:16px auto 0;background:#fff;border:1px solid #efd6de;border-radius:18px;padding:16px;text-align:left;display:none}.note-editor.show{display:block;animation:sceneIn .4s both}

/* Flower Boutique */
.shop-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:14px;margin:22px 0}.flower-card{background:#fff;border:1px solid #f0d5dd;border-radius:18px;padding:15px;text-align:center;box-shadow:0 8px 22px #8d405a0c;transition:.2s}.flower-card:hover{transform:translateY(-4px);border-color:#d9a6b6}.flower-art{font-size:44px;display:block;animation:bob 3s infinite ease-in-out}.flower-card p{font-size:12px;margin:4px 0 10px}.bouquet-wrap{background:#fbeaf0;border-radius:20px;padding:18px;text-align:center}.bouquet{min-height:120px;display:flex;align-items:end;justify-content:center;gap:4px;flex-wrap:wrap;padding:12px}.bouquet-flower{font-size:38px;display:inline-block;animation:popFlower .5s cubic-bezier(.2,1.5,.4,1) both;transform-origin:bottom;cursor:pointer}.bouquet-flower:hover{transform:scale(1.2) rotate(8deg)}.bouquet-flower:nth-child(even){animation-delay:.08s}.vase{width:126px;height:58px;margin:-2px auto 0;background:linear-gradient(90deg,#f1c7d2,#fff1f3,#e8aebe);clip-path:polygon(12% 0,88% 0,75% 100%,25% 100%);border-bottom:3px solid #c98da1;position:relative;display:grid;place-items:center;font-size:18px}

/* Kitchen */
.kitchen{display:grid;grid-template-columns:1fr 1fr;gap:18px;margin:22px 0}.appliance{border-radius:22px;padding:20px;background:#fff;border:1px solid #efd6de;text-align:center;min-height:270px;position:relative;overflow:hidden}.oven,.fridge{font-size:70px;display:block;filter:drop-shadow(0 7px 5px #693c4b20)}.door{position:absolute;inset:0;background:#f9e8edee;backdrop-filter:blur(4px);display:grid;place-items:center;transition:transform .8s;transform:translateY(0);z-index:2}.door.open{transform:translateY(-110%)}.treat{font-size:36px;display:inline-block;animation:treatOut .9s cubic-bezier(.2,1.4,.4,1) both}.treats{display:flex;justify-content:center;gap:12px;flex-wrap:wrap;margin-top:14px}.treat-card{background:#fff7f1;border-radius:16px;padding:12px 16px;border:1px solid #eed8c4;min-width:105px;cursor:pointer;transition:.2s}.treat-card:hover{transform:scale(1.06);border-color:#c86b86;background:#fff0e6}

/* Gift & Finale */
.gift-scene{min-height:390px;display:grid;place-items:center}.gift{font-size:130px;cursor:pointer;filter:drop-shadow(0 15px 15px #713b5128);animation:giftPulse 2s infinite;user-select:none}.gift.open{animation:giftOpen .8s forwards}.reveal{max-height:0;opacity:0;overflow:hidden;transition:all .8s}.reveal.show{max-height:360px;opacity:1;margin-top:10px}
.final-penguin{width:190px;margin:10px auto;animation:dance 1s ease-in-out infinite}.confetti{position:fixed;inset:0;pointer-events:none;z-index:40;overflow:hidden}.petal{position:fixed;top:-30px;z-index:1;pointer-events:none;animation:fall linear forwards;opacity:.75}.spark{position:fixed;pointer-events:none;color:#c49a53;animation:sparkle 1.3s ease-out forwards;z-index:50;font-weight:700}

@keyframes float{50%{transform:translateY(-10px) rotate(2deg)}}@keyframes bob{50%{transform:translateY(-7px) rotate(3deg)}}@keyframes twinkle{to{opacity:.35;transform:scale(1.15)}}@keyframes popFlower{from{opacity:0;transform:scale(.1) translateY(25px)}to{opacity:1;transform:scale(1) translateY(0)}}@keyframes treatOut{from{opacity:0;transform:translateY(80px) scale(.5)}to{opacity:1;transform:none}}@keyframes giftPulse{50%{transform:scale(1.07) rotate(3deg)}}@keyframes giftOpen{to{transform:rotate(-15deg) scale(1.25);filter:drop-shadow(0 0 25px #e6ad4e)}}@keyframes fall{to{transform:translateY(110vh) rotate(560deg);opacity:0}}@keyframes sparkle{0%{transform:scale(0);opacity:0}40%{opacity:1}100%{transform:scale(1.7) translateY(-35px);opacity:0}}
@keyframes penguinWaddle{0%,100%{transform:rotate(0) translateY(0)}25%{transform:rotate(-8deg) translateY(-5px)}75%{transform:rotate(8deg) translateY(-5px)}}@keyframes penguinPeek{0%,100%{transform:translateX(0)}50%{transform:translateX(10px) rotate(4deg)}}@keyframes penguinHop{0%,100%{transform:translateY(0)}50%{transform:translateY(-18px)}}@keyframes dance{0%,100%{transform:rotate(-9deg) translateY(0)}25%{transform:rotate(10deg) translateY(-12px)}50%{transform:rotate(-10deg) translateY(-3px)}75%{transform:rotate(9deg) translateY(-14px)}}
.companion.waddle .penguin{animation:penguinWaddle 1.2s infinite}.companion.peek .penguin{animation:penguinPeek 2.3s infinite}.companion.hop .penguin{animation:penguinHop 1s infinite}
@media(max-width:760px){.grid,.studio-grid,.kitchen{grid-template-columns:1fr}.hero{min-height:540px}.shop-grid{grid-template-columns:1fr 1fr}.companion{right:8px;bottom:8px;transform:scale(.82);transform-origin:bottom right}.panel{padding:22px 18px}.preview{min-height:300px}.letter.open{transform:translateY(-135px)}}
@media(prefers-reduced-motion:reduce){*,*:before,*:after{animation-duration:.01ms!important;animation-iteration-count:1!important;scroll-behavior:auto!important;transition-duration:.01ms!important}}

/* Additive Polish: Click Sparkles & Smooth Focus */
.click-heart{position:fixed;pointer-events:none;z-index:60;font-size:16px;animation:clickFloat .9s ease-out forwards}
@keyframes clickFloat{0%{opacity:1;transform:translate(-50%,-50%) scale(.5)}100%{opacity:0;transform:translate(-50%,-95px) scale(1.35)}}

/* Cute Additive Features: Royal Affirmation Toast, Penguin Blink/Wiggle & Heart Fireworks */
.royal-toast{position:fixed;top:74px;left:50%;transform:translateX(-50%) translateY(-16px) scale(.95);background:#fffdf9ee;backdrop-filter:blur(6px);border:1.5px solid #e6b3c3;color:var(--deep);padding:11px 20px;border-radius:999px;font-size:13px;font-weight:600;box-shadow:0 12px 30px #7c344e25;z-index:70;opacity:0;pointer-events:none;transition:all .35s cubic-bezier(.2,.9,.3,1);max-width:90vw;text-align:center}
.royal-toast.show{opacity:1;transform:translateX(-50%) translateY(0) scale(1)}
.penguin:hover{transform:scale(1.04) rotate(-2deg)}
.penguin.love-pop{animation:lovePop .6s cubic-bezier(.2,1.5,.4,1)}
@keyframes lovePop{0%{transform:scale(1)}40%{transform:scale(1.13) rotate(4deg)}70%{transform:scale(.97) rotate(-3deg)}100%{transform:scale(1)}}
.firework-heart{position:fixed;pointer-events:none;z-index:65;font-size:20px;animation:fwBurst 1.1s cubic-bezier(.15,.85,.3,1) forwards}
@keyframes fwBurst{0%{opacity:1;transform:translate(-50%,-50%) scale(.4)}100%{opacity:0;transform:translate(calc(-50% + var(--dx)),calc(-50% + var(--dy))) scale(1.25) rotate(25deg)}}
</style></head>
<body>
<div class="app">
<header class="topbar">
  <div class="brand">A little royal surprise ✧ 💖</div>
  <div class="top-controls">
    <button class="pill" id="complimentBtn">✨ Sweet Reminder</button>
    <button class="pill" id="heartBurstBtn">💗 Send Hearts</button>
    <button class="pill" id="petalToggle">🌸 Petals: On</button>
    <button class="pill" id="musicBtn">♫ Play gentle music</button>
  </div>
</header>

<main>
<!-- SCENE 0: HERO -->
<section class="scene active" data-scene="0"><div class="panel hero"><div class="hero-inner">
  <div class="floral">💖 🌷 👑 🌸 💗</div>
  <div class="eyebrow">A heartfelt celebration just for you 💕</div>
  <h1>Happy<br>Princess Day! 💖</h1>
  <div class="script">To someone whose heart makes every day softer & brighter ❤️</div>
  <p>You carry so much warmth, quiet strength, and genuine kindness wherever you go—even on the days when you feel tired or unseen. Today is a gentle reminder to pause, breathe, feel deeply appreciated, and let yourself be celebrated just as you are. You deserve every bit of love, peace, and magic in this world. 💗✨</p>
  <button class="btn" onclick="startJourney()">Step into your fairytale 💖</button>
  <p class="hint">Made with warmth, care, a tiny penguin, and lots of heart 💕</p>
</div></div></section>

<!-- SCENE 1: PENGUIN STUDIO -->
<section class="scene" data-scene="1"><div class="panel"><div class="eyebrow">Chapter 01 · Your royal sidekick 💕</div><h2>Meet your penguin pal</h2><p class="intro">Create a tiny royal companion to keep you company. Pick a look, give them a name, and tap them anytime in the corner for a little encouragement! 💖</p><div class="studio-grid"><div class="preview"><div class="penguin" id="studioPenguin" onclick="sparkBurst(this)"></div><div class="p-name" id="studioName">Pip</div></div><div class="controls">
<div class="field"><label>Give your penguin a name</label><input id="penguinName" maxlength="16" value="Pip" placeholder="e.g. Pip"></div>
<div class="field"><label>Choose an outfit</label><div class="choices" id="outfits"><button class="choice selected" data-v="gown">Princess gown</button><button class="choice" data-v="dress">Party dress</button><button class="choice" data-v="cape">Royal cape</button><button class="choice" data-v="suit">Dapper suit</button></div></div>
<div class="field"><label>Outfit colour</label><div class="choices" id="colours"><button class="swatch selected" data-v="#d8759a" style="background:#d8759a" aria-label="Rose pink"></button><button class="swatch" data-v="#9a83c7" style="background:#9a83c7" aria-label="Lilac"></button><button class="swatch" data-v="#75a9a0" style="background:#75a9a0" aria-label="Sage"></button><button class="swatch" data-v="#e6b65e" style="background:#e6b65e" aria-label="Gold"></button><button class="swatch" data-v="#6c8fb8" style="background:#6c8fb8" aria-label="Blue"></button><button class="swatch" data-v="#bd5966" style="background:#bd5966" aria-label="Berry"></button></div></div>
<div class="field"><label>Headpiece</label><div class="choices" id="crowns"><button class="choice selected" data-v="👑">Crown 👑</button><button class="choice" data-v="🎀">Bow 🎀</button><button class="choice" data-v="🌸">Flower 🌸</button><button class="choice" data-v="✨">Tiara ✨</button><button class="choice" data-v="">No headpiece</button></div></div>
<div class="field"><label>Extra floating companion</label><div class="choices" id="accessories"><button class="choice selected" data-v="💖">Heart 💖</button><button class="choice" data-v="✨">Sparkles ✨</button><button class="choice" data-v="🦋">Butterfly 🦋</button><button class="choice" data-v="🪄">Wand 🪄</button><button class="choice" data-v="⭐">Star ⭐</button><button class="choice" data-v="">None</button></div></div>
<div class="actions"><button class="btn" onclick="savePenguin()">Save my penguin 💖</button><button class="btn secondary" onclick="randomLook()">Surprise me 🎲</button></div><p class="hint">Saved right in your browser so your pal stays dressed up.</p>
</div></div></div></section>

<!-- SCENE 2: INTERACTIVE GARDEN -->
<section class="scene" data-scene="2"><div class="panel center"><div class="eyebrow">Ch
