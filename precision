<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>PrecisionFlow Markets | Professional Trading</title>
<link href="https://fonts.googleapis.com/css2?family=Bebas+Neue&family=DM+Sans:ital,wght@0,300;0,400;0,500;0,600;1,300&family=DM+Mono:wght@400;500&display=swap" rel="stylesheet">
<style>
*{margin:0;padding:0;box-sizing:border-box}
:root{
  --gold:#C9A84C;--gold-light:#E8C97A;--dark:#07090F;--dark2:#0C1018;
  --dark3:#111620;--dark4:#161C28;--accent:#1A6FFF;--green:#00C896;
  --red:#FF4757;--text:#E4EAF5;--muted:#5A6B82;--border:rgba(201,168,76,0.12);
}
html{scroll-behavior:smooth}
body{background:var(--dark);color:var(--text);font-family:'DM Sans',sans-serif;overflow-x:hidden}
::-webkit-scrollbar{width:4px}::-webkit-scrollbar-track{background:var(--dark)}::-webkit-scrollbar-thumb{background:var(--gold);border-radius:2px}
nav{position:fixed;top:0;left:0;right:0;z-index:500;padding:18px 5%;display:flex;align-items:center;justify-content:space-between;backdrop-filter:blur(24px);background:rgba(7,9,15,0.85);border-bottom:1px solid var(--border);transition:all 0.3s}
.logo{font-family:'Bebas Neue',sans-serif;font-size:26px;letter-spacing:4px;color:var(--gold);text-decoration:none}
.logo span{color:var(--text);opacity:0.5}
.nav-links{display:flex;gap:36px;list-style:none;align-items:center}
.nav-links a{color:var(--muted);text-decoration:none;font-size:13px;letter-spacing:1px;text-transform:uppercase;transition:color 0.3s;font-weight:500}
.nav-links a:hover{color:var(--gold)}
.nav-cta{background:var(--gold);color:var(--dark);padding:10px 22px;border-radius:3px;font-size:12px;font-weight:700;text-decoration:none;letter-spacing:2px;text-transform:uppercase;transition:all 0.3s}
.nav-cta:hover{background:var(--gold-light);transform:translateY(-1px);box-shadow:0 8px 24px rgba(201,168,76,0.3)}
.hamburger{display:none;flex-direction:column;gap:5px;cursor:pointer;background:none;border:none;padding:5px}
.hamburger span{width:24px;height:2px;background:var(--gold);display:block;transition:all 0.3s}
.mobile-menu{display:none;position:fixed;top:70px;left:0;right:0;background:rgba(7,9,15,0.98);backdrop-filter:blur(24px);padding:30px 5%;border-bottom:1px solid var(--border);z-index:499}
.mobile-menu.open{display:block}
.mobile-menu a{display:block;color:var(--muted);text-decoration:none;font-size:16px;padding:14px 0;border-bottom:1px solid rgba(255,255,255,0.05);text-transform:uppercase;letter-spacing:1px;transition:color 0.3s}
.mobile-menu a:hover{color:var(--gold)}
.hero{min-height:100vh;display:flex;align-items:center;padding:120px 5% 80px;position:relative;overflow:hidden}
.hero-bg{position:absolute;inset:0;background:radial-gradient(ellipse 70% 70% at 80% 50%,rgba(26,111,255,0.05) 0%,transparent 70%),radial-gradient(ellipse 50% 60% at 10% 80%,rgba(201,168,76,0.06) 0%,transparent 60%)}
.hero-grid{position:absolute;inset:0;background-image:linear-gradient(rgba(201,168,76,0.025) 1px,transparent 1px),linear-gradient(90deg,rgba(201,168,76,0.025) 1px,transparent 1px);background-size:80px 80px}
.hero-inner{position:relative;z-index:2;display:grid;grid-template-columns:1fr 1fr;gap:60px;align-items:center;width:100%;max-width:1400px;margin:0 auto}
.hero-tag{display:inline-flex;align-items:center;gap:10px;background:rgba(201,168,76,0.08);border:1px solid rgba(201,168,76,0.2);padding:8px 18px;border-radius:100px;font-size:11px;color:var(--gold);letter-spacing:2px;text-transform:uppercase;margin-bottom:28px;animation:fadeUp 0.8s ease both}
.live-dot{width:7px;height:7px;background:var(--green);border-radius:50%;animation:pulse 2s infinite}
@keyframes pulse{0%,100%{opacity:1;transform:scale(1)}50%{opacity:0.4;transform:scale(1.8)}}
.hero h1{font-family:'Bebas Neue',sans-serif;font-size:clamp(56px,8vw,110px);line-height:0.88;letter-spacing:1px;animation:fadeUp 0.8s 0.15s ease both}
.hero h1 .gold{color:var(--gold)}
.hero h1 .dim{opacity:0.2;-webkit-text-stroke:1px rgba(201,168,76,0.3);color:transparent}
.hero-sub{font-size:17px;color:var(--muted);line-height:1.8;margin:24px 0 40px;max-width:480px;animation:fadeUp 0.8s 0.3s ease both;font-weight:300}
.hero-btns{display:flex;gap:14px;flex-wrap:wrap;animation:fadeUp 0.8s 0.45s ease both}
.btn-primary{background:var(--gold);color:var(--dark);padding:14px 32px;border-radius:3px;font-size:13px;font-weight:700;text-decoration:none;letter-spacing:2px;text-transform:uppercase;transition:all 0.3s;border:none;cursor:pointer;display:inline-block}
.btn-primary:hover{background:var(--gold-light);transform:translateY(-2px);box-shadow:0 12px 30px rgba(201,168,76,0.35)}
.btn-outline{border:1px solid var(--border);color:var(--text);padding:14px 32px;border-radius:3px;font-size:13px;font-weight:500;text-decoration:none;letter-spacing:2px;text-transform:uppercase;transition:all 0.3s;display:inline-block}
.btn-outline:hover{border-color:var(--gold);color:var(--gold);transform:translateY(-2px)}
.hero-stats{display:flex;gap:32px;margin-top:52px;animation:fadeUp 0.8s 0.6s ease both}
.hero-stat-num{font-family:'Bebas Neue',sans-serif;font-size:42px;color:var(--gold);letter-spacing:2px;line-height:1}
.hero-stat-label{font-size:11px;color:var(--muted);text-transform:uppercase;letter-spacing:2px;margin-top:4px}
.hero-visual{position:relative;animation:fadeUp 0.8s 0.3s ease both}
.chart-card{background:var(--dark3);border:1px solid var(--border);border-radius:12px;padding:28px;position:relative;overflow:hidden}
.chart-card::before{content:'';position:absolute;top:0;left:0;right:0;height:1px;background:linear-gradient(90deg,transparent,var(--gold),transparent)}
.chart-header{display:flex;justify-content:space-between;align-items:center;margin-bottom:20px}
.chart-symbol{font-family:'Bebas Neue',sans-serif;font-size:22px;letter-spacing:2px}
.chart-price{font-family:'DM Mono',monospace;font-size:24px;color:var(--green);font-weight:500}
.chart-change{font-size:12px;color:var(--green);background:rgba(0,200,150,0.1);padding:4px 10px;border-radius:100px}
.chart-svg{width:100%;height:120px}
.trade-cards{display:grid;grid-template-columns:1fr 1fr;gap:12px;margin-top:16px}
.trade-card{background:var(--dark4);border:1px solid rgba(255,255,255,0.05);border-radius:8px;padding:14px}
.trade-card-top{display:flex;justify-content:space-between;align-items:center;margin-bottom:8px}
.trade-type{font-size:10px;letter-spacing:2px;text-transform:uppercase;font-weight:600}
.trade-type.buy{color:var(--green)}.trade-type.sell{color:var(--red)}
.trade-pair{font-size:12px;color:var(--muted)}
.trade-pnl{font-family:'DM Mono',monospace;font-size:15px;font-weight:500}
.trade-pnl.pos{color:var(--green)}.trade-pnl.neg{color:var(--red)}
.trade-pips{font-size:10px;color:var(--muted);margin-top:2px}
.floating-badge{position:absolute;top:-16px;right:20px;background:var(--dark3);border:1px solid var(--border);border-radius:8px;padding:12px 16px;display:flex;align-items:center;gap:10px;box-shadow:0 20px 40px rgba(0,0,0,0.5)}
.badge-text{font-size:11px;color:var(--muted);letter-spacing:1px}
.badge-val{font-size:16px;color:var(--gold);font-weight:600;font-family:'DM Mono',monospace}
@keyframes fadeUp{from{opacity:0;transform:translateY(30px)}to{opacity:1;transform:translateY(0)}}
.ticker{background:var(--dark2);border-top:1px solid var(--border);border-bottom:1px solid var(--border);padding:14px 0;overflow:hidden}
.ticker-track{display:flex;gap:60px;animation:ticker 30s linear infinite;width:max-content}
.ticker-item{display:flex;align-items:center;gap:10px;font-family:'DM Mono',monospace;font-size:13px;white-space:nowrap}
.ticker-sym{color:var(--gold);font-weight:500;letter-spacing:1px}
.ticker-chg.up{color:var(--green)}.ticker-chg.dn{color:var(--red)}
.ticker-dot{width:3px;height:3px;background:var(--border);border-radius:50%}
@keyframes ticker{from{transform:translateX(0)}to{transform:translateX(-50%)}}
section{padding:100px 5%}
.section-inner{max-width:1200px;margin:0 auto}
.section-tag{font-size:11px;letter-spacing:3px;text-transform:uppercase;color:var(--gold);margin-bottom:16px;display:flex;align-items:center;gap:10px}
.section-tag::before{content:'';width:30px;height:1px;background:var(--gold)}
.section-title{font-family:'Bebas Neue',sans-serif;font-size:clamp(40px,6vw,72px);letter-spacing:2px;line-height:1;margin-bottom:20px}
.section-sub{font-size:16px;color:var(--muted);max-width:500px;line-height:1.8;font-weight:300}
.about{background:var(--dark)}
.about-grid{display:grid;grid-template-columns:1fr 1fr;gap:80px;align-items:center;margin-top:60px}
.about-img{width:100%;border-radius:12px;background:linear-gradient(135deg,var(--dark3),var(--dark4));border:1px solid var(--border);aspect-ratio:4/5;display:flex;flex-direction:column;align-items:center;justify-content:center;gap:16px;position:relative;overflow:hidden}
.about-img-icon{font-size:80px;opacity:0.1}
.about-img-text{font-size:12px;color:var(--muted);letter-spacing:2px;text-transform:uppercase}
.about-img-note{font-size:11px;color:rgba(90,107,130,0.5);letter-spacing:1px}
.about-badge{position:absolute;bottom:24px;left:24px;background:rgba(7,9,15,0.9);backdrop-filter:blur(12px);border:1px solid var(--border);border-radius:8px;padding:16px 20px}
.about-badge-num{font-family:'Bebas Neue',sans-serif;font-size:36px;color:var(--gold);letter-spacing:2px;line-height:1}
.about-badge-text{font-size:11px;color:var(--muted);text-transform:uppercase;letter-spacing:2px;margin-top:4px}
.about-content p{font-size:16px;color:var(--muted);line-height:1.9;margin-bottom:20px;font-weight:300}
.about-content p strong{color:var(--text);font-weight:500}
.skills-grid{display:grid;grid-template-columns:1fr 1fr;gap:12px;margin-top:32px}
.skill-item{background:var(--dark3);border:1px solid var(--border);border-radius:8px;padding:16px;transition:all 0.3s}
.skill-item:hover{border-color:rgba(201,168,76,0.3);transform:translateY(-2px)}
.skill-name{font-size:13px;font-weight:600;margin-bottom:8px}
.skill-bar{height:3px;background:rgba(255,255,255,0.06);border-radius:2px;overflow:hidden}
.skill-fill{height:100%;border-radius:2px;background:linear-gradient(90deg,var(--gold),var(--gold-light))}
.markets{background:var(--dark2)}
.markets-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:20px;margin-top:60px}
.market-card{background:var(--dark3);border:1px solid var(--border);border-radius:12px;padding:32px;transition:all 0.4s;position:relative;overflow:hidden}
.market-card::before{content:'';position:absolute;top:0;left:0;right:0;height:2px;opacity:0;transition:opacity 0.3s}
.market-card.gold-card::before{background:linear-gradient(90deg,transparent,var(--gold),transparent)}
.market-card.nasdaq-card::before{background:linear-gradient(90deg,transparent,var(--accent),transparent)}
.market-card.v25-card::before{background:linear-gradient(90deg,transparent,var(--green),transparent)}
.market-card:hover::before{opacity:1}
.market-card:hover{transform:translateY(-6px);border-color:rgba(201,168,76,0.2);box-shadow:0 24px 50px rgba(0,0,0,0.4)}
.market-icon{font-size:36px;margin-bottom:20px}
.market-name{font-family:'Bebas Neue',sans-serif;font-size:28px;letter-spacing:2px;margin-bottom:8px}
.market-desc{font-size:14px;color:var(--muted);line-height:1.7;margin-bottom:24px;font-weight:300}
.market-stats{display:flex;gap:20px}
.mstat{border-left:2px solid var(--border);padding-left:12px}
.mstat-val{font-family:'DM Mono',monospace;font-size:16px;font-weight:500}
.mstat-val.gold{color:var(--gold)}.mstat-val.blue{color:var(--accent)}.mstat-val.green{color:var(--green)}
.mstat-label{font-size:10px;color:var(--muted);text-transform:uppercase;letter-spacing:1px;margin-top:2px}
.results{background:var(--dark)}
.results-grid{display:grid;grid-template-columns:repeat(4,1fr);gap:16px;margin-top:60px;margin-bottom:40px}
.result-card{background:var(--dark3);border:1px solid var(--border);border-radius:12px;padding:28px;text-align:center;transition:all 0.3s}
.result-card:hover{transform:translateY(-4px);border-color:rgba(201,168,76,0.25)}
.result-num{font-family:'Bebas Neue',sans-serif;font-size:52px;color:var(--gold);letter-spacing:3px;line-height:1}
.result-label{font-size:12px;color:var(--muted);text-transform:uppercase;letter-spacing:2px;margin-top:8px}
.results-table{background:var(--dark3);border:1px solid var(--border);border-radius:12px;overflow:hidden}
.table-header{display:grid;grid-template-columns:2fr 1fr 1fr 1fr 1fr;padding:16px 28px;background:var(--dark4);font-size:11px;color:var(--muted);text-transform:uppercase;letter-spacing:2px;border-bottom:1px solid var(--border)}
.table-row{display:grid;grid-template-columns:2fr 1fr 1fr 1fr 1fr;padding:18px 28px;border-bottom:1px solid rgba(255,255,255,0.04);font-size:14px;align-items:center;transition:background 0.2s}
.table-row:hover{background:rgba(201,168,76,0.03)}
.table-row:last-child{border-bottom:none}
.tr-market{font-weight:500;display:flex;align-items:center;gap:10px}
.tr-dot{width:8px;height:8px;border-radius:50%}
.tr-dot.gold{background:var(--gold)}.tr-dot.blue{background:var(--accent)}.tr-dot.green{background:var(--green)}
.tr-win{color:var(--green);font-family:'DM Mono',monospace}
.tr-pnl{font-family:'DM Mono',monospace;color:var(--green)}
.tr-trades{font-family:'DM Mono',monospace;color:var(--muted)}
.tr-streak{color:var(--gold);font-family:'DM Mono',monospace}
.bot{background:var(--dark2)}
.bot-grid{display:grid;grid-template-columns:1fr 1fr;gap:60px;align-items:start;margin-top:60px}
.bot-features{display:flex;flex-direction:column;gap:16px}
.bot-feature{background:var(--dark3);border:1px solid var(--border);border-radius:10px;padding:24px;display:flex;gap:16px;align-items:flex-start;transition:all 0.3s}
.bot-feature:hover{border-color:rgba(201,168,76,0.25);transform:translateX(4px)}
.bot-feature-icon{width:44px;height:44px;border-radius:8px;background:rgba(201,168,76,0.1);display:flex;align-items:center;justify-content:center;font-size:20px;flex-shrink:0}
.bot-feature-title{font-size:15px;font-weight:600;margin-bottom:6px}
.bot-feature-desc{font-size:13px;color:var(--muted);line-height:1.6;font-weight:300}
.bot-terminal{background:var(--dark);border:1px solid var(--border);border-radius:12px;overflow:hidden;font-family:'DM Mono',monospace}
.terminal-header{background:var(--dark3);padding:14px 20px;display:flex;align-items:center;gap:8px;border-bottom:1px solid var(--border)}
.terminal-dot{width:10px;height:10px;border-radius:50%}
.terminal-title{font-size:11px;color:var(--muted);letter-spacing:2px;margin-left:8px;text-transform:uppercase}
.terminal-body{padding:24px;font-size:13px;line-height:2}
.t-green{color:var(--green)}.t-gold{color:var(--gold)}.t-red{color:var(--red)}.t-muted{color:var(--muted)}.t-white{color:var(--text)}
.t-blink{animation:blink 1s infinite}
@keyframes blink{0%,100%{opacity:1}50%{opacity:0}}
.signals{background:var(--dark)}
.signals-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:20px;margin-top:60px}
.signal-card{background:var(--dark3);border:1px solid var(--border);border-radius:12px;padding:32px;transition:all 0.4s;position:relative;overflow:hidden}
.signal-card.featured{border-color:rgba(201,168,76,0.4);background:linear-gradient(135deg,var(--dark3),rgba(201,168,76,0.04))}
.signal-badge{position:absolute;top:20px;right:20px;background:var(--gold);color:var(--dark);font-size:10px;font-weight:700;letter-spacing:2px;padding:4px 12px;border-radius:100px;text-transform:uppercase}
.signal-plan{font-size:11px;letter-spacing:3px;text-transform:uppercase;color:var(--muted);margin-bottom:12px}
.signal-price{font-family:'Bebas Neue',sans-serif;font-size:56px;color:var(--gold);letter-spacing:2px;line-height:1}
.signal-price span{font-size:20px;color:var(--muted)}
.signal-desc{font-size:14px;color:var(--muted);margin:16px 0 24px;line-height:1.7;font-weight:300}
.signal-features{list-style:none;margin-bottom:32px}
.signal-features li{font-size:14px;padding:10px 0;border-bottom:1px solid rgba(255,255,255,0.04);display:flex;align-items:center;gap:10px;color:var(--muted)}
.signal-features li::before{content:'✓';color:var(--green);font-weight:700;font-size:12px}
.signal-features li.active{color:var(--text)}
.signal-features li.inactive::before{content:'✗';color:var(--muted)}
.testimonials{background:var(--dark2)}
.testi-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:20px;margin-top:60px}
.testi-card{background:var(--dark3);border:1px solid var(--border);border-radius:12px;padding:28px;transition:all 0.3s}
.testi-card:hover{transform:translateY(-4px);border-color:rgba(201,168,76,0.2)}
.testi-stars{color:var(--gold);font-size:14px;letter-spacing:2px;margin-bottom:16px}
.testi-text{font-size:15px;color:var(--muted);line-height:1.8;font-style:italic;font-weight:300;margin-bottom:20px}
.testi-author{display:flex;align-items:center;gap:12px}
.testi-avatar{width:42px;height:42px;border-radius:50%;background:linear-gradient(135deg,var(--gold),var(--accent));display:flex;align-items:center;justify-content:center;font-weight:700;font-size:16px;color:var(--dark);flex-shrink:0}
.testi-name{font-size:14px;font-weight:600}
.testi-role{font-size:12px;color:var(--muted)}
.contact{background:var(--dark)}
.contact-grid{display:grid;grid-template-columns:1fr 1fr;gap:80px;margin-top:60px;align-items:start}
.contact-info p{font-size:16px;color:var(--muted);line-height:1.8;font-weight:300;margin-bottom:40px}
.contact-links{display:flex;flex-direction:column;gap:16px}
.contact-link{display:flex;align-items:center;gap:16px;background:var(--dark3);border:1px solid var(--border);border-radius:10px;padding:18px 24px;text-decoration:none;transition:all 0.3s}
.contact-link:hover{border-color:rgba(201,168,76,0.3);transform:translateX(4px)}
.contact-link-icon{font-size:20px;width:40px;text-align:center}
.contact-link-text{font-size:14px;font-weight:500;color:var(--text)}
.contact-link-sub{font-size:12px;color:var(--muted);margin-top:2px}
.contact-form{background:var(--dark3);border:1px solid var(--border);border-radius:12px;padding:36px}
.contact-form h3{font-family:'Bebas Neue',sans-serif;font-size:28px;letter-spacing:2px;margin-bottom:24px}
.form-group{margin-bottom:16px}
.form-group label{font-size:12px;color:var(--muted);text-transform:uppercase;letter-spacing:2px;display:block;margin-bottom:8px}
.form-group input,.form-group select,.form-group textarea{width:100%;background:var(--dark4);border:1px solid var(--border);border-radius:6px;padding:14px 16px;color:var(--text);font-family:'DM Sans',sans-serif;font-size:14px;transition:border-color 0.3s;outline:none}
.form-group input:focus,.form-group select:focus,.form-group textarea:focus{border-color:rgba(201,168,76,0.4)}
.form-group textarea{height:120px;resize:none;font-weight:300}
.form-group select option{background:var(--dark3)}
.form-submit{width:100%;background:var(--gold);color:var(--dark);padding:14px;border:none;border-radius:6px;font-size:13px;font-weight:700;letter-spacing:2px;text-transform:uppercase;cursor:pointer;transition:all 0.3s}
.form-submit:hover{background:var(--gold-light);transform:translateY(-1px);box-shadow:0 8px 24px rgba(201,168,76,0.3)}
footer{background:var(--dark2);border-top:1px solid var(--border);padding:60px 5% 30px}
.footer-inner{max-width:1200px;margin:0 auto}
.footer-top{display:grid;grid-template-columns:2fr 1fr 1fr 1fr;gap:60px;margin-bottom:60px}
.footer-brand .logo{display:block;margin-bottom:16px;font-size:24px}
.footer-brand p{font-size:14px;color:var(--muted);line-height:1.8;font-weight:300;max-width:280px}
.footer-col h4{font-size:12px;letter-spacing:3px;text-transform:uppercase;color:var(--gold);margin-bottom:20px}
.footer-col ul{list-style:none}
.footer-col ul li{margin-bottom:10px}
.footer-col ul li a{color:var(--muted);text-decoration:none;font-size:14px;transition:color 0.3s}
.footer-col ul li a:hover{color:var(--gold)}
.footer-bottom{display:flex;justify-content:space-between;align-items:center;border-top:1px solid var(--border);padding-top:24px;font-size:13px;color:var(--muted)}
.fo
