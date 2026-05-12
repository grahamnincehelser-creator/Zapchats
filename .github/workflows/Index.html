<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0, viewport-fit=cover">
<meta name="theme-color" content="#0d0d18">
<meta name="apple-mobile-web-app-capable" content="yes">
<meta name="apple-mobile-web-app-status-bar-style" content="black-translucent">
<meta name="apple-mobile-web-app-title" content="ZapChat">
<title>ZapChat</title>
<link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@400;500;600;700;800&family=Space+Grotesk:wght@700&display=swap" rel="stylesheet">
<style>
:root{
  --bg:#0d0d18;--surface:#16162a;--surface2:#1e1e38;--surface3:#252545;
  --border:rgba(255,255,255,0.07);--border2:rgba(255,255,255,0.12);
  --p:#a78bfa;--p2:#7c3aed;--pk:#f472b6;--cy:#22d3ee;--gr:#34d399;
  --text:#ede9fe;--text2:#a09ac0;--text3:#6b6490;--danger:#f87171;
  --safe:env(safe-area-inset-bottom,0px);
}
*{box-sizing:border-box;margin:0;padding:0;-webkit-tap-highlight-color:transparent;}
html,body{height:100%;overflow:hidden;}
body{font-family:'Plus Jakarta Sans',sans-serif;background:var(--bg);color:var(--text);height:100dvh;display:flex;flex-direction:column;}

/* glow */
.glow{position:fixed;inset:0;pointer-events:none;z-index:0;overflow:hidden;}
.glow span{position:absolute;border-radius:50%;filter:blur(90px);}
.glow span:nth-child(1){width:500px;height:500px;background:rgba(124,58,237,0.14);top:-120px;left:-80px;animation:g1 14s ease-in-out infinite alternate;}
.glow span:nth-child(2){width:400px;height:400px;background:rgba(244,114,182,0.09);bottom:-80px;right:-60px;animation:g2 11s ease-in-out infinite alternate;}
@keyframes g1{from{transform:translate(0,0)}to{transform:translate(70px,90px)}}
@keyframes g2{from{transform:translate(0,0)}to{transform:translate(-60px,-50px)}}

/* screens */
.screen{position:absolute;inset:0;display:flex;flex-direction:column;z-index:1;transition:opacity .2s,transform .2s;}
.screen.hidden{opacity:0;pointer-events:none;transform:translateY(10px);}

/* ── AUTH ── */
#s-auth{align-items:center;justify-content:center;padding:20px;gap:0;}
.brand{display:flex;align-items:center;gap:12px;margin-bottom:8px;animation:pop .6s cubic-bezier(.34,1.56,.64,1) both;}
.b-icon{width:52px;height:52px;border-radius:16px;background:linear-gradient(135deg,var(--p2),var(--pk));display:flex;align-items:center;justify-content:center;font-size:26px;box-shadow:0 8px 28px rgba(124,58,237,.5);}
.b-name{font-family:'Space Grotesk',sans-serif;font-size:40px;font-weight:700;letter-spacing:-2px;background:linear-gradient(135deg,#c4b5fd,#f9a8d4,#67e8f9);-webkit-background-clip:text;-webkit-text-fill-color:transparent;background-clip:text;}
.tagline{font-size:14px;color:var(--text2);margin-bottom:28px;animation:up .5s .1s both;}
@keyframes pop{from{opacity:0;transform:scale(.7)}to{opacity:1;transform:none}}
@keyframes up{from{opacity:0;transform:translateY(10px)}to{opacity:1;transform:none}}

.card{background:var(--surface);border:1px solid var(--border2);border-radius:26px;padding:26px 22px;width:100%;max-width:370px;box-shadow:0 20px 60px rgba(0,0,0,.45);animation:up .5s .2s both;}
.tabs{display:flex;background:var(--surface2);border-radius:12px;padding:3px;margin-bottom:20px;gap:3px;}
.tab{flex:1;padding:8px;border-radius:10px;border:none;background:none;color:var(--text3);font-family:'Plus Jakarta Sans',sans-serif;font-size:14px;font-weight:600;cursor:pointer;transition:all .2s;}
.tab.on{background:var(--surface3);color:var(--text);}
.field{margin-bottom:13px;}
.field label{display:block;font-size:10px;font-weight:700;letter-spacing:1px;text-transform:uppercase;color:var(--text3);margin-bottom:6px;}
.inp{width:100%;background:var(--surface2);border:1.5px solid var(--border2);border-radius:13px;color:var(--text);font-family:'Plus Jakarta Sans',sans-serif;font-size:15px;padding:12px 15px;outline:none;transition:border-color .2s,box-shadow .2s;}
.inp:focus{border-color:var(--p);box-shadow:0 0 0 3px rgba(167,139,250,.16);}
.inp::placeholder{color:var(--text3);}
.err{font-size:12px;color:var(--danger);min-height:18px;padding:2px 2px 8px;font-weight:500;line-height:1.4;}
.btn-main{width:100%;padding:13px;border-radius:14px;border:none;font-family:'Plus Jakarta Sans',sans-serif;font-size:15px;font-weight:700;cursor:pointer;background:linear-gradient(135deg,var(--p2),var(--pk));color:#fff;box-shadow:0 6px 20px rgba(124,58,237,.35);transition:transform .15s,box-shadow .2s,opacity .15s;}
.btn-main:not(:disabled):hover{transform:translateY(-2px);box-shadow:0 10px 28px rgba(124,58,237,.5);}
.btn-main:active{transform:scale(.97);}
.btn-main:disabled{opacity:.55;cursor:not-allowed;}

.hint{margin-top:16px;padding:12px 14px;background:rgba(34,211,238,.07);border:1px solid rgba(34,211,238,.15);border-radius:12px;font-size:12px;color:var(--cy);line-height:1.6;text-align:center;max-width:370px;animation:up .5s .35s both;}

/* ── APP ── */
#s-app{flex-direction:row;}

/* sidebar */
.sb{width:290px;min-width:250px;background:var(--surface);border-right:1px solid var(--border);display:flex;flex-direction:column;flex-shrink:0;z-index:2;}
@media(max-width:680px){
  .sb{position:absolute;inset:0;width:100%;z-index:10;transition:transform .28s cubic-bezier(.4,0,.2,1);}
  .sb.out{transform:translateX(-100%);}
  .cmain{width:100%;}
}
.sb-top{padding:16px 16px 13px;border-bottom:1px solid var(--border);flex-shrink:0;}
.sb-logo{display:flex;align-items:center;gap:9px;margin-bottom:13px;}
.sb-logo-icon{width:32px;height:32px;border-radius:9px;background:linear-gradient(135deg,var(--p2),var(--pk));display:flex;align-items:center;justify-content:center;font-size:16px;}
.sb-logo-text{font-family:'Space Grotesk',sans-serif;font-size:20px;font-weight:700;letter-spacing:-1px;background:linear-gradient(135deg,#c4b5fd,#f9a8d4);-webkit-background-clip:text;-webkit-text-fill-color:transparent;background-clip:text;}
.me-row{display:flex;align-items:center;gap:9px;background:var(--surface2);border-radius:13px;padding:9px 11px;cursor:pointer;}
.me-row:hover{background:var(--surface3);}
.av{border-radius:50%;display:flex;align-items:center;justify-content:center;font-weight:700;color:#fff;flex-shrink:0;}
.me-av{width:32px;height:32px;font-size:12px;}
.me-info strong{display:block;font-size:13px;font-weight:600;}
.me-info small{font-size:11px;color:var(--text3);}
.online{width:7px;height:7px;border-radius:50%;background:var(--gr);box-shadow:0 0 6px var(--gr);margin-left:auto;flex-shrink:0;}

.sb-label{display:flex;align-items:center;justify-content:space-between;padding:13px 16px 5px;font-size:10px;font-weight:700;letter-spacing:1.5px;text-transform:uppercase;color:var(--text3);}
.sb-label button{background:linear-gradient(135deg,var(--p2),var(--pk));border:none;color:#fff;border-radius:7px;padding:3px 9px;font-size:12px;font-weight:600;font-family:'Plus Jakarta Sans',sans-serif;cursor:pointer;transition:transform .15s;}
.sb-label button:hover{transform:scale(1.06);}

.clist{flex:1;overflow-y:auto;padding:5px 9px 9px;}
.clist::-webkit-scrollbar{width:3px;}
.clist::-webkit-scrollbar-thumb{background:var(--border2);border-radius:99px;}
.ci{display:flex;align-items:center;gap:10px;padding:10px 11px;border-radius:14px;cursor:pointer;transition:background .15s;border:1.5px solid transparent;position:relative;}
.ci:hover{background:var(--surface2);}
.ci.on{background:rgba(124,58,237,.12);border-color:rgba(167,139,250,.2);}
.ci-av{width:42px;height:42px;font-size:14px;}
.ci-av.grp{border-radius:13px;font-size:17px;}
.ci-info{flex:1;min-width:0;}
.ci-info strong{display:block;font-size:13px;font-weight:600;white-space:nowrap;overflow:hidden;text-overflow:ellipsis;}
.ci-info span{font-size:11px;color:var(--text3);white-space:nowrap;overflow:hidden;text-overflow:ellipsis;display:block;margin-top:1px;}
.ci-meta{display:flex;flex-direction:column;align-items:flex-end;gap:3px;flex-shrink:0;}
.ci-t{font-size:10px;color:var(--text3);}
.ci-u{width:19px;height:19px;border-radius:50%;background:linear-gradient(135deg,var(--p),var(--pk));color:#fff;font-size:10px;font-weight:700;display:flex;align-items:center;justify-content:center;}
.ci-x{position:absolute;right:7px;top:50%;transform:translateY(-50%);width:26px;height:26px;border-radius:50%;border:none;background:none;color:var(--text3);cursor:pointer;font-size:17px;display:none;align-items:center;justify-content:center;}
.ci:hover .ci-x{display:flex;}
.ci-x:hover{background:rgba(248,113,113,.15);color:var(--danger);}

.empty{padding:28px 16px;text-align:center;color:var(--text3);display:flex;flex-direction:column;align-items:center;gap:8px;}
.empty-icon{font-size:36px;opacity:.45;}
.empty p{font-size:13px;line-height:1.6;}

.sb-bot{padding:12px;border-top:1px solid var(--border);flex-shrink:0;}
.btn-out{width:100%;padding:9px;border-radius:12px;border:1px solid var(--border2);background:transparent;color:var(--text3);font-family:'Plus Jakarta Sans',sans-serif;font-size:13px;cursor:pointer;transition:all .2s;}
.btn-out:hover{color:var(--danger);border-color:rgba(248,113,113,.3);background:rgba(248,113,113,.06);}

/* chat main */
.cmain{flex:1;display:flex;flex-direction:column;overflow:hidden;min-width:0;}
.nochat{flex:1;display:flex;flex-direction:column;align-items:center;justify-content:center;gap:12px;color:var(--text2);padding:32px;text-align:center;}
.nochat-icon{font-size:48px;animation:float 3s ease-in-out infinite;}
@keyframes float{0%,100%{transform:translateY(0)}50%{transform:translateY(-9px)}}
.nochat h3{font-size:20px;font-weight:700;font-family:'Space Grotesk',sans-serif;}
.nochat p{font-size:14px;color:var(--text3);max-width:240px;line-height:1.6;}
.btn-nc{margin-top:6px;padding:11px 24px;border-radius:13px;border:none;background:linear-gradient(135deg,var(--p2),var(--pk));color:#fff;font-family:'Plus Jakarta Sans',sans-serif;font-size:14px;font-weight:700;cursor:pointer;transition:transform .15s,box-shadow .2s;}
.btn-nc:hover{transform:translateY(-2px);box-shadow:0 8px 22px rgba(124,58,237,.4);}

/* chat header */
.chdr{display:flex;align-items:center;gap:11px;padding:13px 18px;border-bottom:1px solid var(--border);background:rgba(13,13,24,.88);backdrop-filter:blur(16px);flex-shrink:0;z-index:1;}
.hdr-back{display:none;width:34px;height:34px;border-radius:50%;border:none;background:var(--surface2);color:var(--text2);font-size:20px;cursor:pointer;align-items:center;justify-content:center;flex-shrink:0;}
@media(max-width:680px){.hdr-back{display:flex;}}
.hdr-back:hover{background:var(--surface3);}
.hdr-av{width:36px;height:36px;font-size:13px;}
.hdr-av.grp{border-radius:11px;font-size:17px;}
.hdr-info h2{font-size:15px;font-weight:700;}
.hdr-info p{font-size:11px;color:var(--text3);margin-top:1px;}
.hdr-btns{margin-left:auto;display:flex;gap:7px;}
.hdr-btn{width:34px;height:34px;border-radius:50%;border:none;background:var(--surface2);color:var(--text2);font-size:15px;cursor:pointer;display:flex;align-items:center;justify-content:center;transition:background .15s;}
.hdr-btn:hover{background:var(--surface3);color:var(--text);}

/* messages */
.msgs{flex:1;overflow-y:auto;padding:14px 14px 6px;display:flex;flex-direction:column;gap:8px;}
.msgs::-webkit-scrollbar{width:3px;}
.msgs::-webkit-scrollbar-thumb{background:rgba(167,139,250,.2);border-radius:99px;}
.mrow{display:flex;align-items:flex-end;gap:7px;}
.mrow.me{flex-direction:row-reverse;}
.mav{width:24px;height:24px;font-size:9px;}
.mbody{max-width:74%;display:flex;flex-direction:column;gap:2px;}
.mrow.me .mbody{align-items:flex-end;}
.msender{font-size:10px;color:var(--text3);padding:0 3px;}
.mbub{padding:9px 13px;border-radius:17px;font-size:14px;line-height:1.55;word-break:break-word;}
.mrow.me .mbub{background:linear-gradient(135deg,var(--p2),var(--p));color:#fff;border-bottom-right-radius:3px;}
.mrow:not(.me) .mbub{background:var(--surface2);color:var(--text);border:1px solid var(--border2);border-bottom-left-radius:3px;}
.mimg{padding:3px;border-radius:17px;overflow:hidden;max-width:240px;}
.mimg img{width:100%;max-width:240px;border-radius:13px;display:block;cursor:pointer;}
.mrow.me .mimg{background:linear-gradient(135deg,var(--p2),var(--p));border-bottom-right-radius:3px;}
.mrow:not(.me) .mimg{background:var(--surface2);border:1px solid var(--border2);border-bottom-left-radius:3px;}
.mtime{font-size:10px;color:var(--text3);padding:0 3px;}
.msys{text-align:center;font-size:12px;color:var(--text3);padding:6px;}
.mrow.me .mbub,.mrow.me .mimg{animation:sr .2s cubic-bezier(.34,1.3,.64,1) both;}
.mrow:not(.me) .mbub,.mrow:not(.me) .mimg{animation:sl .2s cubic-bezier(.34,1.3,.64,1) both;}
@keyframes sr{from{opacity:0;transform:translateX(10px) scale(.95)}to{opacity:1;transform:none}}
@keyframes sl{from{opacity:0;transform:translateX(-10px) scale(.95)}to{opacity:1;transform:none}}
.ddiv{display:flex;align-items:center;gap:9px;font-size:11px;color:var(--text3);padding:3px 0;}
.ddiv::before,.ddiv::after{content:'';flex:1;height:1px;background:var(--border);}

/* input */
.iarea{padding:9px 11px calc(9px + var(--safe)) 11px;border-top:1px solid var(--border);background:rgba(13,13,24,.92);backdrop-filter:blur(16px);flex-shrink:0;}
.emojis{display:flex;gap:3px;margin-bottom:7px;overflow-x:auto;scrollbar-width:none;}
.emojis::-webkit-scrollbar{display:none;}
.emj{min-width:28px;height:28px;border-radius:7px;border:none;background:var(--surface2);cursor:pointer;font-size:14px;display:flex;align-items:center;justify-content:center;flex-shrink:0;transition:transform .15s;}
.emj:hover{transform:scale(1.18);}
.irow{display:flex;gap:7px;align-items:flex-end;}
.mta{flex:1;background:var(--surface2);border:1.5px solid var(--border2);border-radius:16px;color:var(--text);font-family:'Plus Jakarta Sans',sans-serif;font-size:14px;padding:10px 14px;outline:none;resize:none;min-height:42px;max-height:120px;line-height:1.5;overflow-y:auto;transition:border-color .2s;}
.mta:focus{border-color:var(--p);box-shadow:0 0 0 3px rgba(167,139,250,.1);}
.mta::placeholder{color:var(--text3);}
.ibtns{display:flex;gap:5px;align-items:flex-end;flex-shrink:0;}
.imgbtn{width:42px;height:42px;border-radius:50%;border:1.5px solid var(--border2);background:var(--surface2);display:flex;align-items:center;justify-content:center;font-size:18px;cursor:pointer;transition:transform .15s;}
.imgbtn:hover{transform:scale(1.08);}
.sendbtn{width:42px;height:42px;border-radius:50%;border:none;cursor:pointer;background:linear-gradient(135deg,var(--p2),var(--pk));display:flex;align-items:center;justify-content:center;flex-shrink:0;box-shadow:0 4px 12px rgba(124,58,237,.35);transition:transform .15s,box-shadow .2s;}
.sendbtn:hover{transform:scale(1.1);}
.sendbtn:active{transform:scale(.92);}
.sendbtn svg{width:17px;height:17px;fill:#fff;}
.prevwrap{display:none;position:relative;margin-bottom:7px;width:fit-content;}
.prevwrap img{max-height:90px;max-width:180px;border-radius:11px;display:block;border:1.5px solid var(--border2);}
.prevx{position:absolute;top:-7px;right:-7px;width:20px;height:20px;border-radius:50%;border:none;background:var(--danger);color:#fff;font-size:13px;cursor:pointer;display:flex;align-items:center;justify-content:center;font-weight:700;}

/* lightbox */
.lbox{position:fixed;inset:0;background:rgba(0,0,0,.93);z-index:999;display:flex;align-items:center;justify-content:center;cursor:pointer;backdrop-filter:blur(8px);}
.lbox.hidden{display:none;}
.lbox img{max-width:95vw;max-height:90vh;border-radius:11px;object-fit:contain;}

/* modal */
.overlay{position:fixed;inset:0;background:rgba(0,0,0,.72);z-index:100;display:flex;align-items:flex-end;justify-content:center;backdrop-filter:blur(6px);padding:14px;transition:opacity .2s;}
.overlay.hidden{opacity:0;pointer-events:none;}
@media(min-width:480px){.overlay{align-items:center;}}
.modal{background:var(--surface);border:1px solid var(--border2);border-radius:26px;padding:22px;width:100%;max-width:400px;animation:shup .28s cubic-bezier(.34,1.2,.64,1) both;max-height:88vh;overflow-y:auto;}
@keyframes shup{from{opacity:0;transform:translateY(36px)}to{opacity:1;transform:none}}
.modal h3{font-family:'Space Grotesk',sans-serif;font-size:19px;font-weight:700;margin-bottom:5px;}
.modal .msub{font-size:13px;color:var(--text3);margin-bottom:18px;line-height:1.5;}
.modal .field{margin-bottom:13px;}
.modal .field label{display:block;font-size:10px;font-weight:700;letter-spacing:1px;text-transform:uppercase;color:var(--text3);margin-bottom:6px;}
.modal .inp{width:100%;background:var(--surface2);border:1.5px solid var(--border2);border-radius:12px;color:var(--text);font-family:'Plus Jakarta Sans',sans-serif;font-size:14px;padding:10px 13px;outline:none;transition:border-color .2s;}
.modal .inp:focus{border-color:var(--p);box-shadow:0 0 0 3px rgba(167,139,250,.13);}
.merr{font-size:12px;color:var(--danger);min-height:16px;padding:2px 2px 0;}
.mbtns{display:flex;gap:9px;margin-top:16px;}
.mbtn{flex:1;padding:11px;border-radius:13px;border:none;cursor:pointer;font-family:'Plus Jakarta Sans',sans-serif;font-size:14px;font-weight:600;transition:all .15s;}
.mbtn:disabled{opacity:.55;cursor:not-allowed;}
.mbtn.ok{background:linear-gradient(135deg,var(--p2),var(--pk));color:#fff;}
.mbtn.ok:not(:disabled):hover{transform:translateY(-1px);box-shadow:0 6px 16px rgba(124,58,237,.4);}
.mbtn.cl{background:var(--surface2);color:var(--text2);border:1px solid var(--border2);}
.mbtn.cl:hover{color:var(--text);}

/* tag input */
.tagwrap{background:var(--surface2);border:1.5px solid var(--border2);border-radius:12px;padding:7px 9px;display:flex;flex-wrap:wrap;gap:5px;cursor:text;min-height:46px;transition:border-color .2s;}
.tagwrap:focus-within{border-color:var(--p);box-shadow:0 0 0 3px rgba(167,139,250,.13);}
.tag{display:flex;align-items:center;gap:4px;background:rgba(167,139,250,.15);border:1px solid rgba(167,139,250,.25);border-radius:99px;padding:2px 9px 2px 11px;font-size:12px;color:var(--p);font-weight:500;}
.tag button{background:none;border:none;color:rgba(167,139,250,.6);cursor:pointer;font-size:14px;line-height:1;padding:0 1px;}
.tag button:hover{color:var(--danger);}
.taginp{background:none;border:none;color:var(--text);outline:none;font-family:'Plus Jakarta Sans',sans-serif;font-size:13px;min-width:90px;flex:1;padding:2px 3px;}
.taginp::placeholder{color:var(--text3);}
.taghint{font-size:11px;color:var(--text3);margin-top:4px;}

/* members */
.mems{display:flex;flex-wrap:wrap;gap:7px;margin-top:9px;}
.memchip{display:flex;align-items:center;gap:5px;background:var(--surface2);border:1px solid var(--border2);border-radius:99px;padding:4px 11px;font-size:12px;color:var(--text2);}
.memav{width:18px;height:18px;border-radius:50%;display:flex;align-items:center;justify-content:center;font-size:8px;font-weight:700;color:#fff;}

/* toast */
.toast{position:fixed;bottom:calc(18px + var(--safe));left:50%;transform:translateX(-50%);background:var(--surface);border:1px solid var(--border2);border-radius:13px;padding:10px 18px;font-size:13px;color:var(--text2);box-shadow:0 8px 28px rgba(0,0,0,.5);z-index:998;white-space:nowrap;pointer-events:none;animation:up .3s both;}
.toast.hidden{display:none;}

/* spinner */
.spin{display:inline-block;width:14px;height:14px;border:2px solid rgba(255,255,255,.25);border-top-color:#fff;border-radius:50%;animation:spinning .6s linear infinite;vertical-align:middle;margin-right:6px;}
@keyframes spinning{to{transform:rotate(360deg)}}
/* captcha */
.captcha-box{background:var(--surface2);border:1.5px solid var(--border2);border-radius:13px;padding:13px 15px;display:flex;align-items:center;gap:12px;margin-bottom:13px;}
.captcha-q{font-size:15px;font-weight:700;color:var(--text);flex:1;}
.captcha-inp{width:70px;background:var(--surface3);border:1.5px solid var(--border2);border-radius:10px;color:var(--text);font-family:'Plus Jakarta Sans',sans-serif;font-size:15px;font-weight:700;padding:8px 10px;outline:none;text-align:center;transition:border-color .2s;}
.captcha-inp:focus{border-color:var(--p);}
.captcha-refresh{width:30px;height:30px;border-radius:50%;border:none;background:var(--surface3);color:var(--text3);cursor:pointer;font-size:16px;display:flex;align-items:center;justify-content:center;transition:transform .2s;}
.captcha-refresh:hover{transform:rotate(180deg);color:var(--p);}
/* parental overlay */
.pc-overlay{position:fixed;inset:0;background:rgba(0,0,0,.85);z-index:500;display:flex;align-items:center;justify-content:center;padding:20px;backdrop-filter:blur(10px);}
.pc-overlay.hidden{display:none;}
.pc-panel{background:var(--surface);border:1px solid var(--border2);border-radius:26px;padding:26px 22px;width:100%;max-width:400px;max-height:90vh;overflow-y:auto;}
.pc-panel h2{font-family:'Space Grotesk',sans-serif;font-size:22px;font-weight:700;margin-bottom:4px;display:flex;align-items:center;gap:10px;}
.pc-panel .pc-sub{font-size:13px;color:var(--text3);margin-bottom:20px;}
.pc-section{background:var(--surface2);border-radius:16px;padding:16px;margin-bottom:14px;}
.pc-section h4{font-size:12px;font-weight:700;letter-spacing:1px;text-transform:uppercase;color:var(--text3);margin-bottom:12px;}
.pc-user-row{display:flex;align-items:center;gap:10px;padding:8px 0;border-bottom:1px solid var(--border);}
.pc-user-row:last-child{border-bottom:none;}
.pc-user-av{width:32px;height:32px;border-radius:50%;display:flex;align-items:center;justify-content:center;font-size:11px;font-weight:700;color:#fff;flex-shrink:0;}
.pc-user-info{flex:1;}
.pc-user-info strong{display:block;font-size:13px;font-weight:600;}
.pc-user-info span{font-size:11px;color:var(--text3);}
.pc-chat-row{background:var(--surface3);border-radius:12px;padding:10px 12px;margin-bottom:8px;cursor:pointer;transition:background .15s;}
.pc-chat-row:hover{background:#2e2e52;}
.pc-chat-row strong{display:block;font-size:13px;font-weight:600;margin-bottom:2px;}
.pc-chat-row span{font-size:11px;color:var(--text3);}
.pc-chat-msgs{display:none;background:var(--bg);border-radius:10px;padding:10px;margin-top:8px;max-height:200px;overflow-y:auto;}
.pc-chat-msgs.open{display:block;}
.pc-msg-line{font-size:12px;padding:4px 0;border-bottom:1px solid var(--border);color:var(--text2);}
.pc-msg-line:last-child{border:none;}
.pc-msg-line strong{color:var(--p);}
.pc-pin-dots{display:flex;gap:10px;justify-content:center;margin:14px 0;}
.pc-pin-dot{width:14px;height:14px;border-radius:50%;background:var(--border2);transition:background .2s;}
.pc-pin-dot.filled{background:var(--p);}
.pc-numpad{display:grid;grid-template-columns:repeat(3,1fr);gap:8px;max-width:220px;margin:0 auto;}
.pc-key{padding:14px;border-radius:13px;border:none;background:var(--surface2);color:var(--text);font-family:'Plus Jakarta Sans',sans-serif;font-size:18px;font-weight:700;cursor:pointer;transition:background .15s,transform .1s;}
.pc-key:hover{background:var(--surface3);}
.pc-key:active{transform:scale(.93);}
.pc-key.del{font-size:14px;color:var(--text3);}
.pc-key.empty{background:transparent;pointer-events:none;}
.locked-overlay{position:fixed;inset:0;background:var(--bg);z-index:900;display:flex;flex-direction:column;align-items:center;justify-content:center;padding:24px;}
.locked-overlay.hidden{display:none;}
.locked-icon{font-size:52px;margin-bottom:12px;}
.locked-title{font-family:'Space Grotesk',sans-serif;font-size:26px;font-weight:700;margin-bottom:6px;}
.locked-sub{font-size:14px;color:var(--text3);margin-bottom:28px;}
.parent-link{margin-top:12px;font-size:12px;color:var(--text3);cursor:pointer;text-align:center;text-decoration:underline;text-underline-offset:3px;}
.parent-link:hover{color:var(--text2);}
.limit-banner{background:rgba(248,113,113,.1);border:1px solid rgba(248,113,113,.25);border-radius:13px;padding:12px 14px;font-size:13px;color:var(--danger);margin-bottom:14px;line-height:1.5;text-align:center;}


/* account settings modal */
.acct-tabs{display:flex;background:var(--surface2);border-radius:12px;padding:3px;margin-bottom:18px;gap:3px;}
.acct-tab{flex:1;padding:8px;border-radius:10px;border:none;background:none;color:var(--text3);font-family:'Plus Jakarta Sans',sans-serif;font-size:13px;font-weight:600;cursor:pointer;transition:all .2s;}
.acct-tab.on{background:var(--surface3);color:var(--text);}
.danger-zone{background:rgba(248,113,113,.07);border:1px solid rgba(248,113,113,.2);border-radius:14px;padding:14px;}
.danger-zone p{font-size:13px;color:var(--text3);margin-bottom:12px;line-height:1.5;}
.btn-danger{width:100%;padding:11px;border-radius:12px;border:none;background:rgba(248,113,113,.15);color:var(--danger);font-family:'Plus Jakarta Sans',sans-serif;font-size:14px;font-weight:600;cursor:pointer;border:1px solid rgba(248,113,113,.25);transition:all .15s;}
.btn-danger:hover{background:rgba(248,113,113,.25);}
.strength-bar{height:4px;border-radius:99px;background:var(--border2);margin-top:6px;overflow:hidden;}
.strength-fill{height:100%;border-radius:99px;transition:width .3s,background .3s;}
.strength-label{font-size:10px;margin-top:4px;font-weight:600;}
.acct-btn{width:34px;height:34px;border-radius:50%;border:none;background:var(--surface2);color:var(--text2);font-size:15px;cursor:pointer;display:flex;align-items:center;justify-content:center;transition:background .15s;margin-left:auto;flex-shrink:0;}
.acct-btn:hover{background:var(--surface3);color:var(--text);}
</style>
</head>
<body>
<div class="glow"><span></span><span></span></div>

<!-- AUTH -->
<div class="screen" id="s-auth">
  <div class="brand"><div class="b-icon">⚡</div><div class="b-name">ZapChat</div></div>
  <p class="tagline">Real-time private chats — no phone number needed</p>
  <div class="card">
    <div class="tabs">
      <button class="tab on" id="t-in">Log in</button>
      <button class="tab" id="t-up">Sign up</button>
    </div>
    <!-- login -->
    <div id="f-in">
      <div class="field"><label>Username</label><input class="inp" type="text" id="in-u" placeholder="Your username" autocomplete="username" autocorrect="off" spellcheck="false"/></div>
      <div class="field"><label>Password</label><input class="inp" type="password" id="in-p" placeholder="Your password" autocomplete="current-password"/></div>
      <div class="err" id="in-err"></div>
      <button class="btn-main" id="in-btn">Log in →</button>
    </div>
    <!-- signup -->
    <div id="f-up" style="display:none">
      <div class="limit-banner hidden" id="limit-banner">⚠️ This device already has 2 accounts. Max 2 accounts per device for safety.</div>
      <div class="field"><label>Choose a username</label><input class="inp" type="text" id="up-u" placeholder="e.g. StarDust42" maxlength="20" autocomplete="username" autocorrect="off" spellcheck="false"/></div>
      <div class="field"><label>Choose a password</label><input class="inp" type="password" id="up-p" placeholder="Min 4 characters" autocomplete="new-password"/></div>
      <div class="field"><label>Confirm password</label><input class="inp" type="password" id="up-p2" placeholder="Repeat password" autocomplete="new-password"/></div>
      <div class="field"><label>Prove you're human</label>
        <div class="captcha-box">
          <div class="captcha-q" id="cap-q">3 + 4 = ?</div>
          <input class="captcha-inp" type="number" id="cap-ans" placeholder="?" autocomplete="off"/>
          <button class="captcha-refresh" id="cap-refresh" type="button">↻</button>
        </div>
      </div>
      <div class="err" id="up-err"></div>
      <button class="btn-main" id="up-btn">Create account →</button>
    </div>
  </div>
  <p class="parent-link" id="parent-link">👨‍👩‍👧 Parental Controls</p>
  <div class="hint">📲 <strong>Install as app:</strong> Share → Add to Home Screen (iPhone) · ⋮ → Add to Home Screen (Android)</div>
</div>

<!-- APP -->
<div class="screen hidden" id="s-app">
  <div class="sb" id="sb">
    <div class="sb-top">
      <div class="sb-logo"><div class="sb-logo-icon">⚡</div><div class="sb-logo-text">ZapChat</div></div>
      <div class="me-row" id="me-row" title="Click to copy username">
        <div class="av me-av" id="me-av">?</div>
        <div class="me-info"><strong id="me-name">—</strong><small>click to copy username</small></div>
        <div class="online"></div>
        <button class="acct-btn" id="acct-btn" title="Account settings">⚙️</button>
      </div>
    </div>
    <div class="sb-label">Chats <button id="new-btn">+ New Chat</button></div>
    <div class="clist" id="clist"><div class="empty"><div class="empty-icon">💬</div><p>No chats yet.<br>Hit <strong>+ New Chat</strong> to start!</p></div></div>
    <div class="sb-bot"><button class="btn-out" id="pc-sb-btn" style="margin-bottom:8px;">👨‍👩‍👧 Parental Controls</button><button class="btn-out" id="out-btn">← Sign out</button></div>
  </div>

  <div class="cmain">
    <div class="nochat" id="nochat">
      <div class="nochat-icon">⚡</div>
      <h3>Pick a chat</h3>
      <p>Select a conversation or create a new one.</p>
      <button class="btn-nc" id="nc-new">+ New Chat</button>
    </div>
    <div id="achat" style="display:none;flex-direction:column;flex:1;overflow:hidden;">
      <div class="chdr">
        <button class="hdr-back" id="hdr-back">‹</button>
        <div class="av hdr-av" id="hdr-av">?</div>
        <div class="hdr-info"><h2 id="hdr-name">—</h2><p id="hdr-sub">—</p></div>
        <div class="hdr-btns"><button class="hdr-btn" id="info-btn">👥</button></div>
      </div>
      <div class="msgs" id="msgs"></div>
      <div class="iarea">
        <div class="prevwrap" id="prevwrap"><img id="prev-img" src="" alt=""/><button class="prevx" id="prevx">×</button></div>
        <div class="emojis">
          <button class="emj" data-e="😂">😂</button><button class="emj" data-e="🔥">🔥</button>
          <button class="emj" data-e="💀">💀</button><button class="emj" data-e="❤️">❤️</button>
          <button class="emj" data-e="👏">👏</button><button class="emj" data-e="😮">😮</button>
          <button class="emj" data-e="✨">✨</button><button class="emj" data-e="💯">💯</button>
          <button class="emj" data-e="😭">😭</button><button class="emj" data-e="🤣">🤣</button>
          <button class="emj" data-e="💅">💅</button><button class="emj" data-e="🫡">🫡</button>
        </div>
        <div class="irow">
          <textarea class="mta" id="mta" placeholder="Message..." rows="1"></textarea>
          <div class="ibtns">
            <button class="imgbtn" id="imgbtn">🖼️</button>
            <input type="file" id="imgfile" accept="image/*" style="display:none"/>
            <button class="sendbtn" id="sendbtn"><svg viewBox="0 0 24 24"><path d="M2.01 21L23 12 2.01 3 2 10l15 2-15 2z"/></svg></button>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>


<!-- PARENTAL ENTRY — master password for dashboard, PIN for lock -->
<div class="pc-overlay hidden" id="pc-pin-overlay">
  <div class="pc-panel">
    <h2>👨‍👩‍👧 Parental Controls</h2>
    <p class="pc-sub" id="pc-pin-sub">Enter your master password to continue.</p>

    <!-- Master password input (shown for dashboard access) -->
    <div id="pc-master-input-wrap">
      <div class="field" style="margin-bottom:8px;">
        <label>Master Password</label>
        <input class="inp" type="password" id="pc-master-inp" placeholder="Enter master password" autocomplete="current-password"/>
      </div>
      <div class="merr" id="pc-pin-err"></div>
      <div class="mbtns" style="margin-top:14px;">
        <button class="mbtn cl" id="pc-pin-cancel">Cancel</button>
        <button class="mbtn ok" id="pc-master-submit">Unlock →</button>
      </div>
    </div>

    <!-- PIN numpad (shown for lock PIN change) -->
    <div id="pc-pin-input-wrap" style="display:none;">
      <div class="pc-pin-dots" id="pc-pin-dots">
        <div class="pc-pin-dot"></div><div class="pc-pin-dot"></div>
        <div class="pc-pin-dot"></div><div class="pc-pin-dot"></div>
      </div>
      <div class="merr" id="pc-pin-err2"></div>
      <div class="pc-numpad" id="pc-numpad">
        <button class="pc-key" data-k="1">1</button><button class="pc-key" data-k="2">2</button><button class="pc-key" data-k="3">3</button>
        <button class="pc-key" data-k="4">4</button><button class="pc-key" data-k="5">5</button><button class="pc-key" data-k="6">6</button>
        <button class="pc-key" data-k="7">7</button><button class="pc-key" data-k="8">8</button><button class="pc-key" data-k="9">9</button>
        <button class="pc-key empty"></button><button class="pc-key" data-k="0">0</button><button class="pc-key del" data-k="del">⌫</button>
      </div>
      <div class="mbtns" style="margin-top:14px;">
        <button class="mbtn cl" id="pc-pin-cancel2">Cancel</button>
      </div>
    </div>
  </div>
</div>

<!-- PARENTAL DASHBOARD -->
<div class="pc-overlay hidden" id="pc-dash">
  <div class="pc-panel">
    <h2>👨‍👩‍👧 Parental Controls</h2>
    <p class="pc-sub">Monitor accounts and chats on this device.</p>

    <div class="pc-section">
      <h4>Accounts on this device</h4>
      <div id="pc-accounts"></div>
    </div>

    <div class="pc-section">
      <h4>Chat history</h4>
      <div id="pc-chats"></div>
    </div>

    <div class="pc-section">
      <h4>App lock</h4>
      <p style="font-size:13px;color:var(--text3);margin-bottom:10px;">Lock the app so kids need the PIN to open it.</p>
      <div style="display:flex;gap:9px;">
        <button class="mbtn ok" id="pc-lock-btn" style="flex:1;">🔒 Lock App Now</button>
        <button class="mbtn cl" id="pc-change-pin" style="flex:1;">🔑 Change PIN</button>
      </div>
    </div>

    <div class="mbtns">
      <button class="mbtn cl" id="pc-dash-close">Close</button>
    </div>
  </div>
</div>

<!-- LOCKED SCREEN -->
<div class="locked-overlay hidden" id="locked-screen">
  <div class="locked-icon">🔒</div>
  <div class="locked-title">App Locked</div>
  <div class="locked-sub">A parent has locked ZapChat.</div>
  <div class="pc-pin-dots" id="lock-pin-dots">
    <div class="pc-pin-dot" id="lpd0"></div><div class="pc-pin-dot" id="lpd1"></div>
    <div class="pc-pin-dot" id="lpd2"></div><div class="pc-pin-dot" id="lpd3"></div>
  </div>
  <div class="merr" id="lock-err"></div>
  <div class="pc-numpad" id="lock-numpad">
    <button class="pc-key" data-k="1">1</button><button class="pc-key" data-k="2">2</button><button class="pc-key" data-k="3">3</button>
    <button class="pc-key" data-k="4">4</button><button class="pc-key" data-k="5">5</button><button class="pc-key" data-k="6">6</button>
    <button class="pc-key" data-k="7">7</button><button class="pc-key" data-k="8">8</button><button class="pc-key" data-k="9">9</button>
    <button class="pc-key empty"></button><button class="pc-key" data-k="0">0</button><button class="pc-key del" data-k="del">⌫</button>
  </div>
</div>


<!-- ACCOUNT SETTINGS MODAL -->
<div class="overlay hidden" id="m-acct">
  <div class="modal">
    <h3>⚙️ Account Settings</h3>
    <p class="msub">Manage your ZapChat account.</p>
    <div class="acct-tabs">
      <button class="acct-tab on" id="at-pw">Change Password</button>
      <button class="acct-tab" id="at-del">Delete Account</button>
    </div>

    <!-- change password -->
    <div id="af-pw">
      <div class="field"><label>Current Password</label><input class="inp" type="password" id="pw-cur" placeholder="Your current password" autocomplete="current-password"/></div>
      <div class="field"><label>New Password</label>
        <input class="inp" type="password" id="pw-new" placeholder="Min 4 characters" autocomplete="new-password"/>
        <div class="strength-bar"><div class="strength-fill" id="pw-strength-fill" style="width:0%"></div></div>
        <div class="strength-label" id="pw-strength-label" style="color:var(--text3)"></div>
      </div>
      <div class="field"><label>Confirm New Password</label><input class="inp" type="password" id="pw-new2" placeholder="Repeat new password" autocomplete="new-password"/></div>
      <div class="merr" id="pw-err"></div>
      <div class="mbtns">
        <button class="mbtn cl" id="pw-cancel">Cancel</button>
        <button class="mbtn ok" id="pw-save">Update Password</button>
      </div>
    </div>

    <!-- delete account -->
    <div id="af-del" style="display:none">
      <div class="danger-zone">
        <p>⚠️ <strong>This cannot be undone.</strong> Your account and all your chats will be permanently deleted.</p>
        <div class="field"><label>Confirm your password</label><input class="inp" type="password" id="del-pw" placeholder="Enter password to confirm" autocomplete="current-password"/></div>
        <div class="merr" id="del-err"></div>
        <button class="btn-danger" id="del-confirm">🗑️ Permanently Delete My Account</button>
      </div>
      <div class="mbtns" style="margin-top:14px;">
        <button class="mbtn cl" id="del-cancel">Cancel</button>
      </div>
    </div>
  </div>
</div>

<!-- NEW CHAT MODAL -->
<div class="overlay hidden" id="m-new">
  <div class="modal">
    <h3>New Chat</h3>
    <p class="msub">Type your friend's username. They must have already signed up. Add multiple for a group chat.</p>
    <div class="field">
      <label>Add people (press Enter after each name)</label>
      <div class="tagwrap" id="tagwrap"><input class="taginp" id="taginp" placeholder="Type a username..." maxlength="20" autocomplete="off" autocorrect="off" spellcheck="false"/></div>
      <div class="taghint">1 person = DM &nbsp;·&nbsp; 2+ people = group</div>
    </div>
    <div class="field" id="gname-f" style="display:none">
      <label>Group name (optional)</label>
      <input class="inp" type="text" id="gname" placeholder="e.g. The Squad 🔥" maxlength="28" autocomplete="off"/>
    </div>
    <div class="merr" id="new-err"></div>
    <div class="mbtns">
      <button class="mbtn cl" id="new-cl">Cancel</button>
      <button class="mbtn ok" id="new-ok">Start Chat →</button>
    </div>
  </div>
</div>

<!-- INFO MODAL -->
<div class="overlay hidden" id="m-info">
  <div class="modal">
    <h3 id="info-title">Chat info</h3>
    <p class="msub" id="info-sub"></p>
    <div class="field"><label>Members</label><div class="mems" id="info-mems"></div></div>
    <div class="mbtns">
      <button class="mbtn cl" id="info-cl">Close</button>
      <button class="mbtn ok" style="background:rgba(248,113,113,.18);color:var(--danger);box-shadow:none;" id="info-del">Leave chat</button>
    </div>
  </div>
</div>

<!-- LIGHTBOX -->
<div class="lbox hidden" id="lbox"><img id="limg" src="" alt=""/></div>

<!-- TOAST -->
<div class="toast hidden" id="toast"></div>

<script>
// ── CONFIG ──────────────────────────────────────
const URL_SB = 'https://xszbtiivlsvbahmcimwl.supabase.co';
const KEY_SB = 'eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJzdXBhYmFzZSIsInJlZiI6InhzemJ0aWl2bHN2YmFobWNpbXdsIiwicm9sZSI6ImFub24iLCJpYXQiOjE3NzgxODAzNjEsImV4cCI6MjA5Mzc1NjM2MX0.deB80cZ9s_TDxZlGSF83eaIN1c6v60Zbwifx2GeEgRY';

// ── SUPABASE REST HELPERS (no SDK = no DataCloneError) ──
// We call Supabase directly via fetch instead of using the JS SDK.
// This completely avoids the service worker / Headers clone bug.

const H = () => ({'Content-Type':'application/json','apikey':KEY_SB,'Authorization':'Bearer '+KEY_SB,'Prefer':'return=representation'});

async function dbSelect(table, params=''){
  const r = await fetch(`${URL_SB}/rest/v1/${table}?${params}`, {headers:H()});
  if(!r.ok){ const e=await r.text(); throw new Error(e); }
  return r.json();
}
async function dbInsert(table, body){
  const r = await fetch(`${URL_SB}/rest/v1/${table}`, {method:'POST', headers:H(), body:JSON.stringify(body)});
  if(!r.ok){ const e=await r.text(); throw new Error(e); }
  return r.json();
}
async function dbUpdate(table, params, body){
  const r = await fetch(`${URL_SB}/rest/v1/${table}?${params}`, {method:'PATCH', headers:H(), body:JSON.stringify(body)});
  if(!r.ok){ const e=await r.text(); throw new Error(e); }
  return r.json();
}
async function dbDelete(table, params){
  const r = await fetch(`${URL_SB}/rest/v1/${table}?${params}`, {method:'DELETE', headers:H()});
  if(!r.ok){ const e=await r.text(); throw new Error(e); }
  return true;
}

// Realtime via Supabase websocket
function realtimeSub(table, filter, cb){
  // Use Supabase realtime endpoint
  const wsUrl = URL_SB.replace('https','wss') + '/realtime/v1/websocket?apikey=' + KEY_SB + '&vsn=1.0.0';
  const ws = new WebSocket(wsUrl);
  let joined = false;
  const topic = `realtime:public:${table}`;
  ws.onopen = () => {
    ws.send(JSON.stringify({topic:'realtime:public',event:'phx_join',payload:{},ref:'1'}));
    ws.send(JSON.stringify({topic,event:'phx_join',payload:{config:{broadcast:{self:false},presence:{key:''},postgres_changes:[{event:'INSERT',schema:'public',table,filter:filter||''}]}},ref:'2'}));
  };
  ws.onmessage = e => {
    try{
      const msg = JSON.parse(e.data);
      if(msg.event==='postgres_changes' && msg.payload?.data?.record){
        cb(msg.payload.data.record);
      }
    }catch{}
  };
  ws.onerror = ()=>{};
  return ws;
}

// ── HELPERS ─────────────────────────────────────
const AVC=['linear-gradient(135deg,#7c3aed,#a78bfa)','linear-gradient(135deg,#db2777,#f472b6)','linear-gradient(135deg,#0891b2,#22d3ee)','linear-gradient(135deg,#d97706,#fbbf24)','linear-gradient(135deg,#059669,#34d399)','linear-gradient(135deg,#7c3aed,#f472b6)','linear-gradient(135deg,#0891b2,#7c3aed)','linear-gradient(135deg,#dc2626,#f472b6)'];
function avc(n){let h=0;for(const c of(n||''))h=(h*31+c.charCodeAt(0))%AVC.length;return AVC[h];}
const ini=n=>(n||'?').slice(0,2).toUpperCase();
const uid=()=>Date.now().toString(36)+Math.random().toString(36).slice(2,6);
const fmtT=d=>new Date(+d).toLocaleTimeString([],{hour:'2-digit',minute:'2-digit'});
const fmtD=d=>new Date(+d).toLocaleDateString([],{month:'short',day:'numeric'});
const esc=s=>{const d=document.createElement('div');d.appendChild(document.createTextNode(s||''));return d.innerHTML;};
const trunc=(s,n)=>s&&s.length>n?s.slice(0,n)+'…':s;
const $=id=>document.getElementById(id);
let toastTid;
function toast(msg,ms=2800){const t=$('toast');t.textContent=msg;t.classList.remove('hidden');clearTimeout(toastTid);toastTid=setTimeout(()=>t.classList.add('hidden'),ms);}

async function sha256(str){
  const b=await crypto.subtle.digest('SHA-256',new TextEncoder().encode(str));
  return Array.from(new Uint8Array(b)).map(x=>x.toString(16).padStart(2,'0')).join('');
}

// ── STATE ────────────────────────────────────────
let me='';
let chats=[];
let activeId=null;
let wsMsgs=null, wsChats=null;

// ── AUTH TABS ────────────────────────────────────
$('t-in').onclick=()=>setTab('in');
$('t-up').onclick=()=>setTab('up');
function setTab(t){
  $('f-in').style.display=t==='in'?'block':'none';
  $('f-up').style.display=t==='up'?'block':'none';
  $('t-in').className='tab'+(t==='in'?' on':'');
  $('t-up').className='tab'+(t==='up'?' on':'');
  $('in-err').textContent='';$('up-err').textContent='';
}

// ── LOGIN ────────────────────────────────────────
$('in-btn').onclick=doLogin;
$('in-p').onkeydown=e=>{if(e.key==='Enter')doLogin();};
async function doLogin(){
  const u=$('in-u').value.trim(), p=$('in-p').value;
  if(!u||!p){$('in-err').textContent='Please fill in both fields.';return;}
  const btn=$('in-btn');btn.disabled=true;btn.innerHTML='<span class="spin"></span>Logging in...';
  $('in-err').textContent='';
  try{
    const hash=await sha256(p);
    const rows=await dbSelect('users',`username=eq.${encodeURIComponent(u)}&password_hash=eq.${encodeURIComponent(hash)}&select=username`);
    if(!rows||rows.length===0){$('in-err').textContent='Wrong username or password.';return;}
    me=rows[0].username;
    localStorage.setItem('zc_me',me);
    enterApp();
  }catch(err){
    $('in-err').textContent='Error: '+err.message;
  }finally{btn.disabled=false;btn.innerHTML='Log in →';}
}

// ── SIGNUP ───────────────────────────────────────
$('up-btn').onclick=doSignup;
$('up-p2').onkeydown=e=>{if(e.key==='Enter')doSignup();};
async function doSignup(){
  const u=$('up-u').value.trim().replace(/\s+/g,'_'), p=$('up-p').value, p2=$('up-p2').value;
  if(deviceAtLimit()){$('up-err').textContent='Max 2 accounts per device reached.';return;}
  if(!u||!p||!p2){$('up-err').textContent='Please fill in all fields.';return;}
  if(!checkCaptcha()){$('up-err').textContent='Incorrect answer to the math puzzle. Try again.';newCaptcha();return;}
  if(u.length<2){$('up-err').textContent='Username must be at least 2 characters.';return;}
  if(p.length<4){$('up-err').textContent='Password must be at least 4 characters.';return;}
  if(p!==p2){$('up-err').textContent='Passwords do not match.';return;}
  const btn=$('up-btn');btn.disabled=true;btn.innerHTML='<span class="spin"></span>Creating account...';
  $('up-err').textContent='';
  try{
    // check if username taken
    const exists=await dbSelect('users',`username=eq.${encodeURIComponent(u)}&select=username`);
    if(exists&&exists.length>0){$('up-err').textContent='Username already taken. Try another.';return;}
    const hash=await sha256(p);
    await dbInsert('users',{id:uid(),username:u,password_hash:hash});
    me=u;
    localStorage.setItem('zc_me',me);
    addDeviceAccount(u);
    enterApp();
  }catch(err){
    $('up-err').textContent='Error: '+err.message;
  }finally{btn.disabled=false;btn.innerHTML='Create account →';}
}

// ── ENTER APP ────────────────────────────────────
async function enterApp(){
  $('s-auth').classList.add('hidden');
  $('s-app').classList.remove('hidden');
  $('me-av').textContent=ini(me);$('me-av').style.background=avc(me);
  $('me-name').textContent=me;
  $('me-row').onclick=()=>{navigator.clipboard?.writeText(me);toast('Username copied! Share it with friends 👍');};
  await loadChats();
  subChats();
}

// ── LOAD CHATS ───────────────────────────────────
async function loadChats(){
  try{
    // Get chats where me is in members array
    const rows=await dbSelect('chats',`members=cs.{${encodeURIComponent(me)}}&order=created_at.desc`);
    chats=rows||[];
    // For each chat, get last message
    await Promise.all(chats.map(async chat=>{
      try{
        const msgs=await dbSelect('messages',`chat_id=eq.${chat.id}&order=ts.desc&limit=1`);
        chat._last=msgs?.[0]||null;
      }catch{chat._last=null;}
    }));
    chats.sort((a,b)=>(b._last?.ts||0)-(a._last?.ts||0));
    renderChats();
  }catch(err){toast('Error loading chats: '+err.message);}
}

// ── REALTIME: watch for new chats ────────────────
function subChats(){
  if(wsChats){try{wsChats.close();}catch{}}
  wsChats=realtimeSub('chats','',async row=>{
    if(row.members&&row.members.includes(me)&&!chats.find(c=>c.id===row.id)){
      row._last=null;
      chats.unshift(row);
      renderChats();
      toast('New chat: '+getChatName(row));
    }
  });
}

// ── CHAT LIST ────────────────────────────────────
function getChatName(chat){
  const others=(chat.members||[]).filter(m=>m!==me);
  return chat.type==='group'?(chat.name||others.join(', ')):others[0]||'?';
}
function getChatAv(chat){
  const others=(chat.members||[]).filter(m=>m!==me);
  return chat.type==='group'?chat.name:(others[0]||'?');
}

function renderChats(){
  const c=$('clist');
  if(!chats||chats.length===0){
    c.innerHTML='<div class="empty"><div class="empty-icon">💬</div><p>No chats yet.<br>Hit <strong>+ New Chat</strong>!</p></div>';return;
  }
  c.innerHTML='';
  const sorted=[...chats].sort((a,b)=>(b._last?.ts||0)-(a._last?.ts||0));
  sorted.forEach(chat=>{
    const isG=chat.type==='group';
    const name=getChatName(chat);
    const avN=getChatAv(chat);
    const prev=chat._last?.img?'📷 Image':trunc(chat._last?.text||'',28)||'Tap to chat';
    const el=document.createElement('div');
    el.className='ci'+(chat.id===activeId?' on':'');
    el.innerHTML=`
      <div class="av ci-av ${isG?'grp':''}" style="background:${avc(avN)}">${isG?'👥':ini(avN)}</div>
      <div class="ci-info"><strong>${esc(name)}</strong><span>${esc(prev)}</span></div>
      <div class="ci-meta">
        ${chat._last?.ts?`<div class="ci-t">${fmtT(chat._last.ts)}</div>`:''}
        ${chat._unread?`<div class="ci-u">${chat._unread}</div>`:''}
      </div>
      <button class="ci-x" title="Leave">×</button>`;
    el.onclick=e=>{if(e.target.classList.contains('ci-x'))return;openChat(chat.id);};
    el.querySelector('.ci-x').onclick=e=>{e.stopPropagation();if(confirm('Leave this chat?'))leaveChat(chat.id);};
    c.appendChild(el);
  });
}

// ── OPEN CHAT ────────────────────────────────────
async function openChat(id){
  activeId=id;
  const chat=chats.find(c=>c.id===id);if(!chat)return;
  chat._unread=0;
  if(window.innerWidth<=680)$('sb').classList.add('out');

  const isG=chat.type==='group';
  const name=getChatName(chat);
  const avN=getChatAv(chat);

  const ha=$('hdr-av');
  ha.textContent=isG?'👥':ini(avN);
  ha.style.background=avc(avN);
  ha.className='av hdr-av'+(isG?' grp':'');
  $('hdr-name').textContent=name;
  $('hdr-sub').textContent=isG?`${chat.members.length} members`:`DM`;

  $('nochat').style.display='none';
  $('achat').style.display='flex';
  renderChats();
  await loadMsgs(id);
  subMsgs(id);
}

async function loadMsgs(chatId){
  const c=$('msgs');c.innerHTML='';
  try{
    const rows=await dbSelect('messages',`chat_id=eq.${chatId}&order=ts.asc`);
    if(!rows||rows.length===0){
      c.innerHTML='<div class="msys">Say hi! 👋</div>';return;
    }
    let lastD='';
    rows.forEach(msg=>{
      const d=fmtD(msg.ts);
      if(d!==lastD){const dv=document.createElement('div');dv.className='ddiv';dv.textContent=d;c.appendChild(dv);lastD=d;}
      c.appendChild(buildMsg(msg));
    });
    scrollBot();
  }catch(err){toast('Error loading messages.');}
}

function buildMsg(msg){
  const chat=chats.find(c=>c.id===msg.chat_id);
  const isMe=msg.from_user===me;
  const row=document.createElement('div');row.className='mrow'+(isMe?' me':'');
  const av=document.createElement('div');av.className='av mav';av.style.background=avc(msg.from_user);av.textContent=ini(msg.from_user);
  const body=document.createElement('div');body.className='mbody';
  if(!isMe&&chat?.type==='group'){const sn=document.createElement('div');sn.className='msender';sn.textContent=msg.from_user;body.appendChild(sn);}
  if(msg.img){
    const bub=document.createElement('div');bub.className='mimg';
    const img=document.createElement('img');img.src=msg.img;img.alt='img';
    img.onclick=()=>{$('limg').src=msg.img;$('lbox').classList.remove('hidden');};
    bub.appendChild(img);body.appendChild(bub);
  } else {
    const bub=document.createElement('div');bub.className='mbub';bub.textContent=msg.text||'';body.appendChild(bub);
  }
  const t=document.createElement('div');t.className='mtime';t.textContent=fmtT(msg.ts);body.appendChild(t);
  row.appendChild(av);row.appendChild(body);
  return row;
}

function addMsg(msg){
  const c=$('msgs');
  const ph=c.querySelector('.msys');if(ph)ph.remove();
  if(msg.chat_id===activeId){c.appendChild(buildMsg(msg));scrollBot();}
}

function scrollBot(){const c=$('msgs');requestAnimationFrame(()=>{c.scrollTop=c.scrollHeight;});}

// ── REALTIME: watch messages ──────────────────────
function subMsgs(chatId){
  if(wsMsgs){try{wsMsgs.close();}catch{}}
  wsMsgs=realtimeSub('messages',`chat_id=eq.${chatId}`,msg=>{
    if(msg.from_user===me)return; // already shown optimistically
    addMsg(msg);
    const chat=chats.find(c=>c.id===chatId);
    if(chat){chat._last=msg;renderChats();}
  });
}

// ── SEND ─────────────────────────────────────────
let pendImg=null;
$('imgbtn').onclick=()=>$('imgfile').click();
$('imgfile').onchange=e=>{
  const f=e.target.files[0];if(!f)return;
  if(!f.type.startsWith('image/')){toast('Pick an image file.');return;}
  if(f.size>4*1024*1024){toast('Image too large — max 4MB.');return;}
  const r=new FileReader();
  r.onload=ev=>{pendImg=ev.target.result;$('prev-img').src=pendImg;$('prevwrap').style.display='block';};
  r.readAsDataURL(f);e.target.value='';
};
$('prevx').onclick=()=>{pendImg=null;$('prevwrap').style.display='none';$('prev-img').src='';};
$('sendbtn').onclick=sendMsg;
$('mta').onkeydown=e=>{if(e.key==='Enter'&&!e.shiftKey){e.preventDefault();sendMsg();}};
$('mta').oninput=function(){this.style.height='auto';this.style.height=Math.min(this.scrollHeight,120)+'px';};
document.querySelectorAll('.emj').forEach(b=>b.onclick=()=>{const ta=$('mta');ta.value+=b.dataset.e;ta.focus();});

async function sendMsg(){
  const ta=$('mta'), text=ta.value.trim();
  if(!text&&!pendImg)return;
  if(!activeId)return;
  const msg={id:uid(),chat_id:activeId,from_user:me,text:text||null,img:pendImg||null,ts:Date.now()};
  // optimistic
  addMsg(msg);
  ta.value='';ta.style.height='';
  if(pendImg){$('prevwrap').style.display='none';$('prev-img').src='';pendImg=null;}
  const chat=chats.find(c=>c.id===activeId);
  if(chat){chat._last=msg;renderChats();}
  try{await dbInsert('messages',msg);}
  catch(err){toast('Failed to send: '+err.message);}
}

// ── NEW CHAT ─────────────────────────────────────
let tags=[];
function openNewModal(){
  tags=[];
  $('tagwrap').querySelectorAll('.tag').forEach(t=>t.remove());
  $('taginp').value='';$('new-err').textContent='';
  $('gname-f').style.display='none';$('gname').value='';
  $('m-new').classList.remove('hidden');
  setTimeout(()=>$('taginp').focus(),80);
}
function addTag(n){
  n=n.trim().replace(/\s+/g,'_');
  if(!n||tags.includes(n)||n===me)return;
  tags.push(n);
  const t=document.createElement('div');t.className='tag';
  t.innerHTML=`<span>${esc(n)}</span><button>×</button>`;
  t.querySelector('button').onclick=()=>{tags=tags.filter(x=>x!==n);t.remove();updGname();};
  $('tagwrap').insertBefore(t,$('taginp'));
  updGname();$('new-err').textContent='';
}
function updGname(){$('gname-f').style.display=tags.length>=2?'block':'none';}
$('taginp').onkeydown=e=>{
  const v=e.target.value.trim();
  if(e.key==='Enter'||e.key===','){e.preventDefault();if(v)addTag(v);e.target.value='';}
  else if(e.key==='Backspace'&&!v&&tags.length>0){tags.pop();const ts2=$('tagwrap').querySelectorAll('.tag');if(ts2.length)ts2[ts2.length-1].remove();updGname();}
};
$('tagwrap').onclick=()=>$('taginp').focus();
$('new-cl').onclick=()=>$('m-new').classList.add('hidden');
$('m-new').onclick=e=>{if(e.target===$('m-new'))$('m-new').classList.add('hidden');};

$('new-ok').onclick=async()=>{
  const v=$('taginp').value.trim();if(v)addTag(v);$('taginp').value='';
  if(tags.length===0){$('new-err').textContent='Add at least one username.';return;}
  const btn=$('new-ok');btn.disabled=true;btn.textContent='Checking...';
  try{
    // verify users exist
    const found=await dbSelect('users',`username=in.(${tags.map(t=>`"${t}"`).join(',')})&select=username`);
    const foundNames=(found||[]).map(u=>u.username);
    const missing=tags.filter(t=>!foundNames.includes(t));
    if(missing.length>0){$('new-err').textContent=`Not signed up yet: ${missing.join(', ')}`;return;}
    const isG=tags.length>=2;
    const gname=$('gname').value.trim();
    const members=[me,...tags];
    const chat={id:uid(),type:isG?'group':'dm',name:isG?(gname||tags.join(', ')):tags[0],members,created_at:new Date().toISOString()};
    await dbInsert('chats',chat);
    chat._last=null;chat._unread=0;
    chats.unshift(chat);
    $('m-new').classList.add('hidden');
    renderChats();
    openChat(chat.id);
  }catch(err){$('new-err').textContent='Error: '+err.message;}
  finally{btn.disabled=false;btn.textContent='Start Chat →';}
};

// ── LEAVE CHAT ───────────────────────────────────
async function leaveChat(id){
  const chat=chats.find(c=>c.id===id);if(!chat)return;
  try{
    const newM=chat.members.filter(m=>m!==me);
    if(newM.length===0)await dbDelete('chats',`id=eq.${id}`);
    else await dbUpdate('chats',`id=eq.${id}`,{members:newM});
    chats=chats.filter(c=>c.id!==id);
    if(activeId===id){activeId=null;$('achat').style.display='none';$('nochat').style.display='flex';if(window.innerWidth<=680)$('sb').classList.remove('out');}
    renderChats();
  }catch(err){toast('Error: '+err.message);}
}

// ── INFO MODAL ───────────────────────────────────
$('info-btn').onclick=()=>{
  const chat=chats.find(c=>c.id===activeId);if(!chat)return;
  $('info-title').textContent=getChatName(chat);
  $('info-sub').textContent=chat.type==='group'?`Group · ${chat.members.length} members`:'Direct Message';
  const ml=$('info-mems');ml.innerHTML='';
  chat.members.forEach(n=>{
    const ch=document.createElement('div');ch.className='memchip';
    ch.innerHTML=`<div class="memav" style="background:${avc(n)}">${ini(n)}</div>${esc(n)}${n===me?' (you)':''}`;
    ml.appendChild(ch);
  });
  $('m-info').classList.remove('hidden');
};
$('info-cl').onclick=()=>$('m-info').classList.add('hidden');
$('m-info').onclick=e=>{if(e.target===$('m-info'))$('m-info').classList.add('hidden');};
$('info-del').onclick=()=>{if(confirm('Leave this chat?')){$('m-info').classList.add('hidden');leaveChat(activeId);}};

// ── LIGHTBOX ─────────────────────────────────────
$('lbox').onclick=()=>$('lbox').classList.add('hidden');

// ── NAV ──────────────────────────────────────────
$('new-btn').onclick=openNewModal;
$('nc-new').onclick=openNewModal;
$('hdr-back').onclick=()=>{
  $('sb').classList.remove('out');
  activeId=null;$('achat').style.display='none';$('nochat').style.display='flex';
  renderChats();if(wsMsgs)try{wsMsgs.close();}catch{}
};
$('out-btn').onclick=()=>{
  if(!confirm('Sign out?'))return;
  me='';chats=[];activeId=null;
  localStorage.removeItem('zc_me');
  try{if(wsMsgs)wsMsgs.close();if(wsChats)wsChats.close();}catch{}
  $('s-app').classList.add('hidden');$('s-auth').classList.remove('hidden');
  setTab('in');$('in-u').value='';$('in-p').value='';
  $('achat').style.display='none';$('nochat').style.display='flex';
};


// ── CAPTCHA ──────────────────────────────────────
let capA = 0, capB = 0;
function newCaptcha(){
  capA = Math.floor(Math.random()*10)+1;
  capB = Math.floor(Math.random()*10)+1;
  document.getElementById('cap-q').textContent = capA + ' + ' + capB + ' = ?';
  document.getElementById('cap-ans').value = '';
}
newCaptcha();
document.getElementById('cap-refresh').onclick = newCaptcha;
function checkCaptcha(){
  const ans = parseInt(document.getElementById('cap-ans').value);
  return ans === capA + capB;
}

// ── ACCOUNT LIMIT (max 2 per device) ─────────────
const MAX_ACCOUNTS = 2;
function getDeviceAccounts(){
  try{
    const raw = JSON.parse(localStorage.getItem('zc_device_accounts')||'[]');
    // Always deduplicate on read and save back clean version
    const deduped = [...new Set(raw)];
    if(deduped.length !== raw.length) localStorage.setItem('zc_device_accounts', JSON.stringify(deduped));
    return deduped;
  }catch{return [];}
}
function addDeviceAccount(u){
  const a = getDeviceAccounts();
  if(!a.includes(u)){
    a.push(u);
    localStorage.setItem('zc_device_accounts', JSON.stringify(a));
  }
}
function deviceAtLimit(){
  // Only count accounts that haven't been removed and are unique
  return getDeviceAccounts().length >= MAX_ACCOUNTS;
}

// Show limit banner when signup tab opened if at limit
const origSetTab = setTab;
setTab = function(t){
  origSetTab(t);
  if(t==='up'){
    const banner = document.getElementById('limit-banner');
    const btn = document.getElementById('up-btn');
    if(deviceAtLimit()){
      banner.classList.remove('hidden');
      btn.disabled = true;
      document.getElementById('cap-ans').disabled = true;
    } else {
      banner.classList.add('hidden');
      btn.disabled = false;
      document.getElementById('cap-ans').disabled = false;
    }
  }
};

// ── PARENTAL CONTROLS ────────────────────────────
const DEFAULT_PIN = '1234';
function getParentPin(){ return localStorage.getItem('zc_parent_pin') || DEFAULT_PIN; }
function setParentPin(p){ localStorage.setItem('zc_parent_pin', p); }
function isLocked(){ return localStorage.getItem('zc_locked') === '1'; }
function setLocked(v){ if(v) localStorage.setItem('zc_locked','1'); else localStorage.removeItem('zc_locked'); }

// Check lock on load
function checkLock(){
  if(isLocked()){
    document.getElementById('locked-screen').classList.remove('hidden');
  }
}
checkLock();

// PIN input logic (reusable)
function makePinInput(dotsId, numpadId, errId, onComplete){
  let pin = '';
  const dots = [0,1,2,3].map(i=>document.getElementById(dotsId.replace('dots','dot').slice(0,-1)+i) ||
    document.querySelectorAll('#'+dotsId+' .pc-pin-dot')[i]);
  // Actually query by parent
  const dotEls = document.querySelectorAll('#'+dotsId+' .pc-pin-dot');
  function updateDots(){
    dotEls.forEach((d,i)=>{ d.classList.toggle('filled', i < pin.length); });
  }
  document.querySelectorAll('#'+numpadId+' .pc-key').forEach(btn=>{
    btn.onclick = ()=>{
      const k = btn.dataset.k;
      if(k==='del'){ pin=pin.slice(0,-1); }
      else if(pin.length<4){ pin+=k; }
      if(errId) document.getElementById(errId).textContent='';
      updateDots();
      if(pin.length===4) setTimeout(()=>{ onComplete(pin); pin=''; updateDots(); }, 120);
    };
  });
}

// ── LOCK SCREEN PIN ──────────────────────────────
makePinInput('lock-pin-dots','lock-numpad','lock-err', pin=>{
  if(pin === getParentPin()){
    setLocked(false);
    document.getElementById('locked-screen').classList.add('hidden');
    document.getElementById('lock-err').textContent='';
  } else {
    document.getElementById('lock-err').textContent='Wrong PIN. Try again.';
  }
});

// ── PARENTAL ENTRY PIN ───────────────────────────
let pcMode = 'enter'; // 'enter' | 'set' | 'change'
let pcNewPin = '';

function openParentalEntry(mode='enter'){
  pcMode = mode;
  pcNewPin = '';
  const sub = document.getElementById('pc-pin-sub');
  if(mode==='enter') sub.textContent = 'Enter your 4-digit parent PIN. (Default: 1234)';
  else if(mode==='set') sub.textContent = 'Set a new 4-digit parent PIN.';
  else if(mode==='change') sub.textContent = 'Enter your current PIN first.';
  document.getElementById('pc-pin-err').textContent='';
  document.querySelectorAll('#pc-pin-dots .pc-pin-dot').forEach(d=>d.classList.remove('filled'));
  document.getElementById('pc-pin-overlay').classList.remove('hidden');
}

makePinInput('pc-pin-dots','pc-numpad','pc-pin-err', pin=>{
  if(pcMode==='enter'){
    if(pin===getParentPin()){
      document.getElementById('pc-pin-overlay').classList.add('hidden');
      openParentalDash();
    } else {
      document.getElementById('pc-pin-err').textContent='Wrong PIN.';
    }
  } else if(pcMode==='set'){
    if(!pcNewPin){ pcNewPin=pin; document.getElementById('pc-pin-sub').textContent='Confirm your new PIN.'; }
    else if(pin===pcNewPin){ setParentPin(pin); document.getElementById('pc-pin-overlay').classList.add('hidden'); toast('PIN updated! ✅'); }
    else { pcNewPin=''; document.getElementById('pc-pin-err').textContent='PINs did not match. Try again.'; document.getElementById('pc-pin-sub').textContent='Set a new 4-digit parent PIN.'; }
  } else if(pcMode==='change'){
    if(pin===getParentPin()){ pcMode='set'; pcNewPin=''; document.getElementById('pc-pin-sub').textContent='Enter your new 4-digit PIN.'; document.getElementById('pc-pin-err').textContent=''; }
    else { document.getElementById('pc-pin-err').textContent='Wrong current PIN.'; }
  }
});

// pc-pin-cancel already bound above

// ── MASTER PASSWORD ──────────────────────────────
// Master password is stored as a SHA-256 hash in localStorage
// Default master password is "parent123" — shown to user on first open
const MASTER_PW_KEY = 'zc_master_pw_hash';
const DEFAULT_MASTER_PW = 'parent123';

async function getMasterPwHash(){
  const stored = localStorage.getItem(MASTER_PW_KEY);
  if(stored) return stored;
  // First time: set default
  const h = await sha256(DEFAULT_MASTER_PW);
  localStorage.setItem(MASTER_PW_KEY, h);
  return h;
}
async function checkMasterPw(pw){
  const h = await sha256(pw);
  const stored = await getMasterPwHash();
  return h === stored;
}
async function setMasterPw(pw){
  const h = await sha256(pw);
  localStorage.setItem(MASTER_PW_KEY, h);
}

// Override PIN system to also support master password text entry
// Parental entry now shows a password field instead of PIN for more security
function openParentalEntry(mode='enter'){
  pcMode = mode;
  pcNewPin = '';
  const sub = document.getElementById('pc-pin-sub');
  const masterWrap = document.getElementById('pc-master-input-wrap');
  const pinWrap = document.getElementById('pc-pin-input-wrap');
  document.getElementById('pc-master-inp').value='';
  document.getElementById('pc-pin-err').textContent='';
  if(document.getElementById('pc-pin-err2')) document.getElementById('pc-pin-err2').textContent='';
  document.querySelectorAll('#pc-pin-dots .pc-pin-dot').forEach(d=>d.classList.remove('filled'));

  if(mode==='enter'){
    // Show master password input
    sub.textContent='Enter your master password. (Default: parent123)';
    masterWrap.style.display='block';
    pinWrap.style.display='none';
    setTimeout(()=>document.getElementById('pc-master-inp').focus(),100);
  } else {
    // Show PIN numpad for lock PIN change
    sub.textContent = mode==='set'?'Set a new 4-digit app lock PIN.':'Enter your current lock PIN.';
    masterWrap.style.display='none';
    pinWrap.style.display='block';
  }
  document.getElementById('pc-pin-overlay').classList.remove('hidden');
}

// Master password submit
document.getElementById('pc-master-submit').onclick = async ()=>{
  const pw = document.getElementById('pc-master-inp').value;
  const errEl = document.getElementById('pc-pin-err');
  if(!pw){errEl.textContent='Enter your master password.';return;}
  const ok = await checkMasterPw(pw);
  if(ok){
    document.getElementById('pc-pin-overlay').classList.add('hidden');
    openParentalDash();
  } else {
    errEl.textContent='Wrong master password. Try again.';
    document.getElementById('pc-master-inp').value='';
    document.getElementById('pc-master-inp').focus();
  }
};
document.getElementById('pc-master-inp').onkeydown = e=>{if(e.key==='Enter') document.getElementById('pc-master-submit').click();};
document.getElementById('pc-pin-cancel').onclick = ()=>document.getElementById('pc-pin-overlay').classList.add('hidden');
if(document.getElementById('pc-pin-cancel2')) document.getElementById('pc-pin-cancel2').onclick = ()=>document.getElementById('pc-pin-overlay').classList.add('hidden');

// ── PARENTAL DASHBOARD ───────────────────────────
async function openParentalDash(){
  const accs = getDeviceAccounts();

  // ── ACCOUNTS SECTION ──
  const accEl = document.getElementById('pc-accounts');
  accEl.innerHTML = '';
  if(accs.length===0){
    accEl.innerHTML='<p style="font-size:13px;color:var(--text3);">No accounts on this device yet.</p>';
  } else {
    // Fetch real user data from Supabase for each account
    for(const u of accs){
      try{
        const rows = await dbSelect('users', `username=eq.${encodeURIComponent(u)}&select=username,created_at`);
        const exists = rows && rows.length > 0;
        const row = document.createElement('div'); row.className='pc-user-row';

        const joinDate = exists && rows[0].created_at
          ? new Date(rows[0].created_at).toLocaleDateString([],{month:'short',day:'numeric',year:'numeric'})
          : 'Unknown';

        row.innerHTML=`
          <div class="pc-user-av" style="background:${avc(u)}">${ini(u)}</div>
          <div class="pc-user-info">
            <strong>${esc(u)}</strong>
            <span>${exists ? 'Active · joined '+joinDate : '⚠️ Account not found on server'}</span>
          </div>
          <button class="mbtn ok" style="flex:0;padding:6px 12px;font-size:12px;margin-left:auto;background:rgba(248,113,113,.15);color:var(--danger);box-shadow:none;border:1px solid rgba(248,113,113,.25);" data-remove="${esc(u)}">Remove</button>`;

        row.querySelector('[data-remove]').onclick = async (e)=>{
          const uname = e.target.dataset.remove;
          if(!confirm(`Remove account "${uname}" from this device? This only removes it from this device's list, not the server.`)) return;
          const updated = getDeviceAccounts().filter(a=>a!==uname);
          localStorage.setItem('zc_device_accounts', JSON.stringify(updated));
          toast(`Removed ${uname} from this device`);
          openParentalDash(); // refresh
        };
        accEl.appendChild(row);
      }catch(e){
        const row = document.createElement('div'); row.className='pc-user-row';
        row.innerHTML=`<div class="pc-user-av" style="background:${avc(u)}">${ini(u)}</div><div class="pc-user-info"><strong>${esc(u)}</strong><span style="color:var(--danger)">Error loading</span></div>`;
        accEl.appendChild(row);
      }
    }
    // Account count badge
    const badge = document.createElement('div');
    badge.style.cssText='font-size:11px;color:var(--text3);margin-top:8px;padding:4px 0;';
    badge.textContent=`${accs.length}/${MAX_ACCOUNTS} accounts used on this device`;
    accEl.appendChild(badge);
  }

  // ── CHATS SECTION ──
  const chatEl = document.getElementById('pc-chats');
  chatEl.innerHTML='<div style="font-size:12px;color:var(--text3);padding:4px;">Loading chats...</div>';

  if(accs.length===0){
    chatEl.innerHTML='<p style="font-size:13px;color:var(--text3);">No accounts to monitor.</p>';
  } else {
    try{
      const allChats=[];
      for(const u of accs){
        // Use correct PostgREST array contains syntax
        const cs = await dbSelect('chats', 'members=cs.{'+u+'}&order=created_at.desc');
        (cs||[]).forEach(c=>{ if(!allChats.find(x=>x.id===c.id)) allChats.push({...c,_owner:u}); });
      }
      chatEl.innerHTML='';
      if(allChats.length===0){
        chatEl.innerHTML='<p style="font-size:13px;color:var(--text3);">No chats yet.</p>';
      } else {
        for(const chat of allChats.slice(0,30)){
          const others = (chat.members||[]).filter(m=>m!==chat._owner);
          const name = chat.type==='group'
            ? (chat.name || others.join(', '))
            : (others[0] || 'Unknown');
          const wrapper = document.createElement('div');
          const row = document.createElement('div'); row.className='pc-chat-row';
          const msgsDiv = document.createElement('div'); msgsDiv.className='pc-chat-msgs';
          row.innerHTML=`
            <strong>💬 ${esc(name)}</strong>
            <span>${chat.type==='group'?'Group':'DM'} · ${(chat.members||[]).length} members · account: ${esc(chat._owner)}</span>`;
          row.onclick=async()=>{
            if(msgsDiv.classList.contains('open')){ msgsDiv.classList.remove('open'); return; }
            msgsDiv.innerHTML='<div style="font-size:12px;color:var(--text3);">Loading messages...</div>';
            msgsDiv.classList.add('open');
            try{
              const msgs=await dbSelect('messages',`chat_id=eq.${chat.id}&order=ts.asc&limit=100`);
              msgsDiv.innerHTML='';
              if(!msgs||msgs.length===0){
                msgsDiv.innerHTML='<p style="font-size:12px;color:var(--text3);">No messages yet.</p>';return;
              }
              msgs.forEach(m=>{
                const line=document.createElement('div');
                line.className='pc-msg-line'+(m.img?' img-msg':'');
                const t=new Date(m.ts).toLocaleTimeString([],{hour:'2-digit',minute:'2-digit'});
                line.innerHTML=`<strong>${esc(m.from_user)}</strong> <span style="color:var(--text3);font-size:10px;">${t}</span>: ${m.img?'📷 [Image]':esc(m.text||'')}`;
                msgsDiv.appendChild(line);
              });
            }catch(e){
              msgsDiv.innerHTML=`<p style="font-size:12px;color:var(--danger);">Error: ${esc(e.message)}</p>`;
            }
          };
          wrapper.appendChild(row);
          wrapper.appendChild(msgsDiv);
          chatEl.appendChild(wrapper);
        }
      }
    }catch(e){
      chatEl.innerHTML=`<p style="font-size:13px;color:var(--danger);">Error loading chats: ${esc(e.message)}</p>`;
    }
  }

  // ── MASTER PASSWORD SECTION ──
  let mpSection = document.getElementById('pc-master-pw-section');
  if(!mpSection){
    mpSection = document.createElement('div');
    mpSection.id='pc-master-pw-section';
    mpSection.className='pc-section';
    mpSection.innerHTML=`
      <h4>Master Password</h4>
      <p style="font-size:13px;color:var(--text3);margin-bottom:10px;">Change the master password used to access parental controls. Default is <strong>parent123</strong>.</p>
      <div class="field"><label>Current Master Password</label><input class="inp" type="password" id="mp-cur" placeholder="Current password" autocomplete="current-password"/></div>
      <div class="field"><label>New Master Password</label><input class="inp" type="password" id="mp-new" placeholder="New password (min 4 chars)" autocomplete="new-password"/></div>
      <div class="field"><label>Confirm New Password</label><input class="inp" type="password" id="mp-new2" placeholder="Repeat new password" autocomplete="new-password"/></div>
      <div class="merr" id="mp-err"></div>
      <button class="mbtn ok" id="mp-save" style="width:100%;margin-top:4px;">Update Master Password</button>`;
    // Insert before the lock section (pc-lock-btn parent)
    const lockBtn = document.getElementById('pc-lock-btn');
    if(lockBtn) lockBtn.closest('.pc-section').before(mpSection);
    else document.getElementById('pc-dash-close').before(mpSection);

    document.getElementById('mp-save').onclick = async ()=>{
      const cur=$('mp-cur').value, nw=$('mp-new').value, nw2=$('mp-new2').value;
      const errEl=$('mp-err'); errEl.textContent='';
      if(!cur||!nw||!nw2){errEl.textContent='Fill in all fields.';return;}
      if(nw.length<4){errEl.textContent='Min 4 characters.';return;}
      if(nw!==nw2){errEl.textContent='Passwords do not match.';return;}
      const ok = await checkMasterPw(cur);
      if(!ok){errEl.textContent='Current master password is wrong.';return;}
      await setMasterPw(nw);
      $('mp-cur').value='';$('mp-new').value='';$('mp-new2').value='';
      toast('Master password updated! ✅');
    };
  }

  document.getElementById('pc-dash').classList.remove('hidden');
}

document.getElementById('pc-dash-close').onclick=()=>document.getElementById('pc-dash').classList.add('hidden');
document.getElementById('pc-lock-btn').onclick=()=>{
  setLocked(true);
  document.getElementById('pc-dash').classList.add('hidden');
  document.getElementById('locked-screen').classList.remove('hidden');
  // sign out current user
  me='';chats=[];activeId=null;
  document.getElementById('s-app').classList.add('hidden');
  document.getElementById('s-auth').classList.remove('hidden');
};
document.getElementById('pc-change-pin').onclick=()=>{
  document.getElementById('pc-dash').classList.add('hidden');
  openParentalEntry('change');
};

// Hook up all parental control buttons
['parent-link','pc-sb-btn'].forEach(id=>{
  const el=document.getElementById(id);
  if(el) el.onclick=()=>openParentalEntry('enter');
});


// ── ACCOUNT SETTINGS ─────────────────────────────

// tabs
function setAcctTab(t){
  document.getElementById('af-pw').style.display = t==='pw'?'block':'none';
  document.getElementById('af-del').style.display = t==='del'?'block':'none';
  document.getElementById('at-pw').className = 'acct-tab'+(t==='pw'?' on':'');
  document.getElementById('at-del').className = 'acct-tab'+(t==='del'?' on':'');
  document.getElementById('pw-err').textContent='';
  document.getElementById('del-err').textContent='';
}
document.getElementById('at-pw').onclick = ()=>setAcctTab('pw');
document.getElementById('at-del').onclick = ()=>setAcctTab('del');

// open modal
document.getElementById('acct-btn').onclick = ()=>{
  setAcctTab('pw');
  ['pw-cur','pw-new','pw-new2','del-pw'].forEach(id=>document.getElementById(id).value='');
  document.getElementById('pw-strength-fill').style.width='0%';
  document.getElementById('pw-strength-label').textContent='';
  document.getElementById('m-acct').classList.remove('hidden');
};

// close buttons
document.getElementById('pw-cancel').onclick = ()=>document.getElementById('m-acct').classList.add('hidden');
document.getElementById('del-cancel').onclick = ()=>document.getElementById('m-acct').classList.add('hidden');
document.getElementById('m-acct').onclick = e=>{ if(e.target===document.getElementById('m-acct')) document.getElementById('m-acct').classList.add('hidden'); };

// password strength meter
document.getElementById('pw-new').oninput = function(){
  const v = this.value;
  const fill = document.getElementById('pw-strength-fill');
  const label = document.getElementById('pw-strength-label');
  let score = 0;
  if(v.length >= 4) score++;
  if(v.length >= 8) score++;
  if(/[A-Z]/.test(v)) score++;
  if(/[0-9]/.test(v)) score++;
  if(/[^A-Za-z0-9]/.test(v)) score++;
  const levels = [
    {w:'0%',   c:'transparent', t:''},
    {w:'25%',  c:'var(--danger)', t:'Weak'},
    {w:'50%',  c:'var(--ye)',     t:'Fair'},
    {w:'75%',  c:'#60a5fa',      t:'Good'},
    {w:'100%', c:'var(--gr)',     t:'Strong'},
  ];
  const lv = levels[Math.min(score, 4)];
  fill.style.width = lv.w;
  fill.style.background = lv.c;
  label.textContent = lv.t;
  label.style.color = lv.c;
};

// change password
document.getElementById('pw-save').onclick = async ()=>{
  const cur  = document.getElementById('pw-cur').value;
  const nw   = document.getElementById('pw-new').value;
  const nw2  = document.getElementById('pw-new2').value;
  const errEl= document.getElementById('pw-err');
  errEl.textContent='';
  if(!cur||!nw||!nw2){errEl.textContent='Please fill in all fields.';return;}
  if(nw.length<4){errEl.textContent='New password must be at least 4 characters.';return;}
  if(nw===cur){errEl.textContent='New password must be different from current.';return;}
  if(nw!==nw2){errEl.textContent='New passwords do not match.';return;}

  const btn=document.getElementById('pw-save');
  btn.disabled=true;btn.innerHTML='<span class="spin"></span>Updating...';
  try{
    // verify current password
    const curHash = await sha256(cur);
    const rows = await dbSelect('users',`username=eq.${encodeURIComponent(me)}&password_hash=eq.${encodeURIComponent(curHash)}&select=username`);
    if(!rows||rows.length===0){errEl.textContent='Current password is incorrect.';return;}
    // update to new password
    const newHash = await sha256(nw);
    await dbUpdate('users',`username=eq.${encodeURIComponent(me)}`,{password_hash:newHash});
    document.getElementById('m-acct').classList.add('hidden');
    toast('Password updated successfully ✅');
  }catch(err){errEl.textContent='Error: '+err.message;}
  finally{btn.disabled=false;btn.textContent='Update Password';}
};

// delete account
document.getElementById('del-confirm').onclick = async ()=>{
  const pw   = document.getElementById('del-pw').value;
  const errEl= document.getElementById('del-err');
  errEl.textContent='';
  if(!pw){errEl.textContent='Please enter your password.';return;}

  const btn=document.getElementById('del-confirm');
  btn.disabled=true;btn.textContent='Deleting...';
  try{
    // verify password
    const hash = await sha256(pw);
    const rows = await dbSelect('users',`username=eq.${encodeURIComponent(me)}&password_hash=eq.${encodeURIComponent(hash)}&select=username`);
    if(!rows||rows.length===0){errEl.textContent='Wrong password. Please try again.';return;}

    // remove user from all their chats (leave each one)
    const userChats = await dbSelect('chats',`members=cs.{${encodeURIComponent(me)}}`);
    for(const chat of (userChats||[])){
      const newM = chat.members.filter(m=>m!==me);
      if(newM.length===0) await dbDelete('chats',`id=eq.${chat.id}`);
      else await dbUpdate('chats',`id=eq.${chat.id}`,{members:newM});
    }
    // delete all messages sent by this user
    await dbDelete('messages',`from_user=eq.${encodeURIComponent(me)}`);
    // delete user record
    await dbDelete('users',`username=eq.${encodeURIComponent(me)}`);

    // remove from device account list
    const devAccs = getDeviceAccounts().filter(a=>a!==me);
    localStorage.setItem('zc_device_accounts', JSON.stringify(devAccs));
    localStorage.removeItem('zc_me');

    // sign out
    me='';chats=[];activeId=null;
    if(wsMsgs)try{wsMsgs.close();}catch{}
    if(wsChats)try{wsChats.close();}catch{}
    document.getElementById('m-acct').classList.add('hidden');
    document.getElementById('s-app').classList.add('hidden');
    document.getElementById('s-auth').classList.remove('hidden');
    document.getElementById('achat').style.display='none';
    document.getElementById('nochat').style.display='flex';
    setTab('in');
    document.getElementById('in-u').value='';
    document.getElementById('in-p').value='';
    toast('Account deleted. Sorry to see you go 👋');
  }catch(err){errEl.textContent='Error: '+err.message;}
  finally{btn.disabled=false;btn.textContent='🗑️ Permanently Delete My Account';}
};


// ── AUTO LOGIN ───────────────────────────────────
// Self-heal: deduplicate device accounts on every load
(function cleanDeviceAccounts(){
  try{
    const raw = JSON.parse(localStorage.getItem('zc_device_accounts')||'[]');
    const clean = [...new Set(raw.filter(x=>typeof x==='string'&&x.length>0))];
    localStorage.setItem('zc_device_accounts', JSON.stringify(clean));
  }catch{ localStorage.setItem('zc_device_accounts','[]'); }
})();

(async()=>{
  const saved=localStorage.getItem('zc_me');
  if(saved){
    try{
      const rows=await dbSelect('users',`username=eq.${encodeURIComponent(saved)}&select=username`);
      if(rows&&rows.length>0){me=rows[0].username;await enterApp();return;}
    }catch{}
    localStorage.removeItem('zc_me');
  }
})();
</script>
</body>
</html>
