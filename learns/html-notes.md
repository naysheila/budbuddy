<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>BuddBuddy 💰✨</title>
  <link rel="stylesheet" href="style.css">
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">
</head>
<body>
  > Headernyaaaaa
  <header class="hero">
    <div class="container">
      <div class="hero-content">
        <div class="money-float">
          <span class="coin">🪙</span>
          <span class="coin">💰</span>
          <span class="coin">💵</span>
        </div>
        
        <h1 class="main-title">
          <!-- <span class="title-gradient">Budgeting</span><br> -->
          <span class="title-gradient">BuddBuddy!</span>
        </h1>
        
        <p class="hero-subtitle">Ayo kelola uangmu dengan cerdas pakai metode <strong>50/30/20</strong>! 🥰</p>
        
        <a href="budget.html" class="cta-button">
          <span>🚀 start your money journey</span>
          <div class="button-glow"></div>
        </a>
      </div>
    </div>
  </header>

  <!-- Penjelasan Metode 50/30/20 -->
  <section class="method-section">
    <div class="container">
      <h2 class="section-title">💡 Metode 50/30/20 Itu Apa?</h2>
      
      <div class="method-grid">
        <!-- Kebutuhan (50%) -->
        <div class="method-card needs">
          <div class="card-icon">🏠</div>
          <h3>50% Kebutuhan</h3>
          <p>Bayar tagihan, makan, transportasi, dan kebutuhan pokok lainnya.</p>
          <div class="percentage">50%</div>
        </div>

        <!-- Keinginan (30%) -->
        <div class="method-card wants">
          <div class="card-icon">☕</div>
          <h3>30% Keinginan</h3>
          <p>Hiburan, jajan, belanja fashion, atau traveling kecil-kecilan.</p>
          <div class="percentage">30%</div>
        </div>

        <!-- Tabungan (20%) -->
        <div class="method-card savings">
          <div class="card-icon">💎</div>
          <h3>20% Tabungan</h3>
          <p>Investasi, dana darurat, atau tabungan impian masa depanmu!</p>
          <div class="percentage">20%</div>
        </div>
      </div>
    </div>
  </section>

  <!-- Statistik Singkat -->
  <section class="stats-section">
    <div class="container">
      <div class="stats-grid">
        <div class="stat-item">
          <span class="stat-number" data-target="50">50</span>
          <span class="stat-label">%</span>
          <p>Kebutuhan</p>
        </div>
        <div class="stat-item">
          <span class="stat-number" data-target="30">30</span>
          <span class="stat-label">%</span>
          <p>Keinginan</p>
        </div>
        <div class="stat-item">
          <span class="stat-number" data-target="20">20</span>
          <span class="stat-label">%</span>
          <p>Tabungan</p>
        </div>
      </div>
    </div>
  </section>

  <script src="script.js"></script>
</body>
</html>
