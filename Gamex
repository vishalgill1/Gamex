<!doctype html>
<html lang="hi">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>TourneyDown — Tournament App Download</title>
  <meta name="description" content="TourneyDown — Download the tournament app, register teams, view schedule, and get live updates.">
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700;800&display=swap" rel="stylesheet">
  <style>
    :root{
      --bg:#0f1724; /* deep navy */
      --card:#0b1220;
      --accent:#ff4757; /* energetic red */
      --accent-2:#ff8a65;
      --muted:#94a3b8;
      --glass: rgba(255,255,255,0.03);
    }
    *{box-sizing:border-box}
    html,body{height:100%;margin:0;font-family:Inter,system-ui,Segoe UI,Roboto,'Helvetica Neue',Arial;color:#e6eef8;background:linear-gradient(180deg,var(--bg),#071022);}
    a{color:inherit;text-decoration:none}
    .container{max-width:1100px;margin:0 auto;padding:28px}

    /* header */
    header{display:flex;align-items:center;justify-content:space-between;padding:12px 0}
    .brand{display:flex;gap:12px;align-items:center}
    .logo{width:56px;height:56px;border-radius:12px;background:linear-gradient(135deg,var(--accent),var(--accent-2));display:flex;align-items:center;justify-content:center;color:white;font-weight:800;font-size:20px;box-shadow:0 6px 18px rgba(255,71,87,0.18)}
    nav{display:flex;gap:18px;align-items:center}
    nav a{color:var(--muted);font-weight:600}
    .cta{background:linear-gradient(90deg,var(--accent),var(--accent-2));padding:10px 14px;border-radius:10px;color:white;font-weight:700;box-shadow:0 8px 24px rgba(255,72,87,0.18)}

    /* hero */
    .hero{display:grid;grid-template-columns:1fr 420px;gap:34px;align-items:center;padding:36px 0}
    .hero-left h1{font-size:40px;margin:0 0 12px;line-height:1.05}
    .tag{color:var(--muted);margin-bottom:18px}
    .download-row{display:flex;gap:12px;align-items:center}
    .btn{display:inline-flex;gap:10px;align-items:center;padding:12px 16px;border-radius:12px;background:rgba(255,255,255,0.04);border:1px solid rgba(255,255,255,0.03);cursor:pointer}
    .btn.primary{background:linear-gradient(90deg,var(--accent),var(--accent-2));color:white;border:none}
    .app-card{background:linear-gradient(180deg,rgba(255,255,255,0.02),rgba(255,255,255,0.01));padding:22px;border-radius:16px;border:1px solid rgba(255,255,255,0.03);box-shadow:0 20px 50px rgba(2,6,23,0.6)}
    .device{width:100%;height:460px;border-radius:14px;background:linear-gradient(180deg,#071228,#081926);position:relative;overflow:hidden;padding:18px;display:flex;flex-direction:column}
    .device .screen{flex:1;border-radius:10px;background:linear-gradient(180deg,#041026,#092033);display:flex;align-items:center;justify-content:center;color:var(--muted);font-size:14px}

    /* features */
    .features{display:grid;grid-template-columns:repeat(3,1fr);gap:18px;margin-top:28px}
    .feature{background:var(--card);padding:18px;border-radius:12px;border:1px solid var(--glass)}
    .feature h4{margin:0 0 8px}
    .promo-banner{margin-top:18px;background:linear-gradient(90deg,rgba(255,72,87,0.06),rgba(255,138,101,0.03));padding:16px;border-radius:12px;display:flex;justify-content:space-between;align-items:center}

    /* sections */
    section{margin-top:48px}
    .screenshots{display:flex;gap:12px;overflow:auto;padding-bottom:6px}
    .shot{min-width:240px;height:420px;border-radius:12px;background:linear-gradient(180deg,#06222f,#071a2b);display:flex;align-items:center;justify-content:center;color:var(--muted);font-weight:600}

    footer{margin-top:48px;padding:28px 0;color:var(--muted);display:flex;justify-content:space-between;align-items:center}

    /* small screens */
    @media (max-width:880px){
      .hero{grid-template-columns:1fr;}
      .device{height:360px}
      .features{grid-template-columns:repeat(2,1fr)}
    }
    @media (max-width:520px){
      .features{grid-template-columns:1fr}
      .device{height:300px}
    }

    /* micro animations */
    .pulse{animation:pulse 2.4s infinite}
    @keyframes pulse{0%{transform:scale(1)}50%{transform:scale(1.03)}100%{transform:scale(1)}}
    .float{animation:float 6s ease-in-out infinite}
    @keyframes float{0%{transform:translateY(0)}50%{transform:translateY(-10px)}100%{transform:translateY(0)}}

    /* simple modal */
    .modal-backdrop{position:fixed;inset:0;background:rgba(3,6,12,0.6);display:none;align-items:center;justify-content:center;padding:20px}
    .modal{background:#071226;padding:20px;border-radius:12px;border:1px solid rgba(255,255,255,0.04);max-width:760px;width:100%}
    .close-btn{background:transparent;border:1px solid rgba(255,255,255,0.04);padding:6px 10px;border-radius:8px}
  </style>
</head>
<body>
  <div class="container">
    <header>
      <div class="brand">
        <div class="logo">TD</div>
        <div>
          <div style="font-weight:800;color:white">TourneyDown</div>
          <div style="color:var(--muted);font-size:13px">Tournament app — download & compete</div>
        </div>
      </div>
      <nav>
        <a href="#features">Features</a>
        <a href="#screens">Screens</a>
        <a href="#faq">FAQ</a>
        <a class="cta" href="#download">Download</a>
      </nav>
    </header>

    <main>
      <section class="hero">
        <div class="hero-left">
          <h1>Apni tournament team banayein — ab aur asaan</h1>
          <p class="tag">TourneyDown se team register karein, bracket dekhein, live score aur push updates payen. Bas app download kijiye aur khel shuru kijiye.</p>
          <div class="download-row">
            <button class="btn primary" onclick="openModal()">APK Download — Android</button>
            <a class="btn" href="#" onclick="notify('App Store link jaldi aayega')">App Store</a>
            <a class="btn" href="#contact">Contact</a>
          </div>

          <div class="promo-banner" style="margin-top:18px">
            <div>
              <strong>Launch Offer:</strong> Pehle 100 teams ko free premium bracket tools.
            </div>
            <div style="font-weight:700;color:var(--accent)">Limited Time</div>
          </div>

          <div style="margin-top:18px;color:var(--muted);font-size:14px">Share karo: <a href="#">WhatsApp</a> • <a href="#">Telegram</a> • <a href="#">Instagram</a></div>
        </div>

        <div class="app-card pulse float">
          <div style="display:flex;justify-content:space-between;align-items:center;margin-bottom:12px">
            <div style="font-weight:700">TourneyDown</div>
            <div style="font-size:13px;color:var(--muted)">Version 1.0 — 12 MB</div>
          </div>
          <div class="device">
            <div class="screen">
              <div style="text-align:center">
                <div style="font-size:18px;font-weight:700;color:white;margin-bottom:6px">Upcoming: City Championship</div>
                <div style="color:var(--muted);max-width:300px;margin:0 auto">Team A vs Team B — Dec 12 · 5:00 PM</div>
              </div>
            </div>
            <div style="display:flex;gap:8px;align-items:center;margin-top:12px">
              <div class="btn" onclick="notify('Sharing link copied')">Share</div>
              <div class="btn" onclick="openModal()">Download APK</div>
            </div>
          </div>
        </div>
      </section>

      <section id="features">
        <h2 style="color:white;margin:0 0 12px">Features</h2>
        <div class="features">
          <div class="feature">
            <h4>Bracket Management</h4>
            <div style="color:var(--muted);font-size:13px">Teams add karein, seedings set karein aur bracket automatically generate karein.</div>
          </div>
          <div class="feature">
            <h4>Live Score & Notifications</h4>
            <div style="color:var(--muted);font-size:13px">Har match ke liye live updates aur push notifications.</div>
          </div>
          <div class="feature">
            <h4>Team Chat & Profiles</h4>
            <div style="color:var(--muted);font-size:13px">Team members ke liye built-in chat aur profile cards.</div>
          </div>
        </div>
      </section>

      <section id="screens">
        <h2 style="color:white;margin:0 0 12px">App Screenshots</h2>
        <div class="screenshots">
          <div class="shot">Home</div>
          <div class="shot">Bracket</div>
          <div class="shot">Live Score</div>
          <div class="shot">Team Profile</div>
        </div>
      </section>

      <section id="download">
        <h2 style="color:white;margin:0 0 12px">Download</h2>
        <div style="display:flex;gap:12px;flex-wrap:wrap;align-items:center">
          <div style="flex:1;min-width:220px">
            <div style="background:linear-gradient(180deg,rgba(255,255,255,0.02),transparent);padding:16px;border-radius:12px;border:1px solid rgba(255,255,255,0.03)">
              <div style="font-weight:800">Android APK</div>
              <div style="color:var(--muted);font-size:13px;margin:8px 0">Sideload karein: Settings → Security → Unknown sources (Android 8+ par install karne se pehle allow karein).</div>
              <div style="display:flex;gap:8px">
                <button class="btn primary" onclick="openModal()">Direct APK</button>
                <a class="btn" href="#" onclick="notify('Play Store link coming soon')">Play Store</a>
              </div>
            </div>
          </div>

          <div style="flex:1;min-width:220px">
            <div style="background:linear-gradient(180deg,rgba(255,255,255,0.02),transparent);padding:16px;border-radius:12px;border:1px solid rgba(255,255,255,0.03)">
              <div style="font-weight:800">iPhone</div>
              <div style="color:var(--muted);font-size:13px;margin:8px 0">iOS version jaldi aa raha hai — TestFlight invite ke liye contact karein.</div>
              <div style="display:flex;gap:8px">
                <button class="btn" onclick="notify('TestFlight invite request sent')">Request Invite</button>
              </div>
            </div>
          </div>
        </div>
      </section>

      <section id="faq">
        <h2 style="color:white;margin:0 0 12px">FAQ</h2>
        <div style="display:grid;gap:12px;max-width:920px">
          <div style="background:var(--card);padding:14px;border-radius:10px;border:1px solid var(--glass)">
            <strong>Q:</strong> Kya app free hai?
            <div style="color:var(--muted);margin-top:6px">A: Haan, basic features free hain. Premium bracket tools paid hain.</div>
          </div>
          <div style="background:var(--card);padding:14px;border-radius:10px;border:1px solid var(--glass)">
            <strong>Q:</strong> APK safe hai?
            <div style="color:var(--muted);margin-top:6px">A: Hamare build signed hai. Install karne se pehle permissions check karein.</div>
          </div>
        </div>
      </section>

      <section id="contact">
        <h2 style="color:white;margin:0 0 12px">Contact & Support</h2>
        <div style="display:flex;gap:16px;flex-wrap:wrap">
          <div style="min-width:260px;background:var(--card);padding:12px;border-radius:10px;border:1px solid var(--glass)">
            <div style="font-weight:700">Get support</div>
            <div style="color:var(--muted);margin-top:6px">Email: support@tourneydown.app</div>
            <div style="color:var(--muted);margin-top:6px">WhatsApp: +91 98765 43210</div>
          </div>

          <form id="leadForm" style="flex:1;min-width:260px;background:var(--card);padding:12px;border-radius:10px;border:1px solid var(--glass)" onsubmit="event.preventDefault();submitLead()">
            <div style="margin-bottom:8px"><input id="name" placeholder="Naam" required style="width:100%;padding:10px;border-radius:8px;border:1px solid rgba(255,255,255,0.03);background:transparent;color:white"></div>
            <div style="margin-bottom:8px"><input id="email" placeholder="Email" required style="width:100%;padding:10px;border-radius:8px;border:1px solid rgba(255,255,255,0.03);background:transparent;color:white"></div>
            <div style="display:flex;gap:8px"><button class="btn primary" type="submit">Send</button><button class="btn" type="button" onclick="notify('Support pe ham jald contact karenge')">Chat</button></div>
          </form>
        </div>
      </section>

    </main>

    <footer>
      <div>© <span id="year"></span> TourneyDown</div>
      <div style="color:var(--muted)">Built with ❤️ — Tournament organisers friendly</div>
    </footer>
  </div>

  <!-- simple modal for APK details -->
  <div id="modal" class="modal-backdrop" onclick="closeModal(event)">
    <div class="modal" onclick="event.stopPropagation()">
      <div style="display:flex;justify-content:space-between;align-items:center;margin-bottom:10px">
        <div style="font-weight:800">Direct APK Download</div>
        <button class="close-btn" onclick="closeModal(event)">Close</button>
      </div>
      <div style="color:var(--muted);margin-bottom:12px">Yahaan pe aap real APK link daal sakte hain. Example: <code>/downloads/tourneydown-v1.apk</code></div>
      <div style="display:flex;gap:8px;flex-wrap:wrap">
        <a class="btn primary" href="/downloads/tourneydown-v1.apk">Download APK (12 MB)</a>
        <a class="btn" href="#" onclick="notify('Mirror download copied')">Mirror Link</a>
      </div>
    </div>
  </div>

  <script>
    document.getElementById('year').innerText = new Date().getFullYear();
    function openModal(){document.getElementById('modal').style.display='flex'}
    function closeModal(e){if(e) e.stopPropagation();document.getElementById('modal').style.display='none'}
    function notify(msg){alert(msg)}
    function submitLead(){
      const name=document.getElementById('name').value || 'Guest';
      alert('Shukriya '+name+'! Hum jaldi contact karenge.');
      document.getElementById('leadForm').reset();
    }
  </script>
</body>
</html>
