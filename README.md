# ali
<!doctype html>
<html lang="id">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Ali Irawan — Profil</title>
  <meta name="description" content="Profil Ali Irawan — Mahasiswa D3 Perencanaan Sumberdaya Lahan, Universitas Jenderal Soedirman." />
  <style>
    :root{
      --bg:#0f1724; /* dark blue-gray */
      --card:#0b1220;
      --muted:#94a3b8;
      --accent:#60a5fa;
      --glass: rgba(255,255,255,0.03);
      --radius:16px;
      --maxw:900px;
      color-scheme: dark;
      color: #e6eef8;
      font-family: Inter, ui-sans-serif, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
    }
    html,body{height:100%;margin:0;background:linear-gradient(180deg,var(--bg),#071020);display:flex;align-items:center;justify-content:center;padding:32px}
    .container{width:100%;max-width:var(--maxw)}

    .card{background:linear-gradient(180deg,rgba(255,255,255,0.02), rgba(255,255,255,0.01));border-radius:var(--radius);padding:28px;box-shadow:0 6px 30px rgba(2,6,23,0.6);backdrop-filter:blur(6px);display:grid;grid-template-columns:180px 1fr;gap:20px;align-items:start}

    .avatar{width:180px;height:180px;border-radius:14px;overflow:hidden;display:flex;align-items:center;justify-content:center;background:linear-gradient(135deg,var(--accent),#7dd3fc);font-weight:700;font-size:18px;color:#04263b}
    .avatar img{width:100%;height:100%;object-fit:cover;display:block}

    h1{margin:0;font-size:24px}
    .meta{color:var(--muted);margin-top:6px;font-size:14px}

    .section{margin-top:18px}
    .grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:12px}
    .small-card{background:var(--glass);padding:12px;border-radius:12px}

    p{line-height:1.5;margin:0}
    .label{font-weight:600;color:var(--accent);font-size:13px}

    .footer{margin-top:18px;display:flex;gap:12px;flex-wrap:wrap}
    a.btn{display:inline-block;padding:10px 14px;border-radius:10px;background:linear-gradient(90deg,var(--accent),#38bdf8);color:#052033;text-decoration:none;font-weight:700}
    a.ghost{padding:10px 14px;border-radius:10px;border:1px solid rgba(255,255,255,0.06);text-decoration:none;color:var(--muted);background:transparent}

    @media (max-width:640px){.card{grid-template-columns:1fr;}
      .avatar{width:140px;height:140px;margin:0 auto}
      .footer{justify-content:center}
    }
  </style>
</head>
<body>
  <main class="container">
    <article class="card" aria-labelledby="nama">
      <div>
        <div class="avatar" aria-hidden="true">
          <!-- Ganti dengan foto Anda: <img src="foto.jpg" alt="Ali Irawan"> -->
          AI
        </div>
      </div>

      <div>
        <header>
          <h1 id="nama">Ali Irawan</h1>
          <div class="meta">Lahir di Banjarnegara — 20 Maret 2007</div>
        </header>

        <section class="section">
          <div class="label">Tentang Saya</div>
          <p style="margin-top:8px">Halo! Saya Ali Irawan. Saat ini saya sedang menempuh pendidikan di Universitas Jenderal Soedirman pada program D3 Perencanaan Sumberdaya Lahan, Fakultas Pertanian. Saya tertarik pada perencanaan lahan, konservasi tanah, dan penerapan praktik pertanian berkelanjutan.</p>
        </section>

        <section class="section">
          <div class="label">Pendidikan</div>
          <div class="grid" style="margin-top:8px">
            <div class="small-card">
              <div style="font-weight:700">D3 Perencanaan Sumberdaya Lahan</div>
              <div class="meta">Universitas Jenderal Soedirman — Fakultas Pertanian</div>
            </div>
            <div class="small-card">
              <div style="font-weight:700">Asal</div>
              <div class="meta">Banjarnegara</div>
            </div>
          </div>
        </section>

        <section class="section">
          <div class="label">Keahlian (contoh)</div>
          <div class="grid" style="margin-top:8px">
            <div class="small-card"><div style="font-weight:600">Perencanaan Lahan</div><div class="meta">Analisis tata guna lahan dan pemetaan sederhana</div></div>
            <div class="small-card"><div style="font-weight:600">Konservasi Tanah</div><div class="meta">Praktik konservasi dan pengelolaan erosi</div></div>
            <div class="small-card"><div style="font-weight:600">Penggunaan GIS (dasar)</div><div class="meta">Pengolahan data spasial dan peta</div></div>
          </div>
        </section>

        <section class="section">
          <div class="label">Kontak & Tautan</div>
          <div style="margin-top:8px;display:flex;gap:8px;flex-wrap:wrap">
            <a class="btn" href="#">Hubungi Saya</a>
            <a class="ghost" href="#">GitHub</a>
            <a class="ghost" href="#">LinkedIn</a>
          </div>
        </section>

        <div class="footer">
          <small class="meta">Halaman ini dibuat untuk profil singkat. Ganti foto dan tautan sesuai kebutuhan.</small>
        </div>
      </div>
    </article>
  </main>
</body>
</html>
