<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=5.0, viewport-fit=cover">
<title>CATrend Analyzer – Cochran–Armitage Trend Test</title>
<meta name="description" content="Free online statistical analysis tool for Cochran-Armitage Trend Test. Analyze trends in proportions across ordered categories for clinical trials, epidemiology, and public health research.">
<meta name="robots" content="index, follow">
<link rel="canonical" href="https://catrendanalyzer.mudasiribrahim.com/">
<meta property="og:title" content="CATrend Analyzer – Cochran–Armitage Trend Test">
<meta property="og:description" content="Free, open-source web tool for Cochran-Armitage Trend Test analysis.">
<meta property="og:type" content="website">
<meta property="og:url" content="https://catrendanalyzer.mudasiribrahim.com/">
<script type="application/ld+json">
{"@context":"https://schema.org","@type":"SoftwareApplication","name":"CATrend Analyzer","url":"https://catrendanalyzer.mudasiribrahim.com/","applicationCategory":"StatisticalAnalysisApplication","operatingSystem":"Web","offers":{"@type":"Offer","price":"0","priceCurrency":"USD"},"author":{"@type":"Person","name":"Mudasir Mohammed Ibrahim"}}
</script>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
<link href="https://fonts.googleapis.com/css2?family=Source+Serif+4:ital,wght@0,300;0,400;0,600;0,700;1,400;1,600&family=IBM+Plex+Mono:wght@400;500;600;700&family=Nunito+Sans:wght@400;500;600;700;800;900&display=swap" rel="stylesheet">
<script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
<script src="https://cdn.jsdelivr.net/npm/chartjs-plugin-datalabels@2.0.0"></script>

<style>
/* =====================================================
   DESIGN TOKENS
===================================================== */
:root {
  --sidebar-bg:     #0d1117;
  --sidebar-border: #30363d;
  --sidebar-hover:  #161b22;
  --sidebar-active: #1f2937;

  --bg:          #f0f4f8;
  --surface:     #ffffff;
  --surface-2:   #f4f7fb;
  --surface-3:   #e8edf5;

  --border:      #c8d0db;
  --border-med:  #a0adb9;
  --border-focus:#0969da;

  --brand:       #0757ba;
  --brand-dark:  #054699;
  --brand-light: #3d8ef0;
  --brand-bg:    rgba(7,87,186,0.07);
  --brand-glow:  rgba(7,87,186,0.18);

  --teal:        #0a6680;
  --teal-bg:     rgba(10,102,128,0.07);
  --teal-border: rgba(10,102,128,0.3);

  --emerald:     #166534;
  --emerald-bg:  rgba(22,101,52,0.07);
  --emerald-border:rgba(22,101,52,0.3);

  --amber:       #854d0e;
  --amber-bg:    rgba(133,77,14,0.07);
  --amber-border:rgba(133,77,14,0.3);

  --rose:        #9f1239;
  --rose-bg:     rgba(159,18,57,0.07);
  --rose-border: rgba(159,18,57,0.3);

  --violet:      #4c1d95;
  --violet-bg:   rgba(76,29,149,0.07);

  /* Text — bold and clear */
  --text-1:      #0a0f1e;
  --text-2:      #1a2233;
  --text-3:      #374151;
  --text-4:      #4b5563;
  --text-inv:    #f0f6fc;

  /* Sidebar text */
  --st-1:        #f0f6fc;
  --st-2:        #d0dae8;
  --st-3:        #9aafc4;
  --st-4:        #6e7e94;

  --font-ui:     'Nunito Sans', system-ui, sans-serif;
  --font-serif:  'Source Serif 4', Georgia, 'Times New Roman', serif;
  --font-mono:   'IBM Plex Mono', 'Courier New', monospace;

  --r-xs: 4px;
  --r-sm: 6px;
  --r-md: 8px;
  --r-lg: 12px;
  --r-xl: 16px;

  --s-sm:  0 1px 4px rgba(10,15,30,0.08), 0 1px 2px rgba(10,15,30,0.05);
  --s-md:  0 4px 16px rgba(10,15,30,0.12), 0 2px 6px rgba(10,15,30,0.07);
  --s-lg:  0 12px 36px rgba(10,15,30,0.16), 0 4px 12px rgba(10,15,30,0.09);
  --s-xl:  0 24px 64px rgba(10,15,30,0.22), 0 8px 24px rgba(10,15,30,0.12);

  /* Card hover shadows */
  --s-hover-brand:  0 8px 28px rgba(7,87,186,0.22), 0 2px 8px rgba(7,87,186,0.12);
  --s-hover-teal:   0 8px 28px rgba(10,102,128,0.22), 0 2px 8px rgba(10,102,128,0.12);
  --s-hover-green:  0 8px 28px rgba(22,101,52,0.22), 0 2px 8px rgba(22,101,52,0.12);
  --s-hover-rose:   0 8px 28px rgba(159,18,57,0.22), 0 2px 8px rgba(159,18,57,0.12);
}

[data-theme="dark"] {
  --bg:          #0d1117;
  --surface:     #161b22;
  --surface-2:   #1c2128;
  --surface-3:   #21262d;
  --border:      #30363d;
  --border-med:  #484f58;
  --border-focus:#58a6ff;
  --brand:       #4d9eff;
  --brand-dark:  #3d8ef0;
  --brand-light: #79c0ff;
  --brand-bg:    rgba(77,158,255,0.10);
  --brand-glow:  rgba(77,158,255,0.20);
  --teal:        #22d3ee;
  --teal-bg:     rgba(34,211,238,0.09);
  --teal-border: rgba(34,211,238,0.28);
  --emerald:     #4ade80;
  --emerald-bg:  rgba(74,222,128,0.09);
  --emerald-border:rgba(74,222,128,0.28);
  --amber:       #fbbf24;
  --amber-bg:    rgba(251,191,36,0.09);
  --amber-border:rgba(251,191,36,0.28);
  --rose:        #fb7185;
  --rose-bg:     rgba(251,113,133,0.09);
  --rose-border: rgba(251,113,133,0.28);
  --violet:      #c084fc;
  --violet-bg:   rgba(192,132,252,0.09);
  --text-1:      #f0f6fc;
  --text-2:      #dde6f0;
  --text-3:      #b0bec8;
  --text-4:      #8b949e;
  --s-sm:  0 1px 4px rgba(0,0,0,0.5);
  --s-md:  0 4px 16px rgba(0,0,0,0.55);
  --s-lg:  0 12px 36px rgba(0,0,0,0.65);
  --s-xl:  0 24px 64px rgba(0,0,0,0.75);
  --s-hover-brand:  0 8px 28px rgba(77,158,255,0.28), 0 2px 8px rgba(77,158,255,0.14);
}

/* =====================================================
   RESET & BASE
===================================================== */
*, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }
html { font-size: 15px; scroll-behavior: smooth; }
body {
  font-family: var(--font-ui);
  background: var(--bg);
  color: var(--text-1);
  min-height: 100vh;
  display: flex;
  line-height: 1.6;
  -webkit-font-smoothing: antialiased;
}
a { color: var(--brand); text-decoration: none; }
a:hover { text-decoration: underline; }

/* =====================================================
   SIDEBAR
===================================================== */
.sidebar {
  width: 264px;
  min-width: 264px;
  background: var(--sidebar-bg);
  border-right: 1px solid var(--sidebar-border);
  display: flex;
  flex-direction: column;
  position: fixed;
  top: 0; left: 0;
  height: 100vh;
  z-index: 200;
  transition: transform 0.28s cubic-bezier(0.4,0,0.2,1);
}

.sidebar-logo {
  padding: 20px 18px 18px;
  border-bottom: 1px solid var(--sidebar-border);
}

.logo-mark {
  display: flex;
  align-items: center;
  gap: 12px;
  cursor: pointer;
  text-decoration: none;
}

.logo-icon-wrap {
  width: 40px; height: 40px;
  border-radius: var(--r-md);
  background: linear-gradient(135deg, #0757ba, #0a6680);
  display: flex; align-items: center; justify-content: center;
  flex-shrink: 0;
  box-shadow: 0 0 0 1px rgba(255,255,255,0.12), 0 4px 14px rgba(7,87,186,0.4);
}
.logo-icon-wrap i { color: #fff; font-size: 1rem; }

.logo-text { display: flex; flex-direction: column; }
.logo-name { font-size: 1.08rem; font-weight: 900; color: #f0f6fc; line-height: 1.2; letter-spacing: -0.01em; font-family: var(--font-ui); }
.logo-sub { font-size: 0.67rem; color: var(--st-3); text-transform: uppercase; letter-spacing: 0.12em; font-weight: 700; margin-top: 2px; }

.sidebar-nav { flex: 1; padding: 14px 10px; overflow-y: auto; }

.nav-section {
  font-size: 0.63rem;
  font-weight: 800;
  letter-spacing: 0.14em;
  text-transform: uppercase;
  color: var(--st-4);
  padding: 16px 10px 7px;
}

.nav-item {
  display: flex;
  align-items: center;
  gap: 9px;
  padding: 10px 13px;
  border-radius: var(--r-sm);
  cursor: pointer;
  font-size: 0.9rem;
  font-weight: 700;
  color: var(--st-2);
  transition: all 0.15s;
  border: 1px solid transparent;
  text-decoration: none;
  margin-bottom: 2px;
}
.nav-item:hover { background: var(--sidebar-hover); color: #f0f6fc; text-decoration: none; border-color: var(--sidebar-border); }
.nav-item.active { background: var(--brand); color: #fff; border-color: rgba(255,255,255,0.12); box-shadow: 0 2px 10px rgba(7,87,186,0.4); }
.nav-item.active:hover { background: var(--brand-dark); }
.nav-item i { width: 16px; text-align: center; font-size: 0.84rem; }

.sidebar-footer {
  padding: 14px 16px;
  border-top: 1px solid var(--sidebar-border);
}
.theme-row { display: flex; align-items: center; justify-content: space-between; margin-bottom: 10px; }
.theme-label { font-size: 0.8rem; color: var(--st-3); font-weight: 700; }
.theme-btn {
  display: flex; align-items: center; gap: 6px;
  background: var(--sidebar-hover);
  border: 1px solid var(--sidebar-border);
  color: var(--st-2);
  border-radius: var(--r-sm);
  padding: 6px 13px;
  font-size: 0.79rem; font-family: var(--font-ui); font-weight: 700;
  cursor: pointer; transition: all 0.15s;
}
.theme-btn:hover { background: #21262d; color: #f0f6fc; border-color: #484f58; }
.ver-badge {
  font-size: 0.69rem; font-family: var(--font-mono); font-weight: 600;
  color: var(--st-4); text-align: center;
  background: rgba(255,255,255,0.04);
  border: 1px solid var(--sidebar-border);
  border-radius: var(--r-xs); padding: 6px 10px;
  letter-spacing: 0.05em;
}

/* =====================================================
   MAIN LAYOUT
===================================================== */
.main { margin-left: 264px; flex: 1; display: flex; flex-direction: column; min-height: 100vh; }

.topbar {
  height: 60px;
  background: var(--surface);
  border-bottom: 2px solid var(--border);
  display: flex; align-items: center; justify-content: space-between;
  padding: 0 34px;
  position: sticky; top: 0; z-index: 100;
  box-shadow: 0 2px 8px rgba(10,15,30,0.08);
}

.topbar-left { display: flex; align-items: center; gap: 10px; }
.hamburger { display: none; background: transparent; border: 1px solid var(--border); color: var(--text-2); border-radius: var(--r-sm); width: 36px; height: 36px; align-items: center; justify-content: center; cursor: pointer; font-size: 0.9rem; }

.breadcrumb {
  font-family: var(--font-ui);
  font-size: 0.9rem; font-weight: 700; color: var(--text-3);
  display: flex; align-items: center; gap: 7px;
}
.breadcrumb .sep { color: var(--border-med); font-weight: 400; }
.breadcrumb .current { color: var(--text-1); font-weight: 800; }

.topbar-right { display: flex; align-items: center; gap: 9px; }
.tb-ghost {
  background: var(--surface-2); border: 1px solid var(--border);
  color: var(--text-2); border-radius: var(--r-sm);
  padding: 8px 16px; font-size: 0.85rem; font-family: var(--font-ui);
  font-weight: 700; cursor: pointer; transition: all 0.18s;
  display: flex; align-items: center; gap: 7px; text-decoration: none;
}
.tb-ghost:hover { background: var(--surface-3); color: var(--text-1); border-color: var(--border-med); text-decoration: none; box-shadow: var(--s-sm); }
.tb-primary {
  background: var(--brand); color: #fff; border: 1px solid var(--brand-dark);
  border-radius: var(--r-sm); padding: 8px 18px;
  font-size: 0.85rem; font-family: var(--font-ui); font-weight: 800;
  cursor: pointer; transition: all 0.18s;
  display: flex; align-items: center; gap: 7px;
  box-shadow: 0 2px 10px rgba(7,87,186,0.30);
}
.tb-primary:hover { background: var(--brand-dark); transform: translateY(-1px); box-shadow: 0 4px 18px rgba(7,87,186,0.4); }

/* =====================================================
   PAGE SECTIONS
===================================================== */
.page-section { display: none; }
.page-section.active { display: block; }
.content { padding: 36px 36px 72px; max-width: 1100px; }

/* =====================================================
   HOME — HERO
===================================================== */
.hero { padding: 48px 36px 0; max-width: 1100px; }

.hero-badge {
  display: inline-flex; align-items: center; gap: 8px;
  font-size: 0.73rem; font-weight: 900; letter-spacing: 0.14em;
  text-transform: uppercase; color: var(--brand);
  background: var(--brand-bg); border: 1.5px solid rgba(7,87,186,0.22);
  border-radius: 99px; padding: 6px 16px; margin-bottom: 22px;
}
.hero-badge .dot { width: 7px; height: 7px; border-radius: 50%; background: var(--brand); animation: pulse-dot 2s ease-in-out infinite; }
@keyframes pulse-dot { 0%,100%{opacity:1} 50%{opacity:0.35} }

.hero-headline {
  font-family: var(--font-serif);
  font-size: 3.1rem;
  font-weight: 700;
  line-height: 1.1;
  color: var(--text-1);
  letter-spacing: -0.025em;
  margin-bottom: 20px;
  max-width: 720px;
}
.hero-headline em { font-style: italic; color: var(--brand); }

.hero-sub {
  font-size: 1.05rem; font-weight: 500;
  color: var(--text-3); max-width: 600px;
  line-height: 1.8; margin-bottom: 36px;
  font-family: var(--font-serif);
}

.cta-row { display: flex; gap: 13px; margin-bottom: 52px; flex-wrap: wrap; }
.btn-primary {
  background: var(--brand); color: #fff;
  border: none; border-radius: var(--r-md);
  padding: 13px 28px; font-family: var(--font-ui);
  font-size: 0.96rem; font-weight: 800; cursor: pointer;
  transition: all 0.22s; display: inline-flex; align-items: center; gap: 9px;
  box-shadow: 0 3px 16px rgba(7,87,186,0.34);
}
.btn-primary:hover { background: var(--brand-dark); transform: translateY(-2px); box-shadow: 0 7px 24px rgba(7,87,186,0.46); }
.btn-outline {
  background: var(--surface); color: var(--text-2);
  border: 2px solid var(--border-med); border-radius: var(--r-md);
  padding: 13px 28px; font-family: var(--font-ui);
  font-size: 0.96rem; font-weight: 700; cursor: pointer;
  transition: all 0.22s; display: inline-flex; align-items: center; gap: 9px;
}
.btn-outline:hover { border-color: var(--brand); color: var(--brand); background: var(--brand-bg); transform: translateY(-1px); }

/* Stats strip */
.stats-strip {
  display: grid; grid-template-columns: repeat(4,1fr);
  border: 1.5px solid var(--border); border-radius: var(--r-xl);
  background: var(--surface); margin-bottom: 48px;
  box-shadow: var(--s-md); overflow: hidden;
}
.stat-cell { padding: 22px 24px; border-right: 1px solid var(--border); transition: background 0.2s; }
.stat-cell:last-child { border-right: none; }
.stat-cell:hover { background: var(--surface-2); }
.stat-num { font-family: var(--font-serif); font-size: 1.65rem; font-weight: 700; color: var(--text-1); line-height: 1.2; }
.stat-desc { font-size: 0.78rem; color: var(--text-3); margin-top: 3px; font-weight: 700; letter-spacing: 0.03em; }

/* Demo card */
.demo-card {
  background: var(--surface); border: 1.5px solid var(--border);
  border-radius: var(--r-xl); padding: 32px;
  margin-bottom: 48px; position: relative; overflow: hidden;
  box-shadow: var(--s-md);
  transition: box-shadow 0.25s, transform 0.25s, border-color 0.25s;
}
.demo-card::before {
  content: ''; position: absolute; top: 0; left: 0; right: 0; height: 4px;
  background: linear-gradient(90deg, #0757ba, #0a6680, #166534);
}
.demo-card:hover {
  box-shadow: var(--s-lg);
  transform: translateY(-2px);
  border-color: var(--brand);
}
.demo-header { display: flex; align-items: flex-start; justify-content: space-between; margin-bottom: 30px; gap: 12px; }
.demo-title { font-family: var(--font-serif); font-size: 1.15rem; font-weight: 700; color: var(--text-1); }
.demo-subtitle { font-size: 0.86rem; color: var(--text-3); margin-top: 4px; font-weight: 500; font-family: var(--font-serif); font-style: italic; }
.demo-badge {
  background: var(--teal-bg); color: var(--teal);
  border: 1.5px solid var(--teal-border); border-radius: 99px;
  font-size: 0.69rem; font-weight: 900; padding: 5px 14px;
  letter-spacing: 0.12em; white-space: nowrap; flex-shrink: 0;
}
.sparkline-wrap { display: grid; grid-template-columns: 1fr 1fr; gap: 24px; margin-bottom: 24px; }
.mini-chart-area {
  background: var(--surface-2); border: 1.5px solid var(--border);
  border-radius: var(--r-lg); padding: 20px; min-height: 185px;
}
.mini-chart-label { font-size: 0.71rem; color: var(--text-3); font-weight: 800; letter-spacing: 0.09em; text-transform: uppercase; margin-bottom: 16px; }
.trend-bars { display: flex; align-items: flex-end; gap: 9px; height: 108px; }
.trend-bar-group { flex: 1; display: flex; flex-direction: column; align-items: center; gap: 4px; height: 100%; justify-content: flex-end; }
.trend-bar { width: 100%; border-radius: 3px 3px 0 0; transition: height 1s cubic-bezier(0.34,1.56,0.64,1); }
.trend-bar.s { background: linear-gradient(180deg, #0757ba, rgba(7,87,186,0.35)); }
.trend-bar.f { background: linear-gradient(180deg, #9f1239, rgba(159,18,57,0.28)); }
.trend-bar-lbl { font-size: 0.6rem; color: var(--text-4); text-align: center; white-space: nowrap; overflow: hidden; text-overflow: ellipsis; max-width: 100%; font-weight: 700; }

/* Preview table */
.preview-tbl { width: 100%; border-collapse: collapse; font-size: 0.83rem; }
.preview-tbl th { background: var(--surface-3); color: var(--text-2); font-weight: 800; font-size: 0.7rem; letter-spacing: 0.07em; text-transform: uppercase; padding: 9px 12px; text-align: center; border-bottom: 2px solid var(--border-med); border: 1px solid var(--border); }
.preview-tbl td { padding: 8px 12px; text-align: center; border: 1px solid var(--border); color: var(--text-1); font-family: var(--font-mono); font-size: 0.83rem; font-weight: 600; }
.preview-tbl .row-hdr { text-align: left; font-family: var(--font-ui); color: var(--text-1); font-size: 0.83rem; font-weight: 800; }
.preview-tbl .total-row td { background: var(--brand-bg); color: var(--brand); font-weight: 800; }

.demo-stats-row { display: grid; grid-template-columns: repeat(4,1fr); gap: 13px; }
.demo-stat { background: var(--surface-2); border: 1.5px solid var(--border); border-radius: var(--r-md); padding: 17px; text-align: center; transition: border-color 0.2s, box-shadow 0.2s, transform 0.2s; }
.demo-stat:hover { border-color: var(--brand); box-shadow: 0 4px 16px rgba(7,87,186,0.15); transform: translateY(-2px); }
.demo-stat-val { font-family: var(--font-mono); font-size: 1.22rem; font-weight: 700; color: var(--brand); margin-bottom: 6px; }
.demo-stat-val.pos { color: var(--emerald); }
.demo-stat-val.neu { color: var(--text-1); }
.demo-stat-lbl { font-size: 0.73rem; color: var(--text-3); font-weight: 700; letter-spacing: 0.03em; }

/* Panel */
.panel {
  background: var(--surface); border: 1.5px solid var(--border);
  border-radius: var(--r-xl); margin-bottom: 22px; overflow: hidden;
  box-shadow: var(--s-sm);
  transition: box-shadow 0.25s, transform 0.25s, border-color 0.25s;
}
.panel:hover { box-shadow: var(--s-md); }
.panel-header { padding: 17px 26px; border-bottom: 1.5px solid var(--border); display: flex; align-items: center; justify-content: space-between; background: var(--surface-2); }
.panel-title { font-size: 0.95rem; font-weight: 800; color: var(--text-1); display: flex; align-items: center; gap: 10px; }
.panel-title i { color: var(--brand); font-size: 0.87rem; }
.panel-body { padding: 26px; }

/* Section header */
.section-header { padding: 38px 36px 0; max-width: 1100px; margin-bottom: 30px; }
.section-title { font-family: var(--font-serif); font-size: 2.2rem; font-weight: 700; color: var(--text-1); letter-spacing: -0.025em; margin-bottom: 8px; }
.section-desc { font-family: var(--font-serif); font-size: 1rem; font-weight: 500; color: var(--text-3); font-style: italic; max-width: 600px; line-height: 1.75; }

/* Feature cards */
.feature-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(260px,1fr)); gap: 18px; }
.feature-card {
  padding: 22px; background: var(--surface-2); border: 1.5px solid var(--border);
  border-radius: var(--r-lg);
  transition: border-color 0.22s, box-shadow 0.22s, transform 0.22s, background 0.22s;
  cursor: default; position: relative; overflow: hidden;
}
.feature-card::after {
  content: ''; position: absolute; inset: 0; opacity: 0;
  background: linear-gradient(135deg, rgba(7,87,186,0.04), transparent);
  transition: opacity 0.22s;
  border-radius: var(--r-lg);
  pointer-events: none;
}
.feature-card:hover { border-color: var(--brand); box-shadow: var(--s-hover-brand); transform: translateY(-4px); background: var(--surface); }
.feature-card:hover::after { opacity: 1; }
.feature-icon { font-size: 1.5rem; margin-bottom: 12px; }
.feature-title { font-weight: 800; font-size: 0.96rem; color: var(--text-1); margin-bottom: 8px; }
.feature-desc { font-family: var(--font-serif); font-size: 0.87rem; color: var(--text-3); line-height: 1.65; font-weight: 400; }

/* =====================================================
   ANALYSIS SECTION
===================================================== */
.ctrl-bar { display: flex; align-items: center; gap: 9px; flex-wrap: wrap; margin-bottom: 20px; }
.ctrl-group { display: flex; align-items: center; gap: 5px; background: var(--surface-2); border: 1.5px solid var(--border); border-radius: var(--r-md); padding: 7px; }
.ctrl-lbl { font-size: 0.7rem; color: var(--text-3); font-weight: 800; letter-spacing: 0.09em; text-transform: uppercase; padding: 0 7px; }
.ctrl-btn { background: var(--surface); border: 1px solid var(--border); color: var(--text-3); border-radius: var(--r-xs); width: 32px; height: 32px; cursor: pointer; display: flex; align-items: center; justify-content: center; font-size: 0.76rem; transition: all 0.15s; font-weight: 800; }
.ctrl-btn:hover { background: var(--surface-3); color: var(--text-1); }
.ctrl-btn.add:hover { background: var(--emerald-bg); color: var(--emerald); border-color: var(--emerald-border); }
.ctrl-btn.rem:hover { background: var(--rose-bg); color: var(--rose); border-color: var(--rose-border); }

/* Data Table */
.tbl-wrap { overflow-x: auto; }
.data-tbl { width: 100%; border-collapse: collapse; min-width: 480px; font-size: 0.9rem; }
.data-tbl th { background: var(--surface-3); color: var(--text-2); font-size: 0.72rem; font-weight: 800; letter-spacing: 0.08em; text-transform: uppercase; padding: 12px 13px; text-align: center; border: 1px solid var(--border-med); }
.data-tbl th:first-child { text-align: left; border-left: none; }
.data-tbl td { padding: 8px 9px; border: 1px solid var(--border); text-align: center; vertical-align: middle; }
.data-tbl td:first-child { border-left: none; }
.data-tbl tr:last-child td { border-bottom: none; }
.data-tbl .row-hdr-cell { font-size: 0.89rem; color: var(--text-1); font-weight: 800; text-align: left; padding-left: 0; }
.data-tbl .total-cell { background: var(--surface-2); color: var(--text-1); font-family: var(--font-mono); font-size: 0.86rem; font-weight: 700; }
.data-tbl .grand-total { color: var(--brand); font-weight: 800; }
.data-tbl input[type="number"] {
  width: 100%; min-width: 64px;
  background: var(--surface); border: 1.5px solid var(--border);
  border-radius: var(--r-xs); padding: 8px 9px;
  font-family: var(--font-mono); font-size: 0.9rem; font-weight: 600;
  color: var(--text-1); text-align: center; outline: none;
  transition: border-color 0.15s, box-shadow 0.15s;
}
.data-tbl input[type="number"]:focus { border-color: var(--brand); box-shadow: 0 0 0 3px var(--brand-glow); }
.data-tbl input::-webkit-inner-spin-button, .data-tbl input::-webkit-outer-spin-button { opacity: 0; }
.hdr-input { background: transparent; border: none; border-bottom: 2px solid transparent; color: var(--text-2); font-size: 0.72rem; font-weight: 800; letter-spacing: 0.08em; text-transform: uppercase; text-align: center; font-family: var(--font-ui); width: 100%; outline: none; padding: 3px 4px; transition: all 0.15s; }
.hdr-input:focus { border-bottom-color: var(--brand); color: var(--text-1); }
.row-hdr-input { background: transparent; border: none; border-bottom: 2px solid transparent; color: var(--text-1); font-size: 0.9rem; font-weight: 800; font-family: var(--font-ui); width: 100%; outline: none; padding: 3px 0; transition: all 0.15s; }
.row-hdr-input:focus { border-bottom-color: var(--brand); }

/* Form */
.form-row { display: grid; grid-template-columns: 1fr 1fr; gap: 20px; margin-bottom: 22px; }
.checkbox-item { display: flex; align-items: center; gap: 10px; cursor: pointer; font-size: 0.9rem; font-weight: 700; color: var(--text-2); padding: 10px 13px; border-radius: var(--r-md); border: 1.5px solid transparent; transition: all 0.18s; margin-bottom: 4px; }
.checkbox-item:hover { background: var(--surface-2); border-color: var(--border); }
.checkbox-item input[type="checkbox"] { width: 16px; height: 16px; accent-color: var(--brand); cursor: pointer; }

/* Formula box */
.formula-box { background: var(--brand-bg); border: 1.5px solid rgba(7,87,186,0.22); border-radius: var(--r-lg); padding: 16px 24px; font-family: var(--font-mono); font-size: 0.97rem; font-weight: 700; color: var(--brand); text-align: center; margin: 18px 0; letter-spacing: 0.01em; }

/* Run button */
.run-section { text-align: center; padding: 30px; border-top: 1.5px solid var(--border); background: var(--surface-2); }
.run-btn {
  background: var(--brand); color: #fff; border: none; border-radius: var(--r-lg);
  padding: 16px 56px; font-family: var(--font-ui); font-size: 1rem; font-weight: 800;
  cursor: pointer; transition: all 0.24s; display: inline-flex; align-items: center; gap: 11px;
  box-shadow: 0 3px 18px rgba(7,87,186,0.36); position: relative; overflow: hidden;
}
.run-btn::after { content: ''; position: absolute; top: 0; left: -100%; width: 100%; height: 100%; background: linear-gradient(90deg, transparent, rgba(255,255,255,0.14), transparent); transition: left 0.5s; }
.run-btn:hover { background: var(--brand-dark); transform: translateY(-2px); box-shadow: 0 7px 30px rgba(7,87,186,0.5); }
.run-btn:hover::after { left: 100%; }
.warn-msg { display: none; align-items: center; gap: 9px; background: var(--amber-bg); border: 1.5px solid var(--amber-border); border-radius: var(--r-md); padding: 11px 17px; font-size: 0.88rem; font-weight: 700; color: var(--amber); margin-top: 16px; max-width: 500px; margin-left: auto; margin-right: auto; }

/* Alert strips */
.alert-strip { border-radius: var(--r-md); padding: 13px 17px; margin: 15px 0; font-size: 0.88rem; font-weight: 700; display: flex; align-items: flex-start; gap: 11px; border: 1.5px solid; }
.alert-info { background: var(--brand-bg); border-color: rgba(7,87,186,0.22); color: var(--text-2); }
.alert-info i { color: var(--brand); margin-top: 1px; }
.alert-warn { background: var(--amber-bg); border-color: var(--amber-border); color: var(--text-2); }
.alert-warn i { color: var(--amber); margin-top: 1px; }

/* =====================================================
   RESULTS
===================================================== */
.results-section { display: none; }
.results-section.active { display: block; animation: fadeUp 0.4s ease; }
@keyframes fadeUp { from{opacity:0;transform:translateY(20px)} to{opacity:1;transform:translateY(0)} }

/* Result chips */
.result-chips { display: grid; grid-template-columns: repeat(auto-fit, minmax(175px,1fr)); gap: 15px; margin-bottom: 22px; }
.chip {
  background: var(--surface); border: 1.5px solid var(--border);
  border-radius: var(--r-lg); padding: 20px 22px;
  position: relative; overflow: hidden; box-shadow: var(--s-sm);
  transition: box-shadow 0.22s, transform 0.22s, border-color 0.22s;
  cursor: default;
}
.chip:hover { box-shadow: var(--s-md); transform: translateY(-3px); }
.chip::before { content:''; position:absolute; top:0; left:0; width:4px; height:100%; border-radius:var(--r-lg) 0 0 var(--r-lg); }
.chip.c-brand::before { background: var(--brand); }
.chip.c-brand:hover { border-color: var(--brand); box-shadow: var(--s-hover-brand); }
.chip.c-teal::before { background: var(--teal); }
.chip.c-teal:hover { border-color: var(--teal); box-shadow: var(--s-hover-teal); }
.chip.c-amber::before { background: var(--amber); }
.chip.c-violet::before { background: var(--violet); }
.chip.c-green::before { background: var(--emerald); }
.chip.c-green:hover { border-color: var(--emerald); box-shadow: var(--s-hover-green); }
.chip.c-rose::before { background: var(--rose); }
.chip.c-rose:hover { border-color: var(--rose); box-shadow: var(--s-hover-rose); }

.chip-lbl { font-size: 0.7rem; font-weight: 800; letter-spacing: 0.1em; text-transform: uppercase; color: var(--text-4); margin-bottom: 9px; }
.chip-val { font-family: var(--font-mono); font-size: 1.5rem; font-weight: 700; color: var(--text-1); line-height: 1.2; }
.chip-val.v-brand { color: var(--brand); }
.chip-val.v-teal  { color: var(--teal); }
.chip-val.v-amber { color: var(--amber); }
.chip-val.v-violet{ color: var(--violet); }
.chip-val.v-green { color: var(--emerald); }
.chip-val.v-rose  { color: var(--rose); }
.chip-sub { font-size: 0.73rem; color: var(--text-4); margin-top: 6px; font-weight: 600; }

/* Significance banner */
.sig-banner { border-radius: var(--r-lg); padding: 20px 24px; display: flex; align-items: center; gap: 16px; margin-bottom: 22px; border: 1.5px solid; box-shadow: var(--s-sm); transition: box-shadow 0.22s, transform 0.22s; }
.sig-banner:hover { box-shadow: var(--s-md); transform: translateY(-1px); }
.sig-banner.sig  { background: var(--emerald-bg); border-color: var(--emerald-border); }
.sig-banner.nsig { background: var(--rose-bg); border-color: var(--rose-border); }
.sig-icon { width: 42px; height: 42px; border-radius: 50%; display: flex; align-items: center; justify-content: center; font-size: 1.05rem; flex-shrink: 0; }
.sig .sig-icon { background: rgba(22,101,52,0.14); color: var(--emerald); }
.nsig .sig-icon { background: rgba(159,18,57,0.14); color: var(--rose); }
.sig-title { font-size: 1rem; font-weight: 800; color: var(--text-1); margin-bottom: 3px; }
.sig-text { font-size: 0.9rem; color: var(--text-2); line-height: 1.55; font-family: var(--font-serif); font-weight: 500; }

/* P-value dual panel */
.pval-panel {
  background: var(--surface); border: 1.5px solid var(--border);
  border-radius: var(--r-lg); padding: 22px 24px; margin-bottom: 22px;
  box-shadow: var(--s-sm); display: grid; grid-template-columns: 1fr 1fr; gap: 18px;
  transition: box-shadow 0.22s;
}
.pval-panel:hover { box-shadow: var(--s-md); }
.pval-half { background: var(--surface-2); border: 1.5px solid var(--border); border-radius: var(--r-md); padding: 18px 20px; text-align: center; transition: border-color 0.2s, box-shadow 0.2s, transform 0.2s; }
.pval-half:hover { border-color: var(--brand); box-shadow: 0 4px 16px rgba(7,87,186,0.14); transform: translateY(-2px); }
.pval-half-lbl { font-size: 0.7rem; font-weight: 800; letter-spacing: 0.1em; text-transform: uppercase; color: var(--text-4); margin-bottom: 9px; }
.pval-half-val { font-family: var(--font-mono); font-size: 1.42rem; font-weight: 700; color: var(--amber); margin-bottom: 6px; }
.pval-half-note { font-family: var(--font-serif); font-size: 0.76rem; font-style: italic; color: var(--text-3); font-weight: 500; line-height: 1.5; }

/* Chi-square panel */
.chi-panel {
  background: var(--amber-bg); border: 1.5px solid var(--amber-border);
  border-radius: var(--r-lg); padding: 20px 24px; margin-bottom: 22px;
  transition: box-shadow 0.22s, transform 0.22s;
}
.chi-panel:hover { box-shadow: 0 6px 22px rgba(133,77,14,0.16); transform: translateY(-1px); }
.chi-panel-title { font-size: 0.74rem; font-weight: 800; letter-spacing: 0.1em; text-transform: uppercase; color: var(--amber); margin-bottom: 12px; display: flex; align-items: center; gap: 7px; }
.chi-row { display: flex; gap: 22px; flex-wrap: wrap; align-items: center; }
.chi-val { font-family: var(--font-mono); font-size: 1.4rem; font-weight: 800; color: var(--amber); }
.chi-meta { font-size: 0.9rem; color: var(--text-2); font-weight: 700; }
.chi-note { font-family: var(--font-serif); font-size: 0.82rem; color: var(--text-3); margin-top: 10px; padding-top: 10px; border-top: 1px solid var(--amber-border); font-style: italic; font-weight: 500; }

/* Interpretation box */
.interp-box {
  background: var(--brand-bg); border: 1.5px solid rgba(7,87,186,0.2);
  border-radius: var(--r-lg); padding: 24px 26px; margin-bottom: 22px;
  transition: box-shadow 0.22s, transform 0.22s, border-color 0.22s;
}
.interp-box:hover { box-shadow: 0 6px 24px rgba(7,87,186,0.14); border-color: var(--brand); transform: translateY(-1px); }
.interp-title { font-size: 0.74rem; font-weight: 800; letter-spacing: 0.1em; text-transform: uppercase; color: var(--brand); margin-bottom: 13px; display: flex; align-items: center; gap: 7px; }
.interp-text { font-family: var(--font-serif); font-size: 1rem; color: var(--text-2); line-height: 1.85; margin-bottom: 15px; font-weight: 500; }
.interp-text strong { color: var(--text-1); font-weight: 800; }
.interp-divider { border: none; border-top: 1.5px solid rgba(7,87,186,0.14); margin: 15px 0; }
.interp-impl { font-family: var(--font-serif); font-size: 0.96rem; color: var(--text-2); line-height: 1.8; font-weight: 500; }

/* Proportion table */
.prop-tbl-wrap {
  background: var(--surface); border: 1.5px solid var(--border);
  border-radius: var(--r-lg); overflow: hidden; margin-bottom: 22px;
  box-shadow: var(--s-sm); transition: box-shadow 0.22s;
}
.prop-tbl-wrap:hover { box-shadow: var(--s-md); }
.prop-tbl-header { padding: 13px 20px; border-bottom: 1.5px solid var(--border); font-size: 0.74rem; font-weight: 800; letter-spacing: 0.1em; text-transform: uppercase; color: var(--text-3); display: flex; align-items: center; gap: 7px; background: var(--surface-2); }
.prop-tbl { width: 100%; border-collapse: collapse; font-size: 0.9rem; }
.prop-tbl th { background: var(--surface-3); color: var(--text-2); font-size: 0.71rem; font-weight: 800; letter-spacing: 0.08em; text-transform: uppercase; padding: 11px 17px; text-align: center; border: 1px solid var(--border-med); }
.prop-tbl th:first-child { text-align: left; }
.prop-tbl td { padding: 11px 17px; border: 1px solid var(--border); text-align: center; font-family: var(--font-mono); font-size: 0.9rem; font-weight: 600; color: var(--text-2); }
.prop-tbl td:first-child { text-align: left; font-family: var(--font-ui); font-weight: 800; font-size: 0.9rem; color: var(--text-1); }
.prop-tbl tr:last-child td { background: var(--brand-bg); color: var(--brand); font-weight: 800; }
.prop-tbl tr:last-child td:first-child { color: var(--text-1); }

/* Chart */
.chart-bar { display: flex; align-items: center; justify-content: space-between; margin-bottom: 18px; flex-wrap: wrap; gap: 9px; }
.chart-bar-title { font-size: 0.96rem; font-weight: 800; color: var(--text-1); }
.chart-bar-btns { display: flex; gap: 9px; }
.sm-btn {
  background: var(--surface-2); border: 1.5px solid var(--border); color: var(--text-2);
  border-radius: var(--r-md); padding: 8px 15px; font-size: 0.82rem; font-family: var(--font-ui);
  font-weight: 700; cursor: pointer; transition: all 0.18s;
  display: flex; align-items: center; gap: 7px;
}
.sm-btn:hover { background: var(--surface-3); color: var(--text-1); border-color: var(--border-med); box-shadow: var(--s-sm); transform: translateY(-1px); }
.sm-btn.accent { background: var(--brand); color: #fff; border-color: var(--brand-dark); }
.sm-btn.accent:hover { background: var(--brand-dark); box-shadow: 0 4px 14px rgba(7,87,186,0.3); }
.chart-box { background: var(--surface-2); border: 1.5px solid var(--border); border-radius: var(--r-lg); padding: 20px; height: 430px; position: relative; cursor: pointer; transition: border-color 0.2s, box-shadow 0.2s; }
.chart-box:hover { border-color: var(--brand); box-shadow: 0 4px 18px rgba(7,87,186,0.12); }
.chart-hint { text-align: center; font-size: 0.73rem; font-weight: 700; color: var(--text-4); margin-top: 9px; }

/* Export */
.export-grid { display: grid; grid-template-columns: repeat(3,1fr); gap: 18px; margin-bottom: 22px; }
.export-card {
  background: var(--surface-2); border: 1.5px solid var(--border);
  border-radius: var(--r-lg); padding: 24px; text-align: center;
  transition: border-color 0.22s, transform 0.22s, box-shadow 0.22s, background 0.22s;
  cursor: default; position: relative; overflow: hidden;
}
.export-card::before {
  content: ''; position: absolute; bottom: 0; left: 0; right: 0; height: 3px;
  background: var(--brand); transform: scaleX(0); transition: transform 0.25s;
  transform-origin: left;
}
.export-card:hover { border-color: var(--brand); transform: translateY(-5px); box-shadow: var(--s-hover-brand); background: var(--surface); }
.export-card:hover::before { transform: scaleX(1); }
.export-icon { font-size: 2.1rem; margin-bottom: 12px; color: var(--brand); }
.export-title { font-size: 0.96rem; font-weight: 800; color: var(--text-1); margin-bottom: 6px; }
.export-desc { font-family: var(--font-serif); font-size: 0.8rem; color: var(--text-3); margin-bottom: 16px; line-height: 1.55; font-weight: 500; }
.export-btn { width: 100%; background: var(--brand-bg); border: 1.5px solid rgba(7,87,186,0.26); color: var(--brand); border-radius: var(--r-md); padding: 10px; font-family: var(--font-ui); font-size: 0.86rem; font-weight: 800; cursor: pointer; transition: all 0.18s; display: flex; align-items: center; justify-content: center; gap: 7px; }
.export-btn:hover { background: var(--brand); color: #fff; border-color: var(--brand); box-shadow: 0 3px 12px rgba(7,87,186,0.28); }

/* Citation */
.citation-box { background: var(--surface-2); border: 1.5px solid var(--border); border-radius: var(--r-lg); padding: 20px 24px; font-family: var(--font-serif); font-size: 1.01rem; color: var(--text-2); line-height: 1.9; position: relative; font-weight: 500; transition: border-color 0.2s; }
.citation-box:hover { border-color: var(--brand); }
.citation-box em { font-style: italic; color: var(--text-1); font-weight: 600; }
.copy-cite-btn { position: absolute; top: 13px; right: 13px; background: var(--surface); border: 1.5px solid var(--border); color: var(--text-3); border-radius: var(--r-sm); padding: 6px 12px; font-size: 0.73rem; font-family: var(--font-ui); font-weight: 700; cursor: pointer; transition: all 0.15s; }
.copy-cite-btn:hover { background: var(--brand); color: #fff; border-color: var(--brand); }

/* =====================================================
   DOCUMENTATION
===================================================== */
.doc-prose { font-family: var(--font-serif); font-size: 1rem; color: var(--text-2); line-height: 1.85; margin-bottom: 18px; font-weight: 500; }
.doc-prose strong { color: var(--text-1); font-weight: 800; }
.doc-code { background: var(--surface-3); border: 1.5px solid var(--border-med); border-radius: var(--r-lg); padding: 20px 24px; font-family: var(--font-mono); font-size: 0.83rem; color: var(--text-1); line-height: 1.9; overflow-x: auto; margin: 18px 0; white-space: pre; border-left: 4px solid var(--brand); font-weight: 500; }
[data-theme="dark"] .doc-code { background: #0d1117; color: #e6edf3; }
.doc-list { list-style: none; padding: 0; margin: 14px 0 20px; }
.doc-list li { display: flex; align-items: flex-start; gap: 11px; padding: 9px 0; font-family: var(--font-serif); font-size: 0.96rem; color: var(--text-2); border-bottom: 1px solid var(--border); font-weight: 500; }
.doc-list li:last-child { border-bottom: none; }
.doc-list li::before { content: '→'; color: var(--brand); font-size: 0.82rem; margin-top: 3px; flex-shrink: 0; font-weight: 800; font-family: var(--font-mono); }
.doc-list li strong { color: var(--text-1); font-weight: 800; }
.faq-item { margin-bottom: 20px; padding-bottom: 20px; border-bottom: 1px solid var(--border); }
.faq-item:last-child { border-bottom: none; }
.faq-q { font-family: var(--font-serif); font-size: 1rem; font-weight: 700; color: var(--text-1); margin-bottom: 9px; display: flex; align-items: flex-start; gap: 10px; }
.faq-q::before { content:'Q'; background: var(--brand-bg); color: var(--brand); border: 1.5px solid rgba(7,87,186,0.24); border-radius: var(--r-xs); width: 24px; height: 24px; display: flex; align-items: center; justify-content: center; font-size: 0.71rem; font-weight: 900; flex-shrink: 0; font-family: var(--font-ui); }
.faq-a { font-family: var(--font-serif); font-size: 0.95rem; color: var(--text-2); line-height: 1.8; padding-left: 34px; font-weight: 500; }

/* =====================================================
   DEVELOPER
===================================================== */
.dev-profile { display: flex; gap: 24px; align-items: flex-start; margin-bottom: 24px; flex-wrap: wrap; }
.dev-avatar { width: 76px; height: 76px; border-radius: 50%; background: linear-gradient(135deg, var(--brand), var(--teal)); display: flex; align-items: center; justify-content: center; font-size: 1.9rem; flex-shrink: 0; box-shadow: 0 4px 18px rgba(7,87,186,0.32); overflow: hidden; }
.dev-name { font-family: var(--font-serif); font-size: 1.6rem; font-weight: 700; color: var(--text-1); margin-bottom: 5px; }
.dev-role { font-size: 0.85rem; color: var(--brand); font-weight: 800; margin-bottom: 12px; }
.dev-bio { font-family: var(--font-serif); font-size: 0.95rem; color: var(--text-2); line-height: 1.8; font-weight: 500; }
.tech-grid { display: grid; grid-template-columns: repeat(4,1fr); gap: 14px; margin: 18px 0; }
.tech-card {
  background: var(--surface-2); border: 1.5px solid var(--border);
  border-radius: var(--r-lg); padding: 18px; text-align: center;
  transition: border-color 0.22s, box-shadow 0.22s, transform 0.22s, background 0.22s;
  cursor: default;
}
.tech-card:hover { border-color: var(--brand); box-shadow: var(--s-hover-brand); transform: translateY(-4px); background: var(--surface); }
.tech-icon { font-size: 1.7rem; color: var(--brand); margin-bottom: 9px; }
.tech-name { font-size: 0.89rem; font-weight: 800; color: var(--text-1); }
.tech-desc { font-family: var(--font-serif); font-size: 0.73rem; color: var(--text-4); margin-top: 3px; font-weight: 500; }
.contact-links { display: flex; gap: 10px; flex-wrap: wrap; margin-top: 18px; }
.contact-link {
  display: inline-flex; align-items: center; gap: 8px;
  background: var(--surface-2); border: 1.5px solid var(--border-med);
  border-radius: var(--r-md); padding: 10px 18px; font-size: 0.88rem; font-weight: 700;
  color: var(--text-2); text-decoration: none;
  transition: all 0.22s;
}
.contact-link:hover { color: var(--brand); background: var(--brand-bg); border-color: rgba(7,87,186,0.32); text-decoration: none; transform: translateY(-2px); box-shadow: 0 4px 14px rgba(7,87,186,0.16); }

/* Developer feature cards */
.dev-feature-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(220px,1fr)); gap: 16px; margin-bottom: 22px; }
.dev-feature-card {
  padding: 22px; background: var(--surface-2); border: 1.5px solid var(--border);
  border-radius: var(--r-lg);
  transition: border-color 0.22s, box-shadow 0.22s, transform 0.22s, background 0.22s;
  cursor: default; position: relative; overflow: hidden;
}
.dev-feature-card::after {
  content: ''; position: absolute; inset: 0; opacity: 0;
  background: linear-gradient(135deg, rgba(7,87,186,0.04), transparent);
  transition: opacity 0.22s; border-radius: var(--r-lg); pointer-events: none;
}
.dev-feature-card:hover { border-color: var(--brand); box-shadow: var(--s-hover-brand); transform: translateY(-4px); background: var(--surface); }
.dev-feature-card:hover::after { opacity: 1; }
.dev-feature-card .feature-icon { font-size: 1.5rem; margin-bottom: 12px; }
.dev-feature-card .feature-title { font-weight: 800; font-size: 0.96rem; color: var(--text-1); margin-bottom: 8px; }
.dev-feature-card .feature-desc { font-family: var(--font-serif); font-size: 0.87rem; color: var(--text-3); line-height: 1.65; font-weight: 400; }

/* =====================================================
   FULLSCREEN MODAL
===================================================== */
.fs-modal { display: none; position: fixed; inset: 0; background: rgba(10,15,30,0.95); z-index: 9999; flex-direction: column; align-items: center; justify-content: center; backdrop-filter: blur(10px); }
.fs-modal.open { display: flex; }
.fs-inner { width: 95%; height: 82%; background: var(--surface); border: 1.5px solid var(--border-med); border-radius: var(--r-xl); padding: 22px; position: relative; box-shadow: var(--s-xl); }
.fs-close { position: absolute; top: -15px; right: -15px; width: 36px; height: 36px; border-radius: 50%; background: var(--brand); border: none; color: #fff; font-size: 0.9rem; cursor: pointer; display: flex; align-items: center; justify-content: center; box-shadow: 0 3px 16px rgba(7,87,186,0.36); transition: all 0.15s; }
.fs-close:hover { background: var(--brand-dark); transform: scale(1.1); }
.fs-toolbar { display: flex; gap: 10px; justify-content: center; margin-top: 18px; }

/* =====================================================
   LOADING
===================================================== */
.loading-screen { position: fixed; inset: 0; background: var(--sidebar-bg); z-index: 9999; display: flex; flex-direction: column; align-items: center; justify-content: center; gap: 22px; transition: opacity 0.4s; }
.loading-screen.fade-out { opacity: 0; pointer-events: none; }
.loading-spinner { width: 46px; height: 46px; border: 3px solid var(--sidebar-border); border-top-color: var(--brand); border-radius: 50%; animation: spin 0.8s linear infinite; }
@keyframes spin { to { transform: rotate(360deg); } }
.loading-title { font-family: var(--font-serif); font-size: 1.6rem; font-weight: 700; color: var(--st-1); letter-spacing: -0.01em; }
.loading-sub { font-size: 0.8rem; color: var(--st-4); font-family: var(--font-mono); font-weight: 600; }

/* =====================================================
   FOOTER
===================================================== */
.site-footer { border-top: 1.5px solid var(--border); padding: 30px 36px; text-align: center; background: var(--surface); }
.site-footer p { font-family: var(--font-serif); font-size: 0.84rem; color: var(--text-4); line-height: 1.9; font-weight: 500; }

/* =====================================================
   RESPONSIVE
===================================================== */
@media (max-width: 768px) {
  .sidebar { transform: translateX(-100%); }
  .sidebar.open { transform: translateX(0); box-shadow: var(--s-xl); }
  .main { margin-left: 0; }
  .hamburger { display: flex; }
  .hero { padding: 24px 18px 0; }
  .hero-headline { font-size: 2.15rem; }
  .content, .section-header { padding: 18px 18px; }
  .sparkline-wrap, .form-row, .export-grid { grid-template-columns: 1fr; }
  .tech-grid { grid-template-columns: 1fr 1fr; }
  .result-chips { grid-template-columns: 1fr 1fr; }
  .stats-strip { grid-template-columns: 1fr 1fr; }
  .stat-cell { border-right: 1px solid var(--border); }
  .topbar { padding: 0 16px; }
  .demo-stats-row { grid-template-columns: 1fr 1fr; }
  .pval-panel { grid-template-columns: 1fr; }
}

.mt-4 { margin-top: 16px; }
.mb-4 { margin-bottom: 16px; }
</style>
</head>

<body>

<!-- Loading -->
<div class="loading-screen" id="loadingScreen">
  <div class="loading-spinner"></div>
  <div class="loading-title">CATrend Analyzer</div>
  <div class="loading-sub">Cochran–Armitage Trend Test · v1.0.0</div>
</div>

<!-- Sidebar -->
<aside class="sidebar" id="sidebar">
  <div class="sidebar-logo">
    <div class="logo-mark" onclick="showSection('home')">
      <div class="logo-icon-wrap"><i class="fas fa-chart-line"></i></div>
      <div class="logo-text">
        <span class="logo-name">CATrend</span>
        <span class="logo-sub">Trend Analyzer</span>
      </div>
    </div>
  </div>

  <nav class="sidebar-nav">
    <span class="nav-section">Navigation</span>
    <div class="nav-item active" data-sec="home" onclick="showSection('home')"><i class="fas fa-house"></i> Home</div>
    <div class="nav-item" data-sec="analysis" onclick="showSection('analysis')"><i class="fas fa-calculator"></i> Analysis</div>
    <span class="nav-section">Resources</span>
    <div class="nav-item" data-sec="documentation" onclick="showSection('documentation')"><i class="fas fa-book-open"></i> Documentation</div>
    <div class="nav-item" data-sec="developer" onclick="showSection('developer')"><i class="fas fa-user-circle"></i> Developer</div>
  </nav>

  <div class="sidebar-footer">
    <div class="theme-row">
      <span class="theme-label">Appearance</span>
      <button class="theme-btn" id="themeBtn"><i class="fas fa-moon" id="themeIcon"></i> <span id="themeLabel">Dark</span></button>
    </div>
    <div class="ver-badge">v1.0.0 · Open Source · Ghana</div>
  </div>
</aside>

<!-- Main -->
<div class="main">
  <!-- Topbar -->
  <div class="topbar">
    <div class="topbar-left">
      <button class="hamburger" id="hamburgerBtn"><i class="fas fa-bars"></i></button>
      <div class="breadcrumb">
        <span>CATrend Analyzer</span>
        <span class="sep">/</span>
        <span class="current" id="topbarSection">Home</span>
      </div>
    </div>
    <div class="topbar-right">
      <a href="https://github.com/mudassiribrahim12/cochran-armitage" target="_blank" rel="noopener" class="tb-ghost">
        <i class="fab fa-github"></i> Source Code
      </a>
      <button class="tb-primary" onclick="showSection('analysis')">
        <i class="fas fa-play"></i> Start Analysis
      </button>
    </div>
  </div>

  <!-- ==================== HOME ==================== -->
  <div class="page-section active" id="section-home">
    <div class="hero">
      <div class="hero-badge"><span class="dot"></span> Statistical Analysis Software</div>
      <h1 class="hero-headline">Cochran–Armitage<br>Trend Test, <em>reimagined.</em></h1>
      <p class="hero-sub">A free, open-source web tool for analysing trends in proportions across ordered categorical groups — built for clinical trials, epidemiology, and public health research.</p>
      <div class="cta-row">
        <button class="btn-primary" onclick="showSection('analysis')"><i class="fas fa-play-circle"></i> Start Analysis</button>
        <button class="btn-outline" onclick="showSection('documentation')"><i class="fas fa-book-open"></i> Documentation</button>
      </div>
    </div>

    <div class="content" style="padding-top:0;">
      <div class="stats-strip">
        <div class="stat-cell"><div class="stat-num">100%</div><div class="stat-desc">Free &amp; Open Source</div></div>
        <div class="stat-cell"><div class="stat-num">No Login</div><div class="stat-desc">Required</div></div>
        <div class="stat-cell"><div class="stat-num">1 &amp; 2‑sided</div><div class="stat-desc">P-value Reporting</div></div>
        <div class="stat-cell"><div class="stat-num">Word / CSV</div><div class="stat-desc">Export Formats</div></div>
      </div>

      <!-- Demo card -->
      <div class="demo-card" id="demoCard">
        <div class="demo-header">
          <div>
            <div class="demo-title">Sample Trend Analysis</div>
            <div class="demo-subtitle">Increasing success rates across treatment levels</div>
          </div>
          <div class="demo-badge">DEMO</div>
        </div>
        <div class="sparkline-wrap">
          <div class="mini-chart-area">
            <div class="mini-chart-label">Frequency by group</div>
            <div class="trend-bars" id="demoBars"></div>
          </div>
          <div class="mini-chart-area">
            <div class="mini-chart-label">Sample contingency table</div>
            <table class="preview-tbl" style="margin-top:6px;">
              <thead><tr id="prevHead"></tr></thead>
              <tbody id="prevBody"></tbody>
            </table>
          </div>
        </div>
        <div class="demo-stats-row">
          <div class="demo-stat"><div class="demo-stat-val" id="demoZ">4.32</div><div class="demo-stat-lbl">Z-statistic (signed)</div></div>
          <div class="demo-stat"><div class="demo-stat-val pos" id="demoP">&lt;0.001</div><div class="demo-stat-lbl">Two-sided P-value</div></div>
          <div class="demo-stat"><div class="demo-stat-val pos" id="demoTrend">Increasing</div><div class="demo-stat-lbl">Trend direction</div></div>
          <div class="demo-stat"><div class="demo-stat-val neu" id="demoN">400</div><div class="demo-stat-lbl">Total observations</div></div>
        </div>
      </div>

      <!-- About -->
      <div class="panel">
        <div class="panel-header"><div class="panel-title"><i class="fas fa-info-circle"></i> About the Cochran–Armitage Trend Test</div></div>
        <div class="panel-body">
          <p class="doc-prose">The <strong>Cochran–Armitage Trend Test (CATT)</strong> is a statistical method for detecting monotone trends in proportions across ordered categorical variables. It is especially powerful when the explanatory variable has a natural ordering and the outcome is binary.</p>
          <ul class="doc-list">
            <li><strong>Clinical Trials:</strong> Testing if treatment response increases with dosage levels</li>
            <li><strong>Epidemiology:</strong> Analysing disease incidence across ordered age groups</li>
            <li><strong>Public Health:</strong> Examining vaccination rates across socioeconomic strata</li>
            <li><strong>Genetics:</strong> Testing genotype–phenotype associations (dose-response modelling)</li>
            <li><strong>Market Research:</strong> Analysing preference trends across product variants</li>
          </ul>
          <div class="formula-box">Z = Σ yⱼ(xⱼ − x̄) / √[ p̄(1−p̄) · Σ nⱼ(xⱼ − x̄)² ]</div>
          <p class="doc-prose"><strong>Key assumptions:</strong> ordered categories, independent observations, binary outcome, sufficient sample size for normal approximation, non-zero marginal totals.</p>
        </div>
      </div>

      <!-- Features -->
      <div class="panel">
        <div class="panel-header"><div class="panel-title"><i class="fas fa-star"></i> Key Features</div></div>
        <div class="panel-body">
          <div class="feature-grid">
            <div class="feature-card"><div class="feature-icon" style="color:var(--brand)"><i class="fas fa-table"></i></div><div class="feature-title">Interactive Contingency Tables</div><div class="feature-desc">Create and edit tables with unlimited rows and columns. Dynamic totals update in real time as you type.</div></div>
            <div class="feature-card"><div class="feature-icon" style="color:var(--teal)"><i class="fas fa-chart-bar"></i></div><div class="feature-title">Advanced Visualisation</div><div class="feature-desc">Clustered bar charts with counts, row %, and column % labels. Full-screen view and PNG export.</div></div>
            <div class="feature-card"><div class="feature-icon" style="color:var(--amber)"><i class="fas fa-file-word"></i></div><div class="feature-title">Professional Export</div><div class="feature-desc">Export to Microsoft Word, CSV with tables, results, interpretation, and APA citation.</div></div>
            <div class="feature-card"><div class="feature-icon" style="color:var(--rose)"><i class="fas fa-lightbulb"></i></div><div class="feature-title">Automatic Interpretation</div><div class="feature-desc">Signed Z-statistic, one-sided &amp; two-sided p-values, trend direction, and plain-language summaries.</div></div>
            <div class="feature-card"><div class="feature-icon" style="color:var(--emerald)"><i class="fas fa-graduation-cap"></i></div><div class="feature-title">Educational Resources</div><div class="feature-desc">Detailed formula explanations, step-by-step documentation, and a comprehensive FAQ section.</div></div>
            <div class="feature-card"><div class="feature-icon" style="color:var(--violet)"><i class="fas fa-shield-halved"></i></div><div class="feature-title">Privacy First</div><div class="feature-desc">All calculations run entirely in your browser. No data is ever sent to any server.</div></div>
          </div>
        </div>
      </div>
    </div>

    <div class="site-footer">
      <p>© <span id="currentYear"></span> CATrend Analyzer — Open-Source Cochran–Armitage Trend Test Software.<br>
      Built in Ghana by <a href="https://mudasiribrahim.vercel.app/" target="_blank" rel="noopener">Mudasir Mohammed Ibrahim</a>
      · Version 1.0.0 · Last updated: <span id="lastUpdated"></span></p>
    </div>
  </div>

  <!-- ==================== ANALYSIS ==================== -->
  <div class="page-section" id="section-analysis">
    <div class="section-header">
      <h2 class="section-title">Cochran–Armitage Trend Test</h2>
      <p class="section-desc">Enter your contingency table, configure options, and run the analysis. Results with full interpretation appear below.</p>
    </div>
    <div class="content" style="padding-top:0;">
      <div class="panel">
        <div class="panel-header"><div class="panel-title"><i class="fas fa-table"></i> Contingency Table Input</div></div>
        <div class="panel-body">
          <div class="alert-strip alert-info">
            <i class="fas fa-info-circle"></i>
            <div>Enter frequency counts (whole numbers). <strong>Row 1</strong> = success/event; <strong>Columns</strong> = ordered groups. Click any header to rename it.</div>
          </div>
          <div class="ctrl-bar">
            <div class="ctrl-group">
              <span class="ctrl-lbl">Rows</span>
              <button class="ctrl-btn add" id="addRowBtn" title="Add Row"><i class="fas fa-plus"></i></button>
              <button class="ctrl-btn rem" id="removeRowBtn" title="Remove Row"><i class="fas fa-minus"></i></button>
            </div>
            <div class="ctrl-group">
              <span class="ctrl-lbl">Columns</span>
              <button class="ctrl-btn add" id="addColBtn" title="Add Column"><i class="fas fa-plus"></i></button>
              <button class="ctrl-btn rem" id="removeColBtn" title="Remove Column"><i class="fas fa-minus"></i></button>
            </div>
          </div>
          <div class="tbl-wrap">
            <table class="data-tbl" id="contingencyTable">
              <thead id="tableHeader"></thead>
              <tbody id="tableBody"></tbody>
            </table>
          </div>
        </div>
      </div>

      <div class="form-row">
        <div class="panel" style="margin-bottom:0;">
          <div class="panel-header"><div class="panel-title"><i class="fas fa-cog"></i> Analysis Options</div></div>
          <div class="panel-body">
            <label class="checkbox-item">
              <input type="checkbox" id="continuityCorrection">
              <span>Apply continuity correction <span style="color:var(--text-4);font-size:0.82em;">(recommended for N &lt; 100)</span></span>
            </label>
            <div class="formula-box" style="font-size:0.86rem;padding:14px;">Z = Σ yⱼ(xⱼ − x̄) / √[p̄(1−p̄) Σ nⱼ(xⱼ − x̄)²]</div>
          </div>
        </div>
        <div class="panel" style="margin-bottom:0;">
          <div class="panel-header"><div class="panel-title"><i class="fas fa-chart-bar"></i> Chart Labels</div></div>
          <div class="panel-body">
            <label class="checkbox-item"><input type="checkbox" id="showCounts" checked><span>Show counts on bars</span></label>
            <label class="checkbox-item"><input type="checkbox" id="showRowPercent"><span>Show row percentages</span></label>
            <label class="checkbox-item"><input type="checkbox" id="showColPercent" checked><span>Show column percentages</span></label>
          </div>
        </div>
      </div>

      <div class="run-section">
        <button class="run-btn" id="runAnalysisBtn"><i class="fas fa-flask"></i> Run Cochran–Armitage Test</button>
        <div class="warn-msg" id="dataWarning"><i class="fas fa-exclamation-triangle"></i> Please enter valid numeric data before running the analysis.</div>
      </div>

      <div class="results-section" id="resultsSection"></div>
    </div>
  </div>

  <!-- ==================== DOCUMENTATION ==================== -->
  <div class="page-section" id="section-documentation">
    <div class="section-header">
      <h2 class="section-title">Documentation</h2>
      <p class="section-desc">Statistical methodology, interpretation guidelines, and answers to frequently asked questions.</p>
    </div>
    <div class="content" style="padding-top:0;">
      <div class="panel">
        <div class="panel-header"><div class="panel-title"><i class="fas fa-square-root-variable"></i> Mathematical Foundation</div></div>
        <div class="panel-body">
          <p class="doc-prose">The test statistic is computed as:</p>
          <div class="formula-box">Z = (Σ yⱼ(xⱼ − x̄)) / √[ p̄(1−p̄) · Σ nⱼ(xⱼ − x̄)² ]</div>
          <ul class="doc-list">
            <li><strong>xⱼ</strong> — Scores for ordered groups (default: 1, 2, 3, …)</li>
            <li><strong>yⱼ</strong> — Success counts in each group</li>
            <li><strong>nⱼ</strong> — Total counts in each group</li>
            <li><strong>x̄</strong> — Weighted mean: Σ(nⱼ·xⱼ)/N</li>
            <li><strong>p̄</strong> — Overall proportion of successes: Σyⱼ/N</li>
            <li><strong>N</strong> — Grand total: Σnⱼ</li>
          </ul>
          <p class="doc-prose"><strong>Signed Z-statistic:</strong> CATrend Analyzer reports a signed Z value. A positive Z indicates an increasing trend; a negative Z indicates a decreasing trend. Both one-sided and two-sided p-values are reported.</p>
          <p class="doc-prose"><strong>Continuity correction:</strong></p>
          <div class="formula-box">Z = (|Σ yⱼ(xⱼ − x̄)| − 0.5) / √[ p̄(1−p̄) · Σ nⱼ(xⱼ − x̄)² ]</div>
          <p class="doc-prose"><strong>P-value computation:</strong></p>
          <div class="doc-code">One-sided p-value  = 1 − Φ(|Z|)      [tail in direction of observed Z]
Two-sided p-value  = 2 × (1 − Φ(|Z|))

Chi-square (Pearson, general association):
  Expected Eᵢⱼ = (rowTotalᵢ × colTotalⱼ) / N
  χ²           = Σᵢⱼ (Oᵢⱼ − Eᵢⱼ)² / Eᵢⱼ
  df           = (rows−1) × (cols−1)</div>
          <p class="doc-prose"><strong>Step-by-step algorithm:</strong></p>
          <div class="doc-code">1. Assign scores xⱼ = 1, 2, …, k
2. Compute column totals nⱼ and success counts yⱼ
3. Compute weighted mean x̄ = Σ(nⱼ·xⱼ) / N
4. Compute overall proportion p̄ = Σyⱼ / N
5. Numerator = Σ yⱼ(xⱼ − x̄)
6. Variance = p̄(1−p̄) · Σ nⱼ(xⱼ − x̄)²
7. Z = (|Numerator| − correction) / √Variance, sign from Numerator
8. One-sided p = 1 − Φ(|Z|)
9. Two-sided p = 2 × (1 − Φ(|Z|))</div>
        </div>
      </div>

      <div class="panel">
        <div class="panel-header"><div class="panel-title"><i class="fas fa-chart-line"></i> Interpretation Guidelines</div></div>
        <div class="panel-body">
          <ul class="doc-list">
            <li><strong>p &lt; 0.001</strong> — Highly significant trend</li>
            <li><strong>p &lt; 0.01</strong> — Very significant trend</li>
            <li><strong>p &lt; 0.05</strong> — Statistically significant trend</li>
            <li><strong>p ≥ 0.05</strong> — No significant trend detected</li>
          </ul>
        </div>
      </div>

      <div class="panel">
        <div class="panel-header"><div class="panel-title"><i class="fas fa-circle-question"></i> Frequently Asked Questions</div></div>
        <div class="panel-body">
          <div class="faq-item">
            <div class="faq-q">What is the minimum sample size required?</div>
            <div class="faq-a">There is no strict minimum. The test relies on a normal approximation, so it works best when expected counts per cell are not too small. A common guideline is ≥ 20 observations per group. For smaller samples, consider exact methods.</div>
          </div>
          <div class="faq-item">
            <div class="faq-q">Can I use this test for more than two outcome categories?</div>
            <div class="faq-a">No. CATT requires a binary outcome. For ordinal outcomes with multiple categories, consider the Jonckheere–Terpstra test or the linear-by-linear association test.</div>
          </div>
          <div class="faq-item">
            <div class="faq-q">What is the difference between one-sided and two-sided p-values?</div>
            <div class="faq-a">The one-sided p-value tests whether the trend goes in a specific direction (increasing or decreasing) as observed. The two-sided p-value tests whether any trend exists regardless of direction. For confirmatory analysis where you pre-specified the direction, the one-sided p is appropriate; otherwise, the two-sided p is recommended.</div>
          </div>
          <div class="faq-item">
            <div class="faq-q">How does this differ from a chi-square test?</div>
            <div class="faq-a">The Pearson chi-square test detects any association between variables (df = (rows−1)×(cols−1)). CATT specifically tests for a linear trend in proportions across ordered groups (df = 1), making it more powerful when a monotone trend is expected. The chi-square results shown here use the correct Pearson formula compatible with SPSS, R, and SAS.</div>
          </div>
          <div class="faq-item">
            <div class="faq-q">How do I cite CATrend Analyzer?</div>
            <div class="faq-a">Use the citation provided in the results panel after running an analysis. The citation follows APA format and includes the retrieval URL.</div>
          </div>
        </div>
      </div>

      <div class="panel">
        <div class="panel-header"><div class="panel-title"><i class="fas fa-triangle-exclamation"></i> Troubleshooting</div></div>
        <div class="panel-body">
          <div class="alert-strip alert-warn" style="margin-bottom:10px;"><i class="fas fa-exclamation-circle"></i><div><strong>Zero cells:</strong> The test may still run, but interpret results cautiously. Consider aggregating groups or using exact methods.</div></div>
          <div class="alert-strip alert-warn" style="margin-bottom:10px;"><i class="fas fa-exclamation-circle"></i><div><strong>Small samples (N &lt; 20):</strong> Normal approximation may be invalid. Enable continuity correction or consult a statistician.</div></div>
          <div class="alert-strip alert-warn"><i class="fas fa-exclamation-circle"></i><div><strong>Missing data:</strong> All cells must be filled with non-negative integers. Handle missing data before entering values.</div></div>
        </div>
      </div>
    </div>
  </div>

  <!-- ==================== DEVELOPER ==================== -->
  <div class="page-section" id="section-developer">
    <div class="section-header">
      <h2 class="section-title">Developer</h2>
      <p class="section-desc">About the creator of CATrend Analyzer and the technical implementation.</p>
    </div>
    <div class="content" style="padding-top:0;">
      <div class="panel">
        <div class="panel-header"><div class="panel-title"><i class="fas fa-user-circle"></i> About the Developer</div></div>
        <div class="panel-body">
          <div class="dev-profile">
            <div class="dev-avatar">👨‍💻</div>
            <div>
              <div class="dev-name">Mudasir Mohammed Ibrahim</div>
              <div class="dev-role">Registered Nurse &amp; Health Researcher · Ghana</div>
              <div class="dev-bio">A dedicated healthcare professional with a passion for data analysis and research methodology. CATrend Analyzer was created to bridge the gap between clinical practice and statistical analysis — making advanced tools accessible to healthcare professionals, researchers, and students without requiring programming knowledge.</div>
            </div>
          </div>
          <div class="dev-feature-grid">
            <div class="dev-feature-card"><div class="feature-icon" style="color:var(--rose)"><i class="fas fa-heartbeat"></i></div><div class="feature-title">Healthcare Vision</div><div class="feature-desc">Improve outcomes through accessible data analysis tools that empower medical professionals to make evidence-based decisions.</div></div>
            <div class="dev-feature-card"><div class="feature-icon" style="color:var(--teal)"><i class="fas fa-laptop-code"></i></div><div class="feature-title">Technical Approach</div><div class="feature-desc">Developing user-friendly, open-source tools implementing rigorous statistical methods with clinical relevance.</div></div>
            <div class="dev-feature-card"><div class="feature-icon" style="color:var(--emerald)"><i class="fas fa-globe"></i></div><div class="feature-title">Community Impact</div><div class="feature-desc">Free resources supporting healthcare research and education worldwide, particularly in resource-limited settings.</div></div>
          </div>
          <div class="contact-links">
            <a href="mailto:mudassiribrahim30@gmail.com" class="contact-link"><i class="fas fa-envelope"></i> Email</a>
            <a href="https://www.researchgate.net/profile/Mudasir-Ibrahim" target="_blank" rel="noopener" class="contact-link"><i class="fab fa-researchgate"></i> ResearchGate</a>
            <a href="https://scholar.google.com/citations?user=xEFzAvgAAAAJ&hl=en" target="_blank" rel="noopener" class="contact-link"><i class="fas fa-graduation-cap"></i> Google Scholar</a>
            <a href="https://orcid.org/0000-0002-9049-8222" target="_blank" rel="noopener" class="contact-link"><i class="fas fa-id-badge"></i> ORCID</a>
          </div>
        </div>
      </div>

      <div class="panel">
        <div class="panel-header"><div class="panel-title"><i class="fas fa-code"></i> Technology Stack</div></div>
        <div class="panel-body">
          <div class="tech-grid">
            <div class="tech-card"><div class="tech-icon"><i class="fab fa-html5"></i></div><div class="tech-name">HTML5</div><div class="tech-desc">Semantic markup &amp; SEO</div></div>
            <div class="tech-card"><div class="tech-icon"><i class="fab fa-css3-alt"></i></div><div class="tech-name">CSS3</div><div class="tech-desc">Custom properties, Grid</div></div>
            <div class="tech-card"><div class="tech-icon"><i class="fab fa-js"></i></div><div class="tech-name">JavaScript</div><div class="tech-desc">Vanilla ES6+</div></div>
            <div class="tech-card"><div class="tech-icon"><i class="fas fa-chart-bar"></i></div><div class="tech-name">Chart.js</div><div class="tech-desc">Data visualisation</div></div>
          </div>
          <p class="doc-prose" style="margin-top:12px;">All statistical computations run entirely client-side. No data is transmitted to any server.</p>
          <div class="doc-code">// Core Cochran–Armitage computation
function performCATT(data, cc) {
  const scores = data.cols.map((_,i) => i + 1);
  const N    = data.flat().reduce((a,b) => a+b, 0);
  const nj   = scores.map((_,j) => data.reduce((s,r) => s+r[j], 0));
  const yj   = data[0];
  const xbar = nj.reduce((s,n,j) => s + n*scores[j], 0) / N;
  const pbar = yj.reduce((a,b) => a+b, 0) / N;
  const num  = yj.reduce((s,y,j) => s + y*(scores[j]-xbar), 0);
  const den  = Math.sqrt(pbar*(1-pbar)*nj.reduce((s,n,j) =>
                 s + n*(scores[j]-xbar)**2, 0));
  const Z    = (Math.abs(num)-(cc?0.5:0))/den * Math.sign(num);
  return { Z, pOne: 1-normalCDF(Math.abs(Z)), pTwo: 2*(1-normalCDF(Math.abs(Z))) };
}</div>
        </div>
      </div>
    </div>
  </div>
</div>

<!-- Fullscreen modal -->
<div class="fs-modal" id="fsModal">
  <div class="fs-inner">
    <button class="fs-close" id="fsClose"><i class="fas fa-times"></i></button>
    <canvas id="fsChart" style="width:100%;height:100%;"></canvas>
  </div>
  <div class="fs-toolbar">
    <button class="sm-btn" id="fsZoomIn"><i class="fas fa-magnifying-glass-plus"></i> Zoom In</button>
    <button class="sm-btn" id="fsZoomOut"><i class="fas fa-magnifying-glass-minus"></i> Zoom Out</button>
    <button class="sm-btn" id="fsReset"><i class="fas fa-rotate"></i> Reset</button>
    <button class="sm-btn accent" id="fsDl"><i class="fas fa-download"></i> Download PNG</button>
  </div>
</div>

<!-- =====================================================
     JAVASCRIPT
===================================================== -->
<script>
let currentData = null;
let chartInst = null;
let fsChartInst = null;
let fsZoom = 1;

const DEMO = {
  labels:['Level 1','Level 2','Level 3','Level 4'],
  s:[40,65,80,95], f:[60,35,20,5],
  z:4.32, p:'<0.001', trend:'Increasing', N:400
};

document.addEventListener('DOMContentLoaded', () => {
  Chart.register(ChartDataLabels);
  initTheme();
  initDemoViz();
  initNavigation();
  initAnalysis();
  initHamburger();
  document.getElementById('currentYear').textContent = new Date().getFullYear();
  const now = new Date();
  const months=['January','February','March','April','May','June','July','August','September','October','November','December'];
  document.getElementById('lastUpdated').textContent = months[now.getMonth()] + ' ' + now.getFullYear();
  setTimeout(() => {
    const ls = document.getElementById('loadingScreen');
    ls.classList.add('fade-out');
    setTimeout(() => ls.remove(), 500);
  }, 900);
});

const NAMES = {home:'Home',analysis:'Analysis',documentation:'Documentation',developer:'Developer'};
function showSection(id) {
  document.querySelectorAll('.page-section').forEach(s => s.classList.remove('active'));
  document.querySelectorAll('.nav-item').forEach(n => n.classList.remove('active'));
  document.getElementById('section-'+id).classList.add('active');
  const nav = document.querySelector('.nav-item[data-sec="'+id+'"]');
  if (nav) nav.classList.add('active');
  document.getElementById('topbarSection').textContent = NAMES[id] || id;
  window.scrollTo({top:0,behavior:'smooth'});
  if (window.innerWidth <= 768) document.getElementById('sidebar').classList.remove('open');
}
function initNavigation() {
  document.querySelectorAll('.nav-item[data-sec]').forEach(el => {
    el.addEventListener('click', () => showSection(el.dataset.sec));
  });
}
function initHamburger() {
  const btn = document.getElementById('hamburgerBtn');
  const sb  = document.getElementById('sidebar');
  btn.addEventListener('click', () => sb.classList.toggle('open'));
  document.addEventListener('click', e => { if (!sb.contains(e.target) && !btn.contains(e.target)) sb.classList.remove('open'); });
}

function initTheme() {
  const saved = localStorage.getItem('catrend-theme');
  const pref  = window.matchMedia('(prefers-color-scheme: dark)').matches ? 'dark' : 'light';
  setTheme(saved || pref);
  document.getElementById('themeBtn').addEventListener('click', () => {
    const cur = document.documentElement.getAttribute('data-theme') || 'light';
    setTheme(cur === 'dark' ? 'light' : 'dark');
  });
}
function setTheme(t) {
  document.documentElement.setAttribute('data-theme', t);
  localStorage.setItem('catrend-theme', t);
  document.getElementById('themeIcon').className = t === 'dark' ? 'fas fa-sun' : 'fas fa-moon';
  document.getElementById('themeLabel').textContent = t === 'dark' ? 'Light' : 'Dark';
}

function initDemoViz() {
  const bars = document.getElementById('demoBars');
  bars.innerHTML = '';
  const maxV = Math.max(...DEMO.s,...DEMO.f);
  DEMO.labels.forEach((lbl,i) => {
    const g = document.createElement('div'); g.className = 'trend-bar-group';
    const sh = Math.round((DEMO.s[i]/maxV)*96);
    const fh = Math.round((DEMO.f[i]/maxV)*96);
    g.innerHTML = `<div class="trend-bar s" style="height:0;" data-h="${sh}"></div>
                   <div class="trend-bar f" style="height:0;" data-h="${fh}"></div>
                   <div class="trend-bar-lbl">${lbl}</div>`;
    bars.appendChild(g);
  });
  setTimeout(() => document.querySelectorAll('.trend-bar').forEach(b => b.style.height = b.dataset.h+'px'), 120);

  const hd = document.getElementById('prevHead');
  const bd = document.getElementById('prevBody');
  hd.innerHTML = '<th></th>'+DEMO.labels.map(l=>'<th>'+l+'</th>').join('')+'<th>Total</th>';
  const tots = DEMO.labels.map((_,i)=>DEMO.s[i]+DEMO.f[i]);
  bd.innerHTML = `
    <tr><td class="row-hdr">Success</td>${DEMO.s.map(v=>'<td>'+v+'</td>').join('')}<td>${DEMO.s.reduce((a,b)=>a+b,0)}</td></tr>
    <tr><td class="row-hdr">Failure</td>${DEMO.f.map(v=>'<td>'+v+'</td>').join('')}<td>${DEMO.f.reduce((a,b)=>a+b,0)}</td></tr>
    <tr class="total-row"><td class="row-hdr">Total</td>${tots.map(v=>'<td>'+v+'</td>').join('')}<td>${tots.reduce((a,b)=>a+b,0)}</td></tr>`;
  document.getElementById('demoZ').textContent = DEMO.z;
  document.getElementById('demoP').textContent = DEMO.p;
  document.getElementById('demoTrend').textContent = DEMO.trend;
  document.getElementById('demoN').textContent = DEMO.N;
}

function initAnalysis() {
  currentData = {
    rows:['Success','Failure'],
    cols:['Level 1','Level 2','Level 3'],
    data:[[10,25,30],[30,15,10]]
  };
  chartInst = null;
  renderTable();
  document.getElementById('addRowBtn').onclick    = ()=>{ currentData.rows.push('Outcome '+(currentData.rows.length+1)); currentData.data.push(new Array(currentData.cols.length).fill(0)); renderTable(); };
  document.getElementById('removeRowBtn').onclick = ()=>{ if(currentData.rows.length>1){ currentData.rows.pop(); currentData.data.pop(); renderTable(); } };
  document.getElementById('addColBtn').onclick    = ()=>{ currentData.cols.push('Level '+(currentData.cols.length+1)); currentData.data.forEach(r=>r.push(0)); renderTable(); };
  document.getElementById('removeColBtn').onclick = ()=>{ if(currentData.cols.length>1){ currentData.cols.pop(); currentData.data.forEach(r=>r.pop()); renderTable(); } };
  document.getElementById('runAnalysisBtn').onclick = ()=>{ if(validateData()){ const r=performCAT(); displayResults(r); } };
  ['showCounts','showRowPercent','showColPercent'].forEach(id => {
    document.getElementById(id).onchange = ()=>{ if(chartInst){ updateChart(performCAT()); } };
  });
}

function renderTable() {
  const {rows,cols,data} = currentData;
  let hdr = '<tr><th></th>';
  cols.forEach((c,j)=>{ hdr+=`<th><input class="hdr-input" value="${c}" data-col="${j}"/></th>`; });
  hdr+='<th>Total</th><th>%</th></tr>';
  document.getElementById('tableHeader').innerHTML = hdr;

  const rowT = data.map(r=>r.reduce((a,b)=>a+b,0));
  const colT = cols.map((_,j)=>data.reduce((s,r)=>s+r[j],0));
  const grand = rowT.reduce((a,b)=>a+b,0);
  let bdy='';
  rows.forEach((row,i)=>{
    const pct = grand>0?(rowT[i]/grand*100).toFixed(1):'0.0';
    bdy+=`<tr>
      <td class="row-hdr-cell"><input class="row-hdr-input" value="${row}" data-row="${i}"/></td>
      ${data[i].map((v,j)=>`<td><input type="number" min="0" value="${v}" data-row="${i}" data-col="${j}"/></td>`).join('')}
      <td class="total-cell" id="rt-${i}">${rowT[i]}</td>
      <td class="total-cell" id="rp-${i}">${pct}%</td>
    </tr>`;
  });
  bdy+=`<tr>
    <td class="total-cell">Total</td>
    ${colT.map((t,j)=>`<td class="total-cell" id="ct-${j}">${t}</td>`).join('')}
    <td class="total-cell grand-total" id="grand">${grand}</td>
    <td class="total-cell">100%</td>
  </tr>`;
  document.getElementById('tableBody').innerHTML = bdy;

  document.querySelectorAll('.hdr-input').forEach(inp=>{
    inp.addEventListener('change',e=>{ currentData.cols[+e.target.dataset.col]=e.target.value; });
  });
  document.querySelectorAll('.row-hdr-input').forEach(inp=>{
    inp.addEventListener('change',e=>{ currentData.rows[+e.target.dataset.row]=e.target.value; });
  });
  document.querySelectorAll('#tableBody input[type="number"]').forEach(inp=>{
    inp.addEventListener('input',e=>{
      const r=+e.target.dataset.row,c=+e.target.dataset.col;
      currentData.data[r][c]=parseInt(e.target.value)||0;
      updateTotals();
    });
  });
}

function updateTotals() {
  const {data,rows,cols}=currentData;
  const rowT=data.map(r=>r.reduce((a,b)=>a+b,0));
  const colT=cols.map((_,j)=>data.reduce((s,r)=>s+r[j],0));
  const grand=rowT.reduce((a,b)=>a+b,0);
  rows.forEach((_,i)=>{
    const rt=document.getElementById('rt-'+i); if(rt) rt.textContent=rowT[i];
    const rp=document.getElementById('rp-'+i); if(rp) rp.textContent=(grand>0?(rowT[i]/grand*100).toFixed(1):'0.0')+'%';
  });
  cols.forEach((_,j)=>{ const ct=document.getElementById('ct-'+j); if(ct) ct.textContent=colT[j]; });
  const g=document.getElementById('grand'); if(g) g.textContent=grand;
}

function validateData() {
  const has=currentData.data.flat().some(v=>v>0);
  document.getElementById('dataWarning').style.display=has?'none':'flex';
  return has;
}

function erf(x) {
  const a=[0.254829592,-0.284496736,1.421413741,-1.453152027,1.061405429],p=0.3275911;
  const s=x<0?-1:1; x=Math.abs(x);
  const t=1/(1+p*x);
  return s*(1-(((((a[4]*t+a[3])*t)+a[2])*t+a[1])*t+a[0])*t*Math.exp(-x*x));
}
function normalCDF(z){ return (1+erf(z/Math.sqrt(2)))/2; }

function gammaLn(z) {
  const g=7,c=[0.99999999999980993,676.5203681218851,-1259.1392167224028,771.32342877765313,-176.61502916214059,12.507343278686905,-0.13857109526572012,9.9843695780195716e-6,1.5056327351493116e-7];
  if(z<0.5) return Math.log(Math.PI/Math.sin(Math.PI*z))-gammaLn(1-z);
  z-=1; let x=c[0];
  for(let i=1;i<g+2;i++) x+=c[i]/(z+i);
  const t=z+g+0.5;
  return 0.5*Math.log(2*Math.PI)+(z+0.5)*Math.log(t)-t+Math.log(x);
}
function gammaSeriesP(a,x){const IT=200,EPS=3e-14;let ap=a,del=1/a,sum=del;for(let n=1;n<=IT;n++){ap++;del*=x/ap;sum+=del;if(Math.abs(del)<Math.abs(sum)*EPS)break;}return sum*Math.exp(-x+a*Math.log(x)-gammaLn(a));}
function gammaCFQ(a,x){const IT=200,EPS=3e-14,FP=1e-300;let b=x+1-a,c=1/FP,d=1/b,h=d;for(let i=1;i<=IT;i++){const an=-i*(i-a);b+=2;d=an*d+b;if(Math.abs(d)<FP)d=FP;c=b+an/c;if(Math.abs(c)<FP)c=FP;d=1/d;const dl=d*c;h*=dl;if(Math.abs(dl-1)<EPS)break;}return Math.exp(-x+a*Math.log(x)-gammaLn(a))*h;}
function chiSqP(chi2,df){if(chi2<=0||df<=0)return 1;const a=df/2,x=chi2/2;return x<a+1?1-gammaSeriesP(a,x):gammaCFQ(a,x);}

function pearsonChiSq(){
  const {rows,cols,data}=currentData;
  const rowT=data.map(r=>r.reduce((a,b)=>a+b,0));
  const colT=cols.map((_,j)=>data.reduce((s,r)=>s+r[j],0));
  const N=rowT.reduce((a,b)=>a+b,0);
  if(N===0) return{stat:0,df:0,p:1};
  let chi=0;
  data.forEach((r,i)=>r.forEach((v,j)=>{const e=rowT[i]*colT[j]/N;if(e>0)chi+=(v-e)**2/e;}));
  const df=(rows.length-1)*(cols.length-1);
  return{stat:chi,df,p:chiSqP(chi,df)};
}

function performCAT(){
  const cc=document.getElementById('continuityCorrection').checked;
  const {rows,cols,data}=currentData;
  const k=cols.length,scores=Array.from({length:k},(_,i)=>i+1);
  const N=data.flat().reduce((a,b)=>a+b,0);
  const nj=scores.map((_,j)=>data.reduce((s,r)=>s+r[j],0));
  const yj=data[0].slice();
  const xbar=nj.reduce((s,n,j)=>s+n*scores[j],0)/N;
  const num=yj.reduce((s,y,j)=>s+y*(scores[j]-xbar),0);
  const pbar=yj.reduce((a,b)=>a+b,0)/N;
  const varT=pbar*(1-pbar)*nj.reduce((s,n,j)=>s+n*(scores[j]-xbar)**2,0);
  const corr=cc?0.5:0;
  const Z=varT>0?(Math.abs(num)-corr)/Math.sqrt(varT)*(num<0?-1:1):0;
  const pTwo=2*(1-normalCDF(Math.abs(Z)));
  const pOne=1-normalCDF(Math.abs(Z));
  const chiTrend=Z*Z;
  const rowT=data.map(r=>r.reduce((a,b)=>a+b,0));
  const rowPct=data.map((r,i)=>r.map(v=>rowT[i]>0?(v/rowT[i]*100).toFixed(1):'0.0'));
  const colPct=data.map((r)=>r.map((v,j)=>nj[j]>0?(v/nj[j]*100).toFixed(1):'0.0'));
  const props=yj.map((y,j)=>nj[j]>0?(y/nj[j]*100).toFixed(1):'0.0');
  const fP=p=>p<0.001?'<0.001':p<0.01?p.toFixed(4):p.toFixed(6);
  const pTwoD=fP(pTwo),pOneD=fP(pOne);
  const sig=pTwo<0.05;
  const trend=Z>0.001?'Increasing':Z<-0.001?'Decreasing':'No trend';
  let interp='';
  if(pTwo<0.001) interp=`There is a <strong>highly significant</strong> trend in proportions across the ordered groups (two-sided p &lt; 0.001). `;
  else if(pTwo<0.01) interp=`There is a <strong>very significant</strong> trend in proportions across the ordered groups (two-sided p &lt; 0.01). `;
  else if(pTwo<0.05) interp=`There is a <strong>statistically significant</strong> trend in proportions across the ordered groups (two-sided p &lt; 0.05). `;
  else interp=`No statistically significant trend was detected across the ordered groups (two-sided p = ${pTwo.toFixed(4)}). `;
  if(pTwo<0.05) interp+=`The evidence supports an <strong>${trend.toLowerCase()}</strong> trend (Z = ${Z.toFixed(4)}, one-sided p = ${pOneD}).`;
  else interp+='This suggests no systematic relationship between the outcome and the ordered groups.';
  const impl=sig
    ?`Statistical evidence supports a ${trend.toLowerCase()} trend across groups. The signed Z-statistic (${Z.toFixed(4)}) indicates the direction. Consider effect size and clinical context.`
    :`No statistical evidence for a trend was found. The outcome variable does not show systematic change across ordered categories.`;
  const chiAssoc=pearsonChiSq();
  return{Z,chiTrend,pTwo,pOne,pTwoD,pOneD,sig,N,k,pbar,nj,yj,rowT,rowPct,colPct,props,labels:cols.slice(),trend,chiAssoc,interp,impl,cc};
}

function displayResults(r){
  const rs=document.getElementById('resultsSection');
  const pChiD=r.chiAssoc.p<0.001?'<0.001':r.chiAssoc.p.toFixed(6);
  const propRows=`
    <tr><td>Success Count</td>${r.yj.map(v=>`<td>${v}</td>`).join('')}</tr>
    <tr><td>Total Count</td>${r.nj.map(v=>`<td>${v}</td>`).join('')}</tr>
    <tr><td><strong>Success Proportion (%)</strong></td>${r.props.map(p=>`<td><strong>${p}%</strong></td>`).join('')}</tr>`;

  rs.innerHTML=`
    <div class="result-chips">
      <div class="chip c-brand"><div class="chip-lbl">Z-statistic (signed)</div><div class="chip-val v-brand">${r.Z.toFixed(4)}</div><div class="chip-sub">+ increasing / − decreasing</div></div>
      <div class="chip c-teal"><div class="chip-lbl">χ² trend (df=1)</div><div class="chip-val v-teal">${r.chiTrend.toFixed(4)}</div><div class="chip-sub">Linear trend = Z²</div></div>
      <div class="chip c-amber"><div class="chip-lbl">Two-sided P-value</div><div class="chip-val v-amber">${r.pTwoD}</div><div class="chip-sub">CATT (both directions)</div></div>
      <div class="chip c-violet"><div class="chip-lbl">One-sided P-value</div><div class="chip-val v-violet">${r.pOneD}</div><div class="chip-sub">Direction of observed trend</div></div>
      <div class="chip c-brand"><div class="chip-lbl">Sample Size</div><div class="chip-val">${r.N}</div><div class="chip-sub">${r.k} ordered groups</div></div>
      <div class="chip ${r.sig?'c-green':'c-rose'}"><div class="chip-lbl">Trend</div><div class="chip-val ${r.sig?'v-green':'v-rose'}">${r.sig?r.trend:'None'}</div><div class="chip-sub">${r.sig?'Significant at α=0.05':'Not significant'}</div></div>
    </div>

    <div class="sig-banner ${r.sig?'sig':'nsig'}">
      <div class="sig-icon"><i class="fas fa-${r.sig?'check':'times'}"></i></div>
      <div>
        <div class="sig-title">${r.sig?'Significant Trend Detected':'No Significant Trend'}</div>
        <div class="sig-text">${r.sig?`A statistically significant ${r.trend.toLowerCase()} trend was detected (Z = ${r.Z.toFixed(4)}, one-sided p = ${r.pOneD}, two-sided p = ${r.pTwoD}).`:`No significant trend detected (Z = ${r.Z.toFixed(4)}, one-sided p = ${r.pOneD}, two-sided p = ${r.pTwoD}).`}</div>
      </div>
    </div>

    <div class="pval-panel">
      <div class="pval-half">
        <div class="pval-half-lbl">One-sided P-value</div>
        <div class="pval-half-val">${r.pOneD}</div>
        <div class="pval-half-note">Tests trend in <strong>${r.trend.toLowerCase()}</strong> direction only.<br>Use when direction was pre-specified.</div>
      </div>
      <div class="pval-half">
        <div class="pval-half-lbl">Two-sided P-value</div>
        <div class="pval-half-val">${r.pTwoD}</div>
        <div class="pval-half-note">Tests any trend regardless of direction.<br>Recommended for exploratory analysis.</div>
      </div>
    </div>

    <div class="chi-panel">
      <div class="chi-panel-title"><i class="fas fa-compress-alt"></i> Pearson Chi-Square Test of Association</div>
      <div class="chi-row">
        <span class="chi-val">${r.chiAssoc.stat.toFixed(4)}</span>
        <span class="chi-meta">χ² (df = ${r.chiAssoc.df}) · p = ${pChiD}</span>
      </div>
      <div class="chi-note">Standard Pearson chi-square of general association — same formula as SPSS/R/SAS. Tests any association between row and column variables, not specifically a linear trend. df = (rows−1)×(cols−1) = ${r.chiAssoc.df}.</div>
    </div>

    <div class="interp-box">
      <div class="interp-title"><i class="fas fa-lightbulb"></i> Statistical Interpretation</div>
      <div class="interp-text">${r.interp}</div>
      <hr class="interp-divider">
      <div class="interp-impl"><strong>Practical implications:</strong> ${r.impl}</div>
    </div>

    <div class="prop-tbl-wrap">
      <div class="prop-tbl-header"><i class="fas fa-percent"></i> Success Proportions by Level</div>
      <table class="prop-tbl">
        <thead><tr><th>Metric</th>${r.labels.map(l=>`<th>${l}</th>`).join('')}</tr></thead>
        <tbody>${propRows}</tbody>
      </table>
    </div>

    <div class="panel" style="margin-bottom:22px;">
      <div class="panel-header"><div class="panel-title"><i class="fas fa-chart-bar"></i> Data Visualisation</div></div>
      <div class="panel-body">
        <div class="chart-bar">
          <div class="chart-bar-title">Frequency Distribution</div>
          <div class="chart-bar-btns">
            <button class="sm-btn" id="fsBtn"><i class="fas fa-expand"></i> Full Screen</button>
            <button class="sm-btn accent" id="dlChartBtn"><i class="fas fa-download"></i> PNG</button>
          </div>
        </div>
        <div class="chart-box" id="chartBox"><canvas id="analysisChart"></canvas></div>
        <div class="chart-hint"><i class="fas fa-hand-pointer"></i> Click chart to expand full-screen</div>
      </div>
    </div>

    <div class="panel" style="margin-bottom:22px;">
      <div class="panel-header"><div class="panel-title"><i class="fas fa-file-export"></i> Export Results</div></div>
      <div class="panel-body">
        <div class="export-grid">
          <div class="export-card">
            <div class="export-icon"><i class="fas fa-file-word"></i></div>
            <div class="export-title">Microsoft Word</div>
            <div class="export-desc">Complete report with tables, results, interpretation &amp; APA citation</div>
            <button class="export-btn" id="exportWordBtn"><i class="fas fa-download"></i> Export .doc</button>
          </div>
          <div class="export-card">
            <div class="export-icon" style="color:var(--emerald)"><i class="fas fa-file-excel"></i></div>
            <div class="export-title">Results CSV</div>
            <div class="export-desc">Data, statistical results, and interpretation in CSV format</div>
            <button class="export-btn" id="exportExcelBtn"><i class="fas fa-download"></i> Export .csv</button>
          </div>
          <div class="export-card">
            <div class="export-icon" style="color:var(--teal)"><i class="fas fa-file-csv"></i></div>
            <div class="export-title">Raw Data CSV</div>
            <div class="export-desc">Observation-level data: each row = one case, columns = Group and Outcome</div>
            <button class="export-btn" id="exportCsvBtn"><i class="fas fa-download"></i> Export .csv</button>
          </div>
        </div>
      </div>
    </div>

    <div class="panel" style="margin-bottom:22px;">
      <div class="panel-header"><div class="panel-title"><i class="fas fa-book"></i> Citation</div></div>
      <div class="panel-body">
        <p style="font-family:var(--font-serif);font-size:0.9rem;color:var(--text-3);margin-bottom:13px;font-style:italic;font-weight:500;">If you use CATrend Analyzer in your research, please cite it as:</p>
        <div class="citation-box">
          <button class="copy-cite-btn" id="copyCiteBtn"><i class="fas fa-copy"></i> Copy</button>
          Ibrahim, M. M. (2026). <em>CATrend Analyzer: Cochran–Armitage Trend Test Analysis Tool</em> [Computer software]. Retrieved from <a href="https://cochran-armitage.vercel.app/" target="_blank">https://cochran-armitage.vercel.app/</a>
        </div>
        <p style="font-family:var(--font-serif);font-size:0.79rem;color:var(--text-4);margin-top:11px;font-style:italic;font-weight:500;">Analysis performed using CATrend Analyzer v1.0. Z reported with sign (+ = increasing, − = decreasing). One-sided and two-sided p-values reported. Chi-square uses Pearson formula consistent with SPSS/R/SAS.</p>
      </div>
    </div>`;

  rs.classList.add('active');
  updateChart(r);
  bindResultListeners(r);
  setTimeout(()=>rs.scrollIntoView({behavior:'smooth',block:'start'}),100);
}

const PALETTE=[
  {bg:'rgba(7,87,186,0.72)',bd:'rgba(7,87,186,1)'},
  {bg:'rgba(159,18,57,0.72)',bd:'rgba(159,18,57,1)'},
  {bg:'rgba(10,102,128,0.72)',bd:'rgba(10,102,128,1)'},
  {bg:'rgba(133,77,14,0.72)',bd:'rgba(133,77,14,1)'}
];
function buildDatasets(r){
  const sC=document.getElementById('showCounts').checked;
  const sR=document.getElementById('showRowPercent').checked;
  const sCl=document.getElementById('showColPercent').checked;
  return currentData.rows.map((row,i)=>{
    const c=PALETTE[i%PALETTE.length];
    const dl=currentData.data[i].map((v,j)=>{
      let pts=[];
      if(sC) pts.push(v);
      if(sR) pts.push('('+r.rowPct[i][j]+'%)');
      if(sCl) pts.push('['+r.colPct[i][j]+'%]');
      return pts.join('\n')||String(v);
    });
    return{label:row,data:currentData.data[i],dataLabels:dl,backgroundColor:c.bg,borderColor:c.bd,borderWidth:1.5,borderRadius:5};
  });
}

function chartOpts(r,lg=false){
  const fs=lg?1.55:1;
  const dk=(document.documentElement.getAttribute('data-theme')||'light')==='dark';
  const tc=dk?'#b0bec8':'#374151';
  const gc=dk?'rgba(255,255,255,0.06)':'rgba(10,15,30,0.06)';
  const bg=dk?'#1c2128':'#f4f7fb';
  return{
    responsive:true,maintainAspectRatio:false,backgroundColor:bg,
    plugins:{
      title:{display:true,text:'Frequency Distribution',font:{size:14*fs,family:"'Nunito Sans',sans-serif",weight:'800'},color:dk?'#f0f6fc':'#0a0f1e',padding:{bottom:16*fs}},
      legend:{position:'top',labels:{font:{size:11*fs,family:"'Nunito Sans',sans-serif",weight:'700'},color:tc,padding:16*fs}},
      tooltip:{
        backgroundColor:dk?'#21262d':'#fff',
        borderColor:dk?'rgba(255,255,255,0.12)':'rgba(10,15,30,0.1)',
        borderWidth:1,padding:12*fs,
        titleFont:{size:12*fs,family:"'Nunito Sans',sans-serif",weight:'800'},
        bodyFont:{size:11*fs,family:"'Nunito Sans',sans-serif",weight:'600'},
        titleColor:dk?'#f0f6fc':'#0a0f1e',bodyColor:tc,
        callbacks:{label:ctx=>{
          let l=ctx.dataset.label+': '+ctx.parsed.y;
          if(document.getElementById('showRowPercent').checked) l+=' ('+r.rowPct[ctx.datasetIndex][ctx.dataIndex]+'% of row)';
          if(document.getElementById('showColPercent').checked) l+=' ['+r.colPct[ctx.datasetIndex][ctx.dataIndex]+'% of col]';
          return l;
        }}
      },
      datalabels:{display:true,color:'#fff',font:{weight:'700',size:10*fs,family:"'IBM Plex Mono',monospace"},
        formatter:(v,ctx)=>ctx.chart.data.datasets[ctx.datasetIndex].dataLabels?.[ctx.dataIndex]??v,
        anchor:'center',align:'center'}
    },
    scales:{
      x:{title:{display:true,text:'Groups',font:{size:11*fs,family:"'Nunito Sans'",weight:'700'},color:tc},grid:{color:gc},ticks:{color:tc,font:{size:10*fs,weight:'600'}}},
      y:{beginAtZero:true,title:{display:true,text:'Frequency',font:{size:11*fs,family:"'Nunito Sans'",weight:'700'},color:tc},grid:{color:gc},ticks:{precision:0,color:tc,font:{size:10*fs,weight:'600'}}}
    }
  };
}

function updateChart(r){
  const canvas=document.getElementById('analysisChart');
  if(!canvas) return;
  if(chartInst) chartInst.destroy();
  chartInst=new Chart(canvas.getContext('2d'),{type:'bar',data:{labels:r.labels,datasets:buildDatasets(r)},options:chartOpts(r)});
}

function bindResultListeners(r){
  document.getElementById('chartBox')?.addEventListener('click',()=>openFS(r));
  document.getElementById('fsBtn')?.addEventListener('click',()=>openFS(r));
  document.getElementById('dlChartBtn')?.addEventListener('click',()=>{ if(chartInst){const a=document.createElement('a');a.download='catrend-chart.png';a.href=chartInst.toBase64Image();a.click();} });
  document.getElementById('exportWordBtn')?.addEventListener('click',()=>exportWord(r));
  document.getElementById('exportExcelBtn')?.addEventListener('click',()=>exportExcel(r));
  document.getElementById('exportCsvBtn')?.addEventListener('click',()=>exportCSV(r));
  document.getElementById('copyCiteBtn')?.addEventListener('click',function(){
    navigator.clipboard?.writeText(`Ibrahim, M. M. (2026). CATrend Analyzer: Cochran–Armitage Trend Test Analysis Tool [Computer software]. Retrieved from https://cochran-armitage.vercel.app/`);
    this.innerHTML='<i class="fas fa-check"></i> Copied!';
    setTimeout(()=>{this.innerHTML='<i class="fas fa-copy"></i> Copy';},2000);
  });
}

function openFS(r){
  const m=document.getElementById('fsModal'); m.classList.add('open'); document.body.style.overflow='hidden';
  if(fsChartInst) fsChartInst.destroy();
  fsChartInst=new Chart(document.getElementById('fsChart').getContext('2d'),{type:'bar',data:{labels:r.labels,datasets:buildDatasets(r)},options:chartOpts(r,true)});
  fsZoom=1; document.getElementById('fsChart').style.transform='scale(1)';
  document.getElementById('fsClose').onclick=closeFS;
  document.getElementById('fsZoomIn').onclick=()=>{fsZoom=Math.min(3,fsZoom+0.1);document.getElementById('fsChart').style.transform=`scale(${fsZoom})`;};
  document.getElementById('fsZoomOut').onclick=()=>{fsZoom=Math.max(0.5,fsZoom-0.1);document.getElementById('fsChart').style.transform=`scale(${fsZoom})`;};
  document.getElementById('fsReset').onclick=()=>{fsZoom=1;document.getElementById('fsChart').style.transform='scale(1)';};
  document.getElementById('fsDl').onclick=()=>{ if(fsChartInst){const a=document.createElement('a');a.download='catrend-fullscreen.png';a.href=fsChartInst.toBase64Image();a.click();} };
}
function closeFS(){ document.getElementById('fsModal').classList.remove('open'); document.body.style.overflow=''; }
document.addEventListener('keydown',e=>{ if(e.key==='Escape') closeFS(); });

function exportWord(r){
  const pChiD=r.chiAssoc.p<0.001?'<0.001':r.chiAssoc.p.toFixed(6);
  let tbl=`<table border="1" cellpadding="9" style="border-collapse:collapse;width:100%;font-family:'Source Serif 4',Georgia,serif;font-size:10.5pt;"><tr style="background:#EEF3FB;"><th style="text-align:left;font-family:'Nunito Sans',sans-serif;"></th>${currentData.cols.map(c=>`<th style="text-align:center;font-family:'Nunito Sans',sans-serif;">${c}</th>`).join('')}<th style="text-align:center;font-family:'Nunito Sans',sans-serif;">Total</th><th style="text-align:center;font-family:'Nunito Sans',sans-serif;">Row%</th></tr>`;
  currentData.rows.forEach((row,i)=>{const rt=currentData.data[i].reduce((a,b)=>a+b,0);tbl+=`<tr><th style="text-align:left;background:#F6F8FA;font-family:'Nunito Sans',sans-serif;">${row}</th>${currentData.data[i].map(v=>`<td style="text-align:center;font-family:'IBM Plex Mono',monospace;">${v}</td>`).join('')}<td style="text-align:center;font-weight:bold;font-family:'IBM Plex Mono',monospace;">${rt}</td><td style="text-align:center;font-family:'IBM Plex Mono',monospace;">${r.N>0?(rt/r.N*100).toFixed(1):0}%</td></tr>`;});
  tbl+=`<tr style="background:#EEF3FB;"><th style="font-family:'Nunito Sans',sans-serif;">Total</th>${r.nj.map(v=>`<td style="text-align:center;font-weight:bold;font-family:'IBM Plex Mono',monospace;">${v}</td>`).join('')}<td style="text-align:center;font-weight:bold;font-family:'IBM Plex Mono',monospace;">${r.N}</td><td style="text-align:center;font-family:'IBM Plex Mono',monospace;">100%</td></tr></table>`;
  const html=`<!DOCTYPE html><html><head><meta charset="UTF-8"><title>CATrend Analyzer — CATT Report</title>
  <style>body{font-family:'Source Serif 4',Georgia,serif;margin:52px;color:#0a0f1e;font-size:11pt;line-height:1.75;}h1{color:#0757ba;font-size:20pt;font-family:'Nunito Sans',sans-serif;font-weight:900;margin-bottom:5pt;}h2{color:#054699;font-size:13pt;font-family:'Nunito Sans',sans-serif;font-weight:800;margin-top:22pt;margin-bottom:5pt;border-bottom:2px solid #c8d0db;padding-bottom:3pt;}table{border-collapse:collapse;width:100%;margin:9pt 0;}th,td{border:1px solid #c8d0db;padding:7pt;text-align:center;}th{background:#F0F3F7;font-family:'Nunito Sans',sans-serif;font-weight:800;}.mono{font-family:'IBM Plex Mono','Courier New',monospace;}.interp{background:#EEF3FB;border-left:4px solid #0757ba;padding:12pt 16pt;margin:11pt 0;border-radius:5pt;font-family:'Source Serif 4',Georgia,serif;}.impl{background:#F0FFF6;border-left:4px solid #166534;padding:12pt 16pt;margin:11pt 0;border-radius:5pt;}.sig-y{color:#166534;font-weight:bold;}.sig-n{color:#9f1239;font-weight:bold;}.meta{font-size:8.5pt;color:#374151;margin-top:16pt;font-style:italic;}.citation{background:#F6F8FA;border:1px solid #c8d0db;padding:11pt;border-radius:5pt;font-style:italic;margin:7pt 0;}</style></head><body>
  <h1>📊 CATrend Analyzer — Cochran–Armitage Trend Test Report</h1>
  <p style="color:#374151;font-size:9pt;font-family:'Nunito Sans',sans-serif;"><strong>Generated:</strong> ${new Date().toLocaleString()} &nbsp;|&nbsp; <strong>Software:</strong> CATrend Analyzer v1.0 &nbsp;|&nbsp; <strong>URL:</strong> https://cochran-armitage.vercel.app/</p>
  <h2>1. Contingency Table</h2>${tbl}
  <h2>2. Statistical Results</h2>
  <table><tr><th style="text-align:left;">Statistic</th><th>Value</th><th>Interpretation</th></tr>
  <tr><td style="text-align:left;">Z-statistic (signed)</td><td class="mono">${r.Z.toFixed(4)}</td><td>${r.Z>0?'Positive = increasing trend':'Negative = decreasing trend'}</td></tr>
  <tr><td style="text-align:left;">χ² trend (df=1) = Z²</td><td class="mono">${r.chiTrend.toFixed(4)}</td><td>Linear trend component</td></tr>
  <tr><td style="text-align:left;">One-sided P-value (CATT)</td><td class="mono">${r.pOneD}</td><td>Tail in direction of observed trend (${r.trend.toLowerCase()})</td></tr>
  <tr><td style="text-align:left;">Two-sided P-value (CATT)</td><td class="mono">${r.pTwoD}</td><td class="${r.sig?'sig-y':'sig-n'}">${r.sig?'Statistically significant':'Not significant'} (α=0.05)</td></tr>
  <tr><td style="text-align:left;">Pearson χ² (df=${r.chiAssoc.df})</td><td class="mono">${r.chiAssoc.stat.toFixed(4)}</td><td>General association (SPSS/R/SAS compatible)</td></tr>
  <tr><td style="text-align:left;">P-value (association)</td><td class="mono">${pChiD}</td><td>Based on χ² distribution, df=${r.chiAssoc.df}</td></tr>
  <tr><td style="text-align:left;">Sample Size (N)</td><td class="mono">${r.N}</td><td>${r.k} ordered groups</td></tr>
  <tr><td style="text-align:left;">Trend direction</td><td>${r.trend}</td><td>${r.sig?'Significant trend detected':'No significant trend'}</td></tr>
  <tr><td style="text-align:left;">Continuity correction</td><td>${r.cc?'Yes (applied)':'No (not applied)'}</td><td></td></tr></table>
  <h2>3. Statistical Interpretation</h2>
  <div class="interp"><p>${r.interp.replace(/<\/?strong>/g,'')}</p></div>
  <h2>4. Practical Implications</h2>
  <div class="impl"><p>${r.impl}</p></div>
  <h2>5. Reporting Template</h2>
  <p>The Cochran–Armitage Trend Test was conducted to examine the presence of a linear trend in proportions across ${r.k} ordered groups (N = ${r.N}). Results indicated ${r.sig?`a statistically significant ${r.trend.toLowerCase()} trend`:'no statistically significant trend'} (Z = ${r.Z.toFixed(4)}, one-sided p ${r.pOneD}, two-sided p ${r.pTwoD}). The Pearson chi-square test of general association yielded χ²(${r.chiAssoc.df}) = ${r.chiAssoc.stat.toFixed(4)}, p = ${pChiD}. ${r.cc?'A continuity correction was applied.':'No continuity correction was applied.'}</p>
  <h2>6. Citation</h2>
  <div class="citation">Ibrahim, M. M. (2026). <em>CATrend Analyzer: Cochran–Armitage Trend Test Analysis Tool</em> [Computer software]. Retrieved from https://cochran-armitage.vercel.app/</div>
  <p class="meta">Analysis performed using CATrend Analyzer v1.0. Z reported with sign (+ = increasing, − = decreasing). Pearson chi-square uses standard formula consistent with SPSS, R, and SAS.</p>
  </body></html>`;
  const blob=new Blob([html],{type:'application/msword'});
  const a=document.createElement('a');a.href=URL.createObjectURL(blob);a.download=`CATT-Report-${new Date().toISOString().slice(0,10)}.doc`;a.click();
}

function exportExcel(r){
  const pChiD=r.chiAssoc.p<0.001?'<0.001':r.chiAssoc.p.toFixed(6);
  let csv=`CATrend Analyzer - Cochran-Armitage Trend Test Analysis Report\n`;
  csv+=`Generated:,${new Date().toLocaleString()}\nSoftware:,CATrend Analyzer v1.0\nURL:,https://cochran-armitage.vercel.app/\n\n`;
  csv+=`CONTINGENCY TABLE\n,${currentData.cols.join(',')},Total,Row%\n`;
  currentData.rows.forEach((row,i)=>{const rt=currentData.data[i].reduce((a,b)=>a+b,0);csv+=`"${row}",${currentData.data[i].join(',')},${rt},${r.N>0?(rt/r.N*100).toFixed(1):0}%\n`;});
  csv+=`Total,${r.nj.join(',')},${r.N},100%\n\n`;
  csv+=`STATISTICAL RESULTS\nStatistic,Value,Note\n`;
  csv+=`Z-statistic (signed),${r.Z.toFixed(4)},+ = increasing / - = decreasing\n`;
  csv+=`Chi-square trend (df=1),${r.chiTrend.toFixed(4)},Linear trend = Z squared\n`;
  csv+=`One-sided P-value (CATT),${r.pOneD},Tail in ${r.trend.toLowerCase()} direction\n`;
  csv+=`Two-sided P-value (CATT),${r.pTwoD},${r.sig?'SIGNIFICANT at alpha=0.05':'Not significant at alpha=0.05'}\n`;
  csv+=`Pearson chi-square (df=${r.chiAssoc.df}),${r.chiAssoc.stat.toFixed(4)},General association (SPSS/R/SAS compatible)\n`;
  csv+=`P-value (association),${pChiD},Based on chi-square distribution df=${r.chiAssoc.df}\n`;
  csv+=`Sample Size (N),${r.N},\nGroups (k),${r.k},\nTrend Direction,${r.trend},\nContinuity Correction,${r.cc?'Yes':'No'},\n\n`;
  csv+=`INTERPRETATION\n"${r.interp.replace(/<\/?strong>/g,'').replace(/&lt;/g,'<')}"\n\n`;
  csv+=`CITATION\n"Ibrahim, M. M. (2026). CATrend Analyzer [Computer software]. Retrieved from https://cochran-armitage.vercel.app/"\n`;
  const blob=new Blob([csv],{type:'text/csv;charset=utf-8;'});
  const a=document.createElement('a');a.href=URL.createObjectURL(blob);a.download=`CATT-Analysis-${new Date().toISOString().slice(0,10)}.csv`;a.click();
}

function exportCSV(r){
  const {rows,cols,data}=currentData;
  let csv=`Observation,Group,Outcome\n`;
  let n=1;
  cols.forEach((col,j)=>{
    rows.forEach((rowLabel,i)=>{
      const count=data[i][j];
      for(let k=0;k<count;k++){csv+=`${n},"${col}","${rowLabel}"\n`;n++;}
    });
  });
  const blob=new Blob([csv],{type:'text/csv;charset=utf-8;'});
  const a=document.createElement('a');a.href=URL.createObjectURL(blob);a.download=`CATT-RawData-${new Date().toISOString().slice(0,10)}.csv`;a.click();
}
</script>
</body>
</html>
