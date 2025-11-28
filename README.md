
<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Jusvara — Platform Hukum RAG</title>
<meta name="description" content="Jusvara — Platform Hukum RAG dan Legal AI Engineered in Indonesia. Solusi hukum modern berbasis AI untuk masyarakat dan profesional.">
<style>
  /* ===== Global Styles ===== */
  body {
    margin: 0;
    font-family: 'Inter', sans-serif;
    background-color: #0A0F1F;
    color: #FFFFFF;
    scroll-behavior: smooth;
  }
  a { text-decoration: none; color: inherit; }
  section { padding: 80px 10%; }
  h1, h2, h3 { margin: 0 0 20px 0; }
  p { margin: 0 0 15px 0; line-height: 1.6; }

  /* ===== Hero Section ===== */
  .hero {
    background: linear-gradient(135deg, #0088CC, #00B7FF);
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    text-align: center;
    min-height: 90vh;
    transition: background 0.5s;
  }
  .hero:hover { background: linear-gradient(135deg, #00B7FF, #0088CC); }
  .hero h1 {
    font-family: 'Orbitron', sans-serif;
    font-size: 3em;
    font-weight: 700;
    color: #FFFFFF;
  }
  .hero p { font-size: 1.3em; margin-top: 15px; }
  .hero .cta-buttons { margin-top: 30px; }
  .cta-buttons a {
    display: inline-block;
    margin: 0 10px;
    padding: 15px 30px;
    border-radius: 12px;
    font-weight: 600;
    transition: all 0.3s ease;
    box-shadow: 0 0 10px rgba(0,183,255,0.5);
  }
  .cta-primary {
    background-color: #00B7FF;
    color: #0A0F1F;
  }
  .cta-primary:hover {
    background-color: #00E0FF;
    transform: scale(1.05);
    box-shadow: 0 0 20px rgba(0,224,255,0.8);
  }
  .cta-secondary {
    background-color: transparent;
    border: 2px solid #00B7FF;
    color: #FFFFFF;
  }
  .cta-secondary:hover {
    background-color: #00B7FF;
    color: #0A0F1F;
    transform: scale(1.05);
    box-shadow: 0 0 15px rgba(0,183,255,0.6);
  }

  /* ===== Two-Step Section ===== */
  .steps {
    display: flex;
    flex-direction: column;
    align-items: center;
    text-align: center;
  }
  .step {
    background: #0C1525;
    border-radius: 15px;
    padding: 30px;
    margin: 15px 0;
    width: 100%;
    max-width: 500px;
    box-shadow: 0 0 20px rgba(0,183,255,0.5);
    transition: transform 0.3s, box-shadow 0.3s;
  }
  .step:hover {
    transform: translateY(-5px);
    box-shadow: 0 0 25px rgba(0,224,255,0.7);
  }
  .step h3 { color: #00B7FF; }

  /* ===== Features Section ===== */
  .features {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-around;
  }
  .feature-card {
    background: #0C1525;
    border-radius: 12px;
    padding: 25px;
    margin: 15px;
    width: 280px;
    box-shadow: 0 0 15px rgba(0,183,255,0.3);
    transition: transform 0.3s, box-shadow 0.3s;
  }
  .feature-card:hover {
    transform: translateY(-5px);
    box-shadow: 0 0 25px rgba(0,224,255,0.6);
  }

  /* ===== Footer ===== */
  footer {
    background-color: #081223;
    padding: 40px 10%;
    text-align: center;
    font-size: 0.9em;
    color: #AAAAAA;
  }

  /* ===== Responsive ===== */
  @media (max-width: 768px) {
    .features { flex-direction: column; align-items: center; }
    .feature-card { width: 90%; }
    .hero h1 { font-size: 2.5em; }
  }
</style>
</head>
<body>

<!-- ========================= -->
<!-- JUSVARA ULTIMATE FRONTEND -->
<!-- ========================= -->

<!-- Hero Section -->
<section class="hero">
  <h1>Jusvara</h1>
  <p>Platform Hukum RAG — Legal AI Engineered in Indonesia</p>
  <div class="cta-buttons">
    <a href="#steps" class="cta-primary">Mulai Konsultasi</a>
    <a href="#features" class="cta-secondary">Pelajari Platform</a>
  </div>
</section>

<!-- Two-Step / Project Flow Section -->
<section id="steps" class="steps">
  <h2>Cara Kerja Jusvara</h2>
  <div class="step">
    <h3>1. Ajukan Masalah Hukum</h3>
    <p>Ketik pertanyaan atau unggah dokumen, cepat dan mudah.</p>
  </div>
  <div class="step">
    <h3>2. Terima Analisis Otomatis</h3>
    <p>Sistem Hukum-RAG menampilkan jawaban akurat, terstruktur, siap dipahami.</p>
  </div>
</section>

<!-- Features Section -->
<section id="features">
  <h2>Fitur Utama</h2>
  <div class="features">
    <div class="feature-card">
      <h3>Mesin RAG Hukum Terintegrasi</h3>
      <p>Memproses data hukum otomatis dengan presisi tinggi.</p>
    </div>
    <div class="feature-card">
      <h3>Jawaban Terverifikasi & Terstruktur</h3>
      <p>Hasil analisis langsung bisa dipahami masyarakat awam maupun profesional.</p>
    </div>
    <div class="feature-card">
      <h3>Aksesibilitas 24/7</h3>
      <p>Jusvara siap membantu kapan saja, dari laptop atau HP.</p>
    </div>
    <div class="feature-card">
      <h3>Tingkat Akurasi Profesional</h3>
      <p>Data dan referensi hukum selalu diperbarui secara berkala.</p>
    </div>
  </div>
</section>

<!-- Project Table Ultimate -->
<section id="projects" class="projects">
  <h2>Project Table Ultimate</h2>
  <table class="project-table">
    <thead>
      <tr>
        <th>Proyek</th>
        <th>Status</th>
        <th>Prioritas</th>
        <th>Deadline</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Integrasi Modul AI</td>
        <td>Pending</td>
        <td>Tinggi</td>
        <td>Des 2025</td>
      </tr>
      <tr>
        <td>Penyempurnaan Frontend</td>
        <td>Aktif</td>
        <td>Menengah</td>
        <td>Nov 2025</td>
      </tr>
      <tr>
        <td>RAG Legal Testing</td>
        <td>Siap</td>
        <td>Tinggi</td>
        <td>Jan 2026</td>
      </tr>
    </tbody>
  </table>
</section>

<!-- Ecosystem Section -->
<section id="ecosystem">
  <h2>Ekosistem Vertikal AI</h2>
  <p>Terhubung dengan modul Legal Drafting AI, Case Finder AI, Regulation Explorer, dan Library Hukum Cerdas.</p>
</section>

<!-- Contact & Footer -->
<section id="contact">
  <h2>Kontak & Footer</h2>
  <p>Email: contact@jusvara.ai</p>
  <p>© 2025 Jusvara — Platform Hukum RAG</p>
</section>

<!-- ===== CSS & JS Minimal ===== -->
<style>
body { font-family: 'Arial', sans-serif; background:#0A0F1F; color:#FFFFFF; margin:0; padding:0; }
.hero { text-align:center; padding:80px 20px; background:#081223; }
.hero h1 { font-size:3em; color:#00B7FF; margin-bottom:15px; }
.hero p { font-size:1.3em; margin-bottom:30px; }
.cta-buttons a { display:inline-block; margin:0 10px; padding:15px 30px; border-radius:12px; font-weight:600; transition:all 0.3s ease; box-shadow:0 0 10px rgba(0,183,255,0.5); text-decoration:none; }
.cta-primary { background-color:#00B7FF; color:#0A0F1F; }
.cta-primary:hover { background-color:#00E0FF; transform:scale(1.05); box-shadow:0 0 20px rgba(0,224,255,0.8); }
.cta-secondary { background-color:transparent; border:2px solid #00B7FF; color:#FFFFFF; }
.cta-secondary:hover { background-color:#00B7FF; color:#0A0F1F; transform:scale(1.05); box-shadow:0 0 15px rgba(0,183,255,0.6); }

.steps { display:flex; flex-direction:column; align-items:center; text-align:center; padding:40px 20px; }
.step { background:#0C1525; border-radius:15px; padding:30px; margin:15px 0; width:100%; max-width:500px; box-shadow:0 0 20px rgba(0,183,255,0.5); transition:transform 0.3s, box-shadow 0.3s; }
.step:hover { transform:translateY(-5px); box-shadow:0 0 25px rgba(0,224,255,0.7); }
.step h3 { color:#00B7FF; }

.features { display:flex; flex-wrap:wrap; justify-content:space-around; padding:40px 20px; }
.feature-card { background:#0C1525; border-radius:12px; padding:25px; margin:15px; width:280px; box-shadow:0 0 15px rgba(0,183,255,0.3); transition:transform 0.3s, box-shadow 0.3s; }
.feature-card:hover { transform:translateY(-5px); box-shadow:0 0 25px rgba(0,224,255,0.6); }

.projects { padding:40px 20px; text-align:center; }
.project-table { width:100%; border-collapse:collapse; margin-top:20px; }
.project-table th, .project-table td { border:1px solid #00B7FF; padding:12px; text-align:center; }
.project-table th { background:#081223; color:#00B7FF; }

#ecosystem, #contact { padding:40px 20px; text-align:center; }

@media (max-width:768px) {
  .features { flex-direction:column; align-items:center; }
  .feature-card { width:90%; margin:10px 0; }
  .hero h1 { font-size:2.5em; }
  .step { width:90%; }
  .project-table th, .project-table td { font-size:0.9em; padding:8px; }
}
</style>

<script>
// Placeholder JS untuk integrasi backend modul AI
document.querySelectorAll('.cta-primary').forEach(btn => {
  btn.addEventListener('click', e => {
    alert("Modul AI siap integrasi backend. Nanti panggil RAG engine di sini.");
  });
});
</script>

<!-- Hero Section -->
<section class="hero">
  <h1>Jusvara</h1>
  <p>Platform Hukum RAG — Legal AI Engineered in Indonesia</p>
  <div class="cta-buttons">
    <a href="#steps" class="cta-primary">Mulai Konsultasi</a>
    <a href="#features" class="cta-secondary">Pelajari Platform</a>
  </div>
</section>

<section class="hero">
  <h1>Jusvara</h1>
  <p>Platform Hukum RAG — Legal AI Engineered in Indonesia</p>
  ...
</section>

<section id="steps" class="steps">

<!-- Project Table Ultimate -->
<section id="project-table">
  <!-- Paste seluruh kode Ultimate di sini -->
</section>

<!-- Mulai Project Table Ultimate -->
...kode Ultimate...
<!-- Selesai Project Table Ultimate -->

<!-- Two-Step Section -->
<section id="steps" class="steps">
  <h2>Cara Kerja Jusvara</h2>
  <div class="step">
    <h3>1. Ajukan Masalah Hukum</h3>
    <p>Ketik pertanyaan atau unggah dokumen, mudah dan cepat.</p>
  </div>
  <div class="step">
    <h3>2. Terima Analisis Otomatis</h3>
    <p>Sistem Hukum-RAG menampilkan jawaban akurat, terstruktur, dan siap dipahami.</p>
  </div>
</section>

<!-- Features Section -->
<section id="features">
  <h2>Fitur Utama</h2>
  <div class="features">
    <div class="feature-card">
      <h3>Mesin RAG Hukum Terintegrasi</h3>
      <p>Memproses data hukum secara otomatis dengan presisi tinggi.</p>
    </div>
    <div class="feature-card">
      <h3>Jawaban Terverifikasi & Terstruktur</h3>
      <p>Hasil analisis langsung bisa dipahami masyarakat awam maupun profesional.</p>
    </div>
    <div class="feature-card">
      <h3>Aksesibilitas 24/7</h3>
      <p>Jusvara siap membantu kapan saja, dari laptop atau HP.</p>
    </div>
    <div class="feature-card">
      <h3>Tingkat Akurasi Profesional</h3>
      <p>Data dan referensi hukum selalu diperbarui secara berkala.</p>
    </div>
  </div>
</section>

<!-- Additional Homepage Sections -->
<section id="benefits">
  <h2>Manfaat untuk Pengguna</h2>
  <p>Mempercepat pemahaman hukum, mengurangi biaya konsultasi awal, membantu mahasiswa dan praktisi, dan menyediakan solusi modern yang mudah diakses.</p>
</section>

<section id="ecosystem">
  <h2>Ekosistem Vertikal AI</h2>
  <p>Terhubung dengan modul Legal Drafting AI, Case Finder AI, Regulation Explorer, dan Library Hukum Cerdas.</p>
</section>

<section id="contact">
  <h2>Kontak & Footer</h2>
  <p>Email: contact@jusvara.ai</p>
  <p>© 2025 Jusvara — Platform Hukum RAG</p>
</section>

</body>
</html>
