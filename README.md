<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CÔNG TY TNHH XÂY DỰNG ĐẠI QUANG HỘI | Thiết Kế & Thi Công Trọn Gói Đà Nẵng - daiquanghoi.com</title>
    <meta name="description" content="Công Ty TNHH Xây Dựng Đại Quang Hội (daiquanghoi.com) chuyên thiết kế kiến trúc, thi công phần thô, thi công hoàn thiện nhà phố, biệt thự, căn hộ cho thuê, khách sạn uy tín tại Đà Nẵng. Hotline: 0932.103.549.">

    <!-- Thumbnail logo hiển thị khi chia sẻ liên kết trang web (Open Graph & Twitter Card) -->
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://daiquanghoi.com/">
    <meta property="og:site_name" content="CÔNG TY TNHH XÂY DỰNG ĐẠI QUANG HỘI">
    <meta property="og:title" content="CÔNG TY TNHH XÂY DỰNG ĐẠI QUANG HỘI - Thiết Kế & Thi Công Xây Dựng Đà Nẵng">
    <meta property="og:description" content="Làm việc bằng tâm - Xứng tầm chất lượng. Thiết kế & thi công trọn gói nhà phố, biệt thự, căn hộ cho thuê tại Đà Nẵng. Hotline: 0932.103.549.">
    <meta property="og:image" content="https://lh3.googleusercontent.com/d/1rKETtm1G4VkohFkUMZToI0dkvmVaTHUC">
    <meta property="og:image:secure_url" content="https://drive.google.com/thumbnail?id=1rKETtm1G4VkohFkUMZToI0dkvmVaTHUC&sz=w1000">
    <meta property="og:image:alt" content="Logo Công Ty TNHH Xây Dựng Đại Quang Hội">
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:title" content="CÔNG TY TNHH XÂY DỰNG ĐẠI QUANG HỘI - daiquanghoi.com">
    <meta name="twitter:description" content="Nhà thầu thiết kế & thi công xây dựng trọn gói uy tín hàng đầu tại Đà Nẵng. Hotline: 0932.103.549.">
    <meta name="twitter:image" content="https://lh3.googleusercontent.com/d/1rKETtm1G4VkohFkUMZToI0dkvmVaTHUC">
    <link rel="icon" type="image/png" href="https://lh3.googleusercontent.com/d/1rKETtm1G4VkohFkUMZToI0dkvmVaTHUC">

    <!-- Font Inter & Font Awesome Icons -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

    <!-- Tailwind CSS CDN -->
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
                            primary: '#0B3B75',     /* Xanh dương đậm chuẩn thương hiệu xây dựng */
                            dark: '#072750',        /* Xanh đậm footer & hover */
                            light: '#EAF2FB',       /* Nền xanh nhạt tinh tế */
                            accent: '#D98218',      /* Vàng cam xây dựng nổi bật */
                            accentHover: '#B96B0F',
                        }
                    }
                }
            }
        }
    </script>

    <!-- Thiết lập chuẩn Flatsome, khung 95% trên máy tính, chống tràn viền & lệch phải -->
    <style>
        :root {
            --brand-primary: #0B3B75;
            --brand-dark: #072750;
            --brand-accent: #D98218;
        }

        *, *::before, *::after {
            box-sizing: border-box;
        }

        html, body {
            width: 100%;
            max-width: 100%;
            overflow-x: hidden;
            margin: 0;
            padding: 0;
            scroll-behavior: smooth;
            font-family: 'Inter', sans-serif;
            background-color: #ffffff;
            color: #1e293b;
        }

        /* Chiều ngang giao diện trên máy tính bằng 95% kích thước màn hình, căn giữa chuẩn xác */
        .flatsome-container {
            width: 94%;
            max-width: 100%;
            margin-left: auto;
            margin-right: auto;
        }

        @media (min-width: 1024px) {
            .flatsome-container {
                width: 95%;
                max-width: 95%;
            }
        }

        /* Thanh điều hướng máy tính viết liền 1 hàng, không xuống dòng tên danh mục */
        .desktop-nav-item {
            white-space: nowrap;
        }

        /* Dropdown menu chuẩn Flatsome */
        .nav-dropdown-wrapper:hover .nav-dropdown-menu {
            opacity: 1;
            visibility: visible;
            transform: translateY(0);
        }

        .nav-dropdown-menu {
            opacity: 0;
            visibility: hidden;
            transform: translateY(8px);
            transition: all 0.2s ease;
        }

        /* Thanh gạch tiêu đề chuẩn Flatsome */
        .section-title-bar {
            position: relative;
            display: inline-block;
            padding-bottom: 10px;
        }
        .section-title-bar::after {
            content: '';
            position: absolute;
            left: 50%;
            bottom: 0;
            transform: translateX(-50%);
            width: 64px;
            height: 3px;
            border-radius: 999px;
            background: linear-gradient(90deg, var(--brand-primary), var(--brand-accent));
        }

        .section-title-bar-left {
            position: relative;
            display: inline-block;
            padding-bottom: 10px;
        }
        .section-title-bar-left::after {
            content: '';
            position: absolute;
            left: 0;
            bottom: 0;
            width: 64px;
            height: 3px;
            border-radius: 999px;
            background: linear-gradient(90deg, var(--brand-primary), var(--brand-accent));
        }

        /* Banner tự trượt: 2 slide kích thước bằng nhau hoàn toàn */
        .hero-slider-stage {
            position: relative;
            width: 100%;
            overflow: hidden;
        }

        .hero-slide {
            position: absolute;
            inset: 0;
            width: 100%;
            height: 100%;
            opacity: 0;
            pointer-events: none;
            transition: opacity 0.65s ease-in-out;
            z-index: 1;
        }

        .hero-slide.active {
            opacity: 1;
            pointer-events: auto;
            z-index: 2;
        }

        /* Hiệu ứng nhịp sóng tinh tế cho nút Hotline nổi */
        @keyframes pulseRing {
            0% {
                transform: scale(0.95);
                box-shadow: 0 0 0 0 rgba(220, 38, 38, 0.55);
            }
            70% {
                transform: scale(1);
                box-shadow: 0 0 0 12px rgba(220, 38, 38, 0);
            }
            100% {
                transform: scale(0.95);
                box-shadow: 0 0 0 0 rgba(220, 38, 38, 0);
            }
        }

        .hotline-pulse {
            animation: pulseRing 2s infinite;
        }

        /* Ẩn thanh cuộn phụ trên thiết bị di động khi vuốt danh mục ngang */
        .no-scrollbar::-webkit-scrollbar {
            display: none;
        }
        .no-scrollbar {
            -ms-overflow-style: none;
            scrollbar-width: none;
        }
    </style>
</head>
<body class="antialiased text-slate-800 bg-white">

    <!-- =================================================================== -->
    <!-- 1. TOP BAR THÔNG TIN LIÊN HỆ (CHUẨN FLATSOME, KHÔNG THANH UXBUILDER) -->
    <!-- =================================================================== -->
    <div class="bg-brand-dark text-slate-100 text-xs py-2 border-b border-white/10">
        <div class="flatsome-container flex flex-wrap items-center justify-between gap-y-1 gap-x-4">
            <div class="flex flex-wrap items-center gap-x-4 gap-y-1">
                <a href="tel:0932103549" class="inline-flex items-center gap-1.5 hover:text-amber-300 transition-colors whitespace-nowrap">
                    <i class="fa-solid fa-phone text-brand-accent text-[11px]"></i>
                    <span>0932.103.549</span>
                </a>
                <a href="mailto:daiquanghoi@gmail.com" class="hidden sm:inline-flex items-center gap-1.5 hover:text-amber-300 transition-colors whitespace-nowrap">
                    <i class="fa-solid fa-envelope text-brand-accent text-[11px]"></i>
                    <span>daiquanghoi@gmail.com</span>
                </a>
                <span class="hidden lg:inline-flex items-center gap-1.5 text-slate-300 whitespace-nowrap">
                    <i class="fa-solid fa-location-dot text-brand-accent text-[11px]"></i>
                    <span>186/54 Phạm Như Xương, Phường Liên Chiểu, TP Đà Nẵng</span>
                </span>
            </div>
            <div class="flex items-center gap-3">
                <span class="hidden md:inline text-slate-300 font-medium">Làm việc bằng tâm - Xứng tầm chất lượng</span>
                <a href="https://www.facebook.com/nhathauxaydungdndaiquanghoi" target="_blank" rel="noopener noreferrer" aria-label="Facebook Đại Quang Hội" class="hover:text-amber-300 transition-colors">
                    <i class="fa-brands fa-facebook text-sm"></i>
                </a>
                <a href="https://zalo.me/0932103549" target="_blank" rel="noopener noreferrer" aria-label="Zalo Đại Quang Hội" class="hover:text-amber-300 transition-colors font-bold text-[11px] tracking-wide">
                    Zalo
                </a>
            </div>
        </div>
    </div>

    <!-- =================================================================== -->
    <!-- 2. HEADER CHÍNH (LOGO GỌN NHỎ, MENU 1 HÀNG, KHÔNG NÚT GỌI NGAY)     -->
    <!-- =================================================================== -->
    <header id="main-header" class="sticky top-0 z-40 bg-white/95 backdrop-blur border-b border-slate-200 shadow-sm">
        <div class="flatsome-container flex items-center justify-between py-2.5 lg:py-3 gap-3">
            <!-- Logo Công Ty (chỉnh gọn nhỏ, sắc nét) -->
            <a href="#trang-chu" class="flex items-center gap-2.5 shrink-0 min-w-0">
                <img
                    src="https://lh3.googleusercontent.com/d/1rKETtm1G4VkohFkUMZToI0dkvmVaTHUC"
                    data-gdrive-id="1rKETtm1G4VkohFkUMZToI0dkvmVaTHUC"
                    alt="Logo Công Ty TNHH Xây Dựng Đại Quang Hội"
                    class="h-10 sm:h-11 lg:h-12 w-auto max-w-[120px] object-contain rounded-md"
                    onerror="handleDriveImageError(this, true)"
                >
                <div class="leading-tight">
                    <div class="text-brand-primary font-extrabold text-sm sm:text-base tracking-tight whitespace-nowrap">ĐẠI QUANG HỘI</div>
                    <div class="text-[10px] sm:text-[11px] text-slate-500 font-medium tracking-wide whitespace-nowrap">XÂY DỰNG TRỌN GÓI ĐÀ NẴNG</div>
                </div>
            </a>

            <!-- Menu Máy Tính: Viết liền trên 1 hàng, chữ gọn sắc nét, không xuống dòng -->
            <nav aria-label="Menu chính" class="hidden lg:flex items-center justify-end gap-1 xl:gap-2 flex-nowrap">
                <a href="#trang-chu" class="desktop-nav-item px-2 xl:px-2.5 py-2 text-[12px] xl:text-[13px] font-semibold text-brand-primary hover:text-brand-accent transition-colors rounded-lg">
                    Trang chủ
                </a>
                <a href="#gioi-thieu" class="desktop-nav-item px-2 xl:px-2.5 py-2 text-[12px] xl:text-[13px] font-semibold text-slate-700 hover:text-brand-primary transition-colors rounded-lg">
                    Giới thiệu
                </a>

                <!-- Dropdown: Công trình thực tế (theo danh mục web mẫu) -->
                <div class="relative nav-dropdown-wrapper">
                    <a href="#cong-trinh-thuc-te" class="desktop-nav-item inline-flex items-center gap-1 px-2 xl:px-2.5 py-2 text-[12px] xl:text-[13px] font-semibold text-slate-700 hover:text-brand-primary transition-colors rounded-lg">
                        <span>Công trình thực tế</span>
                        <i class="fa-solid fa-chevron-down text-[9px] opacity-70"></i>
                    </a>
                    <div class="nav-dropdown-menu absolute left-0 top-full pt-1 w-60 z-50">
                        <div class="bg-white rounded-xl shadow-xl border border-slate-100 py-2">
                            <button type="button" onclick="selectCategoryAndScroll('can-ho')" class="w-full text-left px-4 py-2 text-xs font-medium text-slate-700 hover:bg-brand-light hover:text-brand-primary transition-colors">Khách sạn – Căn hộ – Phòng trọ</button>
                            <button type="button" onclick="selectCategoryAndScroll('biet-thu')" class="w-full text-left px-4 py-2 text-xs font-medium text-slate-700 hover:bg-brand-light hover:text-brand-primary transition-colors">Biệt thự</button>
                            <button type="button" onclick="selectCategoryAndScroll('nha-pho')" class="w-full text-left px-4 py-2 text-xs font-medium text-slate-700 hover:bg-brand-light hover:text-brand-primary transition-colors">Nhà phố</button>
                            <button type="button" onclick="selectCategoryAndScroll('van-phong')" class="w-full text-left px-4 py-2 text-xs font-medium text-slate-700 hover:bg-brand-light hover:text-brand-primary transition-colors">Văn phòng – Nội thất</button>
                        </div>
                    </div>
                </div>

                <!-- Dropdown: Lĩnh vực hoạt động -->
                <div class="relative nav-dropdown-wrapper">
                    <a href="#dich-vu" class="desktop-nav-item inline-flex items-center gap-1 px-2 xl:px-2.5 py-2 text-[12px] xl:text-[13px] font-semibold text-slate-700 hover:text-brand-primary transition-colors rounded-lg">
                        <span>Lĩnh vực hoạt động</span>
                        <i class="fa-solid fa-chevron-down text-[9px] opacity-70"></i>
                    </a>
                    <div class="nav-dropdown-menu absolute left-0 top-full pt-1 w-56 z-50">
                        <div class="bg-white rounded-xl shadow-xl border border-slate-100 py-2">
                            <a href="#dich-vu" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-brand-light hover:text-brand-primary transition-colors">Thiết kế Kiến trúc – Nội thất</a>
                            <button type="button" onclick="selectCategoryAndScroll('phan-tho')" class="w-full text-left px-4 py-2 text-xs font-medium text-slate-700 hover:bg-brand-light hover:text-brand-primary transition-colors">Thi công phần thô</button>
                            <button type="button" onclick="selectCategoryAndScroll('hoan-thien')" class="w-full text-left px-4 py-2 text-xs font-medium text-slate-700 hover:bg-brand-light hover:text-brand-primary transition-colors">Thi công hoàn thiện</button>
                            <button type="button" onclick="selectCategoryAndScroll('van-phong')" class="w-full text-left px-4 py-2 text-xs font-medium text-slate-700 hover:bg-brand-light hover:text-brand-primary transition-colors">Thi công nội thất</button>
                        </div>
                    </div>
                </div>

                <a href="#du-an-da-nang" class="desktop-nav-item px-2 xl:px-2.5 py-2 text-[12px] xl:text-[13px] font-semibold text-slate-700 hover:text-brand-primary transition-colors rounded-lg">
                    Dự án Đà Nẵng
                </a>

                <!-- Dropdown: Báo giá -->
                <div class="relative nav-dropdown-wrapper">
                    <a href="#bao-gia" class="desktop-nav-item inline-flex items-center gap-1 px-2 xl:px-2.5 py-2 text-[12px] xl:text-[13px] font-semibold text-slate-700 hover:text-brand-primary transition-colors rounded-lg">
                        <span>Báo giá</span>
                        <i class="fa-solid fa-chevron-down text-[9px] opacity-70"></i>
                    </a>
                    <div class="nav-dropdown-menu absolute left-0 top-full pt-1 w-56 z-50">
                        <div class="bg-white rounded-xl shadow-xl border border-slate-100 py-2">
                            <a href="#bao-gia" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-brand-light hover:text-brand-primary transition-colors">Báo giá thiết kế kiến trúc</a>
                            <a href="#bao-gia" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-brand-light hover:text-brand-primary transition-colors">Báo giá thi công phần thô</a>
                            <a href="#bao-gia" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-brand-light hover:text-brand-primary transition-colors">Báo giá thi công hoàn thiện</a>
                            <a href="#bao-gia" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-brand-light hover:text-brand-primary transition-colors">Báo giá thi công trọn gói</a>
                        </div>
                    </div>
                </div>

                <a href="#doi-tac" class="desktop-nav-item px-2 xl:px-2.5 py-2 text-[12px] xl:text-[13px] font-semibold text-slate-700 hover:text-brand-primary transition-colors rounded-lg">
                    Đối tác
                </a>
                <a href="#tin-tuc" class="desktop-nav-item px-2 xl:px-2.5 py-2 text-[12px] xl:text-[13px] font-semibold text-slate-700 hover:text-brand-primary transition-colors rounded-lg">
                    Tin tức
                </a>
                <a href="#lien-he" class="desktop-nav-item px-2 xl:px-2.5 py-2 text-[12px] xl:text-[13px] font-semibold text-slate-700 hover:text-brand-primary transition-colors rounded-lg">
                    Liên hệ
                </a>
            </nav>

            <!-- Nút mở Menu trên Điện thoại / Tablet -->
            <button
                id="mobile-menu-btn"
                type="button"
                aria-label="Mở menu điều hướng"
                class="lg:hidden inline-flex items-center justify-center w-10 h-10 rounded-lg border border-slate-200 text-brand-primary hover:bg-brand-light transition-colors shrink-0"
            >
                <i class="fa-solid fa-bars text-lg"></i>
            </button>
        </div>

        <!-- Menu Mobile Dạng Drawer Gọn Đẹp -->
        <div id="mobile-menu-panel" class="hidden lg:hidden bg-white border-t border-slate-200 shadow-lg">
            <div class="flatsome-container py-3 flex flex-col divide-y divide-slate-100 text-sm font-semibold text-slate-700">
                <a href="#trang-chu" onclick="closeMobileMenu()" class="py-2.5 hover:text-brand-primary">Trang chủ</a>
                <a href="#gioi-thieu" onclick="closeMobileMenu()" class="py-2.5 hover:text-brand-primary">Giới thiệu</a>
                <a href="#dich-vu" onclick="closeMobileMenu()" class="py-2.5 hover:text-brand-primary">Lĩnh vực hoạt động</a>
                <a href="#cong-trinh-thuc-te" onclick="closeMobileMenu()" class="py-2.5 hover:text-brand-primary">Công trình thực tế</a>
                <a href="#du-an-da-nang" onclick="closeMobileMenu()" class="py-2.5 hover:text-brand-primary">Dự án Đà Nẵng</a>
                <a href="#bao-gia" onclick="closeMobileMenu()" class="py-2.5 hover:text-brand-primary">Báo giá & Yêu cầu tư vấn</a>
                <a href="#doi-tac" onclick="closeMobileMenu()" class="py-2.5 hover:text-brand-primary">Đối tác tiêu biểu</a>
                <a href="#tin-tuc" onclick="closeMobileMenu()" class="py-2.5 hover:text-brand-primary">Tin tức & Kiến thức</a>
                <a href="#lien-he" onclick="closeMobileMenu()" class="py-2.5 hover:text-brand-primary">Liên hệ & Bản đồ</a>
            </div>
        </div>
    </header>

    <!-- =================================================================== -->
    <!-- 3. 2 ẢNH BANNER TỰ TRƯỢT CHUYÊN NGHIỆP KÍCH THƯỚC BẰNG NHAU         -->
    <!-- Chữ & nội dung nằm trọn bên trong, cách xa viền ảnh trên mọi thiết bị -->
    <!-- =================================================================== -->
    <section id="trang-chu" class="py-3 sm:py-4 bg-slate-50">
        <div class="flatsome-container">
            <div
                id="hero-slider"
                class="hero-slider-stage rounded-2xl shadow-md bg-brand-dark h-[340px] sm:h-[420px] md:h-[460px] lg:h-[510px]"
            >
                <!-- Slide 1 -->
                <div class="hero-slide active">
                    <img
                        src="https://lh3.googleusercontent.com/d/13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz"
                        data-gdrive-id="13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz"
                        alt="Thiết kế và thi công xây dựng trọn gói Đại Quang Hội Đà Nẵng"
                        class="w-full h-full object-cover object-center"
                        onerror="handleDriveImageError(this, false)"
                    >
                    <!-- Lớp phủ tối tương phản giúp chữ nổi bật hoàn hảo -->
                    <div class="absolute inset-0 bg-gradient-to-r from-[#072750]/90 via-[#0B3B75]/75 to-[#072750]/45"></div>
                    <!-- Nội dung căn trong vùng an toàn cách xa mọi viền ảnh -->
                    <div class="absolute inset-0 flex items-center">
                        <div class="w-full px-10 sm:px-16 md:px-20 lg:px-24 py-8 sm:py-12">
                            <div class="max-w-2xl text-white">
                                <p class="text-[11px] sm:text-xs md:text-sm font-semibold uppercase tracking-widest text-amber-300 mb-2">
                                    CÔNG TY TNHH XÂY DỰNG ĐẠI QUANG HỘI
                                </p>
                                <h1 class="text-xl sm:text-3xl md:text-4xl lg:text-[42px] font-extrabold leading-tight mb-3">
                                    THIẾT KẾ & THI CÔNG XÂY DỰNG TRỌN GÓI TẠI ĐÀ NẴNG
                                </h1>
                                <p class="text-xs sm:text-sm md:text-base text-slate-100 leading-relaxed mb-5 sm:mb-6">
                                    Chủ nhà trao cơ hội – Đại Quang Hội trao niềm tin. Miễn phí 100% thiết kế & giấy phép xây dựng khi ký hợp đồng thi công phần thô và trọn gói.
                                </p>
                                <div class="flex flex-wrap items-center gap-2.5 sm:gap-3">
                                    <a href="#form-bao-gia" class="inline-flex items-center gap-2 bg-brand-accent hover:bg-brand-accentHover text-white text-xs sm:text-sm font-bold px-4 sm:px-6 py-2.5 sm:py-3 rounded-xl shadow transition-colors">
                                        <span>Nhận báo giá miễn phí</span>
                                        <i class="fa-solid fa-arrow-right text-xs"></i>
                                    </a>
                                    <a href="#cong-trinh-thuc-te" class="inline-flex items-center gap-2 bg-white/15 hover:bg-white/25 backdrop-blur border border-white/30 text-white text-xs sm:text-sm font-semibold px-4 sm:px-5 py-2.5 sm:py-3 rounded-xl transition-colors">
                                        <span>Xem công trình</span>
                                    </a>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Slide 2 -->
                <div class="hero-slide">
                    <img
                        src="https://lh3.googleusercontent.com/d/157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT"
                        data-gdrive-id="157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT"
                        alt="Thi công căn hộ cho thuê, nhà phố, biệt thự tại Đà Nẵng"
                        class="w-full h-full object-cover object-center"
                        onerror="handleDriveImageError(this, false)"
                    >
                    <div class="absolute inset-0 bg-gradient-to-r from-[#072750]/92 via-[#0B3B75]/78 to-[#072750]/45"></div>
                    <!-- Nội dung căn trong vùng an toàn cách xa mọi viền ảnh -->
                    <div class="absolute inset-0 flex items-center">
                        <div class="w-full px-10 sm:px-16 md:px-20 lg:px-24 py-8 sm:py-12">
                            <div class="max-w-2xl text-white">
                                <p class="text-[11px] sm:text-xs md:text-sm font-semibold uppercase tracking-widest text-amber-300 mb-2">
                                    LÀM VIỆC BẰNG TÂM – XỨNG TẦM CHẤT LƯỢNG
                                </p>
                                <h2 class="text-xl sm:text-3xl md:text-4xl lg:text-[42px] font-extrabold leading-tight mb-3">
                                    CHUYÊN NHÀ PHỐ, BIỆT THỰ & CĂN HỘ CHO THUÊ
                                </h2>
                                <p class="text-xs sm:text-sm md:text-base text-slate-100 leading-relaxed mb-5 sm:mb-6">
                                    Đơn giá phần thô chỉ từ 3,3 triệu/m² – Chìa khóa trao tay từ 5,5 triệu/m². Kỹ sư giám sát 24/7, không phát sinh chi phí, bảo hành 5 năm & bảo trì trọn đời.
                                </p>
                                <div class="flex flex-wrap items-center gap-2.5 sm:gap-3">
                                    <a href="#bao-gia" class="inline-flex items-center gap-2 bg-brand-accent hover:bg-brand-accentHover text-white text-xs sm:text-sm font-bold px-4 sm:px-6 py-2.5 sm:py-3 rounded-xl shadow transition-colors">
                                        <span>Xem bảng giá 2026</span>
                                        <i class="fa-solid fa-file-invoice-dollar text-xs"></i>
                                    </a>
                                    <a href="#du-an-da-nang" class="inline-flex items-center gap-2 bg-white/15 hover:bg-white/25 backdrop-blur border border-white/30 text-white text-xs sm:text-sm font-semibold px-4 sm:px-5 py-2.5 sm:py-3 rounded-xl transition-colors">
                                        <span>Dự án tại Đà Nẵng</span>
                                    </a>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Nút chuyển Banner Trái / Phải đặt gọn sát mép không chạm chữ -->
                <button
                    type="button"
                    id="prev-slide"
                    aria-label="Banner trước"
                    class="absolute left-2 sm:left-4 top-1/2 -translate-y-1/2 z-10 w-8 h-8 sm:w-10 sm:h-10 rounded-full bg-black/35 hover:bg-brand-accent text-white flex items-center justify-center transition-colors"
                >
                    <i class="fa-solid fa-chevron-left text-xs sm:text-sm"></i>
                </button>
                <button
                    type="button"
                    id="next-slide"
                    aria-label="Banner tiếp theo"
                    class="absolute right-2 sm:right-4 top-1/2 -translate-y-1/2 z-10 w-8 h-8 sm:w-10 sm:h-10 rounded-full bg-black/35 hover:bg-brand-accent text-white flex items-center justify-center transition-colors"
                >
                    <i class="fa-solid fa-chevron-right text-xs sm:text-sm"></i>
                </button>

                <!-- Dấu chấm chỉ báo 2 banner -->
                <div class="absolute bottom-3 sm:bottom-4 left-1/2 -translate-x-1/2 z-10 flex items-center gap-2.5">
                    <button type="button" data-slide-dot="0" aria-label="Chọn banner 1" class="slide-dot w-7 h-2 rounded-full bg-brand-accent transition-all"></button>
                    <button type="button" data-slide-dot="1" aria-label="Chọn banner 2" class="slide-dot w-2.5 h-2 rounded-full bg-white/60 hover:bg-white transition-all"></button>
                </div>
            </div>
        </div>
    </section>

    <!-- =================================================================== -->
    <!-- 4. DỊCH VỤ TIÊU BIỂU (BỐ CỤC 3 CỘT CHUẨN WEB MẪU FLATSOME)          -->
    <!-- =================================================================== -->
    <section id="dich-vu" class="py-10 sm:py-14 bg-white">
        <div class="flatsome-container">
            <div class="text-center mb-8">
                <h2 class="section-title-bar text-xl sm:text-2xl lg:text-3xl font-extrabold text-brand-primary uppercase">
                    Dịch Vụ Tiêu Biểu
                </h2>
                <p class="text-xs sm:text-sm text-slate-500 mt-3 max-w-2xl mx-auto">
                    Giải pháp đồng bộ từ khâu tư vấn thiết kế, xin phép xây dựng đến thi công hoàn thiện và bàn giao chìa khóa trao tay tại Đà Nẵng.
                </p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-3 gap-4 sm:gap-6">
                <!-- Dịch vụ 1: Thiết kế -->
                <div class="group bg-white rounded-2xl overflow-hidden border border-slate-200 shadow-sm hover:shadow-lg transition-all flex flex-col">
                    <div class="aspect-[16/10] w-full overflow-hidden bg-slate-100">
                        <img
                            src="https://lh3.googleusercontent.com/d/1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff"
                            data-gdrive-id="1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff"
                            alt="Thiết kế kiến trúc nhà phố biệt thự căn hộ"
                            class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500"
                            onerror="handleDriveImageError(this, false)"
                        >
                    </div>
                    <div class="p-4 sm:p-5 text-center flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="text-base sm:text-lg font-extrabold text-brand-primary uppercase mb-2">THIẾT KẾ KIẾN TRÚC</h3>
                            <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">
                                Thiết kế kiến trúc nhà phố, biệt thự, khách sạn, căn hộ cho thuê tối ưu công năng, chuẩn phong thủy và tiết kiệm chi phí đầu tư.
                            </p>
                        </div>
                        <a href="#form-bao-gia" class="inline-flex items-center justify-center gap-1.5 mt-4 text-xs sm:text-sm font-bold text-brand-accent hover:text-brand-primary transition-colors">
                            <span>Tư vấn thiết kế</span>
                            <i class="fa-solid fa-angle-right"></i>
                        </a>
                    </div>
                </div>

                <!-- Dịch vụ 2: Thi công -->
                <div class="group bg-white rounded-2xl overflow-hidden border border-slate-200 shadow-sm hover:shadow-lg transition-all flex flex-col">
                    <div class="aspect-[16/10] w-full overflow-hidden bg-slate-100">
                        <img
                            src="https://lh3.googleusercontent.com/d/1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR"
                            data-gdrive-id="1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR"
                            alt="Thi công phần thô và trọn gói chìa khóa trao tay"
                            class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500"
                            onerror="handleDriveImageError(this, false)"
                        >
                    </div>
                    <div class="p-4 sm:p-5 text-center flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="text-base sm:text-lg font-extrabold text-brand-primary uppercase mb-2">THI CÔNG XÂY DỰNG</h3>
                            <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">
                                Thi công phần thô, hoàn thiện và xây nhà trọn gói chìa khóa trao tay. Kỹ sư túc trực giám sát 24/7, vật tư minh bạch, đúng tiến độ.
                            </p>
                        </div>
                        <a href="#bao-gia" class="inline-flex items-center justify-center gap-1.5 mt-4 text-xs sm:text-sm font-bold text-brand-accent hover:text-brand-primary transition-colors">
                            <span>Xem đơn giá thi công</span>
                            <i class="fa-solid fa-angle-right"></i>
                        </a>
                    </div>
                </div>

                <!-- Dịch vụ 3: Nội thất & Cải tạo -->
                <div class="group bg-white rounded-2xl overflow-hidden border border-slate-200 shadow-sm hover:shadow-lg transition-all flex flex-col">
                    <div class="aspect-[16/10] w-full overflow-hidden bg-slate-100">
                        <img
                            src="https://lh3.googleusercontent.com/d/1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv"
                            data-gdrive-id="1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv"
                            alt="Thiết kế thi công nội thất và cải tạo sửa chữa"
                            class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500"
                            onerror="handleDriveImageError(this, false)"
                        >
                    </div>
                    <div class="p-4 sm:p-5 text-center flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="text-base sm:text-lg font-extrabold text-brand-primary uppercase mb-2">NỘI THẤT & CẢI TẠO</h3>
                            <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">
                                Thiết kế, thi công nội thất văn phòng, nhà ở, khách sạn, showroom và dịch vụ sửa chữa, nâng tầng, cải tạo công trình chuyên nghiệp.
                            </p>
                        </div>
                        <a href="#form-bao-gia" class="inline-flex items-center justify-center gap-1.5 mt-4 text-xs sm:text-sm font-bold text-brand-accent hover:text-brand-primary transition-colors">
                            <span>Yêu cầu khảo sát</span>
                            <i class="fa-solid fa-angle-right"></i>
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- =================================================================== -->
    <!-- 5. GIỚI THIỆU CÔNG TY TNHH XÂY DỰNG ĐẠI QUANG HỘI                   -->
    <!-- =================================================================== -->
    <section id="gioi-thieu" class="py-10 sm:py-14 bg-slate-50 border-y border-slate-200/70">
        <div class="flatsome-container">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 lg:gap-10 items-center">
                <div class="lg:col-span-7 space-y-4">
                    <h2 class="section-title-bar-left text-xl sm:text-2xl lg:text-3xl font-extrabold text-brand-primary uppercase">
                        CÔNG TY TNHH XÂY DỰNG ĐẠI QUANG HỘI
                    </h2>
                    <p class="text-sm sm:text-base text-slate-700 leading-relaxed">
                        <strong>CÔNG TY TNHH XÂY DỰNG ĐẠI QUANG HỘI</strong> là nhà thầu uy tín với gần <strong>10 năm kinh nghiệm</strong> trong lĩnh vực thiết kế kiến trúc, thi công phần thô, thi công hoàn thiện và xây dựng trọn gói các công trình nhà phố, biệt thự, căn hộ cho thuê, khách sạn, văn phòng, trường học và cải tạo sửa chữa tại Đà Nẵng cùng khu vực miền Trung.
                    </p>
                    <p class="text-sm sm:text-base text-slate-700 leading-relaxed">
                        Với phương châm <strong>“Làm việc bằng tâm – Xứng tầm chất lượng”</strong>, chúng tôi cam kết xây dựng tổ ấm bền vững phù hợp tài chính gia chủ, minh bạch từng hạng mục vật tư, không phát sinh chi phí và đảm bảo tiêu chuẩn <strong>An toàn – Chất lượng – Thẩm mỹ – Đúng tiến độ</strong>.
                    </p>

                    <!-- Thông số nổi bật dạng Flatsome Row đơn giản -->
                    <div class="grid grid-cols-2 sm:grid-cols-4 gap-3 pt-2">
                        <div class="bg-white rounded-xl p-3.5 border border-slate-200 text-center">
                            <div class="text-xl sm:text-2xl font-extrabold text-brand-primary">10+</div>
                            <div class="text-[11px] sm:text-xs text-slate-600 font-medium mt-0.5">Năm kinh nghiệm</div>
                        </div>
                        <div class="bg-white rounded-xl p-3.5 border border-slate-200 text-center">
                            <div class="text-xl sm:text-2xl font-extrabold text-brand-accent">100%</div>
                            <div class="text-[11px] sm:text-xs text-slate-600 font-medium mt-0.5">Miễn phí thiết kế</div>
                        </div>
                        <div class="bg-white rounded-xl p-3.5 border border-slate-200 text-center">
                            <div class="text-xl sm:text-2xl font-extrabold text-brand-primary">24/7</div>
                            <div class="text-[11px] sm:text-xs text-slate-600 font-medium mt-0.5">Kỹ sư giám sát</div>
                        </div>
                        <div class="bg-white rounded-xl p-3.5 border border-slate-200 text-center">
                            <div class="text-xl sm:text-2xl font-extrabold text-brand-accent">5 Năm</div>
                            <div class="text-[11px] sm:text-xs text-slate-600 font-medium mt-0.5">Bảo hành & Bảo trì</div>
                        </div>
                    </div>
                </div>

                <div class="lg:col-span-5">
                    <div class="rounded-2xl overflow-hidden shadow-md border border-slate-200 bg-white">
                        <img
                            src="https://lh3.googleusercontent.com/d/1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_"
                            data-gdrive-id="1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_"
                            alt="Đội ngũ thi công thực tế Công Ty TNHH Xây Dựng Đại Quang Hội"
                            class="w-full h-64 sm:h-80 object-cover"
                            onerror="handleDriveImageError(this, false)"
                        >
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- =================================================================== -->
    <!-- 6. THẾ MẠNH CỦA CHÚNG TÔI (6 HỘP ICON GIỐNG WEB MẪU)                -->
    <!-- =================================================================== -->
    <section class="py-10 sm:py-14 bg-white">
        <div class="flatsome-container">
            <div class="text-center mb-8">
                <h2 class="section-title-bar text-xl sm:text-2xl lg:text-3xl font-extrabold text-brand-primary uppercase">
                    Thế Mạnh Của Chúng Tôi
                </h2>
            </div>

            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-4 sm:gap-5">
                <div class="p-5 rounded-2xl border border-slate-200 bg-slate-50/70 hover:bg-white hover:shadow-md transition-all flex gap-4 items-start">
                    <div class="w-11 h-11 rounded-xl bg-brand-primary text-white flex items-center justify-center shrink-0">
                        <i class="fa-solid fa-helmet-safety text-lg"></i>
                    </div>
                    <div>
                        <h3 class="text-sm sm:text-base font-bold text-brand-primary mb-1">Kiến trúc sư & kỹ sư lành nghề</h3>
                        <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">Đội ngũ kiến trúc sư sáng tạo cùng kỹ sư kết cấu giàu kinh nghiệm và thợ thi công chuyên môn cao.</p>
                    </div>
                </div>

                <div class="p-5 rounded-2xl border border-slate-200 bg-slate-50/70 hover:bg-white hover:shadow-md transition-all flex gap-4 items-start">
                    <div class="w-11 h-11 rounded-xl bg-brand-accent text-white flex items-center justify-center shrink-0">
                        <i class="fa-solid fa-compass-drafting text-lg"></i>
                    </div>
                    <div>
                        <h3 class="text-sm sm:text-base font-bold text-brand-primary mb-1">Miễn phí 100% thiết kế & GPXD</h3>
                        <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">Hỗ trợ trọn gói hồ sơ thiết kế kiến trúc, kết cấu và thủ tục xin giấy phép xây dựng khi ký hợp đồng thi công.</p>
                    </div>
                </div>

                <div class="p-5 rounded-2xl border border-slate-200 bg-slate-50/70 hover:bg-white hover:shadow-md transition-all flex gap-4 items-start">
                    <div class="w-11 h-11 rounded-xl bg-brand-primary text-white flex items-center justify-center shrink-0">
                        <i class="fa-solid fa-clipboard-check text-lg"></i>
                    </div>
                    <div>
                        <h3 class="text-sm sm:text-base font-bold text-brand-primary mb-1">Giám sát tiến độ chuẩn xác 24/7</h3>
                        <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">Kỹ sư túc trực tại công trình, cập nhật hình ảnh tiến độ hằng ngày giúp chủ nhà an tâm theo dõi từ xa.</p>
                    </div>
                </div>

                <div class="p-5 rounded-2xl border border-slate-200 bg-slate-50/70 hover:bg-white hover:shadow-md transition-all flex gap-4 items-start">
                    <div class="w-11 h-11 rounded-xl bg-brand-accent text-white flex items-center justify-center shrink-0">
                        <i class="fa-solid fa-shield-halved text-lg"></i>
                    </div>
                    <div>
                        <h3 class="text-sm sm:text-base font-bold text-brand-primary mb-1">Bảo hành 5 năm – Bảo trì trọn đời</h3>
                        <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">Thường xuyên kiểm tra bảo hành sau bàn giao, hỗ trợ nhanh chóng với tinh thần trách nhiệm cao nhất.</p>
                    </div>
                </div>

                <div class="p-5 rounded-2xl border border-slate-200 bg-slate-50/70 hover:bg-white hover:shadow-md transition-all flex gap-4 items-start">
                    <div class="w-11 h-11 rounded-xl bg-brand-primary text-white flex items-center justify-center shrink-0">
                        <i class="fa-solid fa-hand-holding-dollar text-lg"></i>
                    </div>
                    <div>
                        <h3 class="text-sm sm:text-base font-bold text-brand-primary mb-1">Giá cả minh bạch – Không phát sinh</h3>
                        <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">Dự toán chi tiết ngay từ đầu, cân đối chi phí hợp lý theo ngân sách gia chủ và đúng chủng loại vật tư.</p>
                    </div>
                </div>

                <div class="p-5 rounded-2xl border border-slate-200 bg-slate-50/70 hover:bg-white hover:shadow-md transition-all flex gap-4 items-start">
                    <div class="w-11 h-11 rounded-xl bg-brand-accent text-white flex items-center justify-center shrink-0">
                        <i class="fa-solid fa-headset text-lg"></i>
                    </div>
                    <div>
                        <h3 class="text-sm sm:text-base font-bold text-brand-primary mb-1">Hỗ trợ tư vấn miễn phí 24/7</h3>
                        <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">Sẵn sàng khảo sát thực tế mặt bằng, lên phương án sơ bộ và tư vấn giải pháp tối ưu cho mọi công trình.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- =================================================================== -->
    <!-- 7. DANH MỤC SẢN PHẨM & CÔNG TRÌNH THỰC TẾ (9 ẢNH THỰC TẾ TỪ DRIVE)  -->
    <!-- Danh mục nhỏ gọn, không xuống dòng tên danh mục, 2 cột trên điện thoại, KHÔNG nhãn dán -->
    <!-- =================================================================== -->
    <section id="cong-trinh-thuc-te" class="py-10 sm:py-14 bg-slate-50 border-t border-slate-200/70">
        <div class="flatsome-container">
            <div class="text-center mb-6">
                <h2 class="section-title-bar text-xl sm:text-2xl lg:text-3xl font-extrabold text-brand-primary uppercase">
                    Công Trình Thực Tế & Hạng Mục Thi Công
                </h2>
                <p class="text-xs sm:text-sm text-slate-500 mt-3 max-w-2xl mx-auto">
                    Hình ảnh thực tế các công trình do Công Ty TNHH Xây Dựng Đại Quang Hội trực tiếp thiết kế và thi công.
                </p>
            </div>

            <!-- Thanh Danh Mục Sản Phẩm: Chữ nhỏ gọn, viết liền không ngắt dòng trong từng tên danh mục, tối ưu đẹp cho máy tính & điện thoại -->
            <div class="flex flex-wrap items-center justify-center gap-1.5 sm:gap-2 mb-7">
                <button type="button" data-cat="all" class="cat-tab whitespace-nowrap px-3 py-1.5 rounded-lg text-[11px] sm:text-xs font-semibold transition-all bg-brand-primary text-white shadow-sm">
                    Tất cả
                </button>
                <button type="button" data-cat="can-ho" class="cat-tab whitespace-nowrap px-3 py-1.5 rounded-lg text-[11px] sm:text-xs font-semibold transition-all bg-white text-slate-700 border border-slate-200 hover:border-brand-primary hover:text-brand-primary">
                    Khách sạn - Căn hộ - Phòng trọ
                </button>
                <button type="button" data-cat="biet-thu" class="cat-tab whitespace-nowrap px-3 py-1.5 rounded-lg text-[11px] sm:text-xs font-semibold transition-all bg-white text-slate-700 border border-slate-200 hover:border-brand-primary hover:text-brand-primary">
                    Biệt thự
                </button>
                <button type="button" data-cat="nha-pho" class="cat-tab whitespace-nowrap px-3 py-1.5 rounded-lg text-[11px] sm:text-xs font-semibold transition-all bg-white text-slate-700 border border-slate-200 hover:border-brand-primary hover:text-brand-primary">
                    Nhà phố
                </button>
                <button type="button" data-cat="phan-tho" class="cat-tab whitespace-nowrap px-3 py-1.5 rounded-lg text-[11px] sm:text-xs font-semibold transition-all bg-white text-slate-700 border border-slate-200 hover:border-brand-primary hover:text-brand-primary">
                    Thi công phần thô
                </button>
                <button type="button" data-cat="hoan-thien" class="cat-tab whitespace-nowrap px-3 py-1.5 rounded-lg text-[11px] sm:text-xs font-semibold transition-all bg-white text-slate-700 border border-slate-200 hover:border-brand-primary hover:text-brand-primary">
                    Thi công hoàn thiện
                </button>
                <button type="button" data-cat="van-phong" class="cat-tab whitespace-nowrap px-3 py-1.5 rounded-lg text-[11px] sm:text-xs font-semibold transition-all bg-white text-slate-700 border border-slate-200 hover:border-brand-primary hover:text-brand-primary">
                    Văn phòng - Nội thất
                </button>
            </div>

            <!-- Lưới sản phẩm / công trình thực tế: 2 cột trên điện thoại, 3-4 cột trên máy tính -->
            <div id="construction-grid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-3 sm:gap-5">
                <!-- Render bằng JavaScript để lọc danh mục tức thì, sạch đẹp, không nhãn dán -->
            </div>
        </div>
    </section>

    <!-- =================================================================== -->
    <!-- 8. DANH MỤC CÁC DỰ ÁN Ở ĐÀ NẴNG (10 ẢNH DỰ ÁN TỪ GOOGLE DRIVE)      -->
    <!-- =================================================================== -->
    <section id="du-an-da-nang" class="py-10 sm:py-14 bg-white border-t border-slate-200/70">
        <div class="flatsome-container">
            <div class="text-center mb-8">
                <h2 class="section-title-bar text-xl sm:text-2xl lg:text-3xl font-extrabold text-brand-primary uppercase">
                    Các Dự Án Tiêu Biểu Tại Đà Nẵng
                </h2>
                <p class="text-xs sm:text-sm text-slate-500 mt-3 max-w-2xl mx-auto">
                    Tổng hợp các công trình nhà phố, căn hộ cho thuê, biệt thự và khách sạn thực tế đã và đang triển khai khắp các quận Liên Chiểu, Hải Châu, Sơn Trà, Cẩm Lệ, Ngũ Hành Sơn.
                </p>
            </div>

            <!-- 2 cột trên điện thoại, 5 cột trên máy tính (2 hàng x 5 dự án = 10 dự án cân đối) -->
            <div id="danang-projects-grid" class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-5 gap-3 sm:gap-4">
                <!-- Render tự động 10 dự án Đà Nẵng -->
            </div>
        </div>
    </section>

    <!-- =================================================================== -->
    <!-- 9. BẢNG BÁO GIÁ THAM KHẢO (DỮ LIỆU CHÍNH THỨC TỪ FANPAGE ĐQH)       -->
    <!-- =================================================================== -->
    <section id="bao-gia" class="py-10 sm:py-14 bg-slate-50 border-t border-slate-200/70">
        <div class="flatsome-container">
            <div class="text-center mb-8">
                <h2 class="section-title-bar text-xl sm:text-2xl lg:text-3xl font-extrabold text-brand-primary uppercase">
                    Bảng Báo Giá Xây Dựng Tại Đà Nẵng
                </h2>
                <p class="text-xs sm:text-sm text-slate-500 mt-3 max-w-2xl mx-auto">
                    Đơn giá minh bạch, cạnh tranh nhất khu vực Đà Nẵng. Liên hệ trực tiếp để nhận bảng dự toán chi tiết theo diện tích đất thực tế.
                </p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-3 gap-4 sm:gap-6">
                <!-- Gói 1: Nhân công -->
                <div class="bg-white rounded-2xl border border-slate-200 p-5 sm:p-6 shadow-sm flex flex-col justify-between">
                    <div>
                        <h3 class="text-base sm:text-lg font-extrabold text-brand-primary uppercase">Gói Thi Công Nhân Công</h3>
                        <p class="text-xs text-slate-500 mt-1">Phù hợp chủ đầu tư đã chủ động nguồn vật tư</p>
                        <div class="my-4 py-3 border-y border-slate-100">
                            <span class="text-xs text-slate-500">Chỉ từ</span>
                            <div class="text-2xl sm:text-3xl font-extrabold text-brand-accent">1,4 triệu / m²</div>
                        </div>
                        <ul class="space-y-2 text-xs sm:text-sm text-slate-700">
                            <li class="flex items-start gap-2"><i class="fa-solid fa-check text-brand-primary mt-1 text-xs"></i><span>Đội thợ tay nghề cao, thi công đúng bản vẽ kỹ thuật</span></li>
                            <li class="flex items-start gap-2"><i class="fa-solid fa-check text-brand-primary mt-1 text-xs"></i><span>Kỹ sư hướng dẫn, giám sát chất lượng hằng ngày</span></li>
                            <li class="flex items-start gap-2"><i class="fa-solid fa-check text-brand-primary mt-1 text-xs"></i><span>Đảm bảo an toàn lao động & tiến độ cam kết</span></li>
                        </ul>
                    </div>
                    <a href="#form-bao-gia" onclick="prefillQuoteType('Thi công nhân công')" class="mt-6 block w-full text-center bg-brand-light hover:bg-brand-primary text-brand-primary hover:text-white font-bold text-xs sm:text-sm py-3 rounded-xl transition-colors">
                        Nhận báo giá gói này
                    </a>
                </div>

                <!-- Gói 2: Phần thô -->
                <div class="bg-brand-primary text-white rounded-2xl border-2 border-brand-primary p-5 sm:p-6 shadow-lg flex flex-col justify-between">
                    <div>
                        <h3 class="text-base sm:text-lg font-extrabold uppercase text-amber-300">Gói Xây Dựng Phần Thô</h3>
                        <p class="text-xs text-slate-200 mt-1">Vật tư thô chính hãng + Nhân công hoàn thiện</p>
                        <div class="my-4 py-3 border-y border-white/15">
                            <span class="text-xs text-slate-200">Chỉ từ</span>
                            <div class="text-2xl sm:text-3xl font-extrabold text-white">3,3 – 3,6 triệu / m²</div>
                        </div>
                        <ul class="space-y-2 text-xs sm:text-sm text-slate-100">
                            <li class="flex items-start gap-2"><i class="fa-solid fa-check text-amber-300 mt-1 text-xs"></i><span>Miễn phí 100% thiết kế & xin giấy phép xây dựng</span></li>
                            <li class="flex items-start gap-2"><i class="fa-solid fa-check text-amber-300 mt-1 text-xs"></i><span>Vật tư thô chuẩn: Thép Hòa Phát, Xi măng Sông Gianh, Cadivi</span></li>
                            <li class="flex items-start gap-2"><i class="fa-solid fa-check text-amber-300 mt-1 text-xs"></i><span>Bảo hành kết cấu 5 năm, bảo trì trọn đời</span></li>
                        </ul>
                    </div>
                    <a href="#form-bao-gia" onclick="prefillQuoteType('Thi công phần thô')" class="mt-6 block w-full text-center bg-brand-accent hover:bg-brand-accentHover text-white font-bold text-xs sm:text-sm py-3 rounded-xl shadow transition-colors">
                        Đăng ký tư vấn ngay
                    </a>
                </div>

                <!-- Gói 3: Trọn gói chìa khóa trao tay -->
                <div class="bg-white rounded-2xl border border-slate-200 p-5 sm:p-6 shadow-sm flex flex-col justify-between">
                    <div>
                        <h3 class="text-base sm:text-lg font-extrabold text-brand-primary uppercase">Chìa Khóa Trao Tay</h3>
                        <p class="text-xs text-slate-500 mt-1">Trọn gói từ thiết kế, phần thô đến hoàn thiện</p>
                        <div class="my-4 py-3 border-y border-slate-100">
                            <span class="text-xs text-slate-500">Chỉ từ</span>
                            <div class="text-2xl sm:text-3xl font-extrabold text-brand-accent">5,5 – 5,8 triệu / m²</div>
                        </div>
                        <ul class="space-y-2 text-xs sm:text-sm text-slate-700">
                            <li class="flex items-start gap-2"><i class="fa-solid fa-check text-brand-primary mt-1 text-xs"></i><span>Miễn phí 100% hồ sơ thiết kế & thủ tục pháp lý</span></li>
                            <li class="flex items-start gap-2"><i class="fa-solid fa-check text-brand-primary mt-1 text-xs"></i><span>Cam kết không phát sinh chi phí, tối ưu công năng</span></li>
                            <li class="flex items-start gap-2"><i class="fa-solid fa-check text-brand-primary mt-1 text-xs"></i><span>Bàn giao hoàn thiện dọn vào ở hoặc khai thác ngay</span></li>
                        </ul>
                    </div>
                    <a href="#form-bao-gia" onclick="prefillQuoteType('Thi công trọn gói chìa khóa trao tay')" class="mt-6 block w-full text-center bg-brand-light hover:bg-brand-primary text-brand-primary hover:text-white font-bold text-xs sm:text-sm py-3 rounded-xl transition-colors">
                        Nhận báo giá trọn gói
                    </a>
                </div>
            </div>
        </div>
    </section>

    <!-- =================================================================== -->
    <!-- 10. FORM YÊU CẦU TƯ VẤN & BÁO GIÁ TRANG CHỦ (MẪU TÍN TRƯỜNG THỊNH)  -->
    <!-- =================================================================== -->
    <section id="form-bao-gia" class="py-10 sm:py-14 bg-brand-dark text-white">
        <div class="flatsome-container">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 lg:gap-10 items-center">
                <div class="lg:col-span-5 space-y-4">
                    <p class="text-xs font-bold uppercase tracking-widest text-amber-300">MIỄN PHÍ TƯ VẤN & KHẢO SÁT</p>
                    <h2 class="text-2xl sm:text-3xl font-extrabold leading-tight">
                        YÊU CẦU TƯ VẤN & NHẬN BÁO GIÁ CHI TIẾT
                    </h2>
                    <p class="text-xs sm:text-sm text-slate-200 leading-relaxed">
                        Để lại thông tin công trình dự kiến của quý khách, kỹ sư của <strong>Công Ty TNHH Xây Dựng Đại Quang Hội</strong> sẽ liên hệ tư vấn phương án thiết kế và gửi bảng dự toán chi phí hoàn toàn miễn phí trong vòng 30 phút.
                    </p>
                    <div class="space-y-2.5 pt-2 text-xs sm:text-sm">
                        <div class="flex items-center gap-3">
                            <span class="w-8 h-8 rounded-lg bg-white/10 flex items-center justify-center text-amber-300 shrink-0"><i class="fa-solid fa-phone"></i></span>
                            <span>Hotline / Zalo: <strong class="text-white">0932.103.549</strong></span>
                        </div>
                        <div class="flex items-center gap-3">
                            <span class="w-8 h-8 rounded-lg bg-white/10 flex items-center justify-center text-amber-300 shrink-0"><i class="fa-solid fa-envelope"></i></span>
                            <span>Email: <strong class="text-white">daiquanghoi@gmail.com</strong></span>
                        </div>
                        <div class="flex items-center gap-3">
                            <span class="w-8 h-8 rounded-lg bg-white/10 flex items-center justify-center text-amber-300 shrink-0"><i class="fa-solid fa-location-dot"></i></span>
                            <span>186/54 Phạm Như Xương, Phường Liên Chiểu, TP Đà Nẵng</span>
                        </div>
                    </div>
                </div>

                <div class="lg:col-span-7">
                    <form id="quote-form" class="bg-white text-slate-800 rounded-2xl p-5 sm:p-7 shadow-xl space-y-4">
                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                            <div>
                                <label for="q-name" class="block text-xs font-bold text-slate-700 mb-1.5">Họ và tên <span class="text-red-500">*</span></label>
                                <input id="q-name" type="text" required placeholder="Nhập họ tên của bạn" class="w-full px-3.5 py-2.5 text-sm rounded-xl border border-slate-300 focus:outline-none focus:border-brand-primary focus:ring-2 focus:ring-brand-primary/15">
                            </div>
                            <div>
                                <label for="q-phone" class="block text-xs font-bold text-slate-700 mb-1.5">Số điện thoại <span class="text-red-500">*</span></label>
                                <input id="q-phone" type="tel" required placeholder="VD: 0932 103 549" class="w-full px-3.5 py-2.5 text-sm rounded-xl border border-slate-300 focus:outline-none focus:border-brand-primary focus:ring-2 focus:ring-brand-primary/15">
                            </div>
                        </div>

                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                            <div>
                                <label for="q-type" class="block text-xs font-bold text-slate-700 mb-1.5">Loại công trình</label>
                                <select id="q-type" class="w-full px-3.5 py-2.5 text-sm rounded-xl border border-slate-300 bg-white focus:outline-none focus:border-brand-primary focus:ring-2 focus:ring-brand-primary/15">
                                    <option value="Nhà phố">Nhà phố</option>
                                    <option value="Khách sạn – Căn hộ cho thuê – Phòng trọ">Khách sạn – Căn hộ cho thuê – Phòng trọ</option>
                                    <option value="Biệt thự">Biệt thự</option>
                                    <option value="Văn phòng – Showroom">Văn phòng – Showroom</option>
                                    <option value="Thi công phần thô">Thi công phần thô</option>
                                    <option value="Thi công trọn gói chìa khóa trao tay">Thi công trọn gói chìa khóa trao tay</option>
                                    <option value="Thi công nhân công">Thi công nhân công</option>
                                    <option value="Cải tạo sửa chữa">Cải tạo sửa chữa</option>
                                </select>
                            </div>
                            <div>
                                <label for="q-budget" class="block text-xs font-bold text-slate-700 mb-1.5">Mức đầu tư dự kiến</label>
                                <select id="q-budget" class="w-full px-3.5 py-2.5 text-sm rounded-xl border border-slate-300 bg-white focus:outline-none focus:border-brand-primary focus:ring-2 focus:ring-brand-primary/15">
                                    <option value="Chưa xác định">Chưa xác định</option>
                                    <option value="Dưới 500 triệu">Dưới 500 triệu</option>
                                    <option value="500 triệu - 1 tỷ">500 triệu – 1 tỷ</option>
                                    <option value="1 tỷ - 2 tỷ">1 tỷ – 2 tỷ</option>
                                    <option value="2 tỷ - 3 tỷ">2 tỷ – 3 tỷ</option>
                                    <option value="Trên 3 tỷ">Trên 3 tỷ</option>
                                </select>
                            </div>
                        </div>

                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                            <div>
                                <label for="q-email" class="block text-xs font-bold text-slate-700 mb-1.5">Email (nếu có)</label>
                                <input id="q-email" type="email" placeholder="example@gmail.com" class="w-full px-3.5 py-2.5 text-sm rounded-xl border border-slate-300 focus:outline-none focus:border-brand-primary focus:ring-2 focus:ring-brand-primary/15">
                            </div>
                            <div>
                                <label for="q-area" class="block text-xs font-bold text-slate-700 mb-1.5">Diện tích & số tầng dự kiến</label>
                                <input id="q-area" type="text" placeholder="VD: 5x20m, 3 tầng tại Liên Chiểu" class="w-full px-3.5 py-2.5 text-sm rounded-xl border border-slate-300 focus:outline-none focus:border-brand-primary focus:ring-2 focus:ring-brand-primary/15">
                            </div>
                        </div>

                        <div>
                            <label for="q-note" class="block text-xs font-bold text-slate-700 mb-1.5">Yêu cầu chi tiết</label>
                            <textarea id="q-note" rows="3" placeholder="Mô tả nhu cầu thiết kế, thi công hoặc thời gian dự kiến khởi công..." class="w-full px-3.5 py-2.5 text-sm rounded-xl border border-slate-300 focus:outline-none focus:border-brand-primary focus:ring-2 focus:ring-brand-primary/15"></textarea>
                        </div>

                        <button type="submit" class="w-full bg-brand-accent hover:bg-brand-accentHover text-white font-bold text-sm py-3.5 rounded-xl shadow-md transition-colors flex items-center justify-center gap-2">
                            <i class="fa-solid fa-paper-plane"></i>
                            <span>GỬI YÊU CẦU BÁO GIÁ MIỄN PHÍ</span>
                        </button>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- =================================================================== -->
    <!-- 11. DANH MỤC CÁC ĐỐI TÁC & NHÀ CUNG CẤP VẬT TƯ                      -->
    <!-- =================================================================== -->
    <section id="doi-tac" class="py-10 sm:py-14 bg-white">
        <div class="flatsome-container">
            <div class="text-center mb-8">
                <h2 class="section-title-bar text-xl sm:text-2xl lg:text-3xl font-extrabold text-brand-primary uppercase">
                    Đối Tác & Nhà Cung Cấp Vật Tư
                </h2>
                <p class="text-xs sm:text-sm text-slate-500 mt-3 max-w-2xl mx-auto">
                    Đại Quang Hội hợp tác trực tiếp cùng các thương hiệu vật liệu xây dựng hàng đầu để đảm bảo chất lượng bền vững và tối ưu chi phí cho chủ đầu tư.
                </p>
            </div>

            <div class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-4 lg:grid-cols-6 gap-3 sm:gap-4">
                <div class="rounded-xl border border-slate-200 bg-slate-50 hover:bg-white hover:shadow-md transition-all p-4 flex flex-col items-center justify-center text-center min-h-[88px]">
                    <span class="text-sm sm:text-base font-extrabold text-[#0054A6] tracking-tight">HÒA PHÁT</span>
                    <span class="text-[10px] text-slate-500 mt-0.5">Thép xây dựng</span>
                </div>
                <div class="rounded-xl border border-slate-200 bg-slate-50 hover:bg-white hover:shadow-md transition-all p-4 flex flex-col items-center justify-center text-center min-h-[88px]">
                    <span class="text-sm sm:text-base font-extrabold text-[#C8102E] tracking-tight">SÔNG GIANH</span>
                    <span class="text-[10px] text-slate-500 mt-0.5">Xi măng cao cấp</span>
                </div>
                <div class="rounded-xl border border-slate-200 bg-slate-50 hover:bg-white hover:shadow-md transition-all p-4 flex flex-col items-center justify-center text-center min-h-[88px]">
                    <span class="text-sm sm:text-base font-extrabold text-[#003399] tracking-tight">DULUX</span>
                    <span class="text-[10px] text-slate-500 mt-0.5">Sơn nội ngoại thất</span>
                </div>
                <div class="rounded-xl border border-slate-200 bg-slate-50 hover:bg-white hover:shadow-md transition-all p-4 flex flex-col items-center justify-center text-center min-h-[88px]">
                    <span class="text-sm sm:text-base font-extrabold text-[#D97706] tracking-tight">CADIVI</span>
                    <span class="text-[10px] text-slate-500 mt-0.5">Dây cáp điện</span>
                </div>
                <div class="rounded-xl border border-slate-200 bg-slate-50 hover:bg-white hover:shadow-md transition-all p-4 flex flex-col items-center justify-center text-center min-h-[88px]">
                    <span class="text-sm sm:text-base font-extrabold text-[#006837] tracking-tight">BÌNH MINH</span>
                    <span class="text-[10px] text-slate-500 mt-0.5">Ống nhựa cấp thoát nước</span>
                </div>
                <div class="rounded-xl border border-slate-200 bg-slate-50 hover:bg-white hover:shadow-md transition-all p-4 flex flex-col items-center justify-center text-center min-h-[88px]">
                    <span class="text-sm sm:text-base font-extrabold text-[#1E3A8A] tracking-tight">CÁ SẤU THÁI LAN</span>
                    <span class="text-[10px] text-slate-500 mt-0.5">Keo dán gạch & chống thấm</span>
                </div>
            </div>
        </div>
    </section>

    <!-- =================================================================== -->
    <!-- 12. DANH MỤC CÁC BÀI VIẾT TRANG CHỦ (TIN TỨC & KINH NGHIỆM XÂY NHÀ) -->
    <!-- =================================================================== -->
    <section id="tin-tuc" class="py-10 sm:py-14 bg-slate-50 border-t border-slate-200/70">
        <div class="flatsome-container">
            <div class="text-center mb-8">
                <h2 class="section-title-bar text-xl sm:text-2xl lg:text-3xl font-extrabold text-brand-primary uppercase">
                    Bài Viết & Kinh Nghiệm Xây Dựng
                </h2>
                <p class="text-xs sm:text-sm text-slate-500 mt-3 max-w-2xl mx-auto">
                    Chia sẻ kiến thức kỹ thuật thi công, kinh nghiệm dự toán chi phí và xu hướng thiết kế nhà đẹp tại Đà Nẵng.
                </p>
            </div>

            <!-- 2 cột trên điện thoại, 4 cột trên máy tính -->
            <div id="articles-grid" class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">
                <!-- Render bài viết từ dữ liệu JS -->
            </div>
        </div>
    </section>

    <!-- =================================================================== -->
    <!-- 13. FANPAGE FACEBOOK & BẢN ĐỒ GOOGLE MAP RA NGOÀI TRANG CHỦ         -->
    <!-- =================================================================== -->
    <section id="lien-he" class="py-10 sm:py-14 bg-white border-t border-slate-200/70">
        <div class="flatsome-container">
            <div class="text-center mb-8">
                <h2 class="section-title-bar text-xl sm:text-2xl lg:text-3xl font-extrabold text-brand-primary uppercase">
                    Kết Nối Fanpage & Bản Đồ Chỉ Đường
                </h2>
                <p class="text-xs sm:text-sm text-slate-500 mt-3">
                    Trụ sở: 186/54 Phạm Như Xương, Phường Liên Chiểu, TP Đà Nẵng — Hotline: 0932.103.549
                </p>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-stretch">
                <!-- Cột Trái: Google Map trực tiếp -->
                <div class="lg:col-span-7 bg-slate-50 rounded-2xl border border-slate-200 overflow-hidden flex flex-col shadow-sm">
                    <div class="px-4 sm:px-5 py-3.5 bg-white border-b border-slate-200 flex flex-wrap items-center justify-between gap-2">
                        <div class="flex items-center gap-2 text-brand-primary font-bold text-sm">
                            <i class="fa-solid fa-map-location-dot text-brand-accent"></i>
                            <span>Bản đồ Google Maps – Công Ty TNHH Xây Dựng Đại Quang Hội</span>
                        </div>
                        <a
                            href="https://www.google.com/maps/search/?api=1&query=186%2F54+Ph%E1%BA%A1m+Nh%C6%B0+X%C6%B0%C6%A1ng,+Li%C3%AAn+Chi%E1%BB%83u,+%C4%90%C3%A0+N%E1%BA%B5ng"
                            target="_blank"
                            rel="noopener noreferrer"
                            class="text-xs font-semibold text-brand-accent hover:text-brand-primary transition-colors"
                        >
                            Mở chỉ đường <i class="fa-solid fa-arrow-up-right-from-square text-[10px]"></i>
                        </a>
                    </div>
                    <div class="w-full h-[320px] sm:h-[380px] flex-1 bg-slate-100">
                        <iframe
                            title="Bản đồ Công Ty TNHH Xây Dựng Đại Quang Hội - 186/54 Phạm Như Xương, Liên Chiểu, Đà Nẵng"
                            src="https://maps.google.com/maps?q=186%2F54+Ph%E1%BA%A1m+Nh%C6%B0+X%C6%B0%C6%A1ng,+Li%C3%AAn+Chi%E1%BB%83u,+%C4%90%C3%A0+N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed"
                            class="w-full h-full border-0"
                            loading="lazy"
                            referrerpolicy="no-referrer-when-downgrade"
                            allowfullscreen
                        ></iframe>
                    </div>
                </div>

                <!-- Cột Phải: Fanpage Facebook chính thức -->
                <div class="lg:col-span-5 bg-slate-50 rounded-2xl border border-slate-200 overflow-hidden flex flex-col shadow-sm">
                    <div class="px-4 sm:px-5 py-3.5 bg-white border-b border-slate-200 flex items-center justify-between gap-2">
                        <div class="flex items-center gap-2 text-brand-primary font-bold text-sm">
                            <i class="fa-brands fa-facebook text-[#1877F2] text-base"></i>
                            <span>Fanpage Chính Thức</span>
                        </div>
                        <a
                            href="https://www.facebook.com/nhathauxaydungdndaiquanghoi"
                            target="_blank"
                            rel="noopener noreferrer"
                            class="text-xs font-semibold text-[#1877F2] hover:underline"
                        >
                            Theo dõi trang
                        </a>
                    </div>

                    <!-- Khung nhúng Facebook Page Plugin kết hợp thẻ thông tin trực quan -->
                    <div class="p-4 sm:p-5 flex-1 flex flex-col justify-between gap-4">
                        <div class="w-full rounded-xl overflow-hidden bg-white border border-slate-200">
                            <iframe
                                title="Fanpage Thiết Kế và Xây Dựng - ĐẠI QUANG HỘI"
                                src="https://www.facebook.com/plugins/page.php?href=https%3A%2F%2Fwww.facebook.com%2Fnhathauxaydungdndaiquanghoi&tabs=timeline&width=420&height=260&small_header=false&adapt_container_width=true&hide_cover=false&show_facepile=true"
                                class="w-full h-[260px] border-0"
                                scrolling="no"
                                frameborder="0"
                                allowfullscreen="true"
                                allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share"
                            ></iframe>
                        </div>

                        <!-- Thẻ tóm tắt Fanpage luôn hiển thị rõ ràng trên mọi trình duyệt -->
                        <div class="bg-white rounded-xl p-4 border border-slate-200 flex items-center justify-between gap-3">
                            <div class="flex items-center gap-3 min-w-0">
                                <img
                                    src="https://lh3.googleusercontent.com/d/1rKETtm1G4VkohFkUMZToI0dkvmVaTHUC"
                                    data-gdrive-id="1rKETtm1G4VkohFkUMZToI0dkvmVaTHUC"
                                    alt="Fanpage Đại Quang Hội"
                                    class="w-11 h-11 rounded-lg object-contain border border-slate-200 p-1 shrink-0"
                                    onerror="handleDriveImageError(this, true)"
                                >
                                <div class="min-w-0">
                                    <div class="text-xs sm:text-sm font-bold text-brand-primary break-words">Thiết Kế và Xây Dựng - ĐẠI QUANG HỘI</div>
                                    <div class="text-[11px] text-slate-500">Cập nhật tiến độ thi công hằng ngày tại Đà Nẵng</div>
                                </div>
                            </div>
                            <a
                                href="https://www.facebook.com/nhathauxaydungdndaiquanghoi"
                                target="_blank"
                                rel="noopener noreferrer"
                                class="shrink-0 bg-[#1877F2] hover:bg-blue-700 text-white text-xs font-bold px-3.5 py-2 rounded-lg transition-colors"
                            >
                                Xem Fanpage
                            </a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- =================================================================== -->
    <!-- 14. FOOTER CHUYÊN NGHIỆP (CHUẨN FLATSOME 3 CỘT)                     -->
    <!-- =================================================================== -->
    <footer class="bg-brand-dark text-slate-200 pt-10 sm:pt-12 pb-6">
        <div class="flatsome-container">
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-12 gap-8 pb-8 border-b border-white/10">
                <!-- Cột 1: Thông tin doanh nghiệp -->
                <div class="lg:col-span-5 space-y-3">
                    <div class="flex items-center gap-3">
                        <div class="bg-white rounded-lg p-1.5 shrink-0">
                            <img
                                src="https://lh3.googleusercontent.com/d/1rKETtm1G4VkohFkUMZToI0dkvmVaTHUC"
                                data-gdrive-id="1rKETtm1G4VkohFkUMZToI0dkvmVaTHUC"
                                alt="Logo Công Ty TNHH Xây Dựng Đại Quang Hội"
                                class="h-9 w-auto object-contain"
                                onerror="handleDriveImageError(this, true)"
                            >
                        </div>
                        <div>
                            <h3 class="text-sm sm:text-base font-extrabold text-white uppercase">CÔNG TY TNHH XÂY DỰNG ĐẠI QUANG HỘI</h3>
                            <p class="text-[11px] text-amber-300 font-medium">Làm việc bằng tâm – Xứng tầm chất lượng</p>
                        </div>
                    </div>
                    <ul class="space-y-2 text-xs sm:text-sm text-slate-300 pt-1">
                        <li class="flex items-start gap-2.5">
                            <i class="fa-solid fa-location-dot text-brand-accent mt-1 shrink-0"></i>
                            <span><strong>Địa chỉ:</strong> 186/54 Phạm Như Xương, Phường Liên Chiểu, TP Đà Nẵng</span>
                        </li>
                        <li class="flex items-center gap-2.5">
                            <i class="fa-solid fa-phone text-brand-accent shrink-0"></i>
                            <span><strong>Hotline / Zalo:</strong> <a href="tel:0932103549" class="text-white hover:text-amber-300 font-semibold">0932.103.549</a></span>
                        </li>
                        <li class="flex items-center gap-2.5">
                            <i class="fa-solid fa-envelope text-brand-accent shrink-0"></i>
                            <span><strong>Email:</strong> <a href="mailto:daiquanghoi@gmail.com" class="hover:text-amber-300">daiquanghoi@gmail.com</a></span>
                        </li>
                        <li class="flex items-center gap-2.5">
                            <i class="fa-solid fa-globe text-brand-accent shrink-0"></i>
                            <span><strong>Website:</strong> <a href="https://daiquanghoi.com" class="hover:text-amber-300">daiquanghoi.com</a></span>
                        </li>
                        <li class="flex items-center gap-2.5">
                            <i class="fa-solid fa-building-shield text-brand-accent shrink-0"></i>
                            <span><strong>Mã số thuế:</strong> 0401872569</span>
                        </li>
                    </ul>
                </div>

                <!-- Cột 2: Lĩnh vực hoạt động -->
                <div class="lg:col-span-3 space-y-3">
                    <h4 class="text-sm font-extrabold text-white uppercase tracking-wide">Lĩnh Vực Hoạt Động</h4>
                    <ul class="space-y-2 text-xs sm:text-sm text-slate-300">
                        <li><a href="#dich-vu" class="hover:text-amber-300 transition-colors">Thiết kế Kiến trúc – Nội thất</a></li>
                        <li><a href="#cong-trinh-thuc-te" onclick="selectCategoryAndScroll('phan-tho')" class="hover:text-amber-300 transition-colors">Thi công phần thô Đà Nẵng</a></li>
                        <li><a href="#cong-trinh-thuc-te" onclick="selectCategoryAndScroll('hoan-thien')" class="hover:text-amber-300 transition-colors">Thi công hoàn thiện trọn gói</a></li>
                        <li><a href="#cong-trinh-thuc-te" onclick="selectCategoryAndScroll('can-ho')" class="hover:text-amber-300 transition-colors">Xây dựng căn hộ cho thuê & Khách sạn</a></li>
                        <li><a href="#cong-trinh-thuc-te" onclick="selectCategoryAndScroll('van-phong')" class="hover:text-amber-300 transition-colors">Thi công nội thất & Cải tạo nhà ở</a></li>
                    </ul>
                </div>

                <!-- Cột 3: Hỗ trợ khách hàng -->
                <div class="lg:col-span-4 space-y-3">
                    <h4 class="text-sm font-extrabold text-white uppercase tracking-wide">Hỗ Trợ Khách Hàng</h4>
                    <ul class="space-y-2 text-xs sm:text-sm text-slate-300">
                        <li><a href="#bao-gia" class="hover:text-amber-300 transition-colors">Báo giá thi công phần thô & trọn gói</a></li>
                        <li><a href="#du-an-da-nang" class="hover:text-amber-300 transition-colors">Dự án tiêu biểu tại Đà Nẵng</a></li>
                        <li><a href="#tin-tuc" class="hover:text-amber-300 transition-colors">Cẩm nang kinh nghiệm xây nhà</a></li>
                        <li><a href="#form-bao-gia" class="hover:text-amber-300 transition-colors">Đăng ký khảo sát & dự toán miễn phí</a></li>
                        <li><a href="https://www.facebook.com/nhathauxaydungdndaiquanghoi" target="_blank" rel="noopener noreferrer" class="hover:text-amber-300 transition-colors">Fanpage: facebook.com/nhathauxaydungdndaiquanghoi</a></li>
                    </ul>
                </div>
            </div>

            <div class="pt-5 flex flex-col sm:flex-row items-center justify-between gap-2 text-xs text-slate-400 text-center sm:text-left">
                <p>Copyright 2026 © CÔNG TY TNHH XÂY DỰNG ĐẠI QUANG HỘI – daiquanghoi.com</p>
                <p>Thiết kế chuẩn giao diện Flatsome UX Builder</p>
            </div>
        </div>
    </footer>

    <!-- =================================================================== -->
    <!-- 15. CÁC NÚT LIÊN HỆ NỔI BẬT: ZALO, FACEBOOK, HOTLINE                -->
    <!-- Tương thích gọn đẹp trên cả máy tính và điện thoại, không tràn viền -->
    <!-- =================================================================== -->
    <div class="fixed right-3 sm:right-5 bottom-4 sm:bottom-6 z-40 flex flex-col items-end gap-2.5">
        <!-- Nút Facebook -->
        <a
            href="https://www.facebook.com/nhathauxaydungdndaiquanghoi"
            target="_blank"
            rel="noopener noreferrer"
            aria-label="Liên hệ Facebook Đại Quang Hội"
            class="group flex items-center gap-2 bg-[#1877F2] hover:bg-blue-700 text-white rounded-full shadow-lg p-2.5 sm:px-3.5 sm:py-2.5 transition-all"
        >
            <i class="fa-brands fa-facebook-messenger text-lg sm:text-base w-5 h-5 flex items-center justify-center"></i>
            <span class="hidden sm:inline text-xs font-bold pr-1">Facebook</span>
        </a>

        <!-- Nút Zalo -->
        <a
            href="https://zalo.me/0932103549"
            target="_blank"
            rel="noopener noreferrer"
            aria-label="Chat Zalo 0932.103.549"
            class="group flex items-center gap-2 bg-[#0068FF] hover:bg-blue-600 text-white rounded-full shadow-lg p-2.5 sm:px-3.5 sm:py-2.5 transition-all"
        >
            <span class="w-5 h-5 rounded-full bg-white text-[#0068FF] font-extrabold text-[10px] flex items-center justify-center leading-none">Z</span>
            <span class="hidden sm:inline text-xs font-bold pr-1">Zalo</span>
        </a>

        <!-- Nút Hotline -->
        <a
            href="tel:0932103549"
            aria-label="Gọi Hotline 0932.103.549"
            class="hotline-pulse flex items-center gap-2 bg-red-600 hover:bg-red-700 text-white rounded-full shadow-xl p-2.5 sm:px-4 sm:py-2.5 transition-all"
        >
            <i class="fa-solid fa-phone-volume text-base w-5 h-5 flex items-center justify-center"></i>
            <span class="hidden sm:inline text-xs font-extrabold tracking-wide">0932.103.549</span>
        </a>

        <!-- Nút lên đầu trang -->
        <button
            id="scroll-top-btn"
            type="button"
            aria-label="Lên đầu trang"
            onclick="window.scrollTo({ top: 0, behavior: 'smooth' })"
            class="hidden w-10 h-10 rounded-full bg-brand-primary/90 hover:bg-brand-dark text-white shadow-md items-center justify-center transition-all"
        >
            <i class="fa-solid fa-arrow-up text-xs"></i>
        </button>
    </div>

    <!-- =================================================================== -->
    <!-- 16. MODAL XEM CHI TIẾT CÔNG TRÌNH / BÀI VIẾT & THÔNG BÁO FORM       -->
    <!-- =================================================================== -->
    <div id="detail-modal" class="fixed inset-0 z-50 hidden items-center justify-center bg-slate-900/70 backdrop-blur-sm p-3 sm:p-6">
        <div class="bg-white rounded-2xl max-w-2xl w-full max-h-[90vh] overflow-y-auto shadow-2xl border border-slate-200">
            <div class="sticky top-0 bg-white px-5 py-3.5 border-b border-slate-200 flex items-center justify-between gap-3 z-10">
                <h3 id="modal-title" class="text-sm sm:text-base font-extrabold text-brand-primary leading-snug"></h3>
                <button type="button" onclick="closeDetailModal()" aria-label="Đóng cửa sổ" class="w-8 h-8 rounded-lg bg-slate-100 hover:bg-slate-200 text-slate-700 flex items-center justify-center shrink-0">
                    <i class="fa-solid fa-xmark"></i>
                </button>
            </div>
            <div class="p-5 space-y-4">
                <div id="modal-image-wrap" class="w-full rounded-xl overflow-hidden bg-slate-100">
                    <img id="modal-image" src="" alt="" class="w-full max-h-[380px] object-cover">
                </div>
                <div id="modal-meta" class="flex flex-wrap gap-3 text-xs text-slate-500"></div>
                <div id="modal-body" class="text-xs sm:text-sm text-slate-700 leading-relaxed space-y-3"></div>
                <div class="pt-3 border-t border-slate-100 flex flex-wrap items-center justify-between gap-3">
                    <a href="tel:0932103549" class="inline-flex items-center gap-2 bg-brand-primary hover:bg-brand-dark text-white text-xs sm:text-sm font-bold px-4 py-2.5 rounded-xl transition-colors">
                        <i class="fa-solid fa-phone"></i>
                        <span>Gọi tư vấn: 0932.103.549</span>
                    </a>
                    <a href="#form-bao-gia" onclick="closeDetailModal()" class="inline-flex items-center gap-2 bg-brand-accent hover:bg-brand-accentHover text-white text-xs sm:text-sm font-bold px-4 py-2.5 rounded-xl transition-colors">
                        <span>Nhận báo giá mẫu này</span>
                    </a>
                </div>
            </div>
        </div>
    </div>

    <!-- Hộp thông báo phản hồi Form (thay thế hoàn toàn alert) -->
    <div id="toast-box" class="fixed top-5 left-1/2 -translate-x-1/2 z-50 hidden max-w-md w-[92%] bg-emerald-700 text-white px-5 py-3.5 rounded-xl shadow-2xl items-center gap-3 text-xs sm:text-sm font-medium">
        <i class="fa-solid fa-circle-check text-lg text-emerald-200 shrink-0"></i>
        <span id="toast-message"></span>
    </div>

    <!-- =================================================================== -->
    <!-- 17. JAVASCRIPT XỬ LÝ BANNER, DỮ LIỆU ẢNH GOOGLE DRIVE & TƯƠNG TÁC   -->
    <!-- =================================================================== -->
    <script>
        /**
         * Hàm tạo URL ảnh Google Drive tối ưu hiển thị trực tiếp
         */
        function getDriveImageUrl(fileId) {
            return 'https://lh3.googleusercontent.com/d/' + fileId;
        }

        /**
         * Xử lý fallback tự động nếu đường dẫn ảnh Google Drive chính bị chậm/chặn
         */
        function handleDriveImageError(imgEl, isLogo) {
            try {
                const fileId = imgEl.getAttribute('data-gdrive-id');
                const retryCount = parseInt(imgEl.getAttribute('data-retry') || '0', 10);

                if (fileId && retryCount === 0) {
                    imgEl.setAttribute('data-retry', '1');
                    imgEl.src = 'https://drive.google.com/thumbnail?id=' + fileId + '&sz=w1000';
                    return;
                }

                if (retryCount < 2) {
                    imgEl.setAttribute('data-retry', '2');
                    imgEl.src = isLogo
                        ? 'https://placehold.co/240x90/0B3B75/FFFFFF?text=DAI+QUANG+HOI'
                        : 'https://placehold.co/800x600/0B3B75/FFFFFF?text=Xay+Dung+Dai+Quang+Hoi';
                }
            } catch (err) {
                console.error('Lỗi tải ảnh dự phòng:', err);
            }
        }

        /**
         * Dữ liệu 9 ảnh thực tế thi công xây dựng từ Google Drive
         * Phân nhóm theo đúng danh mục sản phẩm của web mẫu
         */
        const constructionWorks = [
            {
                id: '13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz',
                title: 'Thi Công Phần Thô Nhà Phố Võ Duy Dương – Đà Nẵng',
                category: 'phan-tho',
                categoryLabel: 'Thi công phần thô',
                location: 'Đà Nẵng',
                scale: 'Nhà phố 3 tầng – Kết cấu bê tông cốt thép',
                desc: 'Hạng mục thi công móng, cột, dầm sàn theo đúng bản vẽ kết cấu và quy chuẩn kỹ thuật. Kỹ sư Đại Quang Hội giám sát trực tiếp từng công đoạn đổ bê tông và bảo dưỡng chuẩn.'
            },
            {
                id: '1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR',
                title: 'Thi Công Đổ Sàn & Khung Kết Cấu Nhà Phố Hiện Đại',
                category: 'phan-tho',
                categoryLabel: 'Thi công phần thô',
                location: 'Quận Liên Chiểu, Đà Nẵng',
                scale: 'Diện tích sàn 280m²',
                desc: 'Công tác lắp dựng cốp pha, cốt thép đạt độ chính xác cao, kiểm tra nghiệm thu chặt chẽ cùng chủ đầu tư trước khi tiến hành đổ bê tông sàn.'
            },
            {
                id: '1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv',
                title: 'Thi Công Hoàn Thiện Trọn Gói Nhà Phố 3 Tầng',
                category: 'hoan-thien',
                categoryLabel: 'Thi công hoàn thiện',
                location: 'Đà Nẵng',
                scale: 'Chìa khóa trao tay',
                desc: 'Hoàn thiện mặt tiền, hệ thống điện nước âm tường, sơn bả cao cấp và lắp đặt thiết bị vệ sinh đồng bộ, bàn giao đúng tiến độ cam kết.'
            },
            {
                id: '1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_',
                title: 'Xây Dựng Căn Hộ Cho Thuê Khép Kín Tối Ưu Công Năng',
                category: 'can-ho',
                categoryLabel: 'Khách sạn - Căn hộ - Phòng trọ',
                location: 'Quận Liên Chiểu, Đà Nẵng',
                scale: '5 tầng – 16 phòng căn hộ',
                desc: 'Giải pháp thiết kế và thi công căn hộ cho thuê hoàn vốn nhanh, tối ưu ánh sáng tự nhiên, phòng cháy chữa cháy và vật liệu bền đẹp dễ vận hành.'
            },
            {
                id: '1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO',
                title: 'Thiết Kế & Thi Công Nhà Phố Mặt Tiền Sang Trọng',
                category: 'nha-pho',
                categoryLabel: 'Nhà phố',
                location: 'Quận Hải Châu, Đà Nẵng',
                scale: 'Nhà phố 3 tầng 1 tum',
                desc: 'Kiến trúc hiện đại thông thoáng với ban công rộng, hệ lam chắn nắng tinh tế và giải pháp chống thấm toàn diện phù hợp khí hậu miền Trung.'
            },
            {
                id: '1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t',
                title: 'Thi Công Biệt Thự Hiện Đại Không Gian Mở',
                category: 'biet-thu',
                categoryLabel: 'Biệt thự',
                location: 'Quận Ngũ Hành Sơn, Đà Nẵng',
                scale: 'Biệt thự 2 mặt tiền – Sân vườn',
                desc: 'Biệt thự thiết kế đẳng cấp kết hợp không gian sân vườn xanh mát, sử dụng vật liệu hoàn thiện cao cấp, đảm bảo thẩm mỹ bền vững theo thời gian.'
            },
            {
                id: '1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_',
                title: 'Hoàn Thiện Kiến Trúc & Chống Thấm Ngoại Thất',
                category: 'hoan-thien',
                categoryLabel: 'Thi công hoàn thiện',
                location: 'Quận Cẩm Lệ, Đà Nẵng',
                scale: 'Gói hoàn thiện tiêu chuẩn',
                desc: 'Xử lý bề mặt tường, sơn chống thấm ngoài trời nhiều lớp và ốp lát gạch thẩm mỹ giúp công trình bền màu dưới điều kiện nắng gió ven biển.'
            },
            {
                id: '1wHGqk7znpnGmrOjz4_EdpHnHK8xKyxkT',
                title: 'Thiết Kế & Thi Công Nội Thất Văn Phòng – Nhà Ở',
                category: 'van-phong',
                categoryLabel: 'Văn phòng - Nội thất',
                location: 'Quận Thanh Khê, Đà Nẵng',
                scale: 'Thi công nội thất trọn gói',
                desc: 'Bố trí công năng khoa học, ánh sáng hài hòa cùng hệ nội thất gỗ công nghiệp chống ẩm An Cường sắc nét từng chi tiết.'
            },
            {
                id: '1-eBgG9wF3I6_gyPir2CmCnwJg4sP7Bnn',
                title: 'Xây Dựng Nhà Phố Dân Dụng Trọn Gói Liên Chiểu',
                category: 'nha-pho',
                categoryLabel: 'Nhà phố',
                location: 'Phường Hòa Khánh, Liên Chiểu, Đà Nẵng',
                scale: 'Nhà phố 2 tầng 1 tum',
                desc: 'Công trình thiết kế và thi công trọn gói chìa khóa trao tay, không phát sinh chi phí, bàn giao sạch đẹp và bảo hành dài hạn.'
            }
        ];

        /**
         * Dữ liệu 10 dự án tiêu biểu tại Đà Nẵng từ Google Drive
         */
        const danangProjects = [
            {
                id: '157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT',
                title: 'Dự Án Nhà Phố Hiện Đại – Hòa Khánh, Liên Chiểu',
                location: 'Quận Liên Chiểu, TP Đà Nẵng',
                desc: 'Công trình nhà phố 3 tầng thiết kế tối ưu diện tích, thông gió tự nhiên và thi công trọn gói bởi đội ngũ Đại Quang Hội.'
            },
            {
                id: '1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff',
                title: 'Dự Án Căn Hộ Cho Thuê Cao Cấp – Sơn Trà',
                location: 'Quận Sơn Trà, TP Đà Nẵng',
                desc: 'Tòa căn hộ dịch vụ hiện đại gần biển, bố trí công năng tối đa số phòng cho thuê và đảm bảo kết cấu vững chắc.'
            },
            {
                id: '1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz',
                title: 'Dự Án Nhà Phố 3 Tầng – Khu Đô Thị Hòa Xuân',
                location: 'Quận Cẩm Lệ, TP Đà Nẵng',
                desc: 'Nhà ở gia đình kiến trúc hiện đại tại Hòa Xuân, hoàn thiện tinh tế, vật tư chính hãng và bàn giao đúng hẹn.'
            },
            {
                id: '1I7lc3ghS0tyqh6Pq3xsZTidKsr0oT-8k',
                title: 'Dự Án Biệt Thự Phố Sang Trọng – Ngũ Hành Sơn',
                location: 'Quận Ngũ Hành Sơn, TP Đà Nẵng',
                desc: 'Thiết kế mặt tiền ấn tượng kết hợp vật liệu kính và đá tự nhiên, tạo không gian sống đẳng cấp cho gia chủ.'
            },
            {
                id: '1Q8VoCbT7s09UNaoI8GNcYdvKpJ2wz78N',
                title: 'Dự Án Nhà Ở Kết Hợp Kinh Doanh – Hải Châu',
                location: 'Quận Hải Châu, TP Đà Nẵng',
                desc: 'Tối ưu tầng trệt làm mặt bằng kinh doanh và các tầng trên cho không gian sinh hoạt riêng tư tiện nghi.'
            },
            {
                id: '1tkQlfZJTkaSunwOIMhfnzkEG2YHwxhML',
                title: 'Dự Án Thi Công Căn Hộ Mini – Phạm Như Xương',
                location: 'Liên Chiểu, TP Đà Nẵng',
                desc: 'Mô hình căn hộ cho thuê thu hút sinh viên và người đi làm tại khu vực Đại học Sư Phạm & Bách Khoa Đà Nẵng.'
            },
            {
                id: '1An7LyMVwj3rhKZlsVnYQ2UrLe48IeTBF',
                title: 'Dự Án Nhà Phố 2 Mặt Tiền – Khu Phước Lý',
                location: 'Cẩm Lệ – Liên Chiểu, TP Đà Nẵng',
                desc: 'Khai thác triệt để lợi thế 2 mặt tiền thoáng sáng, kết cấu kiên cố và hệ mái chống nóng hiệu quả.'
            },
            {
                id: '1R1Da04pAYI9-NJz1IsAfa7pVKkuK7J-A',
                title: 'Dự Án Khách Sạn Boutique – Mỹ Khê, Đà Nẵng',
                location: 'Quận Sơn Trà, TP Đà Nẵng',
                desc: 'Thi công phần thô và hoàn thiện khách sạn du lịch đạt tiêu chuẩn kỹ thuật, thẩm mỹ cao và tối ưu chi phí đầu tư.'
            },
            {
                id: '1FdQEsiEBrIW5TiN22dvzV5g6amDPp-80',
                title: 'Dự Án Văn Phòng Làm Việc – Thanh Khê',
                location: 'Quận Thanh Khê, TP Đà Nẵng',
                desc: 'Không gian văn phòng chuyên nghiệp, tối ưu ánh sáng và hệ thống kỹ thuật cơ điện hiện đại.'
            },
            {
                id: '1So_3V4rw1y7lHegiIkYmh2Z9UIdozAL4',
                title: 'Dự Án Biệt Thự Vườn – Nam Việt Á, Đà Nẵng',
                location: 'Quận Ngũ Hành Sơn, TP Đà Nẵng',
                desc: 'Biệt thự gia đình yên tĩnh, hoàn thiện nội ngoại thất đồng bộ, bảo hành kết cấu 5 năm và bảo trì trọn đời.'
            }
        ];

        /**
         * Dữ liệu các bài viết kiến thức xây dựng hiển thị trên trang chủ
         */
        const articlesData = [
            {
                title: 'Hướng dẫn bảo dưỡng bê tông móng và sàn đúng kỹ thuật sau khi đổ',
                imageId: '1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR',
                date: '15/10/2026',
                excerpt: 'Bảo dưỡng bê tông đúng cách quyết định trực tiếp đến cường độ chịu lực và khả năng chống nứt lâu dài cho toàn bộ công trình.',
                content: 'Trong quá trình thi công phần thô tại Đà Nẵng, khí hậu nắng nóng dễ khiến bề mặt bê tông mất nước nhanh. Kỹ sư Đại Quang Hội luôn yêu cầu tưới nước giữ ẩm liên tục trong 7 ngày đầu, che phủ bao bố giữ ẩm và kiểm tra độ sụt bê tông nghiêm ngặt trước khi đổ để công trình đạt cường độ thiết kế cao nhất.'
            },
            {
                title: 'Kinh nghiệm xây căn hộ cho thuê tại Đà Nẵng tối ưu chi phí & hoàn vốn nhanh',
                imageId: '1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_',
                date: '02/10/2026',
                excerpt: 'Làm sao để tối ưu số lượng phòng, tiết kiệm chi phí xây dựng mà vẫn đảm bảo không gian thoáng đẹp, thu hút khách thuê lâu dài?',
                content: 'Khi đầu tư xây dựng căn hộ cho thuê tại Đà Nẵng, chủ đầu tư cần chú trọng 3 yếu tố then chốt: tối ưu diện tích giao thông chung, lựa chọn vật tư bền đẹp dễ bảo trì và chuẩn bị đầy đủ hồ sơ cấp phép cũng như giải pháp PCCC. Đại Quang Hội hỗ trợ miễn phí tư vấn phương án mặt bằng và dự toán chi tiết ngay từ đầu.'
            },
            {
                title: '03 lưu ý quan trọng chủ nhà cần biết trước khi ký hợp đồng xây nhà trọn gói',
                imageId: '1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv',
                date: '20/09/2026',
                excerpt: 'Kiểm tra rõ chủng loại vật tư, tiến độ thanh toán và chính sách bảo hành sẽ giúp gia chủ tránh hoàn toàn rủi ro phát sinh chi phí.',
                content: 'Trước khi khởi công, chủ nhà nên thống nhất bản vẽ thiết kế chi tiết, bảng liệt kê thương hiệu vật tư thô và hoàn thiện cụ thể trong phụ lục hợp đồng, đồng thời lựa chọn đơn vị có kỹ sư giám sát trực tiếp tại công trình. Cam kết minh bạch và không phát sinh là nguyên tắc hàng đầu tại Công Ty TNHH Xây Dựng Đại Quang Hội.'
            },
            {
                title: 'Bí quyết chống thấm nhà phố miền Trung hiệu quả bền vững qua mùa mưa bão',
                imageId: '1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_',
                date: '08/09/2026',
                excerpt: 'Xử lý chống thấm đúng quy trình tại khu vực sân thượng, nhà vệ sinh và tường giáp ranh giúp ngôi nhà luôn bền đẹp như mới.',
                content: 'Với đặc thù thời tiết mưa lớn kéo dài vào cuối năm tại Đà Nẵng, công tác chống thấm cần được thực hiện đồng bộ ngay từ giai đoạn thi công phần thô: xử lý cổ ống xuyên sàn bằng vữa không co ngót, quét tối thiểu 2-3 lớp màng chống thấm đàn hồi và ngâm thử nước 48 giờ trước khi lát gạch hoàn thiện.'
            }
        ];

        /**
         * Hiển thị danh sách công trình thực tế (2 cột trên điện thoại, không nhãn dán)
         */
        function renderConstructionGrid(filterCat) {
            const container = document.getElementById('construction-grid');
            if (!container) return;

            const filtered = filterCat === 'all'
                ? constructionWorks
                : constructionWorks.filter(item => item.category === filterCat);

            container.innerHTML = filtered.map((item, idx) => `
                <article
                    onclick="openWorkModal('${item.id}', 'work')"
                    class="group cursor-pointer bg-white rounded-xl sm:rounded-2xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-lg transition-all flex flex-col"
                >
                    <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
                        <img
                            src="${getDriveImageUrl(item.id)}"
                            data-gdrive-id="${item.id}"
                            alt="${item.title}"
                            loading="lazy"
                            class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500"
                            onerror="handleDriveImageError(this, false)"
                        >
                    </div>
                    <div class="p-2.5 sm:p-4 flex-1 flex flex-col justify-between gap-1.5">
                        <h3 class="text-[12px] sm:text-sm font-bold text-slate-800 group-hover:text-brand-primary leading-snug break-words">
                            ${item.title}
                        </h3>
                        <p class="text-[11px] sm:text-xs text-slate-500 flex items-center gap-1">
                            <i class="fa-solid fa-location-dot text-brand-accent text-[10px] shrink-0"></i>
                            <span class="break-words">${item.location}</span>
                        </p>
                    </div>
                </article>
            `).join('');
        }

        /**
         * Hiển thị danh sách 10 dự án tiêu biểu tại Đà Nẵng (2 cột trên điện thoại, 5 cột trên máy tính)
         */
        function renderDanangProjects() {
            const container = document.getElementById('danang-projects-grid');
            if (!container) return;

            container.innerHTML = danangProjects.map(item => `
                <article
                    onclick="openWorkModal('${item.id}', 'danang')"
                    class="group cursor-pointer bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-lg transition-all flex flex-col"
                >
                    <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
                        <img
                            src="${getDriveImageUrl(item.id)}"
                            data-gdrive-id="${item.id}"
                            alt="${item.title}"
                            loading="lazy"
                            class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500"
                            onerror="handleDriveImageError(this, false)"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between gap-1">
                        <h3 class="text-[12px] sm:text-[13px] font-bold text-slate-800 group-hover:text-brand-primary leading-snug break-words">
                            ${item.title}
                        </h3>
                        <p class="text-[10px] sm:text-[11px] text-slate-500 break-words">
                            ${item.location}
                        </p>
                    </div>
                </article>
            `).join('');
        }

        /**
         * Hiển thị danh sách bài viết trang chủ (2 cột trên điện thoại, 4 cột trên máy tính)
         */
        function renderArticles() {
            const container = document.getElementById('articles-grid');
            if (!container) return;

            container.innerHTML = articlesData.map((art, index) => `
                <article
                    onclick="openArticleModal(${index})"
                    class="group cursor-pointer bg-white rounded-xl sm:rounded-2xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-lg transition-all flex flex-col"
                >
                    <div class="aspect-[16/10] w-full overflow-hidden bg-slate-100">
                        <img
                            src="${getDriveImageUrl(art.imageId)}"
                            data-gdrive-id="${art.imageId}"
                            alt="${art.title}"
                            loading="lazy"
                            class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500"
                            onerror="handleDriveImageError(this, false)"
                        >
                    </div>
                    <div class="p-2.5 sm:p-4 flex-1 flex flex-col justify-between gap-2">
                        <div>
                            <div class="text-[10px] sm:text-[11px] text-slate-400 mb-1">
                                <i class="fa-regular fa-calendar mr-1"></i>${art.date}
                            </div>
                            <h3 class="text-[12px] sm:text-sm font-bold text-slate-800 group-hover:text-brand-primary leading-snug break-words mb-1.5">
                                ${art.title}
                            </h3>
                            <p class="hidden sm:block text-xs text-slate-600 leading-relaxed">
                                ${art.excerpt}
                            </p>
                        </div>
                        <span class="text-[11px] sm:text-xs font-bold text-brand-accent group-hover:text-brand-primary inline-flex items-center gap-1">
                            <span>Đọc chi tiết</span>
                            <i class="fa-solid fa-arrow-right text-[10px]"></i>
                        </span>
                    </div>
                </article>
            `).join('');
        }

        /**
         * Kích hoạt chọn danh mục từ menu thả xuống và cuộn mượt tới mục công trình
         */
        function selectCategoryAndScroll(cat) {
            setActiveCategoryTab(cat);
            renderConstructionGrid(cat);
            const target = document.getElementById('cong-trinh-thuc-te');
            if (target) {
                target.scrollIntoView({ behavior: 'smooth', block: 'start' });
            }
        }

        /**
         * Cập nhật trạng thái nổi bật cho tab danh mục
         */
        function setActiveCategoryTab(cat) {
            document.querySelectorAll('.cat-tab').forEach(btn => {
                const isActive = btn.getAttribute('data-cat') === cat;
                if (isActive) {
                    btn.className = 'cat-tab whitespace-nowrap px-3 py-1.5 rounded-lg text-[11px] sm:text-xs font-semibold transition-all bg-brand-primary text-white shadow-sm';
                } else {
                    btn.className = 'cat-tab whitespace-nowrap px-3 py-1.5 rounded-lg text-[11px] sm:text-xs font-semibold transition-all bg-white text-slate-700 border border-slate-200 hover:border-brand-primary hover:text-brand-primary';
                }
            });
        }

        /**
         * Mở hộp thoại chi tiết công trình / dự án
         */
        function openWorkModal(id, type) {
            const list = type === 'danang' ? danangProjects : constructionWorks;
            const item = list.find(x => x.id === id);
            if (!item) return;

            const modal = document.getElementById('detail-modal');
            const img = document.getElementById('modal-image');
            document.getElementById('modal-title').textContent = item.title;
            img.setAttribute('data-gdrive-id', item.id);
            img.setAttribute('data-retry', '0');
            img.src = getDriveImageUrl(item.id);
            img.alt = item.title;
            img.onerror = function() { handleDriveImageError(this, false); };

            document.getElementById('modal-meta').innerHTML = `
                <span><i class="fa-solid fa-location-dot text-brand-accent mr-1"></i>${item.location}</span>
                ${item.scale ? `<span><i class="fa-solid fa-ruler-combined text-brand-primary mr-1"></i>${item.scale}</span>` : ''}
                ${item.categoryLabel ? `<span><i class="fa-solid fa-folder-open text-brand-primary mr-1"></i>${item.categoryLabel}</span>` : ''}
            `;
            document.getElementById('modal-body').innerHTML = `<p>${item.desc}</p><p><strong>Đơn vị thực hiện:</strong> Công Ty TNHH Xây Dựng Đại Quang Hội – Địa chỉ: 186/54 Phạm Như Xương, Phường Liên Chiểu, TP Đà Nẵng.</p>`;

            modal.classList.remove('hidden');
            modal.classList.add('flex');
        }

        /**
         * Mở hộp thoại đọc chi tiết bài viết
         */
        function openArticleModal(index) {
            const art = articlesData[index];
            if (!art) return;

            const modal = document.getElementById('detail-modal');
            const img = document.getElementById('modal-image');
            document.getElementById('modal-title').textContent = art.title;
            img.setAttribute('data-gdrive-id', art.imageId);
            img.setAttribute('data-retry', '0');
            img.src = getDriveImageUrl(art.imageId);
            img.alt = art.title;
            img.onerror = function() { handleDriveImageError(this, false); };

            document.getElementById('modal-meta').innerHTML = `
                <span><i class="fa-regular fa-calendar text-brand-accent mr-1"></i>Ngày đăng: ${art.date}</span>
                <span><i class="fa-solid fa-user-pen text-brand-primary mr-1"></i>Kỹ sư Đại Quang Hội</span>
            `;
            document.getElementById('modal-body').innerHTML = `<p class="font-medium text-slate-800">${art.excerpt}</p><p>${art.content}</p>`;

            modal.classList.remove('hidden');
            modal.classList.add('flex');
        }

        /**
         * Đóng hộp thoại chi tiết
         */
        function closeDetailModal() {
            const modal = document.getElementById('detail-modal');
            modal.classList.add('hidden');
            modal.classList.remove('flex');
        }

        /**
         * Điền sẵn loại công trình khi bấm từ bảng giá
         */
        function prefillQuoteType(typeName) {
            const select = document.getElementById('q-type');
            if (select) {
                for (let i = 0; i < select.options.length; i++) {
                    if (select.options[i].value === typeName) {
                        select.selectedIndex = i;
                        break;
                    }
                }
            }
        }

        /**
         * Hiển thị hộp thông báo thân thiện (không dùng alert)
         */
        let toastTimer = null;
        function showToast(message) {
            const box = document.getElementById('toast-box');
            const msgEl = document.getElementById('toast-message');
            if (!box || !msgEl) return;

            msgEl.textContent = message;
            box.classList.remove('hidden');
            box.classList.add('flex');

            if (toastTimer) clearTimeout(toastTimer);
            toastTimer = setTimeout(() => {
                box.classList.add('hidden');
                box.classList.remove('flex');
            }, 4500);
        }

        /**
         * Đóng menu di động
         */
        function closeMobileMenu() {
            const panel = document.getElementById('mobile-menu-panel');
            if (panel) panel.classList.add('hidden');
        }

        /**
         * Khởi tạo toàn bộ tính năng trang khi tải xong DOM
         */
        document.addEventListener('DOMContentLoaded', function () {
            try {
                // 1. Render các khu vực dữ liệu
                renderConstructionGrid('all');
                renderDanangProjects();
                renderArticles();

                // 2. Xử lý sự kiện lọc danh mục sản phẩm
                document.querySelectorAll('.cat-tab').forEach(btn => {
                    btn.addEventListener('click', function () {
                        const cat = this.getAttribute('data-cat');
                        setActiveCategoryTab(cat);
                        renderConstructionGrid(cat);
                    });
                });

                // 3. Xử lý nút menu di động
                const mobileBtn = document.getElementById('mobile-menu-btn');
                const mobilePanel = document.getElementById('mobile-menu-panel');
                if (mobileBtn && mobilePanel) {
                    mobileBtn.addEventListener('click', function () {
                        mobilePanel.classList.toggle('hidden');
                    });
                }

                // 4. Hệ thống 2 ảnh Banner tự trượt mượt mà (hỗ trợ cả vuốt cảm ứng trên điện thoại)
                const slides = document.querySelectorAll('.hero-slide');
                const dots = document.querySelectorAll('.slide-dot');
                let currentSlide = 0;
                let autoSlideInterval = null;

                function goToSlide(index) {
                    currentSlide = (index + slides.length) % slides.length;
                    slides.forEach((s, i) => {
                        s.classList.toggle('active', i === currentSlide);
                    });
                    dots.forEach((d, i) => {
                        if (i === currentSlide) {
                            d.className = 'slide-dot w-7 h-2 rounded-full bg-brand-accent transition-all';
                        } else {
                            d.className = 'slide-dot w-2.5 h-2 rounded-full bg-white/60 hover:bg-white transition-all';
                        }
                    });
                }

                function startAutoSlide() {
                    stopAutoSlide();
                    autoSlideInterval = setInterval(() => {
                        goToSlide(currentSlide + 1);
                    }, 5200);
                }

                function stopAutoSlide() {
                    if (autoSlideInterval) clearInterval(autoSlideInterval);
                }

                document.getElementById('prev-slide')?.addEventListener('click', () => {
                    goToSlide(currentSlide - 1);
                    startAutoSlide();
                });

                document.getElementById('next-slide')?.addEventListener('click', () => {
                    goToSlide(currentSlide + 1);
                    startAutoSlide();
                });

                dots.forEach(dot => {
                    dot.addEventListener('click', function () {
                        const idx = parseInt(this.getAttribute('data-slide-dot') || '0', 10);
                        goToSlide(idx);
                        startAutoSlide();
                    });
                });

                // Hỗ trợ thao tác vuốt ngang trên banner điện thoại
                const sliderEl = document.getElementById('hero-slider');
                let touchStartX = 0;
                if (sliderEl) {
                    sliderEl.addEventListener('touchstart', e => {
                        touchStartX = e.changedTouches[0].screenX;
                    }, { passive: true });
                    sliderEl.addEventListener('touchend', e => {
                        const diff = e.changedTouches[0].screenX - touchStartX;
                        if (Math.abs(diff) > 45) {
                            goToSlide(diff < 0 ? currentSlide + 1 : currentSlide - 1);
                            startAutoSlide();
                        }
                    }, { passive: true });
                }

                startAutoSlide();

                // 5. Xử lý gửi Form yêu cầu tư vấn & báo giá
                const quoteForm = document.getElementById('quote-form');
                if (quoteForm) {
                    quoteForm.addEventListener('submit', function (e) {
                        e.preventDefault();
                        const name = document.getElementById('q-name').value.trim();
                        const phone = document.getElementById('q-phone').value.trim();

                        if (!name || !phone) {
                            showToast('Vui lòng nhập đầy đủ Họ tên và Số điện thoại để kỹ sư liên hệ tư vấn.');
                            return;
                        }

                        showToast('Cảm ơn ' + name + '! Yêu cầu báo giá của bạn đã được gửi đến Công Ty TNHH Xây Dựng Đại Quang Hội. Kỹ sư sẽ liên hệ qua số ' + phone + ' trong thời gian sớm nhất.');
                        quoteForm.reset();
                    });
                }

                // 6. Đóng modal khi bấm nền tối hoặc phím Escape
                const detailModal = document.getElementById('detail-modal');
                if (detailModal) {
                    detailModal.addEventListener('click', function (e) {
                        if (e.target === detailModal) closeDetailModal();
                    });
                }
                document.addEventListener('keydown', function (e) {
                    if (e.key === 'Escape') closeDetailModal();
                });

                // 7. Hiển thị nút cuộn lên đầu trang khi kéo xuống
                const scrollTopBtn = document.getElementById('scroll-top-btn');
                window.addEventListener('scroll', function () {
                    if (!scrollTopBtn) return;
                    if (window.scrollY > 380) {
                        scrollTopBtn.classList.remove('hidden');
                        scrollTopBtn.classList.add('flex');
                    } else {
                        scrollTopBtn.classList.add('hidden');
                        scrollTopBtn.classList.remove('flex');
                    }
                }, { passive: true });
            } catch (error) {
                console.error('Lỗi khởi tạo trang web Đại Quang Hội:', error);
            }
        });
    </script>
</body>
</html>
