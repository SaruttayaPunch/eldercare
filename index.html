<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0">
<title>CareCompanion</title>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">
<style>
*,*::before,*::after{box-sizing:border-box;margin:0;padding:0}
:root{
  --bg:#F7F7F7;--white:#fff;--accent:#F5A623;--green:#4CAF82;
  --dark:#1A1A2E;--text:#333;--muted:#999;--border:#EFEFEF;
}
body{font-family:'Poppins',sans-serif;background:var(--bg);color:var(--text);max-width:390px;margin:0 auto;min-height:100vh;overflow-x:hidden}

/* ── SCREENS ── */
.screen{display:none;flex-direction:column;min-height:100vh}
.screen.active{display:flex}

/* ── TOP NAV ── */
.topnav{background:var(--white);padding:16px 20px;display:flex;align-items:center;justify-content:space-between;position:sticky;top:0;z-index:50;border-bottom:1px solid var(--border)}
.menu-icon{font-size:20px;cursor:pointer}
.logo{font-size:14px;font-weight:700;color:var(--dark)}
.avatar-sm{width:34px;height:34px;border-radius:50%;background:linear-gradient(135deg,var(--accent),#e8831a);display:flex;align-items:center;justify-content:center;font-size:15px}

/* ── HOME SCREEN ── */
.hero-header{background:var(--white);padding:6px 20px 20px}
.hero-header h1{font-size:24px;font-weight:800;color:var(--dark);line-height:1.25;margin-bottom:4px}
.hero-header h1 span{color:var(--accent)}
.hero-header p{font-size:13px;color:var(--muted)}

.search-wrap{background:var(--white);padding:0 20px 16px}
.search-box{display:flex;align-items:center;gap:10px;background:var(--bg);border-radius:14px;padding:11px 16px;border:1.5px solid transparent;transition:border-color .2s}
.search-box:focus-within{border-color:var(--accent)}
.search-box input{border:none;background:transparent;font-family:'Poppins',sans-serif;font-size:14px;color:var(--text);outline:none;flex:1}
.search-box input::placeholder{color:var(--muted)}
.filter-btn{background:var(--accent);border:none;border-radius:10px;width:36px;height:36px;display:flex;align-items:center;justify-content:center;font-size:15px;cursor:pointer;flex-shrink:0}

.chips-wrap{padding:0 20px 16px;display:flex;gap:8px;overflow-x:auto;scrollbar-width:none;background:var(--white)}
.chips-wrap::-webkit-scrollbar{display:none}
.chip{display:flex;align-items:center;gap:5px;padding:7px 14px;border-radius:30px;font-size:12px;font-weight:500;white-space:nowrap;cursor:pointer;border:2px solid transparent;transition:all .18s;flex-shrink:0;font-family:'Poppins',sans-serif}
.chip.active{background:var(--accent);color:var(--white)}
.chip:not(.active){background:var(--bg);color:var(--text)}

.sec-header{display:flex;justify-content:space-between;align-items:center;padding:18px 20px 12px}
.sec-header h2{font-size:16px;font-weight:700;color:var(--dark)}
.sec-header span{font-size:12px;color:var(--muted);cursor:pointer}

.featured-scroll{padding:0 20px 4px;display:flex;gap:12px;overflow-x:auto;scrollbar-width:none}
.featured-scroll::-webkit-scrollbar{display:none}
.feat-card{border-radius:18px;padding:18px;min-width:220px;position:relative;overflow:hidden;flex-shrink:0;cursor:pointer;transition:transform .15s}
.feat-card:active{transform:scale(.97)}
.feat-emoji{font-size:44px;position:absolute;top:12px;right:14px;filter:drop-shadow(0 4px 8px rgba(0,0,0,.25))}
.feat-tag{background:var(--accent);color:#fff;font-size:9px;font-weight:600;letter-spacing:1px;padding:3px 9px;border-radius:20px;display:inline-block;margin-bottom:8px}
.feat-title{font-size:14px;font-weight:700;color:#fff;margin-bottom:3px;max-width:130px;line-height:1.3}
.feat-sub{font-size:11px;color:rgba(255,255,255,.5);max-width:120px;line-height:1.5}
.feat-price{margin-top:12px;font-size:16px;font-weight:700;color:var(--accent)}
.feat-price span{font-size:10px;font-weight:400;color:rgba(255,255,255,.4);margin-left:3px}

.results-meta{padding:0 20px 12px;font-size:13px;color:var(--muted)}
.results-meta strong{color:var(--dark);font-weight:700}

.grid{padding:0 20px;display:grid;grid-template-columns:1fr 1fr;gap:12px;margin-bottom:90px}
.svc-card{background:var(--white);border-radius:16px;overflow:hidden;cursor:pointer;transition:transform .15s;box-shadow:0 2px 10px rgba(0,0,0,.05);text-decoration:none;color:inherit;display:flex;flex-direction:column}
.svc-card:active{transform:scale(.97)}
.svc-img{height:90px;display:flex;align-items:center;justify-content:center;font-size:40px;position:relative}
.badge-tag{position:absolute;top:7px;left:7px;background:rgba(255,255,255,.9);border-radius:7px;font-size:9px;font-weight:600;padding:2px 7px;color:var(--text)}
.svc-body{padding:10px 10px 12px;flex:1}
.svc-title{font-size:12px;font-weight:700;color:var(--dark);margin-bottom:2px;line-height:1.3}
.svc-desc{font-size:11px;color:var(--muted);line-height:1.4;margin-bottom:8px}
.svc-footer{display:flex;align-items:center;justify-content:space-between}
.svc-price{font-size:14px;font-weight:700;color:var(--dark)}
.svc-price span{font-size:9px;font-weight:400;color:var(--muted)}
.add-btn{width:26px;height:26px;background:var(--accent);border:none;border-radius:7px;color:#fff;font-size:16px;display:flex;align-items:center;justify-content:center;cursor:pointer;font-weight:300;box-shadow:0 2px 8px rgba(245,166,35,.35)}

/* ── BOTTOM NAV ── */
.bottom-nav{position:fixed;bottom:0;left:50%;transform:translateX(-50%);width:100%;max-width:390px;background:var(--white);border-top:1px solid var(--border);display:flex;padding:8px 10px 20px;z-index:100;box-shadow:0 -4px 20px rgba(0,0,0,.07)}
.nav-item{flex:1;display:flex;flex-direction:column;align-items:center;gap:2px;cursor:pointer;text-decoration:none;color:var(--muted);font-size:10px;font-weight:500;transition:color .15s}
.nav-item .nicon{font-size:20px}
.nav-item.active{color:var(--accent)}
.nav-book{flex:1.4;background:var(--accent);border-radius:12px;display:flex;align-items:center;justify-content:center;flex-direction:column;gap:2px;margin:0 4px;color:#fff;font-size:10px;font-weight:600;text-decoration:none;cursor:pointer;padding:4px 0}
.nav-book .nicon{font-size:18px}

/* ── BOTTOM SHEET ── */
.overlay{position:fixed;inset:0;background:rgba(0,0,0,.5);z-index:200;opacity:0;pointer-events:none;transition:opacity .3s;max-width:390px;left:50%;transform:translateX(-50%)}
.overlay.show{opacity:1;pointer-events:all}
.sheet{position:fixed;bottom:0;left:50%;transform:translateX(-50%) translateY(100%);width:100%;max-width:390px;background:var(--white);border-radius:24px 24px 0 0;z-index:201;transition:transform .35s cubic-bezier(.4,0,.2,1);max-height:92vh;overflow-y:auto;padding-bottom:24px}
.sheet.open{transform:translateX(-50%) translateY(0)}
.sheet-handle{width:40px;height:4px;background:var(--border);border-radius:4px;margin:12px auto 0}
.sheet-head{padding:16px 20px 14px;border-bottom:1px solid var(--border)}
.sheet-top{display:flex;align-items:flex-start;justify-content:space-between}
.sheet-emoji{font-size:36px;margin-right:12px}
.sheet-info{flex:1}
.sheet-title{font-size:17px;font-weight:700;color:var(--dark)}
.sheet-price{font-size:14px;font-weight:600;color:var(--accent);margin-top:2px}
.sheet-desc{font-size:12px;color:var(--muted);margin-top:6px;line-height:1.55}
.close-btn{background:var(--bg);border:none;border-radius:50%;width:32px;height:32px;font-size:16px;cursor:pointer;display:flex;align-items:center;justify-content:center;flex-shrink:0}

.carers-section{padding:16px 20px 0}
.carers-label{font-size:14px;font-weight:700;color:var(--dark);margin-bottom:4px}
.carers-sub{font-size:12px;color:var(--muted);margin-bottom:14px}

.carer-card{background:var(--bg);border-radius:16px;padding:14px;margin-bottom:12px;cursor:pointer;transition:transform .15s}
.carer-card:active{transform:scale(.98)}
.carer-top{display:flex;align-items:center;gap:12px;margin-bottom:10px}
.carer-avatar{width:50px;height:50px;border-radius:50%;display:flex;align-items:center;justify-content:center;font-size:22px;flex-shrink:0;font-weight:700;color:#fff}
.carer-meta{flex:1}
.carer-name{font-size:14px;font-weight:700;color:var(--dark)}
.carer-age{font-size:11px;color:var(--muted)}
.carer-rating{display:flex;align-items:center;gap:5px;margin-top:3px}
.stars{color:#F5A623;font-size:12px}
.rating-num{font-size:12px;font-weight:600;color:var(--dark)}
.review-count{font-size:11px;color:var(--muted)}
.verified{display:inline-flex;align-items:center;gap:3px;background:#E8F7F0;color:var(--green);font-size:10px;font-weight:600;padding:2px 8px;border-radius:20px;margin-left:auto;flex-shrink:0}
.skill-tags{display:flex;flex-wrap:wrap;gap:6px;margin-bottom:12px}
.skill-tag{background:var(--white);border:1px solid var(--border);border-radius:20px;font-size:10px;font-weight:500;padding:3px 10px;color:var(--text)}
.carer-actions{display:flex;gap:8px}
.btn-outline{flex:1;background:transparent;border:1.5px solid var(--accent);color:var(--accent);border-radius:10px;padding:9px;font-family:'Poppins',sans-serif;font-size:12px;font-weight:600;cursor:pointer;transition:all .15s}
.btn-outline:active{background:var(--accent);color:#fff}
.btn-fill{flex:1;background:var(--accent);border:none;color:#fff;border-radius:10px;padding:9px;font-family:'Poppins',sans-serif;font-size:12px;font-weight:600;cursor:pointer;box-shadow:0 3px 10px rgba(245,166,35,.3)}

/* ── PROFILE SCREEN ── */
#profileScreen{background:var(--bg);overflow-y:auto}
.profile-header{background:var(--white);padding:16px 20px;display:flex;align-items:center;gap:14px;border-bottom:1px solid var(--border);position:sticky;top:0;z-index:10}
.back-btn{background:var(--bg);border:none;border-radius:50%;width:36px;height:36px;display:flex;align-items:center;justify-content:center;font-size:18px;cursor:pointer;flex-shrink:0}
.profile-header-title{font-size:15px;font-weight:700;color:var(--dark)}

.profile-hero{background:var(--white);padding:28px 20px 22px;display:flex;flex-direction:column;align-items:center;text-align:center;border-bottom:1px solid var(--border)}
.profile-avatar{width:90px;height:90px;border-radius:50%;display:flex;align-items:center;justify-content:center;font-size:38px;font-weight:700;color:#fff;margin-bottom:14px;box-shadow:0 6px 24px rgba(0,0,0,.12)}
.profile-name{font-size:20px;font-weight:800;color:var(--dark);margin-bottom:2px}
.profile-location{font-size:13px;color:var(--muted);margin-bottom:8px}
.profile-rating-row{display:flex;align-items:center;gap:8px;justify-content:center}
.p-stars{color:var(--accent);font-size:14px}
.p-rating{font-size:14px;font-weight:700;color:var(--dark)}
.p-reviews{font-size:12px;color:var(--muted)}
.p-verified{display:inline-flex;align-items:center;gap:3px;background:#E8F7F0;color:var(--green);font-size:11px;font-weight:600;padding:3px 10px;border-radius:20px;margin-top:8px}

.profile-section{background:var(--white);margin:10px 0;padding:18px 20px}
.p-sec-title{font-size:13px;font-weight:700;color:var(--dark);margin-bottom:10px;text-transform:uppercase;letter-spacing:.5px}
.p-bio{font-size:13px;color:var(--text);line-height:1.65}
.p-tags{display:flex;flex-wrap:wrap;gap:7px}
.p-tag{background:var(--bg);border:1px solid var(--border);border-radius:20px;font-size:12px;font-weight:500;padding:5px 13px;color:var(--text)}
.p-tag.highlight{background:#FFF3DC;border-color:#F5A623;color:#b37a10}

.review-card{background:var(--bg);border-radius:12px;padding:12px 14px;margin-bottom:10px}
.review-top{display:flex;align-items:center;justify-content:space-between;margin-bottom:5px}
.reviewer-name{font-size:13px;font-weight:600;color:var(--dark)}
.review-date{font-size:11px;color:var(--muted)}
.review-stars{color:var(--accent);font-size:12px;margin-bottom:5px}
.review-text{font-size:12px;color:var(--text);line-height:1.55}

.exp-card{display:flex;gap:12px;align-items:flex-start;margin-bottom:10px}
.exp-icon{width:40px;height:40px;background:var(--bg);border-radius:10px;display:flex;align-items:center;justify-content:center;font-size:18px;flex-shrink:0}
.exp-title{font-size:13px;font-weight:600;color:var(--dark)}
.exp-sub{font-size:12px;color:var(--muted)}

.profile-book-bar{background:var(--white);padding:12px 20px 28px;border-top:1px solid var(--border);display:flex;align-items:center;gap:14px;margin-top:10px}
.book-price{font-size:20px;font-weight:800;color:var(--dark)}
.book-price span{font-size:12px;font-weight:400;color:var(--muted)}
.book-btn{flex:1;background:var(--accent);border:none;color:#fff;border-radius:13px;padding:15px;font-family:'Poppins',sans-serif;font-size:15px;font-weight:700;cursor:pointer;box-shadow:0 4px 16px rgba(245,166,35,.35)}

/* colors */
.bg-o{background:linear-gradient(135deg,#FFE4C4,#FFD09B)}
.bg-g{background:linear-gradient(135deg,#D4EDDA,#B8DFCA)}
.bg-b{background:linear-gradient(135deg,#D6EAF8,#AED6F1)}
.bg-p{background:linear-gradient(135deg,#E8D5F5,#D2B4E8)}
.bg-pk{background:linear-gradient(135deg,#FADBD8,#F9B6B0)}
.bg-y{background:linear-gradient(135deg,#FEF9C3,#FDE68A)}

.av1{background:linear-gradient(135deg,#667eea,#764ba2)}
.av2{background:linear-gradient(135deg,#f093fb,#f5576c)}
.av3{background:linear-gradient(135deg,#4facfe,#00f2fe)}
.av4{background:linear-gradient(135deg,#43e97b,#38f9d7)}
.av5{background:linear-gradient(135deg,#fa709a,#fee140)}

/* ── BROWSE CARER CARD ── */
.browse-card{background:var(--white);border-radius:18px;padding:16px;box-shadow:0 2px 12px rgba(0,0,0,.06);cursor:pointer;transition:transform .15s;border:1px solid var(--border)}
.browse-card:active{transform:scale(.98)}
.browse-top{display:flex;gap:14px;margin-bottom:12px}
.browse-avatar{width:64px;height:64px;border-radius:16px;display:flex;align-items:center;justify-content:center;font-size:24px;font-weight:700;color:#fff;flex-shrink:0}
.browse-meta{flex:1}
.browse-name{font-size:15px;font-weight:700;color:var(--dark);margin-bottom:2px}
.browse-role{font-size:11px;color:var(--muted);margin-bottom:5px}
.browse-rating{display:flex;align-items:center;gap:5px}
.browse-stars{color:var(--accent);font-size:12px}
.browse-num{font-size:12px;font-weight:600;color:var(--dark)}
.browse-rev{font-size:11px;color:var(--muted)}
.browse-verified{display:inline-flex;align-items:center;gap:3px;background:#E8F7F0;color:var(--green);font-size:10px;font-weight:600;padding:2px 8px;border-radius:20px;margin-top:4px}
.browse-bio{font-size:12px;color:var(--muted);line-height:1.55;margin-bottom:10px}
.browse-skills{display:flex;flex-wrap:wrap;gap:6px;margin-bottom:12px}
.browse-skill{background:var(--bg);border:1px solid var(--border);border-radius:20px;font-size:10px;font-weight:500;padding:3px 10px;color:var(--text)}
.browse-actions{display:flex;gap:8px}
.browse-actions .btn-outline{flex:1;background:transparent;border:1.5px solid var(--accent);color:var(--accent);border-radius:10px;padding:9px;font-family:'Poppins',sans-serif;font-size:12px;font-weight:600;cursor:pointer}
.browse-actions .btn-fill{flex:1;background:var(--accent);border:none;color:#fff;border-radius:10px;padding:9px;font-family:'Poppins',sans-serif;font-size:12px;font-weight:600;cursor:pointer;box-shadow:0 3px 10px rgba(245,166,35,.3)}

@keyframes fadeUp{from{opacity:0;transform:translateY(14px)}to{opacity:1;transform:translateY(0)}}
.grid .svc-card{animation:fadeUp .4s ease forwards;opacity:0}
.grid .svc-card:nth-child(1){animation-delay:.05s}
.grid .svc-card:nth-child(2){animation-delay:.12s}
.grid .svc-card:nth-child(3){animation-delay:.19s}
.grid .svc-card:nth-child(4){animation-delay:.26s}
.grid .svc-card:nth-child(5){animation-delay:.33s}
.grid .svc-card:nth-child(6){animation-delay:.40s}
</style>
</head>
<body>

<!-- ══════════════ HOME SCREEN ══════════════ -->
<div class="screen active" id="homeScreen">

  <div class="topnav">
    <span class="menu-icon">☰</span>
    <div class="logo">CareCompanion 🧡</div>
    <div class="avatar-sm">👤</div>
  </div>

  <div style="overflow-y:auto;flex:1;padding-bottom:80px">
    <div class="hero-header">
      <h1>Find and book<br>your care <span>service 🧡</span></h1>
      <p>Trusted companions for your loved ones</p>
    </div>

    <div class="search-wrap">
      <div class="search-box">
        <span>🔍</span>
        <input type="text" placeholder="Search services...">
        <button class="filter-btn">⚙️</button>
      </div>
    </div>

    <div class="chips-wrap">
      <div class="chip active" onclick="filterChip(this)">🏥 Medical</div>
      <div class="chip" onclick="filterChip(this)">🌳 Outings</div>
      <div class="chip" onclick="filterChip(this)">🏠 Home Care</div>
      <div class="chip" onclick="filterChip(this)">🛒 Errands</div>
      <div class="chip" onclick="filterChip(this)">💬 Social</div>
    </div>

    <div class="sec-header"><h2>✨ Most Booked</h2><span>See all</span></div>
    <div class="featured-scroll">
      <div class="feat-card" style="background:linear-gradient(135deg,#1A1A2E,#2d2d44)" onclick="openSheet('Hospital Companion','🏥','$25/visit','Escort to appointments, wait alongside, note doctor\'s instructions, and send a full summary to the family.')">
        <span class="feat-emoji">🏥</span>
        <div class="feat-tag">POPULAR</div>
        <div class="feat-title">Hospital Companion</div>
        <div class="feat-sub">Escort, wait & report back</div>
        <div class="feat-price">1300฿ <span>/ visit</span></div>
      </div>
      <div class="feat-card" style="background:linear-gradient(135deg,#1B4332,#2D6A4F)" onclick="openSheet('Senior Outing','🌳','$18/trip','Park walks, temple visits, or lunch with friends — we escort and keep your loved one safe and happy.')">
        <span class="feat-emoji">🌳</span>
        <div class="feat-tag">NEW</div>
        <div class="feat-title">Senior Outing</div>
        <div class="feat-sub">Park, temple & friends</div>
        <div class="feat-price">1000฿ <span>/ trip</span></div>
      </div>
      <div class="feat-card" style="background:linear-gradient(135deg,#4A1C40,#7B2D8B)" onclick="openSheet('Companionship','💬','$15/hour','A friendly visit to chat, teach social media, or simply read aloud — so your loved one never feels alone.')">
        <span class="feat-emoji">💬</span>
        <div class="feat-tag">LOVED</div>
        <div class="feat-title">Companionship</div>
        <div class="feat-sub">Chat, teach & read aloud</div>
        <div class="feat-price">600฿ <span>/ hour</span></div>
      </div>
    </div>

    <div class="sec-header"><h2>🔍 All Services</h2></div>
    <div class="results-meta">Found <strong>6 services</strong> near you</div>

    <div class="grid">
      <div class="svc-card" onclick="openSheet('Hospital Companion','🏥','$25/visit','Escort to appointments, wait alongside, note doctor\'s instructions, and send a full summary to the family.')">
        <div class="svc-img bg-o">🏥<span class="badge-tag">Medical</span></div>
        <div class="svc-body">
          <div class="svc-title">Hospital Companion</div>
          <div class="svc-desc">Escort & note doctor's orders</div>
          <div class="svc-footer"><div class="svc-price">1300฿ <span>/visit</span></div><button class="add-btn" onclick="addTap(event,this)">+</button></div>
        </div>
      </div>
      <div class="svc-card" onclick="openSheet('Health Check-up Trip','🩺','$35/trip','Full door-to-door service for yearly health screenings — pickup, companionship throughout, and drop-off.')">
        <div class="svc-img bg-b">🩺<span class="badge-tag">Medical</span></div>
        <div class="svc-body">
          <div class="svc-title">Health Check-up Trip</div>
          <div class="svc-desc">Full annual screening</div>
          <div class="svc-footer"><div class="svc-price">1500฿ <span>/trip</span></div><button class="add-btn" onclick="addTap(event,this)">+</button></div>
        </div>
      </div>
      <div class="svc-card" onclick="openSheet('Senior Outing','🌳','$18/trip','Park walks, temple visits, or lunch with friends — we escort and keep your loved one safe and happy.')">
        <div class="svc-img bg-g">🌳<span class="badge-tag">Outing</span></div>
        <div class="svc-body">
          <div class="svc-title">Senior Outing</div>
          <div class="svc-desc">Park, temple or friends</div>
          <div class="svc-footer"><div class="svc-price">1000฿ <span>/trip</span></div><button class="add-btn" onclick="addTap(event,this)">+</button></div>
        </div>
      </div>
      <div class="svc-card" onclick="openSheet('Grocery Assistant','🛒','$12/trip','Accompany for shopping, or take a list from the family and pick everything up — fresh and on time.')">
        <div class="svc-img bg-y">🛒<span class="badge-tag">Errand</span></div>
        <div class="svc-body">
          <div class="svc-title">Grocery Assistant</div>
          <div class="svc-desc">Shop or pick up for them</div>
          <div class="svc-footer"><div class="svc-price">1000฿ <span>/trip</span></div><button class="add-btn" onclick="addTap(event,this)">+</button></div>
        </div>
      </div>
      <div class="svc-card" onclick="openSheet('Safety Check','🏠','$20/check','Inspect the home — replace bulbs, check anti-slip flooring, secure loose carpets, and flag any hazards.')">
        <div class="svc-img bg-pk">🏠<span class="badge-tag">Home</span></div>
        <div class="svc-body">
          <div class="svc-title">Safety Check</div>
          <div class="svc-desc">Hazard & home inspection</div>
          <div class="svc-footer"><div class="svc-price">1000฿ <span>/check</span></div><button class="add-btn" onclick="addTap(event,this)">+</button></div>
        </div>
      </div>
      <div class="svc-card" onclick="openSheet('Companionship','💬','$15/hour','A friendly visit to chat, teach social media, or simply read aloud — so your loved one never feels alone.')">
        <div class="svc-img bg-p">💬<span class="badge-tag">Social</span></div>
        <div class="svc-body">
          <div class="svc-title">Companionship</div>
          <div class="svc-desc">Chat, teach & read aloud</div>
          <div class="svc-footer"><div class="svc-price">600฿ <span>/hr</span></div><button class="add-btn" onclick="addTap(event,this)">+</button></div>
        </div>
      </div>
    </div>
  </div>

  <nav class="bottom-nav">
    <a class="nav-item active" onclick="switchTab('home',this)"><span class="nicon">🏠</span>Home</a>
    <a class="nav-item" onclick="switchTab('carers',this)"><span class="nicon">👥</span>Carers</a>
    <a class="nav-book"><span class="nicon">📅</span>Book</a>
    <a class="nav-item"><span class="nicon">📋</span>My Care</a>
    <a class="nav-item"><span class="nicon">👤</span>Profile</a>
  </nav>
</div>

<!-- ══════════════ CARERS SCREEN ══════════════ -->
<div class="screen" id="carersScreen">
  <div class="topnav">
    <span class="menu-icon">☰</span>
    <div class="logo">Our Carers 👥</div>
    <div class="avatar-sm">👤</div>
  </div>
  <div style="overflow-y:auto;flex:1;padding-bottom:90px">
    <div class="hero-header">
      <h1>Meet our <span>trusted carers</span></h1>
      <p>Verified, rated & ready to help</p>
    </div>
    <div class="search-wrap">
      <div class="search-box">
        <span>🔍</span>
        <input type="text" placeholder="Search carers by name or skill..." oninput="filterCarers(this.value)">
        <button class="filter-btn">⚙️</button>
      </div>
    </div>
    <div class="chips-wrap" id="carerChips">
      <div class="chip active" onclick="filterCarerChip(this,'all')">⭐ All</div>
      <div class="chip" onclick="filterCarerChip(this,'medical')">🏥 Medical</div>
      <div class="chip" onclick="filterCarerChip(this,'outing')">🌳 Outings</div>
      <div class="chip" onclick="filterCarerChip(this,'home')">🏠 Home Care</div>
      <div class="chip" onclick="filterCarerChip(this,'social')">💬 Social</div>
    </div>
    <div style="padding:4px 20px 10px;display:flex;justify-content:space-between;align-items:center">
      <div style="font-size:13px;color:var(--muted)">Showing <strong id="carerCount" style="color:var(--dark)">3</strong> carers</div>
      <div style="font-size:12px;color:var(--accent);font-weight:600;cursor:pointer">Top Rated ↓</div>
    </div>
    <div id="carerBrowseList" style="padding:0 20px;display:flex;flex-direction:column;gap:14px;margin-bottom:10px"></div>
  </div>
  <nav class="bottom-nav">
    <a class="nav-item" onclick="switchTab('home',this)"><span class="nicon">🏠</span>Home</a>
    <a class="nav-item active" onclick="switchTab('carers',this)"><span class="nicon">👥</span>Carers</a>
    <a class="nav-book"><span class="nicon">📅</span>Book</a>
    <a class="nav-item"><span class="nicon">📋</span>My Care</a>
    <a class="nav-item"><span class="nicon">👤</span>Profile</a>
  </nav>
</div>

<!-- ══════════════ PROFILE SCREEN ══════════════ -->
<div class="screen" id="profileScreen">
  <div class="profile-header">
    <button class="back-btn" onclick="closeProfile()">←</button>
    <div class="profile-header-title" id="profileHeaderName">Carer Profile</div>
  </div>
  <div style="overflow-y:auto;flex:1" id="profileContent"></div>
</div>

<!-- ══════════════ OVERLAY + SHEET ══════════════ -->
<div class="overlay" id="overlay" onclick="closeSheet()"></div>
<div class="sheet" id="sheet">
  <div class="sheet-handle"></div>
  <div class="sheet-head">
    <div class="sheet-top">
      <div style="display:flex;align-items:flex-start">
        <span class="sheet-emoji" id="sheetEmoji">🏥</span>
        <div class="sheet-info">
          <div class="sheet-title" id="sheetTitle">Service</div>
          <div class="sheet-price" id="sheetPrice">$25/visit</div>
        </div>
      </div>
      <button class="close-btn" onclick="closeSheet()">✕</button>
    </div>
    <div class="sheet-desc" id="sheetDesc"></div>
  </div>
  <div class="carers-section">
    <div class="carers-label">Choose your carer</div>
    <div class="carers-sub" id="carersSub"></div>
    <div id="carersList"></div>
  </div>
</div>

<script>
const carers = [
  {
    id:1, name:"Nipa Srisuk", age:34, avatar:"NS", avClass:"av1",
    photo:"https://randomuser.me/api/portraits/women/44.jpg",
    rating:4.9, reviews:128, location:"Bangkok, Thailand",
    skills:["Hospital escort","Medication reminders","Speaks Thai & English"],
    tags:["Medical assist","Cantonese","Gentle with dementia"],
    bio:"I'm a former nurse assistant with 6 years of experience caring for elderly patients in both hospital and home settings. I'm patient, attentive, and genuinely enjoy making seniors feel comfortable and heard.",
    bestAt:["Hospital escort","Medication reminders","Wheelchair assist","Speaks English & Thai","Post-surgery care"],
    experience:"6 years · Former nurse assistant at Bumrungrad Hospital",
    expRole:"Nurse Assistant → Private Carer",
    price:"$25/visit",
    reviewsList:[
      {name:"Somchai K.", stars:"★★★★★", date:"Feb 2026", text:"Nipa was incredibly kind with my mother. She kept detailed notes from the doctor and explained everything clearly to us after."},
      {name:"Lisa T.", stars:"★★★★★", date:"Jan 2026", text:"Very professional and warm. My dad actually looked forward to her visits!"}
    ]
  },
  {
    id:2, name:"Malee Wongsuk", age:29, avatar:"MW", avClass:"av2",
    photo:"https://randomuser.me/api/portraits/women/68.jpg",
    rating:4.8, reviews:94, location:"Bangkok, Thailand",
    skills:["Outings & activities","Dementia care","Cooking assist"],
    tags:["Senior outings","Dementia friendly","Active & cheerful"],
    bio:"I have a background in occupational therapy and love helping seniors stay active and socially connected. I plan fun, safe outings and always make sure everyone returns home with a smile.",
    bestAt:["Senior outings","Dementia support","Light exercise","Social activities","Meal preparation"],
    experience:"4 years · Occupational therapy background",
    expRole:"Occupational Therapy Aide → Senior Companion",
    price:"$18/trip",
    reviewsList:[
      {name:"Araya P.", stars:"★★★★★", date:"Feb 2026", text:"Malee took my grandmother to the temple and they had the best time. She sent photos and a little report — so thoughtful."},
      {name:"James W.", stars:"★★★★☆", date:"Dec 2025", text:"Great energy and very reliable. My mom was nervous at first but warmed up to Malee quickly."}
    ]
  },
  {
    id:3, name:"Kanya Thongdee", age:41, avatar:"KT", avClass:"av3",
    photo:"https://randomuser.me/api/portraits/women/26.jpg",
    rating:4.7, reviews:76, location:"Nonthaburi, Thailand",
    skills:["Home safety","Errand running","Companionship"],
    tags:["Home care","Trustworthy","Detail-oriented"],
    bio:"With over 8 years of home care experience, I specialise in keeping elderly homes safe and well-maintained. I'm thorough, reliable and treat every home like my own.",
    bestAt:["Home safety inspection","Grocery shopping","Light housekeeping","Companionship","Errands"],
    experience:"8 years · Home care specialist",
    expRole:"Home Care Worker → Senior Safety Specialist",
    price:"$20/check",
    reviewsList:[
      {name:"Priya N.", stars:"★★★★★", date:"Jan 2026", text:"Kanya found several hazards in my father's home that we had completely missed. So grateful for her thoroughness."},
      {name:"Tom S.", stars:"★★★★☆", date:"Nov 2025", text:"Very friendly and efficient. Done in an hour and gave us a clear checklist of everything she checked."}
    ]
  }
];

let currentService = {};
let carerFilter = 'all';

const carerCategories = {
  1: ['medical','social'],
  2: ['outing','social'],
  3: ['home','social']
};

function switchTab(tab, el){
  // update home nav
  document.querySelectorAll('#homeScreen .nav-item').forEach(i=>i.classList.remove('active'));
  document.querySelectorAll('#carersScreen .nav-item').forEach(i=>i.classList.remove('active'));
  if(el) el.classList.add('active');

  if(tab==='home'){
    document.getElementById('homeScreen').classList.add('active');
    document.getElementById('carersScreen').classList.remove('active');
  } else {
    document.getElementById('homeScreen').classList.remove('active');
    document.getElementById('carersScreen').classList.add('active');
    renderBrowseCarers(carers);
  }
}

function renderBrowseCarers(list){
  document.getElementById('carerCount').textContent = list.length;
  document.getElementById('carerBrowseList').innerHTML = list.map(c=>`
    <div class="browse-card">
      <div class="browse-top">
        <div class="browse-avatar ${c.avClass}" style="overflow:hidden;padding:0"><img src="${c.photo}" style="width:100%;height:100%;object-fit:cover;border-radius:16px" onerror="this.parentElement.innerHTML='${c.avatar}'"></div>
        <div class="browse-meta">
          <div class="browse-name">${c.name}</div>
          <div class="browse-role">${c.expRole}</div>
          <div class="browse-rating">
            <span class="browse-stars">★★★★★</span>
            <span class="browse-num">${c.rating}</span>
            <span class="browse-rev">(${c.reviews} reviews)</span>
          </div>
          <span class="browse-verified">✓ Verified</span>
        </div>
      </div>
      <div class="browse-bio">${c.bio.substring(0,100)}...</div>
      <div class="browse-skills">${c.tags.map(t=>`<span class="browse-skill">${t}</span>`).join('')}</div>
      <div class="browse-actions">
        <button class="btn-outline" onclick="openProfileFromBrowse(${c.id})">View Profile</button>
        <button class="btn-fill">Book Now</button>
      </div>
    </div>`).join('');
}

function filterCarers(val){
  const q = val.toLowerCase();
  const filtered = carers.filter(c=>
    c.name.toLowerCase().includes(q) ||
    c.tags.some(t=>t.toLowerCase().includes(q)) ||
    c.bestAt.some(t=>t.toLowerCase().includes(q))
  );
  renderBrowseCarers(filtered);
}

function filterCarerChip(el, cat){
  document.querySelectorAll('#carerChips .chip').forEach(c=>c.classList.remove('active'));
  el.classList.add('active');
  carerFilter = cat;
  const filtered = cat==='all' ? carers : carers.filter(c=>(carerCategories[c.id]||[]).includes(cat));
  renderBrowseCarers(filtered);
}

function openProfileFromBrowse(id){
  const c = carers.find(x=>x.id===id);
  document.getElementById('profileHeaderName').textContent=c.name;
  document.getElementById('profileContent').innerHTML = buildProfileHTML(c);
  document.getElementById('carersScreen').classList.remove('active');
  document.getElementById('profileScreen').classList.add('active');
  document.getElementById('profileScreen').scrollTop=0;
  // mark back origin
  document.getElementById('profileScreen').dataset.from='carers';
}

function filterChip(el){
  document.querySelectorAll('.chip').forEach(c=>c.classList.remove('active'));
  el.classList.add('active');
}

function addTap(e,btn){
  e.stopPropagation();
  btn.textContent='✓';btn.style.background='var(--green)';
  setTimeout(()=>{btn.textContent='+';btn.style.background='var(--accent)'},1500);
}

function openSheet(title,emoji,price,desc){
  currentService={title,emoji,price,desc};
  document.getElementById('sheetTitle').textContent=title;
  document.getElementById('sheetEmoji').textContent=emoji;
  document.getElementById('sheetPrice').textContent=price;
  document.getElementById('sheetDesc').textContent=desc;
  document.getElementById('carersSub').textContent=carers.length+' trusted carers available for '+title;
  document.getElementById('carersList').innerHTML=carers.map(c=>carerCard(c)).join('');
  document.getElementById('overlay').classList.add('show');
  document.getElementById('sheet').classList.add('open');
}

function closeSheet(){
  document.getElementById('overlay').classList.remove('show');
  document.getElementById('sheet').classList.remove('open');
}

function carerCard(c){
  const img = `<img src="${c.photo}" style="width:100%;height:100%;object-fit:cover;border-radius:50%" onerror="this.style.display='none'">`;
  return `<div class="carer-card">
    <div class="carer-top">
      <div class="carer-avatar ${c.avClass}" style="overflow:hidden;padding:0">${img}</div>
      <div class="carer-meta">
        <div class="carer-name">${c.name}</div>
        <div class="carer-age">Age ${c.age} · ${c.location}</div>
        <div class="carer-rating">
          <span class="stars">★★★★★</span>
          <span class="rating-num">${c.rating}</span>
          <span class="review-count">(${c.reviews} reviews)</span>
        </div>
      </div>
      <span class="verified">✓ Verified</span>
    </div>
    <div class="skill-tags">${c.tags.map(t=>`<span class="skill-tag">${t}</span>`).join('')}</div>
    <div class="carer-actions">
      <button class="btn-outline" onclick="openProfile(${c.id})">View Profile</button>
      <button class="btn-fill">Book Now</button>
    </div>
  </div>`;
}

function buildProfileHTML(c){
  return `
    <div class="profile-hero">
      <div class="profile-avatar ${c.avClass}" style="overflow:hidden;padding:0;width:100px;height:100px">
        <img src="${c.photo}" style="width:100%;height:100%;object-fit:cover;border-radius:50%" onerror="this.parentElement.innerHTML='${c.avatar}'">
      </div>
      <div class="profile-name">${c.name}</div>
      <div class="profile-location">📍 ${c.location} · Age ${c.age}</div>
      <div class="profile-rating-row">
        <span class="p-stars">★★★★★</span>
        <span class="p-rating">${c.rating}</span>
        <span class="p-reviews">(${c.reviews} reviews)</span>
      </div>
      <span class="p-verified">✓ Verified Carer</span>
    </div>
    <div class="profile-section">
      <div class="p-sec-title">About Me</div>
      <div class="p-bio">${c.bio}</div>
    </div>
    <div class="profile-section">
      <div class="p-sec-title">Best At</div>
      <div class="p-tags">${c.bestAt.map((t,i)=>`<span class="p-tag${i<2?' highlight':''}">${t}</span>`).join('')}</div>
    </div>
    <div class="profile-section">
      <div class="p-sec-title">Experience</div>
      <div class="exp-card">
        <div class="exp-icon">🏥</div>
        <div><div class="exp-title">${c.expRole}</div><div class="exp-sub">${c.experience}</div></div>
      </div>
    </div>
    <div class="profile-section">
      <div class="p-sec-title">Recent Reviews</div>
      ${c.reviewsList.map(r=>`
        <div class="review-card">
          <div class="review-top"><span class="reviewer-name">${r.name}</span><span class="review-date">${r.date}</span></div>
          <div class="review-stars">${r.stars}</div>
          <div class="review-text">${r.text}</div>
        </div>`).join('')}
    </div>
    <div class="profile-book-bar">
      <div><div class="book-price">${c.price} <span>/ session</span></div></div>
      <button class="book-btn">Book ${c.name.split(' ')[0]}</button>
    </div>`;
}

function openProfile(id){
  const c = carers.find(x=>x.id===id);
  document.getElementById('profileHeaderName').textContent=c.name;
  document.getElementById('profileContent').innerHTML=buildProfileHTML(c);
  closeSheet();
  document.getElementById('homeScreen').classList.remove('active');
  document.getElementById('profileScreen').classList.add('active');
  document.getElementById('profileScreen').dataset.from='sheet';
  document.getElementById('profileScreen').scrollTop=0;
}

function closeProfile(){
  const from = document.getElementById('profileScreen').dataset.from;
  document.getElementById('profileScreen').classList.remove('active');
  if(from==='carers'){
    document.getElementById('carersScreen').classList.add('active');
  } else {
    document.getElementById('homeScreen').classList.add('active');
    openSheet(currentService.title,currentService.emoji,currentService.price,currentService.desc);
  }
}
</script>
</body>
</html>
