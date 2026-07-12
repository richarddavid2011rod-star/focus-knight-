# focus-knight-<!DOCTYPE html>
<html>
<head><meta name="google-site-verification" content="Vhd-k2hqKLtSTWakc522EVPulMgPv4FE4OINvHk9bVs" />
<title>Knight Focus ♞</title>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
    *{margin:0;padding:0;box-sizing:border-box}
    body{
        background:#0a0a14; color:#e5e5e5; font-family:'Segoe UI', sans-serif;
        display:flex; justify-content:center; align-items:center; min-height:100vh;
        background: radial-gradient(circle at center, #1a1a2e 0%, #0a0a14 100%);
    }
    .container{
        background:#161625; padding:40px; border-radius:16px; 
        box-shadow:0 0 40px rgba(139,92,246,0.3); border:1px solid #8b5cf6;
        text-align:center; width:90%; max-width:500px;
    }
    h1{color:#8b5cf6; margin-bottom:10px; text-shadow:0 0 10px #8b5cf6}
    .timer{font-size:80px; font-weight:bold; margin:20px 0; color:#fff; font-variant-numeric:tabular-nums}
    .mode{font-size:18px; color:#a78bfa; margin-bottom:20px}
    .btns{display:flex; gap:10px; justify-content:center; margin-bottom:30px}
    button{
        background:#8b5cf6; color:white; border:none; padding:12px 24px; 
        border-radius:8px; font-size:16px; font-weight:600; cursor:pointer;
        transition:0.2s;
    }
    button:hover{background:#7c3aed; transform:scale(1.05)}
    button.secondary{background:#333; color:#aaa}
    button.danger{background:#ef4444}

    .blocker{
        background:#1f1f33; padding:20px; border-radius:12px; margin-top:20px;
        text-align:left;
    }
    .blocker h3{color:#a78bfa; margin-bottom:10px}
    .site-input{display:flex; gap:8px}
    .site-input input{
        flex:1; padding:10px; background:#0a0a14; border:1px solid #333; 
        border-radius:6px; color:#fff
    }
    .site-list{margin-top:10px}
    .site-tag{
        background:#8b5cf6; display:inline-block; padding:6px 12px; 
        border-radius:20px; margin:4px; font-size:14px;
    }
    .site-tag span{cursor:pointer; margin-left:8px; color:#000; font-weight:bold}
    
    .sounds{display:flex; gap:10px; margin-top:15px; justify-content:center}
    .sound-btn{
        background:#333; padding:8px 16px; border-radius:6px; cursor:pointer;
    }
    .sound-btn.active{background:#8b5cf6}
</style>
</head>
<body>
    <div class="container">
        <h1>♞ Knight Focus</h1>
        <p>Stay in the zone. Block distractions.</p>

        <div class="mode" id="mode">Focus Time</div>
        <div class="timer" id="timer">25:00</div>

        <div class="btns">
            <button id="start">Start</button>
            <button id="pause" class="secondary">Pause</button>
            <button id="reset" class="danger">Reset</button>
        </div>

        <div class="sounds">
            <div class="sound-btn" onclick="playSound('rain')">🌧️ Rain</div>
            <div class="sound-btn" onclick="playSound('white')">⚪ White Noise</if(!isPaid && focusSessions > 3){ 
    alert("Free limit: 3 sessions/day. Pay ₦1100 for unlimited") 
}