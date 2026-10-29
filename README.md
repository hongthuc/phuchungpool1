<html lang="vi" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Phúc Hưng Pool & Sauna - Thiết Bị Bể Bơi, Phòng Xông Hơi Đà Nẵng - Quảng Nam | phuchungpool.com</title>
    <meta name="description" content="CÔNG TY TNHH XÂY DỰNG VÀ CÔNG NGHỆ PHÚC HƯNG - Chuyên tư vấn, thiết kế, thi công thiết bị bể bơi, phòng xông hơi khô, ướt, đá muối tại Quảng Nam - Đà Nẵng. Hotline: 0934.722.773">
    
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    
    <!-- Google Fonts: Inter -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">
    
    <!-- Font Awesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                    },
                    colors: {
                        primary: {
                            DEFAULT: '#005b96', // Xanh bể bơi chủ đạo
                            dark: '#03396c',
                            light: '#e6f2ff'
                        },
                        sauna: {
                            DEFAULT: '#c87d28', // Vàng gỗ thông xông hơi
                            dark: '#9c5d16',
                            light: '#fdf6ec'
                        }
                    }
                }
            }
        }
    </script>

    <style>
        /* Chuẩn hóa kiểu dáng giống hệt Flatsome Theme (Row, Col, Section Title, Product Box) */
        body {
            font-family: 'Inter', sans-serif;
            color: #333333;
            background-color: #f8fafc;
        }

        /* Flatsome Section Title Style: gạch ngang 2 bên tiêu đề */
        .section-title-container {
            margin-bottom: 1.5rem;
        }
        .section-title-main {
            position: relative;
            display: flex;
            align-items: center;
            justify-content: center;
            width: 100%;
            text-align: center;
        }
        .section-title-main b {
            display: block;
            flex: 1;
            height: 2px;
            background-color: #e2e8f0;
        }
        .section-title-main span {
            padding: 0 18px;
            font-weight: 800;
            text-transform: uppercase;
            letter-spacing: 0.03em;
            color: #03396c;
        }

        /* Hiệu ứng mượt cho Card Sản phẩm kiểu Flatsome */
        .flatsome-product-box {
            transition: all 0.25s ease;
        }
        .flatsome-product-box:hover {
            transform: translateY(-4px);
            box-shadow: 0 10px 25px -5px rgba(0, 0, 0, 0.1), 0 8px 10px -6px rgba(0, 0, 0, 0.05);
        }
        .flatsome-product-box .product-img {
            transition: transform 0.4s ease;
        }
        .flatsome-product-box:hover .product-img {
            transform: scale(1.05);
        }

        /* Nút gọi điện rung nhẹ thu hút chú ý */
        @keyframes phoneRing {
            0%, 100% { transform: rotate(0deg) scale(1); }
            10%, 30% { transform: rotate(-12deg) scale(1.06); }
            20%, 40% { transform: rotate(12deg) scale(1.06); }
            50% { transform: rotate(0deg) scale(1); }
        }
        .animate-ring {
            animation: phoneRing 2.2s infinite ease-in-out;
        }

        /* Ẩn thanh cuộn ngang trên tab mobile */
        .no-scrollbar::-webkit-scrollbar {
            display: none;
        }
        .no-scrollbar {
            -ms-overflow-style: none;
            scrollbar-width: none;
        }
    </style>
</head>
<body class="antialiased selection:bg-primary selection:text-white">

    <!-- =====================================================================
         FLATSOME HEADER: TOP BAR + HEADER MAIN + HEADER BOTTOM NAV
         ===================================================================== -->
    <header id="header" class="bg-white shadow-sm sticky top-0 z-40">
        
        <!-- 1. FLATSOME TOP BAR -->
        <div class="bg-primary-dark text-white text-xs py-1.5 px-3">
            <div class="max-w-7xl mx-auto flex flex-wrap items-center justify-between gap-2">
                <div class="font-medium truncate">
                    <i class="fa-solid fa-certificate text-amber-400 mr-1"></i>
                    CÔNG TY TNHH XÂY DỰNG VÀ CÔNG NGHỆ PHÚC HƯNG - Chuyên Thiết Bị Bể Bơi & Phòng Xông Hơi
                </div>
                <div class="hidden lg:flex items-center gap-5 text-slate-200">
                    <span><i class="fa-solid fa-location-dot text-amber-400 mr-1"></i> 408 Văn Tiến Dũng, P. Hòa Xuân, TP Đà Nẵng</span>
                    <span><i class="fa-regular fa-clock text-amber-400 mr-1"></i> 07:30 - 18:00 (T2 - CN)</span>
                    <a href="tel:0934722773" class="text-amber-300 font-bold hover:underline">
                        <i class="fa-solid fa-phone-volume mr-1"></i> 0934.722.773
                    </a>
                    <a href="https://www.facebook.com/phuchungpoolsauna/" target="_blank" rel="noopener noreferrer" class="hover:text-white">
                        <i class="fa-brands fa-facebook mr-1"></i> fb.com/phuchungpoolsauna
                    </a>
                </div>
            </div>
        </div>

        <!-- 2. FLATSOME HEADER MAIN -->
        <div class="max-w-7xl mx-auto px-3 sm:px-4 py-3 flex items-center justify-between gap-3">
            
            <!-- Nút Menu Mobile (Chuẩn Flatsome Off-Canvas Left) -->
            <button onclick="toggleMobileMenu()" class="lg:hidden p-2.5 rounded-lg border border-slate-200 text-slate-700 hover:bg-slate-100" aria-label="Mở menu">
                <i class="fa-solid fa-bars text-xl"></i>
            </button>

            <!-- LOGO PHÚC HƯNG POOL & SAUNA -->
            <a href="#" class="flex items-center gap-2.5 group shrink-0">
                <!-- Biểu tượng Logo SVG kết hợp Sóng nước Bể bơi & Gỗ/Lá Xông hơi -->
                <div class="w-12 h-12 sm:w-14 sm:h-14 rounded-xl bg-gradient-to-br from-primary-dark via-primary to-sky-500 flex items-center justify-center shadow-md border-2 border-amber-400/80 relative overflow-hidden shrink-0">
                    <svg class="w-9 h-9 text-white" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <!-- Hơi ấm Sauna phía trên -->
                        <path d="M22 14C22 10 26 9 26 5" stroke="#fbbf24" stroke-width="3.5" stroke-linecap="round"/>
                        <path d="M32 16C32 11 36 10 36 5" stroke="#fbbf24" stroke-width="3.5" stroke-linecap="round"/>
                        <path d="M42 14C42 10 46 9 46 5" stroke="#fbbf24" stroke-width="3.5" stroke-linecap="round"/>
                        <!-- Khung nhà gỗ Sauna -->
                        <path d="M12 30L32 17L52 30" stroke="#fbbf24" stroke-width="4" stroke-linecap="round" stroke-linejoin="round"/>
                        <!-- Chữ PH -->
                        <text x="32" y="42" text-anchor="middle" fill="#ffffff" font-size="16" font-weight="900" font-family="Inter, sans-serif">PH</text>
                        <!-- Sóng nước bể bơi phía dưới -->
                        <path d="M8 49C14 45 20 53 26 49C32 45 38 53 44 49C50 45 54 51 56 49" stroke="#38bdf8" stroke-width="4" stroke-linecap="round"/>
                        <path d="M12 56C18 52 24 60 30 56C36 52 42 60 48 56" stroke="#bae6fd" stroke-width="3" stroke-linecap="round"/>
                    </svg>
                </div>
                <div>
                    <div class="text-base sm:text-xl font-extrabold tracking-tight text-primary-dark leading-none">
                        PHÚC HƯNG <span class="text-sauna">POOL & SAUNA</span>
                    </div>
                    <div class="text-[11px] sm:text-xs font-semibold text-slate-600 mt-1">
                        phuchungpool.com | Bể Bơi & Xông Hơi Đà Nẵng
                    </div>
                </div>
            </a>

            <!-- Ô TÌM KIẾM SẢN PHẨM (Chuẩn Flatsome Search Form) -->
            <div class="hidden md:flex flex-1 max-w-md mx-4">
                <div class="relative w-full flex">
                    <input 
                        type="text" 
                        id="searchInput"
                        oninput="handleSearchProducts(this.value)"
                        placeholder="Tìm máy xông hơi, bình lọc bể bơi, phòng xông hơi..." 
                        class="w-full pl-4 pr-10 py-2.5 text-sm rounded-l-lg border border-slate-300 focus:outline-none focus:border-primary"
                    >
                    <button onclick="document.getElementById('san-pham').scrollIntoView({behavior:'smooth'})" class="bg-primary hover:bg-primary-dark text-white px-4 rounded-r-lg transition" aria-label="Tìm kiếm">
                        <i class="fa-solid fa-magnifying-glass"></i>
                    </button>
                </div>
            </div>

            <!-- HOTLINE & NÚT BÁO GIÁ MIỄN PHÍ -->
            <div class="flex items-center gap-2.5">
                <a href="tel:0934722773" class="hidden sm:flex items-center gap-2.5 bg-amber-50 border border-amber-200 px-3.5 py-1.5 rounded-xl hover:bg-amber-100 transition">
                    <div class="w-9 h-9 rounded-full bg-sauna text-white flex items-center justify-center animate-ring">
                        <i class="fa-solid fa-phone"></i>
                    </div>
                    <div class="leading-tight">
                        <span class="block text-[11px] text-slate-500 font-medium">Tư vấn & Báo giá 24/7</span>
                        <span class="block text-sm font-extrabold text-red-600">0934.722.773</span>
                    </div>
                </a>

                <a href="#lien-he-bao-gia" class="bg-primary hover:bg-primary-dark text-white text-xs sm:text-sm font-bold px-3.5 py-2.5 rounded-xl shadow-sm transition flex items-center gap-1.5">
                    <i class="fa-solid fa-calculator"></i>
                    <span class="hidden sm:inline">Báo Giá Miễn Phí</span>
                    <span class="sm:hidden">Báo Giá</span>
                </a>
            </div>
        </div>

        <!-- 3. FLATSOME HEADER BOTTOM NAVIGATION (Desktop) -->
        <nav class="hidden lg:block bg-primary text-white border-t border-primary-dark">
            <div class="max-w-7xl mx-auto px-4">
                <ul class="flex items-center text-[13px] font-bold uppercase tracking-wide">
                    <li>
                        <a href="#" class="block py-3 px-4 bg-sauna text-white"><i class="fa-solid fa-house mr-1.5"></i>Trang Chủ</a>
                    </li>
                    <li>
                        <a href="#gioi-thieu" class="block py-3 px-4 hover:bg-primary-dark transition">Giới Thiệu</a>
                    </li>
                    <!-- Dropdown Thiết Bị Bể Bơi (Chuẩn Hanteco) -->
                    <li class="relative group">
                        <a href="#san-pham" onclick="filterProducts('thiet-bi-be-boi')" class="flex items-center gap-1.5 py-3 px-4 hover:bg-primary-dark transition">
                            <span>Thiết Bị Bể Bơi</span>
                            <i class="fa-solid fa-chevron-down text-[10px]"></i>
                        </a>
                        <ul class="absolute left-0 top-full w-64 bg-white text-slate-800 shadow-xl rounded-b-lg border border-slate-100 py-2 hidden group-hover:block z-50 capitalize font-semibold text-sm">
                            <li><a href="#san-pham" onclick="filterProducts('thiet-bi-be-boi')" class="block px-4 py-2 hover:bg-sky-50 hover:text-primary">Máy Bơm Bể Bơi Waterco / Emaux / Kripsol</a></li>
                            <li><a href="#san-pham" onclick="filterProducts('thiet-bi-be-boi')" class="block px-4 py-2 hover:bg-sky-50 hover:text-primary">Bình Lọc Bể Bơi & Cột Lọc Cartridge</a></li>
                            <li><a href="#san-pham" onclick="filterProducts('thiet-bi-be-boi')" class="block px-4 py-2 hover:bg-sky-50 hover:text-primary">Lọc Bể Bơi Thông Minh & Máy Cấp Nhiệt</a></li>
                            <li><a href="#san-pham" onclick="filterProducts('thiet-bi-be-boi')" class="block px-4 py-2 hover:bg-sky-50 hover:text-primary">Đèn Bể Bơi, Thang Inox & Phụ Kiện</a></li>
                            <li><a href="#san-pham" onclick="filterProducts('thiet-bi-be-boi')" class="block px-4 py-2 hover:bg-sky-50 hover:text-primary">Thiết Bị Vệ Sinh & Robot Bể Bơi</a></li>
                            <li><a href="#san-pham" onclick="filterProducts('thiet-bi-be-boi')" class="block px-4 py-2 hover:bg-sky-50 hover:text-primary">Điện Phân Muối - Đèn UV Khử Trùng</a></li>
                        </ul>
                    </li>
                    <!-- Dropdown Thiết Bị Xông Hơi (Chuẩn Hanteco) -->
                    <li class="relative group">
                        <a href="#san-pham" onclick="filterProducts('thiet-bi-xong-hoi')" class="flex items-center gap-1.5 py-3 px-4 hover:bg-primary-dark transition">
                            <span>Thiết Bị Xông Hơi</span>
                            <i class="fa-solid fa-chevron-down text-[10px]"></i>
                        </a>
                        <ul class="absolute left-0 top-full w-64 bg-white text-slate-800 shadow-xl rounded-b-lg border border-slate-100 py-2 hidden group-hover:block z-50 capitalize font-semibold text-sm">
                            <li><a href="#san-pham" onclick="filterProducts('thiet-bi-xong-hoi')" class="block px-4 py-2 hover:bg-sky-50 hover:text-primary">Máy Xông Hơi Khô SAWO / Harvia / Coasts</a></li>
                            <li><a href="#san-pham" onclick="filterProducts('thiet-bi-xong-hoi')" class="block px-4 py-2 hover:bg-sky-50 hover:text-primary">Máy Xông Hơi Ướt SAWO / Harvia / Coasts</a></li>
                            <li><a href="#san-pham" onclick="filterProducts('thiet-bi-xong-hoi')" class="block px-4 py-2 hover:bg-sky-50 hover:text-primary">Máy Xông Hơi Amazon / Dolomiti&F</a></li>
                            <li><a href="#san-pham" onclick="filterProducts('thiet-bi-xong-hoi')" class="block px-4 py-2 hover:bg-sky-50 hover:text-primary">Phòng Xông Hơi Khô & Phòng Xông Ướt</a></li>
                            <li><a href="#san-pham" onclick="filterProducts('thiet-bi-xong-hoi')" class="block px-4 py-2 hover:bg-sky-50 hover:text-primary">Phụ Kiện Phòng Xông (Xô Gáo, Đồng Hồ, Ghế)</a></li>
                        </ul>
                    </li>
                    <!-- Dropdown Bể Sục Jacuzzi & Gạch Mosaic -->
                    <li class="relative group">
                        <a href="#san-pham" onclick="filterProducts('be-suc-jacuzzi')" class="flex items-center gap-1.5 py-3 px-4 hover:bg-primary-dark transition">
                            <span>Jacuzzi & Gạch Mosaic</span>
                            <i class="fa-solid fa-chevron-down text-[10px]"></i>
                        </a>
                        <ul class="absolute left-0 top-full w-64 bg-white text-slate-800 shadow-xl rounded-b-lg border border-slate-100 py-2 hidden group-hover:block z-50 capitalize font-semibold text-sm">
                            <li><a href="#san-pham" onclick="filterProducts('be-suc-jacuzzi')" class="block px-4 py-2 hover:bg-sky-50 hover:text-primary">Bể Sục Jacuzzi - Bồn Tắm Massage</a></li>
                            <li><a href="#san-pham" onclick="filterProducts('be-suc-jacuzzi')" class="block px-4 py-2 hover:bg-sky-50 hover:text-primary">Bồn Ngâm Thủy Trị Liệu Cao Cấp</a></li>
                            <li><a href="#san-pham" onclick="filterProducts('gach-mosaic')" class="block px-4 py-2 hover:bg-sky-50 hover:text-primary">Gạch Mosaic Thủy Tinh & Gốm Bể Bơi</a></li>
                            <li><a href="#san-pham" onclick="filterProducts('gach-mosaic')" class="block px-4 py-2 hover:bg-sky-50 hover:text-primary">Gạch Mosaic Vảy Cá, Chiếc Lá & Keo Dán</a></li>
                        </ul>
                    </li>
                    <!-- Dropdown Hóa Chất, Cứu Hộ & Ngoại Thất -->
                    <li class="relative group">
                        <a href="#san-pham" onclick="filterProducts('hoa-chat-cuu-ho')" class="flex items-center gap-1.5 py-3 px-4 hover:bg-primary-dark transition">
                            <span>Hóa Chất & Ngoại Thất</span>
                            <i class="fa-solid fa-chevron-down text-[10px]"></i>
                        </a>
                        <ul class="absolute left-0 top-full w-64 bg-white text-slate-800 shadow-xl rounded-b-lg border border-slate-100 py-2 hidden group-hover:block z-50 capitalize font-semibold text-sm">
                            <li><a href="#san-pham" onclick="filterProducts('hoa-chat-cuu-ho')" class="block px-4 py-2 hover:bg-sky-50 hover:text-primary">Hóa Chất Xử Lý Nước Bể Bơi (Chlorine, TCCA)</a></li>
                            <li><a href="#san-pham" onclick="filterProducts('hoa-chat-cuu-ho')" class="block px-4 py-2 hover:bg-sky-50 hover:text-primary">Thiết Bị Cứu Hộ (Áo Phao, Phao, Ghế Cứu Hộ)</a></li>
                            <li><a href="#san-pham" onclick="filterProducts('acrylic-ngoai-that')" class="block px-4 py-2 hover:bg-sky-50 hover:text-primary">Vách Kính Acrylic Hồ Bơi & Thủy Cung</a></li>
                            <li><a href="#san-pham" onclick="filterProducts('acrylic-ngoai-that')" class="block px-4 py-2 hover:bg-sky-50 hover:text-primary">Cây Sen Tắm Ngoài Trời & Công Viên Nước</a></li>
                        </ul>
                    </li>
                    <li>
                        <a href="#cong-trinh" class="block py-3 px-4 hover:bg-primary-dark transition">Dự Án</a>
                    </li>
                    <li>
                        <a href="#tin-tuc" class="block py-3 px-4 hover:bg-primary-dark transition">Tin Tức</a>
                    </li>
                    <li>
                        <a href="#lien-he-bao-gia" class="block py-3 px-4 hover:bg-primary-dark transition">Liên Hệ</a>
                    </li>
                </ul>
            </div>
        </nav>
    </header>

    <!-- =====================================================================
         MENU DI ĐỘNG OFF-CANVAS (Chuẩn Mobile Menu của Flatsome)
         ===================================================================== -->
    <div id="mobileMenuOverlay" class="fixed inset-0 bg-slate-900/60 z-50 hidden" onclick="toggleMobileMenu()">
        <div class="w-80 max-w-[85vw] bg-white h-full overflow-y-auto p-5 flex flex-col justify-between" onclick="event.stopPropagation()">
            <div>
                <div class="flex items-center justify-between pb-4 border-b border-slate-200">
                    <span class="font-extrabold text-primary-dark text-base">PHÚC HƯNG POOL & SAUNA</span>
                    <button onclick="toggleMobileMenu()" class="w-8 h-8 rounded-full bg-slate-100 text-slate-600 flex items-center justify-center">
                        <i class="fa-solid fa-xmark"></i>
                    </button>
                </div>

                <!-- Tìm kiếm trên Mobile -->
                <div class="my-4">
                    <input 
                        type="text" 
                        oninput="handleSearchProducts(this.value)"
                        placeholder="Tìm sản phẩm..." 
                        class="w-full px-3.5 py-2 text-sm rounded-lg border border-slate-300"
                    >
                </div>

                <!-- Danh sách link điều hướng (Chuẩn danh mục Hanteco) -->
                <ul class="divide-y divide-slate-100 text-sm font-bold text-slate-700">
                    <li><a href="#" onclick="toggleMobileMenu()" class="block py-3 text-primary">Trang Chủ</a></li>
                    <li><a href="#gioi-thieu" onclick="toggleMobileMenu()" class="block py-3">Giới Thiệu Công Ty</a></li>
                    <li><a href="#san-pham" onclick="filterProducts('thiet-bi-be-boi'); toggleMobileMenu()" class="block py-3">Thiết Bị Bể Bơi Nhập Khẩu</a></li>
                    <li><a href="#san-pham" onclick="filterProducts('thiet-bi-xong-hoi'); toggleMobileMenu()" class="block py-3">Thiết Bị Xông Hơi Khô & Ướt</a></li>
                    <li><a href="#san-pham" onclick="filterProducts('be-suc-jacuzzi'); toggleMobileMenu()" class="block py-3">Bể Sục Jacuzzi - Bồn Tắm</a></li>
                    <li><a href="#san-pham" onclick="filterProducts('gach-mosaic'); toggleMobileMenu()" class="block py-3">Gạch Mosaic Ốp Bể Bơi</a></li>
                    <li><a href="#san-pham" onclick="filterProducts('hoa-chat-cuu-ho'); toggleMobileMenu()" class="block py-3">Hóa Chất & Thiết Bị Cứu Hộ</a></li>
                    <li><a href="#san-pham" onclick="filterProducts('acrylic-ngoai-that'); toggleMobileMenu()" class="block py-3">Vách Acrylic & Ngoại Thất Hồ Bơi</a></li>
                    <li><a href="#cong-trinh" onclick="toggleMobileMenu()" class="block py-3">Dự Án Tiêu Biểu</a></li>
                    <li><a href="#tin-tuc" onclick="toggleMobileMenu()" class="block py-3">Tin Tức & Kiến Thức</a></li>
                    <li><a href="#lien-he-bao-gia" onclick="toggleMobileMenu()" class="block py-3">Liên Hệ Nhận Báo Giá</a></li>
                </ul>
            </div>

            <div class="pt-4 border-t border-slate-200 text-xs text-slate-600 space-y-2">
                <p class="font-bold text-slate-900">CÔNG TY TNHH XD & CN PHÚC HƯNG</p>
                <p><i class="fa-solid fa-location-dot text-primary mr-1.5"></i> 408 Văn Tiến Dũng, P. Hòa Xuân, Đà Nẵng</p>
                <p><i class="fa-solid fa-phone text-red-600 mr-1.5"></i> Hotline/Zalo: <a href="tel:0934722773" class="font-bold text-red-600">0934.722.773</a></p>
            </div>
        </div>
    </div>

    <!-- =====================================================================
         SECTION 1: BANNER CHÍNH (TÁI HIỆN ĐÚNG ẢNH BÌA FACEBOOK PHÚC HƯNG POOL SAUNA)
         ===================================================================== -->
    <section class="bg-[#f3ead8] border-b border-amber-200/80 py-5 sm:py-8">
        <div class="max-w-7xl mx-auto px-3 sm:px-4">
            <!-- Khung Header Banner giống hệt ảnh Facebook khách gửi -->
            <div class="text-center mb-5 sm:mb-6 px-2">
                <h1 class="text-xl sm:text-3xl lg:text-4xl font-extrabold text-[#1e1b4b] tracking-wide uppercase leading-tight">
                    CÔNG TY TNHH XÂY DỰNG VÀ CÔNG NGHỆ PHÚC HƯNG
                </h1>
                <p class="text-sm sm:text-xl font-bold text-slate-800 mt-2">
                    Chuyên thiết bị bể bơi, phòng xông hơi Quảng Nam - Đà Nẵng
                </p>
                <div class="inline-block bg-red-600 text-white font-extrabold text-xs sm:text-base px-4 py-1.5 rounded-full shadow-sm mt-2.5 uppercase tracking-wide">
                    "HOÀN TOÀN MIỄN PHÍ" : THIẾT KẾ, TƯ VẤN, BÁO GIÁ
                </div>
                <p class="text-base sm:text-xl font-extrabold text-slate-900 mt-2.5">
                    Hotline : <a href="tel:0934722773" class="text-red-600 hover:underline">0934.722.773</a> - Zalo, FB (<a href="https://www.facebook.com/phuchungpoolsauna/" target="_blank" rel="noopener noreferrer" class="text-primary hover:underline">fb.com/phuchungpoolsauna</a>)
                </p>
            </div>

            <!-- 3 Cột Hình Ảnh Chủ Lực giống đúng bố cục Banner gốc trên Facebook -->
            <div class="grid grid-cols-1 md:grid-cols-3 gap-3 sm:gap-4 bg-white p-2.5 sm:p-3 rounded-2xl shadow-lg border border-amber-200">
                
                <!-- Ảnh 1: Bể bơi Villa / Gia đình -->
                <div class="relative group overflow-hidden rounded-xl min-h-[260px] sm:min-h-[320px] flex flex-col justify-between p-4 sm:p-5 text-white">
                    <img 
                        src="https://images.unsplash.com/photo-1576013551627-0cc20b96c2a7?auto=format&fit=crop&w=900&q=80" 
                        onerror="this.src='https://placehold.co/600x650/005b96/ffffff?text=Be+Boi+Phuc+Hung'"
                        alt="Thi công thiết bị bể bơi gia đình và biệt thự Đà Nẵng" 
                        class="absolute inset-0 w-full h-full object-cover group-hover:scale-105 transition duration-500 z-0"
                    >
                    <div class="absolute inset-0 bg-gradient-to-t from-slate-950/90 via-slate-900/50 to-slate-900/25 z-0"></div>
                    <div class="relative z-10">
                        <span class="inline-block bg-sky-500 text-white text-[11px] font-extrabold px-3 py-1 rounded-md shadow-md">HẠNG MỤC 01</span>
                    </div>
                    <div class="relative z-10 mt-6 pt-2">
                        <h2 class="text-lg sm:text-xl font-extrabold text-white leading-snug m-0">THIẾT KẾ & THI CÔNG BỂ BƠI</h2>
                        <p class="text-xs text-slate-200 mt-1.5 leading-relaxed">Cung cấp bình lọc cát, máy bơm, đèn âm nước, điện phân muối & hóa chất bể bơi chính hãng.</p>
                        <a href="#san-pham" onclick="filterProducts('thiet-bi-be-boi')" class="mt-3 inline-flex items-center gap-1.5 text-xs font-bold text-amber-300 hover:text-amber-200">
                            <span>Xem thiết bị bể bơi</span> <i class="fa-solid fa-arrow-right"></i>
                        </a>
                    </div>
                </div>

                <!-- Ảnh 2: Phòng xông hơi khô gỗ thông (Sauna) -->
                <div class="relative group overflow-hidden rounded-xl min-h-[260px] sm:min-h-[320px] flex flex-col justify-between p-4 sm:p-5 text-white">
                    <img 
                        src="https://images.unsplash.com/photo-1540555700478-4be289fbecef?auto=format&fit=crop&w=900&q=80" 
                        onerror="this.src='https://placehold.co/600x650/9c5d16/ffffff?text=Phong+Xong+Hoi+Kho'"
                        alt="Thi công phòng xông hơi khô gỗ thông Phần Lan Đà Nẵng" 
                        class="absolute inset-0 w-full h-full object-cover group-hover:scale-105 transition duration-500 z-0"
                    >
                    <div class="absolute inset-0 bg-gradient-to-t from-slate-950/90 via-slate-900/50 to-slate-900/25 z-0"></div>
                    <div class="relative z-10">
                        <span class="inline-block bg-sauna text-white text-[11px] font-extrabold px-3 py-1 rounded-md shadow-md">HẠNG MỤC 02</span>
                    </div>
                    <div class="relative z-10 mt-6 pt-2">
                        <h2 class="text-lg sm:text-xl font-extrabold text-white leading-snug m-0">PHÒNG XÔNG HƠI KHÔ (SAUNA)</h2>
                        <p class="text-xs text-slate-200 mt-1.5 leading-relaxed">Gỗ thông Phần Lan, Tuyết Tùng nhập khẩu kết hợp đá muối Himalaya & máy Harvia, Sawo, Coasts.</p>
                        <a href="#san-pham" onclick="filterProducts('thiet-bi-xong-hoi')" class="mt-3 inline-flex items-center gap-1.5 text-xs font-bold text-amber-300 hover:text-amber-200">
                            <span>Xem thiết bị xông hơi</span> <i class="fa-solid fa-arrow-right"></i>
                        </a>
                    </div>
                </div>

                <!-- Ảnh 3: Phòng xông hơi ướt & khô kết hợp (Steam + Sauna) -->
                <div class="relative group overflow-hidden rounded-xl min-h-[260px] sm:min-h-[320px] flex flex-col justify-between p-4 sm:p-5 text-white">
                    <img 
                        src="https://images.unsplash.com/photo-1584622650111-993a426fbf0a?auto=format&fit=crop&w=900&q=80" 
                        onerror="this.src='https://placehold.co/600x650/0f766e/ffffff?text=Phong+Xong+Hoi+Uot+Steam'"
                        alt="Thi công phòng xông hơi ướt kết hợp khô vách kính Đà Nẵng" 
                        class="absolute inset-0 w-full h-full object-cover group-hover:scale-105 transition duration-500 z-0"
                    >
                    <div class="absolute inset-0 bg-gradient-to-t from-slate-950/90 via-slate-900/50 to-slate-900/25 z-0"></div>
                    <div class="relative z-10">
                        <span class="inline-block bg-teal-600 text-white text-[11px] font-extrabold px-3 py-1 rounded-md shadow-md">HẠNG MỤC 03</span>
                    </div>
                    <div class="relative z-10 mt-6 pt-2">
                        <h2 class="text-lg sm:text-xl font-extrabold text-white leading-snug m-0">PHÒNG XÔNG HƠI ƯỚT & JACUZZI</h2>
                        <p class="text-xs text-slate-200 mt-1.5 leading-relaxed">Thi công phòng Steam vách kính cường lực, bồn sục Jacuzzi, ốp gạch Mosaic cao cấp cho Gia đình, Spa, Hotel.</p>
                        <a href="#san-pham" onclick="filterProducts('be-suc-jacuzzi')" class="mt-3 inline-flex items-center gap-1.5 text-xs font-bold text-amber-300 hover:text-amber-200">
                            <span>Xem bồn sục & xông ướt</span> <i class="fa-solid fa-arrow-right"></i>
                        </a>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- =====================================================================
         SECTION 2: 04 BƯỚC CHUYÊN NGHIỆP TRONG QUY TRÌNH CỦA PHÚC HƯNG
         ===================================================================== -->
    <section class="py-10 bg-white border-b border-slate-200">
        <div class="max-w-7xl mx-auto px-3 sm:px-4">
            <div class="section-title-container">
                <h2 class="section-title-main text-lg sm:text-2xl">
                    <b></b>
                    <span>04 BƯỚC CHUYÊN NGHIỆP TRONG QUY TRÌNH CỦA PHÚC HƯNG</span>
                    <b></b>
                </h2>
                <p class="text-center text-xs sm:text-sm text-slate-500 mt-1">
                    Cam kết hoàn toàn miễn phí khảo sát, tư vấn, thiết kế và lập bảng báo giá tận nơi tại Đà Nẵng - Quảng Nam
                </p>
            </div>

            <!-- Chia 2 cột trên điện thoại, 4 cột trên máy tính -->
            <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-6 mt-6">
                <!-- Bước 01 -->
                <div class="bg-slate-50 rounded-xl p-4 sm:p-5 border border-slate-200/80 hover:border-primary transition relative">
                    <div class="flex items-center justify-between mb-3">
                        <span class="text-2xl sm:text-3xl font-black text-primary/20">01</span>
                        <div class="w-10 h-10 rounded-lg bg-primary text-white flex items-center justify-center">
                            <i class="fa-solid fa-comments"></i>
                        </div>
                    </div>
                    <h3 class="font-bold text-sm sm:text-base text-slate-900 mb-1.5">Khảo sát & Tư vấn</h3>
                    <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">
                        Trực tiếp khảo sát mặt bằng thực tế, trao đổi ý tưởng, tư vấn vật liệu và thiết bị phù hợp ngân sách của bạn.
                    </p>
                </div>

                <!-- Bước 02 -->
                <div class="bg-slate-50 rounded-xl p-4 sm:p-5 border border-slate-200/80 hover:border-primary transition relative">
                    <div class="flex items-center justify-between mb-3">
                        <span class="text-2xl sm:text-3xl font-black text-primary/20">02</span>
                        <div class="w-10 h-10 rounded-lg bg-sauna text-white flex items-center justify-center">
                            <i class="fa-solid fa-compass-drafting"></i>
                        </div>
                    </div>
                    <h3 class="font-bold text-sm sm:text-base text-slate-900 mb-1.5">Thiết kế & Báo giá 0đ</h3>
                    <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">
                        Lên bản vẽ thiết kế chi tiết bể bơi / phòng xông hơi và gửi báo giá trọn gói hoàn toàn miễn phí, không phát sinh.
                    </p>
                </div>

                <!-- Bước 03 -->
                <div class="bg-slate-50 rounded-xl p-4 sm:p-5 border border-slate-200/80 hover:border-primary transition relative">
                    <div class="flex items-center justify-between mb-3">
                        <span class="text-2xl sm:text-3xl font-black text-primary/20">03</span>
                        <div class="w-10 h-10 rounded-lg bg-primary text-white flex items-center justify-center">
                            <i class="fa-solid fa-screwdriver-wrench"></i>
                        </div>
                    </div>
                    <h3 class="font-bold text-sm sm:text-base text-slate-900 mb-1.5">Thi công & Giám sát</h3>
                    <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">
                        Đội ngũ kỹ thuật viên Phúc Hưng thi công lắp đặt chuẩn kỹ thuật, thẩm mỹ cao và đảm bảo tuyệt đối an toàn điện nước.
                    </p>
                </div>

                <!-- Bước 04 -->
                <div class="bg-slate-50 rounded-xl p-4 sm:p-5 border border-slate-200/80 hover:border-primary transition relative">
                    <div class="flex items-center justify-between mb-3">
                        <span class="text-2xl sm:text-3xl font-black text-primary/20">04</span>
                        <div class="w-10 h-10 rounded-lg bg-emerald-600 text-white flex items-center justify-center">
                            <i class="fa-solid fa-shield-halved"></i>
                        </div>
                    </div>
                    <h3 class="font-bold text-sm sm:text-base text-slate-900 mb-1.5">Bàn giao & Bảo hành</h3>
                    <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">
                        Vận hành thử nghiệm, hướng dẫn khách hàng sử dụng chi tiết, bàn giao công trình và bảo hành tận nơi nhanh chóng.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- =====================================================================
         SECTION 3: DANH MỤC SẢN PHẨM CHÍNH (TỐI ƯU 2 CỘT TRÊN ĐIỆN THOẠI, 4 CỘT TRÊN MÁY TÍNH)
         ===================================================================== -->
    <section id="san-pham" class="py-10 sm:py-12 bg-slate-50">
        <div class="max-w-7xl mx-auto px-3 sm:px-4">
            <!-- Tiêu đề chuẩn Flatsome -->
            <div class="section-title-container">
                <h2 class="section-title-main text-lg sm:text-2xl">
                    <b></b>
                    <span>DANH MỤC SẢN PHẨM & THIẾT BỊ NHẬP KHẨU</span>
                    <b></b>
                </h2>
                <p class="text-center text-xs sm:text-sm text-slate-600 mt-1">
                    Cung cấp Thiết bị bể bơi, Thiết bị xông hơi, Bể sục Jacuzzi, Gạch Mosaic, Hóa chất & Thiết bị cứu hộ chính hãng tại Đà Nẵng - Quảng Nam
                </p>
            </div>

            <!-- Thanh lọc Tab Danh mục chuẩn theo Hanteco.vn -->
            <div class="flex items-center justify-start lg:justify-center gap-2 overflow-x-auto no-scrollbar pb-3 mb-6">
                <button onclick="filterProducts('all')" data-cat="all" class="cat-tab-btn shrink-0 px-4 py-2 rounded-full text-xs sm:text-sm font-bold bg-primary text-white shadow-sm transition">
                    Tất Cả Sản Phẩm
                </button>
                <button onclick="filterProducts('thiet-bi-be-boi')" data-cat="thiet-bi-be-boi" class="cat-tab-btn shrink-0 px-4 py-2 rounded-full text-xs sm:text-sm font-bold bg-white text-slate-700 hover:bg-slate-100 border border-slate-200 transition">
                    Thiết Bị Bể Bơi
                </button>
                <button onclick="filterProducts('thiet-bi-xong-hoi')" data-cat="thiet-bi-xong-hoi" class="cat-tab-btn shrink-0 px-4 py-2 rounded-full text-xs sm:text-sm font-bold bg-white text-slate-700 hover:bg-slate-100 border border-slate-200 transition">
                    Thiết Bị Xông Hơi
                </button>
                <button onclick="filterProducts('be-suc-jacuzzi')" data-cat="be-suc-jacuzzi" class="cat-tab-btn shrink-0 px-4 py-2 rounded-full text-xs sm:text-sm font-bold bg-white text-slate-700 hover:bg-slate-100 border border-slate-200 transition">
                    Bể Sục Jacuzzi - Bồn Tắm
                </button>
                <button onclick="filterProducts('gach-mosaic')" data-cat="gach-mosaic" class="cat-tab-btn shrink-0 px-4 py-2 rounded-full text-xs sm:text-sm font-bold bg-white text-slate-700 hover:bg-slate-100 border border-slate-200 transition">
                    Gạch Mosaic
                </button>
                <button onclick="filterProducts('hoa-chat-cuu-ho')" data-cat="hoa-chat-cuu-ho" class="cat-tab-btn shrink-0 px-4 py-2 rounded-full text-xs sm:text-sm font-bold bg-white text-slate-700 hover:bg-slate-100 border border-slate-200 transition">
                    Hóa Chất & Cứu Hộ
                </button>
                <button onclick="filterProducts('acrylic-ngoai-that')" data-cat="acrylic-ngoai-that" class="cat-tab-btn shrink-0 px-4 py-2 rounded-full text-xs sm:text-sm font-bold bg-white text-slate-700 hover:bg-slate-100 border border-slate-200 transition">
                    Vách Acrylic & Ngoại Thất
                </button>
            </div>

            <!-- LƯỚI SẢN PHẨM: 2 CỘT TRÊN ĐIỆN THOẠI (grid-cols-2), 4 CỘT TRÊN MÁY TÍNH (lg:grid-cols-4) -->
            <div id="productGrid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-3 sm:gap-5">
                <!-- Danh sách sản phẩm được render tự động từ JS bên dưới -->
            </div>

            <!-- Banner kêu gọi tư vấn miễn phí dưới danh sách sản phẩm -->
            <div class="mt-8 bg-gradient-to-r from-primary-dark via-primary to-sky-700 rounded-2xl p-5 sm:p-7 text-white flex flex-col md:flex-row items-center justify-between gap-4 shadow-md">
                <div>
                    <span class="bg-amber-400 text-slate-950 text-[11px] font-extrabold px-2.5 py-0.5 rounded uppercase">Ưu đãi đặc biệt tại Quảng Nam - Đà Nẵng</span>
                    <h3 class="text-lg sm:text-2xl font-extrabold mt-1.5">MIỄN PHÍ 100% KHẢO SÁT, THIẾT KẾ 3D & BÁO GIÁ TẬN NƠI</h3>
                    <p class="text-xs sm:text-sm text-sky-100 mt-1">Gọi ngay hoặc nhắn Zalo để kỹ thuật trưởng Phúc Hưng tư vấn cấu hình phù hợp nhất!</p>
                </div>
                <div class="flex flex-wrap items-center gap-3 shrink-0">
                    <a href="tel:0934722773" class="bg-amber-400 hover:bg-amber-300 text-slate-950 font-extrabold text-sm px-5 py-3 rounded-xl shadow transition flex items-center gap-2">
                        <i class="fa-solid fa-phone-volume"></i>
                        <span>0934.722.773</span>
                    </a>
                    <a href="https://zalo.me/0934722773" target="_blank" rel="noopener noreferrer" class="bg-white/15 hover:bg-white/25 border border-white/30 text-white font-bold text-sm px-4 py-3 rounded-xl transition flex items-center gap-2">
                        <i class="fa-solid fa-comment-dots"></i>
                        <span>Chat Zalo Ngay</span>
                    </a>
                </div>
            </div>
        </div>
    </section>

    <!-- =====================================================================
         SECTION 4: CÔNG TRÌNH TIÊU BIỂU ĐÃ THI CÔNG (Giống mẫu dinhgosauna.vn)
         ===================================================================== -->
    <section id="cong-trinh" class="py-10 sm:py-12 bg-white border-t border-slate-200">
        <div class="max-w-7xl mx-auto px-3 sm:px-4">
            <div class="section-title-container">
                <h2 class="section-title-main text-lg sm:text-2xl">
                    <b></b>
                    <span>CÔNG TRÌNH TIÊU BIỂU TẠI ĐÀ NẴNG - QUẢNG NAM</span>
                    <b></b>
                </h2>
                <p class="text-center text-xs sm:text-sm text-slate-500 mt-1">
                    Hình ảnh thực tế các dự án Bể bơi & Phòng xông hơi do Công ty TNHH Xây dựng và Công nghệ Phúc Hưng thi công bàn giao
                </p>
            </div>

            <!-- Chia 2 cột trên điện thoại, 3 cột trên máy tính -->
            <div id="projectGrid" class="grid grid-cols-2 lg:grid-cols-3 gap-3 sm:gap-6 mt-6">
                <!-- Render từ mảng dữ liệu Dự án thực tế bên dưới -->
            </div>
        </div>
    </section>

    <!-- =====================================================================
         SECTION 5: TẠI SAO CHỌN CHÚNG TÔI & GIỚI THIỆU PHÚC HƯNG
         ===================================================================== -->
    <section id="gioi-thieu" class="py-10 sm:py-14 bg-slate-100 border-t border-slate-200">
        <div class="max-w-7xl mx-auto px-3 sm:px-4">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 sm:gap-8 items-center">
                
                <!-- Cột Trái (7/12): Tại sao chọn Phúc Hưng (4 Ô đánh số 01-04 giống dinhgosauna.vn) -->
                <div class="lg:col-span-7">
                    <span class="text-xs font-extrabold uppercase tracking-wider text-sauna">GIẢI PHÁP CHO SỨC KHỎE & THƯ GIÃN</span>
                    <h2 class="text-xl sm:text-2xl font-extrabold text-primary-dark mt-1 mb-5">
                        TẠI SAO KHÁCH HÀNG TIN CHỌN PHÚC HƯNG POOL & SAUNA?
                    </h2>

                    <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                        <!-- Lý do 01 -->
                        <div class="bg-white p-4 sm:p-5 rounded-xl shadow-sm border border-slate-200/80">
                            <div class="text-2xl font-black text-sauna mb-1">01. Vật tư chính hãng</div>
                            <h3 class="font-bold text-slate-900 text-sm mb-1.5">Chất lượng bền bỉ vượt trội</h3>
                            <p class="text-xs text-slate-600 leading-relaxed">
                                100% gỗ thông Phần Lan, Tuyết Tùng nhập khẩu, máy xông hơi Harvia, Sawo, Coast và thiết bị bể bơi Emaux, Kripsol có CO/CQ đầy đủ.
                            </p>
                        </div>

                        <!-- Lý do 02 -->
                        <div class="bg-white p-4 sm:p-5 rounded-xl shadow-sm border border-slate-200/80">
                            <div class="text-2xl font-black text-primary mb-1">02. Thi công chuẩn mực</div>
                            <h3 class="font-bold text-slate-900 text-sm mb-1.5">Đội ngũ kỹ thuật chuyên sâu</h3>
                            <p class="text-xs text-slate-600 leading-relaxed">
                                Trực tiếp khảo sát và thi công trọn gói tại Đà Nẵng - Quảng Nam, đảm bảo độ kín nhiệt, chống thấm và vận hành êm ái, an toàn.
                            </p>
                        </div>

                        <!-- Lý do 03 -->
                        <div class="bg-white p-4 sm:p-5 rounded-xl shadow-sm border border-slate-200/80">
                            <div class="text-2xl font-black text-emerald-600 mb-1">03. Miễn phí 100%</div>
                            <h3 class="font-bold text-slate-900 text-sm mb-1.5">Tư vấn, thiết kế & báo giá</h3>
                            <p class="text-xs text-slate-600 leading-relaxed">
                                Hỗ trợ lên phương án kỹ thuật, bản vẽ bố trí mặt bằng và dự toán chi phí hoàn toàn miễn phí trước khi khách hàng quyết định.
                            </p>
                        </div>

                        <!-- Lý do 04 -->
                        <div class="bg-white p-4 sm:p-5 rounded-xl shadow-sm border border-slate-200/80">
                            <div class="text-2xl font-black text-red-600 mb-1">04. Giá gốc tận xưởng</div>
                            <h3 class="font-bold text-slate-900 text-sm mb-1.5">Bảo hành tận nơi nhanh chóng</h3>
                            <p class="text-xs text-slate-600 leading-relaxed">
                                Trực tiếp nhập khẩu và gia công lắp đặt không qua trung gian, tối ưu 15-25% chi phí cùng chế độ bảo hành 24/7 tại Đà Nẵng - Quảng Nam.
                            </p>
                        </div>
                    </div>
                </div>

                <!-- Cột Phải (5/12): Hộp Thông Tin Công Ty TNHH Xây Dựng Và Công Nghệ Phúc Hưng -->
                <div class="lg:col-span-5 bg-white rounded-2xl p-5 sm:p-7 shadow-md border-t-4 border-primary">
                    <div class="inline-flex items-center gap-2 bg-primary-light text-primary text-xs font-bold px-3 py-1 rounded-full mb-3">
                        <i class="fa-solid fa-building-shield"></i>
                        <span>MST: 0402102763</span>
                    </div>
                    <h3 class="text-lg sm:text-xl font-extrabold text-primary-dark leading-snug">
                        CÔNG TY TNHH XÂY DỰNG VÀ CÔNG NGHỆ PHÚC HƯNG
                    </h3>
                    <p class="text-xs font-semibold text-sauna mt-1">
                        PHUC HUNG TECHNOLOGY AND CONSTRUCTION COMPANY LIMITED
                    </p>
                    <p class="text-xs sm:text-sm text-slate-600 mt-3 leading-relaxed">
                        Với nhiều năm kinh nghiệm trong lĩnh vực thi công <strong>Thiết bị bể bơi & Phòng xông hơi khô - ướt</strong> tại khu vực Đà Nẵng, Quảng Nam và miền Trung, <strong>Phúc Hưng Pool & Sauna</strong> tự hào kiến tạo hàng trăm không gian thư giãn, chăm sóc sức khỏe chuẩn Spa ngay tại ngôi nhà, biệt thự, khách sạn và resort của quý khách hàng.
                    </p>
                    <ul class="mt-4 space-y-2 text-xs sm:text-sm text-slate-700">
                        <li class="flex items-start gap-2">
                            <i class="fa-solid fa-location-dot text-primary mt-1"></i>
                            <span><strong>Địa chỉ:</strong> 408 Văn Tiến Dũng, Phường Hòa Xuân, TP Đà Nẵng</span>
                        </li>
                        <li class="flex items-start gap-2">
                            <i class="fa-solid fa-phone-volume text-red-600 mt-1"></i>
                            <span><strong>Hotline / Zalo:</strong> <a href="tel:0934722773" class="font-extrabold text-red-600">0934.722.773</a></span>
                        </li>
                        <li class="flex items-start gap-2">
                            <i class="fa-solid fa-globe text-primary mt-1"></i>
                            <span><strong>Website:</strong> phuchungpool.com</span>
                        </li>
                        <li class="flex items-start gap-2">
                            <i class="fa-brands fa-facebook text-blue-600 mt-1"></i>
                            <span><strong>Fanpage:</strong> <a href="https://www.facebook.com/phuchungpoolsauna/" target="_blank" rel="noopener noreferrer" class="text-primary hover:underline">facebook.com/phuchungpoolsauna</a></span>
                        </li>
                    </ul>
                    <div class="mt-5 pt-4 border-t border-slate-100 flex flex-wrap gap-3">
                        <a href="tel:0934722773" class="flex-1 text-center bg-red-600 hover:bg-red-700 text-white font-bold text-xs sm:text-sm py-2.5 px-4 rounded-xl transition">
                            <i class="fa-solid fa-phone mr-1.5"></i> Gọi Ngay: 0934.722.773
                        </a>
                        <a href="https://www.facebook.com/phuchungpoolsauna/" target="_blank" rel="noopener noreferrer" class="flex-1 text-center bg-primary hover:bg-primary-dark text-white font-bold text-xs sm:text-sm py-2.5 px-4 rounded-xl transition">
                            <i class="fa-brands fa-facebook-messenger mr-1.5"></i> Nhắn Fanpage
                        </a>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- =====================================================================
         SECTION 6: TIN TỨC & KINH NGHIỆM BỂ BƠI - XÔNG HƠI
         ===================================================================== -->
    <section id="tin-tuc" class="py-10 sm:py-12 bg-white border-t border-slate-200">
        <div class="max-w-7xl mx-auto px-3 sm:px-4">
            <div class="section-title-container">
                <h2 class="section-title-main text-lg sm:text-2xl">
                    <b></b>
                    <span>TIN TỨC & CẨM NANG KỸ THUẬT</span>
                    <b></b>
                </h2>
                <p class="text-center text-xs sm:text-sm text-slate-500 mt-1">
                    Chia sẻ kinh nghiệm lựa chọn máy xông hơi, thiết kế phòng sauna và vận hành bể bơi gia đình tiết kiệm
                </p>
            </div>

            <!-- Chia 2 cột trên điện thoại, 4 cột trên máy tính -->
            <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5 mt-6">
                <!-- Bài viết 1 -->
                <article class="bg-slate-50 rounded-xl overflow-hidden border border-slate-200/80 flex flex-col">
                    <div class="relative aspect-[16/10] overflow-hidden">
                        <img src="https://images.unsplash.com/photo-1540555700478-4be289fbecef?auto=format&fit=crop&w=600&q=80" alt="Kinh nghiệm làm phòng xông hơi gia đình" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                        <div class="absolute top-2.5 left-2.5 z-10 bg-primary text-white text-[10px] font-bold px-2 py-1 rounded shadow-md text-center leading-tight">
                            <span class="block text-xs font-extrabold">18</span>Th10
                        </div>
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="font-bold text-xs sm:text-sm text-slate-900 line-clamp-2 hover:text-primary cursor-pointer" onclick="openConsultModal('Tư vấn chi phí làm phòng xông hơi gia đình')">
                                Báo Giá Thi Công Phòng Xông Hơi Gia Đình Trọn Gói Tại Đà Nẵng 2026
                            </h3>
                            <p class="text-[11px] sm:text-xs text-slate-500 mt-1.5 line-clamp-2">
                                Tổng hợp chi phí đóng phòng xông hơi khô gỗ thông Phần Lan và phòng xông hơi ướt kính cường lực theo kích thước thực tế...
                            </p>
                        </div>
                        <button onclick="openConsultModal('Tư vấn chi phí làm phòng xông hơi gia đình')" class="text-[11px] font-bold text-primary hover:underline mt-3 text-left">
                            Xem chi tiết <i class="fa-solid fa-angle-right ml-0.5"></i>
                        </button>
                    </div>
                </article>

                <!-- Bài viết 2 -->
                <article class="bg-slate-50 rounded-xl overflow-hidden border border-slate-200/80 flex flex-col">
                    <div class="relative aspect-[16/10] overflow-hidden">
                        <img src="https://images.unsplash.com/photo-1576013551627-0cc20b96c2a7?auto=format&fit=crop&w=600&q=80" alt="Chi phí xây dựng bể bơi gia đình" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                        <div class="absolute top-2.5 left-2.5 z-10 bg-primary text-white text-[10px] font-bold px-2 py-1 rounded shadow-md text-center leading-tight">
                            <span class="block text-xs font-extrabold">12</span>Th10
                        </div>
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="font-bold text-xs sm:text-sm text-slate-900 line-clamp-2 hover:text-primary cursor-pointer" onclick="openConsultModal('Tư vấn trọn bộ thiết bị bể bơi gia đình')">
                                Trọn Bộ Thiết Bị Phòng Máy Bể Bơi Gia Đình Gồm Những Gì?
                            </h3>
                            <p class="text-[11px] sm:text-xs text-slate-500 mt-1.5 line-clamp-2">
                                Hướng dẫn chọn công suất máy bơm, bình lọc cát và hệ thống điện phân muối giúp nước hồ bơi luôn trong xanh an toàn...
                            </p>
                        </div>
                        <button onclick="openConsultModal('Tư vấn trọn bộ thiết bị bể bơi gia đình')" class="text-[11px] font-bold text-primary hover:underline mt-3 text-left">
                            Xem chi tiết <i class="fa-solid fa-angle-right ml-0.5"></i>
                        </button>
                    </div>
                </article>

                <!-- Bài viết 3 -->
                <article class="bg-slate-50 rounded-xl overflow-hidden border border-slate-200/80 flex flex-col">
                    <div class="relative aspect-[16/10] overflow-hidden">
                        <img src="https://images.unsplash.com/photo-1515377905703-c4788e51af15?auto=format&fit=crop&w=600&q=80" alt="Chọn máy xông hơi loại nào tốt" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                        <div class="absolute top-2.5 left-2.5 z-10 bg-primary text-white text-[10px] font-bold px-2 py-1 rounded shadow-md text-center leading-tight">
                            <span class="block text-xs font-extrabold">05</span>Th10
                        </div>
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="font-bold text-xs sm:text-sm text-slate-900 line-clamp-2 hover:text-primary cursor-pointer" onclick="openConsultModal('Tư vấn chọn máy xông hơi Harvia, Sawo, Coast')">
                                Máy Xông Hơi Gia Đình Loại Nào Tốt? So Sánh Harvia, Sawo Và Coast
                            </h3>
                            <p class="text-[11px] sm:text-xs text-slate-500 mt-1.5 line-clamp-2">
                                Kinh nghiệm chọn công suất máy xông hơi 6KW, 9KW, 12KW phù hợp thể tích phòng và tiết kiệm điện năng nhất...
                            </p>
                        </div>
                        <button onclick="openConsultModal('Tư vấn chọn máy xông hơi Harvia, Sawo, Coast')" class="text-[11px] font-bold text-primary hover:underline mt-3 text-left">
                            Xem chi tiết <i class="fa-solid fa-angle-right ml-0.5"></i>
                        </button>
                    </div>
                </article>

                <!-- Bài viết 4 -->
                <article class="bg-slate-50 rounded-xl overflow-hidden border border-slate-200/80 flex flex-col">
                    <div class="relative aspect-[16/10] overflow-hidden">
                        <img src="https://images.unsplash.com/photo-1584622650111-993a426fbf0a?auto=format&fit=crop&w=600&q=80" alt="So sánh phòng xông hơi khô và ướt" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                        <div class="absolute top-2.5 left-2.5 z-10 bg-primary text-white text-[10px] font-bold px-2 py-1 rounded shadow-md text-center leading-tight">
                            <span class="block text-xs font-extrabold">28</span>Th09
                        </div>
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="font-bold text-xs sm:text-sm text-slate-900 line-clamp-2 hover:text-primary cursor-pointer" onclick="openConsultModal('Tư vấn phòng xông hơi khô kết hợp ướt')">
                                Nên Lắp Phòng Xông Hơi Khô Hay Ướt Cho Gia Đình & Villa Nghỉ Dưỡng?
                            </h3>
                            <p class="text-[11px] sm:text-xs text-slate-500 mt-1.5 line-clamp-2">
                                Phân tích ưu nhược điểm của xông hơi khô (Sauna) và xông hơi ướt (Steam) hoặc giải pháp phòng đôi kết hợp 2 trong 1...
                            </p>
                        </div>
                        <button onclick="openConsultModal('Tư vấn phòng xông hơi khô kết hợp ướt')" class="text-[11px] font-bold text-primary hover:underline mt-3 text-left">
                            Xem chi tiết <i class="fa-solid fa-angle-right ml-0.5"></i>
                        </button>
                    </div>
                </article>
            </div>
        </div>
    </section>

    <!-- =====================================================================
         SECTION 7: ĐĂNG KÝ NHẬN THIẾT KẾ & BÁO GIÁ MIỄN PHÍ
         ===================================================================== -->
    <section id="lien-he-bao-gia" class="py-10 sm:py-12 bg-gradient-to-br from-primary-dark to-primary text-white">
        <div class="max-w-7xl mx-auto px-3 sm:px-4">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 sm:gap-8 items-center">
                
                <!-- Thông tin cam kết -->
                <div class="lg:col-span-6 space-y-4">
                    <span class="bg-amber-400 text-slate-950 text-xs font-extrabold px-3 py-1 rounded-full uppercase">
                        HOÀN TOÀN MIỄN PHÍ: THIẾT KẾ - TƯ VẤN - BÁO GIÁ
                    </span>
                    <h2 class="text-2xl sm:text-3xl font-extrabold leading-tight">
                        NHẬN BÁO GIÁ THI CÔNG BỂ BƠI & PHÒNG XÔNG HƠI TẠI ĐÀ NẴNG - QUẢNG NAM
                    </h2>
                    <p class="text-sky-100 text-xs sm:text-sm leading-relaxed">
                        Chỉ cần để lại số điện thoại và nhu cầu của bạn, kỹ thuật viên của <strong>CÔNG TY TNHH XÂY DỰNG VÀ CÔNG NGHỆ PHÚC HƯNG</strong> sẽ liên hệ tư vấn và khảo sát tận nơi miễn phí trong vòng 30 phút.
                    </p>
                    <div class="grid grid-cols-1 sm:grid-cols-2 gap-3 pt-2">
                        <div class="bg-white/10 p-3.5 rounded-xl border border-white/15">
                            <div class="text-amber-300 font-bold text-xs uppercase">Hotline / Zalo 24/7</div>
                            <a href="tel:0934722773" class="text-xl font-black text-white hover:underline block mt-0.5">0934.722.773</a>
                        </div>
                        <div class="bg-white/10 p-3.5 rounded-xl border border-white/15">
                            <div class="text-amber-300 font-bold text-xs uppercase">Trụ sở Đà Nẵng</div>
                            <div class="text-xs sm:text-sm font-semibold text-white mt-0.5">408 Văn Tiến Dũng, P. Hòa Xuân</div>
                        </div>
                    </div>
                </div>

                <!-- Form Gửi Yêu Cầu Báo Giá -->
                <div class="lg:col-span-6 bg-white text-slate-800 rounded-2xl p-5 sm:p-7 shadow-xl">
                    <h3 class="text-base sm:text-lg font-extrabold text-primary-dark mb-1">
                        ĐĂNG KÝ TƯ VẤN & BÁO GIÁ MIỄN PHÍ
                    </h3>
                    <p class="text-xs text-slate-500 mb-4">Điền thông tin bên dưới, Phúc Hưng sẽ gọi lại tư vấn ngay!</p>

                    <form id="quoteForm" onsubmit="submitQuoteForm(event)" class="space-y-3.5">
                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-3.5">
                            <div>
                                <label class="block text-xs font-bold text-slate-700 mb-1">Họ và tên *</label>
                                <input type="text" id="custName" required placeholder="Nhập họ tên của bạn" class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 focus:outline-none focus:border-primary">
                            </div>
                            <div>
                                <label class="block text-xs font-bold text-slate-700 mb-1">Số điện thoại / Zalo *</label>
                                <input type="tel" id="custPhone" required placeholder="Ví dụ: 0934722773" class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 focus:outline-none focus:border-primary">
                            </div>
                        </div>

                        <div>
                            <label class="block text-xs font-bold text-slate-700 mb-1">Hạng mục quan tâm</label>
                            <select id="custService" class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 focus:outline-none focus:border-primary bg-white">
                                <option value="Thiết bị Bể bơi nhập khẩu (Máy bơm, Bình lọc, Đèn, Điện phân muối...)">Thiết bị Bể bơi nhập khẩu (Máy bơm, Bình lọc, Đèn, Điện phân muối...)</option>
                                <option value="Thiết bị Xông hơi (Máy xông hơi khô/ướt SAWO, Harvia, Coasts & Phòng xông)">Thiết bị Xông hơi (Máy xông hơi khô/ướt SAWO, Harvia, Coasts & Phòng xông)</option>
                                <option value="Bể sục Jacuzzi - Bồn tắm massage & Bồn ngâm thủy trị liệu">Bể sục Jacuzzi - Bồn tắm massage & Bồn ngâm thủy trị liệu</option>
                                <option value="Gạch Mosaic ốp lát bể bơi & Hóa chất xử lý nước, Thiết bị cứu hộ">Gạch Mosaic ốp lát bể bơi & Hóa chất xử lý nước, Thiết bị cứu hộ</option>
                                <option value="Vách kính Acrylic hồ bơi, Cây sen tắm ngoài trời & Thiết bị công viên nước">Vách kính Acrylic hồ bơi, Cây sen tắm ngoài trời & Thiết bị công viên nước</option>
                            </select>
                        </div>

                        <div>
                            <label class="block text-xs font-bold text-slate-700 mb-1">Khu vực công trình & Ghi chú kích thước (nếu có)</label>
                            <textarea id="custNote" rows="2" placeholder="Ví dụ: Cần tư vấn phòng xông hơi gia đình cho 2-3 người tại Hòa Xuân, Đà Nẵng..." class="w-full px-3.5 py-2 text-sm rounded-lg border border-slate-300 focus:outline-none focus:border-primary"></textarea>
                        </div>

                        <button type="submit" class="w-full bg-sauna hover:bg-sauna-dark text-white font-extrabold text-sm py-3 rounded-xl shadow transition uppercase tracking-wide">
                            <i class="fa-solid fa-paper-plane mr-1.5"></i> Gửi Yêu Cầu Báo Giá Miễn Phí
                        </button>
                    </form>

                    <!-- Thông báo gửi thành công (Thay cho alert) -->
                    <div id="quoteSuccessBox" class="hidden mt-4 p-3.5 rounded-xl bg-emerald-50 border border-emerald-200 text-emerald-800 text-xs sm:text-sm font-medium">
                        <i class="fa-solid fa-circle-check text-emerald-600 mr-1.5"></i>
                        Cảm ơn bạn! Phúc Hưng Pool & Sauna đã ghi nhận yêu cầu. Bạn cũng có thể bấm <a href="tel:0934722773" class="font-bold underline">Gọi 0934.722.773</a> hoặc nhắn Zalo để nhận báo giá ngay lập tức!
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- =====================================================================
         FLATSOME FOOTER 4 CỘT + ABSOLUTE FOOTER
         ===================================================================== -->
    <footer class="bg-slate-900 text-slate-300 pt-12 pb-20 md:pb-8 border-t border-slate-800">
        <div class="max-w-7xl mx-auto px-3 sm:px-4">
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8 pb-10 border-b border-slate-800">
                
                <!-- Cột 1: Thông tin công ty -->
                <div>
                    <h4 class="text-white font-extrabold text-sm uppercase tracking-wider mb-4 border-l-4 border-amber-400 pl-2.5">
                        CÔNG TY TNHH XD & CN PHÚC HƯNG
                    </h4>
                    <p class="text-xs text-slate-400 leading-relaxed mb-4">
                        Chuyên tư vấn, thiết kế, cung cấp và thi công lắp đặt trọn gói Thiết bị bể bơi, Phòng xông hơi khô, ướt, đá muối uy tín hàng đầu tại Quảng Nam - Đà Nẵng.
                    </p>
                    <ul class="space-y-2 text-xs">
                        <li><i class="fa-solid fa-location-dot text-amber-400 w-5"></i> 408 Văn Tiến Dũng, Phường Hòa Xuân, TP Đà Nẵng</li>
                        <li><i class="fa-solid fa-phone text-amber-400 w-5"></i> Hotline/Zalo: <a href="tel:0934722773" class="text-white font-bold">0934.722.773</a></li>
                        <li><i class="fa-solid fa-id-card text-amber-400 w-5"></i> Mã số thuế: 0402102763</li>
                        <li><i class="fa-solid fa-globe text-amber-400 w-5"></i> Website: phuchungpool.com</li>
                    </ul>
                </div>

                <!-- Cột 2: Danh mục sản phẩm -->
                <div>
                    <h4 class="text-white font-extrabold text-sm uppercase tracking-wider mb-4 border-l-4 border-amber-400 pl-2.5">
                        DANH MỤC SẢN PHẨM
                    </h4>
                    <ul class="space-y-2 text-xs">
                        <li><a href="#san-pham" onclick="filterProducts('thiet-bi-be-boi')" class="hover:text-white transition"><i class="fa-solid fa-angle-right text-amber-400 mr-1.5"></i> Thiết Bị Bể Bơi (Waterco, Emaux, Kripsol)</a></li>
                        <li><a href="#san-pham" onclick="filterProducts('thiet-bi-xong-hoi')" class="hover:text-white transition"><i class="fa-solid fa-angle-right text-amber-400 mr-1.5"></i> Thiết Bị Xông Hơi (SAWO, Harvia, Coasts)</a></li>
                        <li><a href="#san-pham" onclick="filterProducts('be-suc-jacuzzi')" class="hover:text-white transition"><i class="fa-solid fa-angle-right text-amber-400 mr-1.5"></i> Bể Sục Jacuzzi - Bồn Tắm Thủy Trị Liệu</a></li>
                        <li><a href="#san-pham" onclick="filterProducts('gach-mosaic')" class="hover:text-white transition"><i class="fa-solid fa-angle-right text-amber-400 mr-1.5"></i> Gạch Mosaic Thủy Tinh, Gốm & Vảy Cá</a></li>
                        <li><a href="#san-pham" onclick="filterProducts('hoa-chat-cuu-ho')" class="hover:text-white transition"><i class="fa-solid fa-angle-right text-amber-400 mr-1.5"></i> Hóa Chất Xử Lý Nước & Thiết Bị Cứu Hộ</a></li>
                        <li><a href="#san-pham" onclick="filterProducts('acrylic-ngoai-that')" class="hover:text-white transition"><i class="fa-solid fa-angle-right text-amber-400 mr-1.5"></i> Vách Acrylic Hồ Bơi & Sen Tắm Ngoài Trời</a></li>
                    </ul>
                </div>

                <!-- Cột 3: Chính sách & Cam kết -->
                <div>
                    <h4 class="text-white font-extrabold text-sm uppercase tracking-wider mb-4 border-l-4 border-amber-400 pl-2.5">
                        CAM KẾT DỊCH VỤ
                    </h4>
                    <ul class="space-y-2 text-xs">
                        <li><i class="fa-solid fa-check text-emerald-400 mr-1.5"></i> Miễn phí 100% Tư vấn, Thiết kế & Báo giá</li>
                        <li><i class="fa-solid fa-check text-emerald-400 mr-1.5"></i> Khảo sát tận nơi tại Đà Nẵng & Quảng Nam</li>
                        <li><i class="fa-solid fa-check text-emerald-400 mr-1.5"></i> Hàng chính hãng đầy đủ giấy tờ CO, CQ</li>
                        <li><i class="fa-solid fa-check text-emerald-400 mr-1.5"></i> Bảo hành thiết bị từ 12 - 36 tháng tận nhà</li>
                        <li><i class="fa-solid fa-check text-emerald-400 mr-1.5"></i> Hỗ trợ kỹ thuật xử lý nước hồ bơi trọn đời</li>
                    </ul>
                </div>

                <!-- Cột 4: Kết nối Fanpage Facebook -->
                <div>
                    <h4 class="text-white font-extrabold text-sm uppercase tracking-wider mb-4 border-l-4 border-amber-400 pl-2.5">
                        KẾT NỐI FACEBOOK
                    </h4>
                    <div class="bg-slate-800 p-3.5 rounded-xl border border-slate-700">
                        <div class="flex items-center gap-3">
                            <div class="w-11 h-11 rounded-lg bg-primary flex items-center justify-center text-white font-extrabold text-base shrink-0">
                                PH
                            </div>
                            <div>
                                <a href="https://www.facebook.com/phuchungpoolsauna/" target="_blank" rel="noopener noreferrer" class="text-white font-bold text-xs hover:underline block">
                                    Phúc Hưng Pool & Sauna - Bể bơi, Xông hơi
                                </a>
                                <span class="text-[11px] text-slate-400">Chuyên thiết bị bể bơi, phòng xông hơi</span>
                            </div>
                        </div>
                        <div class="mt-3 flex gap-2">
                            <a href="https://www.facebook.com/phuchungpoolsauna/" target="_blank" rel="noopener noreferrer" class="flex-1 bg-blue-600 hover:bg-blue-500 text-white text-center text-xs font-bold py-2 rounded-lg transition">
                                <i class="fa-brands fa-facebook mr-1"></i> Theo dõi Trang
                            </a>
                            <a href="https://zalo.me/0934722773" target="_blank" rel="noopener noreferrer" class="flex-1 bg-sky-500 hover:bg-sky-400 text-white text-center text-xs font-bold py-2 rounded-lg transition">
                                Chat Zalo
                            </a>
                        </div>
                    </div>
                </div>

            </div>

            <div class="pt-5 flex flex-col sm:flex-row items-center justify-between text-xs text-slate-500 gap-2">
                <p>Copyright 2026 © <strong>phuchungpool.com</strong> - CÔNG TY TNHH XÂY DỰNG VÀ CÔNG NGHỆ PHÚC HƯNG</p>
                <p>Thiết kế chuẩn giao diện Flatsome UX Builder</p>
            </div>
        </div>
    </footer>

    <!-- =====================================================================
         NÚT LIÊN HỆ NỔI (ZALO / FACEBOOK / HOTLINE) TRÊN ĐIỆN THOẠI & MÁY TÍNH
         ===================================================================== -->
    <div class="fixed bottom-4 left-3 z-40 hidden sm:flex flex-col gap-2.5">
        <a href="https://www.facebook.com/phuchungpoolsauna/" target="_blank" rel="noopener noreferrer" class="flex items-center gap-2 bg-blue-600 hover:bg-blue-700 text-white px-3.5 py-2 rounded-full shadow-lg text-xs font-bold transition">
            <i class="fa-brands fa-facebook-f text-sm"></i>
            <span>Facebook Phúc Hưng</span>
        </a>
        <a href="https://zalo.me/0934722773" target="_blank" rel="noopener noreferrer" class="flex items-center gap-2 bg-sky-500 hover:bg-sky-600 text-white px-3.5 py-2 rounded-full shadow-lg text-xs font-bold transition">
            <i class="fa-solid fa-comment-dots text-sm"></i>
            <span>Zalo: 0934.722.773</span>
        </a>
        <a href="tel:0934722773" class="flex items-center gap-2 bg-red-600 hover:bg-red-700 text-white px-4 py-2.5 rounded-full shadow-lg text-xs font-extrabold transition">
            <i class="fa-solid fa-phone-volume animate-ring text-sm"></i>
            <span>Gọi: 0934.722.773</span>
        </a>
    </div>

    <!-- Thanh điều hướng cố định dưới đáy màn hình Điện thoại -->
    <div class="sm:hidden fixed bottom-0 inset-x-0 bg-white border-t border-slate-200 z-40 grid grid-cols-3 py-1.5 px-2 gap-1.5 shadow-[0_-4px_12px_rgba(0,0,0,0.08)]">
        <a href="tel:0934722773" class="bg-red-600 text-white rounded-lg py-2 flex flex-col items-center justify-center font-bold text-[11px]">
            <i class="fa-solid fa-phone-volume text-sm mb-0.5"></i>
            <span>0934.722.773</span>
        </a>
        <a href="https://zalo.me/0934722773" target="_blank" rel="noopener noreferrer" class="bg-sky-500 text-white rounded-lg py-2 flex flex-col items-center justify-center font-bold text-[11px]">
            <i class="fa-solid fa-comment-dots text-sm mb-0.5"></i>
            <span>Chat Zalo</span>
        </a>
        <a href="https://www.facebook.com/phuchungpoolsauna/" target="_blank" rel="noopener noreferrer" class="bg-blue-600 text-white rounded-lg py-2 flex flex-col items-center justify-center font-bold text-[11px]">
            <i class="fa-brands fa-facebook-messenger text-sm mb-0.5"></i>
            <span>Facebook</span>
        </a>
    </div>

    <!-- =====================================================================
         MODAL CHI TIẾT SẢN PHẨM / BÁO GIÁ NHANH
         ===================================================================== -->
    <div id="productModal" class="fixed inset-0 bg-slate-900/70 z-50 hidden items-center justify-center p-3" onclick="closeProductModal()">
        <div class="bg-white rounded-2xl max-w-2xl w-full overflow-hidden shadow-2xl border border-slate-200" onclick="event.stopPropagation()">
            <div class="flex items-center justify-between px-5 py-3.5 border-b border-slate-100 bg-slate-50">
                <h3 id="modalTitle" class="font-extrabold text-primary-dark text-sm sm:text-base">Chi Tiết Sản Phẩm</h3>
                <button onclick="closeProductModal()" class="w-8 h-8 rounded-full bg-slate-200/70 hover:bg-slate-300 text-slate-700 flex items-center justify-center">
                    <i class="fa-solid fa-xmark"></i>
                </button>
            </div>
            <div class="p-5 grid grid-cols-1 sm:grid-cols-12 gap-5 items-center">
                <div class="sm:col-span-5">
                    <img id="modalImg" src="" alt="" class="w-full aspect-square object-cover rounded-xl border border-slate-200">
                </div>
                <div class="sm:col-span-7 space-y-2.5">
                    <span id="modalCat" class="inline-block bg-primary-light text-primary text-[11px] font-bold px-2.5 py-0.5 rounded">Danh mục</span>
                    <h4 id="modalName" class="text-base sm:text-lg font-extrabold text-slate-900"></h4>
                    <div id="modalPrice" class="text-red-600 font-extrabold text-base">Liên hệ: 0934.722.773</div>
                    <p id="modalDesc" class="text-xs sm:text-sm text-slate-600 leading-relaxed"></p>
                    <div class="bg-amber-50 border border-amber-200 rounded-xl p-3 text-xs text-slate-700 space-y-1">
                        <div class="font-bold text-slate-900"><i class="fa-solid fa-gift text-red-600 mr-1"></i> Ưu đãi tại Phúc Hưng Pool & Sauna:</div>
                        <div>• Miễn phí khảo sát, thiết kế & báo giá tận nơi Quảng Nam - Đà Nẵng</div>
                        <div>• Bảo hành chính hãng tận nhà - Hỗ trợ kỹ thuật 24/7</div>
                    </div>
                    <div class="pt-2 flex flex-wrap gap-2.5">
                        <a href="tel:0934722773" class="flex-1 bg-red-600 hover:bg-red-700 text-white text-center font-bold text-xs sm:text-sm py-2.5 px-4 rounded-xl transition">
                            <i class="fa-solid fa-phone mr-1"></i> Gọi: 0934.722.773
                        </a>
                        <a href="https://zalo.me/0934722773" target="_blank" rel="noopener noreferrer" class="flex-1 bg-sky-500 hover:bg-sky-600 text-white text-center font-bold text-xs sm:text-sm py-2.5 px-4 rounded-xl transition">
                            <i class="fa-solid fa-comment-dots mr-1"></i> Báo giá qua Zalo
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <!-- =====================================================================
         JAVASCRIPT: DỮ LIỆU SẢN PHẨM, DỰ ÁN & XỬ LÝ TƯƠNG TÁC
         ===================================================================== -->
    <script>
        // Danh sách 20 sản phẩm theo đúng danh mục và sản phẩm trên Hanteco.vn
        const PRODUCTS = [
            // 1. THIẾT BỊ BỂ BƠI (thiet-bi-be-boi)
            {
                id: 1,
                code: "EMAUX-ETURBO",
                name: "Máy Bơm Bể Bơi Emaux E-Turbo Variable Speed (Mới)",
                category: "thiet-bi-be-boi",
                categoryLabel: "Thiết Bị Bể Bơi",
                price: "Liên hệ: 0934.722.773",
                badge: "Mới 2026",
                image: "https://images.unsplash.com/photo-1576013551627-0cc20b96c2a7?auto=format&fit=crop&w=600&q=80",
                desc: "Dòng máy bơm bể bơi biến tần thông minh Emaux E-Turbo thế hệ mới giúp tiết kiệm tới 80% điện năng, vận hành siêu êm, lưu lượng lớn chuyên dụng cho bể bơi gia đình, villa và resort."
            },
            {
                id: 2,
                code: "EMAUX-GALAXY",
                name: "Bộ Lọc Bể Bơi Emaux Galaxy IDE | Chất Lượng Lọc Đặc Biệt",
                category: "thiet-bi-be-boi",
                categoryLabel: "Thiết Bị Bể Bơi",
                price: "Liên hệ: 0934.722.773",
                badge: "Chính hãng",
                image: "https://images.unsplash.com/photo-1562778612-e1e0cda9915c?auto=format&fit=crop&w=600&q=80",
                desc: "Bình lọc bể bơi cao cấp Emaux Galaxy IDE kết hợp bình lọc Waterco / Kripsol, thân vỏ gia cố sợi thủy tinh chịu áp lực cao, chống tia UV, đi kèm van 6 chức năng."
            },
            {
                id: 3,
                code: "WATERCO-PUMP",
                name: "Máy Bơm & Bình Lọc Bể Bơi Waterco Nhập Khẩu Chính Hãng",
                category: "thiet-bi-be-boi",
                categoryLabel: "Thiết Bị Bể Bơi",
                price: "Liên hệ: 0934.722.773",
                badge: "Waterco",
                image: "https://images.unsplash.com/photo-1519046904884-53103b34b206?auto=format&fit=crop&w=600&q=80",
                desc: "Hệ thống bình lọc cát và máy bơm bể bơi thương hiệu Waterco (Úc) nhập khẩu chính hãng, độ bền vượt trội, lọc nước tinh khiết cho bể bơi biệt thự và bể bơi kinh doanh."
            },
            {
                id: 4,
                code: "POOL-ACCESSORY",
                name: "Đèn LED Bể Bơi Âm Nước, Thang Inox 304 & Máy Điện Phân Muối",
                category: "thiet-bi-be-boi",
                categoryLabel: "Thiết Bị Bể Bơi",
                price: "Liên hệ: 0934.722.773",
                badge: "Đồng bộ",
                image: "https://images.unsplash.com/photo-1572331165267-854da2b10ccc?auto=format&fit=crop&w=600&q=80",
                desc: "Cung cấp trọn bộ đèn LED bể bơi đổi màu IP68 (12V), thang bể bơi Inox 304/316 chống gỉ, máy cấp nhiệt bể bơi, đèn UV và máy điện phân muối khử trùng tự động."
            },
            {
                id: 5,
                code: "ROBOT-CLEAN",
                name: "Robot Vệ Sinh Bể Bơi Tự Động & Bộ Dụng Cụ Vệ Sinh 7 Món",
                category: "thiet-bi-be-boi",
                categoryLabel: "Thiết Bị Bể Bơi",
                price: "Liên hệ: 0934.722.773",
                badge: "Tự động",
                image: "https://images.unsplash.com/photo-1540541338287-41700207dee6?auto=format&fit=crop&w=600&q=80",
                desc: "Robot hút cặn vệ sinh đáy và thành bể bơi thông minh cùng trọn bộ thiết bị vệ sinh hồ bơi: bàn hút đáy, sào nhôm nối dài, ống mềm, vợt vớt rác, chổi cọ và bộ test pH/Clo."
            },

            // 2. THIẾT BỊ XÔNG HƠI (thiet-bi-xong-hoi)
            {
                id: 6,
                code: "COASTS-KSA60",
                name: "Máy Xông Hơi Ướt Coasts Model KSA-60 (6kW) Xả Cặn Tự Động",
                category: "thiet-bi-xong-hoi",
                categoryLabel: "Thiết Bị Xông Hơi",
                price: "6.700.000đ (Giá KM)",
                badge: "-20%",
                image: "https://images.unsplash.com/photo-1584622781564-1d987f7333c1?auto=format&fit=crop&w=600&q=80",
                desc: "Máy xông hơi ướt Coasts KSA-60 công suất 6kW vỏ Inox chống gỉ, tích hợp van xả cặn tự động và bảng điều khiển điện tử thông minh chuyên dùng cho phòng xông ướt gia đình & Spa."
            },
            {
                id: 7,
                code: "COASTS-KSA90",
                name: "Máy Xông Hơi Ướt Coasts KSA-90 (9kW) & KSA-150 (15kW)",
                category: "thiet-bi-xong-hoi",
                categoryLabel: "Thiết Bị Xông Hơi",
                price: "7.800.000đ (Giá KM)",
                badge: "-20%",
                image: "https://images.unsplash.com/photo-1507652313519-d4e9174996dd?auto=format&fit=crop&w=600&q=80",
                desc: "Dòng máy xông hơi ướt Coasts KSA-90 (9kW) và KSA-150 (15kW) tạo hơi nhanh, vận hành bền bỉ, phù hợp cho phòng xông hơi ướt thể tích vừa và lớn tại khách sạn, gym, spa."
            },
            {
                id: 8,
                code: "SAWO-HARVIA-DRY",
                name: "Máy Xông Hơi Khô SAWO / HARVIA / Coasts / Amazon Chính Hãng",
                category: "thiet-bi-xong-hoi",
                categoryLabel: "Thiết Bị Xông Hơi",
                price: "Liên hệ: 0934.722.773",
                badge: "Nhập khẩu",
                image: "https://images.unsplash.com/photo-1560185007-cde436f6a4d0?auto=format&fit=crop&w=600&q=80",
                desc: "Phân phối đầy đủ các dòng máy xông hơi khô SAWO (Phần Lan), Harvia, Coasts, Amazon, Dolomiti&F công suất 6kW, 9kW, 12kW, 15kW bảo hành chính hãng tới 36 tháng."
            },
            {
                id: 9,
                code: "SAUNA-ROOM-FULL",
                name: "Thi Công Phòng Xông Hơi Khô Gỗ Thông & Phòng Xông Hơi Ướt",
                category: "thiet-bi-xong-hoi",
                categoryLabel: "Thiết Bị Xông Hơi",
                price: "Miễn phí thiết kế - 0934.722.773",
                badge: "Trọn gói",
                image: "https://images.unsplash.com/photo-1540555700478-4be289fbecef?auto=format&fit=crop&w=600&q=80",
                desc: "Thiết kế và lắp đặt trọn gói phòng xông hơi khô gỗ thông Phần Lan, phòng xông đá muối Himalaya và phòng xông hơi ướt kính cường lực theo kích thước yêu cầu."
            },
            {
                id: 10,
                code: "SAUNA-ACC",
                name: "Phụ Kiện Phòng Xông Hơi: Xô Gáo Gỗ, Ẩm Nhiệt Kế, Đồng Hồ Cát",
                category: "thiet-bi-xong-hoi",
                categoryLabel: "Thiết Bị Xông Hơi",
                price: "Liên hệ: 0934.722.773",
                badge: "Combo",
                image: "https://images.unsplash.com/photo-1544161515-4ab6ce6db874?auto=format&fit=crop&w=600&q=80",
                desc: "Trọn bộ phụ kiện phòng xông hơi gồm: Xô - gáo gỗ thông, ẩm nhiệt kế, đồng hồ cát, đá sauna núi lửa, khung bao máy, khung bao đèn chống nổ, ghế phòng xông và ghế phòng tắm."
            },

            // 3. BỂ SỤC JACUZZI - BỒN TẮM (be-suc-jacuzzi)
            {
                id: 11,
                code: "JACUZZI-HL1803",
                name: "Bồn Sục Jacuzzi Nhập Khẩu HL-1803 | 2200x2200x950 mm",
                category: "be-suc-jacuzzi",
                categoryLabel: "Bể Sục Jacuzzi - Bồn Tắm",
                price: "Liên hệ: 0934.722.773",
                badge: "Cao cấp",
                image: "https://images.unsplash.com/photo-1584622650111-993a426fbf0a?auto=format&fit=crop&w=600&q=80",
                desc: "Bồn sục Jacuzzi HL-1803 nhập khẩu nguyên chiếc, tích hợp mắt sục thủy lực massage toàn thân, hệ thống gia nhiệt, đèn LED đổi màu và bảng điều khiển thông minh."
            },
            {
                id: 12,
                code: "JACUZZI-HL2802",
                name: "Bồn Jacuzzi HL-2802 & HL-1802 Nhập Khẩu | Bồn Sục 6 - 7 Người",
                category: "be-suc-jacuzzi",
                categoryLabel: "Bể Sục Jacuzzi - Bồn Tắm",
                price: "Liên hệ: 0934.722.773",
                badge: "Villa / Resort",
                image: "https://images.unsplash.com/photo-1600566752355-35792bedcfea?auto=format&fit=crop&w=600&q=80",
                desc: "Mẫu bồn sục Jacuzzi cỡ lớn cho 6-7 người sử dụng cùng lúc và các dòng bồn ngâm thủy trị liệu cao cấp dành cho biệt thự, penthouse, spa và khu nghỉ dưỡng."
            },

            // 4. GẠCH MOSAIC (gach-mosaic)
            {
                id: 13,
                code: "MOSAIC-GLASS",
                name: "Gạch Mosaic Thủy Tinh & Gạch Mosaic Gốm Ốp Lát Bể Bơi",
                category: "gach-mosaic",
                categoryLabel: "Gạch Mosaic",
                price: "Giá tổng kho: 0934.722.773",
                badge: "Sẵn kho",
                image: "https://images.unsplash.com/photo-1576013551627-0cc20b96c2a7?auto=format&fit=crop&w=600&q=80",
                desc: "Tổng kho phân phối gạch Mosaic thủy tinh, gạch Mosaic gốm ốp lát bể bơi và phòng xông hơi ướt, chống thấm tuyệt đối, phản quang ánh nước xanh ngọc sang trọng."
            },
            {
                id: 14,
                code: "MOSAIC-HTCL15",
                name: "Gạch Mosaic Chiếc Lá HTCL 15 & Gạch Mosaic Vảy Cá Men Rạn | A1",
                category: "gach-mosaic",
                categoryLabel: "Gạch Mosaic",
                price: "Giá tổng kho: 0934.722.773",
                badge: "Trang trí A1",
                image: "https://images.unsplash.com/photo-1615873968403-89e068629265?auto=format&fit=crop&w=600&q=80",
                desc: "Các mẫu gạch Mosaic trang trí nghệ thuật: gạch chiếc lá màu xanh HTCL 15, gạch vảy cá men rạn, gạch thẻ HGT 082, gạch lục giác và keo dán gạch Mosaic chuyên dụng."
            },

            // 5. HÓA CHẤT & THIẾT BỊ CỨU HỘ (hoa-chat-cuu-ho)
            {
                id: 15,
                code: "CHEM-CHLORINE",
                name: "Hóa Chất Chlorine Ấn Độ (Aquafit, Aqua-ORG) & Xô Clo 5Kg",
                category: "hoa-chat-cuu-ho",
                categoryLabel: "Hóa Chất & Cứu Hộ",
                price: "Giá sỉ & lẻ: 0934.722.773",
                badge: "Xử lý nước",
                image: "https://images.unsplash.com/photo-1532187863486-abf9dbad1b69?auto=format&fit=crop&w=600&q=80",
                desc: "Hóa chất xử lý nước bể bơi chính hãng: Chlorine Ấn Độ 70%, xô Clo 5kg tiện dụng, hóa chất tăng/giảm pH, hóa chất diệt rêu tảo, trợ lắng PAC giúp nước bể bơi trong vắt."
            },
            {
                id: 16,
                code: "CHEM-TCCA",
                name: "Hóa Chất TCCA Viên Nén Cho Hồ Bơi | Thùng 50Kg (Viên 200G)",
                category: "hoa-chat-cuu-ho",
                categoryLabel: "Hóa Chất & Cứu Hộ",
                price: "Giá sỉ & lẻ: 0934.722.773",
                badge: "Tiện dụng",
                image: "https://images.unsplash.com/photo-1584017911766-d451b3d0e843?auto=format&fit=crop&w=600&q=80",
                desc: "Viên nén TCCA 90% tan chậm duy trì nồng độ Clo ổn định lâu dài trong nước hồ bơi, kết hợp cùng bộ châm hóa chất tự động an toàn và tiết kiệm."
            },
            {
                id: 17,
                code: "RESCUE-COMBO",
                name: "Thiết Bị Cứu Hộ Bể Bơi: Ghế Cứu Hộ, Áo Phao Bơi & Phao Cứu Sinh",
                category: "hoa-chat-cuu-ho",
                categoryLabel: "Hóa Chất & Cứu Hộ",
                price: "Liên hệ: 0934.722.773",
                badge: "Chuẩn an toàn",
                image: "https://images.unsplash.com/photo-1519046904884-53103b34b206?auto=format&fit=crop&w=600&q=80",
                desc: "Cung cấp đầy đủ thiết bị cứu hộ bể bơi theo quy định: Ghế quan sát cứu hộ Inox nhập khẩu, áo phao bơi đủ kích cỡ, phao tròn cứu sinh, móc cứu hộ, còi và biển báo hồ bơi."
            },

            // 6. VÁCH ACRYLIC & NGOẠI THẤT HỒ BƠI (acrylic-ngoai-that)
            {
                id: 18,
                code: "ACRYLIC-POOL",
                name: "Tấm Vách Kính Acrylic Hồ Bơi Trong Suốt (Dày 60 - 120mm) Nhập Khẩu",
                category: "acrylic-ngoai-that",
                categoryLabel: "Vách Acrylic & Ngoại Thất",
                price: "Báo giá dự án: 0934.722.773",
                badge: "Bể bơi vô cực",
                image: "https://images.unsplash.com/photo-1540541338287-41700207dee6?auto=format&fit=crop&w=600&q=80",
                desc: "Cung cấp và thi công tấm vách kính Acrylic hồ bơi vô cực trong suốt, vách Acrylic bể cá Koi và thủy cung cao cấp chịu áp lực nước cực lớn, độ truyền sáng 92%."
            },
            {
                id: 19,
                code: "RUBY-A1006",
                name: "Cây Sen Tắm Ngoài Trời Ruby A1006 | Sen Tắm Tráng Hồ Bơi Cao Cấp",
                category: "acrylic-ngoai-that",
                categoryLabel: "Vách Acrylic & Ngoại Thất",
                price: "Liên hệ: 0934.722.773",
                badge: "Ngoại thất",
                image: "https://images.unsplash.com/photo-1584622650111-993a426fbf0a?auto=format&fit=crop&w=600&q=80",
                desc: "Cây sen tắm ngoài trời Ruby A1006 và A1006-MB nhập khẩu chính hãng, thiết kế sang trọng chịu nắng mưa ngoài trời, nâng tầm thẩm mỹ không gian sân vườn và hồ bơi."
            },
            {
                id: 20,
                code: "WATER-PARK",
                name: "Thiết Bị Công Viên Nước, Cầu Trượt Bể Bơi & Đồ Chơi Hồ Bơi",
                category: "acrylic-ngoai-that",
                categoryLabel: "Vách Acrylic & Ngoại Thất",
                price: "Liên hệ: 0934.722.773",
                badge: "Khu vui chơi",
                image: "https://images.unsplash.com/photo-1572331165267-854da2b10ccc?auto=format&fit=crop&w=600&q=80",
                desc: "Cung cấp và lắp đặt cầu trượt bể bơi composite, nấm phun nước, cá heo phun nước và thiết bị bể tạo sóng cho công viên nước, trường học và khu nghỉ dưỡng."
            }
        ];

        // Danh sách 6 Công trình tiêu biểu tại Đà Nẵng & Quảng Nam
        const PROJECTS = [
            {
                title: "Thi Công Phòng Xông Hơi Khô Kết Hợp Ướt Vách Kính Tại Hòa Xuân, Đà Nẵng",
                date: "22",
                month: "Th10",
                location: "Cẩm Lệ, Đà Nẵng",
                image: "https://images.unsplash.com/photo-1584622650111-993a426fbf0a?auto=format&fit=crop&w=700&q=80",
                excerpt: "Hoàn thiện và bàn giao cụm phòng xông hơi khô gỗ thông Phần Lan kết hợp phòng xông hơi ướt ốp gạch Mosaic sang trọng cho biệt thự gia đình."
            },
            {
                title: "Lắp Đặt Hệ Thống Lọc Bể Bơi Villa & Đèn Âm Nước Tại Sơn Trà, Đà Nẵng",
                date: "15",
                month: "Th10",
                location: "Sơn Trà, Đà Nẵng",
                image: "https://images.unsplash.com/photo-1576013551627-0cc20b96c2a7?auto=format&fit=crop&w=700&q=80",
                excerpt: "Thi công trọn gói phòng máy lọc tuần hoàn bể bơi, máy điện phân muối khử trùng tự động và hệ thống đèn LED âm nước đổi màu."
            },
            {
                title: "Bàn Giao Phòng Xông Hơi Gỗ Thông & Máy Harvia Cho Villa Tại Hội An, Quảng Nam",
                date: "04",
                month: "Th10",
                location: "Hội An, Quảng Nam",
                image: "https://images.unsplash.com/photo-1540555700478-4be289fbecef?auto=format&fit=crop&w=700&q=80",
                excerpt: "Thiết kế và lắp đặt phòng Sauna tiêu chuẩn châu Âu phục vụ du khách nghỉ dưỡng tại Villa Hội An với máy xông hơi Harvia 9KW."
            },
            {
                title: "Thi Công Phòng Xông Hơi Đá Muối Himalaya Cho Spa Tại Hải Châu, Đà Nẵng",
                date: "26",
                month: "Th09",
                location: "Hải Châu, Đà Nẵng",
                image: "https://images.unsplash.com/photo-1515377905703-c4788e51af15?auto=format&fit=crop&w=700&q=80",
                excerpt: "Lắp đặt vách đá muối Himalaya xuyên sáng kết hợp gỗ thông nhập khẩu mang lại không gian trị liệu đẳng cấp cho Spa."
            },
            {
                title: "Lắp Đặt Bể Bơi Gia Đình & Phòng Xông Hơi Tại Tam Kỳ, Quảng Nam",
                date: "18",
                month: "Th09",
                location: "Tam Kỳ, Quảng Nam",
                image: "https://images.unsplash.com/photo-1572331165267-854da2b10ccc?auto=format&fit=crop&w=700&q=80",
                excerpt: "Khảo sát, thiết kế miễn phí và thi công trọn gói hạng mục bể bơi sân vườn kết hợp phòng xông hơi gia đình tại TP Tam Kỳ."
            },
            {
                title: "Cải Tạo Nâng Cấp Hệ Thống Lọc Bể Bơi & Khu Sauna Khách Sạn Biển Mỹ Khê",
                date: "09",
                month: "Th09",
                location: "Ngũ Hành Sơn, Đà Nẵng",
                image: "https://images.unsplash.com/photo-1519046904884-53103b34b206?auto=format&fit=crop&w=700&q=80",
                excerpt: "Bảo trì thay cát lọc thạch anh, nâng cấp máy bơm bể bơi và lắp mới 2 máy xông hơi ướt Coast cho khách sạn ven biển Đà Nẵng."
            }
        ];

        // Hàm render danh sách sản phẩm (Chia 2 cột trên điện thoại, 4 cột trên máy tính)
        function renderProducts(list) {
            const grid = document.getElementById('productGrid');
            if (!list.length) {
                grid.innerHTML = `
                    <div class="col-span-full bg-white rounded-xl p-8 text-center border border-slate-200">
                        <p class="text-sm font-bold text-slate-700">Không tìm thấy sản phẩm phù hợp với từ khóa.</p>
                        <button onclick="filterProducts('all')" class="mt-3 bg-primary text-white text-xs font-bold px-4 py-2 rounded-lg">Xem tất cả sản phẩm</button>
                    </div>
                `;
                return;
            }

            grid.innerHTML = list.map(item => `
                <div class="flatsome-product-box bg-white rounded-xl overflow-hidden border border-slate-200/90 flex flex-col justify-between group">
                    <div>
                        <div class="relative aspect-square overflow-hidden bg-slate-100 cursor-pointer" onclick="openProductModal(${item.id})">
                            <img 
                                src="${item.image}" 
                                onerror="this.src='https://placehold.co/500x500/005b96/ffffff?text=Phuc+Hung+Pool'"
                                alt="${item.name}" 
                                class="product-img w-full h-full object-cover"
                            >
                            <span class="absolute top-2.5 left-2.5 z-10 bg-primary text-white text-[10px] font-bold px-2.5 py-1 rounded shadow-md leading-none">
                                ${item.badge}
                            </span>
                        </div>

                        <div class="p-2.5 sm:p-3.5 text-center">
                            <div class="text-[10px] sm:text-[11px] uppercase tracking-wider text-slate-400 font-semibold truncate">
                                ${item.categoryLabel}
                            </div>
                            <h3 onclick="openProductModal(${item.id})" class="font-bold text-xs sm:text-sm text-slate-800 hover:text-primary cursor-pointer line-clamp-2 mt-1 min-h-[2.5rem] leading-snug">
                                ${item.name}
                            </h3>
                            <div class="text-[11px] sm:text-xs font-extrabold text-red-600 mt-1.5">
                                Liên hệ: 0934.722.773
                            </div>
                        </div>
                    </div>

                    <div class="px-2.5 pb-2.5 sm:px-3.5 sm:pb-3.5 pt-1 flex gap-1.5">
                        <button onclick="openProductModal(${item.id})" class="flex-1 bg-primary hover:bg-primary-dark text-white text-[11px] sm:text-xs font-bold py-2 rounded-lg transition">
                            Chi tiết
                        </button>
                        <a href="https://zalo.me/0934722773" target="_blank" rel="noopener noreferrer" class="bg-amber-500 hover:bg-amber-600 text-white text-[11px] sm:text-xs font-bold px-2.5 py-2 rounded-lg transition flex items-center justify-center" title="Tư vấn qua Zalo">
                            Zalo
                        </a>
                    </div>
                </div>
            `).join('');
        }

        // Hàm lọc sản phẩm theo Danh mục Tab
        function filterProducts(category) {
            const buttons = document.querySelectorAll('.cat-tab-btn');
            buttons.forEach(btn => {
                if (btn.getAttribute('data-cat') === category) {
                    btn.className = "cat-tab-btn shrink-0 px-4 py-2 rounded-full text-xs sm:text-sm font-bold bg-primary text-white shadow-sm transition";
                } else {
                    btn.className = "cat-tab-btn shrink-0 px-4 py-2 rounded-full text-xs sm:text-sm font-bold bg-white text-slate-700 hover:bg-slate-100 border border-slate-200 transition";
                }
            });

            if (category === 'all') {
                renderProducts(PRODUCTS);
            } else {
                const filtered = PRODUCTS.filter(p => p.category === category);
                renderProducts(filtered);
            }
        }

        // Hàm tìm kiếm sản phẩm theo từ khóa
        function handleSearchProducts(keyword) {
            const cleanKey = keyword.trim().toLowerCase();
            if (!cleanKey) {
                renderProducts(PRODUCTS);
                return;
            }
            const filtered = PRODUCTS.filter(p => 
                p.name.toLowerCase().includes(cleanKey) || 
                p.categoryLabel.toLowerCase().includes(cleanKey) ||
                p.desc.toLowerCase().includes(cleanKey)
            );
            renderProducts(filtered);
        }

        // Hàm render Công trình tiêu biểu
        function renderProjects() {
            const grid = document.getElementById('projectGrid');
            grid.innerHTML = PROJECTS.map(proj => `
                <article class="bg-slate-50 rounded-xl overflow-hidden border border-slate-200/90 hover:shadow-md transition flex flex-col justify-between group">
                    <div>
                        <div class="relative aspect-[16/10] overflow-hidden bg-slate-200">
                            <img 
                                src="${proj.image}" 
                                onerror="this.src='https://placehold.co/600x400/03396c/ffffff?text=Cong+Trinh+Phuc+Hung'"
                                alt="${proj.title}" 
                                class="w-full h-full object-cover group-hover:scale-105 transition duration-500"
                            >
                            <div class="absolute top-2.5 left-2.5 z-10 bg-white/95 text-primary-dark border border-slate-200 px-2 py-1 rounded text-center leading-none shadow-md">
                                <span class="block text-xs sm:text-sm font-black">${proj.date}</span>
                                <span class="block text-[10px] font-bold uppercase mt-0.5">${proj.month}</span>
                            </div>
                            <span class="absolute bottom-2.5 right-2.5 z-10 bg-slate-900/80 text-amber-300 text-[10px] font-bold px-2.5 py-1 rounded shadow-md">
                                <i class="fa-solid fa-location-dot mr-1"></i>${proj.location}
                            </span>
                        </div>
                        <div class="p-3 sm:p-4">
                            <h3 class="font-bold text-xs sm:text-base text-slate-900 group-hover:text-primary transition line-clamp-2 leading-snug">
                                ${proj.title}
                            </h3>
                            <p class="text-[11px] sm:text-xs text-slate-600 mt-1.5 line-clamp-2 leading-relaxed">
                                ${proj.excerpt}
                            </p>
                        </div>
                    </div>
                    <div class="px-3 pb-3 sm:px-4 sm:pb-4">
                        <a href="#lien-he-bao-gia" onclick="prefillNote('${proj.title}')" class="inline-flex items-center gap-1 text-[11px] sm:text-xs font-bold text-primary hover:underline">
                            <span>Nhận báo giá công trình tương tự</span>
                            <i class="fa-solid fa-arrow-right text-[10px]"></i>
                        </a>
                    </div>
                </article>
            `).join('');
        }

        // Mở Modal Chi tiết sản phẩm
        function openProductModal(id) {
            const product = PRODUCTS.find(p => p.id === id);
            if (!product) return;
            document.getElementById('modalTitle').textContent = "Mã SP: " + product.code;
            document.getElementById('modalImg').src = product.image;
            document.getElementById('modalImg').alt = product.name;
            document.getElementById('modalCat').textContent = product.categoryLabel;
            document.getElementById('modalName').textContent = product.name;
            document.getElementById('modalPrice').textContent = product.price;
            document.getElementById('modalDesc').textContent = product.desc;

            const modal = document.getElementById('productModal');
            modal.classList.remove('hidden');
            modal.classList.add('flex');
        }

        function closeProductModal() {
            const modal = document.getElementById('productModal');
            modal.classList.add('hidden');
            modal.classList.remove('flex');
        }

        // Điền sẵn nội dung cần tư vấn và cuộn tới Form Báo Giá
        function prefillNote(text) {
            const noteEl = document.getElementById('custNote');
            if (noteEl) {
                noteEl.value = "Tôi muốn tư vấn & báo giá mẫu: " + text;
            }
        }

        function openConsultModal(topic) {
            prefillNote(topic);
            document.getElementById('lien-he-bao-gia').scrollIntoView({ behavior: 'smooth' });
        }

        // Xử lý gửi Form Báo Giá
        function submitQuoteForm(e) {
            e.preventDefault();
            const successBox = document.getElementById('quoteSuccessBox');
            successBox.classList.remove('hidden');
            document.getElementById('quoteForm').reset();
        }

        // Đóng/Mở Menu Mobile
        function toggleMobileMenu() {
            const overlay = document.getElementById('mobileMenuOverlay');
            overlay.classList.toggle('hidden');
        }

        // Khởi tạo dữ liệu khi tải trang & dọn sạch các dòng thừa nếu có
        window.onload = function() {
            // Xóa mọi text node thừa chứa <!DOCTYPE html> nếu trình duyệt hiển thị
            document.body.childNodes.forEach(node => {
                if (node.nodeType === Node.TEXT_NODE && node.textContent.includes('DOCTYPE')) {
                    node.remove();
                }
            });
            // Ẩn triệt để mọi thanh công cụ FLATSOME READY nếu còn lưu cache
            document.querySelectorAll('div, section, aside').forEach(el => {
                if (el.innerText && el.innerText.includes('FLATSOME READY') && el.tagName !== 'BODY') {
                    el.remove();
                }
            });

            renderProducts(PRODUCTS);
            renderProjects();
        };
    </script>
</body>
</html>
