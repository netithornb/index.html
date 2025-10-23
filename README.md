<!DOCTYPE html>
<html lang="th" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!-- Updated Title -->
    <title>SYNDICATE LAW OFFICES - บริษัทกฎหมายและที่ปรึกษา</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&family=Sarabun:wght@400;500;600;700&display=swap" rel="stylesheet">
    
    <style>
        body {
            box-sizing: border-box;
            /* Using Inter for EN and Sarabun for TH */
            font-family: 'Inter', 'Sarabun', sans-serif;
        }

        /* Set Sarabun for Thai text */
        :lang(th) {
            font-family: 'Sarabun', 'Inter', sans-serif;
        }
        
        .service-card {
            transition: all 0.4s cubic-bezier(0.4, 0, 0.2, 1);
        }
        
        .service-card:hover {
            transform: translateY(-8px) scale(1.02);
            box-shadow: 0 25px 50px rgba(0,0,0,0.1);
        }
        
        .lang-content {
            display: none;
        }
        
        .lang-content.active {
            display: block;
        }
        
        .fade-in {
            animation: fadeIn 0.8s ease-out;
        }
        
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(30px); }
            to { opacity: 1; transform: translateY(0); }
        }
        
        .pricing-card {
            transition: all 0.4s ease;
        }
        
        .pricing-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 30px 60px rgba(0,0,0,0.15);
        }
        
        .mobile-menu {
            transform: translateX(-100%);
            transition: transform 0.3s ease;
        }
        
        .mobile-menu.open {
            transform: translateX(0);
        }
        
        .review-card {
            transition: all 0.3s ease;
            /* Updated accent color */
            border-left: 4px solid #b89f77; 
        }

        .review-card:hover {
            transform: translateY(-2px);
            box-shadow: 0 10px 25px rgba(0,0,0,0.08);
        }

        .star-rating {
            color: #fbbf24;
        }

        .admin-panel {
            background: linear-gradient(135deg, #f3f4f6, #e5e7eb);
            border: 2px dashed #9ca3af;
        }

        /* Styles for new Tabbed Service Section */
        .tab-button {
            transition: all 0.3s ease;
            border-bottom: 3px solid transparent;
        }
        .tab-button.active {
            /* Updated accent color */
            border-bottom-color: #b89f77;
            color: #1a202c; /* Darker text */
        }
        .tab-content {
            display: none;
        }
        .tab-content.active {
            display: block;
            animation: fadeIn 0.5s ease-in;
        }

        /* New Accordion Styles */
        .accordion-content {
            max-height: 0;
            overflow: hidden;
            transition: max-height 0.4s ease-out;
        }
        .accordion-button.open .accordion-arrow {
            transform: rotate(180deg);
        }
        .accordion-arrow {
            transition: transform 0.3s ease;
        }

        /* Modal Styles */
        .modal-backdrop {
            display: none;
            position: fixed;
            inset: 0;
            background-color: rgba(0, 0, 0, 0.6);
            z-index: 999;
            opacity: 0;
            transition: opacity 0.3s ease;
        }
        .modal-content {
            display: none;
            position: fixed;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            background-color: white;
            padding: 2rem;
            border-radius: 0.5rem;
            box-shadow: 0 20px 25px -5px rgba(0, 0, 0, 0.1), 0 10px 10px -5px rgba(0, 0, 0, 0.04);
            z-index: 1000;
            width: 90%;
            max-width: 400px;
            opacity: 0;
            transition: opacity 0.3s ease, transform 0.3s ease;
            transform: translate(-50%, -60%);
        }
        .modal-backdrop.open, .modal-content.open {
            display: block;
            opacity: 1;
        }
        .modal-content.open {
            transform: translate(-50%, -50%);
        }

    </style>
    <!-- Define new color theme for Tailwind -->
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        'brand-dark': '#1a202c', // Deep charcoal/navy
                        'brand-dark-secondary': '#2d3748',
                        'brand-accent': '#b89f77', // Sophisticated gold
                        'brand-accent-hover': '#a18a68',
                    },
                    fontFamily: {
                        'sans': ['Inter', 'Sarabun', 'sans-serif'],
                        'body': ['Inter', 'Sarabun', 'sans-serif'],
                    }
                }
            }
        }
    </script>
</head>
<body class="bg-gray-50">
    <!-- Navigation -->
    <nav class="bg-white shadow-sm border-b border-gray-200 fixed w-full top-0 z-50">
        <div class=“px-4 sm:px-6 lg:px-8”>
            <div class="flex justify-between items-center h-20">
                <div class="flex items-center">
                    <div class="flex-shrink-0 flex items-center">
    <!-- โลโก้ SVG -->
    <svg version="1.1" id="_x32_" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" viewBox="0 0 512 512" xml:space="preserve" class="h-14 w-auto">
        <style type="text/css">
            .st0{fill:#000000;}
        </style>
        <g>
            <path class="st0" d="M501.98,206.15c-9.769-23.023-25.998-42.56-46.458-56.389c-10.181-6.873-21.446-12.34-33.536-16.068
                c-12.009-3.809-24.842-5.798-38.088-5.798c-16.982,0-33.294,3.316-48.197,9.365c-1.246,0.492-2.402,0.986-3.558,1.568
                c-13.416,5.879-25.675,14.16-36.188,24.017c-3.396,3.227-6.623,6.623-9.858,10.432c-5.709,6.542-11.588,14.079-17.305,21.696
                c-1.157,1.568-2.402,3.226-3.558,4.804c-3.146,4.302-33.212,48.358-38.509,56.226c-2.652,3.97-5.798,8.442-9.195,13.327
                c-0.744,1.076-1.568,2.24-2.393,3.396c-5.636,8.031-11.928,16.481-17.726,23.937c-2.895,3.72-5.798,7.197-8.281,10.1
                c-2.563,2.976-4.884,5.378-6.542,6.954c-7.116,6.704-15.486,12.171-24.672,15.899c-9.194,3.728-19.214,5.798-29.816,5.798
                c-7.286,0-14.322-0.996-20.944-2.815c-3.396-0.913-6.712-2.07-9.939-3.477c-14.248-5.968-26.419-16.068-34.95-28.74
                c-4.302-6.372-7.699-13.327-10.019-20.783c-2.233-7.456-3.558-15.316-3.558-23.597c0-11.014,2.24-21.365,6.21-30.892
                c6.049-14.24,16.149-26.329,28.821-34.942c6.372-4.31,13.326-7.618,20.782-9.939c7.448-2.321,15.316-3.638,23.597-3.638
                c10.602,0.08,20.622,2.07,29.816,5.79c9.187,3.808,17.556,9.194,24.672,15.898c1.658,1.577,3.979,4.059,6.542,6.962
                c4.472,5.216,9.769,11.92,15.074,18.964c2.07,2.814,4.14,5.628,6.21,8.523c7.949-11.588,21.858-31.959,29.144-42.48
                c-1.237-1.658-2.482-3.307-3.72-4.965c-3.316-4.23-6.631-8.281-9.938-12.009c-3.316-3.809-6.462-7.205-9.858-10.432
                c-11.426-10.772-24.922-19.545-39.746-25.586c-14.904-6.049-31.222-9.365-48.196-9.365c-17.637,0-34.53,3.566-49.927,10.108
                c-23.022,9.688-42.487,25.918-56.316,46.369c-6.873,10.19-12.332,21.527-16.141,33.536C1.989,229.997,0,242.75,0,256.004
                c0,17.637,3.558,34.53,10.02,49.846c9.768,23.104,25.998,42.569,46.369,56.397c10.27,6.874,21.535,12.332,33.624,16.141
                c12.008,3.728,24.842,5.717,38.088,5.717c16.974,0,33.293-3.316,48.196-9.356c14.824-6.049,28.239-14.824,39.666-25.506l0.08-0.081
                c3.397-3.146,6.543-6.631,9.858-10.44c5.709-6.542,11.588-14.071,17.305-21.689c1.157-1.577,2.402-3.154,3.558-4.723
                c3.146-4.391,44.307-64.758,47.696-69.642c0.752-1.076,1.577-2.232,2.401-3.396c5.637-7.95,11.928-16.48,17.726-23.928
                c2.895-3.728,5.798-7.206,8.281-10.101c2.564-2.984,4.885-5.386,6.542-6.962c7.116-6.704,15.486-12.09,24.673-15.898
                c2.24-0.906,4.472-1.649,6.792-2.402c7.286-2.15,14.984-3.307,23.023-3.388c11.013,0.08,21.446,2.232,30.882,6.291
                c14.241,5.96,26.42,16.06,34.943,28.732c4.31,6.38,7.706,13.335,10.019,20.782c2.321,7.456,3.566,15.324,3.566,23.605
                c0,11.014-2.24,21.446-6.21,30.883c-6.049,14.24-16.149,26.419-28.821,34.942c-6.372,4.31-13.326,7.707-20.782,9.939
                c-7.367,2.321-15.316,3.648-23.597,3.648c-10.602,0-20.622-2.07-29.816-5.798c-9.187-3.728-17.557-9.195-24.673-15.899
                c-1.658-1.577-3.979-4.059-6.542-6.954c-4.472-5.135-9.776-11.928-15.074-18.963c-2.15-2.815-4.221-5.718-6.291-8.613
                c-0.663,0.994-1.326,1.99-2.07,3.065c-13.666,20.039-22.279,32.71-26.994,39.576c1.237,1.658,2.483,3.235,3.72,4.893
                c3.316,4.221,6.631,8.281,9.938,12c3.234,3.808,6.462,7.294,9.858,10.44c11.426,10.763,24.923,19.538,39.746,25.587
                c14.904,6.04,31.215,9.356,48.197,9.356c17.636,0,34.53-3.558,49.846-10.019c23.103-9.769,42.56-25.999,56.396-46.458
                c6.866-10.181,12.421-21.446,16.141-33.536C510.01,282.083,512,269.25,512,256.004C512,238.367,508.442,221.474,501.98,206.15z"/>
        </g>
    </svg>
    
    <!-- เพิ่มคำว่า SYNDICATE LAW OFFICE ตรงนี้ -->
    <span class="ml-3 font-bold text-xl text-gray-800">SYNDICATE LAW OFFICE</span>
</div>
                
                <div class="hidden md:block">
                    <div class="ml-10 flex items-baseline space-x-4">
                        <a href="#home" class="nav-link text-gray-700 hover:text-brand-accent px-3 py-2 rounded-md text-sm font-medium transition-colors">หน้าแรก</a>
                        <a href="#services" class="nav-link text-gray-700 hover:text-brand-accent px-3 py-2 rounded-md text-sm font-medium transition-colors">บริการ</a>
                        <a href="#expertise" class="nav-link text-gray-700 hover:text-brand-accent px-3 py-2 rounded-md text-sm font-medium transition-colors">ความเชี่ยวชาญ</a>
                        <a href="#team" class="nav-link text-gray-700 hover:text-brand-accent px-3 py-2 rounded-md text-sm font-medium transition-colors">ทีมงาน</a>
                        <!-- Added Blog Link -->
                        <a href="#blog" class="nav-link text-gray-700 hover:text-brand-accent px-3 py-2 rounded-md text-sm font-medium transition-colors">ศูนย์รวมความรู้</a>
                        <a href="#pricing" class="nav-link text-gray-700 hover:text-brand-accent px-3 py-2 rounded-md text-sm font-medium transition-colors">ราคา</a>
                        <a href="#testimonials" class="nav-link text-gray-700 hover:text-brand-accent px-3 py-2 rounded-md text-sm font-medium transition-colors">ความคิดเห็น</a>
                        <a href="#contact" class="nav-link text-gray-700 hover:text-brand-accent px-3 py-2 rounded-md text-sm font-medium transition-colors">ติดต่อ</a>
                    </div>
                </div>
                
                <div class="flex items-center space-x-2">
                    <button id="lang-th" class="lang-btn bg-brand-dark text-white px-3 py-1 rounded-md text-sm font-medium transition-colors">ไทย</button>
                    <button id="lang-en" class="lang-btn bg-gray-200 text-gray-700 px-3 py-1 rounded-md text-sm font-medium transition-colors">EN</button>
                    <button id="mobile-menu-btn" class="md:hidden text-gray-700 hover:text-brand-accent">
                        <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16"></path>
                        </svg>
                    </button>
                </div>
            </div>
        </div>
        
        <!-- Mobile Menu -->
        <div id="mobile-menu" class="mobile-menu fixed inset-y-0 left-0 w-64 bg-white shadow-lg md:hidden z-40">
            <div class="p-4">
                <div class="flex justify-between items-center mb-8">
                    <h2 class="text-xl font-bold text-brand-dark">เมนู</h2>
                    <button id="close-mobile-menu" class="text-gray-500">
                        <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12"></path>
                        </svg>
                    </button>
                </div>
                <nav class="space-y-4">
                    <a href="#home" class="mobile-nav-link block text-gray-700 hover:text-brand-accent py-2">หน้าแรก</a>
                    <a href="#services" class="mobile-nav-link block text-gray-700 hover:text-brand-accent py-2">บริการ</a>
                    <a href="#expertise" class="mobile-nav-link block text-gray-700 hover:text-brand-accent py-2">ความเชี่ยวชาญ</a>
                    <a href="#team" class="mobile-nav-link block text-gray-700 hover:text-brand-accent py-2">ทีมงาน</a>
                    <a href="#blog" class="mobile-nav-link block text-gray-700 hover:text-brand-accent py-2">ศูนย์รวมความรู้</a>
                    <a href="#pricing" class="mobile-nav-link block text-gray-700 hover:text-brand-accent py-2">ราคา</a>
                    <a href="#testimonials" class="mobile-nav-link block text-gray-700 hover:text-brand-accent py-2">ความคิดเห็น</a>
                    <a href="#contact" class="mobile-nav-link block text-gray-700 hover:text-brand-accent py-2">ติดต่อ</a>
                </nav>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <!-- Updated Hero with background image and overlay -->
    <section id="home" class="pt-20 relative overflow-hidden bg-brand-dark bg-cover bg-center" style="background-image: url('https://placehold.co/1920x1080/1a202c/4a5568?text=SYNDICATE+LAW+OFFICES');">
        <!-- Dark Overlay -->
        <div class="absolute inset-0 bg-black/60"></div>
        
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-20 md:py-32 relative z-10">
            <div class="grid md:grid-cols-2 gap-12 items-center">
                <div class="text-white">
                    <!-- Thai Content -->
                    <div class="lang-content active" data-lang="th">
                        <h1 class="text-4xl md:text-6xl font-bold mb-6 fade-in">
                            ที่ปรึกษากฎหมายมืออาชีพ
                            <span class="block text-brand-accent">เคียงข้างธุรกิจคุณ</span>
                        </h1>
                        <p class="text-xl md:text-2xl mb-8 opacity-90 fade-in">
                            บริการกฎหมาย ภาษี และบัญชีครบวงจร ด้วยประสบการณ์กว่า 40 ปี 
                            พร้อมทีมผู้เชี่ยวชาญระดับสากล
                        </p>
                        <div class="space-x-4 fade-in">
                            <button class="bg-brand-accent text-brand-dark px-8 py-3 rounded-md font-semibold hover:bg-brand-accent-hover transition-colors shadow-lg">
                                📞 ปรึกษาเบื้องต้น
                            </button>
                        </div>
                    </div>
                    
                    <!-- English Content -->
                    <div class="lang-content" data-lang="en">
                        <h1 class="text-4xl md:text-6xl font-bold mb-6 fade-in">
                            Professional Legal Advisors
                            <span class="block text-brand-accent">Partnering Your Business</span>
                        </h1>
                        <p class="text-xl md:text-2xl mb-8 opacity-90 fade-in">
                            Comprehensive Legal, Tax & Accounting Consultancy with over 15 years of experience 
                            and an international expert team.
                        </p>
                        <div class="space-x-4 fade-in">
                            <button class="bg-brand-accent text-brand-dark px-8 py-3 rounded-md font-semibold hover:bg-brand-accent-hover transition-colors shadow-lg">
                                📞 Initial consultation
                            </button>
                        </div>
                    </div>
                </div>
                
                <div class="slide-in-right">
                    <div class="bg-white bg-opacity-10 backdrop-blur-lg rounded-xl p-8 border border-white border-opacity-20 text-white">
                        <div class="grid grid-cols-2 gap-6 text-center">
                            <div>
                                <div class="text-4xl font-bold counter" data-target="1500">0</div>
                                <div class="text-sm opacity-80 lang-content active" data-lang="th">คดีที่ชนะ</div>
                                <div class="text-sm opacity-80 lang-content" data-lang="en">Cases Won</div>
                            </div>
                            <div>
                                <div class="text-4xl font-bold counter" data-target="500">0</div>
                                <div class="text-sm opacity-80 lang-content active" data-lang="th">ลูกค้าพึงพอใจ</div>
                                <div class="text-sm opacity-80 lang-content" data-lang="en">Satisfied Clients</div>
                            </div>
                            <div>
                                <div class="text-4xl font-bold counter" data-target="40">0</div>
                                <div class="text-sm opacity-80 lang-content active" data-lang="th">ปีประสบการณ์</div>
                                <div class="text-sm opacity-80 lang-content" data-lang="en">Years Experience</div>
                            </div>
                            <div>
                                <div class="text-4xl font-bold counter" data-target="10">0</div>
                                <div class="text-sm opacity-80 lang-content active" data-lang="th">ผู้เชี่ยวชาญ</div>
                                <div class="text-sm opacity-80 lang-content" data-lang="en">Experts</div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Services Section - NEW TABBED LAYOUT -->
    <section id="services" class="py-20 bg-white">
        <div class=“px-4 sm:px-6 lg:px-8”>
            <!-- Thai Content -->
            <div class="lang-content active" data-lang="th">
                <div class="text-center mb-12">
                    <h2 class="text-4xl md:text-5xl font-bold text-gray-900 mb-6">ขอบเขตบริการของเรา</h2>
                    <p class="text-xl text-gray-600 max-w-3xl mx-auto">
                        เราให้บริการที่ปรึกษากฎหมายครอบคลุมทุกมิติสำหรับธุรกิจและบุคคลธรรมดา
                    </p>
                </div>
                
                <!-- Service Tabs TH -->
                <div class="mb-8 flex justify-center space-x-4 md:space-x-8 border-b border-gray-200">
                    <button class="tab-button text-lg font-semibold text-gray-500 py-4 active" data-tab="th-business">
                        สำหรับธุรกิจและนักลงทุน
                    </button>
                    <button class="tab-button text-lg font-semibold text-gray-500 py-4" data-tab="th-individuals">
                        สำหรับบุคคลธรรมดา
                    </button>
                    <button class="tab-button text-lg font-semibold text-gray-500 py-4" data-tab="th-expat">
                        บริการสำหรับชาวต่างชาติ
                    </button>
                </div>

                <!-- Tab Content TH -->
                <div id="th-business" class="tab-content active">
                    <div class="max-w-4xl mx-auto space-y-4">
                        <!-- Accordion Item -->
                        <div class="border rounded-lg overflow-hidden">
                            <button class="accordion-button w-full flex justify-between items-center p-5 bg-gray-50 hover:bg-gray-100">
                                <span class="text-xl font-semibold text-brand-dark">กฎหมายองค์กรธุรกิจ (Corporate Law)</span>
                                <svg class="accordion-arrow w-6 h-6 text-gray-600" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"></path></svg>
                            </button>
                            <div class="accordion-content">
                                <ul class="p-5 pt-0 list-disc list-inside text-gray-700 space-y-2">
                                    <li>การจดทะเบียนบริษัท ห้างหุ้นส่วน และนิติบุคคลทุกประเภท</li>
                                    <li>การขอใบอนุญาตประกอบธุรกิจ (เช่น ใบอนุญาตประกอบธุรกิจของคนต่างด้าว)</li>
                                    <li>การควบรวมและซื้อกิจการ (M&A)</li>
                                    <li>การจัดทำและตรวจสอบสัญญาทางธุรกิจทุกประเภท</li>
                                </ul>
                            </div>
                        </div>
                        <!-- Accordion Item -->
                        <div class="border rounded-lg overflow-hidden">
                            <button class="accordion-button w-full flex justify-between items-center p-5 bg-gray-50 hover:bg-gray-100">
                                <span class="text-xl font-semibold text-brand-dark">กฎหมายแรงงาน (Employment Law)</span>
                                <svg class="accordion-arrow w-6 h-6 text-gray-600" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"></path></svg>
                            </button>
                            <div class="accordion-content">
                                <ul class="p-5 pt-0 list-disc list-inside text-gray-700 space-y-2">
                                    <li>การร่างสัญญาจ้าง ข้อบังคับการทำงาน</li>
                                    <li>การให้คำปรึกษาด้านการเลิกจ้างและค่าชดเชย</li>
                                    <li>การดำเนินคดีในศาลแรงงาน</li>
                                </ul>
                            </div>
                        </div>
                        <!-- Accordion Item -->
                        <div class="border rounded-lg overflow-hidden">
                            <button class="accordion-button w-full flex justify-between items-center p-5 bg-gray-50 hover:bg-gray-100">
                                <span class="text-xl font-semibold text-brand-dark">ทรัพย์สินทางปัญญา (Intellectual Property)</span>
                                <svg class="accordion-arrow w-6 h-6 text-gray-600" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"></path></svg>
                            </button>
                            <div class="accordion-content">
                                <ul class="p-5 pt-0 list-disc list-inside text-gray-700 space-y-2">
                                    <li>การสืบค้นและยื่นจดทะเบียนเครื่องหมายการค้า สิทธิบัตร และลิขสิทธิ์</li>
                                    <li>การจัดทำสัญญาอนุญาตให้ใช้สิทธิ</li>
                                    <li>การปกป้องและบังคับใช้สิทธิทางทรัพย์สินทางปัญญา</li>
                                </ul>
                            </div>
                        </div>
                        <!-- Accordion Item -->
                        <div class="border rounded-lg overflow-hidden">
                            <button class="accordion-button w-full flex justify-between items-center p-5 bg-gray-50 hover:bg-gray-100">
                                <span class="text-xl font-semibold text-brand-dark">ภาษีและการบัญชี (Tax & Accounting)</span>
                                <svg class="accordion-arrow w-6 h-6 text-gray-600" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"></path></svg>
                            </button>
                            <div class="accordion-content">
                                <ul class="p-5 pt-0 list-disc list-inside text-gray-700 space-y-2">
                                    <li>การวางแผนภาษีสำหรับนิติบุคคล</li>
                                    <li>การให้คำปรึกษาด้านภาษีระหว่างประเทศ</li>
                                    <li>บริการด้านบัญชีแบบครบวงจร (ร่วมกับพันธมิตร)</li>
                                </ul>
                            </div>
                        </div>
                    </div>
                </div>

                <div id="th-individuals" class="tab-content">
                    <div class="max-w-4xl mx-auto space-y-4">
                        <!-- Accordion Item -->
                        <div class="border rounded-lg overflow-hidden">
                            <button class="accordion-button w-full flex justify-between items-center p-5 bg-gray-50 hover:bg-gray-100">
                                <span class="text-xl font-semibold text-brand-dark">กฎหมายครอบครัว (Family Law)</span>
                                <svg class="accordion-arrow w-6 h-6 text-gray-600" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"></path></svg>
                            </button>
                            <div class="accordion-content">
                                <ul class="p-5 pt-0 list-disc list-inside text-gray-700 space-y-2">
                                    <li>การจดทะเบียนสมรสกับชาวต่างชาติ</li>
                                    <li>สัญญา ก่อนและหลังสมรส</li>
                                    <li>การดำเนินการหย่าร้าง และข้อตกลงเรื่องทรัพย์สินและบุตร</li>
                                </ul>
                            </div>
                        </div>
                        <!-- Accordion Item -->
                        <div class="border rounded-lg overflow-hidden">
                            <button class="accordion-button w-full flex justify-between items-center p-5 bg-gray-50 hover:bg-gray-100">
                                <span class="text-xl font-semibold text-brand-dark">กฎหมายมรดก (Inheritance Law)</span>
                                <svg class="accordion-arrow w-6 h-6 text-gray-600" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"></path></svg>
                            </button>
                            <div class="accordion-content">
                                <ul class="p-5 pt-0 list-disc list-inside text-gray-700 space-y-2">
                                    <li>การทำพินัยกรรม</li>
                                    <li>การร้องขอแต่งตั้งผู้จัดการมรดก</li>
                                    <li>การฟ้องร้องแบ่งมรดก</li>
                                </ul>
                            </div>
                        </div>
                        <!-- Accordion Item -->
                        <div class="border rounded-lg overflow-hidden">
                            <button class="accordion-button w-full flex justify-between items-center p-5 bg-gray-50 hover:bg-gray-100">
                                <span class="text-xl font-semibold text-brand-dark">อสังหาริมทรัพย์ (Real Estate)</span>
                                <svg class="accordion-arrow w-6 h-6 text-gray-600" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"></path></svg>
                            </button>
                            <div class="accordion-content">
                                <ul class="p-5 pt-0 list-disc list-inside text-gray-700 space-y-2">
                                    <li>การตรวจสอบเอกสารสิทธิ์ก่อนการซื้อขาย</li>
                                    <li>การให้คำปรึกษาการซื้อคอนโดมิเนียมโดยชาวต่างชาติ</li>
                                    <li>การร่างสัญญาเช่าและสัญญาซื้อขาย</li>
                                </ul>
                            </div>
                        </div>
                        <!-- Accordion Item -->
                        <div class="border rounded-lg overflow-hidden">
                            <button class="accordion-button w-full flex justify-between items-center p-5 bg-gray-50 hover:bg-gray-100">
                                <span class="text-xl font-semibold text-brand-dark">คดีแพ่งและอาญา (Civil & Criminal Litigation)</span>
                                <svg class="accordion-arrow w-6 h-6 text-gray-600" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"></path></svg>
                            </button>
                            <div class="accordion-content">
                                <ul class="p-5 pt-0 list-disc list-inside text-gray-700 space-y-2">
                                    <li>การเป็นตัวแทนในศาลทุกชั้นศาล</li>
                                    <li>การไกล่เกลี่ยและระงับข้อพิพาท</li>
                                </ul>
                            </div>
                        </div>
                    </div>
                </div>

                <div id="th-expat" class="tab-content">
                    <div class="max-w-4xl mx-auto space-y-4">
                        <!-- Accordion Item -->
                        <div class="border rounded-lg overflow-hidden">
                            <button class="accordion-button w-full flex justify-between items-center p-5 bg-gray-50 hover:bg-gray-100">
                                <span class="text-xl font-semibold text-brand-dark">วีซ่าและใบอนุญาตทำงาน (Visa & Work Permit)</span>
                                <svg class="accordion-arrow w-6 h-6 text-gray-600" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"></path></svg>
                            </button>
                            <div class="accordion-content">
                                <ul class="p-5 pt-0 list-disc list-inside text-gray-700 space-y-2">
                                    <li>บริการยื่นขอวีซ่าทุกประเภท (ธุรกิจ, เกษียณอายุ, สมรส)</li>
                                    <li>การขอและต่ออายุใบอนุญาตทำงาน</li>
                                </ul>
                            </div>
                        </div>
                        <!-- Accordion Item -->
                        <div class="border rounded-lg overflow-hidden">
                            <button class="accordion-button w-full flex justify-between items-center p-5 bg-gray-50 hover:bg-gray-100">
                                <span class="text-xl font-semibold text-brand-dark">บริการรับรองเอกสาร (Notarial Services)</span>
                                <svg class="accordion-arrow w-6 h-6 text-gray-600" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"></path></svg>
                            </button>
                            <div class="accordion-content">
                                <ul class="p-5 pt-0 list-disc list-inside text-gray-700 space-y-2">
                                    <li>การรับรองลายมือชื่อและเอกสารเพื่อใช้ในต่างประเทศ</li>
                                </ul>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            
            <!-- English Content -->
            <div class="lang-content" data-lang="en">
                <div class="text-center mb-12">
                    <h2 class="text-4xl md:text-5xl font-bold text-gray-900 mb-6">Our Practice Areas</h2>
                    <p class="text-xl text-gray-600 max-w-3xl mx-auto">
                        We provide comprehensive legal counsel for businesses and individuals.
                    </p>
                </div>
                
                <!-- Service Tabs EN -->
                <div class="mb-8 flex justify-center space-x-4 md:space-x-8 border-b border-gray-200">
                    <button class="tab-button text-lg font-semibold text-gray-500 py-4 active" data-tab="en-business">
                        For Business & Investors
                    </button>
                    <button class="tab-button text-lg font-semibold text-gray-500 py-4" data-tab="en-individuals">
                        For Individuals
                    </button>
                    <button class="tab-button text-lg font-semibold text-gray-500 py-4" data-tab="en-expat">
                        Expat & International Services
                    </button>
                </div>

                <!-- Tab Content EN -->
                <div id="en-business" class="tab-content active">
                    <div class="max-w-4xl mx-auto space-y-4">
                        <!-- Accordion Item -->
                        <div class="border rounded-lg overflow-hidden">
                            <button class="accordion-button w-full flex justify-between items-center p-5 bg-gray-50 hover:bg-gray-100">
                                <span class="text-xl font-semibold text-brand-dark">Corporate Law</span>
                                <svg class="accordion-arrow w-6 h-6 text-gray-600" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"></path></svg>
                            </button>
                            <div class="accordion-content">
                                <ul class="p-5 pt-0 list-disc list-inside text-gray-700 space-y-2">
                                    <li>Company, partnership, and all types of juristic person registration</li>
                                    <li>Business license applications (e.g., Foreign Business License)</li>
                                    <li>Mergers & Acquisitions (M&A)</li>
                                    <li>Drafting and reviewing all types of business contracts</li>
                                </ul>
                            </div>
                        </div>
                        <!-- Accordion Item -->
                        <div class="border rounded-lg overflow-hidden">
                            <button class="accordion-button w-full flex justify-between items-center p-5 bg-gray-50 hover:bg-gray-100">
                                <span class="text-xl font-semibold text-brand-dark">Employment Law</span>
                                <svg class="accordion-arrow w-6 h-6 text-gray-600" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"></path></svg>
                            </button>
                            <div class="accordion-content">
                                <ul class="p-5 pt-0 list-disc list-inside text-gray-700 space-y-2">
                                    <li>Drafting employment contracts and work regulations</li>
                                    <li>Consultation on termination and severance pay</li>
                                    <li>Litigation in the Labor Court</li>
                                </ul>
                            </div>
                        </div>
                        <!-- Accordion Item -->
                        <div class="border rounded-lg overflow-hidden">
                            <button class="accordion-button w-full flex justify-between items-center p-5 bg-gray-50 hover:bg-gray-100">
                                <span class="text-xl font-semibold text-brand-dark">Intellectual Property</span>
                                <svg class="accordion-arrow w-6 h-6 text-gray-600" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"></path></svg>
                            </button>
                            <div class="accordion-content">
                                <ul class="p-5 pt-0 list-disc list-inside text-gray-700 space-y-2">
                                    <li>Search and registration of trademarks, patents, and copyrights</li>
                                    <li>Drafting licensing agreements</li>
                                    <li>Protection and enforcement of IP rights</li>
                                </ul>
                            </div>
                        </div>
                        <!-- Accordion Item -->
                        <div class="border rounded-lg overflow-hidden">
                            <button class="accordion-button w-full flex justify-between items-center p-5 bg-gray-50 hover:bg-gray-100">
                                <span class="text-xl font-semibold text-brand-dark">Tax & Accounting</span>
                                <svg class="accordion-arrow w-6 h-6 text-gray-600" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"></path></svg>
                            </button>
                            <div class="accordion-content">
                                <ul class="p-5 pt-0 list-disc list-inside text-gray-700 space-y-2">
                                    <li>Corporate tax planning</li>
                                    <li>International tax advisory</li>
                                    <li>Full-service accounting (with partners)</li>
                                </ul>
                            </div>
                        </div>
                    </div>
                </div>

                <div id="en-individuals" class="tab-content">
                    <div class="max-w-4xl mx-auto space-y-4">
                        <!-- Accordion Item -->
                        <div class="border rounded-lg overflow-hidden">
                            <button class="accordion-button w-full flex justify-between items-center p-5 bg-gray-50 hover:bg-gray-100">
                                <span class="text-xl font-semibold text-brand-dark">Family Law</span>
                                <svg class="accordion-arrow w-6 h-6 text-gray-600" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"></path></svg>
                            </button>
                            <div class="accordion-content">
                                <ul class="p-5 pt-0 list-disc list-inside text-gray-700 space-y-2">
                                    <li>Marriage registration with foreigners</li>
                                    <li>Prenuptial and postnuptial agreements</li>
                                    <li>Divorce proceedings, property and child custody settlements</li>
                                </ul>
                            </div>
                        </div>
                        <!-- Accordion Item -->
                        <div class="border rounded-lg overflow-hidden">
                            <button class="accordion-button w-full flex justify-between items-center p-5 bg-gray-50 hover:bg-gray-100">
                                <span class="text-xl font-semibold text-brand-dark">Inheritance Law</span>
                                <svg class="accordion-arrow w-6 h-6 text-gray-600" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"></path></svg>
                            </button>
                            <div class="accordion-content">
                                <ul class="p-5 pt-0 list-disc list-inside text-gray-700 space-y-2">
                                    <li>Last wills and testaments</li>
                                    <li>Appointment of estate administrator</li>
                                    <li>Inheritance litigation</li>
                                </ul>
                            </div>
                        </div>
                        <!-- Accordion Item -->
                        <div class="border rounded-lg overflow-hidden">
                            <button class="accordion-button w-full flex justify-between items-center p-5 bg-gray-50 hover:bg-gray-100">
                                <span class="text-xl font-semibold text-brand-dark">Real Estate</span>
                                <svg class="accordion-arrow w-6 h-6 text-gray-600" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"></path></svg>
                            </button>
                            <div class="accordion-content">
                                <ul class="p-5 pt-0 list-disc list-inside text-gray-700 space-y-2">
                                    <li>Title deed due diligence before purchase</li>
                                    <li>Advisory on condominium purchase by foreigners</li>
                                    <li>Drafting lease and sale agreements</li>
                                </ul>
                            </div>
                        </div>
                        <!-- Accordion Item -->
                        <div class="border rounded-lg overflow-hidden">
                            <button class="accordion-button w-full flex justify-between items-center p-5 bg-gray-50 hover:bg-gray-100">
                                <span class="text-xl font-semibold text-brand-dark">Civil & Criminal Litigation</span>
                                <svg class="accordion-arrow w-6 h-6 text-gray-600" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"></path></svg>
                            </button>
                            <div class="accordion-content">
                                <ul class="p-5 pt-0 list-disc list-inside text-gray-700 space-y-2">
                                    <li>Representation in all court levels</li>
                                    <li>Mediation and dispute resolution</li>
                                </ul>
                            </div>
                        </div>
                    </div>
                </div>

                <div id="en-expat" class="tab-content">
                    <div class="max-w-4xl mx-auto space-y-4">
                        <!-- Accordion Item -->
                        <div class="border rounded-lg overflow-hidden">
                            <button class="accordion-button w-full flex justify-between items-center p-5 bg-gray-50 hover:bg-gray-100">
                                <span class="text-xl font-semibold text-brand-dark">Visa & Work Permit</span>
                                <svg class="accordion-arrow w-6 h-6 text-gray-600" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"></path></svg>
                            </button>
                            <div class="accordion-content">
                                <ul class="p-5 pt-0 list-disc list-inside text-gray-700 space-y-2">
                                    <li>Applications for all visa types (Business, Retirement, Marriage)</li>
                                    <li>Work permit application and renewal</li>
                                </ul>
                            </div>
                        </div>
                        <!-- Accordion Item -->
                        <div class="border rounded-lg overflow-hidden">
                            <button class="accordion-button w-full flex justify-between items-center p-5 bg-gray-50 hover:bg-gray-100">
                                <span class="text-xl font-semibold text-brand-dark">Notarial Services</span>
                                <svg class="accordion-arrow w-6 h-6 text-gray-600" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"></path></svg>
                            </button>
                            <div class="accordion-content">
                                <ul class="p-5 pt-0 list-disc list-inside text-gray-700 space-y-2">
                                    <li>Certification of signatures and documents for international use</li>
                                </ul>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Expertise Section -->
    <section id="expertise" class="py-20 bg-gray-50">
        <div class=“px-4 sm:px-6 lg:px-8”>
            <!-- Thai Content -->
            <div class="lang-content active" data-lang="th">
                <div class="text-center mb-16">
                    <h2 class="text-4xl md:text-5xl font-bold text-gray-900 mb-6">ความเชี่ยวชาญของเรา</h2>
                    <p class="text-xl text-gray-600 max-w-3xl mx-auto">
                        ด้วยประสบการณ์กว่า 40 ปี เราได้สั่งสมความเชี่ยวชาญในหลากหลายสาขา
                        พร้อมให้บริการที่ตอบโจทย์ทุกความต้องการของลูกค้า
                    </p>
                </div>
                
                <!-- Updated Grid for 8 items -->
                <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-8">
                    <!-- กฎหมายธุรกิจ -->
                    <div class="expertise-item bg-white p-6 rounded-xl shadow-md text-center">
                        <div class="w-16 h-16 bg-brand-accent bg-opacity-10 rounded-lg flex items-center justify-center mx-auto mb-4">
                            <svg fill="#b89f77" viewBox="0 0 50 50" xmlns="http://www.w3.org/2000/svg">
      <path d="M8 2L8 6L4 6L4 48L46 48L46 14L30 14L30 6L26 6L26 2 Z M 10 4L24 4L24 8L28 8L28 46L19 46L19 39L15 39L15 46L6 46L6 8L10 8 Z M 10 10L10 12L12 12L12 10 Z M 14 10L14 12L16 12L16 10 Z M 18 10L18 12L20 12L20 10 Z M 22 10L22 12L24 12L24 10 Z M 10 15L10 19L12 19L12 15 Z M 14 15L14 19L16 19L16 15 Z M 18 15L18 19L20 19L20 15 Z M 22 15L22 19L24 19L24 15 Z M 30 16L44 16L44 46L30 46 Z M 32 18L32 20L34 20L34 18 Z M 36 18L36 20L38 20L38 18 Z M 40 18L40 20L42 20L42 18 Z M 10 21L10 25L12 25L12 21 Z M 14 21L14 25L16 25L16 21 Z M 18 21L18 25L20 25L20 21 Z M 22 21L22 25L24 25L24 21 Z M 32 22L32 24L34 24L34 22 Z M 36 22L36 24L38 24L38 22 Z M 40 22L40 24L42 24L42 22 Z M 32 26L32 28L34 28L34 26 Z M 36 26L36 28L38 28L38 26 Z M 40 26L40 28L42 28L42 26 Z M 10 27L10 31L12 31L12 27 Z M 14 27L14 31L16 31L16 27 Z M 18 27L18 31L20 31L20 27 Z M 22 27L22 31L24 31L24 27 Z M 32 30L32 32L34 32L34 30 Z M 36 30L36 32L38 32L38 30 Z M 40 30L40 32L42 32L42 30 Z M 10 33L10 37L12 37L12 33 Z M 14 33L14 37L16 37L16 33 Z M 18 33L18 37L20 37L20 33 Z M 22 33L22 37L24 37L24 33 Z M 32 34L32 36L34 36L34 34 Z M 36 34L36 36L38 36L38 34 Z M 40 34L40 36L42 36L42 34 Z M 32 38L32 40L34 40L34 38 Z M 36 38L36 40L38 40L38 38 Z M 40 38L40 40L42 40L42 38 Z M 10 39L10 44L12 44L12 39 Z M 22 39L22 44L24 44L24 39 Z M 32 42L32"/></svg>
                        </div>
                        <h3 class="text-xl font-bold text-gray-900 mb-2">กฎหมายธุรกิจ</h3>
                        <p class="text-gray-600 text-sm">จัดตั้งบริษัท ควบรวมกิจการ</p>
                    </div>
                    <!-- กฎหมายสัญญา -->
                    <div class="expertise-item bg-white p-6 rounded-xl shadow-md text-center">
                        <div class="w-16 h-16 bg-brand-accent bg-opacity-10 rounded-lg flex items-center justify-center mx-auto mb-4">
                            <svg width="800px" height="800px" viewBox="0 0 1024 1024" fill="#b89f77" class="icon" version="1.1" xmlns="http://www.w3.org/2000/svg" stroke="#b89f77" stroke-width="11.264">

<g id="SVGRepo_bgCarrier" stroke-width="0"/>

<g id="SVGRepo_tracerCarrier" stroke-linecap="round" stroke-linejoin="round"/>

<g id="SVGRepo_iconCarrier">

<path d="M695.986 847.98H472c-4.422 0-8-3.578-8-8s3.578-8 8-8h223.988c4.42 0 7.998 3.578 7.998 8s-3.58 8-8 8z" fill=""/>

<path d="M599.992 863.978c-0.782 0-1.562-0.11-2.312-0.344a7.992 7.992 0 0 1-5.688-7.656v-29.232c-12.61 10.812-31.498 23.516-47.684 20.86-4.704-0.782-10.5-3.078-15.422-8.984a650.89 650.89 0 0 1-18.86 22.608 7.962 7.962 0 0 1-11.28 0.782 7.986 7.986 0 0 1-0.782-11.28 587.472 587.472 0 0 0 23.046-28.266c-5.876-21.138 0.82-39.778 10.078-48.622 7-6.688 15.734-8.61 23.904-5.266 3.688 1.484 6.25 4.468 7.188 8.39 2.344 9.89-9.016 29.17-23.06 48.292 3 5.688 6.406 6.312 7.656 6.532 14.544 2.734 41.2-21.998 47.028-28.874 2.156-2.562 5.782-3.546 8.906-2.39 3.14 1.156 5.282 4.094 5.282 7.454v21.576l17.342-26.014a8.02 8.02 0 0 1 6.656-3.562h31.998c4.422 0 8 3.578 8 8a7.994 7.994 0 0 1-8 7.998h-27.718l-29.622 44.436a7.984 7.984 0 0 1-6.656 3.562z m-53.87-80.884c-1.094 0.218-2.438 0.86-3.968 2.328-3.688 3.498-6.5 9.904-7.156 17.654 5.732-8.546 9.81-15.67 11.124-19.982zM935.97 927.974a7.97 7.97 0 0 1-6.654-3.562l-32-47.998a7.974 7.974 0 0 1-0.938-6.966l15.594-46.764v-14.702c0-4.422 3.578-8 8-8s8 3.578 8 8v15.998c0 0.86-0.14 1.718-0.406 2.532l-14.766 44.28 29.826 44.748a7.988 7.988 0 0 1-2.218 11.092 8.018 8.018 0 0 1-4.438 1.342z" fill=""/>

<path d="M935.97 927.974a8.014 8.014 0 0 1-4.436-1.344 7.986 7.986 0 0 1-2.218-11.092l29.824-44.748-14.764-44.28a8.16 8.16 0 0 1-0.406-2.532v-15.998c0-4.422 3.578-8 8-8a7.994 7.994 0 0 1 7.998 8v14.702l15.594 46.764a7.968 7.968 0 0 1-0.938 6.966l-31.998 47.998a7.97 7.97 0 0 1-6.656 3.564zM967.968 687.988h-63.996c-4.422 0-8-3.578-8-7.998 0-4.422 3.578-8 8-8h63.996c4.422 0 8 3.578 8 8a7.994 7.994 0 0 1-8 7.998z" fill=""/>

<path d="M903.972 687.988a8.016 8.016 0 0 1-8-7.686l-15.998-399.976a8.02 8.02 0 0 1 7.688-8.312c4.31-0.25 8.124 3.266 8.31 7.686l16 399.976a8.02 8.02 0 0 1-7.688 8.31l-0.312 0.002zM967.968 687.988h-0.312a8.02 8.02 0 0 1-7.688-8.31l16-399.976c0.188-4.42 3.812-7.92 8.312-7.686a8.02 8.02 0 0 1 7.688 8.312l-16 399.976a8.012 8.012 0 0 1-8 7.684z" fill=""/>

<path d="M983.968 288.014c-4.422 0-8-3.578-8-8 0-37.154-13.468-55.996-39.998-55.996s-39.998 18.842-39.998 55.996c0 4.422-3.578 8-7.998 8-4.422 0-8-3.578-8-8 0-45.746 20.404-71.996 55.996-71.996s55.998 26.25 55.998 71.996c0 4.422-3.578 8-8 8z" fill=""/>

<path d="M951.97 224.018h-31.998c-4.422 0-8-3.578-8-8 0-4.42 3.578-8 8-8h31.998a7.994 7.994 0 0 1 7.998 8c0 4.422-3.578 8-7.998 8zM935.97 496a7.994 7.994 0 0 1-7.998-8V248.016c0-4.42 3.578-8 7.998-8 4.422 0 8 3.578 8 8v239.986a7.994 7.994 0 0 1-8 7.998zM967.968 719.988h-63.996c-4.422 0-8-3.578-8-8s3.578-8 8-8h63.996c4.422 0 8 3.578 8 8s-3.578 8-8 8z" fill=""/>

<path d="M967.968 719.988c-4.422 0-8-3.578-8-8v-31.998c0-4.422 3.578-8 8-8s8 3.578 8 8v31.998c0 4.422-3.578 8-8 8zM903.972 719.988c-4.422 0-8-3.578-8-8v-31.998c0-4.422 3.578-8 8-8s8 3.578 8 8v31.998c0 4.422-3.578 8-8 8zM967.968 815.98h-63.996c-4.422 0-8-3.578-8-7.998 0-4.422 3.578-8 8-8h63.996c4.422 0 8 3.578 8 8a7.994 7.994 0 0 1-8 7.998z" fill=""/>

<path d="M967.968 815.98c-4.422 0-8-3.578-8-7.998v-95.994c0-4.422 3.578-8 8-8s8 3.578 8 8v95.994a7.994 7.994 0 0 1-8 7.998zM903.972 815.98c-4.422 0-8-3.578-8-7.998v-95.994c0-4.422 3.578-8 8-8s8 3.578 8 8v95.994a7.994 7.994 0 0 1-8 7.998zM791.98 959.972c-4.422 0-8-3.578-8-8V104.026c0-4.422 3.578-8 8-8s8 3.578 8 8v847.948a7.994 7.994 0 0 1-8 7.998z" fill=""/>

<path d="M791.98 959.972H104.02c-4.42 0-8-3.578-8-8s3.578-8 8-8h687.96c4.422 0 8 3.578 8 8s-3.578 8-8 8z" fill=""/>

<path d="M104.02 959.972c-4.42 0-8-3.578-8-8V8.032c0-4.422 3.578-8 8-8 4.422 0 8 3.578 8 8v943.942a7.994 7.994 0 0 1-8 7.998z" fill=""/>

<path d="M695.986 16.03H104.02c-4.42 0-8-3.578-8-8 0-4.422 3.578-8 8-8h591.966a7.994 7.994 0 0 1 7.998 8c0 4.422-3.578 8-7.998 8z" fill=""/>

<path d="M791.98 112.024a7.976 7.976 0 0 1-5.656-2.344L690.33 13.686a8 8 0 0 1 11.31-11.312l95.996 95.994a8 8 0 0 1-5.656 13.656zM679.986 128.024a7.994 7.994 0 0 1-7.998-8V40.03c0-4.422 3.578-8 7.998-8 4.422 0 8 3.578 8 8v79.994c0 4.422-3.578 8-8 8z" fill=""/>

<path d="M759.982 128.024h-79.996a7.994 7.994 0 0 1-7.998-8c0-4.42 3.578-8 7.998-8h79.996a7.994 7.994 0 0 1 7.998 8c0 4.422-3.578 8-7.998 8zM695.986 432.004H200.014c-4.42 0-8-3.578-8-8 0-4.422 3.578-8 8-8h495.972a7.994 7.994 0 0 1 7.998 8c0 4.422-3.578 8-7.998 8zM695.986 496H200.014c-4.42 0-8-3.578-8-8 0-4.422 3.578-8 8-8h495.972a7.994 7.994 0 0 1 7.998 8c0 4.422-3.578 8-7.998 8z" fill=""/>

<path d="M695.986 559.996H200.014c-4.42 0-8-3.578-8-7.998 0-4.422 3.578-8 8-8h495.972a7.994 7.994 0 0 1 7.998 8 7.994 7.994 0 0 1-7.998 7.998z" fill=""/>

<path d="M695.986 623.992H200.014c-4.42 0-8-3.578-8-7.998 0-4.422 3.578-8 8-8h495.972a7.994 7.994 0 0 1 7.998 8 7.994 7.994 0 0 1-7.998 7.998z" fill=""/>

<path d="M456 687.988H200.014c-4.42 0-8-3.578-8-7.998 0-4.422 3.578-8 8-8H456c4.422 0 8 3.578 8 8 0 4.42-3.58 7.998-8 7.998z" fill=""/>

<path d="M288.01 320.012c-52.934 0-95.994-43.06-95.994-95.994s43.06-95.994 95.994-95.994 95.994 43.06 95.994 95.994-43.06 95.994-95.994 95.994z m0-175.99c-44.106 0-79.996 35.888-79.996 79.996s35.888 79.996 79.996 79.996 79.996-35.888 79.996-79.996-35.89-79.996-79.996-79.996z" fill=""/>

<path d="M264.01 288.014a8 8 0 0 1-5.656-13.656l55.998-55.998a8 8 0 0 1 11.31 11.312l-55.996 55.996a7.966 7.966 0 0 1-5.656 2.346z" fill=""/>

<path d="M344.006 256.016a7.976 7.976 0 0 1-5.656-2.344l-23.998-23.998a8 8 0 0 1 11.31-11.312l24 24a8 8 0 0 1-5.656 13.654z" fill=""/>

<path d="M232.012 256.016a8 8 0 0 1-5.656-13.656l16-16a8 8 0 1 1 11.312 11.312l-16 16a7.974 7.974 0 0 1-5.656 2.344z" fill=""/>

<path d="M264.01 256.016a7.98 7.98 0 0 1-5.656-2.344l-16-16a8 8 0 1 1 11.312-11.312l16 16a8 8 0 0 1-5.656 13.656z" fill=""/>

<path d="M264.01 208.018c-13.232 0-23.998-10.764-23.998-24 0-13.232 10.766-23.998 23.998-23.998 13.234 0 24 10.766 24 23.998 0 13.236-10.764 24-24 24z m0-31.998c-4.414 0-8 3.594-8 8 0 4.406 3.586 8 8 8s8-3.594 8-8c0-4.406-3.586-8-8-8z" fill=""/>

<path d="M72.022 991.97c-4.42 0-8-3.578-8-8V40.03c0-4.422 3.578-8 8-8 4.422 0 8 3.578 8 8v943.942a7.994 7.994 0 0 1-8 7.998z" fill=""/>

<path d="M759.982 991.97H72.022c-4.42 0-8-3.578-8-8a7.994 7.994 0 0 1 8-7.998h687.96a7.994 7.994 0 0 1 7.998 7.998c0 4.422-3.578 8-7.998 8z" fill=""/>

<path d="M727.984 1023.968H40.024c-4.42 0-8-3.578-8-8s3.578-8 8-8h687.96c4.422 0 8 3.578 8 8s-3.578 8-8 8z" fill=""/>

<path d="M40.024 1023.968c-4.42 0-8-3.578-8-8V72.028c0-4.422 3.578-8 8-8 4.422 0 8 3.578 8 8v943.942a7.994 7.994 0 0 1-8 7.998z" fill=""/>

</g>/></svg>
                        </div>
                        <h3 class="text-xl font-bold text-gray-900 mb-2">กฎหมายสัญญา</h3>
                        <p class="text-gray-600 text-sm">ร่าง ตรวจสอบ เจรจาสัญญา</p>
                    </div>
                    <!-- กฎหมายการลงทุน -->
                    <div class="expertise-item bg-white p-6 rounded-xl shadow-md text-center">
                        <div class="w-16 h-16 bg-brand-accent bg-opacity-10 rounded-lg flex items-center justify-center mx-auto mb-4">
                            <svg fill="#b89f77" version="1.1" id="Layer_1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" viewBox="0 0 490 490" xml:space="preserve" width="800px" height="800px">

<g id="SVGRepo_bgCarrier" stroke-width="0"/>

<g id="SVGRepo_tracerCarrier" stroke-linecap="round" stroke-linejoin="round"/>

<g id="SVGRepo_iconCarrier"> <g> <g> <g> <path d="M439.976,110c-0.001-2.602-0.992-5.159-2.904-7.071l-100-100c-1.912-1.912-4.47-2.903-7.071-2.904V0H60 c-5.523,0-10,4.477-10,10v470c0,5.523,4.477,10,10,10h370c5.522,0,10-4.477,10-10V110H439.976z M340,34.142L405.857,100H340 V34.142z M420,470H70V20h250v90c0,5.523,4.478,10,10,10h90V470z"/> <path d="M379.447,339.49c-7.657-12.376-20.975-19.475-36.535-19.475c-7.511,0-15.198,1.64-22.912,4.882 c-7.714-3.242-15.401-4.882-22.912-4.882c-15.56,0-28.875,7.099-36.533,19.476c-8.036,12.989-8.541,29.684-1.551,46.403 c-6.992,16.688-6.49,33.368,1.542,46.364c7.666,12.403,20.998,19.516,36.577,19.515c7.501,0,15.178-1.637,22.877-4.872 c7.7,3.235,15.375,4.872,22.874,4.872c0.001,0,0.003,0,0.004,0c15.579-0.001,28.911-7.116,36.576-19.52 c8.031-12.996,8.533-29.673,1.542-46.358C387.988,369.172,387.483,352.478,379.447,339.49z M362.441,421.739 c-3.998,6.469-10.946,10.033-19.564,10.034c-5.817,0-12.01-1.621-18.404-4.818c-1.407-0.704-2.94-1.056-4.472-1.056 s-3.065,0.352-4.472,1.056c-6.393,3.196-12.586,4.817-18.406,4.818c-8.618,0-15.566-3.562-19.564-10.03 c-5.023-8.128-4.519-19.563,1.386-31.372c1.406-2.812,1.407-6.122,0.005-8.935c-5.908-11.846-6.413-23.298-1.387-31.422 c3.989-6.448,10.924-9.999,19.525-9.999c5.829,0,12.033,1.625,18.44,4.828c2.815,1.407,6.129,1.407,8.943,0 c6.407-3.204,12.611-4.828,18.44-4.828c8.603,0,15.538,3.551,19.527,9.998c5.026,8.123,4.52,19.576-1.389,31.423 c-1.401,2.813-1.4,6.123,0.007,8.935C366.959,402.177,367.464,413.61,362.441,421.739z"/> <rect x="310" y="360.898" width="20" height="20"/> <rect x="300" y="390.898" width="40" height="20"/> <rect x="95" y="395" width="120" height="20"/> <rect x="195" y="430" width="20" height="20"/> <rect x="165" y="430" width="20" height="20"/> <rect x="95" y="430" width="20" height="20"/> <rect x="95" y="40" width="60" height="20"/> <rect x="95" y="70" width="120" height="20"/> <rect x="165" y="150" width="160" height="20"/> <rect x="95" y="190" width="300" height="20"/> <rect x="95" y="230" width="300" height="20"/> <rect x="95" y="270" width="240" height="20"/> <rect x="375" y="270" width="20" height="20"/> <rect x="345" y="270" width="20" height="20"/> </g> </g> </g> </g> /></svg>
                        </div>
                        <h3 class="text-xl font-bold text-gray-900 mb-2">กฎหมายการลงทุน</h3>
                        <p class="text-gray-600 text-sm">สำนักงานคณะกรรมการส่งเสริมการลงทุน (BOI), ใบอนุญาตประกอบธุรกิจของคนต่างด้าว (FBL)</p>
                    </div>
                    <!-- กฎหมายครอบครัวและมรดก -->
                    <div class="expertise-item bg-white p-6 rounded-xl shadow-md text-center">
                        <div class="w-16 h-16 bg-brand-accent bg-opacity-10 rounded-lg flex items-center justify-center mx-auto mb-4">
                            <svg class="w-20 h-20 text-brand-accent" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" d="M15 19.128a9.38 9.38 0 002.625.372 9.337 9.337 0 004.121-.952 4.125 4.125 0 00-7.533-2.493M15 19.128v-.003c0-1.113-.285-2.16-.786-3.07M15 19.128v.106A12.318 12.318 0 018.624 21c-2.331 0-4.512-.645-6.374-1.766l-.001-.109a6.375 6.375 0 0111.964-3.07M12 6.375a3.375 3.375 0 11-6.75 0 3.375 3.375 0 016.75 0zm8.25 2.25a2.625 2.625 0 11-5.25 0 2.625 2.625 0 015.25 0z" /></svg>
                        </div>
                        <h3 class="text-xl font-bold text-gray-900 mb-2">กฎหมายครอบครัวและมรดก</h3>
                        <p class="text-gray-600 text-sm">สมรส หย่าร้าง พินัยกรรม</p>
                    </div>
                    <!-- กฎหมาย PDPA -->
                    <div class="expertise-item bg-white p-6 rounded-xl shadow-md text-center">
                        <div class="w-16 h-16 bg-brand-accent bg-opacity-10 rounded-lg flex items-center justify-center mx-auto mb-4">
                           <svg class="w-8 h-8 text-brand-accent" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" d="M9 12.75L11.25 15 15 9.75m-3-7.036A11.959 11.959 0 013.598 6 11.99 11.99 0 003 9.749c0 5.592 3.824 10.29 9 11.623 5.176-1.333 9-6.031 9-11.623 0-1.601-.39-3.135-1.12-4.494M15 9a3 3 0 11-6 0 3 3 0 016 0z" /></svg>
                        </div>
                        <h3 class="text-xl font-bold text-gray-900 mb-2">กฎหมาย PDPA</h3>
                        <p class="text-gray-600 text-sm">คุ้มครองข้อมูลส่วนบุคคล</p>
                    </div>
                     <!-- กฎหมายอสังหาริมทรัพย์ -->
                    <div class="expertise-item bg-white p-6 rounded-xl shadow-md text-center">
                        <div class="w-16 h-16 bg-brand-accent bg-opacity-10 rounded-lg flex items-center justify-center mx-auto mb-4">
                            <svg class="w-20 h-20 text-brand-accent" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" d="M8.25 21v-4.875c0-.621.504-1.125 1.125-1.125h2.25c.621 0 1.125.504 1.125 1.125V21m0 0h4.5V3.545M12.75 21h7.5V10.75M2.25 21h1.5m18 0h-18M2.25 9l4.5-1.636M18.75 3l-1.5.545m0 6.205l3 1m1.5.5l-1.5-.5M6.75 7.364V3h-3v18m3-13.636l10.5-3.819" /></svg>
                        </div>
                        <h3 class="text-xl font-bold text-gray-900 mb-2">กฎหมายอสังหาริมทรัพย์</h3>
                        <p class="text-gray-600 text-sm">ซื้อขาย เช่า โอนกรรมสิทธิ์</p>
                    </div>
                     <!-- กฎหมายแรงงาน -->
                    <div class="expertise-item bg-white p-6 rounded-xl shadow-md text-center">
                        <div class="w-16 h-16 bg-brand-accent bg-opacity-10 rounded-lg flex items-center justify-center mx-auto mb-4">
                            <svg class="w-20 h-20 text-brand-accent" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" d="M18 18.72a9.094 9.094 0 003.741-.479 3 3 0 00-4.682-2.72m.94 3.198l.001.031c0 .225-.012.447-.037.666A11.944 11.944 0 0112 21c-2.17 0-4.207-.576-5.963-1.584A6.062 6.062 0 016 18.719m12 0a5.971 5.971 0 00-.941-3.197m0 0A5.995 5.995 0 0012 12.75a5.995 5.995 0 00-5.058 2.772m0 0a3 3 0 00-4.681 2.72 8.986 8.986 0 003.74.477m.94-3.197a5.971 5.971 0 00-.94 3.197M15 6.75a3 3 0 11-6 0 3 3 0 016 0zm6 3a2.25 2.25 0 11-4.5 0 2.25 2.25 0 014.5 0zm-13.5 0a2.25 2.25 0 11-4.5 0 2.25 2.25 0 014.5 0z" /></svg>
                        </div>
                        <h3 class="text-xl font-bold text-gray-900 mb-2">กฎหมายแรงงาน</h3>
                        <p class="text-gray-600 text-sm">สัญญาจ้าง ข้อพิพาทแรงงาน</p>
                    </div>
                    <!-- กฎหมายระหว่างประเทศ -->
                    <div class="expertise-item bg-white p-6 rounded-xl shadow-md text-center">
                        <div class="w-16 h-16 bg-brand-accent bg-opacity-10 rounded-lg flex items-center justify-center mx-auto mb-4">
                            <svg class="w-8 h-8 text-brand-accent" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" d="M12 21a9.004 9.004 0 008.716-6.747M12 21a9.004 9.004 0 01-8.716-6.747M12 21c.506 0 1.027-.035 1.544-.102M12 21c-.506 0-1.027-.035-1.544-.102M12 3a9.004 9.004 0 00-8.716 6.747M12 3a9.004 9.004 0 018.716 6.747M12 3c.506 0 1.027.035 1.544.102M12 3c-.506 0-1.027.035-1.544-.102M4.606 15.897A9.003 9.003 0 0112 15c1.604 0 3.11.42 4.394 1.153M15.394 8.103A9.003 9.003 0 0112 9c-1.604 0-3.11-.42-4.394-1.153" /></svg>
                        </div>
                        <h3 class="text-xl font-bold text-gray-900 mb-2">กฎหมายระหว่างประเทศ</h3>
                        <p class="text-gray-600 text-sm">การค้า การลงทุนข้ามชาติ</p>
                    </div>

                </div>
            </div>
            
            <!-- English Content -->
            <div class="lang-content" data-lang="en">
                <div class="text-center mb-16">
                    <h2 class="text-4xl md:text-5xl font-bold text-gray-900 mb-6">Our Expertise</h2>
                    <p class="text-xl text-gray-600 max-w-3xl mx-auto">
                        With over 15 years of experience, we have accumulated expertise in various fields, 
                        ready to provide services that meet all client needs.
                    </p>
                </div>
                
                 <!-- Updated Grid for 8 items -->
                 <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-8">
                     <!-- Business Law -->
                    <div class="expertise-item bg-white p-6 rounded-xl shadow-md text-center">
                        <div class="w-16 h-16 bg-brand-accent bg-opacity-10 rounded-lg flex items-center justify-center mx-auto mb-4">
                            <svg class="w-8 h-8 text-brand-accent" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor"> <path stroke-linecap="round" stroke-linejoin="round" d="M20.25 14.15v4.075c0 1.313-.811 2.38-1.875 2.38s-1.875-1.067-1.875-2.38V14.15M18 18.375l-7.5-7.5-7.5 7.5m15 0v-4.075c0-1.313-.811-2.38-1.875-2.38s-1.875 1.067-1.875 2.38v4.075M3 18.375l7.5-7.5 7.5 7.5m-15 0v-4.075c0-1.313.811-2.38 1.875-2.38s1.875 1.067 1.875 2.38v4.075m15.001-4.874c-.381.026-.76.052-1.137.052c-1.176 0-2.322-.099-3.435-.297c-1.113-.198-2.16-.47-3.132-.816c-1.144-.401-2.188-.9-3.132-1.465c-.381-.226-.728-.464-1.04-.711c-1.023-.797-1.725-1.842-2.022-3.018c-.224-.863-.224-1.76.002-2.613c.227-.852.646-1.649 1.226-2.33c.58-.68 1.28-1.258 2.05-1.733c.77-.473 1.62-.84 2.53-1.066c.907-.225 1.848-.348 2.823-.348c.975 0 1.916.123 2.823.348c.91.226 1.76.593 2.53 1.066c.77.475 1.47.1.053 2.05 1.733c.58.681.999 1.478 1.226 2.33c.226.853.226 1.75.002 2.613c-.297 1.176-1 2.221-2.022 3.018c-.312.247-.659.485-1.04.711c-.944.565-1.988 1.064-3.132 1.465c-1.09.382-2.223.673-3.435.816c-.377.026-.756.052-1.137.052" /></svg>
                        </div>
                        <h3 class="text-xl font-bold text-gray-900 mb-2">Business Law</h3>
                        <p class="text-gray-600 text-sm">Company formation, M&A</p>
                    </div>
                    <!-- Contract Law -->
                    <div class="expertise-item bg-white p-6 rounded-xl shadow-md text-center">
                        <div class="w-16 h-16 bg-brand-accent bg-opacity-10 rounded-lg flex items-center justify-center mx-auto mb-4">
                            <svg class="w-8 h-8 text-brand-accent" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" d="M19.5 14.25v-2.625a3.375 3.375 0 00-3.375-3.375h-1.5A1.125 1.125 0 0113.5 7.125v-1.5a3.375 3.375 0 00-3.375-3.375H8.25m0 12.75h7.5m-7.5 3H12M10.5 2.25H5.625c-.621 0-1.125.504-1.125 1.125v17.25c0 .621.504 1.125 1.125 1.125h12.75c.621 0 1.125-.504 1.125-1.125V11.25a9 9 0 00-9-9z" /></svg>
                        </div>
                        <h3 class="text-xl font-bold text-gray-900 mb-2">Contract Law</h3>
                        <p class="text-gray-600 text-sm">Drafting, review, negotiation</p>
                    </div>
                    <!-- Investment Law -->
                    <div class="expertise-item bg-white p-6 rounded-xl shadow-md text-center">
                        <div class="w-16 h-16 bg-brand-accent bg-opacity-10 rounded-lg flex items-center justify-center mx-auto mb-4">
                            <svg class="w-8 h-8 text-brand-accent" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" d="M2.25 18.75a60.07 60.07 0 0115.797 2.101c.727.198 1.453-.342 1.453-1.096V18.75M3.75 4.5v.75A.75.75 0 013 6h-.75m0 0v-.375c0-.621.504-1.125 1.125-1.125H20.25M2.25 6v9m18-10.5v.75c0 .414.336.75.75.75h.75m-1.5-1.5h.375c.621 0 1.125.504 1.125 1.125v16.5c0 .621-.504 1.125-1.125 1.125h-16.5c-.621 0-1.125-.504-1.125-1.125V6.75A.75.75 0 013.75 6h.75M12 12.75a.75.75 0 110-1.5.75.75 0 010 1.5zm12-1.5a.75.75 0 110-1.5.75.75 0 010 1.5zm-12 3a.75.75 0 110-1.5.75.75 0 010 1.5zm12-1.5a.75.75 0 110-1.5.75.75 0 010 1.5zm-12 3a.75.75 0 110-1.5.75.75 0 010 1.5zm12-1.5a.75.75 0 110-1.5.75.75 0 010 1.5z" /></svg>
                        </div>
                        <h3 class="text-xl font-bold text-gray-900 mb-2">Investment Law</h3>
                        <p class="text-gray-600 text-sm">BOI, FBl</p>
                    </div>
                    <!-- Family & Inheritance Law -->
                    <div class="expertise-item bg-white p-6 rounded-xl shadow-md text-center">
                        <div class="w-16 h-16 bg-brand-accent bg-opacity-10 rounded-lg flex items-center justify-center mx-auto mb-4">
                            <svg class="w-8 h-8 text-brand-accent" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" d="M15 19.128a9.38 9.38 0 002.625.372 9.337 9.337 0 004.121-.952 4.125 4.125 0 00-7.533-2.493M15 19.128v-.003c0-1.113-.285-2.16-.786-3.07M15 19.128v.106A12.318 12.318 0 018.624 21c-2.331 0-4.512-.645-6.374-1.766l-.001-.109a6.375 6.375 0 0111.964-3.07M12 6.375a3.375 3.375 0 11-6.75 0 3.375 3.375 0 016.75 0zm8.25 2.25a2.625 2.625 0 11-5.25 0 2.625 2.625 0 015.25 0z" /></svg>
                        </div>
                        <h3 class="text-xl font-bold text-gray-900 mb-2">Family & Inheritance</h3>
                        <p class="text-gray-600 text-sm">Marriage, divorce, wills</p>
                    </div>
                     <!-- PDPA Law -->
                    <div class="expertise-item bg-white p-6 rounded-xl shadow-md text-center">
                        <div class="w-16 h-16 bg-brand-accent bg-opacity-10 rounded-lg flex items-center justify-center mx-auto mb-4">
                           <svg class="w-8 h-8 text-brand-accent" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" d="M9 12.75L11.25 15 15 9.75m-3-7.036A11.959 11.959 0 013.598 6 11.99 11.99 0 003 9.749c0 5.592 3.824 10.29 9 11.623 5.176-1.333 9-6.031 9-11.623 0-1.601-.39-3.135-1.12-4.494M15 9a3 3 0 11-6 0 3 3 0 016 0z" /></svg>
                        </div>
                        <h3 class="text-xl font-bold text-gray-900 mb-2">PDPA Law</h3>
                        <p class="text-gray-600 text-sm">Data privacy compliance</p>
                    </div>
                    <!-- Real Estate Law -->
                    <div class="expertise-item bg-white p-6 rounded-xl shadow-md text-center">
                        <div class="w-16 h-16 bg-brand-accent bg-opacity-10 rounded-lg flex items-center justify-center mx-auto mb-4">
                            <svg class="w-8 h-8 text-brand-accent" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" d="M8.25 21v-4.875c0-.621.504-1.125 1.125-1.125h2.25c.621 0 1.125.504 1.125 1.125V21m0 0h4.5V3.545M12.75 21h7.5V10.75M2.25 21h1.5m18 0h-18M2.25 9l4.5-1.636M18.75 3l-1.5.545m0 6.205l3 1m1.5.5l-1.5-.5M6.75 7.364V3h-3v18m3-13.636l10.5-3.819" /></svg>
                        </div>
                        <h3 class="text-xl font-bold text-gray-900 mb-2">Real Estate Law</h3>
                        <p class="text-gray-600 text-sm">Sale, lease, title transfer</p>
                    </div>
                     <!-- Employment Law -->
                    <div class="expertise-item bg-white p-6 rounded-xl shadow-md text-center">
                        <div class="w-16 h-16 bg-brand-accent bg-opacity-10 rounded-lg flex items-center justify-center mx-auto mb-4">
                            <svg class="w-8 h-8 text-brand-accent" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" d="M18 18.72a9.094 9.094 0 003.741-.479 3 3 0 00-4.682-2.72m.94 3.198l.001.031c0 .225-.012.447-.037.666A11.944 11.944 0 0112 21c-2.17 0-4.207-.576-5.963-1.584A6.062 6.062 0 016 18.719m12 0a5.971 5.971 0 00-.941-3.197m0 0A5.995 5.995 0 0012 12.75a5.995 5.995 0 00-5.058 2.772m0 0a3 3 0 00-4.681 2.72 8.986 8.986 0 003.74.477m.94-3.197a5.971 5.971 0 00-.94 3.197M15 6.75a3 3 0 11-6 0 3 3 0 016 0zm6 3a2.25 2.25 0 11-4.5 0 2.25 2.25 0 014.5 0zm-13.5 0a2.25 2.25 0 11-4.5 0 2.25 2.25 0 014.5 0z" /></svg>
                        </div>
                        <h3 class="text-xl font-bold text-gray-900 mb-2">Employment Law</h3>
                        <p class="text-gray-600 text-sm">Contracts, labor disputes</p>
                    </div>
                    <!-- International Law -->
                    <div class="expertise-item bg-white p-6 rounded-xl shadow-md text-center">
                        <div class="w-16 h-16 bg-brand-accent bg-opacity-10 rounded-lg flex items-center justify-center mx-auto mb-4">
                            <svg class="w-8 h-8 text-brand-accent" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" d="M12 21a9.004 9.004 0 008.716-6.747M12 21a9.004 9.004 0 01-8.716-6.747M12 21c.506 0 1.027-.035 1.544-.102M12 21c-.506 0-1.027-.035-1.544-.102M12 3a9.004 9.004 0 00-8.716 6.747M12 3a9.004 9.004 0 018.716 6.747M12 3c.506 0 1.027.035 1.544.102M12 3c-.506 0-1.027.035-1.544-.102M4.606 15.897A9.003 9.003 0 0112 15c1.604 0 3.11.42 4.394 1.153M15.394 8.103A9.003 9.003 0 0112 9c-1.604 0-3.11-.42-4.394-1.153" /></svg>
                        </div>
                        <h3 class="text-xl font-bold text-gray-900 mb-2">International Law</h3>
                        <p class="text-gray-600 text-sm">Trade, cross-border investment</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Team Section -->
    <section id="team" class="py-20 bg-white">
        <div class=“px-4 sm:px-6 lg:px-8”>
            <!-- Thai Content -->
            <div class="lang-content active" data-lang="th">
                <div class="text-center mb-16">
                    <h2 class="text-4xl md:text-5xl font-bold text-gray-900 mb-6">ทีมผู้เชี่ยวชาญ</h2>
                    <p class="text-xl text-gray-600 max-w-3xl mx-auto">
                        ทีมทนายความและที่ปรึกษามืออาชีพ พร้อมให้บริการด้วยความเชี่ยวชาญและประสบการณ์สูง
                    </p>
                </div>
                
                <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-8">
                    <!-- Updated team card style -->
                    <div class="bg-white p-6 rounded-xl shadow-md text-center border border-gray-100 hover:shadow-xl transition-shadow">
                        <div class="w-24 h-24 bg-brand-dark-secondary rounded-full mx-auto mb-4 flex items-center justify-center text-white text-3xl font-bold">
                            ดร.ส
                        </div>
                        <h3 class="text-xl font-bold text-gray-900 mb-1">นายณัฐภาคย์ บัณฑิตโกวิทย์ (ตี๋)</h3>
                        <p class="text-brand-accent font-semibold mb-3">หุ้นส่วนอาวุโส</p>
                        <p class="text-gray-600 text-sm">ทนายความอาวุโส ประสบการณ์มากกว่า 40 ปี เชี่ยวชาญกฎหมายแพ่งและอาญา</p>
                    </div>
                    
                    <div class="bg-white p-6 rounded-xl shadow-md text-center border border-gray-100 hover:shadow-xl transition-shadow">
                        <div class="w-24 h-24 bg-brand-dark-secondary rounded-full mx-auto mb-4 flex items-center justify-center text-white text-3xl font-bold">
                            คุณส
                        </div>
                        <h3 class="text-xl font-bold text-gray-900 mb-1">นางสาวภาวิศกาญจน์ (ออม)</h3>
                        <p class="text-brand-accent font-semibold mb-3">นักบัญชีและผู้เชี่ยวชาญภาษี</p>
                        <p class="text-gray-600 text-sm">ประสบการณ์ทางบัญชีและภาษีมากกว่า 4 ปี เชี่ยวชาญการวางแผนภาษีและบัญชี</p>
                    </div>
                    
                    <div class="bg-white p-6 rounded-xl shadow-md text-center border border-gray-100 hover:shadow-xl transition-shadow">
                        <div class="w-24 h-24 bg-brand-dark-secondary rounded-full mx-auto mb-4 flex items-center justify-center text-white text-3xl font-bold">
                            คุณว
                        </div>
                        <h3 class="text-xl font-bold text-gray-900 mb-1">นายเนติธร บัณฑิตโกวิทย์ (ก้อง)</h3>
                        <p class="text-brand-accent font-semibold mb-3">ทนายความคดีธุรกิจ</p>
                        <p class="text-gray-600 text-sm">ทนายความผู้เชี่ยวชาญกฎหมายธุรกิจ สัญญา และการลงทุน ประสบการณ์มมากกว่า 2 ปี</p>
                    </div>
                    
                    <div class="bg-white p-6 rounded-xl shadow-md text-center border border-gray-100 hover:shadow-xl transition-shadow">
                        <div class="w-24 h-24 bg-brand-dark-secondary rounded-full mx-auto mb-4 flex items-center justify-center text-white text-3xl font-bold">
                            คุณม
                        </div>
                        <h3 class="text-xl font-bold text-gray-900 mb-1">คุณมาลี ระหว่างประเทศ</h3>
                        <p class="text-brand-accent font-semibold mb-3">ที่ปรึกษาต่างประเทศ</p>
                        <p class="text-gray-600 text-sm">LL.M. จาก Harvard เชี่ยวชาญกฎหมายระหว่างประเทศ</p>
                    </div>
                </div>
            </div>
            
            <!-- English Content -->
            <div class="lang-content" data-lang="en">
                <div class="text-center mb-16">
                    <h2 class="text-4xl md:text-5xl font-bold text-gray-900 mb-6">Expert Team</h2>
                    <p class="text-xl text-gray-600 max-w-3xl mx-auto">
                        Professional lawyers and consultants ready to serve with high expertise and experience
                    </p>
                </div>
                
                <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-8">
                    <div class="bg-white p-6 rounded-xl shadow-md text-center border border-gray-100 hover:shadow-xl transition-shadow">
                        <div class="w-24 h-24 bg-brand-dark-secondary rounded-full mx-auto mb-4 flex items-center justify-center text-white text-3xl font-bold">
                            Dr.J
                        </div>
                        <h3 class="text-xl font-bold text-gray-900 mb-1">Dr.John Smith</h3>
                        <p class="text-brand-accent font-semibold mb-3">Senior Partner</p>
                        <p class="text-gray-600 text-sm">Senior lawyer with 20 years experience, specializing in business and corporate law</p>
                    </div>
                    
                    <div class="bg-white p-6 rounded-xl shadow-md text-center border border-gray-100 hover:shadow-xl transition-shadow">
                        <div class="w-24 h-24 bg-brand-dark-secondary rounded-full mx-auto mb-4 flex items-center justify-center text-white text-3xl font-bold">
                            S
                        </div>
                        <h3 class="text-xl font-bold text-gray-900 mb-1">Sarah Johnson</h3>
                        <p class="text-brand-accent font-semibold mb-3">Tax Specialist</p>
                        <p class="text-gray-600 text-sm">CPA with 15 years experience, specializing in tax planning and accounting</p>
                    </div>
                    
                    <div class="bg-white p-6 rounded-xl shadow-md text-center border border-gray-100 hover:shadow-xl transition-shadow">
                        <div class="w-24 h-24 bg-brand-dark-secondary rounded-full mx-auto mb-4 flex items-center justify-center text-white text-3xl font-bold">
                            M
                        </div>
                        <h3 class="text-xl font-bold text-gray-900 mb-1">Mike Wilson</h3>
                        <p class="text-brand-accent font-semibold mb-3">Litigation Lawyer</p>
                        <p class="text-gray-600 text-sm">Lawyer specializing in civil and criminal cases with 18 years experience</p>
                    </div>
                    
                    <div class="bg-white p-6 rounded-xl shadow-md text-center border border-gray-100 hover:shadow-xl transition-shadow">
                        <div class="w-24 h-24 bg-brand-dark-secondary rounded-full mx-auto mb-4 flex items-center justify-center text-white text-3xl font-bold">
                            L
                        </div>
                        <h3 class="text-xl font-bold text-gray-900 mb-1">Lisa Chen</h3>
                        <p class="text-brand-accent font-semibold mb-3">International Consultant</p>
                        <p class="text-gray-600 text-sm">LL.M. from Harvard, specializing in international law</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- NEW Blog Section -->
    <section id="blog" class="py-20 bg-gray-50">
        <div class=“px-4 sm:px-6 lg:px-8”>
            <!-- Thai Content -->
            <div class="lang-content active" data-lang="th">
                <div class="text-center mb-16">
                    <h2 class="text-4xl md:text-5xl font-bold text-gray-900 mb-6">ศูนย์รวมความรู้</h2>
                    <p class="text-xl text-gray-600 max-w-3xl mx-auto">
                        บทความและข้อมูลเชิงลึกด้านกฎหมาย ภาษี และธุรกิจ จากทีมผู้เชี่ยวชาญของเรา
                    </p>
                </div>
                
                <div class="grid md:grid-cols-2 gap-8">
                    <!-- Blog Card 1 (TH) -->
                    <div class="bg-white rounded-xl shadow-md overflow-hidden hover:shadow-xl transition-shadow group">
                        <div class="p-6">
                            <span class="text-sm font-semibold text-brand-accent">กฎหมายธุรกิจ</span>
                            <h3 class="text-2xl font-bold text-gray-900 mt-2 mb-3 group-hover:text-brand-dark-secondary">
                                5 ข้อควรรู้ก่อนจดทะเบียนบริษัท ต้องเตรียมอะไรบ้าง?
                            </h3>
                            <p class="text-gray-600 mb-4">
                                การเริ่มต้นบริษัทมีขั้นตอนสำคัญหลายอย่าง การเตรียมตัวที่ดีจะช่วยให้กระบวนการราบรื่น...
                            </p>
                            <a href="#" class="font-semibold text-brand-accent hover:text-brand-accent-hover">อ่านต่อ &rarr;</a>
                        </div>
                    </div>
                    <!-- Blog Card 2 (TH) -->
                    <div class="bg-white rounded-xl shadow-md overflow-hidden hover:shadow-xl transition-shadow group">
                        <div class="p-6">
                            <span class="text-sm font-semibold text-brand-accent">กฎหมายมรดก</span>
                            <h3 class="text-2xl font-bold text-gray-900 mt-2 mb-3 group-hover:text-brand-dark-secondary">
                                การจัดการมรดกที่ไม่มีพินัยกรรม: ขั้นตอนและข้อควรระวัง
                            </h3>
                            <p class="text-gray-600 mb-4">
                                เมื่อบุคคลอันเป็นที่รักจากไปโดยไม่ได้ทำพินัยกรรมไว้ การจัดการมรดกจะมีขั้นตอนตามกฎหมาย...
                            </p>
                            <a href="#" class="font-semibold text-brand-accent hover:text-brand-accent-hover">อ่านต่อ &rarr;</a>
                        </div>
                    </div>
                </div>
            </div>
            
            <!-- English Content -->
            <div class="lang-content" data-lang="en">
                <div class="text-center mb-16">
                    <h2 class="text-4xl md:text-5xl font-bold text-gray-900 mb-6">Knowledge Center</h2>
                    <p class="text-xl text-gray-600 max-w-3xl mx-auto">
                        Articles and insights on law, tax, and business from our expert team.
                    </p>
                </div>
                
                <div class="grid md:grid-cols-2 gap-8">
                    <!-- Blog Card 1 (EN) -->
                    <div class="bg-white rounded-xl shadow-md overflow-hidden hover:shadow-xl transition-shadow group">
                        <div class="p-6">
                            <span class="text-sm font-semibold text-brand-accent">Real Estate</span>
                            <h3 class="text-2xl font-bold text-gray-900 mt-2 mb-3 group-hover:text-brand-dark-secondary">
                                A Foreigner's Guide to Buying a Condominium in Thailand
                            </h3>
                            <p class="text-gray-600 mb-4">
                                Understanding the legal framework is crucial for any foreigner looking to purchase property in Thailand...
                            </p>
                            <a href="#" class="font-semibold text-brand-accent hover:text-brand-accent-hover">Read More &rarr;</a>
                        </div>
                    </div>
                    <!-- Blog Card 2 (EN) -->
                    <div class="bg-white rounded-xl shadow-md overflow-hidden hover:shadow-xl transition-shadow group">
                        <div class="p-6">
                            <span class="text-sm font-semibold text-brand-accent">Data Protection (PDPA)</span>
                            <h3 class="text-2xl font-bold text-gray-900 mt-2 mb-3 group-hover:text-brand-dark-secondary">
                                Understanding Thailand's PDPA for Businesses
                            </h3>
                            <p class="text-gray-600 mb-4">
                                The Personal Data Protection Act (PDPA) imposes new compliance requirements for all businesses...
                            </p>
                            <a href="#" class="font-semibold text-brand-accent hover:text-brand-accent-hover">Read More &rarr;</a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Pricing Section -->
    <section id="pricing" class="py-20 bg-white">
        <div class=“px-4 sm:px-6 lg:px-8”>
            <!-- Thai Content -->
            <div class="lang-content active" data-lang="th">
                <div class="text-center mb-16">
                    <h2 class="text-4xl md:text-5xl font-bold text-gray-900 mb-6">แพ็คเกจบริการ</h2>
                    <p class="text-xl text-gray-600 max-w-3xl mx-auto">
                        เลือกแพ็คเกจที่เหมาะสมกับความต้องการของคุณ ราคาโปร่งใส ไม่มีค่าใช้จ่ายแอบแฝง
                    </p>
                </div>
                
                <div class="grid md:grid-cols-3 gap-8">
                    <!-- Pricing Card 1 -->
                    <div class="pricing-card bg-white p-8 rounded-2xl shadow-lg border border-gray-100">
                        <div class="text-center mb-8">
                            <h3 class="text-2xl font-bold text-gray-900 mb-4">แพ็คเกจเริ่มต้น</h3>
                            <div class="text-4xl font-bold text-brand-dark mb-2">฿15,000</div>
                            <p class="text-gray-500">/ เดือน</p>
                        </div>
                        <ul class="space-y-4 mb-8">
                            <li class="flex items-start">
                                <svg class="w-5 h-5 text-green-500 mr-3 mt-0.5" fill="currentColor" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd"></path></svg>
                                <span>ปรึกษากฎหมายทั่วไป</span>
                            </li>
                            <li class="flex items-start">
                                <svg class="w-5 h-5 text-green-500 mr-3 mt-0.5" fill="currentColor" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd"></path></svg>
                                <span>จัดทำสัญญาพื้นฐาน</span>
                            </li>
                        </ul>
                        <button class="w-full bg-brand-dark text-white py-3 rounded-md font-semibold hover:bg-brand-dark-secondary transition-colors">
                            เลือกแพ็คเกจนี้
                        </button>
                    </div>
                    
                    <!-- Pricing Card 2 (Recommended) -->
                    <div class="pricing-card bg-brand-dark p-8 rounded-2xl shadow-xl text-white transform md:scale-105">
                        <div class="text-center mb-8">
                            <div class="bg-brand-accent text-brand-dark px-4 py-1 rounded-full text-sm font-semibold mb-4 inline-block">
                                แนะนำ
                            </div>
                            <h3 class="text-2xl font-bold mb-4">แพ็คเกจธุรกิจ</h3>
                            <div class="text-4xl font-bold mb-2">฿35,000</div>
                            <p class="text-gray-300">/ เดือน</p>
                        </div>
                        <ul class="space-y-4 mb-8">
                            <li class="flex items-start">
                                <svg class="w-5 h-5 text-brand-accent mr-3 mt-0.5" fill="currentColor" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd"></path></svg>
                                <span>บริการแพ็คเกจเริ่มต้น ทั้งหมด</span>
                            </li>
                            <li class="flex items-start">
                                <svg class="w-5 h-5 text-brand-accent mr-3 mt-0.5" fill="currentColor" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd"></path></svg>
                                <span>กฎหมายบริษัท ห้างหุ้นส่วน</span>
                            </li>
                            <li class="flex items-start">
                                <svg class="w-5 h-5 text-brand-accent mr-3 mt-0.5" fill="currentColor" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd"></path></svg>
                                <span>ภาษีนิติบุคคล VAT</span>
                            </li>
                            <li class="flex items-start">
                                <svg class="w-5 h-5 text-brand-accent mr-3 mt-0.5" fill="currentColor" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd"></path></svg>
                                <span>ที่ปรึกษาธุรกิจ</span>
                            </li>
                        </ul>
                        <button class="w-full bg-brand-accent text-brand-dark py-3 rounded-md font-semibold hover:bg-brand-accent-hover transition-colors">
                            เลือกแพ็คเกจนี้
                        </button>
                    </div>
                    
                    <!-- Pricing Card 3 -->
                    <div class="pricing-card bg-white p-8 rounded-2xl shadow-lg border border-gray-100">
                        <div class="text-center mb-8">
                            <h3 class="text-2xl font-bold text-gray-900 mb-4">แพ็คเกจองค์กร</h3>
                            <div class="text-4xl font-bold text-brand-dark mb-2">฿75,000</div>
                            <p class="text-gray-500">/ เดือน</p>
                        </div>
                        <ul class="space-y-4 mb-8">
                            <li class="flex items-start">
                                <svg class="w-5 h-5 text-green-500 mr-3 mt-0.5" fill="currentColor" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd"></path></svg>
                                <span>บริการแพ็คเกจธุรกิจ ทั้งหมด</span>
                            </li>
                            <li class="flex items-start">
                                <svg class="w-5 h-5 text-green-500 mr-3 mt-0.5" fill="currentColor" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd"></path></svg>
                                <span>กฎหมายระหว่างประเทศ</span>
                            </li>
                            <li class="flex items-start">
                                <svg class="w-5 h-5 text-green-500 mr-3 mt-0.5" fill="currentColor" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd"></path></svg>
                                <span>M&A และ Due Diligence</span>
                            </li>
                            <li class="flex items-start">
                                <svg class="w-5 h-5 text-green-500 mr-3 mt-0.5" fill="currentColor" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd"></path></svg>
                                <span>ทีมผู้เชี่ยวชาญเฉพาะ</span>
                            </li>
                        </ul>
                        <button class="w-full bg-brand-dark text-white py-3 rounded-md font-semibold hover:bg-brand-dark-secondary transition-colors">
                            ติดต่อเรา
                        </button>
                    </div>
                </div>
            </div>
            
            <!-- English Content -->
            <div class="lang-content" data-lang="en">
                <div class="text-center mb-16">
                    <h2 class="text-4xl md:text-5xl font-bold text-gray-900 mb-6">Service Packages</h2>
                    <p class="text-xl text-gray-600 max-w-3xl mx-auto">
                        Choose the package that suits your needs. Transparent pricing with no hidden costs.
                    </p>
                </div>
                
                <div class="grid md:grid-cols-3 gap-8">
                    <!-- Pricing Card 1 -->
                    <div class="pricing-card bg-white p-8 rounded-2xl shadow-lg border border-gray-100">
                        <div class="text-center mb-8">
                            <h3 class="text-2xl font-bold text-gray-900 mb-4">Starter Package</h3>
                            <div class="text-4xl font-bold text-brand-dark mb-2">฿15,000</div>
                            <p class="text-gray-500">/ month</p>
                        </div>
                        <ul class="space-y-4 mb-8">
                            <li class="flex items-start">
                                <svg class="w-5 h-5 text-green-500 mr-3 mt-0.5" fill="currentColor" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd"></path></svg>
                                <span>General legal consultation</span>
                            </li>
                            <li class="flex items-start">
                                <svg class="w-5 h-5 text-green-500 mr-3 mt-0.5" fill="currentColor" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd"></path></svg>
                                <span>Basic contract drafting</span>
                            </li>
                        </ul>
                        <button class="w-full bg-brand-dark text-white py-3 rounded-md font-semibold hover:bg-brand-dark-secondary transition-colors">
                            Choose This Package
                        </button>
                    </div>
                    
                    <!-- Pricing Card 2 (Recommended) -->
                    <div class="pricing-card bg-brand-dark p-8 rounded-2xl shadow-xl text-white transform md:scale-105">
                        <div class="text-center mb-8">
                            <div class="bg-brand-accent text-brand-dark px-4 py-1 rounded-full text-sm font-semibold mb-4 inline-block">
                                Recommended
                            </div>
                            <h3 class="text-2xl font-bold mb-4">Business Package</h3>
                            <div class="text-4xl font-bold mb-2">฿35,000</div>
                            <p class="text-gray-300">/ month</p>
                        </div>
                        <ul class="space-y-4 mb-8">
                            <li class="flex items-start">
                                <svg class="w-5 h-5 text-brand-accent mr-3 mt-0.5" fill="currentColor" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd"></path></svg>
                                <span>All starter package services</span>
                            </li>
                            <li class="flex items-start">
                                <svg class="w-5 h-5 text-brand-accent mr-3 mt-0.5" fill="currentColor" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd"></path></svg>
                                <span>Corporate & partnership law</span>
                            </li>
                            <li class="flex items-start">
                                <svg class="w-5 h-5 text-brand-accent mr-3 mt-0.5" fill="currentColor" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd"></path></svg>
                                <span>Corporate tax & VAT</span>
                            </li>
                            <li class="flex items-start">
                                <svg class="w-5 h-5 text-brand-accent mr-3 mt-0.5" fill="currentColor" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd"></path></svg>
                                <span>Business consulting</span>
                            </li>
                        </ul>
                        <button class="w-full bg-brand-accent text-brand-dark py-3 rounded-md font-semibold hover:bg-brand-accent-hover transition-colors">
                            Choose This Package
                        </button>
                    </div>
                    
                    <!-- Pricing Card 3 -->
                    <div class="pricing-card bg-white p-8 rounded-2xl shadow-lg border border-gray-100">
                        <div class="text-center mb-8">
                            <h3 class="text-2xl font-bold text-gray-900 mb-4">Enterprise Package</h3>
                            <div class="text-4xl font-bold text-brand-dark mb-2">฿75,000</div>
                            <p class="text-gray-500">/ month</p>
                        </div>
                        <ul class="space-y-4 mb-8">
                            <li class="flex items-start">
                                <svg class="w-5 h-5 text-green-500 mr-3 mt-0.5" fill="currentColor" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd"></path></svg>
                                <span>All business package services</span>
                            </li>
                            <li class="flex items-start">
                                <svg class="w-5 h-5 text-green-500 mr-3 mt-0.5" fill="currentColor" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd"></path></svg>
                                <span>International law</span>
                            </li>
                            <li class="flex items-start">
                                <svg class="w-5 h-5 text-green-500 mr-3 mt-0.5" fill="currentColor" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd"></path></svg>
                                <span>M&A and Due Diligence</span>
                            </li>
                            <li class="flex items-start">
                                <svg class="w-5 h-5 text-green-500 mr-3 mt-0.5" fill="currentColor" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd"></path></svg>
                                <span>Dedicated expert team</span>
                            </li>
                        </ul>
                        <button class="w-full bg-brand-dark text-white py-3 rounded-md font-semibold hover:bg-brand-dark-secondary transition-colors">
                            Contact Us
                        </button>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Testimonials Section -->
    <section id="testimonials" class="py-20 bg-gray-50">
        <div class=“px-4 sm:px-6 lg:px-8”>
            <!-- Admin Controls -->
            <div class="mb-8 p-4 bg-gray-100 rounded-lg admin-panel" id="admin-controls" style="display: none;">
                <div class="flex justify-between items-center mb-4">
                    <h3 class="text-lg font-semibold text-gray-900">จัดการความคิดเห็น</h3>
                    <button id="toggle-testimonials" class="bg-brand-dark text-white px-4 py-2 rounded-md hover:bg-brand-dark-secondary transition-colors">
                        <span id="toggle-text">ซ่อนส่วนความคิดเห็น</span>
                    </button>
                </div>
                <button id="admin-login-btn" class="bg-gray-600 text-white px-4 py-2 rounded-md hover:bg-gray-700 transition-colors">
                    เข้าสู่ระบบผู้ดูแล
                </button>
            </div>

            <!-- Thai Content -->
            <div class="lang-content active" data-lang="th" id="testimonials-section">
                <div class="text-center mb-16">
                    <h2 class="text-4xl md:text-5xl font-bold text-gray-900 mb-6">ความคิดเห็นลูกค้า</h2>
                    <p class="text-xl text-gray-600 max-w-3xl mx-auto">
                        แบ่งปันประสบการณ์การใช้บริการของคุณ
                    </p>
                </div>

                <!-- Add Review Form -->
                <div class="max-w-2xl mx-auto mb-12 bg-white p-8 rounded-xl shadow-md">
                    <h3 class="text-2xl font-bold text-gray-900 mb-6 text-center">แสดงความคิดเห็น</h3>
                    <form id="review-form" class="space-y-6">
                        <div class="grid md:grid-cols-2 gap-6">
                            <div>
                                <label for="customer-id" class="block text-sm font-medium text-gray-700 mb-2">เลขที่ลูกค้า *</label>
                                <input type="text" id="customer-id" name="customerId" required 
                                       class="w-full px-4 py-3 border border-gray-300 rounded-md focus:ring-2 focus:ring-brand-accent focus:border-transparent"
                                       placeholder="เช่น LP-2024-001">
                            </div>
                            <div>
                                <label for="customer-name" class="block text-sm font-medium text-gray-700 mb-2">ชื่อ-นามสกุล *</label>
                                <input type="text" id="customer-name" name="customerName" required 
                                       class="w-full px-4 py-3 border border-gray-300 rounded-md focus:ring-2 focus:ring-brand-accent focus:border-transparent"
                                       placeholder="ชื่อของคุณ">
                            </div>
                        </div>
                        <div>
                            <label for="customer-position" class="block text-sm font-medium text-gray-700 mb-2">ตำแหน่ง/บริษัท</label>
                            <input type="text" id="customer-position" name="customerPosition" 
                                   class="w-full px-4 py-3 border border-gray-300 rounded-md focus:ring-2 focus:ring-brand-accent focus:border-transparent"
                                   placeholder="เช่น CEO บริษัท ABC จำกัด">
                        </div>
                        <div>
                            <label for="rating" class="block text-sm font-medium text-gray-700 mb-2">คะแนน *</label>
                            <div class="flex space-x-2">
                                <button type="button" class="star-btn text-3xl text-gray-300 hover:text-yellow-400 transition-colors" data-rating="1">⭐</button>
                                <button type="button" class="star-btn text-3xl text-gray-300 hover:text-yellow-400 transition-colors" data-rating="2">⭐</button>
                                <button type="button" class="star-btn text-3xl text-gray-300 hover:text-yellow-400 transition-colors" data-rating="3">⭐</button>
                                <button type="button" class="star-btn text-3xl text-gray-300 hover:text-yellow-400 transition-colors" data-rating="4">⭐</button>
                                <button type="button" class="star-btn text-3xl text-gray-300 hover:text-yellow-400 transition-colors" data-rating="5">⭐</button>
                            </div>
                            <input type="hidden" id="rating-value" name="rating" required>
                        </div>
                        <div>
                            <label for="review-text" class="block text-sm font-medium text-gray-700 mb-2">ความคิดเห็น *</label>
                            <textarea id="review-text" name="reviewText" rows="4" required 
                                      class="w-full px-4 py-3 border border-gray-300 rounded-md focus:ring-2 focus:ring-brand-accent focus:border-transparent"
                                      placeholder="แบ่งปันประสบการณ์การใช้บริการของคุณ..."></textarea>
                        </div>
                        <button type="submit" class="w-full bg-brand-dark text-white py-3 rounded-md font-semibold hover:bg-brand-dark-secondary transition-colors">
                            ส่งความคิดเห็น
                        </button>
                    </form>
                </div>

                <!-- Reviews Display -->
                <div id="reviews-container" class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
                    <!-- Reviews will be dynamically added here -->
                </div>
            </div>
            
            <!-- English Content -->
            <div class="lang-content" data-lang="en" id="testimonials-section-en">
                <div class="text-center mb-16">
                    <h2 class="text-4xl md:text-5xl font-bold text-gray-900 mb-6">Client Testimonials</h2>
                    <p class="text-xl text-gray-600 max-w-3xl mx-auto">
                        Share your experience with our services
                    </p>
                </div>

                <!-- Add Review Form English -->
                <div class="max-w-2xl mx-auto mb-12 bg-white p-8 rounded-xl shadow-md">
                    <h3 class="text-2xl font-bold text-gray-900 mb-6 text-center">Leave a Review</h3>
                    <form id="review-form-en" class="space-y-6">
                        <div class="grid md:grid-cols-2 gap-6">
                            <div>
                                <label for="customer-id-en" class="block text-sm font-medium text-gray-700 mb-2">Customer ID *</label>
                                <input type="text" id="customer-id-en" name="customerId" required 
                                       class="w-full px-4 py-3 border border-gray-300 rounded-md focus:ring-2 focus:ring-brand-accent focus:border-transparent"
                                       placeholder="e.g. LP-2024-001">
                            </div>
                            <div>
                                <label for="customer-name-en" class="block text-sm font-medium text-gray-700 mb-2">Full Name *</label>
                                <input type="text" id="customer-name-en" name="customerName" required 
                                       class="w-full px-4 py-3 border border-gray-300 rounded-md focus:ring-2 focus:ring-brand-accent focus:border-transparent"
                                       placeholder="Your name">
                            </div>
                        </div>
                        <div>
                            <label for="customer-position-en" class="block text-sm font-medium text-gray-700 mb-2">Position/Company</label>
                            <input type="text" id="customer-position-en" name="customerPosition" 
                                   class="w-full px-4 py-3 border border-gray-300 rounded-md focus:ring-2 focus:ring-brand-accent focus:border-transparent"
                                   placeholder="e.g. CEO, ABC Company Ltd.">
                        </div>
                        <div>
                            <label for="rating-en" class="block text-sm font-medium text-gray-700 mb-2">Rating *</label>
                            <div class="flex space-x-2">
                                <button type="button" class="star-btn-en text-3xl text-gray-300 hover:text-yellow-400 transition-colors" data-rating="1">⭐</button>
                                <button type="button" class="star-btn-en text-3xl text-gray-300 hover:text-yellow-400 transition-colors" data-rating="2">⭐</button>
                                <button type="button" class="star-btn-en text-3xl text-gray-300 hover:text-yellow-400 transition-colors" data-rating="3">⭐</button>
                                <button type="button" class="star-btn-en text-3xl text-gray-300 hover:text-yellow-400 transition-colors" data-rating="4">⭐</button>
                                <button type="button" class="star-btn-en text-3xl text-gray-300 hover:text-yellow-400 transition-colors" data-rating="5">⭐</button>
                            </div>
                            <input type="hidden" id="rating-value-en" name="rating" required>
                        </div>
                        <div>
                            <label for="review-text-en" class="block text-sm font-medium text-gray-700 mb-2">Review *</label>
                            <textarea id="review-text-en" name="reviewText" rows="4" required 
                                      class="w-full px-4 py-3 border border-gray-300 rounded-md focus:ring-2 focus:ring-brand-accent focus:border-transparent"
                                      placeholder="Share your experience with our services..."></textarea>
                        </div>
                        <button type="submit" class="w-full bg-brand-dark text-white py-3 rounded-md font-semibold hover:bg-brand-dark-secondary transition-colors">
                            Submit Review
                        </button>
                    </form>
                </div>

                <!-- Reviews Display English -->
                <div id="reviews-container-en" class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
                    <!-- Reviews will be dynamically added here -->
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-20 bg-white">
        <div class=“px-4 sm:px-6 lg:px-8”>
            <!-- Thai Content -->
            <div class="lang-content active" data-lang="th">
                <div class="text-center mb-16">
                    <h2 class="text-4xl md:text-5xl font-bold text-gray-900 mb-6">ติดต่อเรา</h2>
                    <p class="text-xl text-gray-600 max-w-3xl mx-auto">
                        พร้อมให้คำปรึกษาและบริการ 24/7 ติดต่อเราได้ทุกช่องทาง
                    </p>
                </div>
                
                <div class="grid md:grid-cols-2 gap-12">
                    <div>
                        <div class="space-y-8">
                            <div class="flex items-start">
                                <div class="w-12 h-12 bg-brand-accent bg-opacity-10 rounded-lg flex items-center justify-center mr-4">
                                    <svg class="w-6 h-6 text-brand-accent" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"></path></svg>
                                </div>
                                <div>
                                    <h3 class="text-xl font-bold text-gray-900 mb-2">โทรศัพท์</h3>
                                    <p class="text-gray-600">02-123-4567</p>
                                    <p class="text-gray-600">081-234-5678</p>
                                </div>
                            </div>
                            
                            <div class="flex items-start">
                                <div class="w-12 h-12 bg-brand-accent bg-opacity-10 rounded-lg flex items-center justify-center mr-4">
                                    <svg class="w-6 h-6 text-brand-accent" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"></path></svg>
                                </div>
                                <div>
                                    <h3 class="text-xl font-bold text-gray-900 mb-2">อีเมล</h3>
                                    <p class="text-gray-600">info@syndicate-law.com</p>
                                    <p class="text-gray-600">contact@syndicate-law.com</p>
                                </div>
                            </div>
                            
                            <div class="flex items-start">
                                <div class="w-12 h-12 bg-brand-accent bg-opacity-10 rounded-lg flex items-center justify-center mr-4">
                                    <svg class="w-6 h-6 text-brand-accent" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0zM15 11a3 3 0 11-6 0 3 3 0 016 0z"></path></svg>
                                </div>
                                <div>
                                    <h3 class="text-xl font-bold text-gray-900 mb-2">ที่อยู่</h3>
                                    <p class="text-gray-600">123 ถนนสีลม แขวงสีลม<br>เขตบางรัก กรุงเทพฯ 10500</p>
                                </div>
                            </div>
                        </div>
                    </div>
                    
                    <div class="bg-gray-50 p-8 rounded-xl shadow-md border">
                        <h3 class="text-2xl font-bold text-gray-900 mb-6">ส่งข้อความถึงเรา</h3>
                        <form id="contact-form-th" class="space-y-6">
                            <div class="grid md:grid-cols-2 gap-6">
                                <div>
                                    <label for="contact-name" class="block text-sm font-medium text-gray-700 mb-2">ชื่อ-นามสกุล</label>
                                    <input type="text" id="contact-name" class="w-full px-4 py-3 border border-gray-300 rounded-md focus:ring-2 focus:ring-brand-accent focus:border-transparent">
                                </div>
                                <div>
                                    <label for="contact-phone" class="block text-sm font-medium text-gray-700 mb-2">เบอร์โทรศัพท์</label>
                                    <input type="tel" id="contact-phone" class="w-full px-4 py-3 border border-gray-300 rounded-md focus:ring-2 focus:ring-brand-accent focus:border-transparent">
                                </div>
                            </div>
                            <div>
                                <label for="contact-email" class="block text-sm font-medium text-gray-700 mb-2">อีเมล</label>
                                <input type="email" id="contact-email" class="w-full px-4 py-3 border border-gray-300 rounded-md focus:ring-2 focus:ring-brand-accent focus:border-transparent">
                            </div>
                            <div>
                                <label for="contact-subject" class="block text-sm font-medium text-gray-700 mb-2">หัวข้อ</label>
                                <input type="text" id="contact-subject" class="w-full px-4 py-3 border border-gray-300 rounded-md focus:ring-2 focus:ring-brand-accent focus:border-transparent">
                            </div>
                            <div>
                                <label for="contact-message" class="block text-sm font-medium text-gray-700 mb-2">ข้อความ</label>
                                <textarea id="contact-message" rows="4" class="w-full px-4 py-3 border border-gray-300 rounded-md focus:ring-2 focus:ring-brand-accent focus:border-transparent"></textarea>
                            </div>
                            <button type="submit" class="w-full bg-brand-dark text-white py-3 rounded-md font-semibold hover:bg-brand-dark-secondary transition-colors">
                                ส่งข้อความ
                            </button>
                        </form>
                    </div>
                </div>
            </div>
            
            <!-- English Content -->
            <div class="lang-content" data-lang="en">
                <div class="text-center mb-16">
                    <h2 class="text-4xl md:text-5xl font-bold text-gray-900 mb-6">Contact Us</h2>
                    <p class="text-xl text-gray-600 max-w-3xl mx-auto">
                        Ready to provide consultation and services 24/7. Contact us through any channel.
                    </p>
                </div>
                
                <div class="grid md:grid-cols-2 gap-12">
                    <div>
                        <div class="space-y-8">
                            <div class="flex items-start">
                                <div class="w-12 h-12 bg-brand-accent bg-opacity-10 rounded-lg flex items-center justify-center mr-4">
                                    <svg class="w-6 h-6 text-brand-accent" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"></path></svg>
                                </div>
                                <div>
                                    <h3 class="text-xl font-bold text-gray-900 mb-2">Phone</h3>
                                    <p class="text-gray-600">02-123-4567</p>
                                    <p class="text-gray-600">081-234-5678</p>
                                </div>
                            </div>
                            
                            <div class="flex items-start">
                                <div class="w-12 h-12 bg-brand-accent bg-opacity-10 rounded-lg flex items-center justify-center mr-4">
                                    <svg class="w-6 h-6 text-brand-accent" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"></path></svg>
                                </div>
                                <div>
                                    <h3 class="text-xl font-bold text-gray-900 mb-2">Email</h3>
                                    <p class="text-gray-600">info@syndicate-law.com</p>
                                    <p class="text-gray-600">contact@syndicate-law.com</p>
                                </div>
                            </div>
                            
                            <div class="flex items-start">
                                <div class="w-12 h-12 bg-brand-accent bg-opacity-10 rounded-lg flex items-center justify-center mr-4">
                                    <svg class="w-6 h-6 text-brand-accent" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0zM15 11a3 3 0 11-6 0 3 3 0 016 0z"></path></svg>
                                </div>
                                <div>
                                    <h3 class="text-xl font-bold text-gray-900 mb-2">Address</h3>
                                    <p class="text-gray-600">123 Silom Road, Silom Sub-district<br>Bang Rak District, Bangkok 10500</p>
                                </div>
                            </div>
                        </div>
                    </div>
                    
                    <div class="bg-gray-50 p-8 rounded-xl shadow-md border">
                        <h3 class="text-2xl font-bold text-gray-900 mb-6">Send us a Message</h3>
                        <form id="contact-form-en" class="space-y-6">
                            <div class="grid md:grid-cols-2 gap-6">
                                <div>
                                    <label for="contact-name-en" class="block text-sm font-medium text-gray-700 mb-2">Full Name</label>
                                    <input type="text" id="contact-name-en" class="w-full px-4 py-3 border border-gray-300 rounded-md focus:ring-2 focus:ring-brand-accent focus:border-transparent">
                                </div>
                                <div>
                                    <label for="contact-phone-en" class="block text-sm font-medium text-gray-700 mb-2">Phone Number</label>
                                    <input type="tel" id="contact-phone-en" class="w-full px-4 py-3 border border-gray-300 rounded-md focus:ring-2 focus:ring-brand-accent focus:border-transparent">
                                </div>
                            </div>
                            <div>
                                <label for="contact-email-en" class="block text-sm font-medium text-gray-700 mb-2">Email</label>
                                <input type="email" id="contact-email-en" class="w-full px-4 py-3 border border-gray-300 rounded-md focus:ring-2 focus:ring-brand-accent focus:border-transparent">
                            </div>
                            <div>
                                <label for="contact-subject-en" class="block text-sm font-medium text-gray-700 mb-2">Subject</label>
                                <input type="text" id="contact-subject-en" class="w-full px-4 py-3 border border-gray-300 rounded-md focus:ring-2 focus:ring-brand-accent focus:border-transparent">
                            </div>
                            <div>
                                <label for="contact-message-en" class="block text-sm font-medium text-gray-700 mb-2">Message</label>
                                <textarea id="contact-message-en" rows="4" class="w-full px-4 py-3 border border-gray-300 rounded-md focus:ring-2 focus:ring-brand-accent focus:border-transparent"></textarea>
                            </div>
                            <button type="submit" class="w-full bg-brand-dark text-white py-3 rounded-md font-semibold hover:bg-brand-dark-secondary transition-colors">
                                Send Message
                            </button>
                        </form>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-brand-dark text-white py-12">
        <div class=“px-4 sm:px-6 lg:px-8”>
            <div class="grid grid-cols-2 md:grid-cols-5 gap-8">
                <!-- Footer Logo Column -->
                <div class="col-span-2 md:col-span-2">
                    <div class="flex items-center mb-4">
                        <svg version="1.1" id="_x32_" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" viewBox="0 0 512 512" xml:space="preserve" class="h-14 w-auto mr-4"> <style type="text/css"> .st0{fill:#ffffff;} </style> <g> <path class="st0" d="M501.98,206.15c-9.769-23.023-25.998-42.56-46.458-56.389c-10.181-6.873-21.446-12.34-33.536-16.068 c-12.009-3.809-24.842-5.798-38.088-5.798c-16.982,0-33.294,3.316-48.197,9.365c-1.246,0.492-2.402,0.986-3.558,1.568 c-13.416,5.879-25.675,14.16-36.188,24.017c-3.396,3.227-6.623,6.623-9.858,10.432c-5.709,6.542-11.588,14.079-17.305,21.696 c-1.157,1.568-2.402,3.226-3.558,4.804c-3.146,4.302-33.212,48.358-38.509,56.226c-2.652,3.97-5.798,8.442-9.195,13.327 c-0.744,1.076-1.568,2.24-2.393,3.396c-5.636,8.031-11.928,16.481-17.726,23.937c-2.895,3.72-5.798,7.197-8.281,10.1 c-2.563,2.976-4.884,5.378-6.542,6.954c-7.116,6.704-15.486,12.171-24.672,15.899c-9.194,3.728-19.214,5.798-29.816,5.798 c-7.286,0-14.322-0.996-20.944-2.815c-3.396-0.913-6.712-2.07-9.939-3.477c-14.248-5.968-26.419-16.068-34.95-28.74 c-4.302-6.372-7.699-13.327-10.019-20.783c-2.233-7.456-3.558-15.316-3.558-23.597c0-11.014,2.24-21.365,6.21-30.892 c6.049-14.24,16.149-26.329,28.821-34.942c6.372-4.31,13.326-7.618,20.782-9.939c7.448-2.321,15.316-3.638,23.597-3.638 c10.602,0.08,20.622,2.07,29.816,5.79c9.187,3.808,17.556,9.194,24.672,15.898c1.658,1.577,3.979,4.059,6.542,6.962 c4.472,5.216,9.769,11.92,15.074,18.964c2.07,2.814,4.14,5.628,6.21,8.523c7.949-11.588,21.858-31.959,29.144-42.48 c-1.237-1.658-2.482-3.307-3.72-4.965c-3.316-4.23-6.631-8.281-9.938-12.009c-3.316-3.809-6.462-7.205-9.858-10.432 c-11.426-10.772-24.922-19.545-39.746-25.586c-14.904-6.049-31.222-9.365-48.196-9.365c-17.637,0-34.53,3.566-49.927,10.108 c-23.022,9.688-42.487,25.918-56.316,46.369c-6.873,10.19-12.332,21.527-16.141,33.536C1.989,229.997,0,242.75,0,256.004 c0,17.637,3.558,34.53,10.02,49.846c9.768,23.104,25.998,42.569,46.369,56.397c10.27,6.874,21.535,12.332,33.624,16.141 c12.008,3.728,24.842,5.717,38.088,5.717c16.974,0,33.293-3.316,48.196-9.356c14.824-6.049,28.239-14.824,39.666-25.506l0.08-0.081 c3.397-3.146,6.543-6.631,9.858-10.44c5.709-6.542,11.588-14.071,17.305-21.689c1.157-1.577,2.402-3.154,3.558-4.723 c3.146-4.391,44.307-64.758,47.696-69.642c0.752-1.076,1.577-2.232,2.401-3.396c5.637-7.95,11.928-16.48,17.726-23.928 c2.895-3.728,5.798-7.206,8.281-10.101c2.564-2.984,4.885-5.386,6.542-6.962c7.116-6.704,15.486-12.09,24.673-15.898 c2.24-0.906,4.472-1.649,6.792-2.402c7.286-2.15,14.984-3.307,23.023-3.388c11.013,0.08,21.446,2.232,30.882,6.291 c14.241,5.96,26.42,16.06,34.943,28.732c4.31,6.38,7.706,13.335,10.019,20.782c2.321,7.456,3.566,15.324,3.566,23.605 c0,11.014-2.24,21.446-6.21,30.883c-6.049,14.24-16.149,26.419-28.821,34.942c-6.372,4.31-13.326,7.707-20.782,9.939 c-7.367,2.321-15.316,3.648-23.597,3.648c-10.602,0-20.622-2.07-29.816-5.798c-9.187-3.728-17.557-9.195-24.673-15.899 c-1.658-1.577-3.979-4.059-6.542-6.954c-4.472-5.135-9.776-11.928-15.074-18.963c-2.15-2.815-4.221-5.718-6.291-8.613 c-0.663,0.994-1.326,1.99-2.07,3.065c-13.666,20.039-22.279,32.71-26.994,39.576c1.237,1.658,2.483,3.235,3.72,4.893 c3.316,4.221,6.631,8.281,9.938,12c3.234,3.808,6.462,7.294,9.858,10.44c11.426,10.763,24.923,19.538,39.746,25.587 c14.904,6.04,31.215,9.356,48.197,9.356c17.636,0,34.53-3.558,49.846-10.019c23.103-9.769,42.56-25.999,56.396-46.458 c6.866-10.181,12.421-21.446,16.141-33.536C510.01,282.083,512,269.25,512,256.004C512,238.367,508.442,221.474,501.98,206.15z"/> </g> </svg>
                    <span class="ml-3 font-bold text-xl text-white">SYNDICATE LAW OFFICE</span>
                    </div>
                    <p class="text-gray-400 text-sm max-w-xs">
                        <!-- Updated Years of Experience -->
                        <span class="lang-content active" data-lang="th">บริษัทกฎหมายและที่ปรึกษาครบวงจร ให้บริการด้วยความเชี่ยวชาญและประสบการณ์กว่า 40 ปี</span>
                        <span class="lang-content" data-lang="en">Full-service law and consulting firm with over 40 years of expert experience.</span>
                    </p>
                </div>
                
                <!-- Services Column -->
                <div>
                    <h4 class="text-lg font-semibold mb-4 lang-content active" data-lang="th">บริการ</h4>
                    <h4 class="text-lg font-semibold mb-4 lang-content" data-lang="en">Services</h4>
                    <ul class="space-y-2 text-sm text-gray-400">
                        <!-- Updated Service Links -->
                        <li><a href="#services" class="hover:text-white transition-colors lang-content active" data-lang="th">กฎหมายธุรกิจ</a></li>
                        <li><a href="#services" class="hover:text-white transition-colors lang-content active" data-lang="th">กฎหมายครอบครัว</a></li>
                        <li><a href="#services" class="hover:text-white transition-colors lang-content active" data-lang="th">วีซ่าและใบอนุญาต</a></li>

                        <li><a href="#services" class="hover:text-white transition-colors lang-content" data-lang="en">Business Law</a></li>
                        <li><a href="#services" class="hover:text-white transition-colors lang-content" data-lang="en">Family Law</a></li>
                        <li><a href="#services" class="hover:text-white transition-colors lang-content" data-lang="en">Visa & Work Permit</a></li>
                    </ul>
                </div>
                
                <!-- Company Column -->
                <div>
                    <h4 class="text-lg font-semibold mb-4 lang-content active" data-lang="th">บริษัท</h4>
                    <h4 class="text-lg font-semibold mb-4 lang-content" data-lang="en">Company</h4>
                    <ul class="space-y-2 text-sm text-gray-400">
                        <!-- Updated Company Links -->
                        <li><a href="#team" class="hover:text-white transition-colors lang-content active" data-lang="th">ทีมงาน</a></li>
                        <li><a href="#blog" class="hover:text-white transition-colors lang-content active" data-lang="th">ศูนย์รวมความรู้</a></li>
                        <li><a href="#contact" class="hover:text-white transition-colors lang-content active" data-lang="th">ติดต่อเรา</a></li>

                        <li><a href="#team" class="hover:text-white transition-colors lang-content" data-lang="en">Our Team</a></li>
                        <li><a href="#blog" class="hover:text-white transition-colors lang-content" data-lang="en">Knowledge Center</a></li>
                        <li><a href="#contact" class="hover:text-white transition-colors lang-content" data-lang="en">Contact Us</a></li>
                    </ul>
                </div>

                <!-- Social/Partner Column -->
                 <div>
                 <h4 class="text-lg font-semibold mb-4 lang-content active" data-lang="th">ติดตามเรา</h4>
                 <h4 class="text-lg font-semibold mb-4 lang-content" data-lang="en">Follow Us</h4>
                 <div class="flex space-x-4">
                     <!-- Facebook Link -->
                     <a href="https://www.facebook.com/profile.php?id=61576550558611" target="_blank" rel="noopener noreferrer" class="text-gray-400 hover:text-white transition-colors" aria-label="Facebook">
                         <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 24 24">
                             <path fill-rule="evenodd" d="M22 12c0-5.523-4.477-10-10-10S2 6.477 2 12c0 4.991 3.657 9.128 8.438 9.878v-6.987h-2.54V12h2.54V9.797c0-2.506 1.492-3.89 3.777-3.89 1.094 0 2.238.195 2.238.195v2.46h-1.26c-1.243 0-1.63.771-1.63 1.562V12h2.773l-.443 2.89h-2.33v6.988C18.343 21.128 22 16.991 22 12z" clip-rule="evenodd" />
                         </svg>
                     </a>
                     <!-- Fastwork Link -->
                     <a href="https://fastwork.co/user/netithornb" target="_blank" rel="noopener noreferrer" class="text-gray-400 hover:text-white transition-colors" aria-label="Fastwork">
                        <svg class="w-6 h-6" fill="currentColor" viewBox="0 2 115 100" xmlns="http://www.w3.org/2000/svg">
                            <g>
                                <path d="M95.5,90.3L54.1,73.3c-5.3-2.2-8.5-7.7-7.7-13.4l5.9-44.4c0.5-3.7,3.7-6.5,7.4-6.5c3.7,0,6.9,2.8,7.4,6.5 c0.3,2.1,2.1,3.7,4.2,3.7c0.2,0,0.4,0,0.6,0c2.3-0.3,3.9-2.4,3.6-4.7c-0.5-3.8-2.4-7.3-5.3-9.9s-6.6-3.9-10.5-3.9 c-3.9,0-7.6,1.4-10.5,3.9c-2.9,2.5-4.8,6-5.3,9.9l0,0L38,58.8c-1.3,9.5,4,18.6,12.9,22.3l41.4,17.1c0.5,0.2,1.1,0.3,1.6,0.3 c1.7,0,3.2-1,3.9-2.6C98.7,93.7,97.6,91.2,95.5,90.3z"/>
                                <path d="M46.3,59.9l1.4-10.3l-9.5,7.3L38,58.8c-0.4,2.9-0.2,5.8,0.6,8.5l7.7-5.9C46.2,60.9,46.3,60.4,46.3,59.9z"/>
                                <path d="M113.9,80.4c-0.7-3.8-2.8-7.2-5.9-9.5l0,0L72.5,43.5c-7.6-5.8-18.2-5.8-25.7,0L11.3,70.9 c-1.8,1.4-2.2,4.1-0.8,5.9c1.4,1.8,4.1,2.2,5.9,0.8l35.5-27.3c4.5-3.5,10.9-3.5,15.4,0l35.5,27.3c2.9,2.3,3.8,6.4,1.9,9.6 c-1.9,3.2-5.9,4.6-9.3,3.2c-2.2-0.9-4.6,0.1-5.5,2.3c-0.9,2.2,0.1,4.6,2.3,5.5c1.9,0.8,4,1.2,6.1,1.2c1.7,0,3.5-0.3,5.1-0.8 c3.6-1.2,6.7-3.8,8.6-7.1C114,88.1,114.7,84.1,113.9,80.4z"/>
                                <polygon points="75.8,56.7 87,65.3 84.8,53 74.3,44.9"/>
                                <path d="M66.2,78.3l-11.1,4.6l11.1,4.6l6.1-2.5c1.5-0.6,2.9-1.4,4.2-2.4L66.2,78.3z"/>
                                <path d="M81.3,58.8l-5.9-44.4c-0.3-2.3-2.4-3.9-4.7-3.6c-2.3,0.3-3.9,2.4-3.6,4.7l5.9,44.4c0.8,5.7-2.4,11.2-7.7,13.4 L23.8,90.3c-3.4,1.4-7.4,0.1-9.3-3.2c-1.9-3.2-1-7.4,1.9-9.6c1.8-1.4,2.2-4.1,0.8-5.9c-1.4-1.8-4.1-2.2-5.9-0.8 c-3.1,2.3-5.1,5.7-5.9,9.5c-0.7,3.8-0.1,7.7,1.8,11c1.9,3.3,5,5.9,8.6,7.1c1.7,0.6,3.4,0.8,5.1,0.8c2.1,0,4.1-0.4,6.1-1.2 l41.4-17.1C77.3,77.4,82.6,68.3,81.3,58.8z"/>
                            </g>
                        </svg>
                     </a>
                 </div>
             </div>
            </div>
            
            <div class="border-t border-gray-700 mt-8 pt-8 text-center text-sm text-gray-400">
                <p>&copy; 2024 SYNDICATE LAW OFFICES. All rights reserved.</p>
            </div>
        </div>
    </footer>

    <!-- Admin Login Modal -->
    <div id="admin-login-modal-backdrop" class="modal-backdrop"></div>
    <div id="admin-login-modal" class="modal-content">
        <h3 class="text-xl font-semibold mb-4 lang-content active" data-lang="th">เข้าสู่ระบบผู้ดูแล</h3>
        <h3 class="text-xl font-semibold mb-4 lang-content" data-lang="en">Admin Login</h3>
        <form id="admin-login-form">
            <label for="admin-password" class="block text-sm font-medium text-gray-700 mb-2 lang-content active" data-lang="th">รหัสผ่าน</label>
            <label for="admin-password" class="block text-sm font-medium text-gray-700 mb-2 lang-content" data-lang="en">Password</label>
            <input type="password" id="admin-password" class="w-full px-3 py-2 border border-gray-300 rounded-md mb-4">
            <div class="flex justify-end space-x-2">
                <button type="button" id="cancel-admin-login" class="bg-gray-200 text-gray-700 px-4 py-2 rounded-md hover:bg-gray-300 lang-content active" data-lang="th">ยกเลิก</button>
                <button type="button" id="cancel-admin-login-en" class="bg-gray-200 text-gray-700 px-4 py-2 rounded-md hover:bg-gray-300 lang-content" data-lang="en">Cancel</button>
                
                <button type="submit" class="bg-brand-dark text-white px-4 py-2 rounded-md hover:bg-brand-dark-secondary lang-content active" data-lang="th">เข้าสู่ระบบ</button>
                <button type="submit" class="bg-brand-dark text-white px-4 py-2 rounded-md hover:bg-brand-dark-secondary lang-content" data-lang="en">Login</button>
            </div>
        </form>
    </div>

    <!-- Delete Confirmation Modal -->
    <div id="delete-confirm-modal-backdrop" class="modal-backdrop"></div>
    <div id="delete-confirm-modal" class="modal-content">
        <h3 class="text-xl font-semibold mb-2 lang-content active" data-lang="th">ยืนยันการลบ</h3>
        <h3 class="text-xl font-semibold mb-2 lang-content" data-lang="en">Confirm Deletion</h3>
        <p class="text-gray-600 mb-6 lang-content active" data-lang="th">คุณแน่ใจหรือไม่ว่าต้องการลบความคิดเห็นนี้?</p>
        <p class="text-gray-600 mb-6 lang-content" data-lang="en">Are you sure you want to delete this review?</p>
        <div class="flex justify-end space-x-2">
            <button type="button" id="cancel-delete" class="bg-gray-200 text-gray-700 px-4 py-2 rounded-md hover:bg-gray-300 lang-content active" data-lang="th">ยกเลิก</button>
            <button type="button" id="cancel-delete-en" class="bg-gray-200 text-gray-700 px-4 py-2 rounded-md hover:bg-gray-300 lang-content" data-lang="en">Cancel</button>
            
            <button type="button" id="confirm-delete" class="bg-red-600 text-white px-4 py-2 rounded-md hover:bg-red-700 lang-content active" data-lang="th">ลบ</button>
            <button type="button" id="confirm-delete-en" class="bg-red-600 text-white px-4 py-2 rounded-md hover:bg-red-700 lang-content" data-lang="en">Delete</button>
        </div>
    </div>


    <script>
        // Language switching
        const langButtons = document.querySelectorAll('.lang-btn');
        const langContents = document.querySelectorAll('.lang-content');
        
        langButtons.forEach(button => {
            button.addEventListener('click', () => {
                const lang = button.id.split('-')[1];
                
                // Update button states
                langButtons.forEach(btn => {
                    btn.classList.remove('bg-brand-dark', 'text-white');
                    btn.classList.add('bg-gray-200', 'text-gray-700');
                });
                button.classList.remove('bg-gray-200', 'text-gray-700');
                button.classList.add('bg-brand-dark', 'text-white');
                
                // Update content visibility
                langContents.forEach(content => {
                    content.classList.remove('active');
                    if (content.dataset.lang === lang) {
                        content.classList.add('active');
                    }
                });
            });
        });

        // Mobile menu
        const mobileMenuBtn = document.getElementById('mobile-menu-btn');
        const mobileMenu = document.getElementById('mobile-menu');
        const closeMobileMenu = document.getElementById('close-mobile-menu');
        const mobileNavLinks = document.querySelectorAll('.mobile-nav-link');

        mobileMenuBtn.addEventListener('click', () => {
            mobileMenu.classList.add('open');
        });

        closeMobileMenu.addEventListener('click', () => {
            mobileMenu.classList.remove('open');
        });

        mobileNavLinks.forEach(link => {
            link.addEventListener('click', () => {
                mobileMenu.classList.remove('open');
            });
        });

        // Counter animation
        const counters = document.querySelectorAll('.counter');
        const speed = 200; // Lower number = faster

        const animateCounters = (counter) => {
            const target = +counter.dataset.target;
            const count = +counter.innerText;
            const inc = Math.max(Math.floor(target / speed), 1);

            if (count < target) {
                counter.innerText = Math.min(count + inc, target);
                setTimeout(() => animateCounters(counter), 10);
            } else {
                counter.innerText = target;
            }
        };

        // Intersection Observer for animations
        const observer = new IntersectionObserver((entries) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    if (entry.target.classList.contains('counter')) {
                        animateCounters(entry.target);
                        observer.unobserve(entry.target); // Animate only once
                    }
                }
            });
        }, { threshold: 0.5 }); // Trigger when 50% visible

        counters.forEach(counter => observer.observe(counter));

        // Smooth scrolling for navigation links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                const targetId = this.getAttribute('href');
                const target = document.querySelector(targetId);
                if (target) {
                    // Adjust for fixed header height
                    const headerOffset = 80; // Height of the nav
                    const elementPosition = target.getBoundingClientRect().top;
                    const offsetPosition = elementPosition + window.pageYOffset - headerOffset;

                    window.scrollTo({
                        top: offsetPosition,
                        behavior: 'smooth'
                    });
                }
            });
        });

        // NEW: Service Tab Switching
        const tabButtons = document.querySelectorAll('.tab-button');
        const tabContents = document.querySelectorAll('.tab-content');

        tabButtons.forEach(button => {
            button.addEventListener('click', () => {
                const targetTab = button.dataset.tab;
                
                // Deactivate all buttons and content in the same language group
                const lang = button.dataset.tab.startsWith('th') ? 'th' : 'en';
                document.querySelectorAll(`.tab-button[data-tab^="${lang}-"]`).forEach(btn => btn.classList.remove('active'));
                document.querySelectorAll(`.tab-content[id^="${lang}-"]`).forEach(content => content.classList.remove('active'));

                // Activate the clicked button and target content
                button.classList.add('active');
                document.getElementById(targetTab).classList.add('active');
            });
        });

        // NEW: Accordion Functionality
        document.querySelectorAll('.accordion-button').forEach(button => {
            button.addEventListener('click', () => {
                const content = button.nextElementSibling;
                button.classList.toggle('open');
                if (content.style.maxHeight) {
                    content.style.maxHeight = null;
                } else {
                    content.style.maxHeight = content.scrollHeight + 'px';
                }
            });
        });

        // --- Reviews System ---
        let reviews = JSON.parse(localStorage.getItem('syndicateLawReviews')) || [];
        let isAdminLoggedIn = false;
        let testimonialsVisible = true;
        let reviewToDeleteId = null;

        // Modal Elements
        const adminLoginModalBackdrop = document.getElementById('admin-login-modal-backdrop');
        const adminLoginModal = document.getElementById('admin-login-modal');
        const adminLoginForm = document.getElementById('admin-login-form');
        const cancelAdminLogin = document.getElementById('cancel-admin-login');
        const cancelAdminLoginEn = document.getElementById('cancel-admin-login-en');

        const deleteConfirmModalBackdrop = document.getElementById('delete-confirm-modal-backdrop');
        const deleteConfirmModal = document.getElementById('delete-confirm-modal');
        const cancelDelete = document.getElementById('cancel-delete');
        const cancelDeleteEn = document.getElementById('cancel-delete-en');
        const confirmDelete = document.getElementById('confirm-delete');
        const confirmDeleteEn = document.getElementById('confirm-delete-en');

        // Star rating functionality
        function setupStarRating(containerSelector, valueInputId) {
            const starContainer = document.querySelector(containerSelector);
            if (!starContainer) return;
            const starButtons = starContainer.querySelectorAll('.star-btn, .star-btn-en');
            const ratingInput = document.getElementById(valueInputId);
            
            starButtons.forEach(star => {
                star.addEventListener('click', (e) => {
                    e.preventDefault();
                    const rating = parseInt(star.dataset.rating);
                    ratingInput.value = rating;
                    
                    starButtons.forEach((s, i) => {
                        if (i < rating) {
                            s.classList.remove('text-gray-300');
                            s.classList.add('text-yellow-400');
                        } else {
                            s.classList.remove('text-yellow-400');
                            s.classList.add('text-gray-300');
                        }
                    });
                });
            });
        }

        setupStarRating('#review-form', 'rating-value');
        setupStarRating('#review-form-en', 'rating-value-en');

        // Review form submission
        function setupReviewForm(formId, isEnglish = false) {
            const form = document.getElementById(formId);
            if (!form) return;
            form.addEventListener('submit', (e) => {
                e.preventDefault();
                
                const formData = new FormData(form);
                const review = {
                    id: Date.now(),
                    customerId: formData.get('customerId'),
                    customerName: formData.get('customerName'),
                    customerPosition: formData.get('customerPosition') || (isEnglish ? 'Customer' : 'ลูกค้า'),
                    rating: parseInt(formData.get('rating')),
                    reviewText: formData.get('reviewText'),
                    date: new Date().toLocaleDateString(isEnglish ? 'en-US' : 'th-TH'),
                    language: isEnglish ? 'en' : 'th'
                };
                
                if (!review.rating) {
                    const message = isEnglish ? 'Please select a rating' : 'กรุณาเลือกคะแนน';
                    showNotification(message, 'error');
                    return;
                }
                
                reviews.push(review);
                localStorage.setItem('syndicateLawReviews', JSON.stringify(reviews));
                
                const message = isEnglish ? 'Review submitted successfully!' : 'ส่งความคิดเห็นเรียบร้อยแล้ว!';
                showNotification(message, 'success');
                
                form.reset();
                // Reset star ratings
                const stars = form.querySelectorAll('.star-btn, .star-btn-en');
                stars.forEach(star => {
                    star.classList.remove('text-yellow-400');
                    star.classList.add('text-gray-300');
                });
                
                displayReviews();
            });
        }

        setupReviewForm('review-form', false);
        setupReviewForm('review-form-en', true);

        // Display reviews
        function displayReviews() {
            const thContainer = document.getElementById('reviews-container');
            const enContainer = document.getElementById('reviews-container-en');
            if (!thContainer || !enContainer) return;
            
            const thReviews = reviews.filter(r => r.language === 'th');
            const enReviews = reviews.filter(r => r.language === 'en');
            
            thContainer.innerHTML = thReviews.map(review => createReviewCard(review, false)).join('');
            enContainer.innerHTML = enReviews.map(review => createReviewCard(review, true)).join('');
        }

        // Create review card HTML
        function createReviewCard(review, isEnglish) {
            const stars = '⭐'.repeat(review.rating);
            const deleteBtn = isAdminLoggedIn ? 
                `<button onclick="requestDeleteReview(${review.id})" class="absolute top-2 right-2 bg-red-500 text-white rounded-full w-6 h-6 flex items-center justify-center text-xs hover:bg-red-600 transition-colors">×</button>` : '';
            
            return `
                <div class="review-card bg-white p-6 rounded-xl shadow-md relative">
                    ${deleteBtn}
                    <div class="flex items-center mb-4">
                        <div class="w-12 h-12 bg-brand-dark-secondary rounded-full flex items-center justify-center text-white font-bold mr-4">
                            ${review.customerName.charAt(0).toUpperCase()}
                        </div>
                        <div>
                            <h4 class="font-bold text-gray-900">${review.customerName}</h4>
                            <p class="text-gray-600 text-sm">${review.customerPosition}</p>
                            <p class="text-gray-500 text-xs">${isEnglish ? 'ID:' : 'รหัส:'} ${review.customerId}</p>
                        </div>
                    </div>
                    <div class="flex mb-4">
                        <span class="star-rating">${stars}</span>
                    </div>
                    <p class="text-gray-700 italic">"${review.reviewText}"</p>
                    <p class="text-gray-500 text-sm mt-4">${review.date}</p>
                </div>
            `;
        }

        // --- NEW MODAL-BASED Admin Flow ---

        // Open Admin Login Modal
        document.getElementById('admin-login-btn').addEventListener('click', () => {
            adminLoginModalBackdrop.classList.add('open');
            adminLoginModal.classList.add('open');
        });

        // Close Admin Login Modal
        function closeAdminLoginModal() {
            adminLoginModalBackdrop.classList.remove('open');
            adminLoginModal.classList.remove('open');
        }
        cancelAdminLogin.addEventListener('click', closeAdminLoginModal);
        cancelAdminLoginEn.addEventListener('click', closeAdminLoginModal);
        adminLoginModalBackdrop.addEventListener('click', closeAdminLoginModal);

        // Handle Admin Login
        adminLoginForm.addEventListener('submit', (e) => {
            e.preventDefault();
            const password = document.getElementById('admin-password').value;
            if (password === 'admin123') {
                isAdminLoggedIn = true;
                document.getElementById('admin-controls').style.display = 'block';
                displayReviews();
                showNotification('เข้าสู่ระบบผู้ดูแลเรียบร้อย', 'success');
                closeAdminLoginModal();
                document.getElementById('admin-password').value = '';
            } else {
                showNotification('รหัสผ่านไม่ถูกต้อง', 'error');
            }
        });

        // Open Delete Confirm Modal
        function requestDeleteReview(reviewId) {
            reviewToDeleteId = reviewId;
            deleteConfirmModalBackdrop.classList.add('open');
            deleteConfirmModal.classList.add('open');
        }

        // Close Delete Confirm Modal
        function closeDeleteConfirmModal() {
            deleteConfirmModalBackdrop.classList.remove('open');
            deleteConfirmModal.classList.remove('open');
            reviewToDeleteId = null;
        }
        cancelDelete.addEventListener('click', closeDeleteConfirmModal);
        cancelDeleteEn.addEventListener('click', closeDeleteConfirmModal);
        deleteConfirmModalBackdrop.addEventListener('click', closeDeleteConfirmModal);

        // Handle Delete Confirmation
        function handleDelete() {
            if (reviewToDeleteId) {
                reviews = reviews.filter(r => r.id !== reviewToDeleteId);
                localStorage.setItem('syndicateLawReviews', JSON.stringify(reviews));
                displayReviews();
                showNotification('ลบความคิดเห็นเรียบร้อยแล้ว', 'success');
                closeDeleteConfirmModal();
            }
        }
        confirmDelete.addEventListener('click', handleDelete);
        confirmDeleteEn.addEventListener('click', handleDelete);


        // Toggle testimonials visibility
        document.getElementById('toggle-testimonials').addEventListener('click', () => {
            const sections = document.querySelectorAll('#testimonials-section, #testimonials-section-en');
            const toggleText = document.getElementById('toggle-text');
            
            testimonialsVisible = !testimonialsVisible;
            
            sections.forEach(section => {
                section.style.display = testimonialsVisible ? 'block' : 'none';
            });
            
            toggleText.textContent = testimonialsVisible ? 'ซ่อนส่วนความคิดเห็น' : 'แสดงส่วนความคิดเห็น';
        });

        // Notification system
        function showNotification(message, type = 'info') {
            const notification = document.createElement('div');
            notification.className = `fixed top-24 right-4 z-[9999] px-6 py-3 rounded-md text-white font-semibold transition-all duration-300 ${
                type === 'success' ? 'bg-green-500' : 
                type === 'error' ? 'bg-red-500' : 'bg-blue-500'
            }`;
            notification.textContent = message;
            
            document.body.appendChild(notification);
            
            setTimeout(() => {
                notification.style.opacity = '0';
                notification.style.transform = 'translateX(100%)';
                setTimeout(() => {
                    if (document.body.contains(notification)) {
                        document.body.removeChild(notification);
                    }
                }, 300);
            }, 3000);
        }

        // Initialize reviews display on load
        displayReviews();

        // Contact form submission
        document.querySelectorAll('#contact-form-th, #contact-form-en').forEach(form => {
            form.addEventListener('submit', (e) => {
                e.preventDefault();
                const isEnglish = form.id.includes('-en');
                const message = isEnglish ? 'Message sent successfully! We will contact you soon.' : 'ข้อความถูกส่งเรียบร้อยแล้ว เราจะติดต่อกลับในเร็วๆ นี้';
                showNotification(message, 'success');
                form.reset();
            });
        });
    </script>
</body>
</html>


