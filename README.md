<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=5.0">
    <title>Vinh Thú Cưng - Pet Shop, Spa Grooming & Thú Y Đà Nẵng | vinhthucung.com</title>
    <meta name="description" content="Vinh Thú Cưng (vinhthucung.com) - Chuyên thức ăn, phụ kiện, dinh dưỡng, thuốc thú y, dịch vụ tắm sấy Grooming, cắt tỉa Spa và khách sạn thú cưng tại 26 Trần Quý Cáp, Phường Bàn Thạch, Tp. Đà Nẵng. Hotline: 0984.244.001 - CSKH: 0399.830.237.">

    <!-- OpenGraph Thumbnail là ảnh Logo trang web khi gửi link chia sẻ -->
    <meta property="og:type" content="website">
    <meta property="og:site_name" content="Vinh Thú Cưng - vinhthucung.com">
    <meta property="og:title" content="Vinh Thú Cưng - Siêu Thị Thú Cưng & Spa Grooming Đà Nẵng">
    <meta property="og:description" content="Chuyên sỉ lẻ thức ăn, phụ kiện, dinh dưỡng, thuốc thú y & Spa Grooming chó mèo uy tín tại 26 Trần Quý Cáp, P. Bàn Thạch, Tp. Đà Nẵng. ĐT: 0984.244.001">
    <meta property="og:url" content="https://vinhthucung.com">
    <meta property="og:image" content="https://lh3.googleusercontent.com/d/10sBXJ8sDRq-BhJc4F8EGqjYeuB3gKxmB=w800">
    <meta property="og:image:alt" content="Logo Vinh Thú Cưng - vinhthucung.com">
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:image" content="https://lh3.googleusercontent.com/d/10sBXJ8sDRq-BhJc4F8EGqjYeuB3gKxmB=w800">
    <link rel="icon" href="https://lh3.googleusercontent.com/d/10sBXJ8sDRq-BhJc4F8EGqjYeuB3gKxmB=w200">

    <!-- Tailwind CSS & Font Awesome & Google Fonts (Inter) -->
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">

    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                    },
                    colors: {
                        brand: {
                            DEFAULT: '#ea580c', // Màu cam đỏ chủ đạo theo tông logo & mẫu Petshop
                            dark: '#c2410c',
                            light: '#fff7ed',
                            accent: '#0284c7',
                            navy: '#1e293b'
                        }
                    },
                    maxWidth: {
                        'flatsome': '1500px'
                    }
                }
            }
        }
    </script>

    <style>
        /* Chống tràn viền và chống lệch phải tuyệt đối trên mọi thiết bị */
        *, *::before, *::after {
            box-sizing: border-box;
        }
        html, body {
            margin: 0;
            padding: 0;
            width: 100%;
            max-width: 100%;
            overflow-x: hidden;
            font-family: 'Inter', sans-serif;
            background-color: #f8fafc;
            color: #1e293b;
            scroll-behavior: smooth;
        }

        /* Chuẩn khung 1500px trên máy tính theo yêu cầu */
        .container-1500 {
            width: 100%;
            max-width: 1500px;
            margin-left: auto;
            margin-right: auto;
            padding-left: 12px;
            padding-right: 12px;
        }
        @media (min-width: 1024px) {
            .container-1500 {
                padding-left: 20px;
                padding-right: 20px;
            }
        }

        /* Tối ưu tên danh mục: Luôn viết liền trên 1 hàng, không bao giờ tự ngắt chữ xuống dòng */
        .cat-single-line {
            white-space: nowrap !important;
            display: inline-flex;
            align-items: center;
        }

        /* Tên sản phẩm hiển thị đầy đủ, tự xuống dòng gọn trong thẻ, không tràn, không mất chữ */
        .product-title-full {
            white-space: normal;
            word-break: break-word;
            overflow-wrap: break-word;
            line-height: 1.38;
        }

        /* Hiệu ứng thẻ sản phẩm chuẩn Flatsome */
        .flatsome-product-box {
            transition: transform 0.2s ease, box-shadow 0.2s ease;
        }
        .flatsome-product-box:hover {
            transform: translateY(-3px);
            box-shadow: 0 10px 20px -5px rgba(0, 0, 0, 0.08);
        }

        /* Nút giảm giá góc trên bên trái chuẩn Flatsome */
        .flatsome-badge-sale {
            position: absolute;
            top: 8px;
            left: 8px;
            z-index: 10;
            background-color: #dc2626;
            color: #ffffff;
            font-weight: 700;
            font-size: 11px;
            line-height: 1;
            padding: 5px 7px;
            border-radius: 4px;
            box-shadow: 0 2px 4px rgba(220, 38, 38, 0.25);
        }

        /* Dropdown danh mục trên máy tính */
        .mega-dropdown:hover .mega-dropdown-menu {
            display: block;
        }

        /* Hiệu ứng rung nhẹ cho nút Hotline/Zalo nổi */
        @keyframes pulse-ring {
            0% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(234, 88, 12, 0.6); }
            70% { transform: scale(1); box-shadow: 0 0 0 10px rgba(234, 88, 12, 0); }
            100% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(234, 88, 12, 0); }
        }
        .contact-pulse {
            animation: pulse-ring 2s infinite;
        }
    </style>
</head>
<body class="bg-slate-50 text-slate-800">

    <!-- ==================== HEADER FLATSOME (KHÔNG ĐỂ NÚT GỌI NGAY TRÊN HEADER ĐỂ TRÁNH TRÀN VIỀN) ==================== -->
    <header id="header" class="w-full bg-white shadow-sm sticky top-0 z-40">
        <!-- Top Bar đơn giản chuẩn Flatsome -->
        <div id="top-bar" class="bg-brand-navy text-white text-[11.5px] py-1.5 border-b border-slate-700">
            <div class="container-1500 flex flex-wrap items-center justify-between gap-2">
                <div class="flex items-center gap-3 overflow-hidden">
                    <span class="truncate">
                        <i class="fa-solid fa-paw text-amber-400 mr-1"></i>
                        Chào mừng bạn đến với <strong>Vinh Thú Cưng (vinhthucung.com)</strong> - Pet Shop, Grooming Spa & Thú Y
                    </span>
                </div>
                <div class="hidden md:flex items-center gap-4 text-slate-200 whitespace-nowrap">
                    <span><i class="fa-solid fa-location-dot text-amber-400 mr-1"></i>26 Trần Quý Cáp, P. Bàn Thạch, Tp. Đà Nẵng</span>
                    <span>|</span>
                    <a href="#section-baogia" class="hover:text-amber-300 transition"><i class="fa-solid fa-file-invoice mr-1"></i>Yêu cầu báo giá</a>
                    <span>|</span>
                    <a href="#section-bando-fanpage" class="hover:text-amber-300 transition"><i class="fa-solid fa-map-location-dot mr-1"></i>Bản đồ & Fanpage</a>
                </div>
            </div>
        </div>

        <!-- Header Main: Logo nhỏ gọn + Thanh tìm kiếm + Giỏ hàng (Không có nút gọi ngay tránh tràn viền) -->
        <div id="header-main" class="py-2.5 bg-white border-b border-slate-100">
            <div class="container-1500 flex items-center justify-between gap-2.5 md:gap-6">
                
                <!-- Nút mở Menu Danh Mục trên Điện Thoại -->
                <button onclick="toggleMobileMenu()" aria-label="Mở danh mục" class="lg:hidden p-2 rounded-lg border border-slate-200 text-slate-700 hover:bg-slate-100 shrink-0">
                    <i class="fa-solid fa-bars text-lg"></i>
                </button>

                <!-- Logo chỉnh gọn nhỏ lại theo yêu cầu -->
                <a href="#" class="flex items-center gap-2.5 shrink-0 group">
                    <div class="w-10 h-10 md:w-11 md:h-11 rounded-full overflow-hidden border border-orange-200 bg-white flex items-center justify-center p-0.5 shadow-sm shrink-0">
                        <img id="site-logo"
                             src="https://lh3.googleusercontent.com/d/10sBXJ8sDRq-BhJc4F8EGqjYeuB3gKxmB=w300"
                             onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=10sBXJ8sDRq-BhJc4F8EGqjYeuB3gKxmB&sz=w300';"
                             alt="Logo Vinh Thú Cưng"
                             class="w-full h-full object-contain rounded-full">
                    </div>
                    <div class="flex flex-col">
                        <span class="text-base md:text-lg font-extrabold tracking-tight text-brand leading-none">VINH THÚ CƯNG</span>
                        <span class="text-[10.5px] md:text-[11px] font-medium text-slate-500 mt-0.5">vinhthucung.com</span>
                    </div>
                </a>

                <!-- Thanh tìm kiếm sản phẩm chuẩn mẫu Petshophanoi -->
                <div class="hidden sm:flex flex-1 max-w-2xl mx-auto">
                    <div class="flex w-full border-2 border-brand rounded-lg overflow-hidden bg-white">
                        <select id="search-category-select" onchange="filterBySearch()" class="bg-slate-50 text-slate-700 text-xs font-medium px-2.5 border-r border-slate-200 focus:outline-none hidden md:block">
                            <option value="all">Tất cả danh mục</option>
                            <option value="cho">Dành cho Chó</option>
                            <option value="meo">Dành cho Mèo</option>
                            <option value="phukien">Dây dắt & Phụ kiện</option>
                            <option value="dinhduong">Bổ sung dinh dưỡng</option>
                            <option value="thuy">Thuốc Thú Y</option>
                            <option value="dichvu">Dịch vụ Spa - Hotel</option>
                        </select>
                        <input id="search-input" type="text" oninput="filterBySearch()" placeholder="Tìm thức ăn chó mèo, cát vệ sinh, phụ kiện, thuốc thú y..." class="w-full px-3 py-2 text-xs md:text-sm focus:outline-none">
                        <button onclick="filterBySearch()" class="bg-brand hover:bg-brand-dark text-white px-4 text-xs md:text-sm font-semibold transition shrink-0">
                            <i class="fa-solid fa-magnifying-glass"></i>
                        </button>
                    </div>
                </div>

                <!-- Giỏ hàng & Tra cứu đơn (Gọn gàng, không tràn viền) -->
                <div class="flex items-center gap-2 shrink-0">
                    <a href="#section-baogia" class="hidden xl:flex items-center gap-1.5 text-xs font-semibold text-slate-700 hover:text-brand px-2.5 py-2 rounded-lg border border-slate-200 bg-slate-50">
                        <i class="fa-solid fa-clipboard-check text-brand"></i>
                        <span>Báo giá sỉ/lẻ</span>
                    </a>
                    <button onclick="openCartModal()" class="flex items-center gap-2 bg-orange-50 hover:bg-orange-100 text-brand border border-orange-200 px-3 py-2 rounded-lg transition text-xs font-bold">
                        <i class="fa-solid fa-cart-shopping text-sm"></i>
                        <span class="hidden md:inline">Giỏ hàng</span>
                        <span id="cart-count-badge" class="bg-brand text-white text-[11px] px-1.5 py-0.5 rounded-full leading-none">0</span>
                    </button>
                </div>
            </div>

            <!-- Thanh tìm kiếm trên màn hình điện thoại nhỏ -->
            <div class="container-1500 sm:hidden mt-2">
                <div class="flex w-full border border-brand rounded-lg overflow-hidden bg-white">
                    <input id="search-input-mobile" type="text" oninput="filterBySearchMobile()" placeholder="Tìm sản phẩm cho thú cưng..." class="w-full px-3 py-1.5 text-xs focus:outline-none">
                    <button onclick="filterBySearchMobile()" class="bg-brand text-white px-3 text-xs font-semibold">
                        <i class="fa-solid fa-magnifying-glass"></i>
                    </button>
                </div>
            </div>
        </div>

        <!-- Thanh Danh Mục Ngang Trên Máy Tính (Chữ nhỏ gọn, viết liền 1 hàng không tự ngắt dòng tên danh mục) -->
        <nav id="wide-nav" class="hidden lg:block bg-brand text-white">
            <div class="container-1500 flex items-center gap-3">
                
                <!-- Nút Mega Menu Danh Mục Sản Phẩm giống Petshophanoi -->
                <div class="relative mega-dropdown shrink-0">
                    <button class="flex items-center gap-2 bg-brand-dark px-3.5 py-2.5 text-[12.5px] font-bold uppercase tracking-wide cat-single-line cursor-pointer">
                        <i class="fa-solid fa-bars"></i>
                        <span>DANH MỤC SẢN PHẨM</span>
                        <i class="fa-solid fa-chevron-down text-[10px] ml-1"></i>
                    </button>
                    <!-- Menu thả xuống đầy đủ danh mục mẫu Petshophanoi -->
                    <div class="mega-dropdown-menu hidden absolute left-0 top-full w-72 bg-white text-slate-800 shadow-xl border border-slate-200 rounded-b-lg z-50 py-1.5 text-[12.5px]">
                        <a href="#sec-hang-moi" class="flex items-center justify-between px-3.5 py-2 hover:bg-orange-50 hover:text-brand font-semibold border-b border-slate-100">
                            <span class="cat-single-line"><i class="fa-solid fa-fire text-red-500 w-5"></i>Sản Phẩm Mới & Khuyến Mãi</span>
                            <i class="fa-solid fa-angle-right text-[10px] text-slate-400"></i>
                        </a>
                        <a href="#sec-danh-cho-cho" class="flex items-center justify-between px-3.5 py-2 hover:bg-orange-50 hover:text-brand font-medium border-b border-slate-100">
                            <span class="cat-single-line"><i class="fa-solid fa-dog text-brand w-5"></i>Dành Cho Chó (Thức ăn, Đồ dùng)</span>
                            <i class="fa-solid fa-angle-right text-[10px] text-slate-400"></i>
                        </a>
                        <a href="#sec-danh-cho-meo" class="flex items-center justify-between px-3.5 py-2 hover:bg-orange-50 hover:text-brand font-medium border-b border-slate-100">
                            <span class="cat-single-line"><i class="fa-solid fa-cat text-amber-600 w-5"></i>Dành Cho Mèo (Hạt, Pate, Cát)</span>
                            <i class="fa-solid fa-angle-right text-[10px] text-slate-400"></i>
                        </a>
                        <a href="#sec-phukien-thuy" onclick="filterSubCategory('sec-phukien-thuy', 'daydat')" class="flex items-center justify-between px-3.5 py-2 hover:bg-orange-50 hover:text-brand font-medium border-b border-slate-100">
                            <span class="cat-single-line"><i class="fa-solid fa-link text-sky-600 w-5"></i>Dây Dắt, Vòng Cổ, Phụ Kiện</span>
                            <i class="fa-solid fa-angle-right text-[10px] text-slate-400"></i>
                        </a>
                        <a href="#sec-phukien-thuy" onclick="filterSubCategory('sec-phukien-thuy', 'quanao')" class="flex items-center justify-between px-3.5 py-2 hover:bg-orange-50 hover:text-brand font-medium border-b border-slate-100">
                            <span class="cat-single-line"><i class="fa-solid fa-shirt text-pink-500 w-5"></i>Quần Áo, Bát Ăn, Lồng Vận Chuyển</span>
                            <i class="fa-solid fa-angle-right text-[10px] text-slate-400"></i>
                        </a>
                        <a href="#sec-phukien-thuy" onclick="filterSubCategory('sec-phukien-thuy', 'suatam')" class="flex items-center justify-between px-3.5 py-2 hover:bg-orange-50 hover:text-brand font-medium border-b border-slate-100">
                            <span class="cat-single-line"><i class="fa-solid fa-pump-soap text-teal-600 w-5"></i>Sữa Tắm, Khử Mùi, Chăm Sóc</span>
                            <i class="fa-solid fa-angle-right text-[10px] text-slate-400"></i>
                        </a>
                        <a href="#sec-phukien-thuy" onclick="filterSubCategory('sec-phukien-thuy', 'dinhduong')" class="flex items-center justify-between px-3.5 py-2 hover:bg-orange-50 hover:text-brand font-medium border-b border-slate-100">
                            <span class="cat-single-line"><i class="fa-solid fa-capsules text-emerald-600 w-5"></i>Bổ Sung Dinh Dưỡng (Canxi, Vitamin)</span>
                            <i class="fa-solid fa-angle-right text-[10px] text-slate-400"></i>
                        </a>
                        <a href="#sec-phukien-thuy" onclick="filterSubCategory('sec-phukien-thuy', 'thuy')" class="flex items-center justify-between px-3.5 py-2 hover:bg-orange-50 hover:text-brand font-medium border-b border-slate-100">
                            <span class="cat-single-line"><i class="fa-solid fa-kit-medical text-red-600 w-5"></i>Thú Y (Trị Ve Bọ, Nấm Ghẻ, Đường Ruột)</span>
                            <i class="fa-solid fa-angle-right text-[10px] text-slate-400"></i>
                        </a>
                        <a href="#section-dichvu-baogia" class="flex items-center justify-between px-3.5 py-2 hover:bg-orange-50 hover:text-brand font-medium">
                            <span class="cat-single-line"><i class="fa-solid fa-Scissors text-purple-600 w-5"></i>Dịch Vụ Tắm Sấy, Cắt Tỉa Spa & Hotel</span>
                            <i class="fa-solid fa-angle-right text-[10px] text-slate-400"></i>
                        </a>
                    </div>
                </div>

                <!-- Danh sách tên danh mục trên máy tính: chữ nhỏ gọn, viết liền trên 1 hàng hoặc tự rớt nguyên cụm sang hàng 2, tuyệt đối không ngắt dòng giữa chừng tên danh mục -->
                <div class="flex flex-wrap items-center gap-x-3.5 gap-y-1 py-1.5 flex-1">
                    <a href="#sec-hang-moi" class="cat-single-line text-[12px] xl:text-[12.5px] font-semibold text-white hover:text-amber-200 transition py-0.5">
                        Sản Phẩm Mới
                    </a>
                    <a href="#sec-danh-cho-cho" class="cat-single-line text-[12px] xl:text-[12.5px] font-semibold text-white hover:text-amber-200 transition py-0.5">
                        Dành Cho Chó
                    </a>
                    <a href="#sec-danh-cho-meo" class="cat-single-line text-[12px] xl:text-[12.5px] font-semibold text-white hover:text-amber-200 transition py-0.5">
                        Dành Cho Mèo
                    </a>
                    <a href="#sec-phukien-thuy" onclick="filterSubCategory('sec-phukien-thuy', 'daydat')" class="cat-single-line text-[12px] xl:text-[12.5px] font-semibold text-white hover:text-amber-200 transition py-0.5">
                        Dây Dắt & Phụ Kiện
                    </a>
                    <a href="#sec-phukien-thuy" onclick="filterSubCategory('sec-phukien-thuy', 'quanao')" class="cat-single-line text-[12px] xl:text-[12.5px] font-semibold text-white hover:text-amber-200 transition py-0.5">
                        Quần Áo & Chuồng Đệm
                    </a>
                    <a href="#sec-phukien-thuy" onclick="filterSubCategory('sec-phukien-thuy', 'suatam')" class="cat-single-line text-[12px] xl:text-[12.5px] font-semibold text-white hover:text-amber-200 transition py-0.5">
                        Sữa Tắm & Chăm Sóc
                    </a>
                    <a href="#sec-phukien-thuy" onclick="filterSubCategory('sec-phukien-thuy', 'dinhduong')" class="cat-single-line text-[12px] xl:text-[12.5px] font-semibold text-white hover:text-amber-200 transition py-0.5">
                        Bổ Sung Dinh Dưỡng
                    </a>
                    <a href="#sec-phukien-thuy" onclick="filterSubCategory('sec-phukien-thuy', 'thuy')" class="cat-single-line text-[12px] xl:text-[12.5px] font-semibold text-white hover:text-amber-200 transition py-0.5">
                        Thuốc Thú Y
                    </a>
                    <a href="#section-dichvu-baogia" class="cat-single-line text-[12px] xl:text-[12.5px] font-semibold text-white hover:text-amber-200 transition py-0.5">
                        Dịch Vụ Spa & Hotel
                    </a>
                    <a href="#section-baiviet" class="cat-single-line text-[12px] xl:text-[12.5px] font-semibold text-white hover:text-amber-200 transition py-0.5">
                        Bài Viết Thú Cưng
                    </a>
                    <a href="#section-bando-fanpage" class="cat-single-line text-[12px] xl:text-[12.5px] font-semibold text-white hover:text-amber-200 transition py-0.5">
                        Liên Hệ
                    </a>
                </div>
            </div>
        </nav>
    </header>

    <!-- Drawer Menu Danh Mục trên Điện Thoại -->
    <div id="mobile-menu-backdrop" onclick="toggleMobileMenu()" class="fixed inset-0 bg-black/50 z-50 hidden"></div>
    <aside id="mobile-menu-drawer" class="fixed top-0 left-0 bottom-0 w-72 max-w-[85vw] bg-white z-50 shadow-2xl transform -translate-x-full transition-transform duration-300 flex flex-col">
        <div class="p-3.5 bg-brand text-white flex items-center justify-between">
            <span class="font-bold text-sm uppercase tracking-wide">Danh Mục Vinh Thú Cưng</span>
            <button onclick="toggleMobileMenu()" class="p-1 text-white hover:text-amber-200">
                <i class="fa-solid fa-xmark text-lg"></i>
            </button>
        </div>
        <div class="p-3 overflow-y-auto flex-1 divide-y divide-slate-100 text-xs font-semibold text-slate-700">
            <a href="#sec-hang-moi" onclick="toggleMobileMenu()" class="flex items-center gap-2.5 py-2.5 hover:text-brand"><i class="fa-solid fa-fire text-red-500 w-4"></i>Sản Phẩm Mới</a>
            <a href="#sec-danh-cho-cho" onclick="toggleMobileMenu()" class="flex items-center gap-2.5 py-2.5 hover:text-brand"><i class="fa-solid fa-dog text-brand w-4"></i>Dành Cho Chó (Thức Ăn, Đồ Chơi, Đồ Dùng)</a>
            <a href="#sec-danh-cho-meo" onclick="toggleMobileMenu()" class="flex items-center gap-2.5 py-2.5 hover:text-brand"><i class="fa-solid fa-cat text-amber-600 w-4"></i>Dành Cho Mèo (Thức Ăn, Cát, Nhà Vệ Sinh)</a>
            <a href="#sec-phukien-thuy" onclick="toggleMobileMenu(); filterSubCategory('sec-phukien-thuy', 'daydat')" class="flex items-center gap-2.5 py-2.5 hover:text-brand"><i class="fa-solid fa-link text-sky-600 w-4"></i>Dây Dắt, Vòng Cổ, Phụ Kiện</a>
            <a href="#sec-phukien-thuy" onclick="toggleMobileMenu(); filterSubCategory('sec-phukien-thuy', 'quanao')" class="flex items-center gap-2.5 py-2.5 hover:text-brand"><i class="fa-solid fa-shirt text-pink-500 w-4"></i>Quần Áo, Bát Ăn, Lồng Vận Chuyển</a>
            <a href="#sec-phukien-thuy" onclick="toggleMobileMenu(); filterSubCategory('sec-phukien-thuy', 'suatam')" class="flex items-center gap-2.5 py-2.5 hover:text-brand"><i class="fa-solid fa-pump-soap text-teal-600 w-4"></i>Sữa Tắm, Khử Mùi, Chăm Sóc</a>
            <a href="#sec-phukien-thuy" onclick="toggleMobileMenu(); filterSubCategory('sec-phukien-thuy', 'dinhduong')" class="flex items-center gap-2.5 py-2.5 hover:text-brand"><i class="fa-solid fa-capsules text-emerald-600 w-4"></i>Bổ Sung Dinh Dưỡng (Canxi, Vitamin)</a>
            <a href="#sec-phukien-thuy" onclick="toggleMobileMenu(); filterSubCategory('sec-phukien-thuy', 'thuy')" class="flex items-center gap-2.5 py-2.5 hover:text-brand"><i class="fa-solid fa-kit-medical text-red-600 w-4"></i>Thuốc Thú Y (Trị Ve, Nấm Ghẻ, Đường Ruột)</a>
            <a href="#section-dichvu-baogia" onclick="toggleMobileMenu()" class="flex items-center gap-2.5 py-2.5 hover:text-brand"><i class="fa-solid fa-scissors text-purple-600 w-4"></i>Dịch Vụ Tắm Sấy, Cắt Tỉa Spa & Hotel</a>
            <a href="#section-baogia" onclick="toggleMobileMenu()" class="flex items-center gap-2.5 py-2.5 hover:text-brand"><i class="fa-solid fa-file-signature text-brand w-4"></i>Form Yêu Cầu & Báo Giá</a>
            <a href="#section-baiviet" onclick="toggleMobileMenu()" class="flex items-center gap-2.5 py-2.5 hover:text-brand"><i class="fa-solid fa-newspaper text-blue-600 w-4"></i>Chuyên Mục Bài Viết</a>
            <a href="#section-bando-fanpage" onclick="toggleMobileMenu()" class="flex items-center gap-2.5 py-2.5 hover:text-brand"><i class="fa-solid fa-map-location-dot text-emerald-600 w-4"></i>Bản Đồ & Fanpage</a>
        </div>
        <div class="p-3 bg-slate-50 border-t border-slate-200 text-[11.5px] text-slate-600 space-y-1">
            <div><strong>Địa chỉ:</strong> 26 Trần Quý Cáp, P. Bàn Thạch, Tp. Đà Nẵng</div>
            <div><strong>Hotline:</strong> 0984.244.001 | <strong>CSKH:</strong> 0399.830.237</div>
        </div>
    </aside>

    <!-- ==================== MAIN CONTENT (UX BUILDER FLATSOME SECTIONS) ==================== -->
    <main id="main" class="w-full">

        <!-- SECTION 1: SLIDER 2 BANNER TỰ TRƯỢT KÍCH THƯỚC BẰNG NHAU (RIÊNG BIỆT CHO MÁY TÍNH VÀ ĐIỆN THOẠI) -->
        <section id="section-slider" class="py-3">
            <div class="container-1500">
                <div class="relative w-full overflow-hidden rounded-xl shadow-sm border border-slate-200 bg-white">
                    
                    <!-- SLIDE 1 -->
                    <div class="banner-slide w-full transition-opacity duration-500 block" data-slide="0">
                        
                        <!-- Banner 1 Giao diện Máy Tính (Kích thước cố định 360px bằng Slide 2, chữ nhỏ gọn nằm hoàn toàn bên trong) -->
                        <div class="hidden md:flex w-full h-[350px] lg:h-[370px] bg-gradient-to-r from-[#fff3e6] via-[#ffe6cc] to-[#ffd8b3] items-center justify-between px-10 lg:px-16 py-6 relative overflow-hidden">
                            <div class="w-7/12 z-10 pr-6 space-y-2.5">
                                <div class="inline-flex items-center gap-1.5 bg-brand text-white text-xs font-bold px-3 py-1 rounded-full">
                                    <i class="fa-solid fa-paw"></i>
                                    <span>SIÊU THỊ THÚ CƯNG VINH THÚ CƯNG - VINHTHUCUNG.COM</span>
                                </div>
                                <h1 class="text-xl lg:text-2xl xl:text-3xl font-extrabold text-slate-900 leading-tight">
                                    Thức Ăn, Phụ Kiện, Dinh Dưỡng & Thuốc Thú Y Chính Hãng Cho Chó Mèo
                                </h1>
                                <p class="text-xs lg:text-sm text-slate-700 leading-relaxed max-w-xl">
                                    Đầy đủ hạt dinh dưỡng, pate, cát vệ sinh, dây dắt, quần áo, vitamin và thuốc thú y. Tư vấn tận tâm bởi Bác sỹ Thú Y Vinh - Giao hàng nhanh tại Đà Nẵng & toàn quốc.
                                </p>
                                <div class="pt-1 flex flex-wrap items-center gap-3 text-xs font-semibold text-slate-800">
                                    <span class="bg-white/90 px-3 py-1.5 rounded-lg border border-orange-200"><i class="fa-solid fa-location-dot text-brand mr-1"></i>26 Trần Quý Cáp, P. Bàn Thạch, Tp. Đà Nẵng</span>
                                    <span class="bg-white/90 px-3 py-1.5 rounded-lg border border-orange-200"><i class="fa-solid fa-phone text-brand mr-1"></i>SĐT: 0984.244.001 - CSKH: 0399.830.237</span>
                                </div>
                                <div class="pt-1 flex items-center gap-3">
                                    <a href="#sec-hang-moi" class="bg-brand hover:bg-brand-dark text-white text-xs font-bold px-4 py-2.5 rounded-lg shadow transition">
                                        Mua Sắm Ngay
                                    </a>
                                    <a href="#section-baogia" class="bg-white hover:bg-slate-50 text-brand border border-brand text-xs font-bold px-4 py-2.5 rounded-lg transition">
                                        Nhận Báo Giá Sỉ & Lẻ
                                    </a>
                                </div>
                            </div>
                            <div class="w-5/12 h-full flex items-center justify-center z-10">
                                <div class="grid grid-cols-2 gap-3 w-full max-w-[380px] bg-white/80 p-3 rounded-2xl border border-orange-200 shadow-sm">
                                    <img src="https://lh3.googleusercontent.com/d/1Dhygrqmccuyq2UFGHIbUfWqbhxSx5Jux=w500"
                                         onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1Dhygrqmccuyq2UFGHIbUfWqbhxSx5Jux&sz=w500';"
                                         alt="Sản phẩm Vinh Thú Cưng 1" class="w-full h-32 object-contain bg-white rounded-xl p-1 border border-slate-100">
                                    <img src="https://lh3.googleusercontent.com/d/1Fn8ln_cFgfD-w7rO8MfBBUXXOJdp--Ie=w500"
                                         onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1Fn8ln_cFgfD-w7rO8MfBBUXXOJdp--Ie&sz=w500';"
                                         alt="Sản phẩm Vinh Thú Cưng 2" class="w-full h-32 object-contain bg-white rounded-xl p-1 border border-slate-100">
                                    <img src="https://lh3.googleusercontent.com/d/1pAVitSGZpVZIaCSpu0QBcveQTxka7fzh=w500"
                                         onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1pAVitSGZpVZIaCSpu0QBcveQTxka7fzh&sz=w500';"
                                         alt="Sản phẩm Vinh Thú Cưng 3" class="w-full h-28 object-contain bg-white rounded-xl p-1 border border-slate-100">
                                    <img src="https://lh3.googleusercontent.com/d/1gFJo3LF2Sdb_yXdnzJFmsamxXdvuRclr=w500"
                                         onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1gFJo3LF2Sdb_yXdnzJFmsamxXdvuRclr&sz=w500';"
                                         alt="Sản phẩm Vinh Thú Cưng 4" class="w-full h-28 object-contain bg-white rounded-xl p-1 border border-slate-100">
                                </div>
                            </div>
                        </div>

                        <!-- Banner 1 Thiết Kế Riêng Cho Điện Thoại (Khác với máy tính, chữ nhỏ gọn nằm trọn bên trong, không tràn viền) -->
                        <div class="flex md:hidden w-full h-[215px] bg-gradient-to-br from-[#fff3e6] to-[#ffd8b3] px-4 py-3.5 items-center justify-between gap-2.5 overflow-hidden">
                            <div class="w-[62%] space-y-1.5 pr-1">
                                <span class="inline-block bg-brand text-white text-[10px] font-bold px-2 py-0.5 rounded">
                                    VINHTHUCUNG.COM
                                </span>
                                <h2 class="text-[13.5px] font-extrabold text-slate-900 leading-snug">
                                    Siêu Thị Thức Ăn, Phụ Kiện & Thuốc Thú Y Chó Mèo
                                </h2>
                                <p class="text-[11px] text-slate-700 leading-tight">
                                    ĐC: 26 Trần Quý Cáp, P. Bàn Thạch, Đà Nẵng. ĐT: 0984.244.001
                                </p>
                                <div class="pt-1">
                                    <a href="#sec-hang-moi" class="inline-block bg-brand text-white text-[11px] font-bold px-3 py-1.5 rounded-md">
                                        Xem Sản Phẩm
                                    </a>
                                </div>
                            </div>
                            <div class="w-[38%] h-full flex items-center justify-center">
                                <div class="w-full h-[160px] bg-white/90 rounded-xl p-1.5 border border-orange-200 flex items-center justify-center">
                                    <img src="https://lh3.googleusercontent.com/d/1Dhygrqmccuyq2UFGHIbUfWqbhxSx5Jux=w400"
                                         onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1Dhygrqmccuyq2UFGHIbUfWqbhxSx5Jux&sz=w400';"
                                         alt="Banner Mobile Vinh Thú Cưng 1" class="max-h-full max-w-full object-contain rounded-lg">
                                </div>
                            </div>
                        </div>

                    </div>

                    <!-- SLIDE 2 -->
                    <div class="banner-slide w-full transition-opacity duration-500 hidden" data-slide="1">
                        
                        <!-- Banner 2 Giao diện Máy Tính (Kích thước cố định 360px bằng Slide 1, chữ nhỏ gọn nằm hoàn toàn bên trong) -->
                        <div class="hidden md:flex w-full h-[350px] lg:h-[370px] bg-gradient-to-r from-[#e0f2fe] via-[#bae6fd] to-[#e0f2fe] items-center justify-between px-10 lg:px-16 py-6 relative overflow-hidden">
                            <div class="w-7/12 z-10 pr-6 space-y-2.5">
                                <div class="inline-flex items-center gap-1.5 bg-sky-700 text-white text-xs font-bold px-3 py-1 rounded-full">
                                    <i class="fa-solid fa-scissors"></i>
                                    <span>SPA GROOMING & HOTEL THÚ CƯNG - LOVE PETS</span>
                                </div>
                                <h2 class="text-xl lg:text-2xl xl:text-3xl font-extrabold text-slate-900 leading-tight">
                                    Dịch Vụ Tắm Sấy, Cắt Tỉa Lông Spa & Trông Giữ Thú Cưng Chuẩn Thú Y
                                </h2>
                                <p class="text-xs lg:text-sm text-slate-700 leading-relaxed max-w-xl">
                                    Quy trình kiểm tra da lông, vệ sinh tai, cắt mài móng, tắm sấy khử mùi và cắt tỉa tạo kiểu chuyên nghiệp. Phòng lưu trú Hotel sạch sẽ, khử khuẩn định kỳ mỗi ngày.
                                </p>
                                <div class="pt-1 flex flex-wrap items-center gap-3 text-xs font-semibold text-slate-800">
                                    <span class="bg-white/90 px-3 py-1.5 rounded-lg border border-sky-200"><i class="fa-solid fa-phone-volume text-sky-700 mr-1"></i>Đặt lịch Spa: 0984.244.001</span>
                                    <span class="bg-white/90 px-3 py-1.5 rounded-lg border border-sky-200"><i class="fa-solid fa-headset text-sky-700 mr-1"></i>CSKH: 0399.830.237</span>
                                </div>
                                <div class="pt-1 flex items-center gap-3">
                                    <a href="#section-dichvu-baogia" class="bg-sky-700 hover:bg-sky-800 text-white text-xs font-bold px-4 py-2.5 rounded-lg shadow transition">
                                        Đặt Lịch Spa / Hotel
                                    </a>
                                    <a href="#section-bando-fanpage" class="bg-white hover:bg-slate-50 text-sky-700 border border-sky-700 text-xs font-bold px-4 py-2.5 rounded-lg transition">
                                        Xem Chỉ Đường Map
                                    </a>
                                </div>
                            </div>
                            <div class="w-5/12 h-full flex items-center justify-center z-10">
                                <div class="grid grid-cols-2 gap-3 w-full max-w-[380px] bg-white/80 p-3 rounded-2xl border border-sky-200 shadow-sm">
                                    <img src="https://lh3.googleusercontent.com/d/1mbajwSDtUUSFqnciTNIp0aQQi6zyONhE=w500"
                                         onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1mbajwSDtUUSFqnciTNIp0aQQi6zyONhE&sz=w500';"
                                         alt="Sản phẩm Vinh Thú Cưng 5" class="w-full h-32 object-contain bg-white rounded-xl p-1 border border-slate-100">
                                    <img src="https://lh3.googleusercontent.com/d/1BCxG9MVjrlU7Ivbaye3l55ktJcCWsgOP=w500"
                                         onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1BCxG9MVjrlU7Ivbaye3l55ktJcCWsgOP&sz=w500';"
                                         alt="Sản phẩm Vinh Thú Cưng 6" class="w-full h-32 object-contain bg-white rounded-xl p-1 border border-slate-100">
                                    <img src="https://lh3.googleusercontent.com/d/1sdl7mYe2wOMTeYTEDCM61rS0b_UfHxWz=w500"
                                         onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1sdl7mYe2wOMTeYTEDCM61rS0b_UfHxWz&sz=w500';"
                                         alt="Sản phẩm Vinh Thú Cưng 7" class="w-full h-28 object-contain bg-white rounded-xl p-1 border border-slate-100">
                                    <img src="https://lh3.googleusercontent.com/d/1Wp4-K3ccXMaBEye2tPOJKWcgBEgeOOjF=w500"
                                         onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1Wp4-K3ccXMaBEye2tPOJKWcgBEgeOOjF&sz=w500';"
                                         alt="Sản phẩm Vinh Thú Cưng 8" class="w-full h-28 object-contain bg-white rounded-xl p-1 border border-slate-100">
                                </div>
                            </div>
                        </div>

                        <!-- Banner 2 Thiết Kế Riêng Cho Điện Thoại (Kích thước bằng Banner 1 Điện Thoại 215px, chữ gọn bên trong) -->
                        <div class="flex md:hidden w-full h-[215px] bg-gradient-to-br from-[#e0f2fe] to-[#bae6fd] px-4 py-3.5 items-center justify-between gap-2.5 overflow-hidden">
                            <div class="w-[62%] space-y-1.5 pr-1">
                                <span class="inline-block bg-sky-700 text-white text-[10px] font-bold px-2 py-0.5 rounded">
                                    SPA & HOTEL THÚ CƯNG
                                </span>
                                <h2 class="text-[13.5px] font-extrabold text-slate-900 leading-snug">
                                    Tắm Sấy Grooming, Cắt Tỉa Lông & Trông Giữ Chó Mèo
                                </h2>
                                <p class="text-[11px] text-slate-700 leading-tight">
                                    Hotline: 0984.244.001 - CSKH: 0399.830.237
                                </p>
                                <div class="pt-1">
                                    <a href="#section-dichvu-baogia" class="inline-block bg-sky-700 text-white text-[11px] font-bold px-3 py-1.5 rounded-md">
                                        Đặt Lịch Ngay
                                    </a>
                                </div>
                            </div>
                            <div class="w-[38%] h-full flex items-center justify-center">
                                <div class="w-full h-[160px] bg-white/90 rounded-xl p-1.5 border border-sky-200 flex items-center justify-center">
                                    <img src="https://lh3.googleusercontent.com/d/1mbajwSDtUUSFqnciTNIp0aQQi6zyONhE=w400"
                                         onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1mbajwSDtUUSFqnciTNIp0aQQi6zyONhE&sz=w400';"
                                         alt="Banner Mobile Vinh Thú Cưng 2" class="max-h-full max-w-full object-contain rounded-lg">
                                </div>
                            </div>
                        </div>

                    </div>

                    <!-- Nút điều hướng Slider -->
                    <button onclick="changeSlide(-1)" aria-label="Slide trước" class="absolute left-2 top-1/2 -translate-y-1/2 w-8 h-8 rounded-full bg-white/80 hover:bg-white text-slate-800 shadow flex items-center justify-center z-20">
                        <i class="fa-solid fa-chevron-left text-xs"></i>
                    </button>
                    <button onclick="changeSlide(1)" aria-label="Slide tiếp" class="absolute right-2 top-1/2 -translate-y-1/2 w-8 h-8 rounded-full bg-white/80 hover:bg-white text-slate-800 shadow flex items-center justify-center z-20">
                        <i class="fa-solid fa-chevron-right text-xs"></i>
                    </button>

                    <!-- Dấu chấm chuyển Slide -->
                    <div class="absolute bottom-2.5 left-1/2 -translate-x-1/2 flex items-center gap-2 z-20">
                        <button onclick="goToSlide(0)" class="slide-dot w-6 h-2 rounded-full bg-brand transition-all"></button>
                        <button onclick="goToSlide(1)" class="slide-dot w-2 h-2 rounded-full bg-slate-400/70 transition-all"></button>
                    </div>
                </div>
            </div>
        </section>

        <!-- SECTION 2: DANH MỤC SẢN PHẨM TRANG CHỦ (TỐI ƯU ĐẸP TRÊN MÁY TÍNH & ĐIỆN THOẠI, CHỮ NHỎ GỌN TRÊN 1 HÀNG) -->
        <section id="section-danhmuc-trangchu" class="py-3">
            <div class="container-1500">
                <div class="bg-white rounded-xl border border-slate-200 p-3.5 md:p-4 shadow-sm">
                    <div class="flex items-center justify-between mb-3 pb-2 border-b border-slate-100">
                        <h2 class="text-sm md:text-base font-extrabold text-slate-800 uppercase flex items-center gap-2">
                            <i class="fa-solid fa-layer-group text-brand"></i>
                            <span>Danh Mục Sản Phẩm</span>
                        </h2>
                        <span class="text-[11.5px] text-slate-500 hidden sm:inline">Chọn nhanh danh mục theo nhu cầu của thú cưng</span>
                    </div>

                    <!-- Lưới 10 danh mục: Trên máy tính chia 5 hoặc 10 cột đều đặn, chữ danh mục nhỏ gọn viết liền trên 1 hàng -->
                    <div class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-5 xl:grid-cols-10 gap-2.5">
                        <a href="#sec-hang-moi" class="group flex flex-col items-center justify-center p-2.5 rounded-xl bg-orange-50/60 hover:bg-brand hover:text-white border border-orange-100 transition text-center">
                            <div class="w-10 h-10 rounded-full bg-white text-brand flex items-center justify-center shadow-sm mb-1.5 group-hover:scale-105 transition">
                                <i class="fa-solid fa-bolt text-base"></i>
                            </div>
                            <span class="cat-single-line text-[11.5px] font-bold">Sản Phẩm Mới</span>
                        </a>

                        <a href="#sec-danh-cho-cho" onclick="filterSubCategory('sec-danh-cho-cho', 'thucancho')" class="group flex flex-col items-center justify-center p-2.5 rounded-xl bg-slate-50 hover:bg-brand hover:text-white border border-slate-200/80 transition text-center">
                            <div class="w-10 h-10 rounded-full bg-white text-brand flex items-center justify-center shadow-sm mb-1.5 group-hover:scale-105 transition">
                                <i class="fa-solid fa-dog text-base"></i>
                            </div>
                            <span class="cat-single-line text-[11.5px] font-bold">Thức Ăn Chó</span>
                        </a>

                        <a href="#sec-danh-cho-meo" onclick="filterSubCategory('sec-danh-cho-meo', 'thucanmeo')" class="group flex flex-col items-center justify-center p-2.5 rounded-xl bg-slate-50 hover:bg-brand hover:text-white border border-slate-200/80 transition text-center">
                            <div class="w-10 h-10 rounded-full bg-white text-amber-600 flex items-center justify-center shadow-sm mb-1.5 group-hover:scale-105 transition">
                                <i class="fa-solid fa-cat text-base"></i>
                            </div>
                            <span class="cat-single-line text-[11.5px] font-bold">Thức Ăn Mèo</span>
                        </a>

                        <a href="#sec-danh-cho-meo" onclick="filterSubCategory('sec-danh-cho-meo', 'catvesinh')" class="group flex flex-col items-center justify-center p-2.5 rounded-xl bg-slate-50 hover:bg-brand hover:text-white border border-slate-200/80 transition text-center">
                            <div class="w-10 h-10 rounded-full bg-white text-sky-600 flex items-center justify-center shadow-sm mb-1.5 group-hover:scale-105 transition">
                                <i class="fa-solid fa-box-open text-base"></i>
                            </div>
                            <span class="cat-single-line text-[11.5px] font-bold">Cát Vệ Sinh Mèo</span>
                        </a>

                        <a href="#sec-phukien-thuy" onclick="filterSubCategory('sec-phukien-thuy', 'dinhduong')" class="group flex flex-col items-center justify-center p-2.5 rounded-xl bg-slate-50 hover:bg-brand hover:text-white border border-slate-200/80 transition text-center">
                            <div class="w-10 h-10 rounded-full bg-white text-emerald-600 flex items-center justify-center shadow-sm mb-1.5 group-hover:scale-105 transition">
                                <i class="fa-solid fa-Notes-medical fa-capsules text-base"></i>
                            </div>
                            <span class="cat-single-line text-[11.5px] font-bold">Dinh Dưỡng</span>
                        </a>

                        <a href="#sec-danh-cho-cho" onclick="filterSubCategory('sec-danh-cho-cho', 'dochoicho')" class="group flex flex-col items-center justify-center p-2.5 rounded-xl bg-slate-50 hover:bg-brand hover:text-white border border-slate-200/80 transition text-center">
                            <div class="w-10 h-10 rounded-full bg-white text-purple-600 flex items-center justify-center shadow-sm mb-1.5 group-hover:scale-105 transition">
                                <i class="fa-solid fa-baseball text-base"></i>
                            </div>
                            <span class="cat-single-line text-[11.5px] font-bold">Đồ Chơi & Tập</span>
                        </a>

                        <a href="#sec-phukien-thuy" onclick="filterSubCategory('sec-phukien-thuy', 'daydat')" class="group flex flex-col items-center justify-center p-2.5 rounded-xl bg-slate-50 hover:bg-brand hover:text-white border border-slate-200/80 transition text-center">
                            <div class="w-10 h-10 rounded-full bg-white text-blue-600 flex items-center justify-center shadow-sm mb-1.5 group-hover:scale-105 transition">
                                <i class="fa-solid fa-link text-base"></i>
                            </div>
                            <span class="cat-single-line text-[11.5px] font-bold">Dây Dắt Vòng Cổ</span>
                        </a>

                        <a href="#sec-phukien-thuy" onclick="filterSubCategory('sec-phukien-thuy', 'quanao')" class="group flex flex-col items-center justify-center p-2.5 rounded-xl bg-slate-50 hover:bg-brand hover:text-white border border-slate-200/80 transition text-center">
                            <div class="w-10 h-10 rounded-full bg-white text-pink-600 flex items-center justify-center shadow-sm mb-1.5 group-hover:scale-105 transition">
                                <i class="fa-solid fa-shirt text-base"></i>
                            </div>
                            <span class="cat-single-line text-[11.5px] font-bold">Quần Áo & Chuồng</span>
                        </a>

                        <a href="#sec-phukien-thuy" onclick="filterSubCategory('sec-phukien-thuy', 'thuy')" class="group flex flex-col items-center justify-center p-2.5 rounded-xl bg-slate-50 hover:bg-brand hover:text-white border border-slate-200/80 transition text-center">
                            <div class="w-10 h-10 rounded-full bg-white text-red-600 flex items-center justify-center shadow-sm mb-1.5 group-hover:scale-105 transition">
                                <i class="fa-solid fa-kit-medical text-base"></i>
                            </div>
                            <span class="cat-single-line text-[11.5px] font-bold">Thuốc Thú Y</span>
                        </a>

                        <a href="#section-dichvu-baogia" class="group flex flex-col items-center justify-center p-2.5 rounded-xl bg-slate-50 hover:bg-brand hover:text-white border border-slate-200/80 transition text-center">
                            <div class="w-10 h-10 rounded-full bg-white text-teal-600 flex items-center justify-center shadow-sm mb-1.5 group-hover:scale-105 transition">
                                <i class="fa-solid fa-scissors text-base"></i>
                            </div>
                            <span class="cat-single-line text-[11.5px] font-bold">Dịch Vụ Spa</span>
                        </a>
                    </div>
                </div>
            </div>
        </section>

        <!-- SECTION 3: HÀNG MỚI VỀ & SẢN PHẨM THỰC TẾ TẠI VINH THÚ CƯNG (12 ẢNH THỰC TẾ GOOGLE DRIVE) -->
        <section id="sec-hang-moi" class="py-3">
            <div class="container-1500">
                <div class="bg-white rounded-xl border border-slate-200 p-3.5 md:p-5 shadow-sm">
                    <!-- Header Section chuẩn Flatsome -->
                    <div class="flex flex-wrap items-center justify-between gap-2 pb-3 mb-4 border-b-2 border-brand">
                        <div class="flex items-center gap-2">
                            <span class="w-8 h-8 rounded-lg bg-brand text-white flex items-center justify-center">
                                <i class="fa-solid fa-star text-sm"></i>
                            </span>
                            <h2 class="text-base md:text-lg font-extrabold text-slate-900 uppercase tracking-tight">
                                Hàng Mới Về - Sản Phẩm Thực Tế Tại Shop
                            </h2>
                        </div>
                        <div class="flex flex-wrap items-center gap-1.5">
                            <button onclick="filterFeatured('all')" class="feat-tab-btn cat-single-line text-xs font-bold px-3 py-1.5 rounded-lg bg-brand text-white">Tất Cả (12)</button>
                            <button onclick="filterFeatured('thucan')" class="feat-tab-btn cat-single-line text-xs font-semibold px-3 py-1.5 rounded-lg bg-slate-100 hover:bg-orange-50 text-slate-700">Thức Ăn Chó Mèo</button>
                            <button onclick="filterFeatured('dinhduong')" class="feat-tab-btn cat-single-line text-xs font-semibold px-3 py-1.5 rounded-lg bg-slate-100 hover:bg-orange-50 text-slate-700">Dinh Dưỡng & Thú Y</button>
                            <button onclick="filterFeatured('phukien')" class="feat-tab-btn cat-single-line text-xs font-semibold px-3 py-1.5 rounded-lg bg-slate-100 hover:bg-orange-50 text-slate-700">Đồ Dùng & Phụ Kiện</button>
                        </div>
                    </div>

                    <!-- Grid Sản Phẩm: 2 cột trên điện thoại (grid-cols-2), 6 cột trên máy tính (lg:grid-cols-6) -->
                    <div id="grid-featured-products" class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-4 lg:grid-cols-6 gap-2.5 md:gap-3.5">
                        <!-- Được render tự động bằng JS từ 12 ảnh thực tế Google Drive -->
                    </div>
                </div>
            </div>
        </section>

        <!-- SECTION 4: DANH MỤC DÀNH CHO CHÓ (GIỐNG MẪU PETSHOPHANOI) -->
        <section id="sec-danh-cho-cho" class="py-3">
            <div class="container-1500">
                <div class="bg-white rounded-xl border border-slate-200 p-3.5 md:p-5 shadow-sm">
                    <div class="flex flex-wrap items-center justify-between gap-2 pb-3 mb-4 border-b-2 border-brand">
                        <div class="flex items-center gap-2">
                            <span class="w-8 h-8 rounded-lg bg-brand text-white flex items-center justify-center">
                                <i class="fa-solid fa-dog text-sm"></i>
                            </span>
                            <h2 class="text-base md:text-lg font-extrabold text-slate-900 uppercase tracking-tight">
                                Dành Cho Chó
                            </h2>
                        </div>
                        <!-- Sub-categories viết liền trên 1 hàng chữ nhỏ gọn -->
                        <div class="flex flex-wrap items-center gap-1.5">
                            <button onclick="filterSubCategory('sec-danh-cho-cho', 'all')" class="subtab-cho cat-single-line text-xs font-bold px-2.5 py-1.5 rounded-lg bg-brand text-white">Xem tất cả</button>
                            <button onclick="filterSubCategory('sec-danh-cho-cho', 'thucancho')" class="subtab-cho cat-single-line text-xs font-semibold px-2.5 py-1.5 rounded-lg bg-slate-100 hover:bg-orange-50 text-slate-700">Thức Ăn Chó</button>
                            <button onclick="filterSubCategory('sec-danh-cho-cho', 'dinhduongcho')" class="subtab-cho cat-single-line text-xs font-semibold px-2.5 py-1.5 rounded-lg bg-slate-100 hover:bg-orange-50 text-slate-700">Bổ Sung Dinh Dưỡng</button>
                            <button onclick="filterSubCategory('sec-danh-cho-cho', 'dochoicho')" class="subtab-cho cat-single-line text-xs font-semibold px-2.5 py-1.5 rounded-lg bg-slate-100 hover:bg-orange-50 text-slate-700">Đồ Chơi, Huấn Luyện</button>
                            <button onclick="filterSubCategory('sec-danh-cho-cho', 'dodungcho')" class="subtab-cho cat-single-line text-xs font-semibold px-2.5 py-1.5 rounded-lg bg-slate-100 hover:bg-orange-50 text-slate-700">Đồ Dùng Cho Chó</button>
                        </div>
                    </div>

                    <div id="grid-dog-products" class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-4 lg:grid-cols-6 gap-2.5 md:gap-3.5">
                        <!-- Render bằng JS -->
                    </div>
                </div>
            </div>
        </section>

        <!-- SECTION 5: DANH MỤC DÀNH CHO MÈO (GIỐNG MẪU PETSHOPHANOI) -->
        <section id="sec-danh-cho-meo" class="py-3">
            <div class="container-1500">
                <div class="bg-white rounded-xl border border-slate-200 p-3.5 md:p-5 shadow-sm">
                    <div class="flex flex-wrap items-center justify-between gap-2 pb-3 mb-4 border-b-2 border-brand">
                        <div class="flex items-center gap-2">
                            <span class="w-8 h-8 rounded-lg bg-amber-600 text-white flex items-center justify-center">
                                <i class="fa-solid fa-cat text-sm"></i>
                            </span>
                            <h2 class="text-base md:text-lg font-extrabold text-slate-900 uppercase tracking-tight">
                                Dành Cho Mèo
                            </h2>
                        </div>
                        <div class="flex flex-wrap items-center gap-1.5">
                            <button onclick="filterSubCategory('sec-danh-cho-meo', 'all')" class="subtab-meo cat-single-line text-xs font-bold px-2.5 py-1.5 rounded-lg bg-brand text-white">Xem tất cả</button>
                            <button onclick="filterSubCategory('sec-danh-cho-meo', 'thucanmeo')" class="subtab-meo cat-single-line text-xs font-semibold px-2.5 py-1.5 rounded-lg bg-slate-100 hover:bg-orange-50 text-slate-700">Thức Ăn Mèo & Pate</button>
                            <button onclick="filterSubCategory('sec-danh-cho-meo', 'dochoimeo')" class="subtab-meo cat-single-line text-xs font-semibold px-2.5 py-1.5 rounded-lg bg-slate-100 hover:bg-orange-50 text-slate-700">Đồ Chơi Mèo & Cat Tree</button>
                            <button onclick="filterSubCategory('sec-danh-cho-meo', 'catvesinh')" class="subtab-meo cat-single-line text-xs font-semibold px-2.5 py-1.5 rounded-lg bg-slate-100 hover:bg-orange-50 text-slate-700">Cát & Nhà Vệ Sinh Mèo</button>
                            <button onclick="filterSubCategory('sec-danh-cho-meo', 'dodungmeo')" class="subtab-meo cat-single-line text-xs font-semibold px-2.5 py-1.5 rounded-lg bg-slate-100 hover:bg-orange-50 text-slate-700">Đồ Dùng Cho Mèo</button>
                        </div>
                    </div>

                    <div id="grid-cat-products" class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-4 lg:grid-cols-6 gap-2.5 md:gap-3.5">
                        <!-- Render bằng JS -->
                    </div>
                </div>
            </div>
        </section>

        <!-- SECTION 6: DÂY DẮT, PHỤ KIỆN, DINH DƯỠNG & THUỐC THÚ Y -->
        <section id="sec-phukien-thuy" class="py-3">
            <div class="container-1500">
                <div class="bg-white rounded-xl border border-slate-200 p-3.5 md:p-5 shadow-sm">
                    <div class="flex flex-wrap items-center justify-between gap-2 pb-3 mb-4 border-b-2 border-brand">
                        <div class="flex items-center gap-2">
                            <span class="w-8 h-8 rounded-lg bg-sky-600 text-white flex items-center justify-center">
                                <i class="fa-solid fa-kit-medical text-sm"></i>
                            </span>
                            <h2 class="text-base md:text-lg font-extrabold text-slate-900 uppercase tracking-tight">
                                Phụ Kiện, Dinh Dưỡng & Thuốc Thú Y
                            </h2>
                        </div>
                        <div class="flex flex-wrap items-center gap-1.5">
                            <button onclick="filterSubCategory('sec-phukien-thuy', 'all')" class="subtab-pk cat-single-line text-xs font-bold px-2.5 py-1.5 rounded-lg bg-brand text-white">Xem tất cả</button>
                            <button onclick="filterSubCategory('sec-phukien-thuy', 'daydat')" class="subtab-pk cat-single-line text-xs font-semibold px-2.5 py-1.5 rounded-lg bg-slate-100 hover:bg-orange-50 text-slate-700">Dây Dắt & Vòng Cổ</button>
                            <button onclick="filterSubCategory('sec-phukien-thuy', 'quanao')" class="subtab-pk cat-single-line text-xs font-semibold px-2.5 py-1.5 rounded-lg bg-slate-100 hover:bg-orange-50 text-slate-700">Quần Áo, Bát Ăn, Chuồng</button>
                            <button onclick="filterSubCategory('sec-phukien-thuy', 'suatam')" class="subtab-pk cat-single-line text-xs font-semibold px-2.5 py-1.5 rounded-lg bg-slate-100 hover:bg-orange-50 text-slate-700">Sữa Tắm & Chăm Sóc</button>
                            <button onclick="filterSubCategory('sec-phukien-thuy', 'dinhduong')" class="subtab-pk cat-single-line text-xs font-semibold px-2.5 py-1.5 rounded-lg bg-slate-100 hover:bg-orange-50 text-slate-700">Canxi & Vitamin</button>
                            <button onclick="filterSubCategory('sec-phukien-thuy', 'thuy')" class="subtab-pk cat-single-line text-xs font-semibold px-2.5 py-1.5 rounded-lg bg-slate-100 hover:bg-orange-50 text-slate-700">Thuốc Thú Y</button>
                        </div>
                    </div>

                    <div id="grid-pk-products" class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-4 lg:grid-cols-6 gap-2.5 md:gap-3.5">
                        <!-- Render bằng JS -->
                    </div>
                </div>
            </div>
        </section>

        <!-- SECTION 7: DỊCH VỤ THÚ CƯNG & FORM YÊU CẦU - BÁO GIÁ TRANG CHỦ -->
        <section id="section-dichvu-baogia" class="py-3">
            <div class="container-1500">
                <div class="grid grid-cols-1 lg:grid-cols-12 gap-4">
                    
                    <!-- Cột Trái (7/12): Dịch Vụ Spa Grooming, Cắt Tỉa & Khách Sạn Thú Cưng -->
                    <div class="lg:col-span-7 bg-white rounded-xl border border-slate-200 p-4 md:p-5 shadow-sm flex flex-col justify-between">
                        <div>
                            <div class="flex items-center gap-2 pb-3 mb-4 border-b-2 border-brand">
                                <span class="w-8 h-8 rounded-lg bg-brand text-white flex items-center justify-center">
                                    <i class="fa-solid fa-scissors text-sm"></i>
                                </span>
                                <h2 class="text-base md:text-lg font-extrabold text-slate-900 uppercase">
                                    Dịch Vụ Tắm Sấy, Cắt Tỉa Spa & Trông Giữ Hotel
                                </h2>
                            </div>
                            <p class="text-xs md:text-sm text-slate-600 mb-4 leading-relaxed">
                                Tại <strong>Vinh Thú Cưng – Love Pets (26 Trần Quý Cáp, P. Bàn Thạch, Tp. Đà Nẵng)</strong>, mọi bé cún và mèo đều được kiểm tra tình trạng da, lông và sức khỏe trước khi thực hiện dịch vụ với quy trình nhẹ nhàng, sạch sẽ và an toàn.
                            </p>

                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                                <div class="p-3.5 rounded-xl bg-orange-50/60 border border-orange-100">
                                    <div class="flex items-center justify-between mb-1.5">
                                        <span class="font-bold text-sm text-slate-900"><i class="fa-solid fa-shower text-brand mr-1.5"></i>Tắm Sấy Grooming</span>
                                        <span class="text-xs font-extrabold text-brand">Từ 80.000₫</span>
                                    </div>
                                    <p class="text-xs text-slate-600 leading-relaxed">Tắm sạch khử mùi chuyên sâu, vắt tuyến hôi, vệ sinh tai, cắt & mài móng, sấy bông chải mượt lông.</p>
                                </div>

                                <div class="p-3.5 rounded-xl bg-orange-50/60 border border-orange-100">
                                    <div class="flex items-center justify-between mb-1.5">
                                        <span class="font-bold text-sm text-slate-900"><i class="fa-solid fa-scissors text-brand mr-1.5"></i>Cắt Tỉa Lông Tạo Kiểu Spa</span>
                                        <span class="text-xs font-extrabold text-brand">Từ 150.000₫</span>
                                    </div>
                                    <p class="text-xs text-slate-600 leading-relaxed">Trọn gói tắm vệ sinh kết hợp gỡ rối, cắt tỉa tạo dáng thẩm mỹ theo giống Poodle, Phốc Sóc, Mèo Anh...</p>
                                </div>

                                <div class="p-3.5 rounded-xl bg-sky-50/60 border border-sky-100">
                                    <div class="flex items-center justify-between mb-1.5">
                                        <span class="font-bold text-sm text-slate-900"><i class="fa-solid fa-hotel text-sky-600 mr-1.5"></i>Khách Sạn Trông Giữ Hotel</span>
                                        <span class="text-xs font-extrabold text-sky-700">Từ 80.000₫/ngày</span>
                                    </div>
                                    <p class="text-xs text-slate-600 leading-relaxed">Phòng lưu trú thoáng mát, khử khuẩn hàng ngày, thực đơn linh hoạt theo độ tuổi và thói quen của từng bé.</p>
                                </div>

                                <div class="p-3.5 rounded-xl bg-emerald-50/60 border border-emerald-100">
                                    <div class="flex items-center justify-between mb-1.5">
                                        <span class="font-bold text-sm text-slate-900"><i class="fa-solid fa-user-doctor text-emerald-600 mr-1.5"></i>Tư Vấn Thú Y & Tẩy Giun</span>
                                        <span class="text-xs font-extrabold text-emerald-700">Hỗ trợ 24/7</span>
                                    </div>
                                    <p class="text-xs text-slate-600 leading-relaxed">Tư vấn phác đồ dinh dưỡng, tẩy giun sán, trị ve rận, nấm ghẻ, tiêu búi lông và bệnh đường ruột chó mèo.</p>
                                </div>
                            </div>
                        </div>

                        <div class="mt-4 pt-3 border-t border-slate-100 flex flex-wrap items-center justify-between gap-2 text-xs text-slate-700">
                            <span><i class="fa-solid fa-location-dot text-brand mr-1"></i><strong>Địa chỉ:</strong> 26 Trần Quý Cáp, Phường Bàn Thạch, Tp. Đà Nẵng</span>
                            <span><i class="fa-solid fa-phone text-brand mr-1"></i><strong>Hotline:</strong> 0984.244.001 | <strong>CSKH:</strong> 0399.830.237</span>
                        </div>
                    </div>

                    <!-- Cột Phải (5/12): FORM YÊU CẦU VÀ BÁO GIÁ TRANG CHỦ -->
                    <div id="section-baogia" class="lg:col-span-5 bg-white rounded-xl border-2 border-brand p-4 md:p-5 shadow-sm">
                        <div class="pb-2.5 mb-3 border-b border-slate-100">
                            <span class="inline-block bg-orange-100 text-brand text-[11px] font-bold px-2.5 py-0.5 rounded mb-1">PHẢN HỒI NHANH TRONG 5 PHÚT</span>
                            <h2 class="text-base md:text-lg font-extrabold text-slate-900 uppercase">
                                Form Yêu Cầu Tư Vấn & Báo Giá
                            </h2>
                            <p class="text-xs text-slate-500 mt-0.5">Nhận báo giá sỉ/lẻ thức ăn phụ kiện hoặc đặt lịch Spa - Hotel thú cưng</p>
                        </div>

                        <form id="quote-form" onsubmit="submitQuoteForm(event)" class="space-y-3 text-xs">
                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-2.5">
                                <div>
                                    <label class="block font-semibold text-slate-700 mb-1">Họ và tên <span class="text-red-500">*</span></label>
                                    <input type="text" id="quote-name" required placeholder="Nhập tên của bạn..." class="w-full px-3 py-2 rounded-lg border border-slate-300 focus:border-brand focus:outline-none">
                                </div>
                                <div>
                                    <label class="block font-semibold text-slate-700 mb-1">Số điện thoại / Zalo <span class="text-red-500">*</span></label>
                                    <input type="tel" id="quote-phone" required placeholder="VD: 0984244001" class="w-full px-3 py-2 rounded-lg border border-slate-300 focus:border-brand focus:outline-none">
                                </div>
                            </div>

                            <div>
                                <label class="block font-semibold text-slate-700 mb-1">Danh mục cần yêu cầu / báo giá <span class="text-red-500">*</span></label>
                                <select id="quote-category" class="w-full px-3 py-2 rounded-lg border border-slate-300 focus:border-brand focus:outline-none bg-white">
                                    <option value="Báo giá thức ăn & pate chó mèo">Báo giá thức ăn hạt & pate chó mèo</option>
                                    <option value="Báo giá phụ kiện, cát vệ sinh, lồng chuồng">Báo giá phụ kiện, cát vệ sinh, lồng chuồng</option>
                                    <option value="Tư vấn dinh dưỡng & thuốc thú y">Tư vấn dinh dưỡng & thuốc thú y (ve, nấm, đường ruột)</option>
                                    <option value="Đặt lịch Tắm sấy Grooming / Cắt tỉa Spa">Đặt lịch Tắm sấy Grooming / Cắt tỉa Spa</option>
                                    <option value="Báo giá Trông giữ Khách sạn thú cưng (Hotel)">Báo giá Trông giữ Khách sạn thú cưng (Hotel)</option>
                                    <option value="Yêu cầu báo giá sỉ đại lý">Yêu cầu báo giá sỉ số lượng lớn</option>
                                </select>
                            </div>

                            <div>
                                <label class="block font-semibold text-slate-700 mb-1">Nội dung chi tiết (Tên sản phẩm / Giống & cân nặng bé)</label>
                                <textarea id="quote-message" rows="3" placeholder="Nhập sản phẩm cần báo giá hoặc giống thú cưng, cân nặng, thời gian đặt lịch..." class="w-full px-3 py-2 rounded-lg border border-slate-300 focus:border-brand focus:outline-none"></textarea>
                            </div>

                            <button type="submit" class="w-full bg-brand hover:bg-brand-dark text-white font-bold py-2.5 px-4 rounded-lg shadow transition flex items-center justify-center gap-2 text-xs md:text-sm">
                                <i class="fa-solid fa-paper-plane"></i>
                                <span>GỬI YÊU CẦU & NHẬN BÁO GIÁ NGAY</span>
                            </button>
                        </form>
                    </div>

                </div>
            </div>
        </section>

        <!-- SECTION 8: DANH MỤC CÁC BÀI VIẾT TRANG CHỦ (CHUYÊN MỤC KIẾN THỨC THÚ CƯNG) -->
        <section id="section-baiviet" class="py-3">
            <div class="container-1500">
                <div class="bg-white rounded-xl border border-slate-200 p-3.5 md:p-5 shadow-sm">
                    <div class="flex flex-wrap items-center justify-between gap-2 pb-3 mb-4 border-b-2 border-brand">
                        <div class="flex items-center gap-2">
                            <span class="w-8 h-8 rounded-lg bg-brand text-white flex items-center justify-center">
                                <i class="fa-solid fa-newspaper text-sm"></i>
                            </span>
                            <h2 class="text-base md:text-lg font-extrabold text-slate-900 uppercase tracking-tight">
                                Danh Mục Bài Viết & Kinh Nghiệm Chăm Sóc Thú Cưng
                            </h2>
                        </div>
                        <div class="flex flex-wrap items-center gap-1.5">
                            <button onclick="filterArticles('all')" class="art-tab-btn cat-single-line text-xs font-bold px-2.5 py-1.5 rounded-lg bg-brand text-white">Tất Cả Bài Viết</button>
                            <button onclick="filterArticles('dinhduong')" class="art-tab-btn cat-single-line text-xs font-semibold px-2.5 py-1.5 rounded-lg bg-slate-100 hover:bg-orange-50 text-slate-700">Dinh Dưỡng Chó Mèo</button>
                            <button onclick="filterArticles('thuy')" class="art-tab-btn cat-single-line text-xs font-semibold px-2.5 py-1.5 rounded-lg bg-slate-100 hover:bg-orange-50 text-slate-700">Kiến Thức Thú Y</button>
                            <button onclick="filterArticles('spa')" class="art-tab-btn cat-single-line text-xs font-semibold px-2.5 py-1.5 rounded-lg bg-slate-100 hover:bg-orange-50 text-slate-700">Kinh Nghiệm Spa & Grooming</button>
                        </div>
                    </div>

                    <div id="grid-articles" class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-3.5">
                        <!-- Render bài viết từ nội dung thực tế Vinh Thú Cưng bằng JS -->
                    </div>
                </div>
            </div>
        </section>

        <!-- SECTION 9: ĐƯA FANPAGE VÀ ẢNH GOOGLE MAP RA NGOÀI TRANG CHỦ -->
        <section id="section-bando-fanpage" class="py-3 pb-6">
            <div class="container-1500">
                <div class="bg-white rounded-xl border border-slate-200 p-3.5 md:p-5 shadow-sm">
                    <div class="flex items-center justify-between pb-3 mb-4 border-b-2 border-brand">
                        <div class="flex items-center gap-2">
                            <span class="w-8 h-8 rounded-lg bg-brand text-white flex items-center justify-center">
                                <i class="fa-solid fa-map-location-dot text-sm"></i>
                            </span>
                            <h2 class="text-base md:text-lg font-extrabold text-slate-900 uppercase tracking-tight">
                                Kết Nối Fanpage & Bản Đồ Google Map Vinh Thú Cưng
                            </h2>
                        </div>
                    </div>

                    <div class="grid grid-cols-1 lg:grid-cols-12 gap-5">
                        
                        <!-- Cột 1 (5/12): Fanpage Vinh Thú Cưng ngoài trang chủ -->
                        <div class="lg:col-span-5 flex flex-col justify-between rounded-xl border border-slate-200 bg-slate-50 p-4">
                            <div>
                                <div class="flex items-center justify-between mb-3">
                                    <span class="text-xs font-bold uppercase text-blue-700 flex items-center gap-1.5">
                                        <i class="fa-brands fa-facebook text-base"></i>
                                        Fanpage Chính Thức
                                    </span>
                                    <a href="https://www.facebook.com/vinhthucung" target="_blank" rel="noopener" class="text-xs font-semibold text-brand hover:underline">
                                        Mở Facebook <i class="fa-solid fa-arrow-up-right-from-square text-[10px]"></i>
                                    </a>
                                </div>

                                <!-- Thẻ nhận diện Fanpage Vinh Thú Cưng - Love Pets trực quan -->
                                <div class="bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm mb-3">
                                    <div class="h-24 bg-gradient-to-r from-brand via-orange-500 to-amber-500 px-4 flex items-center justify-between text-white">
                                        <div>
                                            <div class="text-xs font-semibold opacity-90">Chăm Sóc & Làm Đẹp Thú Cưng</div>
                                            <div class="text-base font-extrabold">Vinh Thú Cưng – Love Pets</div>
                                            <div class="text-[11px] opacity-90">facebook.com/vinhthucung</div>
                                        </div>
                                        <img src="https://lh3.googleusercontent.com/d/10sBXJ8sDRq-BhJc4F8EGqjYeuB3gKxmB=w200"
                                             onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=10sBXJ8sDRq-BhJc4F8EGqjYeuB3gKxmB&sz=w200';"
                                             alt="Avatar Fanpage Vinh Thú Cưng" class="w-14 h-14 rounded-full bg-white p-0.5 border-2 border-white object-contain shadow">
                                    </div>
                                    <div class="p-3.5 text-xs space-y-2">
                                        <p class="text-slate-700 leading-relaxed">
                                            <strong>Vinh Thú Cưng (Love Pets)</strong> – Chuyên thức ăn, phụ kiện, dinh dưỡng, thuốc thú y, dịch vụ tỉa lông Spa Grooming và trông giữ thú cưng tại 26 Trần Quý Cáp, Phường Bàn Thạch, Tp. Đà Nẵng.
                                        </p>
                                        <div class="flex flex-wrap gap-2 pt-1">
                                            <a href="https://www.facebook.com/vinhthucung" target="_blank" rel="noopener" class="flex-1 bg-[#1877F2] hover:bg-blue-700 text-white font-bold py-2 px-3 rounded-lg text-center transition">
                                                <i class="fa-brands fa-facebook-f mr-1"></i> Theo Dõi Fanpage
                                            </a>
                                            <a href="https://www.facebook.com/vinhthucung" target="_blank" rel="noopener" class="flex-1 bg-slate-100 hover:bg-slate-200 text-slate-800 font-bold py-2 px-3 rounded-lg text-center transition">
                                                <i class="fa-brands fa-facebook-messenger text-blue-600 mr-1"></i> Nhắn Tin Ngay
                                            </a>
                                        </div>
                                    </div>
                                </div>

                                <!-- Nhúng Facebook Page Plugin tiêu chuẩn -->
                                <div class="w-full overflow-hidden rounded-lg border border-slate-200 bg-white flex justify-center py-1">
                                    <iframe src="https://www.facebook.com/plugins/page.php?href=https%3A%2F%2Fwww.facebook.com%2Fvinhthucung&tabs=timeline&width=340&height=220&small_header=true&adapt_container_width=true&hide_cover=false&show_facepile=true"
                                            width="340" height="220" style="border:none;overflow:hidden;max-width:100%;" scrolling="no" frameborder="0" allowfullscreen="true" allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share" title="Fanpage Vinh Thú Cưng"></iframe>
                                </div>
                            </div>
                        </div>

                        <!-- Cột 2 (7/12): Đưa Ảnh Google Map & Bản Đồ Tương Tác Ra Ngoài Trang Chủ -->
                        <div class="lg:col-span-7 flex flex-col justify-between rounded-xl border border-slate-200 bg-slate-50 p-4">
                            <div>
                                <div class="flex flex-wrap items-center justify-between gap-2 mb-3">
                                    <div>
                                        <span class="text-xs font-bold uppercase text-emerald-700 flex items-center gap-1.5">
                                            <i class="fa-solid fa-location-dot text-red-600 text-sm"></i>
                                            Vị Trí Cửa Hàng Trên Google Maps
                                        </span>
                                        <p class="text-xs text-slate-600 mt-0.5">
                                            <strong>Địa chỉ:</strong> 26 Trần Quý Cáp, Phường Bàn Thạch, Tp. Đà Nẵng
                                        </p>
                                    </div>
                                    <a href="https://maps.app.goo.gl/yDHzMAcg95qto3QdA" target="_blank" rel="noopener" class="bg-emerald-600 hover:bg-emerald-700 text-white text-xs font-bold px-3.5 py-2 rounded-lg shadow-sm transition flex items-center gap-1.5">
                                        <i class="fa-solid fa-diamond-turn-right"></i>
                                        <span>Mở Google Maps Chỉ Đường</span>
                                    </a>
                                </div>

                                <!-- Khung Bản Đồ Google Maps Trực Tiếp Ngoài Trang Chủ -->
                                <div class="relative w-full h-[290px] md:h-[320px] rounded-xl overflow-hidden border border-slate-300 shadow-sm bg-slate-200">
                                    <iframe
                                        src="https://maps.google.com/maps?q=Vinh%20Th%C3%BA%20C%C6%B0ng%2026%20Tr%E1%BA%A7n%20Qu%C3%BD%20C%C3%A1p&t=&z=16&ie=UTF8&iwloc=&output=embed"
                                        class="w-full h-full border-0"
                                        allowfullscreen=""
                                        loading="lazy"
                                        referrerpolicy="no-referrer-when-downgrade"
                                        title="Bản đồ Vinh Thú Cưng 26 Trần Quý Cáp">
                                    </iframe>

                                    <!-- Thẻ nổi thông tin địa chỉ ghim trên ảnh bản đồ -->
                                    <div class="absolute bottom-3 left-3 right-3 sm:right-auto bg-white/95 backdrop-blur-sm p-3 rounded-xl shadow-md border border-slate-200 max-w-sm text-xs">
                                        <div class="font-extrabold text-slate-900 flex items-center gap-1.5">
                                            <i class="fa-solid fa-store text-brand"></i>
                                            <span>Vinh Thú Cưng - vinhthucung.com</span>
                                        </div>
                                        <div class="text-slate-600 mt-0.5">26 Trần Quý Cáp, Phường Bàn Thạch, Tp. Đà Nẵng</div>
                                        <div class="flex items-center gap-3 mt-1.5 pt-1.5 border-t border-slate-100 font-semibold text-brand">
                                            <a href="tel:0984244001"><i class="fa-solid fa-phone mr-1"></i>0984.244.001</a>
                                            <a href="https://maps.app.goo.gl/yDHzMAcg95qto3QdA" target="_blank" rel="noopener" class="text-sky-700 hover:underline"><i class="fa-solid fa-map-pin mr-1"></i>Xem trên App Maps</a>
                                        </div>
                                    </div>
                                </div>
                            </div>

                            <div class="mt-3 pt-2.5 border-t border-slate-200 flex flex-wrap items-center justify-between gap-2 text-xs text-slate-600">
                                <span><i class="fa-solid fa-clock text-brand mr-1"></i>Giờ mở cửa: 07:30 – 21:00 (Tất cả các ngày trong tuần)</span>
                                <a href="https://maps.app.goo.gl/yDHzMAcg95qto3QdA" target="_blank" rel="noopener" class="font-bold text-brand hover:underline">
                                    Link Map: https://maps.app.goo.gl/yDHzMAcg95qto3QdA
                                </a>
                            </div>
                        </div>

                    </div>
                </div>
            </div>
        </section>

    </main>

    <!-- ==================== FOOTER CHUẨN FLATSOME ==================== -->
    <footer id="footer" class="bg-brand-navy text-slate-300 pt-10 pb-20 md:pb-10 border-t-4 border-brand text-xs">
        <div class="container-1500">
            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-6 pb-8 border-b border-slate-700">
                
                <!-- Cột 1: Thông tin liên hệ -->
                <div class="space-y-2.5">
                    <div class="flex items-center gap-2.5">
                        <img src="https://lh3.googleusercontent.com/d/10sBXJ8sDRq-BhJc4F8EGqjYeuB3gKxmB=w200"
                             onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=10sBXJ8sDRq-BhJc4F8EGqjYeuB3gKxmB&sz=w200';"
                             alt="Logo Vinh Thú Cưng" class="w-10 h-10 rounded-full bg-white p-0.5 object-contain">
                        <div>
                            <div class="text-base font-extrabold text-white">VINH THÚ CƯNG</div>
                            <div class="text-[11px] text-amber-400">vinhthucung.com - Love Pets</div>
                        </div>
                    </div>
                    <p class="text-slate-400 leading-relaxed">
                        Chuyên sỉ & lẻ thức ăn, phụ kiện, dinh dưỡng, thuốc thú y, dịch vụ tắm sấy Grooming, cắt tỉa lông Spa và khách sạn thú cưng uy tín.
                    </p>
                    <ul class="space-y-1.5 text-slate-200">
                        <li><i class="fa-solid fa-location-dot text-amber-400 w-5"></i><strong>Địa chỉ:</strong> 26 Trần Quý Cáp, Phường Bàn Thạch, Tp. Đà Nẵng</li>
                        <li><i class="fa-solid fa-phone text-amber-400 w-5"></i><strong>SĐT / Hotline:</strong> <a href="tel:0984244001" class="hover:text-amber-300">0984.244.001</a></li>
                        <li><i class="fa-solid fa-headset text-amber-400 w-5"></i><strong>CSKH:</strong> <a href="tel:0399830237" class="hover:text-amber-300">0399.830.237</a></li>
                        <li><i class="fa-solid fa-globe text-amber-400 w-5"></i><strong>Website:</strong> vinhthucung.com</li>
                    </ul>
                </div>

                <!-- Cột 2: Danh mục sản phẩm -->
                <div>
                    <h3 class="text-sm font-bold text-white uppercase mb-3 border-l-4 border-brand pl-2">Danh Mục Sản Phẩm</h3>
                    <ul class="space-y-2">
                        <li><a href="#sec-danh-cho-cho" class="hover:text-amber-300 transition"><i class="fa-solid fa-angle-right mr-1.5 text-brand"></i>Dành cho Chó (Hạt, Pate, Đồ chơi, Đồ dùng)</a></li>
                        <li><a href="#sec-danh-cho-meo" class="hover:text-amber-300 transition"><i class="fa-solid fa-angle-right mr-1.5 text-brand"></i>Dành cho Mèo (Thức ăn, Cát vệ sinh, Cat tree)</a></li>
                        <li><a href="#sec-phukien-thuy" class="hover:text-amber-300 transition"><i class="fa-solid fa-angle-right mr-1.5 text-brand"></i>Dây dắt, Vòng cổ, Quần áo, Balo vận chuyển</a></li>
                        <li><a href="#sec-phukien-thuy" class="hover:text-amber-300 transition"><i class="fa-solid fa-angle-right mr-1.5 text-brand"></i>Bổ sung Dinh dưỡng (Canxi, Vitamin, Gel)</a></li>
                        <li><a href="#sec-phukien-thuy" class="hover:text-amber-300 transition"><i class="fa-solid fa-angle-right mr-1.5 text-brand"></i>Thuốc Thú Y (Trị ve bọ, nấm ghẻ, đường ruột)</a></li>
                        <li><a href="#section-dichvu-baogia" class="hover:text-amber-300 transition"><i class="fa-solid fa-angle-right mr-1.5 text-brand"></i>Dịch vụ Tắm sấy Grooming, Cắt tỉa Spa, Hotel</a></li>
                    </ul>
                </div>

                <!-- Cột 3: Hỗ trợ khách hàng -->
                <div>
                    <h3 class="text-sm font-bold text-white uppercase mb-3 border-l-4 border-brand pl-2">Chính Sách & Hỗ Trợ</h3>
                    <ul class="space-y-2">
                        <li><a href="#section-baogia" class="hover:text-amber-300 transition"><i class="fa-solid fa-angle-right mr-1.5 text-brand"></i>Hướng dẫn đặt hàng & Nhận báo giá</a></li>
                        <li><a href="#section-dichvu-baogia" class="hover:text-amber-300 transition"><i class="fa-solid fa-angle-right mr-1.5 text-brand"></i>Quy trình tắm sấy & cắt tỉa lông thú cưng</a></li>
                        <li><a href="#section-dichvu-baogia" class="hover:text-amber-300 transition"><i class="fa-solid fa-angle-right mr-1.5 text-brand"></i>Quy định gửi thú cưng Hotel lưu trú</a></li>
                        <li><a href="#section-baiviet" class="hover:text-amber-300 transition"><i class="fa-solid fa-angle-right mr-1.5 text-brand"></i>Cẩm nang sức khỏe & dinh dưỡng thú y</a></li>
                        <li><a href="https://maps.app.goo.gl/yDHzMAcg95qto3QdA" target="_blank" rel="noopener" class="hover:text-amber-300 transition"><i class="fa-solid fa-angle-right mr-1.5 text-brand"></i>Chỉ đường Google Maps đến Shop</a></li>
                    </ul>
                </div>

                <!-- Cột 4: Kết nối mạng xã hội -->
                <div>
                    <h3 class="text-sm font-bold text-white uppercase mb-3 border-l-4 border-brand pl-2">Kết Nối Với Vinh Thú Cưng</h3>
                    <p class="text-slate-400 mb-3 leading-relaxed">
                        Theo dõi Fanpage chính thức để cập nhật sản phẩm mới và chương trình ưu đãi làm đẹp thú cưng hàng tuần.
                    </p>
                    <div class="flex flex-col gap-2">
                        <a href="https://www.facebook.com/vinhthucung" target="_blank" rel="noopener" class="flex items-center gap-2.5 bg-[#1877F2] hover:bg-blue-700 text-white font-bold px-3.5 py-2 rounded-lg transition">
                            <i class="fa-brands fa-facebook text-base"></i>
                            <span>facebook.com/vinhthucung</span>
                        </a>
                        <a href="https://zalo.me/0984244001" target="_blank" rel="noopener" class="flex items-center gap-2.5 bg-sky-600 hover:bg-sky-700 text-white font-bold px-3.5 py-2 rounded-lg transition">
                            <i class="fa-solid fa-comment-dots text-base"></i>
                            <span>Zalo Tư Vấn: 0984.244.001</span>
                        </a>
                        <a href="https://maps.app.goo.gl/yDHzMAcg95qto3QdA" target="_blank" rel="noopener" class="flex items-center gap-2.5 bg-emerald-600 hover:bg-emerald-700 text-white font-bold px-3.5 py-2 rounded-lg transition">
                            <i class="fa-solid fa-location-dot text-base"></i>
                            <span>26 Trần Quý Cáp, P. Bàn Thạch, Đà Nẵng</span>
                        </a>
                    </div>
                </div>

            </div>

            <div class="pt-5 flex flex-wrap items-center justify-between gap-2 text-slate-400">
                <div>© Bản quyền thuộc về <strong class="text-white">vinhthucung.com</strong> - Vinh Thú Cưng (26 Trần Quý Cáp, Phường Bàn Thạch, Tp. Đà Nẵng).</div>
                <div>Giao diện chuẩn UX Builder Flatsome</div>
            </div>
        </div>
    </footer>

    <!-- ==================== CÁC NÚT LIÊN HỆ NỔI BẬT (ZALO, FACEBOOK, HOTLINE) TƯƠNG THÍCH MÁY TÍNH & ĐIỆN THOẠI ==================== -->
    <div class="fixed bottom-4 right-3 z-50 flex flex-col items-end gap-2.5">
        <!-- Nút Facebook Fanpage -->
        <a href="https://www.facebook.com/vinhthucung" target="_blank" rel="noopener"
           class="flex items-center gap-2 bg-[#1877F2] hover:bg-blue-700 text-white pl-3 pr-3.5 py-2 rounded-full shadow-lg transition transform hover:scale-105">
            <span class="w-7 h-7 rounded-full bg-white text-[#1877F2] flex items-center justify-center font-bold">
                <i class="fa-brands fa-facebook-f text-sm"></i>
            </span>
            <span class="text-xs font-bold whitespace-nowrap">Facebook</span>
        </a>

        <!-- Nút Zalo nổi bật -->
        <a href="https://zalo.me/0984244001" target="_blank" rel="noopener"
           class="flex items-center gap-2 bg-[#0068ff] hover:bg-blue-600 text-white pl-3 pr-3.5 py-2 rounded-full shadow-lg transition transform hover:scale-105">
            <span class="w-7 h-7 rounded-full bg-white text-[#0068ff] flex items-center justify-center font-extrabold text-[10px]">
                Zalo
            </span>
            <span class="text-xs font-bold whitespace-nowrap">Zalo: 0984.244.001</span>
        </a>

        <!-- Nút CSKH -->
        <a href="tel:0399830237"
           class="flex items-center gap-2 bg-emerald-600 hover:bg-emerald-700 text-white pl-3 pr-3.5 py-2 rounded-full shadow-lg transition transform hover:scale-105">
            <span class="w-7 h-7 rounded-full bg-white text-emerald-600 flex items-center justify-center">
                <i class="fa-solid fa-headset text-xs"></i>
            </span>
            <span class="text-xs font-bold whitespace-nowrap">CSKH: 0399.830.237</span>
        </a>

        <!-- Nút Hotline chính -->
        <a href="tel:0984244001"
           class="contact-pulse flex items-center gap-2 bg-brand hover:bg-brand-dark text-white pl-3 pr-4 py-2.5 rounded-full shadow-xl transition">
            <span class="w-7 h-7 rounded-full bg-white text-brand flex items-center justify-center">
                <i class="fa-solid fa-phone-volume text-xs"></i>
            </span>
            <span class="text-xs font-extrabold whitespace-nowrap">0984.244.001</span>
        </a>
    </div>

    <!-- ==================== MODAL GIỎ HÀNG & THÔNG BÁO (KHÔNG DÙNG ALERT) ==================== -->
    <div id="cart-modal" class="fixed inset-0 bg-black/50 z-50 hidden items-center justify-center p-3">
        <div class="bg-white rounded-2xl max-w-lg w-full p-4 md:p-5 shadow-2xl border border-slate-200 max-h-[90vh] flex flex-col">
            <div class="flex items-center justify-between pb-3 border-b border-slate-100">
                <h3 class="text-base font-extrabold text-slate-900 flex items-center gap-2">
                    <i class="fa-solid fa-cart-shopping text-brand"></i>
                    <span>Giỏ Hàng Của Bạn</span>
                </h3>
                <button onclick="closeCartModal()" class="text-slate-400 hover:text-slate-700 p-1">
                    <i class="fa-solid fa-xmark text-lg"></i>
                </button>
            </div>
            <div id="cart-items-container" class="py-3 overflow-y-auto flex-1 space-y-2.5 text-xs">
                <!-- Danh sách sản phẩm trong giỏ -->
            </div>
            <div class="pt-3 border-t border-slate-100 space-y-3 text-xs">
                <div class="flex items-center justify-between font-bold text-sm">
                    <span>Tổng cộng tạm tính:</span>
                    <span id="cart-total-price" class="text-brand text-base">0₫</span>
                </div>
                <div class="grid grid-cols-2 gap-2">
                    <button onclick="closeCartModal()" class="py-2.5 px-3 rounded-lg border border-slate-300 font-semibold text-slate-700 hover:bg-slate-50">
                        Tiếp tục xem hàng
                    </button>
                    <button onclick="checkoutFromCart()" class="py-2.5 px-3 rounded-lg bg-brand hover:bg-brand-dark text-white font-bold">
                        Gửi đơn đặt hàng
                    </button>
                </div>
            </div>
        </div>
    </div>

    <!-- Modal Đọc Bài Viết Chi Tiết -->
    <div id="article-modal" class="fixed inset-0 bg-black/50 z-50 hidden items-center justify-center p-3">
        <div class="bg-white rounded-2xl max-w-2xl w-full p-4 md:p-6 shadow-2xl border border-slate-200 max-h-[90vh] flex flex-col">
            <div class="flex items-center justify-between pb-3 border-b border-slate-100">
                <span id="modal-article-cat" class="text-xs font-bold text-brand uppercase">Chuyên mục bài viết</span>
                <button onclick="closeArticleModal()" class="text-slate-400 hover:text-slate-700 p-1">
                    <i class="fa-solid fa-xmark text-lg"></i>
                </button>
            </div>
            <div class="py-3 overflow-y-auto flex-1 space-y-3 text-xs md:text-sm leading-relaxed text-slate-700">
                <h3 id="modal-article-title" class="text-base md:text-lg font-extrabold text-slate-900"></h3>
                <div id="modal-article-body" class="space-y-2.5"></div>
            </div>
            <div class="pt-3 border-t border-slate-100 flex items-center justify-between text-xs">
                <span class="text-slate-500">Tư vấn bởi: <strong>Vinh Thú Cưng - 0984.244.001</strong></span>
                <button onclick="closeArticleModal()" class="bg-brand text-white font-bold px-4 py-2 rounded-lg">Đóng</button>
            </div>
        </div>
    </div>

    <!-- Hộp thông báo Toast (Thay thế hoàn toàn alert) -->
    <div id="toast-box" class="fixed top-4 right-4 z-50 hidden bg-slate-900 text-white text-xs font-semibold px-4 py-3 rounded-xl shadow-xl border border-slate-700 items-center gap-2.5 max-w-sm">
        <i class="fa-solid fa-circle-check text-emerald-400 text-base"></i>
        <span id="toast-message">Đã thêm sản phẩm vào giỏ hàng!</span>
    </div>

    <!-- ==================== JAVASCRIPT XỬ LÝ DỮ LIỆU & TƯƠNG TÁC ==================== -->
    <script>
        // 12 Ảnh sản phẩm thực tế từ Google Drive khách hàng cung cấp
        const driveProductImages = [
            "1Dhygrqmccuyq2UFGHIbUfWqbhxSx5Jux",
            "1Fn8ln_cFgfD-w7rO8MfBBUXXOJdp--Ie",
            "1pAVitSGZpVZIaCSpu0QBcveQTxka7fzh",
            "1gFJo3LF2Sdb_yXdnzJFmsamxXdvuRclr",
            "1mbajwSDtUUSFqnciTNIp0aQQi6zyONhE",
            "1BCxG9MVjrlU7Ivbaye3l55ktJcCWsgOP",
            "1sdl7mYe2wOMTeYTEDCM61rS0b_UfHxWz",
            "1Wp4-K3ccXMaBEye2tPOJKWcgBEgeOOjF",
            "1j8rYGG7W7Wxap3UWOLsCF3iUxFp5hV_F",
            "1CnR3A0XugKLuYx_nQt1b9lqXAdFyQWWQ",
            "1nb-zrDF-X8GvgA5Kumscq_Eg0jwUl4Wu",
            "1uX7rflfBzueBET3tZErjFEz83Pcd2qhg"
        ];

        // Danh sách 12 sản phẩm thực tế tại Vinh Thú Cưng (lấy đúng 12 file ảnh Drive thực tế & phân loại đúng danh mục Petshop)
        const featuredRealProducts = [
            {
                id: "vtc-01",
                name: "Thức ăn hạt cho mèo tiết niệu & tiêu búi lông PETQ C90U Túi 1kg",
                category: "thucan",
                subCat: "thucanmeo",
                price: 190000,
                oldPrice: 230000,
                discount: 17,
                driveId: driveProductImages[0]
            },
            {
                id: "vtc-02",
                name: "Hạt cho chó trưởng thành và chó con vị thịt bò giàu đạm 1kg",
                category: "thucan",
                subCat: "thucancho",
                price: 110000,
                oldPrice: 145000,
                discount: 24,
                driveId: driveProductImages[1]
            },
            {
                id: "vtc-03",
                name: "Pate lon dinh dưỡng cho chó mèo bổ sung Omega 3 mượt lông",
                category: "thucan",
                subCat: "thucanmeo",
                price: 35000,
                oldPrice: 45000,
                discount: 22,
                driveId: driveProductImages[2]
            },
            {
                id: "vtc-04",
                name: "Gel dinh dưỡng & tiêu búi lông cho chó mèo Nuvita / Nutri Plus 120g",
                category: "dinhduong",
                subCat: "dinhduong",
                price: 85000,
                oldPrice: 105000,
                discount: 19,
                driveId: driveProductImages[3]
            },
            {
                id: "vtc-05",
                name: "Sữa bột dinh dưỡng Dr.Kyan Precaten & Predogen Gold cho chó mèo con",
                category: "dinhduong",
                subCat: "dinhduongcho",
                price: 185000,
                oldPrice: 215000,
                discount: 14,
                driveId: driveProductImages[4]
            },
            {
                id: "vtc-06",
                name: "Cát đậu phụ / Cát đất sét vệ sinh cho mèo khử mùi kháng khuẩn túi lớn",
                category: "phukien",
                subCat: "catvesinh",
                price: 95000,
                oldPrice: 115000,
                discount: 17,
                driveId: driveProductImages[5]
            },
            {
                id: "vtc-07",
                name: "Sữa tắm chuyên dụng khử mùi dưỡng lông mềm mượt cho chó mèo",
                category: "phukien",
                subCat: "suatam",
                price: 120000,
                oldPrice: 150000,
                discount: 20,
                driveId: driveProductImages[6]
            },
            {
                id: "vtc-08",
                name: "Thuốc nhỏ gáy & xịt trị ve rận, bọ chét, nấm ghẻ cho chó mèo",
                category: "dinhduong",
                subCat: "thuy",
                price: 135000,
                oldPrice: 165000,
                discount: 18,
                driveId: driveProductImages[7]
            },
            {
                id: "vtc-09",
                name: "Bộ dây dắt kèm yếm và vòng cổ êm ái chống giật cho chó mèo",
                category: "phukien",
                subCat: "daydat",
                price: 65000,
                oldPrice: 85000,
                discount: 24,
                driveId: driveProductImages[8]
            },
            {
                id: "vtc-10",
                name: "Bát ăn đôi inox chống trượt & bình cấp nước tự động cho thú cưng",
                category: "phukien",
                subCat: "quanao",
                price: 75000,
                oldPrice: 95000,
                discount: 21,
                driveId: driveProductImages[9]
            },
            {
                id: "vtc-11",
                name: "Đồ chơi bóng thừng gặm sạch răng & cần câu lông vũ giải trí cho mèo",
                category: "phukien",
                subCat: "dochoicho",
                price: 30000,
                oldPrice: 45000,
                discount: 33,
                driveId: driveProductImages[10]
            },
            {
                id: "vtc-12",
                name: "Balo vận chuyển phi hành gia & nệm ổ nằm êm ái cho chó mèo",
                category: "phukien",
                subCat: "dodungmeo",
                price: 195000,
                oldPrice: 250000,
                discount: 22,
                driveId: driveProductImages[11]
            }
        ];

        // Danh mục sản phẩm Dành Cho Chó (Theo đúng danh mục mẫu Petshophanoi)
        const dogProducts = [
            { id: "dog-1", name: "Hạt chó lớn CUNIO Adult 400g vị thịt bò giàu dinh dưỡng", subCat: "thucancho", price: 30000, oldPrice: 35000, discount: 14, driveId: driveProductImages[1] },
            { id: "dog-2", name: "Hạt chó GRAN DELI 700g thức ăn Nhật Mix Topping thơm ngon", subCat: "thucancho", price: 110000, oldPrice: 135000, discount: 19, driveId: driveProductImages[0] },
            { id: "dog-3", name: "Xúc xích gà mini Doggy Man gói 11 cây bánh thưởng cho chó", subCat: "thucancho", price: 30000, oldPrice: 45000, discount: 33, driveId: driveProductImages[2] },
            { id: "dog-4", name: "Dầu cá cho chó mèo Q8 OMEGA OIL FOR PET 150ml mượt lông", subCat: "dinhduongcho", price: 115000, oldPrice: 150000, discount: 23, driveId: driveProductImages[3] },
            { id: "dog-5", name: "Sữa bột cho Chó Dr.Kyan Predogen Gold gói 100g bổ sung canxi", subCat: "dinhduongcho", price: 45000, oldPrice: 52000, discount: 13, driveId: driveProductImages[4] },
            { id: "dog-6", name: "Đồ chơi cho chó dây thừng thắt 2 đầu & bóng cao su sạch răng", subCat: "dochoicho", price: 25000, oldPrice: 35000, discount: 29, driveId: driveProductImages[10] },
            { id: "dog-7", name: "Clicker huấn luyện phản xạ chuyên nghiệp cho cún cưng", subCat: "dochoicho", price: 30000, oldPrice: 50000, discount: 40, driveId: driveProductImages[8] },
            { id: "dog-8", name: "Đai lưng K9 kèm dây dắt chắc chắn dùng cho chó đi dạo", subCat: "dodungcho", price: 95000, oldPrice: 118000, discount: 19, driveId: driveProductImages[8] },
            { id: "dog-9", name: "Rọ mõm silicon mềm thoáng khí an toàn cho chó mọi kích cỡ", subCat: "dodungcho", price: 30000, oldPrice: 38000, discount: 21, driveId: driveProductImages[9] },
            { id: "dog-10", name: "Pate lon cho chó Muller 375g giàu thịt tươi và vitamin", subCat: "thucancho", price: 35000, oldPrice: 45000, discount: 22, driveId: driveProductImages[2] },
            { id: "dog-11", name: "Gel dinh dưỡng Virbac Nutri Plus Gel 120.5g phục hồi sức khỏe", subCat: "dinhduongcho", price: 255000, oldPrice: 285000, discount: 11, driveId: driveProductImages[3] },
            { id: "dog-12", name: "Bỉm tã vệ sinh & khay đi vệ sinh thành cao cho chó cưng", subCat: "dodungcho", price: 85000, oldPrice: 110000, discount: 23, driveId: driveProductImages[5] }
        ];

        // Danh mục sản phẩm Dành Cho Mèo (Theo đúng danh mục mẫu Petshophanoi)
        const catProducts = [
            { id: "cat-1", name: "Hạt cho mèo tiết niệu PETQ C90U Túi 1kg hỗ trợ thận", subCat: "thucanmeo", price: 190000, oldPrice: 230000, discount: 17, driveId: driveProductImages[0] },
            { id: "cat-2", name: "Thức ăn cho mèo mọi lứa tuổi CARE CAT & Pet Bite 1kg", subCat: "thucanmeo", price: 120000, oldPrice: 145000, discount: 17, driveId: driveProductImages[1] },
            { id: "cat-3", name: "Pate mèo lớn KitCat & Bite of Wild 70g vị cá ngừ sữa dê", subCat: "thucanmeo", price: 18000, oldPrice: 22000, discount: 18, driveId: driveProductImages[2] },
            { id: "cat-4", name: "Hộp trồng cỏ mèo thủy canh hỗ trợ tiêu búi lông tự nhiên", subCat: "thucanmeo", price: 35000, oldPrice: 50000, discount: 30, driveId: driveProductImages[3] },
            { id: "cat-5", name: "Cát đậu phụ cho mèo Miso 7L & EverCat vón cục khử mùi tốt", subCat: "catvesinh", price: 95000, oldPrice: 110000, discount: 14, driveId: driveProductImages[5] },
            { id: "cat-6", name: "Nhà vệ sinh khay cát mèo tai mèo kèm xẻng xúc cát 50x35x35cm", subCat: "catvesinh", price: 185000, oldPrice: 255000, discount: 27, driveId: driveProductImages[11] },
            { id: "cat-7", name: "Men khử mùi hôi cát mèo Zyme For Cat 100g thơm mát", subCat: "catvesinh", price: 25000, oldPrice: 35000, discount: 29, driveId: driveProductImages[6] },
            { id: "cat-8", name: "Đồ chơi mèo bàn cào móng & trụ cào móng Cat Tree", subCat: "dochoimeo", price: 165000, oldPrice: 195000, discount: 15, driveId: driveProductImages[10] },
            { id: "cat-9", name: "Đồ chơi mèo cần câu cán thép đế mút sàn & bóng lông vũ", subCat: "dochoimeo", price: 38000, oldPrice: 55000, discount: 31, driveId: driveProductImages[10] },
            { id: "cat-10", name: "Võng treo chuồng & đệm ngủ ấm áp cho mèo chất liệu vải dày", subCat: "dodungmeo", price: 45000, oldPrice: 65000, discount: 31, driveId: driveProductImages[11] },
            { id: "cat-11", name: "Sữa bột cho Mèo Dr.Kyan Precaten Gold Lon 400g", subCat: "thucanmeo", price: 190000, oldPrice: 210000, discount: 10, driveId: driveProductImages[4] },
            { id: "cat-12", name: "Lược chải lông rụng có nút bấm vệ sinh nhanh cho mèo", subCat: "dodungmeo", price: 45000, oldPrice: 60000, discount: 25, driveId: driveProductImages[9] }
        ];

        // Danh mục Phụ Kiện, Bổ Sung Dinh Dưỡng & Thuốc Thú Y
        const pkThuyProducts = [
            { id: "pk-1", name: "Dây xích inox kèm vòng cổ chuông cho chó mèo bền đẹp", subCat: "daydat", price: 35000, oldPrice: 45000, discount: 22, driveId: driveProductImages[8] },
            { id: "pk-2", name: "Vòng cổ chống liếm Elizabeth nhựa mềm bảo vệ chó mèo", subCat: "daydat", price: 45000, oldPrice: 60000, discount: 25, driveId: driveProductImages[8] },
            { id: "pk-3", name: "Áo tai thỏ cà rốt & áo phao lót lông ấm áp cho chó mèo", subCat: "quanao", price: 95000, oldPrice: 120000, discount: 21, driveId: driveProductImages[11] },
            { id: "pk-4", name: "Bát ăn uống đôi kèm bình cấp nước tự động chống tràn", subCat: "quanao", price: 75000, oldPrice: 95000, discount: 21, driveId: driveProductImages[9] },
            { id: "pk-5", name: "Sữa tắm SOS & nước hoa khử mùi hôi dưỡng lông chó mèo", subCat: "suatam", price: 115000, oldPrice: 145000, discount: 21, driveId: driveProductImages[6] },
            { id: "pk-6", name: "Dung dịch vệ sinh tai & lau ghèn mắt chuyên dụng thú cưng", subCat: "suatam", price: 65000, oldPrice: 80000, discount: 19, driveId: driveProductImages[6] },
            { id: "pk-7", name: "Viên nhai bổ sung Canxi, Khoáng chất & Vitamin cho chó mèo", subCat: "dinhduong", price: 90000, oldPrice: 115000, discount: 22, driveId: driveProductImages[4] },
            { id: "pk-8", name: "Gel dinh dưỡng Nuvita Gel 120g Vemedim kích thích ăn ngon", subCat: "dinhduong", price: 85000, oldPrice: 100000, discount: 15, driveId: driveProductImages[3] },
            { id: "pk-9", name: "Thuốc trị ve rận, bọ chét Frontline / NexGard cho chó mèo", subCat: "thuy", price: 145000, oldPrice: 175000, discount: 17, driveId: driveProductImages[7] },
            { id: "pk-10", name: "Thuốc xịt trị nấm da, ghẻ, viêm da rụng lông cho chó mèo", subCat: "thuy", price: 110000, oldPrice: 135000, discount: 19, driveId: driveProductImages[7] },
            { id: "pk-11", name: "Men tiêu hóa & thuốc hỗ trợ chữa bệnh đường ruột chó mèo", subCat: "thuy", price: 60000, oldPrice: 75000, discount: 20, driveId: driveProductImages[7] },
            { id: "pk-12", name: "Viên tẩy giun sán định kỳ an toàn cho chó và mèo", subCat: "thuy", price: 35000, oldPrice: 45000, discount: 22, driveId: driveProductImages[4] }
        ];

        // Danh mục bài viết trang chủ (Từ nội dung thực tế kênh Bác Sỹ Thú Y Vinh - Vinh Thú Cưng)
        const blogArticles = [
            {
                id: "art-1",
                cat: "dinhduong",
                catName: "Dinh Dưỡng Chó Mèo",
                title: "Mèo Anh Lông Ngắn Có Nên Ăn Cơm? Khám Phá 5 Sự Thật Người Nuôi Cần Biết",
                excerpt: "Mèo là động vật ăn thịt bắt buộc. Tìm hiểu cách kết hợp hạt dinh dưỡng, pate và khẩu phần ăn chuẩn giúp mèo Anh lông ngắn khỏe mạnh, tròn má.",
                image: driveProductImages[0],
                content: "<p>Rất nhiều bạn mới nuôi Mèo Anh Lông Ngắn thường thắc mắc có nên cho mèo ăn cơm trộn cá hay thịt như cách truyền thống hay không.</p><p><strong>1. Mèo cần hàm lượng đạm động vật cao:</strong> Hệ tiêu hóa của mèo được thiết kế để hấp thu protein từ thịt, cá, pate và hạt chuyên dụng thay vì tinh bột từ cơm trắng.</p><p><strong>2. Nguy cơ thiếu Taurine nếu chỉ ăn cơm:</strong> Taurine là axit amin thiết yếu cho mắt và tim mạch của mèo có sẵn trong thức ăn hạt và pate chất lượng tại Vinh Thú Cưng.</p><p><strong>3. Tỷ lệ phối trộn hợp lý:</strong> Nếu muốn cho ăn dặm, chỉ nên dùng dưới 10-15% tinh bột chín mềm kết hợp 85% thịt/pate/hạt chuyên dụng.</p>"
            },
            {
                id: "art-2",
                cat: "thuy",
                catName: "Kiến Thức Thú Y",
                title: "Tại Sao Người Nuôi Mèo Cho Mèo Ăn Gel Tiêu Búi Lông? 3 Bước Xử Lý Tắc Búi Lông",
                excerpt: "Mèo có thói quen tự liếm lông mỗi ngày khiến lông tích tụ trong dạ dày. Hướng dẫn sử dụng Gel tiêu búi lông và cỏ mèo đúng cách.",
                image: driveProductImages[3],
                content: "<p>Khi mèo tự làm sạch cơ thể, các gai nhỏ trên lưỡi mèo sẽ nuốt lượng lớn lông rụng vào đường tiêu hóa.</p><p><strong>Dấu hiệu mèo bị búi lông:</strong> Mèo hay khạc khan, nôn ra dịch vàng hoặc búi lông, biếng ăn, táo bón và lông xơ xác.</p><p><strong>3 Bước xử lý đơn giản tại nhà:</strong></p><p>- Bước 1: Cho mèo ăn Gel tiêu búi lông (như Nuvita Gel / Nutri Plus) 2-3 lần/tuần để làm mềm và đẩy búi lông qua đường phân.</p><p>- Bước 2: Bổ sung cỏ mèo tươi hoặc hạt hỗ trợ tiêu búi lông.</p><p>- Bước 3: Chải lông rụng hàng ngày bằng lược chuyên dụng.</p>"
            },
            {
                id: "art-3",
                cat: "thuy",
                catName: "Kiến Thức Thú Y",
                title: "7 Điều Người Nuôi Thú Cưng Cần Lưu Ý Để Phòng Tránh Nhiễm Giun Sán Chó Mèo",
                excerpt: "Lịch tẩy giun định kỳ và cách giữ vệ sinh khay cát, dụng cụ ăn uống giúp bảo vệ sức khỏe cho cả thú cưng và gia đình bạn.",
                image: driveProductImages[7],
                content: "<p>Phòng ngừa giun sán và ký sinh trùng (ve, rận, bọ chét) là bước quan trọng nhất khi nuôi thú cưng trong nhà.</p><p><strong>1. Tẩy giun đúng lịch:</strong> Chó mèo con từ 3-4 tuần tuổi cần được tẩy giun định kỳ. Chó mèo trưởng thành tẩy giun mỗi 3-6 tháng/lần.</p><p><strong>2. Nhỏ gáy trị ve bọ hàng tháng:</strong> Bọ chét chính là vật chủ trung gian truyền sán dây cho chó mèo.</p><p><strong>3. Vệ sinh khay cát và bát ăn mỗi ngày:</strong> Dọn phân trong khay cát vệ sinh hàng ngày và rửa sạch bát ăn uống.</p>"
            },
            {
                id: "art-4",
                cat: "spa",
                catName: "Spa & Grooming",
                title: "Quy Trình Tắm Sấy Grooming & Cắt Tỉa Lông Thú Cưng Chuẩn Thú Y Tại Vinh Thú Cưng",
                excerpt: "Từ bước kiểm tra da lông, gỡ rối, vệ sinh tai, cắt mài móng, vắt tuyến hôi đến tắm sấy và tạo kiểu thẩm mỹ tại 26 Trần Quý Cáp.",
                image: driveProductImages[6],
                content: "<p>Tại <strong>Vinh Thú Cưng – Love Pets (26 Trần Quý Cáp, Phường Bàn Thạch, Tp. Đà Nẵng)</strong>, quy trình Spa Grooming được thực hiện bài bản:</p><p>1. Kiểm tra tình trạng da và độ rối của bộ lông trước khi tắm.</p><p>2. Cắt móng, mài nhẵn móng, nhổ lông tai và vệ sinh tai bằng dung dịch khử khuẩn.</p><p>3. Tắm 2 bước bằng sữa tắm chuyên dụng phù hợp màu lông, kết hợp vắt tuyến hôi giúp khử mùi triệt để.</p><p>4. Sấy đánh bông lông và cắt tỉa tạo kiểu gọn gàng, đáng yêu theo mong muốn của chủ nuôi.</p>"
            }
        ];

        // Định dạng tiền tệ VNĐ
        function formatVND(amount) {
            return amount.toLocaleString('vi-VN') + '₫';
        }

        // Tạo HTML cho 1 thẻ sản phẩm chuẩn Flatsome
        // Chỉ có duy nhất nhãn giảm giá -XX% ở góc trên bên trái, không có các nhãn dán thừa
        // Tên sản phẩm đầy đủ không bị cắt chữ hay tràn ra ngoài
        function createProductCardHTML(product) {
            const imgUrl = `https://lh3.googleusercontent.com/d/${product.driveId}=w500`;
            const fallbackUrl = `https://drive.google.com/thumbnail?id=${product.driveId}&sz=w500`;
            return `
                <div class="flatsome-product-box bg-white rounded-xl border border-slate-200 overflow-hidden flex flex-col justify-between p-2.5 relative group">
                    <!-- Badge % giảm giá chuẩn Flatsome góc trên bên trái -->
                    <span class="flatsome-badge-sale">-${product.discount}%</span>

                    <div>
                        <!-- Ảnh sản phẩm vuông vắn -->
                        <div class="w-full aspect-square bg-slate-50 rounded-lg overflow-hidden mb-2 flex items-center justify-center p-1.5 border border-slate-100">
                            <img src="${imgUrl}"
                                 onerror="this.onerror=null; this.src='${fallbackUrl}';"
                                 alt="${product.name}"
                                 loading="lazy"
                                 class="w-full h-full object-contain group-hover:scale-105 transition duration-300">
                        </div>

                        <!-- Tên sản phẩm đầy đủ, không cắt bớt chữ, không tràn viền -->
                        <h3 class="product-title-full text-[12.5px] md:text-[13px] font-semibold text-slate-800 group-hover:text-brand transition mb-1.5">
                            ${product.name}
                        </h3>
                    </div>

                    <div class="pt-1 border-t border-slate-100 mt-1">
                        <!-- Giá giảm giá và giá gốc gạch ngang chuẩn Flatsome -->
                        <div class="flex flex-wrap items-baseline gap-1.5 mb-2">
                            <span class="text-red-600 font-extrabold text-[13.5px] md:text-sm">${formatVND(product.price)}</span>
                            <del class="text-slate-400 text-[11px] font-medium">${formatVND(product.oldPrice)}</del>
                        </div>

                        <!-- Nút thêm vào giỏ -->
                        <button onclick="addToCart('${product.id}', '${product.name.replace(/'/g, "\\'")}', ${product.price})"
                                class="w-full bg-orange-50 hover:bg-brand text-brand hover:text-white border border-orange-200 hover:border-brand text-[11.5px] font-bold py-1.5 px-2 rounded-lg transition flex items-center justify-center gap-1.5">
                            <i class="fa-solid fa-cart-plus"></i>
                            <span>Mua hàng</span>
                        </button>
                    </div>
                </div>
            `;
        }

        // Render danh sách sản phẩm vào các khung
        function renderProductsList(containerId, list) {
            const container = document.getElementById(containerId);
            if (!container) return;
            if (list.length === 0) {
                container.innerHTML = `<div class="col-span-full py-6 text-center text-xs text-slate-500">Không tìm thấy sản phẩm phù hợp.</div>`;
                return;
            }
            container.innerHTML = list.map(createProductCardHTML).join('');
        }

        // Lọc tab Hàng Mới Về (12 ảnh thực tế)
        function filterFeatured(cat) {
            const filtered = cat === 'all'
                ? featuredRealProducts
                : featuredRealProducts.filter(p => p.category === cat);
            renderProductsList('grid-featured-products', filtered);
        }

        // Lọc danh mục con trong từng khu vực
        function filterSubCategory(sectionId, subCat) {
            if (sectionId === 'sec-danh-cho-cho') {
                const list = subCat === 'all' ? dogProducts : dogProducts.filter(p => p.subCat === subCat);
                renderProductsList('grid-dog-products', list);
            } else if (sectionId === 'sec-danh-cho-meo') {
                const list = subCat === 'all' ? catProducts : catProducts.filter(p => p.subCat === subCat);
                renderProductsList('grid-cat-products', list);
            } else if (sectionId === 'sec-phukien-thuy') {
                const list = subCat === 'all' ? pkThuyProducts : pkThuyProducts.filter(p => p.subCat === subCat);
                renderProductsList('grid-pk-products', list);
            }
        }

        // Tìm kiếm trực tiếp trên thanh Header
        function filterBySearch() {
            const keyword = (document.getElementById('search-input').value || '').trim().toLowerCase();
            if (!keyword) {
                renderProductsList('grid-featured-products', featuredRealProducts);
                return;
            }
            const allCombined = [...featuredRealProducts, ...dogProducts, ...catProducts, ...pkThuyProducts];
            const uniqueMap = new Map();
            allCombined.forEach(item => {
                if (item.name.toLowerCase().includes(keyword)) {
                    uniqueMap.set(item.name, item);
                }
            });
            const results = Array.from(uniqueMap.values());
            renderProductsList('grid-featured-products', results);
        }

        function filterBySearchMobile() {
            const val = document.getElementById('search-input-mobile').value;
            const desktopInput = document.getElementById('search-input');
            if (desktopInput) desktopInput.value = val;
            filterBySearch();
            document.getElementById('sec-hang-moi').scrollIntoView({ behavior: 'smooth' });
        }

        // Render danh sách bài viết trang chủ
        function renderArticles(cat = 'all') {
            const container = document.getElementById('grid-articles');
            if (!container) return;
            const filtered = cat === 'all' ? blogArticles : blogArticles.filter(a => a.cat === cat);
            container.innerHTML = filtered.map(art => `
                <article class="bg-slate-50 rounded-xl border border-slate-200 overflow-hidden flex flex-col justify-between hover:shadow-md transition">
                    <div>
                        <div class="w-full h-40 bg-white border-b border-slate-100 flex items-center justify-center p-2 overflow-hidden">
                            <img src="https://lh3.googleusercontent.com/d/${art.image}=w500"
                                 onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=${art.image}&sz=w500';"
                                 alt="${art.title}"
                                 class="w-full h-full object-contain">
                        </div>
                        <div class="p-3.5">
                            <span class="inline-block text-[10.5px] font-bold text-brand uppercase mb-1">${art.catName}</span>
                            <h3 class="product-title-full text-xs md:text-[13.5px] font-bold text-slate-900 mb-1.5 hover:text-brand cursor-pointer" onclick="openArticleModal('${art.id}')">
                                ${art.title}
                            </h3>
                            <p class="text-xs text-slate-600 leading-relaxed">
                                ${art.excerpt}
                            </p>
                        </div>
                    </div>
                    <div class="px-3.5 pb-3 pt-1">
                        <button onclick="openArticleModal('${art.id}')" class="text-xs font-bold text-brand hover:underline flex items-center gap-1">
                            <span>Xem chi tiết bài viết</span>
                            <i class="fa-solid fa-arrow-right text-[10px]"></i>
                        </button>
                    </div>
                </article>
            `).join('');
        }

        function filterArticles(cat) {
            renderArticles(cat);
        }

        function openArticleModal(articleId) {
            const art = blogArticles.find(a => a.id === articleId);
            if (!art) return;
            document.getElementById('modal-article-cat').textContent = art.catName;
            document.getElementById('modal-article-title').textContent = art.title;
            document.getElementById('modal-article-body').innerHTML = art.content;
            const modal = document.getElementById('article-modal');
            modal.classList.remove('hidden');
            modal.classList.add('flex');
        }

        function closeArticleModal() {
            const modal = document.getElementById('article-modal');
            modal.classList.add('hidden');
            modal.classList.remove('flex');
        }

        // ==================== SLIDER 2 BANNER TỰ TRƯỢT ====================
        let currentSlide = 0;
        const totalSlides = 2;
        let slideInterval = null;

        function showSlide(index) {
            const slides = document.querySelectorAll('.banner-slide');
            const dots = document.querySelectorAll('.slide-dot');
            currentSlide = (index + totalSlides) % totalSlides;

            slides.forEach((sl, idx) => {
                if (idx === currentSlide) {
                    sl.classList.remove('hidden');
                    sl.classList.add('block');
                } else {
                    sl.classList.add('hidden');
                    sl.classList.remove('block');
                }
            });

            dots.forEach((dot, idx) => {
                if (idx === currentSlide) {
                    dot.className = 'slide-dot w-6 h-2 rounded-full bg-brand transition-all';
                } else {
                    dot.className = 'slide-dot w-2 h-2 rounded-full bg-slate-400/70 transition-all';
                }
            });
        }

        function changeSlide(step) {
            showSlide(currentSlide + step);
            restartSlideTimer();
        }

        function goToSlide(index) {
            showSlide(index);
            restartSlideTimer();
        }

        function restartSlideTimer() {
            if (slideInterval) clearInterval(slideInterval);
            slideInterval = setInterval(() => {
                showSlide(currentSlide + 1);
            }, 4500);
        }

        // ==================== GIỎ HÀNG & FORM BÁO GIÁ ====================
        let cart = [];

        function showToast(msg) {
            const box = document.getElementById('toast-box');
            const text = document.getElementById('toast-message');
            text.textContent = msg;
            box.classList.remove('hidden');
            box.classList.add('flex');
            setTimeout(() => {
                box.classList.add('hidden');
                box.classList.remove('flex');
            }, 3000);
        }

        function addToCart(id, name, price) {
            const existing = cart.find(item => item.id === id);
            if (existing) {
                existing.qty += 1;
            } else {
                cart.push({ id, name, price, qty: 1 });
            }
            updateCartUI();
            showToast(`Đã thêm "${name}" vào giỏ hàng!`);
        }

        function updateCartUI() {
            const totalQty = cart.reduce((sum, item) => sum + item.qty, 0);
            const totalPrice = cart.reduce((sum, item) => sum + item.price * item.qty, 0);
            document.getElementById('cart-count-badge').textContent = totalQty;
            document.getElementById('cart-total-price').textContent = formatVND(totalPrice);

            const container = document.getElementById('cart-items-container');
            if (cart.length === 0) {
                container.innerHTML = `<div class="py-6 text-center text-slate-400">Giỏ hàng của bạn đang trống.</div>`;
                return;
            }
            container.innerHTML = cart.map((item, idx) => `
                <div class="flex items-center justify-between gap-2 p-2.5 rounded-lg bg-slate-50 border border-slate-200">
                    <div class="flex-1">
                        <div class="font-semibold text-slate-800">${item.name}</div>
                        <div class="text-brand font-bold mt-0.5">${formatVND(item.price)} x ${item.qty}</div>
                    </div>
                    <div class="flex items-center gap-1">
                        <button onclick="changeCartQty(${idx}, -1)" class="w-6 h-6 rounded bg-white border border-slate-300 font-bold">-</button>
                        <span class="px-1.5 font-semibold">${item.qty}</span>
                        <button onclick="changeCartQty(${idx}, 1)" class="w-6 h-6 rounded bg-white border border-slate-300 font-bold">+</button>
                    </div>
                </div>
            `).join('');
        }

        function changeCartQty(index, delta) {
            cart[index].qty += delta;
            if (cart[index].qty <= 0) {
                cart.splice(index, 1);
            }
            updateCartUI();
        }

        function openCartModal() {
            updateCartUI();
            const modal = document.getElementById('cart-modal');
            modal.classList.remove('hidden');
            modal.classList.add('flex');
        }

        function closeCartModal() {
            const modal = document.getElementById('cart-modal');
            modal.classList.add('hidden');
            modal.classList.remove('flex');
        }

        function checkoutFromCart() {
            if (cart.length === 0) {
                showToast("Giỏ hàng đang trống, vui lòng chọn sản phẩm!");
                return;
            }
            const summary = cart.map(i => `${i.name} (SL: ${i.qty})`).join(', ');
            closeCartModal();
            const msgField = document.getElementById('quote-message');
            if (msgField) {
                msgField.value = `Đặt mua đơn hàng: ${summary}`;
            }
            document.getElementById('section-baogia').scrollIntoView({ behavior: 'smooth' });
            showToast("Vui lòng điền SĐT vào Form Yêu Cầu để Vinh Thú Cưng xác nhận đơn hàng!");
        }

        function submitQuoteForm(e) {
            e.preventDefault();
            const name = document.getElementById('quote-name').value.trim();
            const phone = document.getElementById('quote-phone').value.trim();
            const cat = document.getElementById('quote-category').value;
            showToast(`Cảm ơn ${name} (${phone})! Yêu cầu "${cat}" đã được gửi tới Vinh Thú Cưng (0984.244.001).`);
            document.getElementById('quote-form').reset();
        }

        function toggleMobileMenu() {
            const drawer = document.getElementById('mobile-menu-drawer');
            const backdrop = document.getElementById('mobile-menu-backdrop');
            const isHidden = drawer.classList.contains('-translate-x-full');
            if (isHidden) {
                drawer.classList.remove('-translate-x-full');
                backdrop.classList.remove('hidden');
            } else {
                drawer.classList.add('-translate-x-full');
                backdrop.classList.add('hidden');
            }
        }

        // Khởi chạy toàn bộ giao diện khi tải trang
        window.onload = function () {
            renderProductsList('grid-featured-products', featuredRealProducts);
            renderProductsList('grid-dog-products', dogProducts);
            renderProductsList('grid-cat-products', catProducts);
            renderProductsList('grid-pk-products', pkThuyProducts);
            renderArticles('all');
            restartSlideTimer();
        };
    </script>
</body>
</html>
