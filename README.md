# Adita-
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>Aditya Shop – Mau, UP</title>
<style>
:root{--bg:#faf7f2;--card:#fff;--tx:#222;--mu:#666;--ac:#c2410c;--bd:#e5ded3;box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px)}
@media (prefers-color-scheme:dark){:root:not([data-theme="light"]){--bg:#17140f;--card:#221e17;--tx:#f3eee6;--mu:#a89f90;--ac:#fb923c;--bd:#3a3326}}
:root[data-theme="dark"]{--bg:#17140f;--card:#221e17;--tx:#f3eee6;--mu:#a89f90;--ac:#fb923c;--bd:#3a3326}
*{box-sizing:border-box}
body{margin:0;background:var(--bg);color:var(--tx);font-family:system-ui,-apple-system,Segoe UI,Roboto,sans-serif}
header{background:var(--ac);color:#fff;padding:20px 16px;text-align:center}
header h1{margin:0;font-size:1.8rem}header p{margin:4px 0 0;opacity:.95}
.wrap{max-width:1000px;margin:auto;padding:16px}
.bar{display:flex;gap:8px;flex-wrap:wrap;margin-bottom:12px}
input,select,textarea{font:inherit;padding:10px;border:1px solid var(--bd);border-radius:8px;background:var(--card);color:var(--tx);width:100%}
.bar input{flex:1;min-width:160px}.bar select{width:auto}
.grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(210px,1fr));gap:14px}
.card{background:var(--card);border:1px solid var(--bd);border-radius:12px;overflow:hidden;display:flex;flex-direction:column}
.img{height:150px;display:flex;align-items:center;justify-content:center;font-size:3.5rem;background:var(--bd);overflow:hidden}
.img img{width:100%;height:100%;object-fit:cover}
.info{padding:12px;display:flex;flex-direction:column;gap:6px;flex:1}
.info small{color:var(--mu)}.price{font-weight:700;font-size:1.1rem;color:var(--ac)}
button{font:inherit;cursor:pointer;border:0;border-radius:8px;padding:10px 14px;background:var(--ac);color:#fff;font-weight:600}
button.alt{background:var(--bd);color:var(--tx)}
.info button{margin-top:auto}
#cartBtn{position:fixed;right:14px;bottom:calc(14px + env(safe-area-inset-bottom,0px));box-shadow:0 4px 14px #0004;border-radius:30px;padding:14px 20px}
#panel{position:fixed;inset:0;background:#0008;display:none;justify-content:flex-end;z-index:5}
#panel.open{display:flex}
.side{background:var(--bg);width:min(420px,100%);height:100%;overflow:auto;padding:16px;padding-top:calc(16px + env(safe-area-inset-top,0px))}
.row{display:flex;justify-content:space-between;align-items:center;gap:8px;padding:8px 0;border-bottom:1px solid var(--bd)}
.qty button{padding:2px 10px}
.side label{display:block;margin:10px 0 4px;font-size:.9rem;color:var(--mu)}
.actions{display:flex;gap:8px;flex-wrap:wrap;margin-top:14px}.actions button{flex:1}
footer{text-align:center;color:var(--mu);padding:24px 16px 80px;font-size:.9rem}
.empty{color:var(--mu);text-align:center;padding:30px}
