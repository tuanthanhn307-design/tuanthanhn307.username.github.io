<!DOCTYPE html>
<html lang="vi" data-theme="dark">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Nguyễn Tuấn Thanh | Portfolio — Nhiếp ảnh & STEM</title>
  <meta name="description" content="Trang giới thiệu cá nhân của Nguyễn Tuấn Thanh - Học sinh lớp 11T2, Trường THPT Chuyên Bến Tre tại Vĩnh Long. Đam mê Nhiếp ảnh và STEM." />
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&family=JetBrains+Mono:wght@400;600&display=swap" rel="stylesheet" />

  <style>
    :root {
      --bg-primary: #0b0f17;
      --bg-secondary: #131a26;
      --bg-card: rgba(22, 30, 46, 0.75);
      --text-primary: #f1f5f9;
      --text-secondary: #94a3b8;
      --accent-stem: #38bdf8;
      --accent-photo: #f59e0b;
      --border-color: rgba(148, 163, 184, 0.16);
      --grid-color: rgba(56, 189, 248, 0.05);
      --shadow: 0 12px 32px rgba(0, 0, 0, 0.35);
    }

    [data-theme="light"] {
      --bg-primary: #f8fafc;
      --bg-secondary: #ffffff;
      --bg-card: rgba(255, 255, 255, 0.9);
      --text-primary: #0f172a;
      --text-secondary: #475569;
      --accent-stem: #0284c7;
      --accent-photo: #d97706;
      --border-color: rgba(15, 23, 42, 0.1);
      --grid-color: rgba(2, 132, 199, 0.06);
      --shadow: 0 10px 25px rgba(15, 23, 42, 0.08);
    }

    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    html {
      scroll-behavior: smooth;
      font-family: 'Inter', system-ui, -apple-system, sans-serif;
    }

    body {
      background-color: var(--bg-primary);
      color: var(--text-primary);
      line-height: 1.6;
      background-image:
        linear-gradient(to right, var(--grid-color) 1px, transparent 1px),
        linear-gradient(to bottom, var(--grid-color) 1px, transparent 1px);
      background-size: 36px 36px;
      transition: background-color 0.3s ease, color 0.3s ease;
    }

    .mono {
      font-family: 'JetBrains Mono', monospace;
    }

    .container {
      max-width: 1080px;
      margin: 0 auto;
      padding: 0 20px;
    }

    /* Sticky Header */
    header {
      position: sticky;
      top: 0;
      z-index: 100;
      backdrop-filter: blur(12px);
      -webkit-backdrop-filter: blur(12px);
      background: rgba(11, 15, 23, 0.8);
      border-bottom: 1px solid var(--border-color);
    }

    [data-theme="light"] header {
      background: rgba(248, 250, 252, 0.85);
    }

    .nav-wrapper {
      display: flex;
      justify-content: space-between;
      align-items: center;
      height: 68px;
    }

    .logo {
      font-weight: 800;
      font-size: 1.15rem;
      letter-spacing: -0.02em;
      text-decoration: none;
      color: var(--text-primary);
      display: flex;
      align-items: center;
      gap: 8px;
    }

    .logo-badge {
      font-size: 0.75rem;
      padding: 2px 8px;
      border-radius: 6px;
      background: rgba(56, 189, 248, 0.15);
      color: var(--accent-stem);
      border: 1px solid rgba(56, 189, 248, 0.3);
    }

    nav {
      display: flex;
      align-items: center;
      gap: 24px;
    }

    nav a {
      text-decoration: none;
      color: var(--text-secondary);
      font-size: 0.92rem;
      font-weight: 500;
      transition: color 0.2s;
    }

    nav a:hover {
      color: var(--accent-stem);
    }

    .theme-btn {
      background: var(--bg-card);
      border: 1px solid var(--border-color);
      color: var(--text-primary);
      padding: 6px 12px;
      border-radius: 8px;
      cursor: pointer;
      font-size: 0.85rem;
      font-weight: 600;
      transition: transform 0.2s, border-color 0.2s;
    }

    .theme-btn:hover {
      border-color: var(--accent-stem);
      transform: translateY(-1px);
    }

    /* Hero Section */
    .hero {
      padding: 72px 0 56px;
      display: grid;
      grid-template-columns: 1.2fr 0.8fr;
      gap: 40px;
      align-items: center;
    }

    .status-pill {
      display: inline-flex;
      align-items: center;
      gap: 8px;
      font-size: 0.82rem;
      padding: 6px 14px;
      border-radius: 999px;
      background: var(--bg-card);
      border: 1px solid var(--border-color);
      color: var(--accent-stem);
      margin-bottom: 18px;
    }

    .dot {
      width: 8px;
      height: 8px;
      border-radius: 50%;
      background: var(--accent-photo);
      box-shadow: 0 0 8px var(--accent-photo);
    }

    h1 {
      font-size: clamp(2.1rem, 4vw, 3.1rem);
      font-weight: 800;
      line-height: 1.15;
      letter-spacing: -0.03em;
      margin-bottom: 16px;
    }

    .highlight-stem {
      color: var(--accent-stem);
    }

    .highlight-photo {
      color: var(--accent-photo);
    }

    .hero-desc {
      color: var(--text-secondary);
      font-size: 1.05rem;
      margin-bottom: 28px;
      max-width: 560px;
    }

    .cta-group {
      display: flex;
      flex-wrap: wrap;
      gap: 14px;
    }

    .btn {
      display: inline-flex;
      align-items: center;
      gap: 8px;
      padding: 12px 22px;
      border-radius: 10px;
      font-weight: 600;
      font-size: 0.95rem;
      text-decoration: none;
      cursor: pointer;
      transition: all 0.2s ease;
      border: 1px solid transparent;
    }

    .btn-primary {
      background: var(--accent-stem);
      color: #090d16;
    }

    .btn-primary:hover {
      filter: brightness(1.1);
      transform: translateY(-2px);
    }

    .btn-outline {
      background: var(--bg-card);
      color: var(--text-primary);
      border-color: var(--border-color);
    }

    .btn-outline:hover {
      border-color: var(--accent-photo);
      transform: translateY(-2px);
    }

    /* Camera Viewfinder Card */
    .viewfinder {
      position: relative;
      background: var(--bg-card);
      border: 1px solid var(--border-color);
      border-radius: 18px;
      padding: 16px;
      box-shadow: var(--shadow);
    }

    .vf-header, .vf-footer {
      display: flex;
      justify-content: space-between;
      font-size: 0.75rem;
      color: var(--text-secondary);
      padding: 4px 6px;
    }

    .vf-rec {
      color: #ef4444;
      font-weight: 600;
    }

    .avatar-box {
      position: relative;
      width: 100%;
      aspect-ratio: 4 / 4.2;
      border-radius: 12px;
      overflow: hidden;
      margin: 8px 0;
      background: linear-gradient(135deg, #1e293b, #0f172a);
      display: flex;
      align-items: center;
      justify-content: center;
    }

    .avatar-box img {
      width: 100%;
      height: 100%;
      object-fit: cover;
      display: block;
    }

    .avatar-placeholder {
      text-align: center;
      padding: 20px;
      color: var(--text-secondary);
    }

    .crosshair {
      position: absolute;
      inset: 14px;
      border: 1px dashed rgba(245, 158, 11, 0.45);
      border-radius: 8px;
      pointer-events: none;
    }

    /* Sections */
    section {
      padding: 56px 0;
    }

    .section-header {
      margin-bottom: 32px;
    }

    .section-tag {
      font-size: 0.8rem;
      text-transform: uppercase;
      letter-spacing: 0.08em;
      color: var(--accent-stem);
      font-weight: 600;
      display: block;
      margin-bottom: 6px;
    }

    .section-title {
      font-size: 1.75rem;
      font-weight: 800;
      letter-spacing: -0.02em;
    }

    /* Info Strip */
    .info-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 16px;
    }

    .info-card {
      background: var(--bg-card);
      border: 1px solid var(--border-color);
      padding: 20px;
      border-radius: 14px;
      transition: transform 0.2s, border-color 0.2s;
    }

    .info-card:hover {
      transform: translateY(-3px);
      border-color: var(--accent-stem);
    }

    .info-label {
      font-size: 0.8rem;
      color: var(--text-secondary);
      margin-bottom: 4px;
    }

    .info-value {
      font-weight: 700;
      font-size: 1.05rem;
    }

    /* Skills Bento Grid */
    .skills-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 24px;
    }

    .skill-panel {
      background: var(--bg-card);
      border: 1px solid var(--border-color);
      border-radius: 16px;
      padding: 26px;
      box-shadow: var(--shadow);
    }

    .skill-panel.stem {
      border-top: 3px solid var(--accent-stem);
    }

    .skill-panel.photo {
      border-top: 3px solid var(--accent-photo);
    }

    .panel-title {
      font-size: 1.25rem;
      font-weight: 700;
      margin-bottom: 12px;
      display: flex;
      align-items: center;
      gap: 10px;
    }

    .skill-list {
      list-style: none;
      display: flex;
      flex-direction: column;
      gap: 12px;
      margin-top: 16px;
    }

    .skill-list li {
      padding: 10px 14px;
      border-radius: 10px;
      background: rgba(148, 163, 184, 0.06);
      border: 1px solid var(--border-color);
      font-size: 0.94rem;
    }

    .skill-list strong {
      display: block;
      margin-bottom: 2px;
    }

    /* Gallery */
    .gallery-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(290px, 1fr));
      gap: 20px;
    }

    .photo-card {
      position: relative;
      border-radius: 14px;
      overflow: hidden;
      background: var(--bg-card);
      border: 1px solid var(--border-color);
      aspect-ratio: 16 / 11;
    }

    .photo-card img {
      width: 100%;
      height: 100%;
      object-fit: cover;
      transition: transform 0.4s ease;
    }

    .photo-card:hover img {
      transform: scale(1.06);
    }

    .photo-overlay {
      position: absolute;
      inset: 0;
      background: linear-gradient(to top, rgba(11, 15, 23, 0.9), transparent 60%);
      display: flex;
      flex-direction: column;
      justify-content: flex-end;
      padding: 18px;
      color: #f8fafc;
    }

    .photo-meta {
      font-size: 0.75rem;
      color: var(--accent-photo);
      margin-bottom: 2px;
    }

    .photo-caption {
      font-weight: 600;
      font-size: 0.98rem;
    }

    /* Contact Box */
    .contact-box {
      background: var(--bg-card);
      border: 1px solid var(--border-color);
      border-radius: 18px;
      padding: 36px 28px;
      text-align: center;
      box-shadow: var(--shadow);
    }

    .contact-box p {
      color: var(--text-secondary);
      max-width: 540px;
      margin: 10px auto 24px;
    }

    .contact-actions {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      gap: 14px;
    }

    footer {
      border-top: 1px solid var(--border-color);
      padding: 28px 0;
      text-align: center;
      color: var(--text-secondary);
      font-size: 0.88rem;
    }

    @media (max-width: 820px) {
      .hero {
        grid-template-columns: 1fr;
        padding-top: 44px;
      }
      nav a {
        display: none;
      }
    }
  </style>
</head>
<body>

  <!-- Header -->
  <header>
    <div class="container nav-wrapper">
      <a href="#" class="logo">
        <span>NTT</span>
        <span class="logo-badge mono">11T2 // STEM &amp; PHOTO</span>
      </a>
      <nav>
        <a href="#gioi-thieu">Giới thiệu</a>
        <a href="#ky-nang">Kỹ năng</a>
        <a href="#bo-suu-tap">Góc Nhiếp ảnh</a>
        <a href="#lien-he">Liên hệ</a>
        <button class="theme-btn" id="themeToggle" aria-label="Đổi giao diện">☀️ Sáng</button>
      </nav>
    </div>
  </header>

  <main class="container">
    <!-- Hero Section -->
    <section class="hero">
      <div>
        <div class="status-pill mono">
          <span class="dot"></span>
          <span>Lớp 11T2 • THPT Chuyên Bến Tre (Vĩnh Long)</span>
        </div>
        <h1>
          Xin chào, mình là <br />
          <span class="highlight-stem">Nguyễn Tuấn Thanh</span>
        </h1>
        <p class="hero-desc">
          Mình là học sinh lớp <strong>11T2</strong> tại trường <strong>THPT Chuyên Bến Tre (tỉnh Vĩnh Long)</strong>. Mình yêu thích việc khám phá thế giới qua hai lăng kính: tư duy logic của <span class="highlight-stem"><strong>STEM</strong></span> và góc nhìn sáng tạo của <span class="highlight-photo"><strong>Nhiếp ảnh</strong></span>.
        </p>
        <div class="cta-group">
          <a href="#ky-nang" class="btn btn-primary">Khám phá kỹ năng</a>
          <a href="#bo-suu-tap" class="btn btn-outline">Xem góc nhiếp ảnh</a>
        </div>
      </div>

      <!-- Viewfinder Portrait Frame -->
      <div class="viewfinder">
        <div class="vf-header mono">
          <span class="vf-rec">● REC</span>
          <span>[ AF-C • RAW ]</span>
          <span>100%</span>
        </div>
        <div class="avatar-box">
          <!-- Khi có ảnh chân dung, bạn thay src bên dưới thành "images/anh-ca-nhan.jpg" -->
          <img src="images/anh-ca-nhan.jpg" alt="Chân dung Nguyễn Tuấn Thanh"
               onerror="this.style.display='none'; this.nextElementSibling.style.display='block';" />
          <div class="avatar-placeholder" style="display: none;">
            <p class="mono" style="font-size: 2rem; margin-bottom: 8px;">📷</p>
            <strong>Ảnh chân dung của bạn</strong>
            <p style="font-size: 0.85rem; margin-top: 6px;">Tải ảnh lên thư mục <code class="mono">images/anh-ca-nhan.jpg</code> trên GitHub để hiển thị tại đây.</p>
          </div>
          <div class="crosshair"></div>
        </div>
        <div class="vf-footer mono">
          <span>ISO 100</span>
          <span>f/1.8</span>
          <span>1/500s</span>
        </div>
      </div>
    </section>

    <!-- About & Academic Info -->
    <section id="gioi-thieu">
      <div class="section-header">
        <span class="section-tag mono">// 01. HỒ SƠ CÁ NHÂN</span>
        <h2 class="section-title">Thông tin cơ bản</h2>
      </div>
      <div class="info-grid">
        <div class="info-card">
          <div class="info-label">Họ và tên</div>
          <div class="info-value">Nguyễn Tuấn Thanh</div>
        </div>
        <div class="info-card">
          <div class="info-label">Đơn vị lớp</div>
          <div class="info-value">Lớp 11T2</div>
        </div>
        <div class="info-card">
          <div class="info-label">Trường học</div>
          <div class="info-value">THPT Chuyên Bến Tre</div>
        </div>
        <div class="info-card">
          <div class="info-label">Địa phương</div>
          <div class="info-value">Tỉnh Vĩnh Long</div>
        </div>
      </div>
    </section>

    <!-- Skills Section -->
    <section id="ky-nang">
      <div class="section-header">
        <span class="section-tag mono">// 02. NĂNG LỰC &amp; ĐAM MÊ</span>
        <h2 class="section-title">Kỹ năng STEM &amp; Nhiếp ảnh</h2>
      </div>
      <div class="skills-grid">
        <!-- STEM Card -->
        <div class="skill-panel stem">
          <div class="panel-title">
            <span>⚙️</span>
            <span>Kỹ năng STEM &amp; Kỹ thuật</span>
          </div>
          <p style="color: var(--text-secondary); font-size: 0.94rem;">
            Vận dụng kiến thức Khoa học, Công nghệ, Kỹ thuật và Toán học để thiết kế, chế tạo và giải quyết vấn đề thực tiễn.
          </p>
          <ul class="skill-list">
            <li>
              <strong>Tư duy Logic &amp; Giải quyết vấn đề</strong>
              Phân tích bài toán kỹ thuật, lên ý tưởng và tối ưu hóa giải pháp thực nghiệm.
            </li>
            <li>
              <strong>Điện tử &amp; Lập trình điều khiển</strong>
              Làm quen với vi điều khiển (Arduino), cảm biến cơ bản và xây dựng mô hình tự động hóa.
            </li>
            <li>
              <strong>Thiết kế &amp; Chế tạo mô hình</strong>
              Phác thảo ý tưởng kỹ thuật, lắp ráp mạch và thử nghiệm sản phẩm STEM học đường.
            </li>
          </ul>
        </div>

        <!-- Photography Card -->
        <div class="skill-panel photo">
          <div class="panel-title">
            <span>📸</span>
            <span>Kỹ năng Nhiếp ảnh</span>
          </div>
          <p style="color: var(--text-secondary); font-size: 0.94rem;">
            Lưu giữ những khoảnh khắc đời thường, kiến trúc và thiên nhiên thông qua bố cục và ánh sáng.
          </p>
          <ul class="skill-list">
            <li>
              <strong>Bố cục &amp; Kiểm soát ánh sáng</strong>
              Áp dụng quy tắc 1/3, đường dẫn, tận dụng ánh sáng tự nhiên (giờ vàng) và góc máy sáng tạo.
            </li>
            <li>
              <strong>Chụp ảnh Phong cảnh &amp; Đời sống</strong>
              Ghi lại nét đẹp học đường, hoạt động sự kiện và cảnh sắc miền Tây sông nước.
            </li>
            <li>
              <strong>Hậu kỳ &amp; Chỉnh màu (Color Grading)</strong>
              Cân bằng sáng, tinh chỉnh tương phản và tạo tông màu có chiều sâu cho bức ảnh.
            </li>
          </ul>
        </div>
      </div>
    </section>

    <!-- Gallery Section -->
    <section id="bo-suu-tap">
      <div class="section-header">
        <span class="section-tag mono">// 03. GÓC LƯU TRỮ</span>
        <h2 class="section-title">Khoảnh khắc Nhiếp ảnh &amp; Dự án STEM</h2>
      </div>
      <div class="gallery-grid">
        <div class="photo-card">
          <img src="https://images.unsplash.com/photo-1516035069371-29a1b244cc32?auto=format&fit=crop&w=800&q=80" alt="Góc máy nhiếp ảnh" />
          <div class="photo-overlay">
            <span class="photo-meta mono">PHOTOGRAPHY • 35MM f/1.8</span>
            <div class="photo-caption">Góc nhìn qua ống kính</div>
          </div>
        </div>
        <div class="photo-card">
          <img src="https://images.unsplash.com/photo-1518770660439-4636190af475?auto=format&fit=crop&w=800&q=80" alt="Mạch điện tử STEM" />
          <div class="photo-overlay">
            <span class="photo-meta mono">STEM LAB • HARDWARE</span>
            <div class="photo-caption">Khám phá mạch điện tử &amp; vi điều khiển</div>
          </div>
        </div>
        <div class="photo-card">
          <img src="https://images.unsplash.com/photo-1500530855697-b586d89ba3ee?auto=format&fit=crop&w=800&q=80" alt="Ánh sáng hoàng hôn" />
          <div class="photo-overlay">
            <span class="photo-meta mono">GOLDEN HOUR • ISO 100</span>
            <div class="photo-caption">Sắc màu ánh sáng tự nhiên</div>
          </div>
        </div>
      </div>
    </section>

    <!-- Contact Section -->
    <section id="lien-he">
      <div class="contact-box">
        <span class="section-tag mono">// 04. KẾT NỐI</span>
        <h2 class="section-title">Cùng giao lưu về Nhiếp ảnh &amp; STEM</h2>
        <p>
          Nếu bạn muốn trao đổi về các dự án STEM, chia sẻ kinh nghiệm chụp ảnh hoặc đơn giản là làm quen, đừng ngần ngại liên hệ với mình nhé!
        </p>
        <div class="contact-actions">
          <button class="btn btn-primary" id="copyInfoBtn">📋 Sao chép thông tin giới thiệu</button>
          <a href="https://github.com/" target="_blank" rel="noopener" class="btn btn-outline">💻 GitHub của mình</a>
        </div>
        <p id="copyFeedback" class="mono" style="font-size: 0.85rem; color: var(--accent-stem); margin-top: 12px; display: none;">
          ✓ Đã sao chép thông tin vào bộ nhớ tạm!
        </p>
      </div>
    </section>
  </main>

  <footer>
    <div class="container">
      <p>© 2026 <strong>Nguyễn Tuấn Thanh</strong> — Lớp 11T2, Trường THPT Chuyên Bến Tre (Vĩnh Long).</p>
    </div>
  </footer>

  <script>
    // Chuyển đổi chế độ Sáng / Tối
    const themeToggle = document.getElementById('themeToggle');
    const htmlEl = document.documentElement;

    themeToggle.addEventListener('click', () => {
      const isDark = htmlEl.getAttribute('data-theme') === 'dark';
      const nextTheme = isDark ? 'light' : 'dark';
      htmlEl.setAttribute('data-theme', nextTheme);
      themeToggle.textContent = nextTheme === 'dark' ? '☀️ Sáng' : '🌙 Tối';
    });

    // Nút sao chép nhanh thông tin cá nhân
    const copyBtn = document.getElementById('copyInfoBtn');
    const feedback = document.getElementById('copyFeedback');

    copyBtn.addEventListener('click', () => {
      const infoText = "Nguyễn Tuấn Thanh - Học sinh lớp 11T2, Trường THPT Chuyên Bến Tre (tỉnh Vĩnh Long). Đam mê Nhiếp ảnh & STEM.";
      navigator.clipboard.writeText(infoText).then(() => {
        feedback.style.display = 'block';
        setTimeout(() => {
          feedback.style.display = 'none';
        }, 3000);
      });
    });
  </script>
</body>
</html>
