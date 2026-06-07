<!DOCTYPE html>
<html dir="rtl" lang="he-IL" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>שיש מילניום - משטחי שיש מעוצבים | קטלוג וצור קשר</title>
    <meta name="description" content="חברתינו עוסקת ביבוא, יצוא, ייצור ושיווק של משטחי שיש מעוצבים, ביניהם שיש למטבחים ולאמבט, מסוג משטחי אבן טבעית, גרניט פורצלן ומשטחי קוורץ של החברות המובילות בעולם.">
    
    <!-- Fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Assistant:wght@200;300;400;500;600;700;800&family=Heebo:wght@100;300;400;500;700;900&display=swap" rel="stylesheet">
    
    <!-- Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Heebo', 'Assistant', 'sans-serif'],
                        serif: ['Assistant', 'sans-serif'],
                    },
                    colors: {
                        brand: {
                            50: '#f9f9f9',
                            100: '#f2f2f2',
                            900: '#0a0a0a',
                            950: '#050505',
                        }
                    },
                    transitionDuration: {
                        '800': '800ms',
                        '1500': '1500ms',
                    }
                }
            }
        }
    </script>
    
    <style>
        /* Custom Styles for Premium Mercedes-like Feel */
        body {
            -webkit-font-smoothing: antialiased;
            -moz-osx-font-smoothing: grayscale;
        }
        
        .nav-scrolled {
            background-color: rgba(10, 10, 10, 0.95);
            backdrop-filter: blur(10px);
            border-bottom: 1px solid rgba(255,255,255,0.1);
        }

        .btn-outline {
            position: relative;
            overflow: hidden;
            transition: all 0.4s ease;
        }
        
        .btn-outline::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-color: currentColor;
            transform: scaleX(0);
            transform-origin: right;
            transition: transform 0.4s cubic-bezier(0.19, 1, 0.22, 1);
            z-index: -1;
        }

        .btn-outline:hover::before {
            transform: scaleX(1);
            transform-origin: left;
        }

        .btn-outline:hover {
            color: #fff !important;
        }
        
        .btn-outline.dark-hover:hover {
            color: #000 !important;
        }

        .reveal {
            opacity: 0;
            transform: translateY(40px);
            transition: all 1s cubic-bezier(0.25, 0.46, 0.45, 0.94);
        }

        .reveal.active {
            opacity: 1;
            transform: translateY(0);
        }

        /* Image mask for logo to blend with dark backgrounds */
        .logo-blend {
            mix-blend-mode: screen;
            filter: grayscale(100%) contrast(1.2);
        }

        /* Form Inputs Premium Styling */
        .premium-input {
            width: 100%;
            background: transparent;
            border: none;
            border-bottom: 1px solid rgba(255,255,255,0.3);
            color: white;
            padding: 12px 0;
            font-family: 'Assistant', sans-serif;
            font-weight: 300;
            transition: all 0.3s ease;
        }
        .premium-input:focus {
            outline: none;
            border-bottom: 1px solid white;
        }
        .premium-input::placeholder {
            color: rgba(255,255,255,0.5);
        }
        
        /* Product Card Zoom */
        .product-card img {
            transition: transform 1.2s cubic-bezier(0.25, 0.46, 0.45, 0.94);
        }
        .product-card:hover img {
            transform: scale(1.08);
        }

        /* Floating WhatsApp Button */
        .whatsapp-float {
            position: fixed;
            bottom: 30px;
            left: 30px;
            background-color: #25d366;
            color: #FFF;
            border-radius: 50px;
            text-align: center;
            font-size: 32px;
            box-shadow: 0px 4px 20px rgba(37, 211, 102, 0.4);
            z-index: 100;
            display: flex;
            align-items: center;
            justify-content: center;
            width: 64px;
            height: 64px;
            transition: all 0.3s ease;
        }
        .whatsapp-float:hover {
            transform: scale(1.1);
            color: white;
            box-shadow: 0px 6px 25px rgba(37, 211, 102, 0.6);
        }
        
        /* TikTok Section Premium Styling */
        .tiktok-preview {
            background: linear-gradient(45deg, #050505, #111111);
            position: relative;
            overflow: hidden;
        }
        .tiktok-preview::before {
            content: '';
            position: absolute;
            top: 0; left: 0; right: 0; bottom: 0;
            background: url('data:image/svg+xml;utf8,<svg width="20" height="20" xmlns="http://www.w3.org/2000/svg"><circle cx="2" cy="2" r="1" fill="rgba(255,255,255,0.03)"/></svg>');
            z-index: 0;
        }
    </style>
</head>
<body id="home" class="bg-brand-50 text-brand-900 overflow-x-hidden selection:bg-black selection:text-white">

    <!-- Navigation -->
    <header id="navbar" class="fixed w-full top-0 z-50 transition-all duration-500 py-4 text-white">
        <div class="max-w-7xl mx-auto px-6 lg:px-12 flex justify-between items-center">
            
            <!-- Mobile Menu Button -->
            <button id="mobile-menu-btn" class="lg:hidden text-2xl focus:outline-none">
                <i class="fas fa-bars"></i>
            </button>

            <!-- Links (Desktop) -->
            <nav class="hidden lg:flex space-x-8 space-x-reverse items-center text-sm font-medium tracking-wide">
                <a href="#home" class="hover:text-gray-300 transition-colors border-b border-transparent hover:border-white pb-1">בית</a>
                <a href="#about" class="hover:text-gray-300 transition-colors border-b border-transparent hover:border-white pb-1">אודות</a>
                <a href="#catalog" class="hover:text-gray-300 transition-colors border-b border-transparent hover:border-white pb-1">קטלוג מלא</a>
                <a href="#services" class="hover:text-gray-300 transition-colors border-b border-transparent hover:border-white pb-1">שירותים</a>
                <a href="#contact" class="hover:text-gray-300 transition-colors border-b border-transparent hover:border-white pb-1">יצירת קשר</a>
            </nav>

            <!-- Logo -->
            <a href="#home" class="block relative z-10 w-32 h-16 overflow-hidden flex items-center justify-center bg-white/10 rounded backdrop-blur-sm px-2">
                <img src="https://m-marble.co.il/wp-content/uploads/2023/08/cropped-logo.jpeg" alt="שיש מילניום" class="object-contain w-full h-full">
            </a>
        </div>

        <!-- Mobile Menu Overlay -->
        <div id="mobile-menu" class="fixed inset-0 bg-brand-950 text-white flex flex-col justify-center items-center space-y-8 text-2xl font-light transform translate-x-full transition-transform duration-500 lg:hidden">
            <button id="close-menu-btn" class="absolute top-8 left-8 text-3xl">
                <i class="fas fa-times"></i>
            </button>
            <a href="#home" class="mobile-link hover:text-gray-400">בית</a>
            <a href="#about" class="mobile-link hover:text-gray-400">אודות</a>
            <a href="#catalog" class="mobile-link hover:text-gray-400">קטלוג מלא</a>
            <a href="#services" class="mobile-link hover:text-gray-400">שירותים</a>
            <a href="#contact" class="mobile-link hover:text-gray-400">יצירת קשר</a>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="relative h-screen w-full flex items-end justify-start overflow-hidden bg-black">
        <div class="absolute inset-0 z-0">
            <img src="https://m-marble.co.il/wp-content/uploads/2023/10/DSCF7580.jpg" alt="משטחי שיש מעוצבים" class="w-full h-full object-cover object-center scale-105 animate-[pulse_20s_ease-in-out_infinite_alternate] opacity-70">
            <div class="absolute inset-0 bg-gradient-to-t from-black/80 via-black/30 to-transparent"></div>
        </div>
        
        <div class="relative z-10 w-full max-w-7xl mx-auto px-6 lg:px-12 pb-24 lg:pb-32 reveal">
            <span class="block text-gray-300 text-sm md:text-base tracking-widest uppercase mb-4 font-light">יצירת מופת למטבח שלך</span>
            <h1 class="text-5xl md:text-7xl lg:text-8xl font-bold text-white leading-tight mb-8">
                שיש מילניום.<br>
                <span class="font-light text-gray-200">משטחי שיש מעוצבים.</span>
            </h1>
            <div class="flex flex-col sm:flex-row gap-4">
                <a href="#catalog" class="inline-flex items-center justify-center px-8 py-4 border border-white text-white font-medium tracking-wide btn-outline hover:text-black hover:bg-white text-lg w-full sm:w-auto">
                    צפה בקטלוג המלא
                </a>
                <a href="#contact" class="inline-flex items-center justify-center px-8 py-4 bg-white text-black font-medium tracking-wide transition duration-300 hover:bg-gray-200 text-lg w-full sm:w-auto">
                    צור קשר לייעוץ
                </a>
            </div>
        </div>
    </section>

    <!-- Brand Story (About) -->
    <section id="about" class="bg-brand-950 text-white overflow-hidden">
        <div class="flex flex-col lg:flex-row">
            <!-- Image Side -->
            <div class="w-full lg:w-1/2 relative h-[50vh] lg:h-auto">
                <img src="https://m-marble.co.il/wp-content/uploads/2023/10/DSCF7567.jpg" alt="אודות שיש מילניום" class="absolute inset-0 w-full h-full object-cover opacity-80">
            </div>
            
            <!-- Text Side -->
            <div class="w-full lg:w-1/2 py-20 px-6 lg:py-32 lg:px-20 xl:px-32 flex flex-col justify-center reveal">
                <span class="uppercase tracking-widest text-xs text-gray-400 mb-6 font-semibold">המורשת שלנו</span>
                <h2 class="text-4xl md:text-5xl font-bold mb-8 leading-tight">3 דורות של אהבה למקצוע.</h2>
                <div class="space-y-6 text-gray-300 text-lg font-light leading-relaxed">
                    <p>
                        חברת שיש מילניום נוסדה בשנת 1985 ע"י דוד נחמיאס וכיום מונה 3 דורות לשיש למטבחים. האהבה למקצוע עוברת בגנים. חברתינו עוסקת ביבוא, יצוא, ייצור ושיווק של משטחי שיש מעוצבים, ביניהם שיש למטבחים ולאמבט, מסוג משטחי אבן טבעית, גרניט פורצלן ומשטחי קוורץ של החברות המובילות בעולם.
                    </p>
                    <p>
                        במילניום תקבלו מעטפת משפחתית שתלווה אתכם בכל תהליך השיש מרגע הבחירה והעיצוב ועד לרגע ההתקנה. אנו מתמחים בעבודות ייחודיות ואומנותיות, משווקים למוסדות, משרד הביטחון, לבתי מלון ולצרכנים פרטיים.
                    </p>
                    <p>
                        מבצעים גם עבודות לפי תוכניות אדריכליות במקום, אולם תצוגה מרהיב, מבחר עצום של חומרים וצוות ייעוץ מקצועי ואדיב שיעזור לכם להבין ולדייק את הצורך שלכם. אתם מוזמנים להגיע אלינו, להתרשם מהחומרים ומהמוצרים, לקבל ייעוץ מקצועי בכל נושא ולבחור את המוצר הטוב ביותר עבורכם.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- Full Catalog Section -->
    <section id="catalog" class="py-24 lg:py-32 bg-white">
        <div class="max-w-7xl mx-auto px-6 lg:px-12">
            <div class="mb-16 flex flex-col md:flex-row justify-between items-end gap-6 reveal">
                <div>
                    <span class="text-gray-500 uppercase tracking-widest text-sm font-semibold mb-2 block">הקולקציה</span>
                    <h2 class="text-4xl md:text-5xl font-light">קטלוג מוצרים.</h2>
                </div>
                <p class="text-gray-500 text-lg max-w-xl font-light">
                    גלו את מגוון המשטחים שלנו - מפורצלן עמיד, דרך קוורץ מודרני ועד לאבן טבעית יוקרתית. כל משטח הוא יצירת אמנות.
                </p>
            </div>

            <!-- Catalog Grid -->
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-10">
                
                <!-- Catalog Item 1 -->
                <div class="product-card group cursor-pointer reveal">
                    <div class="overflow-hidden aspect-[4/3] bg-gray-100 relative">
                        <img src="https://m-marble.co.il/wp-content/uploads/2023/10/DSCF7602.jpg" alt="פורצלן קלקטה" class="w-full h-full object-cover">
                        <div class="absolute inset-0 bg-black/10 group-hover:bg-transparent transition-colors duration-500"></div>
                        <span class="absolute top-4 right-4 bg-black text-white text-xs px-3 py-1 uppercase tracking-wider font-medium">פורצלן</span>
                    </div>
                    <div class="mt-6">
                        <h3 class="text-2xl font-bold text-gray-900 mb-2">קולקציית פורצלן אקסקלוסיבית</h3>
                        <p class="text-gray-500 font-light text-sm mb-4">עמידות לחום, שריטות וכתמים. מראה שיש טבעי עם תחזוקה אפסית.</p>
                        <a href="#contact" class="text-sm border-b border-black pb-1 font-medium hover:text-gray-600 transition-colors">לפרטים נוספים <i class="fas fa-arrow-left ml-1 text-xs"></i></a>
                    </div>
                </div>

                <!-- Catalog Item 2 -->
                <div class="product-card group cursor-pointer reveal" style="transition-delay: 100ms;">
                    <div class="overflow-hidden aspect-[4/3] bg-gray-100 relative">
                        <img src="https://m-marble.co.il/wp-content/uploads/2023/10/DSCF7604.jpg" alt="קוורץ פרימיום" class="w-full h-full object-cover">
                        <div class="absolute inset-0 bg-black/10 group-hover:bg-transparent transition-colors duration-500"></div>
                        <span class="absolute top-4 right-4 bg-black text-white text-xs px-3 py-1 uppercase tracking-wider font-medium">קוורץ</span>
                    </div>
                    <div class="mt-6">
                        <h3 class="text-2xl font-bold text-gray-900 mb-2">משטחי קוורץ מעוצבים</h3>
                        <p class="text-gray-500 font-light text-sm mb-4">חוזק הנדסי המשלב קריסטלי קוורץ טבעיים. מושלם למטבח המודרני והפעיל.</p>
                        <a href="#contact" class="text-sm border-b border-black pb-1 font-medium hover:text-gray-600 transition-colors">לפרטים נוספים <i class="fas fa-arrow-left ml-1 text-xs"></i></a>
                    </div>
                </div>

                <!-- Catalog Item 3 -->
                <div class="product-card group cursor-pointer reveal" style="transition-delay: 200ms;">
                    <div class="overflow-hidden aspect-[4/3] bg-gray-100 relative">
                        <img src="https://m-marble.co.il/wp-content/uploads/2023/10/DSCF7580.jpg" alt="אבן טבעית" class="w-full h-full object-cover">
                        <div class="absolute inset-0 bg-black/10 group-hover:bg-transparent transition-colors duration-500"></div>
                        <span class="absolute top-4 right-4 bg-black text-white text-xs px-3 py-1 uppercase tracking-wider font-medium">אבן טבעית</span>
                    </div>
                    <div class="mt-6">
                        <h3 class="text-2xl font-bold text-gray-900 mb-2">אבן טבעית וגרניט</h3>
                        <p class="text-gray-500 font-light text-sm mb-4">יצירת אמנות חד פעמית של הטבע. מראה עוצר נשימה ויוקרה חסרת פשרות.</p>
                        <a href="#contact" class="text-sm border-b border-black pb-1 font-medium hover:text-gray-600 transition-colors">לפרטים נוספים <i class="fas fa-arrow-left ml-1 text-xs"></i></a>
                    </div>
                </div>

                <!-- Catalog Item 4 (Placeholder styling) -->
                <div class="product-card group cursor-pointer reveal">
                    <div class="overflow-hidden aspect-[4/3] bg-gray-200 relative flex items-center justify-center">
                        <img src="https://placehold.co/800x600/e2e8f0/475569?text=Onyx+Collection" alt="אוניקס" class="w-full h-full object-cover mix-blend-multiply">
                        <span class="absolute top-4 right-4 bg-black text-white text-xs px-3 py-1 uppercase tracking-wider font-medium">פרימיום</span>
                    </div>
                    <div class="mt-6">
                        <h3 class="text-2xl font-bold text-gray-900 mb-2">קולקציית אוניקס</h3>
                        <p class="text-gray-500 font-light text-sm mb-4">שקיפות מרהיבה וטקסטורות עמוקות המאפשרות שילוב תאורה נסתרת מרשימה.</p>
                        <a href="#contact" class="text-sm border-b border-black pb-1 font-medium hover:text-gray-600 transition-colors">לפרטים נוספים <i class="fas fa-arrow-left ml-1 text-xs"></i></a>
                    </div>
                </div>

                <!-- Catalog Item 5 (Placeholder styling) -->
                <div class="product-card group cursor-pointer reveal" style="transition-delay: 100ms;">
                    <div class="overflow-hidden aspect-[4/3] bg-gray-800 relative flex items-center justify-center">
                         <img src="https://placehold.co/800x600/1e293b/94a3b8?text=Dark+Matte" alt="גימור מט" class="w-full h-full object-cover mix-blend-overlay opacity-80">
                        <span class="absolute top-4 right-4 bg-white text-black text-xs px-3 py-1 uppercase tracking-wider font-medium">חדש</span>
                    </div>
                    <div class="mt-6">
                        <h3 class="text-2xl font-bold text-gray-900 mb-2">קולקציית מט כהה</h3>
                        <p class="text-gray-500 font-light text-sm mb-4">המראה המודרני והתעשייתי. גימורי מט אלגנטיים במניפת גוונים כהים ועמוקים.</p>
                        <a href="#contact" class="text-sm border-b border-black pb-1 font-medium hover:text-gray-600 transition-colors">לפרטים נוספים <i class="fas fa-arrow-left ml-1 text-xs"></i></a>
                    </div>
                </div>

                <!-- Catalog Item 6 (Placeholder styling) -->
                <div class="product-card group cursor-pointer reveal" style="transition-delay: 200ms;">
                    <div class="overflow-hidden aspect-[4/3] bg-gray-100 relative flex items-center justify-center">
                         <img src="https://placehold.co/800x600/f8fafc/64748b?text=Calacatta+Gold" alt="קלקטה גולד" class="w-full h-full object-cover mix-blend-multiply">
                        <span class="absolute top-4 right-4 bg-black text-white text-xs px-3 py-1 uppercase tracking-wider font-medium">קלאסי</span>
                    </div>
                    <div class="mt-6">
                        <h3 class="text-2xl font-bold text-gray-900 mb-2">דגמי קלקטה קלאסיים</h3>
                        <p class="text-gray-500 font-light text-sm mb-4">רקע לבן צחור עם גידים דרמטיים בגווני אפור וזהב. מראה על-זמני יוקרתי.</p>
                        <a href="#contact" class="text-sm border-b border-black pb-1 font-medium hover:text-gray-600 transition-colors">לפרטים נוספים <i class="fas fa-arrow-left ml-1 text-xs"></i></a>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- Services Section -->
    <section id="services" class="py-24 bg-brand-50 border-t border-gray-200">
        <div class="max-w-7xl mx-auto px-6 lg:px-12">
            <div class="text-center mb-16 reveal">
                <h2 class="text-4xl font-light">השירותים שלנו.</h2>
                <p class="mt-4 text-gray-500 max-w-2xl mx-auto">מעטפת שלמה ומקצועית, משלב התכנון והייעוץ, דרך חיתוך ועיבוד טכנולוגי מתקדם, ועד להתקנה מושלמת בבית הלקוח.</p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-3 gap-8 text-center">
                <div class="bg-white p-10 shadow-sm reveal">
                    <div class="text-4xl mb-6 text-gray-800"><i class="fas fa-comments"></i></div>
                    <h3 class="text-xl font-bold mb-3">ייעוץ ותכנון אישי</h3>
                    <p class="text-gray-500 font-light text-sm">ליווי צמוד באולם התצוגה, התאמת החומרים לצרכים הייחודיים שלכם ולסגנון העיצובי.</p>
                </div>
                <div class="bg-white p-10 shadow-sm reveal" style="transition-delay: 100ms;">
                    <div class="text-4xl mb-6 text-gray-800"><i class="fas fa-cogs"></i></div>
                    <h3 class="text-xl font-bold mb-3">עיבוד וייצור מתקדם</h3>
                    <p class="text-gray-500 font-light text-sm">שימוש בטכנולוגיות חיתוך ועיבוד מהמתקדמות בעולם לרמת גימור אבסולוטית וללא פשרות.</p>
                </div>
                <div class="bg-white p-10 shadow-sm reveal" style="transition-delay: 200ms;">
                    <div class="text-4xl mb-6 text-gray-800"><i class="fas fa-tools"></i></div>
                    <h3 class="text-xl font-bold mb-3">התקנה מקצועית</h3>
                    <p class="text-gray-500 font-light text-sm">צוות מתקינים מיומן ומנוסה הדואג להרכבה מדויקת, נקייה ובטוחה אצלכם בבית.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- TikTok Preview Section -->
    <section class="tiktok-preview py-24 text-white relative z-10 border-t border-gray-800">
        <div class="max-w-7xl mx-auto px-6 lg:px-12 relative z-10">
            <div class="flex flex-col md:flex-row justify-between items-end gap-8 mb-16 reveal">
                <div>
                    <span class="text-[#00f2fe] uppercase tracking-widest text-sm font-semibold mb-2 flex items-center gap-2">
                        <i class="fab fa-tiktok"></i> עקבו אחרינו
                    </span>
                    <h2 class="text-4xl md:text-5xl font-light">הצצה לעשייה שלנו.</h2>
                </div>
                <a href="https://www.tiktok.com/@milenummarble" target="_blank" rel="noopener noreferrer" class="inline-flex items-center justify-center px-6 py-3 border border-white text-white font-medium tracking-wide btn-outline hover:text-black hover:bg-white transition-all">
                    לעמוד הטיקטוק הרשמי <i class="fab fa-tiktok mr-3"></i>
                </a>
            </div>

            <!-- Mockup TikTok Grid -->
            <div class="grid grid-cols-2 md:grid-cols-4 gap-4 reveal" style="transition-delay: 100ms;">
                <!-- Video 1 -->
                <a href="https://www.tiktok.com/@milenummarble" target="_blank" rel="noopener noreferrer" class="group relative aspect-[9/16] bg-gray-900 rounded-lg overflow-hidden block">
                    <img src="https://m-marble.co.il/wp-content/uploads/2023/10/DSCF7602.jpg" alt="TikTok Preview" class="w-full h-full object-cover opacity-70 group-hover:opacity-100 transition-opacity duration-500 group-hover:scale-105">
                    <div class="absolute inset-0 bg-gradient-to-t from-black/80 via-transparent to-transparent"></div>
                    <div class="absolute bottom-4 left-4 right-4 flex justify-between items-center text-white">
                        <span class="text-xs font-medium"><i class="fas fa-play text-white/80 mr-1"></i> 12.4K</span>
                        <i class="fab fa-tiktok text-white/50 group-hover:text-[#00f2fe] transition-colors"></i>
                    </div>
                </a>
                <!-- Video 2 -->
                <a href="https://www.tiktok.com/@milenummarble" target="_blank" rel="noopener noreferrer" class="group relative aspect-[9/16] bg-gray-900 rounded-lg overflow-hidden block mt-8">
                    <img src="https://m-marble.co.il/wp-content/uploads/2023/10/DSCF7580.jpg" alt="TikTok Preview" class="w-full h-full object-cover opacity-70 group-hover:opacity-100 transition-opacity duration-500 group-hover:scale-105">
                    <div class="absolute inset-0 bg-gradient-to-t from-black/80 via-transparent to-transparent"></div>
                    <div class="absolute bottom-4 left-4 right-4 flex justify-between items-center text-white">
                        <span class="text-xs font-medium"><i class="fas fa-play text-white/80 mr-1"></i> 8.2K</span>
                        <i class="fab fa-tiktok text-white/50 group-hover:text-[#00f2fe] transition-colors"></i>
                    </div>
                </a>
                <!-- Video 3 -->
                <a href="https://www.tiktok.com/@milenummarble" target="_blank" rel="noopener noreferrer" class="group relative aspect-[9/16] bg-gray-900 rounded-lg overflow-hidden block">
                    <img src="https://m-marble.co.il/wp-content/uploads/2023/10/DSCF7604.jpg" alt="TikTok Preview" class="w-full h-full object-cover opacity-70 group-hover:opacity-100 transition-opacity duration-500 group-hover:scale-105">
                    <div class="absolute inset-0 bg-gradient-to-t from-black/80 via-transparent to-transparent"></div>
                    <div class="absolute bottom-4 left-4 right-4 flex justify-between items-center text-white">
                        <span class="text-xs font-medium"><i class="fas fa-play text-white/80 mr-1"></i> 15.1K</span>
                        <i class="fab fa-tiktok text-white/50 group-hover:text-[#00f2fe] transition-colors"></i>
                    </div>
                </a>
                <!-- Video 4 -->
                <a href="https://www.tiktok.com/@milenummarble" target="_blank" rel="noopener noreferrer" class="group relative aspect-[9/16] bg-gray-900 rounded-lg overflow-hidden block mt-8">
                    <img src="https://m-marble.co.il/wp-content/uploads/2023/10/DSCF7567.jpg" alt="TikTok Preview" class="w-full h-full object-cover opacity-70 group-hover:opacity-100 transition-opacity duration-500 group-hover:scale-105">
                    <div class="absolute inset-0 bg-gradient-to-t from-black/80 via-transparent to-transparent"></div>
                    <div class="absolute bottom-4 left-4 right-4 flex justify-between items-center text-white">
                        <span class="text-xs font-medium"><i class="fas fa-play text-white/80 mr-1"></i> 22.3K</span>
                        <i class="fab fa-tiktok text-white/50 group-hover:text-[#00f2fe] transition-colors"></i>
                    </div>
                </a>
            </div>
        </div>
    </section>

    <!-- Full Contact & Details Section -->
    <section id="contact" class="bg-black text-white relative overflow-hidden">
        <div class="absolute inset-0 bg-[url('https://m-marble.co.il/wp-content/uploads/2023/10/DSCF7580.jpg')] bg-cover bg-center opacity-10 grayscale"></div>
        
        <div class="relative z-10 max-w-7xl mx-auto px-6 lg:px-12 py-24 lg:py-32">
            <div class="grid grid-cols-1 lg:grid-cols-2 gap-16 lg:gap-24">
                
                <!-- Contact Details -->
                <div class="reveal">
                    <span class="text-gray-400 uppercase tracking-widest text-sm font-semibold mb-2 block">יצירת קשר</span>
                    <h2 class="text-4xl md:text-6xl font-light mb-8">נשמח לעמוד<br>לשירותכם.</h2>
                    <p class="text-gray-400 font-light text-lg mb-12">
                        צוות היועצים שלנו ממתין לכם באולם התצוגה המרהיב שלנו, לעזור לכם לדייק את הצורך שלכם ולבחור את משטח החלומות למטבח שלכם.
                    </p>

                    <div class="space-y-8">
                        <!-- Phone -->
                        <div class="flex items-start gap-4">
                            <div class="w-12 h-12 rounded-full border border-gray-600 flex items-center justify-center shrink-0">
                                <i class="fas fa-phone text-lg"></i>
                            </div>
                            <div>
                                <h4 class="font-bold text-lg mb-1">טלפון / נייד</h4>
                                <div class="flex flex-col gap-1">
                                    <a href="tel:048402101" class="text-gray-400 hover:text-white transition-colors font-light dir-ltr inline-block">04-8402101</a>
                                    <a href="tel:0543034582" class="text-gray-400 hover:text-white transition-colors font-light dir-ltr inline-block">054-3034582</a>
                                </div>
                            </div>
                        </div>

                        <!-- Address -->
                        <div class="flex items-start gap-4">
                            <div class="w-12 h-12 rounded-full border border-gray-600 flex items-center justify-center shrink-0">
                                <i class="fas fa-map-marker-alt text-lg"></i>
                            </div>
                            <div>
                                <h4 class="font-bold text-lg mb-1">אולם התצוגה</h4>
                                <p class="text-gray-400 font-light">היוזם 2, קרית ביאליק</p>
                            </div>
                        </div>

                        <!-- Email -->
                        <div class="flex items-start gap-4">
                            <div class="w-12 h-12 rounded-full border border-gray-600 flex items-center justify-center shrink-0">
                                <i class="fas fa-envelope text-lg"></i>
                            </div>
                            <div>
                                <h4 class="font-bold text-lg mb-1">דוא"ל</h4>
                                <a href="mailto:milenumarble@gmail.com" class="text-gray-400 hover:text-white transition-colors font-light font-sans">milenumarble@gmail.com</a>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Contact Form -->
                <div class="bg-white/5 backdrop-blur-md p-8 md:p-12 border border-white/10 reveal" style="transition-delay: 100ms;">
                    <h3 class="text-2xl font-bold mb-8">השאירו פרטים ונחזור אליכם</h3>
                    <form onsubmit="event.preventDefault(); document.getElementById('success-msg').classList.remove('hidden'); this.reset();" class="space-y-6">
                        <div>
                            <input type="text" placeholder="שם מלא" required class="premium-input">
                        </div>
                        <div>
                            <input type="tel" placeholder="מספר טלפון" required class="premium-input text-right" dir="rtl">
                        </div>
                        <div>
                            <input type="email" placeholder="דואר אלקטרוני" class="premium-input text-right" dir="rtl">
                        </div>
                        <div>
                            <textarea placeholder="איך נוכל לעזור?" rows="3" class="premium-input resize-none"></textarea>
                        </div>
                        <button type="submit" class="w-full btn-outline border border-white text-white py-4 mt-4 uppercase tracking-wider font-medium hover:bg-white hover:text-black transition-colors">
                            שלח פנייה
                        </button>
                        <p id="success-msg" class="hidden text-green-400 text-sm mt-4 text-center font-light">תודה רבה! פנייתך התקבלה ונחזור אליך בהקדם.</p>
                    </form>
                </div>

            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-brand-950 text-gray-400 py-16 border-t border-white/10">
        <div class="max-w-7xl mx-auto px-6 lg:px-12 grid grid-cols-1 md:grid-cols-4 gap-12">
            <div class="col-span-1 md:col-span-2">
                <img src="https://m-marble.co.il/wp-content/uploads/2023/08/cropped-logo.jpeg" alt="שיש מילניום" class="w-32 mb-6 logo-blend rounded bg-white p-2">
                <p class="text-sm font-light max-w-sm mb-6 leading-relaxed">
                    יבוא, יצוא, ייצור ושיווק של משטחי שיש מעוצבים. מעטפת משפחתית מרגע הבחירה ועד להתקנה, עם ניסיון של 3 דורות. אנו מתחייבים לאיכות וליוקרה ללא פשרות.
                </p>
                <div class="flex gap-4">
                    <a href="#" class="w-10 h-10 rounded-full border border-gray-700 flex items-center justify-center hover:bg-white hover:text-black hover:border-white transition-all">
                        <i class="fab fa-facebook-f"></i>
                    </a>
                    <a href="https://www.tiktok.com/@milenummarble" target="_blank" rel="noopener noreferrer" class="w-10 h-10 rounded-full border border-gray-700 flex items-center justify-center hover:bg-white hover:text-black hover:border-white transition-all">
                        <i class="fab fa-tiktok"></i>
                    </a>
                    <a href="https://wa.me/972543034582" target="_blank" rel="noopener noreferrer" class="w-10 h-10 rounded-full border border-gray-700 flex items-center justify-center hover:bg-white hover:text-black hover:border-white transition-all">
                        <i class="fab fa-whatsapp"></i>
                    </a>
                </div>
            </div>
            
            <div>
                <h4 class="text-white font-medium mb-6 uppercase tracking-wider text-sm">ניווט מהיר</h4>
                <ul class="space-y-4 text-sm font-light">
                    <li><a href="#home" class="hover:text-white transition-colors">בית</a></li>
                    <li><a href="#about" class="hover:text-white transition-colors">אודותינו</a></li>
                    <li><a href="#catalog" class="hover:text-white transition-colors">קטלוג מוצרים</a></li>
                    <li><a href="#services" class="hover:text-white transition-colors">השירותים שלנו</a></li>
                </ul>
            </div>
            
            <div>
                <h4 class="text-white font-medium mb-6 uppercase tracking-wider text-sm">מידע וצור קשר</h4>
                <ul class="space-y-4 text-sm font-light">
                    <li><a href="#contact" class="hover:text-white transition-colors">קביעת פגישת ייעוץ</a></li>
                    <li>טלפון: <span class="dir-ltr">04-8402101</span> | <span class="dir-ltr">054-3034582</span></li>
                    <li>דוא"ל: milenumarble@gmail.com</li>
                    <li>כתובת: היוזם 2, קרית ביאליק</li>
                </ul>
            </div>
        </div>
        
        <div class="max-w-7xl mx-auto px-6 lg:px-12 mt-16 pt-8 border-t border-white/10 flex flex-col md:flex-row justify-between items-center text-xs font-light text-gray-500">
            <p>&copy; 2024 שיש מילניום. כל הזכויות שמורות.</p>
            <div class="mt-4 md:mt-0 space-x-4 space-x-reverse">
                <a href="#" class="hover:text-gray-300">תנאי שימוש</a>
                <a href="#" class="hover:text-gray-300">הצהרת נגישות</a>
            </div>
        </div>
    </footer>

    <!-- Floating WhatsApp Button -->
    <a href="https://wa.me/972543034582" target="_blank" rel="noopener noreferrer" class="whatsapp-float" aria-label="Chat on WhatsApp">
        <i class="fab fa-whatsapp"></i>
    </a>

    <!-- Interactive Scripts -->
    <script>
        document.addEventListener('DOMContentLoaded', () => {
            // Navbar Scroll Effect
            const navbar = document.getElementById('navbar');
            window.addEventListener('scroll', () => {
                if (window.scrollY > 50) {
                    navbar.classList.add('nav-scrolled');
                    navbar.classList.remove('py-4');
                    navbar.classList.add('py-2');
                } else {
                    navbar.classList.remove('nav-scrolled');
                    navbar.classList.add('py-4');
                    navbar.classList.remove('py-2');
                }
            });

            // Mobile Menu Toggle
            const mobileMenuBtn = document.getElementById('mobile-menu-btn');
            const closeMenuBtn = document.getElementById('close-menu-btn');
            const mobileMenu = document.getElementById('mobile-menu');
            const mobileLinks = document.querySelectorAll('.mobile-link');

            const toggleMenu = () => {
                mobileMenu.classList.toggle('translate-x-full');
                document.body.classList.toggle('overflow-hidden');
            };

            mobileMenuBtn.addEventListener('click', toggleMenu);
            closeMenuBtn.addEventListener('click', toggleMenu);
            mobileLinks.forEach(link => {
                link.addEventListener('click', toggleMenu);
            });

            // Scroll Reveal Animation (Intersection Observer)
            const revealElements = document.querySelectorAll('.reveal');
            
            const revealCallback = (entries, observer) => {
                entries.forEach(entry => {
                    if (entry.isIntersecting) {
                        entry.target.classList.add('active');
                        observer.unobserve(entry.target); // Run once
                    }
                });
            };

            const revealOptions = {
                threshold: 0.15,
                rootMargin: "0px 0px -50px 0px"
            };

            const revealObserver = new IntersectionObserver(revealCallback, revealOptions);
            
            revealElements.forEach(el => {
                revealObserver.observe(el);
            });
        });
    </script>
</body>
</html>
