<html lang="vi">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>CÔNG TY TNHH MTV KINGDOOR - Cửa Nhôm Xingfa & Kính Cường Lực Đà Nẵng | kingdoor.com</title>
  <meta name="description" content="CÔNG TY TNHH MTV KINGDOOR - Chuyên thiết kế, sản xuất và thi công Cửa nhôm Xingfa nhập khẩu, Cửa kính cường lực, Cửa nhựa lõi thép, Cửa tự động, Cầu thang kính, Kính ốp bếp, Phòng tắm kính tại Đà Nẵng. Địa chỉ: 502 Ngô Quyền, Sơn Trà, Đà Nẵng.">

  <!-- Thumbnail logo khi chia sẻ liên kết trang web (Open Graph & Twitter Card) -->
  <meta property="og:type" content="website">
  <meta property="og:site_name" content="CÔNG TY TNHH MTV KINGDOOR">
  <meta property="og:title" content="CÔNG TY TNHH MTV KINGDOOR - Cửa Nhôm Xingfa Đà Nẵng | kingdoor.com">
  <meta property="og:description" content="Thi công cửa nhôm Xingfa chính hãng, cửa kính cường lực, cửa nhựa lõi thép, phòng tắm kính, kính ốp bếp uy tín tại Đà Nẵng. Hotline: 0905.445.498 - 0905.39.82.68">
  <meta property="og:url" content="https://kingdoor.com">
  <meta property="og:image" content="https://lh3.googleusercontent.com/d/1bEUVC_WSn6CXUmYabU46kWxO5PBp2Iaq=w1200">
  <meta property="og:image:secure_url" content="https://lh3.googleusercontent.com/d/1bEUVC_WSn6CXUmYabU46kWxO5PBp2Iaq=w1200">
  <meta property="og:image:alt" content="Logo CÔNG TY TNHH MTV KINGDOOR">
  <meta name="twitter:card" content="summary_large_image">
  <meta name="twitter:title" content="CÔNG TY TNHH MTV KINGDOOR - kingdoor.com">
  <meta name="twitter:description" content="Cửa nhôm Xingfa nhập khẩu & Nhôm kính cao cấp tại Đà Nẵng - 502 Ngô Quyền, Sơn Trà, Đà Nẵng.">
  <meta name="twitter:image" content="https://lh3.googleusercontent.com/d/1bEUVC_WSn6CXUmYabU46kWxO5PBp2Iaq=w1200">
  <link rel="icon" type="image/png" href="https://drive.google.com/thumbnail?id=1bEUVC_WSn6CXUmYabU46kWxO5PBp2Iaq&sz=w128">

  <!-- Font chữ Inter chuẩn hiện đại & sắc nét tiếng Việt -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">

  <!-- Tailwind CSS -->
  <script src="https://cdn.tailwindcss.com"></script>
  <script>
    tailwind.config = {
      theme: {
        extend: {
          fontFamily: {
            sans: ['Inter', 'sans-serif'],
          },
          colors: {
            brand: {
              primary: 'var(--brand-primary)',
              dark: 'var(--brand-dark)',
              accent: 'var(--brand-accent)',
              light: 'var(--brand-light)',
            }
          }
        }
      }
    };
  </script>

  <style>
    /* ============================================================
       BIẾN MÀU CHỦ ĐẠO (TỰ ĐỘNG ĐỒNG BỘ THEO TÔNG LOGO KINGDOOR)
       ============================================================ */
    :root {
      --brand-primary: #0b3b75;
      --brand-dark: #07264d;
      --brand-accent: #d48806;
      --brand-light: #f0f5fb;
      --discount-red: #dc2626;
    }

    /* Chống tràn viền & lệch phải tuyệt đối trên mọi thiết bị */
    *, *::before, *::after {
      box-sizing: border-box;
    }

    html {
      scroll-behavior: smooth;
      overflow-x: hidden;
      width: 100%;
      max-width: 100%;
    }

    body {
      font-family: 'Inter', sans-serif;
      color: #1e293b;
      background-color: #ffffff;
      margin: 0;
      padding: 0;
      overflow-x: hidden;
      width: 100%;
      max-width: 100%;
      -webkit-font-smoothing: antialiased;
    }

    /* Khung container Flatsome chuẩn: 95% chiều rộng màn hình trên máy tính */
    .kd-container {
      width: 100%;
      max-width: 100%;
      margin-left: auto;
      margin-right: auto;
      padding-left: 12px;
      padding-right: 12px;
    }

    @media (min-width: 768px) {
      .kd-container {
        width: 96%;
        max-width: 96%;
        padding-left: 16px;
        padding-right: 16px;
      }
    }

    @media (min-width: 1024px) {
      .kd-container {
        width: 95%;
        max-width: 95%;
        padding-left: 0;
        padding-right: 0;
      }
    }

    /* Menu máy tính viết liền 1 hàng, không bao giờ gãy xuống dòng bên trong tên danh mục */
    .desktop-nav-list {
      display: flex;
      flex-wrap: wrap;
      align-items: center;
      justify-content: flex-end;
      gap: 2px 4px;
      margin: 0;
      padding: 0;
      list-style: none;
    }

    .desktop-nav-item {
      position: relative;
      flex-shrink: 0;
    }

    .desktop-nav-link {
      display: inline-flex;
      align-items: center;
      gap: 3px;
      white-space: nowrap;
      font-size: 12px;
      font-weight: 600;
      text-transform: uppercase;
      letter-spacing: 0.01em;
      color: #1e293b;
      padding: 8px 7px;
      border-radius: 6px;
      transition: color 0.2s ease, background-color 0.2s ease;
    }

    @media (min-width: 1280px) {
      .desktop-nav-link {
        font-size: 12.5px;
        padding: 8px 10px;
      }
    }

    .desktop-nav-link:hover,
    .desktop-nav-link.active {
      color: var(--brand-primary);
      background-color: var(--brand-light);
    }

    /* Menu thả xuống Flatsome mượt mà */
    .desktop-dropdown {
      position: absolute;
      top: 100%;
      left: 0;
      min-width: 230px;
      background: #ffffff;
      border: 1px solid #e2e8f0;
      border-top: 3px solid var(--brand-primary);
      border-radius: 0 0 8px 8px;
      box-shadow: 0 12px 28px rgba(15, 23, 42, 0.12);
      opacity: 0;
      visibility: hidden;
      transform: translateY(6px);
      transition: all 0.2s ease;
      z-index: 60;
      padding: 6px 0;
    }

    .desktop-nav-item:hover .desktop-dropdown,
    .desktop-nav-item:focus-within .desktop-dropdown {
      opacity: 1;
      visibility: visible;
      transform: translateY(0);
    }

    .desktop-dropdown a {
      display: block;
      padding: 9px 16px;
      font-size: 13px;
      font-weight: 500;
      color: #334155;
      white-space: nowrap;
      transition: background-color 0.15s ease, color 0.15s ease, padding-left 0.15s ease;
    }

    .desktop-dropdown a:hover {
      background-color: var(--brand-light);
      color: var(--brand-primary);
      padding-left: 20px;
    }

    /* Slider 2 banner tự trượt: 2 slide có chiều cao đồng đều tuyệt đối bằng CSS Grid */
    .banner-stage {
      display: grid;
      grid-template-columns: 1fr;
      width: 100%;
      position: relative;
      overflow: hidden;
    }

    .banner-slide {
      grid-area: 1 / 1;
      width: 100%;
      opacity: 0;
      visibility: hidden;
      pointer-events: none;
      transition: opacity 0.65s ease-in-out, visibility 0.65s ease-in-out;
    }

    .banner-slide.is-active {
      opacity: 1;
      visibility: visible;
      pointer-events: auto;
      z-index: 2;
    }

    /* Tiêu đề mục kiểu Flatsome gọn gàng */
    .flatsome-heading {
      position: relative;
      display: inline-block;
      padding-bottom: 10px;
    }

    .flatsome-heading::after {
      content: "";
      position: absolute;
      left: 50%;
      bottom: 0;
      transform: translateX(-50%);
      width: 64px;
      height: 3px;
      border-radius: 999px;
      background-color: var(--brand-accent);
    }

    .flatsome-heading-left::after {
      left: 0;
      transform: none;
    }

    /* Hiệu ứng rung nhẹ cho nút Hotline nổi bật */
    @keyframes pulseRing {
      0% { box-shadow: 0 0 0 0 rgba(220, 38, 38, 0.55); }
      70% { box-shadow: 0 0 0 12px rgba(220, 38, 38, 0); }
      100% { box-shadow: 0 0 0 0 rgba(220, 38, 38, 0); }
    }

    .pulse-hotline {
      animation: pulseRing 2s infinite;
    }
  </style>
</head>
<body class="bg-white text-slate-800 pb-16 lg:pb-0">

  <!-- ============================================================
       HEADER CHÍNH (FLATSOME - GỌN GÀNG, KHÔNG NÚT GỌI NGAY)
       ============================================================ -->
  <header class="sticky top-0 z-50 bg-white/95 backdrop-blur border-b border-slate-200 shadow-sm w-full">
    <div class="kd-container">
      <div class="flex items-center justify-between gap-3 py-2.5">
        <!-- Logo Kingdoor chỉnh gọn nhỏ sắc nét -->
        <a href="#trang-chu" class="flex items-center gap-2.5 shrink-0 focus:outline-none">
          <img
            id="brandLogoImg"
            src="https://drive.google.com/thumbnail?id=1bEUVC_WSn6CXUmYabU46kWxO5PBp2Iaq&sz=w400"
            data-drive-id="1bEUVC_WSn6CXUmYabU46kWxO5PBp2Iaq"
            alt="Logo CÔNG TY TNHH MTV KINGDOOR"
            class="h-10 sm:h-11 w-auto max-w-[140px] object-contain rounded"
            onerror="handleDriveImgError(this, '1bEUVC_WSn6CXUmYabU46kWxO5PBp2Iaq', 'KINGDOOR')"
          >
          <div class="leading-tight hidden sm:block lg:hidden xl:block">
            <span class="block text-sm font-extrabold tracking-tight text-brand-primary">KINGDOOR</span>
            <span class="block text-[10px] font-medium text-slate-500 uppercase tracking-wider">kingdoor.com</span>
          </div>
        </a>

        <!-- Menu máy tính: 1 hàng liền mạch, chữ nhỏ gọn, không xuống dòng tên danh mục -->
        <nav class="hidden lg:block flex-1 min-w-0" aria-label="Danh mục chính">
          <ul class="desktop-nav-list">
            <li class="desktop-nav-item">
              <a href="#trang-chu" class="desktop-nav-link active">Trang chủ</a>
            </li>
            <li class="desktop-nav-item">
              <a href="#gioi-thieu" class="desktop-nav-link">Giới thiệu</a>
            </li>
            <li class="desktop-nav-item">
              <a href="#san-pham-xingfa" class="desktop-nav-link" onclick="filterProducts('all')">
                <span>Cửa nhôm xingfa</span>
                <svg class="w-3 h-3 shrink-0" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2.5" d="M19 9l-7 7-7-7"/></svg>
              </a>
              <div class="desktop-dropdown">
                <a href="#san-pham-xingfa" onclick="filterProducts('1-canh')">Cửa nhôm xingfa 1 cánh</a>
                <a href="#san-pham-xingfa" onclick="filterProducts('2-canh')">Cửa nhôm xingfa 2 cánh</a>
                <a href="#san-pham-xingfa" onclick="filterProducts('3-canh')">Cửa nhôm xingfa 3 cánh</a>
                <a href="#san-pham-xingfa" onclick="filterProducts('4-canh')">Cửa nhôm xingfa 4 cánh</a>
                <a href="#san-pham-xingfa" onclick="filterProducts('5-canh')">Cửa nhôm xingfa 5 cánh</a>
              </div>
            </li>
            <li class="desktop-nav-item">
              <a href="#danh-muc-san-pham" class="desktop-nav-link">Cửa kính cường lực</a>
            </li>
            <li class="desktop-nav-item">
              <a href="#danh-muc-san-pham" class="desktop-nav-link">
                <span>Sản phẩm</span>
                <svg class="w-3 h-3 shrink-0" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2.5" d="M19 9l-7 7-7-7"/></svg>
              </a>
              <div class="desktop-dropdown">
                <a href="#san-pham-xingfa" onclick="filterProducts('all')">Cửa nhôm xingfa</a>
                <a href="#danh-muc-san-pham">Cửa nhựa lõi thép</a>
                <a href="#danh-muc-san-pham">Cửa kính tự động</a>
                <a href="#danh-muc-san-pham">Cầu thang kính</a>
                <a href="#danh-muc-san-pham">Kính ốp bếp</a>
                <a href="#danh-muc-san-pham">Phòng tắm kính</a>
              </div>
            </li>
            <li class="desktop-nav-item">
              <a href="#cong-trinh" class="desktop-nav-link">Công trình</a>
            </li>
            <li class="desktop-nav-item">
              <a href="#bao-gia" class="desktop-nav-link">Báo giá</a>
            </li>
            <li class="desktop-nav-item">
              <a href="#tin-tuc" class="desktop-nav-link">Tin tức</a>
            </li>
            <li class="desktop-nav-item">
              <a href="#lien-he" class="desktop-nav-link">Liên hệ</a>
            </li>
          </ul>
        </nav>

        <!-- Nút mở menu trên điện thoại & máy tính bảng -->
        <button
          id="mobileMenuBtn"
          type="button"
          class="lg:hidden inline-flex items-center justify-center p-2.5 rounded-lg border border-slate-200 text-slate-700 hover:bg-slate-100 focus:outline-none"
          aria-label="Mở danh mục trang web"
          aria-expanded="false"
        >
          <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16"/>
          </svg>
        </button>
      </div>
    </div>

    <!-- Menu trượt dọc cho Điện thoại (Dễ chạm, đầy đủ danh mục con) -->
    <div id="mobileMenuDrawer" class="hidden lg:hidden bg-white border-t border-slate-200 shadow-lg max-h-[80vh] overflow-y-auto">
      <div class="kd-container py-3 space-y-1">
        <a href="#trang-chu" onclick="closeMobileMenu()" class="block px-3 py-2.5 rounded-lg text-sm font-semibold text-slate-800 hover:bg-brand-light hover:text-brand-primary">Trang chủ</a>
        <a href="#gioi-thieu" onclick="closeMobileMenu()" class="block px-3 py-2.5 rounded-lg text-sm font-semibold text-slate-800 hover:bg-brand-light hover:text-brand-primary">Giới thiệu</a>

        <!-- Accordion: Cửa nhôm xingfa -->
        <div class="rounded-lg border border-slate-100">
          <div class="flex items-center justify-between px-3 py-2.5">
            <a href="#san-pham-xingfa" onclick="filterProducts('all'); closeMobileMenu();" class="text-sm font-semibold text-slate-800">Cửa nhôm xingfa</a>
            <button type="button" onclick="toggleMobileSub('subXingfa', this)" class="p-1.5 rounded bg-slate-100 text-slate-600" aria-label="Mở danh mục Cửa nhôm xingfa">
              <svg class="w-4 h-4 transition-transform duration-200" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"/></svg>
            </button>
          </div>
          <div id="subXingfa" class="hidden bg-slate-50 px-4 pb-2.5 pt-1 space-y-1.5 border-t border-slate-100">
            <a href="#san-pham-xingfa" onclick="filterProducts('1-canh'); closeMobileMenu();" class="block py-1.5 text-sm text-slate-600 hover:text-brand-primary">+ Cửa nhôm xingfa 1 cánh</a>
            <a href="#san-pham-xingfa" onclick="filterProducts('2-canh'); closeMobileMenu();" class="block py-1.5 text-sm text-slate-600 hover:text-brand-primary">+ Cửa nhôm xingfa 2 cánh</a>
            <a href="#san-pham-xingfa" onclick="filterProducts('3-canh'); closeMobileMenu();" class="block py-1.5 text-sm text-slate-600 hover:text-brand-primary">+ Cửa nhôm xingfa 3 cánh</a>
            <a href="#san-pham-xingfa" onclick="filterProducts('4-canh'); closeMobileMenu();" class="block py-1.5 text-sm text-slate-600 hover:text-brand-primary">+ Cửa nhôm xingfa 4 cánh</a>
            <a href="#san-pham-xingfa" onclick="filterProducts('5-canh'); closeMobileMenu();" class="block py-1.5 text-sm text-slate-600 hover:text-brand-primary">+ Cửa nhôm xingfa 5 cánh</a>
          </div>
        </div>

        <a href="#danh-muc-san-pham" onclick="closeMobileMenu()" class="block px-3 py-2.5 rounded-lg text-sm font-semibold text-slate-800 hover:bg-brand-light hover:text-brand-primary">Cửa kính cường lực</a>

        <!-- Accordion: Sản phẩm -->
        <div class="rounded-lg border border-slate-100">
          <div class="flex items-center justify-between px-3 py-2.5">
            <a href="#danh-muc-san-pham" onclick="closeMobileMenu()" class="text-sm font-semibold text-slate-800">Sản phẩm</a>
            <button type="button" onclick="toggleMobileSub('subSanPham', this)" class="p-1.5 rounded bg-slate-100 text-slate-600" aria-label="Mở danh mục Sản phẩm">
              <svg class="w-4 h-4 transition-transform duration-200" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"/></svg>
            </button>
          </div>
          <div id="subSanPham" class="hidden bg-slate-50 px-4 pb-2.5 pt-1 space-y-1.5 border-t border-slate-100">
            <a href="#san-pham-xingfa" onclick="filterProducts('all'); closeMobileMenu();" class="block py-1.5 text-sm text-slate-600 hover:text-brand-primary">+ Cửa nhôm xingfa</a>
            <a href="#danh-muc-san-pham" onclick="closeMobileMenu()" class="block py-1.5 text-sm text-slate-600 hover:text-brand-primary">+ Cửa nhựa lõi thép</a>
            <a href="#danh-muc-san-pham" onclick="closeMobileMenu()" class="block py-1.5 text-sm text-slate-600 hover:text-brand-primary">+ Cửa kính tự động</a>
            <a href="#danh-muc-san-pham" onclick="closeMobileMenu()" class="block py-1.5 text-sm text-slate-600 hover:text-brand-primary">+ Cầu thang kính</a>
            <a href="#danh-muc-san-pham" onclick="closeMobileMenu()" class="block py-1.5 text-sm text-slate-600 hover:text-brand-primary">+ Kính ốp bếp</a>
            <a href="#danh-muc-san-pham" onclick="closeMobileMenu()" class="block py-1.5 text-sm text-slate-600 hover:text-brand-primary">+ Phòng tắm kính</a>
          </div>
        </div>

        <a href="#cong-trinh" onclick="closeMobileMenu()" class="block px-3 py-2.5 rounded-lg text-sm font-semibold text-slate-800 hover:bg-brand-light hover:text-brand-primary">Công trình</a>
        <a href="#bao-gia" onclick="closeMobileMenu()" class="block px-3 py-2.5 rounded-lg text-sm font-semibold text-slate-800 hover:bg-brand-light hover:text-brand-primary">Báo giá</a>
        <a href="#tin-tuc" onclick="closeMobileMenu()" class="block px-3 py-2.5 rounded-lg text-sm font-semibold text-slate-800 hover:bg-brand-light hover:text-brand-primary">Tin tức</a>
        <a href="#lien-he" onclick="closeMobileMenu()" class="block px-3 py-2.5 rounded-lg text-sm font-semibold text-slate-800 hover:bg-brand-light hover:text-brand-primary">Liên hệ</a>
      </div>
    </div>
  </header>

  <!-- ============================================================
       SECTION 1: 2 BANNER TỰ TRƯỢT CHUYÊN NGHIỆP (KÍCH THƯỚC BẰNG NHAU)
       Chữ & hình ảnh nằm trọn bên trong, cách xa viền banner ở mọi màn hình
       ============================================================ -->
  <section id="trang-chu" class="py-4 sm:py-5 bg-slate-50">
    <div class="kd-container">
      <div class="relative rounded-2xl overflow-hidden shadow-md bg-brand-dark">
        <div id="heroBannerStage" class="banner-stage">

          <!-- BANNER 1 -->
          <div class="banner-slide is-active bg-gradient-to-br from-[#07264d] via-[#0b3b75] to-[#124e96] text-white">
            <div class="px-6 py-8 sm:px-12 sm:py-10 md:px-16 md:py-12 lg:px-20 lg:py-14 h-full flex items-center">
              <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 lg:gap-10 items-center w-full">
                <!-- Nội dung chữ cách xa viền an toàn -->
                <div class="lg:col-span-7 space-y-3 sm:space-y-4 text-left">
                  <p class="text-xs sm:text-sm font-semibold uppercase tracking-widest text-amber-300">
                    CÔNG TY TNHH MTV KINGDOOR — ĐÀ NẴNG
                  </p>
                  <h1 class="text-xl sm:text-2xl md:text-3xl lg:text-4xl font-extrabold leading-snug text-white">
                    Cửa Nhôm Xingfa Nhập Khẩu Chính Hãng &amp; Nhôm Kính Cao Cấp
                  </h1>
                  <p class="text-xs sm:text-sm md:text-base text-slate-200 leading-relaxed max-w-2xl">
                    Chuyên sản xuất và thi công trọn gói cửa nhôm Xingfa hệ 55, hệ 93, kính cường lực, cửa tự động cho nhà phố, biệt thự, khách sạn và resort tại Đà Nẵng.
                  </p>
                  <div class="pt-2 flex flex-wrap gap-3">
                    <a href="#bao-gia" class="inline-flex items-center justify-center px-5 py-2.5 rounded-lg bg-brand-accent hover:opacity-95 text-white text-xs sm:text-sm font-bold shadow transition">
                      Nhận Báo Giá Miễn Phí
                    </a>
                    <a href="#san-pham-xingfa" class="inline-flex items-center justify-center px-5 py-2.5 rounded-lg bg-white/15 hover:bg-white/25 text-white border border-white/30 text-xs sm:text-sm font-semibold transition">
                      Xem Mẫu Cửa Xingfa
                    </a>
                  </div>
                </div>
                <!-- Ảnh nằm gọn bên trong khung banner -->
                <div class="lg:col-span-5">
                  <div class="rounded-xl overflow-hidden border-2 border-white/20 shadow-lg bg-white/10 aspect-[16/10]">
                    <img
                      src="https://drive.google.com/thumbnail?id=1lxzMKWX3e_HJn7UELFZDOURuxh-NYZg-&sz=w1000"
                      alt="Cửa đi quay mở 4 cánh nhôm Xingfa Kingdoor Đà Nẵng"
                      class="w-full h-full object-cover"
                      onerror="handleDriveImgError(this, '1lxzMKWX3e_HJn7UELFZDOURuxh-NYZg-', 'Cửa Nhôm Xingfa Kingdoor')"
                    >
                  </div>
                </div>
              </div>
            </div>
          </div>

          <!-- BANNER 2 -->
          <div class="banner-slide bg-gradient-to-br from-[#0f2947] via-[#133b68] to-[#0b2f59] text-white">
            <div class="px-6 py-8 sm:px-12 sm:py-10 md:px-16 md:py-12 lg:px-20 lg:py-14 h-full flex items-center">
              <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 lg:gap-10 items-center w-full">
                <!-- Nội dung chữ cách xa viền an toàn -->
                <div class="lg:col-span-7 space-y-3 sm:space-y-4 text-left">
                  <p class="text-xs sm:text-sm font-semibold uppercase tracking-widest text-amber-300">
                    GIẢI PHÁP KIẾN TRÚC HIỆN ĐẠI — KINGDOOR.COM
                  </p>
                  <h2 class="text-xl sm:text-2xl md:text-3xl lg:text-4xl font-extrabold leading-snug text-white">
                    Thi Công Trọn Gói Khách Sạn, Resort, Nhà Phố Tại Đà Nẵng
                  </h2>
                  <p class="text-xs sm:text-sm md:text-base text-slate-200 leading-relaxed max-w-2xl">
                    Đội ngũ kỹ thuật tay nghề cao, máy ép góc công nghệ chuẩn xác, phụ kiện Kinlong đồng bộ, bảo hành dài hạn. Khảo sát &amp; tư vấn tận nơi tại 502 Ngô Quyền, Sơn Trà.
                  </p>
                  <div class="pt-2 flex flex-wrap gap-3">
                    <a href="#cong-trinh" class="inline-flex items-center justify-center px-5 py-2.5 rounded-lg bg-brand-accent hover:opacity-95 text-white text-xs sm:text-sm font-bold shadow transition">
                      Xem Dự Án Thực Tế
                    </a>
                    <a href="#lien-he" class="inline-flex items-center justify-center px-5 py-2.5 rounded-lg bg-white/15 hover:bg-white/25 text-white border border-white/30 text-xs sm:text-sm font-semibold transition">
                      Liên Hệ Tư Vấn
                    </a>
                  </div>
                </div>
                <!-- Ảnh nằm gọn bên trong khung banner -->
                <div class="lg:col-span-5">
                  <div class="rounded-xl overflow-hidden border-2 border-white/20 shadow-lg bg-white/10 aspect-[16/10]">
                    <img
                      src="https://drive.google.com/thumbnail?id=1MmAfsyp3s3YCaEMymrkk8TZbD38jCsAQ&sz=w1000"
                      alt="Dự án thi công nhôm kính Resort Mỹ Sơn - Kingdoor Đà Nẵng"
                      class="w-full h-full object-cover"
                      onerror="handleDriveImgError(this, '1MmAfsyp3s3YCaEMymrkk8TZbD38jCsAQ', 'Dự Án Thi Công Kingdoor')"
                    >
                  </div>
                </div>
              </div>
            </div>
          </div>

        </div>

        <!-- Nút điều hướng đặt gọn gàng hai bên trên máy tính, cách xa nội dung -->
        <button
          type="button"
          onclick="changeBanner(-1)"
          class="hidden md:flex absolute left-3 top-1/2 -translate-y-1/2 z-10 w-9 h-9 items-center justify-center rounded-full bg-black/35 hover:bg-black/60 text-white transition"
          aria-label="Banner trước"
        >
          <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2.5" d="M15 19l-7-7 7-7"/></svg>
        </button>
        <button
          type="button"
          onclick="changeBanner(1)"
          class="hidden md:flex absolute right-3 top-1/2 -translate-y-1/2 z-10 w-9 h-9 items-center justify-center rounded-full bg-black/35 hover:bg-black/60 text-white transition"
          aria-label="Banner tiếp theo"
        >
          <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2.5" d="M9 5l7 7-7 7"/></svg>
        </button>

        <!-- Dấu chấm chuyển slide nằm gọn phía dưới, không che chữ -->
        <div class="flex items-center justify-center gap-2.5 pb-4 pt-1 bg-[#07264d]/95">
          <button type="button" onclick="goToBanner(0)" id="dot-0" class="w-7 h-2 rounded-full bg-brand-accent transition-all" aria-label="Xem banner 1"></button>
          <button type="button" onclick="goToBanner(1)" id="dot-1" class="w-2.5 h-2 rounded-full bg-white/40 hover:bg-white/70 transition-all" aria-label="Xem banner 2"></button>
        </div>
      </div>
    </div>
  </section>

  <!-- ============================================================
       SECTION 2: GIỚI THIỆU CÔNG TY (PHONG CÁCH FLATSOME ĐƠN GIẢN)
       ============================================================ -->
  <section id="gioi-thieu" class="py-10 sm:py-12 bg-white border-b border-slate-100">
    <div class="kd-container">
      <div class="grid grid-cols-1 lg:grid-cols-12 gap-8 items-center">
        <div class="lg:col-span-7 space-y-4">
          <h2 class="text-xl sm:text-2xl font-extrabold text-brand-primary uppercase flatsome-heading flatsome-heading-left">
            CÔNG TY TNHH MTV KINGDOOR — NHÔM KÍNH ĐÀ NẴNG
          </h2>
          <p class="text-sm sm:text-base text-slate-600 leading-relaxed">
            <strong>CÔNG TY TNHH MTV KINGDOOR</strong> (website: <strong>kingdoor.com</strong>) là đơn vị chuyên thiết kế, gia công sản xuất và thi công lắp đặt các hạng mục nhôm kính cao cấp hàng đầu tại Đà Nẵng và khu vực Miền Trung.
          </p>
          <p class="text-sm sm:text-base text-slate-600 leading-relaxed">
            Các dòng sản phẩm chủ lực của Kingdoor bao gồm: <strong>Cửa nhôm Xingfa nhập khẩu tem đỏ Quảng Đông</strong>, Cửa nhựa lõi thép uPVC, Cửa kính cường lực, Cửa kính tự động, Cầu thang kính, Kính ốp bếp cường lực và Phòng tắm kính. Với phương châm <em>“Uy tín – Chất lượng – Thẩm mỹ – Giá tốt”</em>, chúng tôi cam kết mang đến không gian sống bền đẹp, cách âm, cách nhiệt và an toàn tuyệt đối cho mọi công trình.
          </p>
          <div class="grid grid-cols-1 sm:grid-cols-2 gap-3 pt-1 text-sm text-slate-700">
            <div class="flex items-start gap-2.5 bg-slate-50 p-3 rounded-lg border border-slate-100">
              <span class="text-brand-accent font-bold">✓</span>
              <span>Khảo sát, đo đạc và lên báo giá tận nơi miễn phí tại Đà Nẵng</span>
            </div>
            <div class="flex items-start gap-2.5 bg-slate-50 p-3 rounded-lg border border-slate-100">
              <span class="text-brand-accent font-bold">✓</span>
              <span>Thanh nhôm Xingfa dày 1.4 – 2.0mm, phụ kiện Kinlong đồng bộ</span>
            </div>
            <div class="flex items-start gap-2.5 bg-slate-50 p-3 rounded-lg border border-slate-100">
              <span class="text-brand-accent font-bold">✓</span>
              <span>Sản xuất trực tiếp tại xưởng, giá cạnh tranh không qua trung gian</span>
            </div>
            <div class="flex items-start gap-2.5 bg-slate-50 p-3 rounded-lg border border-slate-100">
              <span class="text-brand-accent font-bold">✓</span>
              <span>Chính sách bảo hành chính hãng dài hạn, bảo trì nhanh chóng</span>
            </div>
          </div>
        </div>

        <!-- 4 chỉ số nổi bật giống mẫu ngochanwindow.com -->
        <div class="lg:col-span-5 grid grid-cols-2 gap-4">
          <div class="rounded-xl bg-brand-light border border-slate-200/70 p-5 text-center">
            <div class="text-2xl sm:text-3xl font-extrabold text-brand-primary">150+</div>
            <div class="text-xs sm:text-sm font-semibold text-slate-600 mt-1">Dự án đã hoàn thành</div>
          </div>
          <div class="rounded-xl bg-brand-light border border-slate-200/70 p-5 text-center">
            <div class="text-2xl sm:text-3xl font-extrabold text-brand-primary">50+</div>
            <div class="text-xs sm:text-sm font-semibold text-slate-600 mt-1">Nhân viên kinh nghiệm</div>
          </div>
          <div class="rounded-xl bg-brand-light border border-slate-200/70 p-5 text-center">
            <div class="text-2xl sm:text-3xl font-extrabold text-brand-primary">100+</div>
            <div class="text-xs sm:text-sm font-semibold text-slate-600 mt-1">Mẫu cửa chất lượng</div>
          </div>
          <div class="rounded-xl bg-brand-light border border-slate-200/70 p-5 text-center">
            <div class="text-2xl sm:text-3xl font-extrabold text-brand-primary">100%</div>
            <div class="text-xs sm:text-sm font-semibold text-slate-600 mt-1">Khách hàng hài lòng</div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- ============================================================
       SECTION 3: BÁO GIÁ & SẢN PHẨM CỬA NHÔM XINGFA ĐÀ NẴNG
       - Chia 2 cột trên điện thoại, 3 cột trên máy tính
       - Giá & Giảm giá % ở góc trên bên trái sản phẩm
       - Tên sản phẩm hiển thị đầy đủ, không tràn hay thiếu chữ
       ============================================================ -->
  <section id="san-pham-xingfa" class="py-10 sm:py-12 bg-slate-50">
    <div class="kd-container">
      <div class="text-center mb-6 sm:mb-8">
        <h2 class="text-xl sm:text-2xl font-extrabold text-brand-primary uppercase flatsome-heading">
          BÁO GIÁ CỬA NHÔM XINGFA ĐÀ NẴNG
        </h2>
        <p class="text-xs sm:text-sm text-slate-500 mt-3 max-w-2xl mx-auto">
          Sản phẩm nhôm Xingfa nhập khẩu chính hãng, kính an toàn cường lực và phụ kiện đồng bộ. Giá ưu đãi trực tiếp tại xưởng Kingdoor.
        </p>

        <!-- Bộ lọc nhanh theo số cánh / kiểu mở -->
        <div class="flex flex-wrap justify-center gap-2 mt-5" id="productFilterTabs">
          <button type="button" data-filter="all" onclick="filterProducts('all')" class="filter-tab px-3.5 py-1.5 rounded-lg text-xs sm:text-sm font-semibold bg-brand-primary text-white transition">Tất cả</button>
          <button type="button" data-filter="1-canh" onclick="filterProducts('1-canh')" class="filter-tab px-3.5 py-1.5 rounded-lg text-xs sm:text-sm font-semibold bg-white text-slate-700 border border-slate-200 hover:border-brand-primary transition">1 cánh</button>
          <button type="button" data-filter="2-canh" onclick="filterProducts('2-canh')" class="filter-tab px-3.5 py-1.5 rounded-lg text-xs sm:text-sm font-semibold bg-white text-slate-700 border border-slate-200 hover:border-brand-primary transition">2 cánh</button>
          <button type="button" data-filter="3-canh" onclick="filterProducts('3-canh')" class="filter-tab px-3.5 py-1.5 rounded-lg text-xs sm:text-sm font-semibold bg-white text-slate-700 border border-slate-200 hover:border-brand-primary transition">3 cánh</button>
          <button type="button" data-filter="4-canh" onclick="filterProducts('4-canh')" class="filter-tab px-3.5 py-1.5 rounded-lg text-xs sm:text-sm font-semibold bg-white text-slate-700 border border-slate-200 hover:border-brand-primary transition">4 cánh</button>
          <button type="button" data-filter="5-canh" onclick="filterProducts('5-canh')" class="filter-tab px-3.5 py-1.5 rounded-lg text-xs sm:text-sm font-semibold bg-white text-slate-700 border border-slate-200 hover:border-brand-primary transition">Xếp trượt / 5 cánh</button>
        </div>
      </div>

      <!-- Lưới sản phẩm: 2 cột trên điện thoại, 3 cột trên máy tính -->
      <div id="productGrid" class="grid grid-cols-2 md:grid-cols-3 gap-3 sm:gap-5">
        <!-- Dữ liệu sản phẩm được render tự động từ JS bên dưới -->
      </div>
    </div>
  </section>

  <!-- ============================================================
       SECTION 4: DANH MỤC SẢN PHẨM NỔI BẬT (GIỐNG WEB MẪU)
       Chữ danh mục nhỏ gọn, sắc nét trên cả điện thoại và máy tính
       ============================================================ -->
  <section id="danh-muc-san-pham" class="py-10 sm:py-12 bg-white">
    <div class="kd-container">
      <div class="text-center mb-7">
        <h2 class="text-xl sm:text-2xl font-extrabold text-brand-primary uppercase flatsome-heading">
          SẢN PHẨM NỔI BẬT
        </h2>
        <p class="text-xs sm:text-sm text-slate-500 mt-3">
          Đa dạng danh mục cửa và nội thất kính cao cấp do Kingdoor trực tiếp thiết kế &amp; lắp đặt
        </p>
      </div>

      <div class="grid grid-cols-2 md:grid-cols-3 gap-3 sm:gap-5">
        <!-- Danh mục 1: Cửa nhôm xingfa -->
        <a href="#san-pham-xingfa" onclick="filterProducts('all')" class="group block rounded-xl overflow-hidden border border-slate-200 bg-white shadow-sm hover:shadow-md transition">
          <div class="aspect-[4/3] overflow-hidden bg-slate-100">
            <img
              src="https://drive.google.com/thumbnail?id=1zRlHJBAneXS7EQ1jdT__hVRCTf2mzOiX&sz=w800"
              alt="Cửa nhôm Xingfa Kingdoor"
              class="w-full h-full object-cover group-hover:scale-105 transition duration-300"
              onerror="handleDriveImgError(this, '1zRlHJBAneXS7EQ1jdT__hVRCTf2mzOiX', 'Cửa Nhôm Xingfa')"
            >
          </div>
          <div class="p-3 text-center bg-white">
            <h3 class="text-xs sm:text-sm font-bold text-brand-primary uppercase tracking-wide group-hover:text-brand-accent transition">
              Cửa Nhôm Xingfa
            </h3>
          </div>
        </a>

        <!-- Danh mục 2: Cửa nhựa lõi thép -->
        <a href="#bao-gia" onclick="preselectQuote('Cửa nhựa lõi thép')" class="group block rounded-xl overflow-hidden border border-slate-200 bg-white shadow-sm hover:shadow-md transition">
          <div class="aspect-[4/3] overflow-hidden bg-slate-100">
            <img
              src="https://drive.google.com/thumbnail?id=1jiHBW-2MoWUHjQUicSe-rO6NlmfNuZNA&sz=w800"
              alt="Cửa nhựa lõi thép Kingdoor"
              class="w-full h-full object-cover group-hover:scale-105 transition duration-300"
              onerror="handleDriveImgError(this, '1jiHBW-2MoWUHjQUicSe-rO6NlmfNuZNA', 'Cửa Nhựa Lõi Thép')"
            >
          </div>
          <div class="p-3 text-center bg-white">
            <h3 class="text-xs sm:text-sm font-bold text-brand-primary uppercase tracking-wide group-hover:text-brand-accent transition">
              Cửa Nhựa Lõi Thép
            </h3>
          </div>
        </a>

        <!-- Danh mục 3: Cửa kính tự động -->
        <a href="#bao-gia" onclick="preselectQuote('Cửa kính tự động')" class="group block rounded-xl overflow-hidden border border-slate-200 bg-white shadow-sm hover:shadow-md transition">
          <div class="aspect-[4/3] overflow-hidden bg-slate-100">
            <img
              src="https://drive.google.com/thumbnail?id=1PIFP1UCQs_FIaKCgGwcJWt-5wTnST9iJ&sz=w800"
              alt="Cửa tự động Kingdoor"
              class="w-full h-full object-cover group-hover:scale-105 transition duration-300"
              onerror="handleDriveImgError(this, '1PIFP1UCQs_FIaKCgGwcJWt-5wTnST9iJ', 'Cửa Tự Động')"
            >
          </div>
          <div class="p-3 text-center bg-white">
            <h3 class="text-xs sm:text-sm font-bold text-brand-primary uppercase tracking-wide group-hover:text-brand-accent transition">
              Cửa Tự Động
            </h3>
          </div>
        </a>

        <!-- Danh mục 4: Cầu thang kính -->
        <a href="#bao-gia" onclick="preselectQuote('Cầu thang kính')" class="group block rounded-xl overflow-hidden border border-slate-200 bg-white shadow-sm hover:shadow-md transition">
          <div class="aspect-[4/3] overflow-hidden bg-slate-100">
            <img
              src="https://drive.google.com/thumbnail?id=1FnuITlKMjk-xTxkIV96ABv43S1PG--Ul&sz=w800"
              alt="Cầu thang kính cường lực Kingdoor"
              class="w-full h-full object-cover group-hover:scale-105 transition duration-300"
              onerror="handleDriveImgError(this, '1FnuITlKMjk-xTxkIV96ABv43S1PG--Ul', 'Cầu Thang Kính')"
            >
          </div>
          <div class="p-3 text-center bg-white">
            <h3 class="text-xs sm:text-sm font-bold text-brand-primary uppercase tracking-wide group-hover:text-brand-accent transition">
              Cầu Thang Kính
            </h3>
          </div>
        </a>

        <!-- Danh mục 5: Kính ốp bếp -->
        <a href="#bao-gia" onclick="preselectQuote('Kính ốp bếp')" class="group block rounded-xl overflow-hidden border border-slate-200 bg-white shadow-sm hover:shadow-md transition">
          <div class="aspect-[4/3] overflow-hidden bg-slate-100">
            <img
              src="https://drive.google.com/thumbnail?id=1ilanOshTrs9llnMXWl5iZ8DtgptJ0hCb&sz=w800"
              alt="Kính ốp bếp cường lực Kingdoor"
              class="w-full h-full object-cover group-hover:scale-105 transition duration-300"
              onerror="handleDriveImgError(this, '1ilanOshTrs9llnMXWl5iZ8DtgptJ0hCb', 'Kính Ốp Bếp')"
            >
          </div>
          <div class="p-3 text-center bg-white">
            <h3 class="text-xs sm:text-sm font-bold text-brand-primary uppercase tracking-wide group-hover:text-brand-accent transition">
              Kính Ốp Bếp
            </h3>
          </div>
        </a>

        <!-- Danh mục 6: Phòng tắm kính -->
        <a href="#bao-gia" onclick="preselectQuote('Phòng tắm kính')" class="group block rounded-xl overflow-hidden border border-slate-200 bg-white shadow-sm hover:shadow-md transition">
          <div class="aspect-[4/3] overflow-hidden bg-slate-100">
            <img
              src="https://drive.google.com/thumbnail?id=1MhCILHQ5goD1cAPTt1hZsY_ajeOMs-qH&sz=w800"
              alt="Phòng tắm kính cường lực Kingdoor"
              class="w-full h-full object-cover group-hover:scale-105 transition duration-300"
              onerror="handleDriveImgError(this, '1MhCILHQ5goD1cAPTt1hZsY_ajeOMs-qH', 'Phòng Tắm Kính')"
            >
          </div>
          <div class="p-3 text-center bg-white">
            <h3 class="text-xs sm:text-sm font-bold text-brand-primary uppercase tracking-wide group-hover:text-brand-accent transition">
              Phòng Tắm Kính
            </h3>
          </div>
        </a>
      </div>
    </div>
  </section>

  <!-- ============================================================
       SECTION 5: CÁC DỰ ÁN NỔI BẬT TẠI ĐÀ NẴNG
       ============================================================ -->
  <section id="cong-trinh" class="py-10 sm:py-12 bg-slate-50 border-t border-slate-100">
    <div class="kd-container">
      <div class="text-center mb-7">
        <h2 class="text-xl sm:text-2xl font-extrabold text-brand-primary uppercase flatsome-heading">
          CÁC DỰ ÁN NỔI BẬT TẠI ĐÀ NẴNG
        </h2>
        <p class="text-xs sm:text-sm text-slate-500 mt-3">
          Những công trình khách sạn, khu nghỉ dưỡng tiêu biểu sử dụng hệ cửa nhôm kính chất lượng cao
        </p>
      </div>

      <div class="grid grid-cols-2 md:grid-cols-3 gap-3 sm:gap-5">
        <!-- Dự án 1 -->
        <article class="rounded-xl overflow-hidden bg-white border border-slate-200 shadow-sm hover:shadow-md transition flex flex-col">
          <div class="aspect-[16/11] overflow-hidden bg-slate-100">
            <img
              src="https://drive.google.com/thumbnail?id=1MmAfsyp3s3YCaEMymrkk8TZbD38jCsAQ&sz=w800"
              alt="DỰ ÁN RESORT MỸ SƠN 4 SAO MY SON HERITAGE RESORT & SPA"
              class="w-full h-full object-cover hover:scale-105 transition duration-300"
              onerror="handleDriveImgError(this, '1MmAfsyp3s3YCaEMymrkk8TZbD38jCsAQ', 'Resort Mỹ Sơn 4 Sao')"
            >
          </div>
          <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
            <h3 class="text-xs sm:text-sm font-bold text-slate-800 leading-snug">
              DỰ ÁN RESORT MỸ SƠN 4 SAO “MY SON HERITAGE RESORT &amp; SPA”
            </h3>
            <p class="text-[11px] sm:text-xs text-slate-500 mt-2">Hạng mục: Hệ cửa nhôm Xingfa &amp; vách kính cường lực</p>
          </div>
        </article>

        <!-- Dự án 2 -->
        <article class="rounded-xl overflow-hidden bg-white border border-slate-200 shadow-sm hover:shadow-md transition flex flex-col">
          <div class="aspect-[16/11] overflow-hidden bg-slate-100">
            <img
              src="https://drive.google.com/thumbnail?id=1YeuDLiSXUK_Epupq9QiGzM90_EGW3Kfy&sz=w800"
              alt="THI CÔNG DỰ ÁN KHÁCH SẠN GODEN LINE"
              class="w-full h-full object-cover hover:scale-105 transition duration-300"
              onerror="handleDriveImgError(this, '1YeuDLiSXUK_Epupq9QiGzM90_EGW3Kfy', 'Khách Sạn Goden Line')"
            >
          </div>
          <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
            <h3 class="text-xs sm:text-sm font-bold text-slate-800 leading-snug">
              THI CÔNG DỰ ÁN KHÁCH SẠN GODEN LINE
            </h3>
            <p class="text-[11px] sm:text-xs text-slate-500 mt-2">Hạng mục: Cửa đi ban công nhôm Xingfa &amp; phòng tắm kính</p>
          </div>
        </article>

        <!-- Dự án 3 -->
        <article class="rounded-xl overflow-hidden bg-white border border-slate-200 shadow-sm hover:shadow-md transition flex flex-col">
          <div class="aspect-[16/11] overflow-hidden bg-slate-100">
            <img
              src="https://drive.google.com/thumbnail?id=1wH-JJ2rOYRmDGsNapl3bIBjfiG3Qm6zZ&sz=w800"
              alt="DỰ ÁN KHÁCH SẠN RUBY LIGHT"
              class="w-full h-full object-cover hover:scale-105 transition duration-300"
              onerror="handleDriveImgError(this, '1wH-JJ2rOYRmDGsNapl3bIBjfiG3Qm6zZ', 'Khách Sạn Ruby Light')"
            >
          </div>
          <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
            <h3 class="text-xs sm:text-sm font-bold text-slate-800 leading-snug">
              DỰ ÁN KHÁCH SẠN RUBY LIGHT
            </h3>
            <p class="text-[11px] sm:text-xs text-slate-500 mt-2">Hạng mục: Vách mặt dựng kính &amp; cửa kính tự động sảnh chính</p>
          </div>
        </article>

        <!-- Dự án 4 -->
        <article class="rounded-xl overflow-hidden bg-white border border-slate-200 shadow-sm hover:shadow-md transition flex flex-col">
          <div class="aspect-[16/11] overflow-hidden bg-slate-100">
            <img
              src="https://drive.google.com/thumbnail?id=1za_IJpAm850uulT6IuhBsk1THb3LuPuc&sz=w800"
              alt="THI CÔNG DỰ ÁN RAON ĐÀ NẴNG BEACH HOTEL"
              class="w-full h-full object-cover hover:scale-105 transition duration-300"
              onerror="handleDriveImgError(this, '1za_IJpAm850uulT6IuhBsk1THb3LuPuc', 'Raon Đà Nẵng Beach Hotel')"
            >
          </div>
          <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
            <h3 class="text-xs sm:text-sm font-bold text-slate-800 leading-snug">
              THI CÔNG DỰ ÁN RAON ĐÀ NẴNG BEACH HOTEL
            </h3>
            <p class="text-[11px] sm:text-xs text-slate-500 mt-2">Hạng mục: Hệ cửa nhôm kính chống bão biển &amp; lan can kính</p>
          </div>
        </article>

        <!-- Dự án 5 -->
        <article class="rounded-xl overflow-hidden bg-white border border-slate-200 shadow-sm hover:shadow-md transition flex flex-col">
          <div class="aspect-[16/11] overflow-hidden bg-slate-100">
            <img
              src="https://drive.google.com/thumbnail?id=1WRgx-EUIrn8IKFZdpmdv6Z2Xyb7L8_64&sz=w800"
              alt="THI CÔNG DỰ ÁN KHÁCH SẠN JOLIA"
              class="w-full h-full object-cover hover:scale-105 transition duration-300"
              onerror="handleDriveImgError(this, '1WRgx-EUIrn8IKFZdpmdv6Z2Xyb7L8_64', 'Khách Sạn Jolia')"
            >
          </div>
          <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
            <h3 class="text-xs sm:text-sm font-bold text-slate-800 leading-snug">
              THI CÔNG DỰ ÁN KHÁCH SẠN JOLIA
            </h3>
            <p class="text-[11px] sm:text-xs text-slate-500 mt-2">Hạng mục: Cửa sổ mở hất Xingfa &amp; cabin tắm kính cường lực</p>
          </div>
        </article>

        <!-- Dự án 6 -->
        <article class="rounded-xl overflow-hidden bg-white border border-slate-200 shadow-sm hover:shadow-md transition flex flex-col">
          <div class="aspect-[16/11] overflow-hidden bg-slate-100">
            <img
              src="https://drive.google.com/thumbnail?id=1-C5bdt4K-PpLX_KqSN6QAR5ULo1WnNzt&sz=w800"
              alt="THI CÔNG DỰ ÁN KHÁCH SẠN SOHO"
              class="w-full h-full object-cover hover:scale-105 transition duration-300"
              onerror="handleDriveImgError(this, '1-C5bdt4K-PpLX_KqSN6QAR5ULo1WnNzt', 'Khách Sạn Soho')"
            >
          </div>
          <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
            <h3 class="text-xs sm:text-sm font-bold text-slate-800 leading-snug">
              THI CÔNG DỰ ÁN KHÁCH SẠN SOHO
            </h3>
            <p class="text-[11px] sm:text-xs text-slate-500 mt-2">Hạng mục: Cửa nhôm Xingfa nhập khẩu &amp; vách kính cách âm</p>
          </div>
        </article>
      </div>
    </div>
  </section>

  <!-- ============================================================
       SECTION 6: FORM YÊU CẦU TƯ VẤN & BÁO GIÁ TRANG CHỦ
       ============================================================ -->
  <section id="bao-gia" class="py-10 sm:py-12 bg-brand-primary text-white">
    <div class="kd-container">
      <div class="grid grid-cols-1 lg:grid-cols-12 gap-8 items-center">
        <!-- Cột trái: Bảng giá tham khảo nhanh & cam kết -->
        <div class="lg:col-span-6 space-y-4">
          <h2 class="text-xl sm:text-2xl font-extrabold uppercase text-white flatsome-heading flatsome-heading-left">
            ĐĂNG KÝ NHẬN BÁO GIÁ MIỄN PHÍ
          </h2>
          <p class="text-xs sm:text-sm text-slate-200 leading-relaxed">
            Để lại thông tin công trình, đội ngũ kỹ sư <strong>CÔNG TY TNHH MTV KINGDOOR</strong> sẽ liên hệ tư vấn giải pháp tối ưu và gửi bảng báo giá chi tiết trong vòng 15 phút.
          </p>

          <div class="bg-white/10 border border-white/20 rounded-xl p-4 space-y-2.5 text-xs sm:text-sm">
            <div class="flex justify-between gap-2 pb-2 border-b border-white/15">
              <span class="text-slate-100">Cửa sổ mở quay / mở hất Xingfa hệ 55</span>
              <span class="font-bold text-amber-300 whitespace-nowrap">1.850.000 ₫/m²</span>
            </div>
            <div class="flex justify-between gap-2 pb-2 border-b border-white/15">
              <span class="text-slate-100">Cửa đi mở quay 1 - 4 cánh Xingfa hệ 55</span>
              <span class="font-bold text-amber-300 whitespace-nowrap">1.950.000 - 2.100.000 ₫/m²</span>
            </div>
            <div class="flex justify-between gap-2 pb-2 border-b border-white/15">
              <span class="text-slate-100">Cửa đi mở xếp trượt gấp nhôm Xingfa</span>
              <span class="font-bold text-amber-300 whitespace-nowrap">2.200.000 ₫/m²</span>
            </div>
            <div class="flex justify-between gap-2">
              <span class="text-slate-100">Kính cường lực / Phòng tắm / Cầu thang kính</span>
              <span class="font-bold text-amber-300 whitespace-nowrap">Báo giá theo bản vẽ</span>
            </div>
          </div>

          <div class="text-xs sm:text-sm text-slate-200 space-y-1">
            <p><strong>Hotline tư vấn 24/7:</strong> <a href="tel:0905445498" class="text-amber-300 font-bold underline">0905.445.498</a> – <a href="tel:0905398268" class="text-amber-300 font-bold underline">0905.39.82.68</a></p>
            <p><strong>Showroom &amp; Xưởng:</strong> 502 Ngô Quyền - Sơn Trà - Đà Nẵng</p>
          </div>
        </div>

        <!-- Cột phải: Form yêu cầu báo giá trực tiếp -->
        <div class="lg:col-span-6">
          <form id="quoteForm" class="bg-white text-slate-800 rounded-2xl p-5 sm:p-7 shadow-xl space-y-4">
            <h3 class="text-base sm:text-lg font-extrabold text-brand-primary uppercase">
              Gửi Yêu Cầu Báo Giá Nhanh
            </h3>

            <div class="grid grid-cols-1 sm:grid-cols-2 gap-3.5">
              <div>
                <label for="qName" class="block text-xs font-semibold text-slate-700 mb-1">Họ và tên *</label>
                <input id="qName" type="text" required placeholder="Nhập họ tên của bạn" class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-sm focus:outline-none focus:border-brand-primary">
              </div>
              <div>
                <label for="qPhone" class="block text-xs font-semibold text-slate-700 mb-1">Số điện thoại / Zalo *</label>
                <input id="qPhone" type="tel" required placeholder="Ví dụ: 0905..." class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-sm focus:outline-none focus:border-brand-primary">
              </div>
            </div>

            <div class="grid grid-cols-1 sm:grid-cols-2 gap-3.5">
              <div>
                <label for="qProduct" class="block text-xs font-semibold text-slate-700 mb-1">Hạng mục quan tâm</label>
                <select id="qProduct" class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-sm bg-white focus:outline-none focus:border-brand-primary">
                  <option value="Cửa nhôm Xingfa nhập khẩu">Cửa nhôm Xingfa nhập khẩu</option>
                  <option value="Cửa kính cường lực">Cửa kính cường lực</option>
                  <option value="Cửa nhựa lõi thép">Cửa nhựa lõi thép</option>
                  <option value="Cửa kính tự động">Cửa kính tự động</option>
                  <option value="Cầu thang kính">Cầu thang kính</option>
                  <option value="Kính ốp bếp">Kính ốp bếp</option>
                  <option value="Phòng tắm kính">Phòng tắm kính</option>
                  <option value="Thi công trọn gói công trình">Thi công trọn gói công trình</option>
                </select>
              </div>
              <div>
                <label for="qArea" class="block text-xs font-semibold text-slate-700 mb-1">Khối lượng dự kiến (m² / số bộ)</label>
                <input id="qArea" type="text" placeholder="Ví dụ: 35m² hoặc 6 bộ cửa" class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-sm focus:outline-none focus:border-brand-primary">
              </div>
            </div>

            <div>
              <label for="qNote" class="block text-xs font-semibold text-slate-700 mb-1">Nội dung yêu cầu / Địa chỉ công trình</label>
              <textarea id="qNote" rows="3" placeholder="Nhập địa chỉ công trình tại Đà Nẵng, kích thước hoặc yêu cầu cụ thể..." class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-sm focus:outline-none focus:border-brand-primary"></textarea>
            </div>

            <button type="submit" class="w-full py-3 px-5 rounded-lg bg-brand-accent hover:opacity-95 text-white font-bold text-sm uppercase tracking-wide shadow transition">
              Gửi Yêu Cầu Báo Giá Ngay
            </button>

            <div id="quoteFeedback" class="hidden rounded-lg p-3 text-xs sm:text-sm font-medium bg-emerald-50 text-emerald-800 border border-emerald-200"></div>
          </form>
        </div>
      </div>
    </div>
  </section>

  <!-- ============================================================
       SECTION 7: DANH MỤC CÁC BÀI VIẾT / TIN TỨC TRANG CHỦ
       ============================================================ -->
  <section id="tin-tuc" class="py-10 sm:py-12 bg-white border-b border-slate-100">
    <div class="kd-container">
      <div class="text-center mb-7">
        <h2 class="text-xl sm:text-2xl font-extrabold text-brand-primary uppercase flatsome-heading">
          TIN TỨC &amp; KINH NGHIỆM NHÔM KÍNH
        </h2>
        <p class="text-xs sm:text-sm text-slate-500 mt-3">
          Cập nhật kiến thức chọn cửa nhôm Xingfa, kinh nghiệm thi công và bảng giá mới nhất tại Đà Nẵng
        </p>

        <!-- Danh mục lọc bài viết -->
        <div class="flex flex-wrap justify-center gap-2 mt-4" id="newsCategoryTabs">
          <button type="button" data-news-cat="all" onclick="filterNews('all')" class="news-tab px-3.5 py-1.5 rounded-lg text-xs font-semibold bg-brand-primary text-white transition">Tất cả bài viết</button>
          <button type="button" data-news-cat="xingfa" onclick="filterNews('xingfa')" class="news-tab px-3.5 py-1.5 rounded-lg text-xs font-semibold bg-slate-100 text-slate-700 hover:bg-slate-200 transition">Kiến thức Xingfa</button>
          <button type="button" data-news-cat="kinh-nghiem" onclick="filterNews('kinh-nghiem')" class="news-tab px-3.5 py-1.5 rounded-lg text-xs font-semibold bg-slate-100 text-slate-700 hover:bg-slate-200 transition">Kinh nghiệm chọn cửa</button>
          <button type="button" data-news-cat="bao-gia" onclick="filterNews('bao-gia')" class="news-tab px-3.5 py-1.5 rounded-lg text-xs font-semibold bg-slate-100 text-slate-700 hover:bg-slate-200 transition">Báo giá &amp; Ưu đãi</button>
        </div>
      </div>

      <!-- Lưới bài viết: 2 cột trên mobile, 4 cột trên desktop -->
      <div id="newsGrid" class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">
        <!-- Dữ liệu bài viết được render từ JS bên dưới -->
      </div>
    </div>
  </section>

  <!-- ============================================================
       SECTION 8: ĐỐI TÁC CỦA CHÚNG TÔI (6 LOGO TỪ GOOGLE DRIVE)
       ============================================================ -->
  <section class="py-10 bg-slate-50 border-b border-slate-100">
    <div class="kd-container">
      <div class="text-center mb-6">
        <h2 class="text-lg sm:text-xl font-extrabold text-brand-primary uppercase flatsome-heading">
          ĐỐI TÁC CỦA CHÚNG TÔI
        </h2>
      </div>

      <div class="grid grid-cols-3 md:grid-cols-6 gap-3 sm:gap-4 items-center">
        <div class="bg-white rounded-xl border border-slate-200 p-3 flex items-center justify-center h-20 shadow-sm">
          <img src="https://drive.google.com/thumbnail?id=13il4TeS8ZnrK0CD4VDPMdNX3EKxY8AFk&sz=w400" alt="Đối tác Kingdoor 1" class="max-h-14 w-auto object-contain" onerror="handleDriveImgError(this, '13il4TeS8ZnrK0CD4VDPMdNX3EKxY8AFk', 'Đối tác 1')">
        </div>
        <div class="bg-white rounded-xl border border-slate-200 p-3 flex items-center justify-center h-20 shadow-sm">
          <img src="https://drive.google.com/thumbnail?id=1QRcPtjWfg5PEQXw6UMg6ZylQhg8BpzUq&sz=w400" alt="Đối tác Kingdoor 2" class="max-h-14 w-auto object-contain" onerror="handleDriveImgError(this, '1QRcPtjWfg5PEQXw6UMg6ZylQhg8BpzUq', 'Đối tác 2')">
        </div>
        <div class="bg-white rounded-xl border border-slate-200 p-3 flex items-center justify-center h-20 shadow-sm">
          <img src="https://drive.google.com/thumbnail?id=1-Ka-zScPzx653Tg2oWE9-qmFtTdn3Svn&sz=w400" alt="Đối tác Kingdoor 3" class="max-h-14 w-auto object-contain" onerror="handleDriveImgError(this, '1-Ka-zScPzx653Tg2oWE9-qmFtTdn3Svn', 'Đối tác 3')">
        </div>
        <div class="bg-white rounded-xl border border-slate-200 p-3 flex items-center justify-center h-20 shadow-sm">
          <img src="https://drive.google.com/thumbnail?id=1Oy52Wdfy5x6DKF1lyfYxpZTD5fvGH5vT&sz=w400" alt="Đối tác Kingdoor 4" class="max-h-14 w-auto object-contain" onerror="handleDriveImgError(this, '1Oy52Wdfy5x6DKF1lyfYxpZTD5fvGH5vT', 'Đối tác 4')">
        </div>
        <div class="bg-white rounded-xl border border-slate-200 p-3 flex items-center justify-center h-20 shadow-sm">
          <img src="https://drive.google.com/thumbnail?id=1SDcarhnX0yypmqdbawICjYBRtFnKngn-&sz=w400" alt="Đối tác Kingdoor 5" class="max-h-14 w-auto object-contain" onerror="handleDriveImgError(this, '1SDcarhnX0yypmqdbawICjYBRtFnKngn-', 'Đối tác 5')">
        </div>
        <div class="bg-white rounded-xl border border-slate-200 p-3 flex items-center justify-center h-20 shadow-sm">
          <img src="https://drive.google.com/thumbnail?id=1Ua4C1iiZqrjkWx-3h2quvqM0w_Xj33fg&sz=w400" alt="Đối tác Kingdoor 6" class="max-h-14 w-auto object-contain" onerror="handleDriveImgError(this, '1Ua4C1iiZqrjkWx-3h2quvqM0w_Xj33fg', 'Đối tác 6')">
        </div>
      </div>
    </div>
  </section>

  <!-- ============================================================
       SECTION 9: BẢN ĐỒ GOOGLE MAP & FANPAGE FACEBOOK NGAY TRANG CHỦ
       ============================================================ -->
  <section id="lien-he" class="py-10 sm:py-12 bg-white">
    <div class="kd-container">
      <div class="text-center mb-7">
        <h2 class="text-xl sm:text-2xl font-extrabold text-brand-primary uppercase flatsome-heading">
          BẢN ĐỒ CHỈ ĐƯỜNG &amp; FANPAGE FACEBOOK
        </h2>
        <p class="text-xs sm:text-sm text-slate-500 mt-3">
          Ghé trực tiếp showroom CÔNG TY TNHH MTV KINGDOOR tại 502 Ngô Quyền - Sơn Trà - Đà Nẵng hoặc kết nối qua Fanpage chính thức
        </p>
      </div>

      <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-stretch">
        <!-- Cột trái: Google Map trực quan ra ngoài trang chủ -->
        <div class="lg:col-span-7 flex flex-col rounded-2xl overflow-hidden border border-slate-200 shadow-sm bg-white">
          <div class="px-4 py-3 bg-slate-50 border-b border-slate-200 flex flex-wrap items-center justify-between gap-2">
            <div>
              <h3 class="text-sm font-bold text-brand-primary uppercase">Bản Đồ Google Map — Kingdoor Đà Nẵng</h3>
              <p class="text-xs text-slate-600">502 Ngô Quyền, Quận Sơn Trà, TP. Đà Nẵng</p>
            </div>
            <a
              href="https://www.google.com/maps/search/?api=1&query=502+Ng%C3%B4+Quy%E1%BB%81n,+S%C6%A1n+Tr%C3%A0,+%C4%90%C3%A0+N%E1%BA%B5ng"
              target="_blank"
              rel="noopener noreferrer"
              class="inline-flex items-center gap-1.5 px-3 py-1.5 rounded-lg bg-brand-primary text-white text-xs font-semibold hover:opacity-90 transition"
            >
              <span>Chỉ đường</span>
              <svg class="w-3.5 h-3.5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M10 6H6a2 2 0 00-2 2v10a2 2 0 002 2h10a2 2 0 002-2v-4M14 4h6m0 0v6m0-6L10 14"/></svg>
            </a>
          </div>
          <div class="w-full h-[320px] sm:h-[360px] flex-1 bg-slate-100">
            <iframe
              title="Bản đồ Google Map CÔNG TY TNHH MTV KINGDOOR - 502 Ngô Quyền, Sơn Trà, Đà Nẵng"
              src="https://maps.google.com/maps?q=502%20Ng%C3%B4%20Quy%E1%BB%81n,%20S%C6%A1n%20Tr%C3%A0,%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed"
              class="w-full h-full border-0"
              loading="lazy"
              referrerpolicy="no-referrer-when-downgrade"
              allowfullscreen
            ></iframe>
          </div>
        </div>

        <!-- Cột phải: Fanpage Facebook Kingdoor đưa ra ngoài trang chủ -->
        <div class="lg:col-span-5 flex flex-col rounded-2xl overflow-hidden border border-slate-200 shadow-sm bg-white">
          <div class="px-4 py-3 bg-[#1877f2] text-white flex items-center justify-between gap-2">
            <div class="flex items-center gap-2">
              <svg class="w-5 h-5 shrink-0 fill-current" viewBox="0 0 24 24"><path d="M22.675 0h-21.35C.597 0 0 .597 0 1.326v21.348C0 23.403.597 24 1.326 24h11.495v-9.294H9.692v-3.622h3.129V8.413c0-3.1 1.893-4.788 4.659-4.788 1.325 0 2.463.099 2.795.143v3.24l-1.918.001c-1.504 0-1.795.715-1.795 1.763v2.313h3.587l-.467 3.622h-3.12V24h6.116C23.403 24 24 23.403 24 22.674V1.326C24 .597 23.403 0 22.675 0z"/></svg>
              <h3 class="text-sm font-bold uppercase">Fanpage Facebook Chính Thức</h3>
            </div>
            <a
              href="https://www.facebook.com/profile.php?id=100078389796234"
              target="_blank"
              rel="noopener noreferrer"
              class="px-3 py-1 rounded bg-white text-[#1877f2] text-xs font-bold hover:bg-slate-100 transition"
            >
              Xem Fanpage
            </a>
          </div>

          <div class="p-4 flex-1 flex flex-col justify-between bg-slate-50 gap-4">
            <!-- Khung nhúng Fanpage Facebook -->
            <div class="w-full overflow-hidden rounded-xl border border-slate-200 bg-white">
              <iframe
                title="Fanpage Facebook CÔNG TY TNHH MTV KINGDOOR"
                src="https://www.facebook.com/plugins/page.php?href=https%3A%2F%2Fwww.facebook.com%2Fprofile.php%3Fid%3D100078389796234&tabs=timeline&width=500&height=230&small_header=false&adapt_container_width=true&hide_cover=false&show_facepile=true"
                class="w-full h-[230px] border-0"
                scrolling="no"
                frameborder="0"
                allowfullscreen="true"
                allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share"
              ></iframe>
            </div>

            <!-- Thẻ kết nối nhanh Fanpage (đảm bảo hiển thị đẹp kể cả khi trình duyệt chặn cookie bên thứ 3) -->
            <div class="rounded-xl bg-white border border-slate-200 p-3.5 flex items-center justify-between gap-3">
              <div class="flex items-center gap-3 min-w-0">
                <img
                  src="https://drive.google.com/thumbnail?id=1bEUVC_WSn6CXUmYabU46kWxO5PBp2Iaq&sz=w200"
                  alt="Kingdoor Fanpage"
                  class="w-11 h-11 rounded-full object-contain border border-slate-200 p-1 bg-white shrink-0"
                  onerror="handleDriveImgError(this, '1bEUVC_WSn6CXUmYabU46kWxO5PBp2Iaq', 'KD')"
                >
                <div class="min-w-0">
                  <p class="text-xs sm:text-sm font-bold text-slate-800 truncate">CÔNG TY TNHH MTV KINGDOOR</p>
                  <p class="text-[11px] text-slate-500">Theo dõi công trình thực tế mới nhất tại Đà Nẵng</p>
                </div>
              </div>
              <a
                href="https://www.facebook.com/profile.php?id=100078389796234"
                target="_blank"
                rel="noopener noreferrer"
                class="shrink-0 px-3.5 py-2 rounded-lg bg-[#1877f2] hover:bg-[#1465d0] text-white text-xs font-bold transition"
              >
                Thích Trang
              </a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- ============================================================
       FOOTER CHUYÊN NGHIỆP (PHONG CÁCH FLATSOME 4 CỘT)
       ============================================================ -->
  <footer class="bg-brand-dark text-slate-200 pt-10 pb-6">
    <div class="kd-container">
      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-8 pb-8 border-b border-white/15">
        <!-- Cột 1: Thông tin công ty -->
        <div class="space-y-3">
          <div class="flex items-center gap-2.5">
            <div class="bg-white rounded-lg p-1.5 inline-flex items-center justify-center">
              <img
                src="https://drive.google.com/thumbnail?id=1bEUVC_WSn6CXUmYabU46kWxO5PBp2Iaq&sz=w300"
                alt="Logo Kingdoor"
                class="h-8 w-auto object-contain"
                onerror="handleDriveImgError(this, '1bEUVC_WSn6CXUmYabU46kWxO5PBp2Iaq', 'KINGDOOR')"
              >
            </div>
            <span class="text-sm font-extrabold text-white uppercase">KINGDOOR</span>
          </div>
          <p class="text-sm font-bold text-white">CÔNG TY TNHH MTV KINGDOOR</p>
          <ul class="space-y-2 text-xs sm:text-sm text-slate-300">
            <li><strong>Địa chỉ:</strong> 502 Ngô Quyền - Sơn Trà - Đà Nẵng</li>
            <li><strong>Hotline:</strong> <a href="tel:0905445498" class="text-amber-300 hover:underline">0905.445.498</a> – <a href="tel:0905398268" class="text-amber-300 hover:underline">0905.39.82.68</a></li>
            <li><strong>Website:</strong> <a href="https://kingdoor.com" class="hover:text-white underline">kingdoor.com</a></li>
            <li><strong>Giờ làm việc:</strong> Thứ 2 – Chủ Nhật (07:30 – 19:00)</li>
          </ul>
        </div>

        <!-- Cột 2: Danh mục Cửa nhôm Xingfa -->
        <div>
          <h4 class="text-sm font-bold text-white uppercase mb-3.5 pb-2 border-b border-white/15">Cửa Nhôm Xingfa</h4>
          <ul class="space-y-2 text-xs sm:text-sm text-slate-300">
            <li><a href="#san-pham-xingfa" onclick="filterProducts('1-canh')" class="hover:text-amber-300 transition">Cửa nhôm xingfa 1 cánh</a></li>
            <li><a href="#san-pham-xingfa" onclick="filterProducts('2-canh')" class="hover:text-amber-300 transition">Cửa nhôm xingfa 2 cánh</a></li>
            <li><a href="#san-pham-xingfa" onclick="filterProducts('3-canh')" class="hover:text-amber-300 transition">Cửa nhôm xingfa 3 cánh</a></li>
            <li><a href="#san-pham-xingfa" onclick="filterProducts('4-canh')" class="hover:text-amber-300 transition">Cửa nhôm xingfa 4 cánh</a></li>
            <li><a href="#san-pham-xingfa" onclick="filterProducts('5-canh')" class="hover:text-amber-300 transition">Cửa nhôm xingfa 5 cánh / Xếp trượt</a></li>
          </ul>
        </div>

        <!-- Cột 3: Danh mục sản phẩm -->
        <div>
          <h4 class="text-sm font-bold text-white uppercase mb-3.5 pb-2 border-b border-white/15">Danh Mục Sản Phẩm</h4>
          <ul class="space-y-2 text-xs sm:text-sm text-slate-300">
            <li><a href="#san-pham-xingfa" class="hover:text-amber-300 transition">Cửa nhôm xingfa</a></li>
            <li><a href="#danh-muc-san-pham" class="hover:text-amber-300 transition">Cửa nhựa lõi thép</a></li>
            <li><a href="#danh-muc-san-pham" class="hover:text-amber-300 transition">Cửa kính tự động</a></li>
            <li><a href="#danh-muc-san-pham" class="hover:text-amber-300 transition">Cầu thang kính</a></li>
            <li><a href="#danh-muc-san-pham" class="hover:text-amber-300 transition">Kính ốp bếp</a></li>
            <li><a href="#danh-muc-san-pham" class="hover:text-amber-300 transition">Phòng tắm kính</a></li>
          </ul>
        </div>

        <!-- Cột 4: Liên kết nhanh -->
        <div>
          <h4 class="text-sm font-bold text-white uppercase mb-3.5 pb-2 border-b border-white/15">Hỗ Trợ &amp; Kết Nối</h4>
          <ul class="space-y-2 text-xs sm:text-sm text-slate-300">
            <li><a href="#gioi-thieu" class="hover:text-amber-300 transition">Giới thiệu công ty</a></li>
            <li><a href="#cong-trinh" class="hover:text-amber-300 transition">Công trình đã thi công</a></li>
            <li><a href="#bao-gia" class="hover:text-amber-300 transition">Yêu cầu báo giá</a></li>
            <li><a href="#tin-tuc" class="hover:text-amber-300 transition">Tin tức &amp; Tư vấn</a></li>
            <li><a href="https://www.facebook.com/profile.php?id=100078389796234" target="_blank" rel="noopener noreferrer" class="hover:text-amber-300 transition">Fanpage Facebook Kingdoor</a></li>
          </ul>
        </div>
      </div>

      <div class="pt-5 flex flex-col sm:flex-row items-center justify-between gap-2 text-xs text-slate-400 text-center sm:text-left">
        <p>Copyright 2026 © Bản quyền thuộc về <strong class="text-white">CÔNG TY TNHH MTV KINGDOOR</strong> – kingdoor.com</p>
        <p>502 Ngô Quyền, Sơn Trà, Đà Nẵng</p>
      </div>
    </div>
  </footer>

  <!-- ============================================================
       NÚT LIÊN HỆ NỔI BẬT: ZALO, FACEBOOK, HOTLINE
       - Máy tính: Cụm nút nổi bên phải màn hình
       - Điện thoại: Thanh liên hệ cố định dưới đáy dễ chạm
       ============================================================ -->
  <!-- Phiên bản Máy tính -->
  <div class="hidden lg:flex fixed right-4 bottom-6 z-40 flex-col gap-2.5 items-end">
    <a
      href="https://zalo.me/0905445498"
      target="_blank"
      rel="noopener noreferrer"
      class="flex items-center gap-2.5 pl-4 pr-3 py-2.5 rounded-full bg-[#0068ff] hover:bg-[#0054d1] text-white shadow-lg transition transform hover:-translate-x-1"
      aria-label="Chat Zalo Kingdoor"
    >
      <span class="text-xs font-bold tracking-wide">Chat Zalo</span>
      <span class="w-8 h-8 rounded-full bg-white text-[#0068ff] font-extrabold text-[11px] flex items-center justify-center shrink-0">Zalo</span>
    </a>

    <a
      href="https://www.facebook.com/profile.php?id=100078389796234"
      target="_blank"
      rel="noopener noreferrer"
      class="flex items-center gap-2.5 pl-4 pr-3 py-2.5 rounded-full bg-[#1877f2] hover:bg-[#1465d0] text-white shadow-lg transition transform hover:-translate-x-1"
      aria-label="Fanpage Facebook Kingdoor"
    >
      <span class="text-xs font-bold tracking-wide">Facebook</span>
      <span class="w-8 h-8 rounded-full bg-white text-[#1877f2] flex items-center justify-center shrink-0">
        <svg class="w-4 h-4 fill-current" viewBox="0 0 24 24"><path d="M22.675 0h-21.35C.597 0 0 .597 0 1.326v21.348C0 23.403.597 24 1.326 24h11.495v-9.294H9.692v-3.622h3.129V8.413c0-3.1 1.893-4.788 4.659-4.788 1.325 0 2.463.099 2.795.143v3.24l-1.918.001c-1.504 0-1.795.715-1.795 1.763v2.313h3.587l-.467 3.622h-3.12V24h6.116C23.403 24 24 23.403 24 22.674V1.326C24 .597 23.403 0 22.675 0z"/></svg>
      </span>
    </a>

    <button
      type="button"
      onclick="openHotlineModal()"
      class="pulse-hotline flex items-center gap-2.5 pl-4 pr-3 py-2.5 rounded-full bg-[#dc2626] hover:bg-[#b91c1c] text-white shadow-lg transition transform hover:-translate-x-1"
      aria-label="Gọi Hotline Kingdoor"
    >
      <span class="text-xs font-bold tracking-wide">0905.445.498</span>
      <span class="w-8 h-8 rounded-full bg-white text-[#dc2626] flex items-center justify-center shrink-0">
        <svg class="w-4 h-4 fill-current" viewBox="0 0 24 24"><path d="M6.62 10.79a15.053 15.053 0 006.59 6.59l2.2-2.2a1 1 0 011.01-.24c1.12.37 2.33.57 3.58.57a1 1 0 011 1V20a1 1 0 01-1 1C10.61 21 3 13.39 3 4a1 1 0 011-1h3.5a1 1 0 011 1c0 1.25.2 2.46.57 3.58a1 1 0 01-.25 1.01l-2.2 2.2z"/></svg>
      </span>
    </button>
  </div>

  <!-- Phiên bản Điện thoại & Máy tính bảng: Thanh liên hệ 3 nút cân đối ở đáy màn hình -->
  <div class="lg:hidden fixed bottom-0 left-0 right-0 z-40 bg-white border-t border-slate-200 shadow-[0_-4px_16px_rgba(15,23,42,0.12)] px-2 py-2">
    <div class="grid grid-cols-3 gap-2 max-w-full">
      <button
        type="button"
        onclick="openHotlineModal()"
        class="flex items-center justify-center gap-1.5 py-2.5 px-2 rounded-xl bg-[#dc2626] text-white text-xs font-bold shadow-sm active:scale-95 transition"
      >
        <svg class="w-4 h-4 fill-current shrink-0" viewBox="0 0 24 24"><path d="M6.62 10.79a15.053 15.053 0 006.59 6.59l2.2-2.2a1 1 0 011.01-.24c1.12.37 2.33.57 3.58.57a1 1 0 011 1V20a1 1 0 01-1 1C10.61 21 3 13.39 3 4a1 1 0 011-1h3.5a1 1 0 011 1c0 1.25.2 2.46.57 3.58a1 1 0 01-.25 1.01l-2.2 2.2z"/></svg>
        <span>Hotline</span>
      </button>

      <a
        href="https://zalo.me/0905445498"
        target="_blank"
        rel="noopener noreferrer"
        class="flex items-center justify-center gap-1.5 py-2.5 px-2 rounded-xl bg-[#0068ff] text-white text-xs font-bold shadow-sm active:scale-95 transition"
      >
        <span class="px-1 py-0.5 rounded bg-white text-[#0068ff] text-[10px] font-extrabold leading-none">Zalo</span>
        <span>Chat Zalo</span>
      </a>

      <a
        href="https://www.facebook.com/profile.php?id=100078389796234"
        target="_blank"
        rel="noopener noreferrer"
        class="flex items-center justify-center gap-1.5 py-2.5 px-2 rounded-xl bg-[#1877f2] text-white text-xs font-bold shadow-sm active:scale-95 transition"
      >
        <svg class="w-4 h-4 fill-current shrink-0" viewBox="0 0 24 24"><path d="M22.675 0h-21.35C.597 0 0 .597 0 1.326v21.348C0 23.403.597 24 1.326 24h11.495v-9.294H9.692v-3.622h3.129V8.413c0-3.1 1.893-4.788 4.659-4.788 1.325 0 2.463.099 2.795.143v3.24l-1.918.001c-1.504 0-1.795.715-1.795 1.763v2.313h3.587l-.467 3.622h-3.12V24h6.116C23.403 24 24 23.403 24 22.674V1.326C24 .597 23.403 0 22.675 0z"/></svg>
        <span>Facebook</span>
      </a>
    </div>
  </div>

  <!-- ============================================================
       MODAL CHUNG: XEM CHI TIẾT SẢN PHẨM / BÀI VIẾT / CHỌN SỐ HOTLINE
       ============================================================ -->
  <div id="infoModal" class="hidden fixed inset-0 z-50 bg-slate-900/60 backdrop-blur-sm flex items-center justify-center p-4" onclick="closeModalOnBackdrop(event)">
    <div class="bg-white rounded-2xl max-w-lg w-full max-h-[88vh] overflow-y-auto shadow-2xl border border-slate-200">
      <div class="flex items-center justify-between px-5 py-4 border-b border-slate-100 sticky top-0 bg-white z-10">
        <h3 id="modalTitle" class="text-base font-extrabold text-brand-primary pr-4">Thông tin chi tiết</h3>
        <button type="button" onclick="closeInfoModal()" class="p-1.5 rounded-lg bg-slate-100 hover:bg-slate-200 text-slate-600" aria-label="Đóng cửa sổ">
          <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12"/></svg>
        </button>
      </div>
      <div id="modalBody" class="p-5 text-sm text-slate-700 space-y-4"></div>
    </div>
  </div>

  <!-- ============================================================
       JAVASCRIPT: XỬ LÝ ẢNH DRIVE, SLIDER, LỌC SẢN PHẨM, BÀI VIẾT & MÀU LOGO
       ============================================================ -->
  <script>
    /**
     * Cơ chế dự phòng tải ảnh Google Drive tin cậy qua nhiều đầu mối
     * 1) drive.google.com/thumbnail -> 2) lh3.googleusercontent.com -> 3) placehold.co
     */
    function handleDriveImgError(imgEl, fileId, fallbackLabel) {
      try {
        const attempt = parseInt(imgEl.dataset.attempt || '0', 10);
        if (attempt === 0) {
          imgEl.dataset.attempt = '1';
          imgEl.src = 'https://lh3.googleusercontent.com/d/' + fileId + '=w1000';
        } else if (attempt === 1) {
          imgEl.dataset.attempt = '2';
          imgEl.src = 'https://drive.google.com/uc?export=view&id=' + fileId;
        } else {
          imgEl.onerror = null;
          const safeText = encodeURIComponent(fallbackLabel || 'KINGDOOR');
          imgEl.src = 'https://placehold.co/600x450/0b3b75/ffffff?text=' + safeText;
        }
      } catch (err) {
        imgEl.onerror = null;
      }
    }

    /**
     * Tự động nhận diện màu chủ đạo từ logo Kingdoor (nếu trình duyệt cho phép CORS)
     * để đồng bộ màu trang web với màu logo một cách hài hòa.
     */
    function syncThemeWithLogo() {
      try {
        const probe = new Image();
        probe.crossOrigin = 'anonymous';
        probe.onload = function () {
          try {
            const canvas = document.createElement('canvas');
            const ctx = canvas.getContext('2d');
            canvas.width = 48;
            canvas.height = 48;
            ctx.drawImage(probe, 0, 0, 48, 48);
            const data = ctx.getImageData(0, 0, 48, 48).data;

            let bestR = 0, bestG = 0, bestB = 0, count = 0;
            for (let i = 0; i < data.length; i += 4) {
              const r = data[i], g = data[i + 1], b = data[i + 2], a = data[i + 3];
              if (a < 180) continue;
              const max = Math.max(r, g, b);
              const min = Math.min(r, g, b);
              const sat = max === 0 ? 0 : (max - min) / max;
              // Chỉ lấy các điểm màu thương hiệu đậm rõ (bỏ trắng/xám/đen)
              if (sat > 0.35 && max > 55 && min < 210) {
                bestR += r;
                bestG += g;
                bestB += b;
                count++;
              }
            }

            if (count > 25) {
              const r = Math.round(bestR / count);
              const g = Math.round(bestG / count);
              const b = Math.round(bestB / count);
              const primaryHex = '#' + [r, g, b].map(v => v.toString(16).padStart(2, '0')).join('');
              const darkHex = '#' + [r, g, b].map(v => Math.max(0, Math.round(v * 0.68)).toString(16).padStart(2, '0')).join('');
              document.documentElement.style.setProperty('--brand-primary', primaryHex);
              document.documentElement.style.setProperty('--brand-dark', darkHex);
            }
          } catch (e) {
            // Giữ nguyên bảng màu thương hiệu mặc định nếu bị hạn chế CORS
          }
        };
        probe.src = 'https://lh3.googleusercontent.com/d/1bEUVC_WSn6CXUmYabU46kWxO5PBp2Iaq=w200';
      } catch (e) {
        // Bỏ qua lỗi im lặng
      }
    }

    /* ============================================================
       DỮ LIỆU 6 SẢN PHẨM CỬA NHÔM XINGFA CHÍNH HÃNG KINGDOOR
       ============================================================ */
    const productsData = [
      {
        id: 1,
        name: 'Cửa đi quay mở 1 cánh nhôm Xingfa',
        category: '1-canh',
        driveId: '1-0eBWGjPwzQ-C9c1Wjws9wt0gbsulkPm',
        oldPrice: '2.350.000 ₫/m²',
        salePrice: '1.950.000 ₫/m²',
        discount: '-17%',
        specs: [
          'Thanh nhôm profile Xingfa hệ 55 nhập khẩu chính hãng',
          'Độ dày nhôm: 2.0mm (+-5%), ép góc ke nhôm đặc chuẩn xác',
          'Màu sắc: Ghi xám, Đen tuyền, Trắng sứ, Nâu cafe, Vân gỗ',
          'Kính an toàn 6.38mm hoặc kính cường lực 8mm – 10mm',
          'Phụ kiện Kinlong đồng bộ, gioăng kép EPDM kín khít'
        ]
      },
      {
        id: 2,
        name: 'Cửa đi quay mở 2 cánh nhôm Xingfa',
        category: '2-canh',
        driveId: '1h2r2rbPrEL7dgLE-MiE5lBBuE8gFNehb',
        oldPrice: '2.400.000 ₫/m²',
        salePrice: '2.050.000 ₫/m²',
        discount: '-15%',
        specs: [
          'Thanh nhôm Xingfa hệ 55 nhập khẩu Quảng Đông tem đỏ',
          'Độ dày khung và cánh cửa: 2.0mm chắc chắn, chịu lực tốt',
          'Cách âm, cách nhiệt, chống nước mưa tuyệt đối tại Đà Nẵng',
          'Kính dán an toàn 6.38mm / 8.38mm hoặc kính hộp cách âm',
          'Bảo hành thanh nhôm 5 năm, phụ kiện chính hãng 2 năm'
        ]
      },
      {
        id: 3,
        name: 'Cửa đi quay mở 3 cánh nhôm Xingfa',
        category: '3-canh',
        driveId: '17Qi2D8ntACnVrTeRPZ2V7rC0FmI8ecaR',
        oldPrice: '2.450.000 ₫/m²',
        salePrice: '2.080.000 ₫/m²',
        discount: '-15%',
        specs: [
          'Thanh nhôm Xingfa hệ 55 chính hãng dày 2.0mm',
          'Thiết kế mở quay 3 cánh tối ưu không gian lối đi rộng thoáng',
          'Sơn tĩnh điện ngoài trời cao cấp, bền màu theo thời gian',
          'Keo Dow Corning & ốc vít Inox 304 chống han gỉ vùng biển',
          'Lắp đặt trọn gói, nghiệm thu chuẩn kỹ thuật tại Đà Nẵng'
        ]
      },
      {
        id: 4,
        name: 'Cửa đi quay mở 4 cánh nhôm Xingfa',
        category: '4-canh',
        driveId: '1lxzMKWX3e_HJn7UELFZDOURuxh-NYZg-',
        oldPrice: '2.500.000 ₫/m²',
        salePrice: '2.100.000 ₫/m²',
        discount: '-16%',
        specs: [
          'Thanh nhôm Xingfa nhập khẩu hệ 55 độ dày 2.0mm',
          'Lựa chọn hàng đầu cho cửa mặt tiền nhà phố, biệt thự, khách sạn',
          'Khả năng chịu áp lực gió lên đến 1600 Pascal an toàn mùa bão',
          'Phụ kiện Kinlong cao cấp: bản lề 3D, khóa đa điểm chống trộm',
          'Cam kết đúng chủng loại, đo đạc thực tế và báo giá minh bạch'
        ]
      },
      {
        id: 5,
        name: 'Cửa Nhôm Xingfa Cửa Đi Xếp Trượt',
        category: '5-canh',
        driveId: '1lJpUJBpR_cJp8mIaZ4FnRTynQ_-paNwZ',
        oldPrice: '2.650.000 ₫/m²',
        salePrice: '2.200.000 ₫/m²',
        discount: '-17%',
        specs: [
          'Hệ nhôm Xingfa xếp trượt hệ 63 chuyên dụng (4, 5, 6, 8 cánh)',
          'Độ dày thanh nhôm 1.8mm – 3.5mm kết hợp ray trượt chịu lực êm ái',
          'Mở rộng đến 90% diện tích ô cửa, kết nối tối đa với sân vườn & hồ bơi',
          'Kính cường lực 8mm – 10mm an toàn, thẩm mỹ sang trọng',
          'Phù hợp biệt thự, resort, nhà hàng và mặt tiền rộng'
        ]
      },
      {
        id: 6,
        name: 'Cửa sổ mở hất 2 cánh nhôm Xingfa',
        category: '2-canh',
        driveId: '11fS_oEeJtnDICQZ77fJlYl6GhHf-GOhA',
        oldPrice: '2.200.000 ₫/m²',
        salePrice: '1.850.000 ₫/m²',
        discount: '-16%',
        specs: [
          'Thanh nhôm profile Xingfa hệ 55 chuyên cửa sổ, dày 1.4mm',
          'Mở hất góc tối đa 45 độ, chống hắt mưa và đón gió tự nhiên hiệu quả',
          'Thanh định vị giữ góc mở chống gió dập cực kỳ an toàn cho nhà cao tầng',
          'Gioăng kép EPDM kín khí giúp tiết kiệm điện năng điều hòa',
          'Bảo hành chính hãng, hỗ trợ bảo trì nhanh tại Đà Nẵng'
        ]
      }
    ];

    /* ============================================================
       DỮ LIỆU BÀI VIẾT TIN TỨC TRANG CHỦ
       ============================================================ */
    const newsData = [
      {
        id: 1,
        category: 'xingfa',
        categoryLabel: 'Kiến thức Xingfa',
        date: '15/11/2026',
        driveId: '1zRlHJBAneXS7EQ1jdT__hVRCTf2mzOiX',
        title: 'Cửa nhôm Xingfa có phù hợp với khí hậu biển Đà Nẵng không?',
        excerpt: 'Nhờ lớp sơn tĩnh điện ngoài trời cao cấp và phụ kiện inox chống gỉ, cửa nhôm Xingfa chịu gió bão và hơi muối biển rất bền bỉ.',
        content: 'Khí hậu ven biển Đà Nẵng có độ ẩm cao, nắng gắt và thường xuyên chịu ảnh hưởng của gió bão. Cửa nhôm Xingfa nhập khẩu tem đỏ kết hợp phụ kiện Kinlong đồng bộ, ốc vít Inox 304 và keo silicon chuyên dụng giúp ngăn nước mưa tuyệt đối, không bị cong vênh hay mối mọt như cửa gỗ thông thường. Đặc biệt, kết cấu khoang rỗng với gân gia cường giúp cửa chịu được áp lực gió lên đến 1600 Pascal.'
      },
      {
        id: 2,
        category: 'bao-gia',
        categoryLabel: 'Báo giá & Ưu đãi',
        date: '08/11/2026',
        driveId: '1lxzMKWX3e_HJn7UELFZDOURuxh-NYZg-',
        title: 'Báo giá thi công cửa nhôm Xingfa Đà Nẵng mới nhất 2026',
        excerpt: 'Cập nhật chi tiết đơn giá cửa đi mở quay, cửa sổ mở hất, cửa xếp trượt nhôm Xingfa nhập khẩu trọn gói tại xưởng Kingdoor.',
        content: 'Đơn giá thi công cửa nhôm Xingfa tại CÔNG TY TNHH MTV KINGDOOR dao động từ 1.850.000 ₫/m² đến 2.200.000 ₫/m² tùy theo hệ nhôm (hệ 55, hệ 93, hệ 63 xếp trượt), độ dày kính và khối lượng công trình. Khách hàng tại Đà Nẵng được miễn phí hoàn toàn chi phí khảo sát đo đạc, tư vấn bản vẽ và vận chuyển lắp đặt.'
      },
      {
        id: 3,
        category: 'kinh-nghiem',
        categoryLabel: 'Kinh nghiệm chọn cửa',
        date: '02/11/2026',
        driveId: '1MhCILHQ5goD1cAPTt1hZsY_ajeOMs-qH',
        title: 'Kinh nghiệm chọn kính cường lực cho phòng tắm kính & cầu thang',
        excerpt: 'Nên chọn kính cường lực dày 10mm hay 12mm? Phụ kiện inox 304 loại nào bền đẹp không bị rỉ sét trong môi trường ẩm?',
        content: 'Đối với phòng tắm kính cường lực, độ dày tiêu chuẩn tốt nhất là kính cường lực 10mm kết hợp bộ phụ kiện bản lề, kẹp kính, giằng chống rung bằng Inox 304 chính hãng. Riêng cầu thang kính và lan can kính ban công nên ưu tiên kính cường lực 10mm hoặc 12mm để đảm bảo độ vững chắc và an toàn tuyệt đối cho gia đình có trẻ nhỏ.'
      },
      {
        id: 4,
        category: 'xingfa',
        categoryLabel: 'Kiến thức Xingfa',
        date: '26/10/2026',
        driveId: '1lJpUJBpR_cJp8mIaZ4FnRTynQ_-paNwZ',
        title: 'Cách phân biệt nhôm Xingfa nhập khẩu tem đỏ chính hãng',
        excerpt: 'Hướng dẫn kiểm tra tem đỏ mã QR, ánh kim bên trong thanh nhôm và độ dày tiêu chuẩn 1.4mm – 2.0mm khi nghiệm thu công trình.',
        content: 'Nhôm Xingfa Quảng Đông tem đỏ chính hãng có tem chữ in sắc nét, tích hợp mã QR quét xác thực nguồn gốc rõ ràng. Mặt cắt bên trong thanh nhôm có lớp mạ crom ánh kim chống oxy hóa, bề mặt sơn tĩnh điện mịn đều, góc cửa được ép bằng máy ép góc thủy lực kín khít thay vì bắt vít thủ công.'
      }
    ];

    /**
     * Render danh sách sản phẩm theo bộ lọc
     */
    function renderProducts(filterKey) {
      const grid = document.getElementById('productGrid');
      if (!grid) return;

      const list = filterKey === 'all'
        ? productsData
        : productsData.filter(item => item.category === filterKey);

      grid.innerHTML = list.map(item => `
        <article class="bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
          <!-- Khung ảnh sản phẩm + Nhãn giảm giá % góc trên bên trái -->
          <div class="relative aspect-[4/3] overflow-hidden bg-slate-100 cursor-pointer" onclick="openProductModal(${item.id})">
            <span class="absolute top-2 left-2 z-10 px-2 py-0.5 sm:px-2.5 sm:py-1 rounded-md bg-[#dc2626] text-white text-[11px] sm:text-xs font-extrabold shadow">
              ${item.discount}
            </span>
            <img
              src="https://drive.google.com/thumbnail?id=${item.driveId}&sz=w800"
              alt="${item.name}"
              class="w-full h-full object-cover hover:scale-105 transition duration-300"
              onerror="handleDriveImgError(this, '${item.driveId}', '${item.name}')"
            >
          </div>

          <!-- Thông tin sản phẩm: Tên đầy đủ không bị cắt chữ, giá rõ ràng -->
          <div class="p-2.5 sm:p-4 flex-1 flex flex-col justify-between gap-2">
            <div>
              <h3
                onclick="openProductModal(${item.id})"
                class="text-[12.5px] sm:text-sm md:text-[15px] font-bold text-slate-800 hover:text-brand-primary cursor-pointer leading-snug break-words"
              >
                ${item.name}
              </h3>

              <!-- Giá gốc & giá ưu đãi -->
              <div class="mt-2 flex flex-wrap items-baseline gap-x-2 gap-y-0.5">
                <span class="text-xs sm:text-base font-extrabold text-[#dc2626]">${item.salePrice}</span>
                <span class="text-[11px] sm:text-xs text-slate-400 line-through">${item.oldPrice}</span>
              </div>
            </div>

            <div class="pt-1 grid grid-cols-1 sm:grid-cols-2 gap-1.5">
              <button
                type="button"
                onclick="openProductModal(${item.id})"
                class="w-full py-1.5 sm:py-2 px-2 rounded-lg border border-brand-primary text-brand-primary hover:bg-brand-light text-[11px] sm:text-xs font-bold transition"
              >
                Xem chi tiết
              </button>
              <a
                href="#bao-gia"
                onclick="preselectQuote('${item.name}')"
                class="w-full py-1.5 sm:py-2 px-2 rounded-lg bg-brand-primary hover:bg-brand-dark text-white text-[11px] sm:text-xs font-bold text-center transition"
              >
                Nhận báo giá
              </a>
            </div>
          </div>
        </article>
      `).join('');
    }

    function filterProducts(filterKey) {
      renderProducts(filterKey);
      const buttons = document.querySelectorAll('.filter-tab');
      buttons.forEach(btn => {
        const isActive = btn.dataset.filter === filterKey;
        if (isActive) {
          btn.className = 'filter-tab px-3.5 py-1.5 rounded-lg text-xs sm:text-sm font-semibold bg-brand-primary text-white transition';
        } else {
          btn.className = 'filter-tab px-3.5 py-1.5 rounded-lg text-xs sm:text-sm font-semibold bg-white text-slate-700 border border-slate-200 hover:border-brand-primary transition';
        }
      });
    }

    /**
     * Render danh sách bài viết tin tức theo danh mục
     */
    function renderNews(catKey) {
      const grid = document.getElementById('newsGrid');
      if (!grid) return;

      const list = catKey === 'all'
        ? newsData
        : newsData.filter(item => item.category === catKey);

      grid.innerHTML = list.map(post => `
        <article class="bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
          <div class="aspect-[16/10] overflow-hidden bg-slate-100 cursor-pointer" onclick="openNewsModal(${post.id})">
            <img
              src="https://drive.google.com/thumbnail?id=${post.driveId}&sz=w600"
              alt="${post.title}"
              class="w-full h-full object-cover hover:scale-105 transition duration-300"
              onerror="handleDriveImgError(this, '${post.driveId}', 'Tin Tức Kingdoor')"
            >
          </div>
          <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between gap-2">
            <div>
              <div class="text-[11px] font-semibold text-brand-accent mb-1">${post.categoryLabel} • ${post.date}</div>
              <h3
                onclick="openNewsModal(${post.id})"
                class="text-xs sm:text-sm font-bold text-slate-800 hover:text-brand-primary cursor-pointer leading-snug break-words"
              >
                ${post.title}
              </h3>
              <p class="text-[11px] sm:text-xs text-slate-600 mt-1.5 leading-relaxed hidden sm:block">
                ${post.excerpt}
              </p>
            </div>
            <button
              type="button"
              onclick="openNewsModal(${post.id})"
              class="self-start text-xs font-bold text-brand-primary hover:text-brand-accent transition pt-1"
            >
              Đọc tiếp →
            </button>
          </div>
        </article>
      `).join('');
    }

    function filterNews(catKey) {
      renderNews(catKey);
      const buttons = document.querySelectorAll('.news-tab');
      buttons.forEach(btn => {
        const isActive = btn.dataset.newsCat === catKey;
        if (isActive) {
          btn.className = 'news-tab px-3.5 py-1.5 rounded-lg text-xs font-semibold bg-brand-primary text-white transition';
        } else {
          btn.className = 'news-tab px-3.5 py-1.5 rounded-lg text-xs font-semibold bg-slate-100 text-slate-700 hover:bg-slate-200 transition';
        }
      });
    }

    /* ============================================================
       SLIDER 2 BANNER TỰ TRƯỢT MƯỢT MÀ
       ============================================================ */
    let currentBanner = 0;
    let bannerTimer = null;

    function goToBanner(index) {
      const slides = document.querySelectorAll('#heroBannerStage .banner-slide');
      if (!slides.length) return;
      currentBanner = (index + slides.length) % slides.length;

      slides.forEach((slide, idx) => {
        slide.classList.toggle('is-active', idx === currentBanner);
      });

      for (let i = 0; i < slides.length; i++) {
        const dot = document.getElementById('dot-' + i);
        if (!dot) continue;
        if (i === currentBanner) {
          dot.className = 'w-7 h-2 rounded-full bg-brand-accent transition-all';
        } else {
          dot.className = 'w-2.5 h-2 rounded-full bg-white/40 hover:bg-white/70 transition-all';
        }
      }
      resetBannerTimer();
    }

    function changeBanner(step) {
      goToBanner(currentBanner + step);
    }

    function resetBannerTimer() {
      if (bannerTimer) clearInterval(bannerTimer);
      bannerTimer = setInterval(() => {
        changeBanner(1);
      }, 5000);
    }

    /* ============================================================
       MENU ĐIỆN THOẠI & ACCORDION DANH MỤC CON
       ============================================================ */
    const mobileMenuBtn = document.getElementById('mobileMenuBtn');
    const mobileMenuDrawer = document.getElementById('mobileMenuDrawer');

    if (mobileMenuBtn && mobileMenuDrawer) {
      mobileMenuBtn.addEventListener('click', () => {
        const isHidden = mobileMenuDrawer.classList.toggle('hidden');
        mobileMenuBtn.setAttribute('aria-expanded', String(!isHidden));
      });
    }

    function closeMobileMenu() {
      if (mobileMenuDrawer) mobileMenuDrawer.classList.add('hidden');
      if (mobileMenuBtn) mobileMenuBtn.setAttribute('aria-expanded', 'false');
    }

    function toggleMobileSub(id, btn) {
      const sub = document.getElementById(id);
      if (!sub) return;
      const isHidden = sub.classList.toggle('hidden');
      const icon = btn.querySelector('svg');
      if (icon) {
        icon.style.transform = isHidden ? 'rotate(0deg)' : 'rotate(180deg)';
      }
    }

    /* ============================================================
       MODAL CHI TIẾT SẢN PHẨM, BÀI VIẾT & HOTLINE
       ============================================================ */
    function openInfoModal(title, htmlContent) {
      document.getElementById('modalTitle').textContent = title;
      document.getElementById('modalBody').innerHTML = htmlContent;
      document.getElementById('infoModal').classList.remove('hidden');
    }

    function closeInfoModal() {
      document.getElementById('infoModal').classList.add('hidden');
    }

    function closeModalOnBackdrop(event) {
      if (event.target.id === 'infoModal') {
        closeInfoModal();
      }
    }

    function openProductModal(productId) {
      const item = productsData.find(p => p.id === productId);
      if (!item) return;
      const html = `
        <div class="relative rounded-xl overflow-hidden bg-slate-100 aspect-[16/10]">
          <span class="absolute top-2.5 left-2.5 px-2.5 py-1 rounded-md bg-[#dc2626] text-white text-xs font-extrabold">${item.discount}</span>
          <img src="https://drive.google.com/thumbnail?id=${item.driveId}&sz=w900" alt="${item.name}" class="w-full h-full object-cover" onerror="handleDriveImgError(this, '${item.driveId}', '${item.name}')">
        </div>
        <div class="flex items-baseline gap-3">
          <span class="text-xl font-extrabold text-[#dc2626]">${item.salePrice}</span>
          <span class="text-sm text-slate-400 line-through">${item.oldPrice}</span>
        </div>
        <div>
          <h4 class="font-bold text-slate-800 mb-2">Thông số kỹ thuật tiêu chuẩn Kingdoor:</h4>
          <ul class="space-y-1.5 text-slate-600 text-xs sm:text-sm">
            ${item.specs.map(s => `<li class="flex items-start gap-2"><span class="text-brand-accent font-bold">•</span><span>${s}</span></li>`).join('')}
          </ul>
        </div>
        <div class="grid grid-cols-2 gap-2.5 pt-2">
          <a href="tel:0905445498" class="py-2.5 px-3 rounded-lg bg-[#dc2626] text-white text-center text-xs sm:text-sm font-bold hover:opacity-95 transition">Gọi 0905.445.498</a>
          <a href="#bao-gia" onclick="closeInfoModal(); preselectQuote('${item.name}')" class="py-2.5 px-3 rounded-lg bg-brand-primary text-white text-center text-xs sm:text-sm font-bold hover:opacity-95 transition">Yêu cầu báo giá</a>
        </div>
      `;
      openInfoModal(item.name, html);
    }

    function openNewsModal(postId) {
      const post = newsData.find(n => n.id === postId);
      if (!post) return;
      const html = `
        <div class="rounded-xl overflow-hidden bg-slate-100 aspect-[16/10]">
          <img src="https://drive.google.com/thumbnail?id=${post.driveId}&sz=w800" alt="${post.title}" class="w-full h-full object-cover" onerror="handleDriveImgError(this, '${post.driveId}', 'Tin tức Kingdoor')">
        </div>
        <div class="text-xs font-semibold text-brand-accent">${post.categoryLabel} • Cập nhật ${post.date}</div>
        <p class="text-sm text-slate-700 leading-relaxed">${post.content}</p>
        <div class="rounded-xl bg-brand-light p-3.5 text-xs sm:text-sm text-slate-700">
          <strong>CÔNG TY TNHH MTV KINGDOOR</strong> – 502 Ngô Quyền, Sơn Trà, Đà Nẵng.<br>
          Hotline tư vấn: <a href="tel:0905445498" class="font-bold text-brand-primary">0905.445.498</a> – <a href="tel:0905398268" class="font-bold text-brand-primary">0905.39.82.68</a>
        </div>
      `;
      openInfoModal(post.title, html);
    }

    function openHotlineModal() {
      const html = `
        <p class="text-sm text-slate-600">Chọn số Hotline của <strong>CÔNG TY TNHH MTV KINGDOOR</strong> để gọi tư vấn &amp; khảo sát miễn phí tại Đà Nẵng:</p>
        <div class="space-y-2.5">
          <a href="tel:0905445498" class="flex items-center justify-between p-3.5 rounded-xl bg-red-50 border border-red-200 hover:bg-red-100 transition">
            <div>
              <div class="text-xs text-slate-500">Hotline 1 (Tư vấn &amp; Báo giá)</div>
              <div class="text-base font-extrabold text-[#dc2626]">0905.445.498</div>
            </div>
            <span class="px-3 py-1.5 rounded-lg bg-[#dc2626] text-white text-xs font-bold">Gọi ngay</span>
          </a>
          <a href="tel:0905398268" class="flex items-center justify-between p-3.5 rounded-xl bg-blue-50 border border-blue-200 hover:bg-blue-100 transition">
            <div>
              <div class="text-xs text-slate-500">Hotline 2 (Kỹ thuật &amp; Thi công)</div>
              <div class="text-base font-extrabold text-brand-primary">0905.39.82.68</div>
            </div>
            <span class="px-3 py-1.5 rounded-lg bg-brand-primary text-white text-xs font-bold">Gọi ngay</span>
          </a>
        </div>
      `;
      openInfoModal('Hotline CÔNG TY TNHH MTV KINGDOOR', html);
    }

    function preselectQuote(productName) {
      const select = document.getElementById('qProduct');
      const note = document.getElementById('qNote');
      if (select) {
        let matched = false;
        for (let i = 0; i < select.options.length; i++) {
          if (select.options[i].value.toLowerCase().includes(productName.toLowerCase())) {
            select.selectedIndex = i;
            matched = true;
            break;
          }
        }
        if (!matched && note) {
          note.value = 'Quan tâm sản phẩm: ' + productName;
        }
      }
    }

    /* ============================================================
       XỬ LÝ FORM YÊU CẦU BÁO GIÁ (KHÔNG DÙNG ALERT)
       ============================================================ */
    const quoteForm = document.getElementById('quoteForm');
    if (quoteForm) {
      quoteForm.addEventListener('submit', function (e) {
        e.preventDefault();
        const name = document.getElementById('qName').value.trim();
        const phone = document.getElementById('qPhone').value.trim();
        const product = document.getElementById('qProduct').value;
        const feedback = document.getElementById('quoteFeedback');

        if (!name || !phone) {
          feedback.className = 'rounded-lg p-3 text-xs sm:text-sm font-medium bg-red-50 text-red-700 border border-red-200';
          feedback.textContent = 'Vui lòng nhập đầy đủ Họ tên và Số điện thoại để Kingdoor liên hệ báo giá.';
          feedback.classList.remove('hidden');
          return;
        }

        feedback.className = 'rounded-lg p-3 text-xs sm:text-sm font-medium bg-emerald-50 text-emerald-800 border border-emerald-200';
        feedback.innerHTML = `Cảm ơn <strong>${name}</strong>! Yêu cầu báo giá <strong>${product}</strong> đã được gửi tới <strong>CÔNG TY TNHH MTV KINGDOOR</strong>. Chúng tôi sẽ gọi lại số <strong>${phone}</strong> trong ít phút.`;
        feedback.classList.remove('hidden');
        quoteForm.reset();
      });
    }

    /* Khởi tạo toàn bộ nội dung khi tải trang */
    window.addEventListener('DOMContentLoaded', function () {
      renderProducts('all');
      renderNews('all');
      resetBannerTimer();
      syncThemeWithLogo();
    });
  </script>
</body>
</html>
