# Strawbabble
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <meta name="apple-mobile-web-app-capable" content="yes">
  <meta name="apple-mobile-web-app-status-bar-style" content="default">
  <meta name="format-detection" content="telephone=no">
  <title>Strawbabble – The Pure Garden</title>
  <link href="https://fonts.googleapis.com/css2?family=Fredoka+One&family=Comic+Neue:wght@400;700&family=Reenie+Beanie&display=swap" rel="stylesheet">
  <link rel="apple-touch-icon" href="data:image/svg+xml,<svg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 100 100'><circle cx='50' cy='50' r='45' fill='%23FF4D6D'/><path d='M35 40c0-3 2-5 5-5s5 2 5 5-2 5-5 5-5-2-5-5m20 0c0-3 2-5 5-5s5 2 5 5-2 5-5 5-5-2-5-5' fill='%2390EE90'/><path d='M45 55c0 5 10 10 10 10s10-5 10-10c0-3-5-5-10-5s-10 2-10 5' fill='white'/></svg>">
  <style>
    :root{
      --sky-day:#A0D8F1;--sky-night:#1C3A6B;--grass:#6BBF5A;--flower:#FFB6C1;--strawberry:#FF4D6D;
      --lbp-blue:#6BB9F0;--lbp-pink:#FF69B4;--dora-purple:#9B59B6;--noggin-orange:#FF7F50;
      --crayola-yellow:#FFD700;--alice-teal:#4ECDC4;--disney-cream:#FFF8E7;--text:#22313F;
      --card:rgba(255,255,255,0.96);--shadow:rgba(0,0,0,0.18);--sun:#FFEB3B;--moon:#F4F1C9;
      --cloud:rgba(255,255,255,0.9);--spring:#B5EAD7;--summer:#90EE90;--autumn:#FFB366;
      --winter:#E0F7FA;--gold:#FFD700;
    }
    *{margin:0;padding:0;box-sizing:border-box;}
    
    /* A11y Fix: Visible focus states for keyboard users */
    *:focus-visible {
      outline: 4px dashed var(--dora-purple);
      outline-offset: 2px;
    }

    body{
      background:linear-gradient(to bottom,var(--sky-day) 0%,var(--spring) 40%,var(--grass) 100%);
      font-family:'Comic Neue',cursive;color:var(--text);overflow:hidden;height:100vh;
      perspective:1600px;transition:background 3s ease;position:relative;
      -webkit-font-smoothing:antialiased;-webkit-tap-highlight-color:transparent;
      touch-action:manipulation;
    }
    /* Seasonal and Day/Night Classes */
    body.night{background:linear-gradient(to bottom,var(--sky-night) 0%,#2C3E50 40%,#1e3a2a 100%);}
    body.summer{--grass:var(--summer);}
    body.autumn{--grass:var(--autumn);}
    body.winter{--grass:var(--winter);background:linear-gradient(to bottom,#87CEEB 0%,#E0F7FA 40%,#FFF 100%);}
    body::before{
      content:'';position:absolute;top:0;left:0;right:0;bottom:0;
      background:radial-gradient(circle at 20% 80%,rgba(255,255,255,0) 0%,var(--sky-day) 100%);
      z-index:-1;
      opacity:0.6;
      transition:opacity 3s ease;
    }
    body.night::before{
      background:radial-gradient(circle at 80% 20%,rgba(0,0,0,0) 0%,var(--sky-night) 100%);
      opacity:0.8;
    }

    /* Sun and Moon */
    .sun, .moon{
      position:absolute;
      width:100px;
      height:100px;
      border-radius:50%;
      top:10%;
      right:10%;
      box-shadow:0 0 40px var(--gold);
      transition:transform 3s ease, background 3s ease;
      z-index:5;
    }
    .sun{
      background:var(--sun);
      transform:translateY(0);
      animation:pulse 4s infinite alternate;
    }
    .moon{
      background:var(--moon);
      transform:translateY(500px);
      box-shadow:0 0 30px #B0C4DE;
    }
    body.night .sun{
      transform:translateY(-500px);
    }
    body.night .moon{
      transform:translateY(0);
    }
    @keyframes pulse{
      from{box-shadow:0 0 20px var(--gold), 0 0 50px rgba(255,215,0,0.5);}
      to{box-shadow:0 0 40px var(--gold), 0 0 80px rgba(255,215,0,0.8);}
    }

    /* === 🌳 Structural Layout Styles === */

    header {
      position: relative;
      text-align: center;
      padding: 20px 0 10px;
      z-index: 10;
    }
    header h1 {
      font-family: 'Fredoka One', cursive;
      font-size: clamp(3rem, 10vw, 5rem);
      color: var(--text);
      text-shadow: 
        4px 4px 0 var(--lbp-pink),
        5px 5px 0 var(--strawberry);
      display: inline-block;
      padding: 0 15px;
      transform: rotate(-2deg);
    }
    
    main#garden {
      position: absolute;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      width: 90%;
      max-width: 1200px;
      height: 70%;
      z-index: 5;
    }

    /* Control Panel (The Card) */
    aside.controls {
      position: fixed;
      top: 20px;
      right: 20px;
      width: 280px;
      padding: 20px;
      background: var(--card);
      border: 4px solid var(--text);
      border-radius: 15px;
      box-shadow: 10px 10px 0 var(--shadow);
      z-index: 15;
      transition: all 0.3s ease-in-out;
      font-family: 'Comic Neue
