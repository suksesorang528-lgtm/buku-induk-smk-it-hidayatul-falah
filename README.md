# buku-induk-smk-it-hidayatul-falah
<!doctype html>
<html lang="id">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width,initial-scale=1">
<title>Buku Induk Siswa — SMK IT HIDAYATUL FALAH</title>
<style>
:root{--blue:#07508f;--blue2:#0b6bb5;--light:#eef7ff;--gold:#d4a62a;--ink:#18354e;--muted:#708090;--white:#fff;--line:#dce8f1;--danger:#c53b32;--shadow:0 8px 25px rgba(7,55,91,.10)}
*{box-sizing:border-box}body{margin:0;background:#f5f9fc;color:var(--ink);font:14px "Segoe UI",Arial,sans-serif}button,input,select,textarea{font:inherit}button{cursor:pointer}
.login{min-height:100vh;display:flex;align-items:center;justify-content:center;padding:18px;background:linear-gradient(135deg,#063963,#1175bd)}
.loginbox{width:min(420px,100%);background:#fff;border-radius:22px;padding:30px;box-shadow:0 25px 70px #00294c66;text-align:center}.logo{width:85px;height:85px;object-fit:contain;border-radius:12px}.loginbox h1{color:var(--blue);font-size:22px;margin:12px 0 4px}.gold{color:var(--gold)}.muted{color:var(--muted)}.field{text-align:left;margin:11px 0}.field label{display:block;font-weight:700;color:var(--blue);font-size:13px;margin-bottom:5px}.field input,.field select,.field textarea,.search{width:100%;padding:10px 11px;border:1px solid var(--line);border-radius:9px;outline:none;background:#fff}.field input:focus,.field select:focus,.field textarea:focus,.search:focus{border-color:var(--blue2);box-shadow:0 0 0 3px #ddecfb}.btn{border:0;border-radius:9px;padding:9px 13px;font-weight:700}.primary{background:var(--blue);color:#fff}.goldbtn{background:var(--gold);color:#fff}.secondary{background:#edf5fb;color:var(--blue);border:1px solid #d5e5f1}.danger{background:#fff0ee;color:var(--danger);border:1px solid #ffd3cf}.wide{width:100%}.err{height:18px;color:var(--danger);font-size:12px;margin-top:8px}
.app{display:none}.side{position:fixed;left:0;top:0;bottom:0;width:250px;background:linear-gradient(#063963,#07508f);padding:15px 12px;color:#fff;z-index:5;overflow:auto}.brand{display:flex;gap:10px;align-items:center;padding:6px 7px 17px;border-bottom:1px solid #ffffff25;margin-bottom:12px}.brand img{width:45px;height:45px;object-fit:contain;background:#fff;border-radius:8px}.brand b{display:block;font-size:13px}.brand small{color:#e6c55f}.nav button{width:100%;border:0;background:transparent;color:#dceeff;text-align:left;padding:11px;border-radius:9px;margin:2px 0}.nav button:hover,.nav button.active{background:#ffffff18;color:#fff}.nav .ico{display:inline-block;width:25px}.logout{margin-top:15px;width:100%}
.main{margin-left:250px;padding:20px}.top{display:flex;justify-content:space-between;align-items:center;margin-bottom:18px}.top h2{margin:0;color:var(--blue)}.user{padding:8px 12px;background:#fff;border:1px solid var(--line);border-radius:20px;color:var(--blue)}
.page{display:none}.page.active{display:block}.gridstats{display:grid;grid-template-columns:repeat(4,1fr);gap:14px}.card{background:#fff;border:1px solid var(--line);border-radius:15px;padding:17px;box-shadow:var(--shadow);margin-bottom:16px}.stat .num{font-size:29px;font-weight:800;color:var(--blue)}.stat .label{color:var(--muted);font-size:12px}.toolbar{display:flex;justify-content:space-between;align-items:center;gap:9px;flex-wrap:wrap;margin-bottom:13px}.tools{display:flex;gap:8px;flex-wrap:wrap}.search{width:240px}.tablewrap{overflow:auto}.table{width:100%;border-collapse:collapse;min-width:900px}.table th,.table td{padding:9px;border-bottom:1px solid #e9eff4;text-align:left;font-size:12px;vertical-align:top}.table th{background:#f0f7fd;color:var(--blue)}.actions{display:flex;gap:5px;flex-wrap:wrap}.badge{display:inline-block;background:#e8f4ff;color:var(--blue);padding:4px 8px;border-radius:20px;font-size:11px;font-weight:700}
.classgrid{display:grid;grid-template-columns:repeat(auto-fit,minmax(260px,1fr));gap:15px}.classcard{border:1px solid var(--line);border-radius:14px;background:#fff;overflow:hidden;box-shadow:var(--shadow)}.classhead{background:var(--blue);color:#fff;padding:13px}.classhead b{font-size:17px}.classbody{padding:10px}.classstudent{display:flex;justify-content:space-between;gap:8px;padding:9px;border-bottom:1px solid #edf2f5}.classstudent:last-child{border-bottom:0}.classstudent small{color:var(--muted)}
.notice{background:#fff9e9;border-left:4px solid var(--gold);padding:11px;border-radius:7px;color:#70591b}
.modal{display:none;position:fixed;inset:0;background:#00243d88;z-index:30;align-items:center;justify-content:center;padding:15px}.modal.show{display:flex}.modalbox{width:min(1000px,100%);max-height:94vh;overflow:auto;background:#fff;border-radius:17px;padding:18px}.modalhead{display:flex;justify-content:space-between;align-items:center}.modalhead h3{margin:0;color:var(--blue)}.close{border:0;border-radius:50%;width:33px;height:33px}.formgrid{display:grid;grid-template-columns:1fr 1fr;gap:0 14px}.section{grid-column:1/-1;color:var(--gold);font-weight:800;border-bottom:1px solid var(--line);padding:12px 0 6px}.full{grid-column:1/-1}.modalactions{display:flex;justify-content:flex-end;gap:8px;margin-top:12px}.settings{display:grid;grid-template-columns:1fr 1fr;gap:15px}.preview{display:flex;align-items:center;gap:12px}.preview img{width:55px;height:55px;object-fit:contain}.toast{display:none;position:fixed;right:18px;bottom:18px;background:#143d5d;color:#fff;padding:11px 15px;border-radius:9px;z-index:60}
@media(max-width:850px){.side{width:205px}.main{margin-left:205px}.gridstats{grid-template-columns:1fr 1fr}.settings{grid-template-columns:1fr}}
@media(max-width:620px){.side{position:static;width:100%}.main{margin-left:0;padding:12px}.nav{display:grid;grid-template-columns:1fr 1fr}.gridstats{grid-template-columns:1fr 1fr}.formgrid{grid-template-columns:1fr}.section,.full{grid-column:auto}.top{align-items:flex-start;gap:8px;flex-direction:column}}
@media print{body{background:#fff}button{display:none}.top,.toolbar,.modal,.toast,.nav,.side,.user{display:none !important}.app{display:block !important}.page.active{display:block !important}.main{margin-left:0 !important;padding:0 !important}.printable{display:block}.no-print{display:none}.card{box-shadow:none;border:1px solid #ccc}.table{width:100%}.table tr{page-break-inside:avoid}}
</style>
</head>
<body>
<div id="login" class="login">
<div class="loginbox">
<img id="loginLogo" class="logo"><h1 id="loginSchool">SMK IT HIDAYATUL FALAH</h1><b class="gold">BUKU INDUK SISWA</b>
<p class="muted">Masuk untuk mengelola data sekolah.</p>
<div class="field"><label>Email Login</label><input id="lu" type="email" autocomplete="username" placeholder="Email akun Supabase"></div>
<div class="field"><label>Password</label><input id="lp" type="password" autocomplete="current-password"></div>
<button class="btn primary wide" onclick="login()">Masuk</button><div id="loginErr" class="err"></div>
</div></div>

<div id="app" class="app">
<aside class="side">
<div class="brand"><img id="sideLogo"><div><b id="sideSchool">SMK IT HIDAYATUL FALAH</b><small>Buku Induk Siswa</small></div></div>
<nav class="nav">
<button class="active" data-p="dash">🏠 &nbsp; Dasbor</button>
<button data-p="students">👨‍🎓 &nbsp; Data Siswa</button>
<button data-p="alumni">🎓 &nbsp; Alumni</button>
<button data-p="classes">🏫 &nbsp; Kelas Siswa</button>
<button data-p="grades">📊 &nbsp; Data Nilai</button>
<button data-p="parents">👪 &nbsp; Data Orang Tua</button>
<button data-p="settings">⚙️ &nbsp; Pengaturan</button>
</nav>
<button class="btn goldbtn logout" onclick="logout()">Keluar</button>
</aside>
<main class="main">
<div class="top"><h2 id="title">Dasbor</h2><div class="user">👤 <span id="who"></span></div></div>

<section id="dash" class="page active">
<div style="margin-bottom:15px"><button class="btn primary" onclick="printDash()">🖨️ Print Dasbor</button></div>
<div class="gridstats">
<div class="card stat"><div class="num" id="nStudent">0</div><div class="label">Siswa Aktif</div></div>
<div class="card stat"><div class="num" id="nAlumni">0</div><div class="label">Alumni</div></div>
<div class="card stat"><div class="num" id="nClass">0</div><div class="label">Kelas Terdaftar</div></div>
<div class="card stat"><div class="num" id="nYear">0</div><div class="label">Tahun Masuk</div></div>
</div>
<div class="card"><h3 style="color:var(--blue)">Selamat datang</h3><p>Kelola data siswa, orang tua, alumni, nilai, dan pembagian kelas dari satu aplikasi.</p><div class="notice">Data utama tersimpan di database online Supabase. Anda dapat membuka aplikasi dari HP, tablet, atau laptop lain dan menggunakan akun yang sama.</div></div>
</section>

<section id="students" class="page"><div class="card">
<div class="toolbar"><div class="tools"><button class="btn primary" onclick="studentModal()">＋ Tambah Siswa</button><input id="sq" class="search" placeholder="Cari nama, NISN, kelas..." oninput="renderStudents()"></div><div class="tools"><button class="btn secondary" onclick="csv()">Export CSV</button><button class="btn primary" onclick="printStudents()">🖨️ Print</button></div></div>
<div class="tablewrap"><table class="table"><thead><tr><th>Nama</th><th>NISN</th><th>TTL</th><th>Kelas</th><th>Tahun</th><th>Agama</th><th>Alamat</th><th>Fisik</th><th>Aksi</th></tr></thead><tbody id="studentRows"></tbody></table></div>
</div></section>

<section id="alumni" class="page"><div class="card">
<div class="toolbar"><div class="tools"><button class="btn primary" onclick="alumniModal()">＋ Tambah Alumni</button><input id="aq" class="search" placeholder="Cari alumni..." oninput="renderAlumni()"></div></div>
<div class="tablewrap"><table class="table" style="min-width:650px"><thead><tr><th>Nama</th><th>NISN</th><th>Kelas Terakhir</th><th>Tahun Lulus</th><th>Keterangan</th><th>Aksi</th></tr></thead><tbody id="alumniRows"></tbody></table></div>
</div></section>

<section id="classes" class="page"><div class="card">
<div class="toolbar"><div style="display:flex;gap:8px;flex-wrap:wrap"><button class="btn primary" onclick="classModal()">＋ Tambah Kelas</button></div><div class="muted">Siswa otomatis dikelompokkan berdasarkan kelas yang terdaftar.</div></div>
<div id="classGrid" class="classgrid"></div>
</div></section>

<section id="grades" class="page"><div class="card">
<div class="toolbar"><div class="tools"><button class="btn primary" onclick="gradeModal()">＋ Tambah Nilai</button><input id="gq" class="search" placeholder="Cari siswa / NIS / kelas..." oninput="renderGrades()"></div><button class="btn primary" onclick="printGrades()">🖨️ Print Nilai</button></div>
<div class="tablewrap"><table class="table" style="min-width:1500px"><thead><tr><th>Siswa</th><th>NIS</th><th>Kelas</th><th>Mata Pelajaran</th><th>Prestasi</th><th>KKM</th><th>Formatif</th><th>Sumatif Tengah Semester</th><th>Sumatif Akhir Semester</th><th>Aksi</th></tr></thead><tbody id="gradeRows"></tbody></table></div>
</div></section>

<section id="parents" class="page"><div class="card">
<div class="toolbar"><div class="tools"><input id="pq" class="search" placeholder="Cari nama siswa / orang tua..." oninput="renderParents()"></div><div class="tools"><button class="btn primary" onclick="printParents()">🖨️ Print</button></div></div><div class="muted">Data orang tua dikelola dari form siswa.</div></div>
<div class="tablewrap"><table class="table"><thead><tr><th>Siswa</th><th>Ayah</th><th>NIK Ayah</th><th>Pekerjaan</th><th>Telp</th><th>TTL Ayah</th><th>Ibu</th><th>NIK Ibu</th><th>Pekerjaan</th><th>Telp</th><th>TTL Ibu</th><th>Aksi</th></tr></thead><tbody id="parentRows"></tbody></table></div>
</div></section>

<section id="settings" class="page"><div class="settings">
<div class="card"><h3 style="color:var(--blue)">Profil Sekolah</h3><div class="field"><label>Nama Sekolah</label><input id="schoolName"></div><div class="field"><label>Ganti Logo</label><input id="logoFile" type="file" accept="image/*"></div><button class="btn primary" onclick="saveProfile()">Simpan Profil</button></div>
<div class="card"><h3 style="color:var(--blue)">Akun Login Supabase</h3><div class="field"><label>Email Baru</label><input id="newUser" type="email"></div><div class="field"><label>Password Baru</label><input id="newPass" type="password" placeholder="Minimal 6 karakter"></div><button class="btn goldbtn" onclick="saveAccount()">Simpan Akun</button><p class="muted" style="font-size:12px;margin-top:10px">Login aplikasi menggunakan email dan password Supabase. Jangan masukkan secret key di HTML.</p></div>
<div class="card"><h3 style="color:var(--blue)">Backup & Data</h3><button class="btn secondary" onclick="backup()">Backup JSON</button> <label class="btn secondary">Import JSON<input type="file" accept=".json" onchange="restore(event)" style="display:none"></label> <button class="btn danger" onclick="resetAll()">Reset Data</button></div>
<div class="card"><h3 style="color:var(--blue)">Pratinjau</h3><div class="preview"><img id="previewLogo"><div><b id="previewSchool"></b><div class="muted">Buku Induk Siswa</div></div></div></div>
</div></section>
</main></div>

<div id="modal" class="modal" onclick="if(event.target===this)closeModal()"><div class="modalbox"><div class="modalhead"><h3 id="mt"></h3><button class="close" onclick="closeModal()">✕</button></div><div id="mc"></div></div></div>
<div id="toast" class="toast"></div>

<script>
const SUPABASE_URL="https://sjuehwxbzvfdlvxicvrr.supabase.co";
const SUPABASE_PUBLISHABLE_KEY="sb_publishable_urJF_SZlHG-Q5YNqrWRbdg_ALX6sPCs";
let supabase=null;
let supabaseReady=false;
let navBound=false;
/* =========================================================
   KONEKSI SUPABASE TANPA CDN
   Dibuat agar file HTML yang dibuka langsung dari HP (content:// / file://)
   tetap dapat terhubung ke Supabase tanpa bergantung pada jsDelivr/unpkg.
   ========================================================= */
const SESSION_KEY="SMK_IT_HF_SUPABASE_SESSION_V1";

function apiError(message,status){
  const e=new Error(message||"Permintaan database gagal");
  e.status=status||0;
  return e;
}

async function rawFetch(url,options={}){
  try{
    const res=await fetch(url,options);
    let data=null;
    const txt=await res.text();
    try{data=txt?JSON.parse(txt):null}catch{data=txt}
    if(!res.ok){
      const msg=(data&&typeof data==='object'&&(data.message||data.error_description||data.error))||txt||(`HTTP ${res.status}`);
      throw apiError(msg,res.status);
    }
    return data;
  }catch(e){
    if(e instanceof TypeError) throw apiError("Tidak dapat terhubung ke Supabase. Pastikan internet aktif dan Chrome mengizinkan koneksi untuk file HTML ini.");
    throw e;
  }
}

class RestQuery{
  constructor(client,table){this.client=client;this.table=table;this._method="GET";this._select=null;this._filters=[];this._order=[];this._limit=null;this._body=null;this._single=false;this._maybeSingle=false;this._upsert=false;this._onConflict=null;this._executed=false;}
  select(columns="*"){this._select=columns;return this}
  order(column,opts={}){this._order.push([column,opts]);return this}
  limit(n){this._limit=n;return this}
  eq(column,value){this._filters.push([column,"eq",value]);return this}
  neq(column,value){this._filters.push([column,"neq",value]);return this}
  insert(body){this._method="POST";this._body=body;return this}
  update(body){this._method="PATCH";this._body=body;return this}
  upsert(body,opts={}){this._method="POST";this._body=body;this._upsert=true;this._onConflict=opts.onConflict||null;return this}
  delete(){this._method="DELETE";return this}
  single(){this._single=true;return this}
  maybeSingle(){this._maybeSingle=true;return this}
  then(resolve,reject){return this.execute().then(resolve,reject)}
  catch(reject){return this.execute().catch(reject)}
  finally(fn){return this.execute().finally(fn)}
  async execute(){
    if(this._executed)return this._result;
    this._executed=true;
    try{
      let url=this.client.url+"/rest/v1/"+encodeURIComponent(this.table);
      const qs=[];
      if(this._method==="GET"){
        qs.push("select="+encodeURIComponent(this._select||"*"));
      }
      for(const [c,op,v] of this._filters){qs.push(encodeURIComponent(c)+"="+op+"."+encodeURIComponent(String(v)))}
      for(const [c,o] of this._order){qs.push("order="+encodeURIComponent(c)+"."+(o.ascending===false?"desc":"asc")+(o.nullsFirst===true?".nullsfirst":o.nullsFirst===false?".nullslast":""))}
      if(this._limit!=null)qs.push("limit="+encodeURIComponent(this._limit));
      if(qs.length)url+="?"+qs.join("&");
      const headers={"apikey":this.client.key,"Accept":"application/json"};
      let body;
      if(this._method!=="GET"){
        headers["Content-Type"]="application/json";
        if(this._select)headers["Prefer"]="return=representation";
        if(this._upsert){headers["Prefer"]="resolution=merge-duplicates"+(this._select?",return=representation":"");if(this._onConflict)url+=(url.includes("?")?"&":"?")+"on_conflict="+encodeURIComponent(this._onConflict)}
        body=JSON.stringify(this._body);
      }
      const data=await this.client.request(url,{method:this._method,headers,body});
      let out=data;
      if(this._single||this._maybeSingle){
        const arr=Array.isArray(data)?data:[];
        if(this._single){if(arr.length!==1)throw apiError(`Expected 1 row, received ${arr.length}`);out=arr[0]}
        else out=arr.length?arr[0]:null;
      }
      this._result={data:out,error:null};
    }catch(e){this._result={data:null,error:e}}
    return this._result;
  }
}

class RestClient{
  constructor(url,key){this.url=url.replace(/\/$/,"");this.key=key;this.session=null;this.auth={
    getSession:async()=>({data:{session:await this.getStoredSession()},error:null}),
    signInWithPassword:async({email,password})=>this.signIn(email,password),
    signOut:async()=>{this.session=null;localStorage.removeItem(SESSION_KEY);return {error:null}},
    updateUser:async(payload)=>this.updateUser(payload),
    onAuthStateChange:(cb)=>{this._authCallback=cb;return {data:{subscription:{unsubscribe:()=>{this._authCallback=null}}}}}
  }}
  async getStoredSession(){
    try{const raw=localStorage.getItem(SESSION_KEY);if(!raw)return null;const s=JSON.parse(raw);if(!s?.access_token)return null;this.session=s;if(s.expires_at && Date.now()/1000>s.expires_at-30){if(s.refresh_token) return await this.refresh(s.refresh_token);return null}return s}catch{return null}
  }
  async saveSession(s){this.session=s;try{localStorage.setItem(SESSION_KEY,JSON.stringify(s))}catch{};if(this._authCallback)try{await this._authCallback("SIGNED_IN",s)}catch{};return s}
  async refresh(refreshToken){
    const data=await rawFetch(this.url+"/auth/v1/token?grant_type=refresh_token",{method:"POST",headers:{"apikey":this.key,"Content-Type":"application/json"},body:JSON.stringify({refresh_token:refreshToken})});
    const s={...data,expires_at:Math.floor(Date.now()/1000)+(data.expires_in||3600)};return this.saveSession(s);
  }
  async signIn(email,password){
    try{
      const data=await rawFetch(this.url+"/auth/v1/token?grant_type=password",{method:"POST",headers:{"apikey":this.key,"Content-Type":"application/json"},body:JSON.stringify({email,password})});
      const s={...data,expires_at:Math.floor(Date.now()/1000)+(data.expires_in||3600)};await this.saveSession(s);return {data:{user:data.user,session:s},error:null};
    }catch(error){return {data:{user:null,session:null},error}}
  }
  async updateUser(payload){
    try{const s=await this.getStoredSession();if(!s?.access_token)throw apiError("Sesi login sudah habis. Silakan login kembali.");const data=await rawFetch(this.url+"/auth/v1/user",{method:"PUT",headers:{"apikey":this.key,"Authorization":"Bearer "+s.access_token,"Content-Type":"application/json"},body:JSON.stringify(payload)});if(data?.email)s.user=data;await this.saveSession({...s,user:data});return {data:{user:data},error:null}}catch(error){return {data:{user:null},error}}
  }
  async request(url,opts={}){
    let s=await this.getStoredSession();
    const headers={...(opts.headers||{})};
    headers["apikey"]
