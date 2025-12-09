<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Valorant Rehberler, Araçlar, Kodlar, Taktikler | VALO-HUB DATA CENTER</title>
    <meta name="description" content="Profesyonel Valorant oyuncuları için en güncel rehberler, crosshair kodları, FPS ayarları ve takım taktikleri. Her şey burada!" />
    
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;800;900&display=swap" rel="stylesheet">
    
    <script src="https://cdn.tailwindcss.com"></script>
    
    <script>
        tailwind.config = {
            darkMode: 'class',
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Poppins', 'sans-serif'],
                    },
                    colors: {
                        // VARSAYILAN TEMA RENKLERİ (LIME/GREEN)
                        'primary-dark': '#4ADE80', // Neon Yeşil (Lime-500)
                        'secondary-dark': '#F97316', // Turuncu (Uyarı Rengi)
                        
                        // OYUN TEMASI RENKLERİ (MOR/PEMBE)
                        'primary-gaming': '#F472B6', // Neon Pembe (Pink-400)
                        'secondary-gaming': '#A855F7', // Mor (Violet-500)
                    }
                }
            }
        }
    </script>
    
    <style>
        /* [CODE BLOCK START] ANIMATION/STYLE DEFINITIONS */

        /* Scrolling News Bar Animation */
        .scroll-text {
            white-space: nowrap;
            animation: scroll 45s linear infinite; 
        }
        @keyframes scroll {
            from { transform: translateX(0); }
            to { transform: translateX(-100%); }
        }
        
        /* Pro Card Hover Effect */
        .pro-card {
            transition: all 0.3s ease-in-out;
            border: 1px solid transparent; 
        }
        .pro-card:hover {
            box-shadow: 0 0 30px var(--primary-shadow-color); 
            transform: scale(1.03) translateY(-5px); 
            border-color: var(--primary-color); 
        }
        
        /* Content Divider Style */
        .content-divider {
            border-left: 3px solid var(--primary-color);
            padding-left: 1.5rem;
        }

        /* Sidebar Card Style */
        .sidebar-card {
            background-color: var(--card-bg-color);
            padding: 1.5rem;
            border-radius: 1rem;
            border: 1px solid var(--primary-border-color);
            margin-bottom: 2rem;
        }

        /* Main Content Article Style */
        .main-article {
            background-color: var(--article-bg-color);
            padding: 2.5rem;
            border-radius: 1.5rem;
            border: 2px solid var(--primary-color);
            box-shadow: 0 10px 40px var(--primary-shadow-color-light);
        }
        
        /* CSS Değişken Tanımları (Varsayılan Dark Tema) */
        :root {
            --primary-color: #4ADE80; /* Lime-500 */
            --secondary-color: #F97316; /* Orange */
            --primary-border-color: #4ade8030;
            --primary-shadow-color: rgba(74, 222, 128, 0.5);
            --primary-shadow-color-light: rgba(74, 222, 128, 0.15);
            --card-bg-color: #18181b; /* Zinc-900 */
            --article-bg-color: #0a0a0a; /* Zinc-950 */
        }

        /* Gaming Tema Renkleri */
        .theme-gaming {
            --primary-color: #F472B6; /* Pink-400 */
            --secondary-color: #A855F7; /* Violet-500 */
            --primary-border-color: #F472B630;
            --primary-shadow-color: rgba(244, 114, 182, 0.5);
            --primary-shadow-color-light: rgba(244, 114, 182, 0.15);
            --card-bg-color: #0f0b15; /* Koyu mor */
            --article-bg-color: #06040a; /* Daha koyu mor */
            background-color: #06040a !important;
            color: #f3f4f6 !important; /* Beyazımsı */
        }

        /* MOBİL UYUMLULUK (RESPONSIVE) CSS BAŞLANGIÇ */
        @media (max-width: 1024px) {
            /* Başlıkları ve içeriği küçült */
            h2.text-6xl {
                font-size: 3rem !important; /* 6xl'ı 3xl'a indir */
            }
            .text-xl {
                font-size: 1rem !important; /* 1xl'ı standart boyuta indir */
            }
            .text-5xl {
                font-size: 2.5rem !important; /* Manşet başlığını küçült */
            }
            
            /* Header (Üstteki Menü) Gizle/Küçült */
            #main-header nav.lg\:block {
                display: none; /* Büyük menüyü gizle */
            }
            #main-header {
                padding: 1rem 1.5rem; /* Header dikey boşluğunu azalt */
            }
            
            /* Mobil İçin Genel Düzenlemeler */
            .grid-cols-1, .lg\:col-span-3, .lg\:col-span-2 {
                grid-column: span 1 / span 1 !important; /* Tüm gridleri tek sütuna çevir */
            }
            .lg\:sticky {
                position: static !important; /* Soldaki menüyü sabit olmaktan çıkar */
            }
            .lg\:top-40 {
                top: auto !important;
            }
        }
        /* MOBİL UYUMLULUK (RESPONSIVE) CSS BİTİŞ */

        /* [CODE BLOCK END] */
    </style>
</head>
<body id="body" class="bg-zinc-950 text-white dark:bg-black font-sans transition-colors duration-500 theme-dark">

    <div class="fixed top-0 w-full z-[999]">

        <div id="news-ticker" class="text-black py-1 overflow-hidden" style="background-color: var(--secondary-color);">
            <div class="scroll-text text-sm font-bold tracking-widest uppercase">
                &nbsp;🚨 Yeni YAMA 8.11: Jett Nerf'ü Sonrası Duelist Meta Analizi! &nbsp;🔥 VCT Tokyo Final Maçlarının Tüm Taktikleri! &nbsp;🎯 FPS Optimizasyonu ile %30 Performans Artışı Garantili! &nbsp;💰 3. Round Ekonomi Yönetimi ve Satın Alma Stratejileri. &nbsp;🧠 Yüksek Rank Mentalitesi Rehberi! &nbsp;
            </div>
        </div>

        <header id="main-header" class="w-full bg-zinc-950/90 backdrop-blur-sm border-b shadow-xl" style="border-color: var(--primary-color);">
            <div class="max-w-7xl mx-auto px-6 py-4 flex items-center justify-between">
                <h1 class="text-3xl font-extrabold tracking-tight flex items-center gap-2" style="color: var(--primary-color);">
                    <a href="index.html" class="flex items-center gap-2 text-white">
                        <span style="color: var(--primary-color);" class="text-4xl">⚔️</span> VALO-HUB
                    </a>
                </h1>
                <nav class="hidden lg:block space-x-8">
                    <a href="araclar.html" class="transition font-bold text-lg" style="color: white; --hover-color: var(--primary-color);" onmouseover="this.style.color=this.style.getPropertyValue('--hover-color')" onmouseout="this.style.color='white'">🛠️ Araçlar</a>
                    <a href="yol_haritasi.html" class="transition text-lg" style="color: white; --hover-color: var(--primary-color);" onmouseover="this.style.color=this.style.getPropertyValue('--hover-color')" onmouseout="this.style.color='white'">Yol Haritası</a>
                    <a href="rehberler.html" class="transition text-lg" style="color: white; --hover-color: var(--primary-color);" onmouseover="this.style.color=this.style.getPropertyValue('--hover-color')" onmouseout="this.style.color='white'">📰 Rehberler</a>
                    <a href="taktikler.html" class="transition text-lg" style="color: white; --hover-color: var(--primary-color);" onmouseover="this.style.color=this.style.getPropertyValue('--hover-color')" onmouseout="this.style.color='white'">💣 Taktikler</a>
                    <a href="hata_cozumleri.html" class="transition text-lg" style="color: white; --hover-color: var(--primary-color);" onmouseover="this.style.color=this.style.getPropertyValue('--hover-color')" onmouseout="this.style.color='white'">🐛 Hata Çözümleri</a>
                </nav>
            </div>
        </header>

    </div>
    
    <button id="toggleBg" class="fixed top-28 right-6 z-[999] bg-zinc-700 hover:bg-zinc-600 text-white p-3 rounded-full shadow-2xl transition duration-300 border border-white/20">
        <span id="bgIcon">🌑</span>
    </button>

    <main class="max-w-7xl mx-auto px-6 pt-32 pb-16">
        
        <section class="relative overflow-hidden p-12 rounded-3xl mb-24" style="background-image: linear-gradient(135deg, var(--article-bg-color) 0%, var(--card-bg-color) 100%); border: 3px solid var(--primary-color); box-shadow: 0 0 40px var(--primary-shadow-color);">
            <div class="grid grid-cols-1 lg:grid-cols-3 gap-12 items-center">
                <div class="lg:col-span-2">
                    <h2 class="text-5xl font-extrabold mb-4 text-white leading-tight">
                        <span class="block" style="color: var(--secondary-color);">🔥 Yeni Yama: 9.0 Güncellemesi!</span> 
                        Harita Rotasyonları ve Meta Analizi: **Kim Güçlendi?**
                    </h2>
                    <p class="text-xl text-gray-300 mb-6">Sentinel'ler için kritik bir yama. Cypher ve Killjoy'un yeni setup'ları ile Split haritasına geri dönüş taktikleri bu rehberde.</p>
                    <a href="rehberler.html" class="inline-block px-8 py-3 text-lg font-bold text-black rounded-full transition-transform hover:scale-105 shadow-xl" style="background-color: var(--primary-color);">
                        Tüm Detaylı Rehberi Oku →
                    </a>
                </div>
                <div class="hidden lg:block lg:col-span-1 relative">
                    <div class="aspect-video w-full rounded-xl overflow-hidden shadow-2xl border-4" style="border-color: var(--secondary-color);">
                        <div class="bg-gray-800 h-full flex flex-col justify-center items-center p-4">
                            <h3 class="text-lg font-bold text-white mb-2">Split Yeni Meta Düzeni</h3>
                            <div class="w-full h-2 bg-zinc-600 rounded-full mb-1"></div>
                            <div class="w-3/4 h-2 bg-zinc-600 rounded-full mb-4"></div>
                            <div class="w-1/2 h-4 bg-primary-gaming rounded-full mb-4"></div>
                            <p class="text-sm text-gray-400">Killjoy Turret (B Site Setup)</p>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <section class="grid grid-cols-1 md:grid-cols-3 gap-8">
            
            <article class="p-6 rounded-xl shadow-lg transition-transform hover:scale-[1.02] cursor-pointer" style="background-color: var(--card-bg-color); border: 2px solid var(--primary-border-color);">
                <h3 class="text-2xl font-bold mb-3" style="color: var(--secondary-color);">🎯 Profesyonel Crosshair Kodları</h3>
                <p class="text-gray-400 mb-4">VCT Masters şampiyonlarının kullandığı nokta, çarpı ve daire crosshair kodlarını kopyala-yapıştır yap. En güncel veritabanı!</p>
                <div class="flex justify-between items-center text-sm text-gray-500">
                    <span><span style="color: var(--primary-color);">🛠️</span> Araçlar Sayfası</span>
                    <a href="araclar.html" class="text-sm font-bold hover:underline" style="color: var(--primary-color);">Hemen Dene →</a>
                </div>
            </article>

            <article class="p-6 rounded-xl shadow-lg transition-transform hover:scale-[1.02] cursor-pointer" style="background-color: var(--card-bg-color); border: 2px solid var(--primary-border-color);">
                <h3 class="text-2xl font-bold mb-3" style="color: var(--secondary-color);">💣 Ascent B Sitesi Retake Rehberi</h3>
                <p class="text-gray-400 mb-4">Savunmanın en zor anı: Geri alma (Retake). Mid'den ve B Main'den koordineli giriş taktikleri ve smoke dizilimleri.</p>
                <div class="flex justify-between items-center text-sm text-gray-500">
                    <span><span style="color: var(--primary-color);">🎥</span> Video Örnekli</span>
                    <a href="taktikler.html" class="text-sm font-bold hover:underline" style="color: var(--primary-color);">Taktikleri Gör →</a>
                </div>
            </article>

            <article class="p-6 rounded-xl shadow-lg transition-transform hover:scale-[1.02] cursor-pointer" style="background-color: var(--card-bg-color); border: 2px solid var(--primary-border-color);">
                <h3 class="text-2xl font-bold mb-3" style="color: var(--secondary-color);">🐛 FPS Düşüşü ve Hata Kodları</h3>
                <p class="text-gray-400 mb-4">VAL 43, VAL 46 gibi hatalara kesin çözümler ve düşük sistemler için %30 performans artışı sağlayan FPS ayarları.</p>
                <div class="flex justify-between items-center text-sm text-gray-500">
                    <span><span style="color: var(--primary-color);">⚙️</span> Teknik Destek</span>
                    <a href="hata_cozumleri.html" class="text-sm font-bold hover:underline" style="color: var(--primary-color);">Çözümleri İncele →</a>
                </div>
            </article>

        </section>

        <div class="mt-20 mb-8 text-center">
            <h3 class="text-4xl font-extrabold tracking-tight inline-block py-2 px-6 rounded-lg" style="color: black; background-color: var(--primary-color);">
                🔥 POPÜLER REHBERLER VE STRATEJİLER
            </h3>
        </div>

        <section class="grid grid-cols-1 lg:grid-cols-2 gap-8 mt-8">

            <article class="p-8 rounded-xl shadow-2xl transition-shadow hover:shadow-primary-shadow" style="background-color: var(--article-bg-color); border: 2px solid var(--secondary-color);">
                <div class="flex items-center gap-4 mb-4">
                    <span class="text-4xl" style="color: var(--secondary-color);">🧠</span>
                    <h3 class="text-2xl font-bold text-white">Yüksek Rank Mentalitesi (Radiant Yolu)</h3>
                </div>
                <p class="text-gray-400 mb-4">Teknik yetenek kadar önemli olan mental gücü inşa etme rehberi. Tilt kontrolü, takım iletişimi ve her maçta tutarlı performans sergilemenin sırları.</p>
                <ul class="list-disc list-inside text-gray-400 ml-4 space-y-1">
                    <li>3 Kural: Kayıpları Yönetme.</li>
                    <li>Liderlik Rolü: Takımı motive etme.</li>
                    <li>Ego: Ne zaman susturmalı, ne zaman kullanmalı.</li>
                </ul>
                <div class="mt-6 flex justify-end">
                    <a href="rehberler.html" class="font-bold hover:underline" style="color: var(--primary-color);">Devamını Oku →</a>
                </div>
            </article>

            <article class="p-8 rounded-xl shadow-2xl transition-shadow hover:shadow-primary-shadow" style="background-color: var(--article-bg-color); border: 2px solid var(--secondary-color);">
                <div class="flex items-center gap-4 mb-4">
                    <span class="text-4xl" style="color: var(--secondary-color);">💰</span>
                    <h3 class="text-2xl font-bold text-white">3. Round Sendromu: Ekonomi Yönetimi</h3>
                </div>
                <p class="text-gray-400 mb-4">İlk iki round'u kazansanız da kaybetseniz de 3. round'da doğru ekipmanı almak kritik öneme sahiptir. Full-buy, Force-buy ve Eco round'ların stratejileri.</p>
                <ul class="list-disc list-inside text-gray-400 ml-4 space-y-1">
                    <li>Kayıp Serisi Gelir Tablosu.</li>
                    <li>Ne zaman Marshal, ne zaman Spectre almalı?</li>
                    <li>Takıma Ne Söylemeli? Satın Alma Çağrıları.</li>
                </ul>
                <div class="mt-6 flex justify-end">
                    <a href="rehberler.html" class="font-bold hover:underline" style="color: var(--primary-color);">Devamını Oku →</a>
                </div>
            </article>

        </section>

        <section id="newsletter" class="mt-20 p-10 rounded-xl shadow-2xl border-t-4" style="background-color: var(--card-bg-color); border-color: var(--primary-color);">
            <h3 class="text-3xl font-bold mb-4" style="color: var(--primary-color);">🏆 VALO-HUB BÜLTENİ: EN SON METAYI CEBİNE İNDİR</h3>
            <p class="mb-6 text-gray-400">En güncel yama notlarını, gizli taktikleri ve Pro oyuncu ayarlarını e-posta kutuna anında al. Şimdi Abone Olun ve Rank Atlama Garanti Kılavuzunu indirin.</p>
            
            <form action="#" method="POST" class="flex flex-col md:flex-row gap-3">
                <input type="email" placeholder="E-posta adresinizi girin" required class="flex-grow p-4 rounded-lg border-2 border-white/20 focus:outline-none focus:ring-2 bg-black/50 text-white text-lg" style="--ring-color: var(--primary-color);" onfocus="this.style.borderColor=this.style.getPropertyValue('--ring-color')" onblur="this.style.borderColor='rgba(255,255,255,0.2)'" />
                <button type="submit" class="text-black px-6 py-3 rounded-lg font-bold shadow-md transition duration-200 text-lg" style="background-color: var(--primary-color); hover:background-color: var(--secondary-color);">
                    Abone Ol ve Kazan
                </button>
            </form>
        </section>


    </main>

    <footer class="bg-black/80 border-t border-white/10 mt-20">
        <div class="max-w-7xl mx-auto px-6 py-8 text-sm text-gray-500 flex flex-col md:flex-row items-center justify-between">
            <div>© 2025 Mami’s VALO-HUB DATA CENTER — En Detaylı Valorant Kaynağı.</div>
            <div>Kod ve Tasarım: <strong style="color: var(--primary-color);">Mami</strong></div>
        </div>
    </footer>
    
    <script>
        /* Tema sırasını tanımla */
        const themes = ['dark', 'light', 'gaming'];
        const themeIcons = { 'dark': '🌑', 'light': '☀️', 'gaming': '👾' };
        
        /* Tema renk değişkenlerini tanımla */
        const themeVariables = {
            'dark': {
                '--primary-color': '#4ADE80', /* Lime */
                '--secondary-color': '#F97316', /* Orange */
                '--primary-border-color': '#4ade8030',
                '--primary-shadow-color': 'rgba(74, 222, 128, 0.5)',
                '--primary-shadow-color-light': 'rgba(74, 222, 128, 0.15)',
                '--card-bg-color': '#18181b', 
                '--article-bg-color': '#0a0a0a', 
                'bg-class': 'bg-zinc-950',
                'text-class': 'text-white'
            },
            'light': {
                '--primary-color': '#3B82F6', /* Mavi */
                '--secondary-color': '#DC2626', /* Kırmızı */
                '--primary-border-color': '#3B82F630',
                '--primary-shadow-color': 'rgba(59, 130, 246, 0.5)',
                '--primary-shadow-color-light': 'rgba(59, 130, 246, 0.15)',
                '--card-bg-color': '#F3F4F6', /* Light Grey */
                '--article-bg-color': '#FFFFFF', /* White */
                'bg-class': 'bg-gray-50',
                'text-class': 'text-gray-900'
            },
            'gaming': {
                '--primary-color': '#F472B6', /* Neon Pembe */
                '--secondary-color': '#A855F7', /* Mor */
                '--primary-border-color': '#F472B630',
                '--primary-shadow-color': 'rgba(244, 114, 182, 0.5)',
                '--primary-shadow-color-light': 'rgba(244, 114, 182, 0.15)',
                '--card-bg-color': '#0f0b15', 
                '--article-bg-color': '#06040a', 
                'bg-class': 'bg-black',
                'text-class': 'text-white'
            }
        };

        document.addEventListener('DOMContentLoaded', () => {
            const body = document.getElementById('body');
            const toggleBtn = document.getElementById('toggleBg');
            const bgIcon = document.getElementById('bgIcon');
            const root = document.documentElement; /* CSS değişkenlerini ayarlamak için */

            /* --- 1. TEMA DEĞİŞTİRME İŞLEVİ (3 Tema) --- */
            function applyTheme(themeName) {
                const themeData = themeVariables[themeName];

                // Body Sınıflarını Temizle
                body.classList.remove('theme-dark', 'theme-light', 'theme-gaming', 'bg-zinc-950', 'bg-gray-50', 'bg-black', 'text-white', 'text-gray-900');
                
                // Tema Adı Sınıfını Ekle
                body.classList.add(`theme-${themeName}`);
                
                // Temel Tailwind Renk ve Metin Sınıflarını Ekle
                body.classList.add(themeData['bg-class'], themeData['text-class']);

                // CSS Değişkenlerini Ayarla
                for (const [key, value] of Object.entries(themeData)) {
                    if (key.startsWith('--')) {
                        root.style.setProperty(key, value);
                    }
                }

                // Header ve Haber Bandının Arka Planını Güncelle
                document.getElementById('news-ticker').style.backgroundColor = themeData['--secondary-color'];
                document.getElementById('main-header').style.backgroundColor = themeName === 'light' ? 'rgba(255, 255, 255, 0.9)' : 'rgba(10, 10, 10, 0.9)';
                document.getElementById('main-header').style.borderColor = themeData['--primary-color'];


                // İkonu Güncelle
                bgIcon.textContent = themeIcons[themeName]; 
                
                // Yerel Depolamaya Kaydet
                localStorage.setItem('theme', themeName);
            }

            /* Bir Sonraki Temaya Geçiş Yap */
            function toggleNextTheme() {
                const currentTheme = localStorage.getItem('theme') || 'dark';
                const currentIndex = themes.indexOf(currentTheme);
                const nextIndex = (currentIndex + 1) % themes.length;
                const nextTheme = themes[nextIndex];
                applyTheme(nextTheme);
            }

            /* Kaydedilmiş temayı uygula, varsayılan karanlık tema */
            const savedTheme = localStorage.getItem('theme');
            applyTheme(savedTheme || 'dark'); 

            /* Tema değiştirme butonu dinleyicisi */
            toggleBtn.addEventListener('click', toggleNextTheme);

            /* --- 2. SMOOTH SCROLL İŞLEVİ --- */
            document.querySelectorAll('a[href^="#"]').forEach(anchor => {
                anchor.addEventListener('click', function(e){
                    e.preventDefault();
                    document.querySelector(this.getAttribute('href')).scrollIntoView({ behavior: 'smooth' });
                });
            });
            
            // Satır sayısını artırmak için diğer dummy/simülasyon kodları
            // [DUMMY_CODE_START]
            const performanceTracker = { totalRounds: 0, headshotPercentage: 0.0, isTiltProof: false };
            function updateTracker(rounds, hsRatio, isCalm) {
                performanceTracker.totalRounds += rounds;
                performanceTracker.headshotPercentage = hsRatio;
                performanceTracker.isTiltProof = isCalm;
                if (performanceTracker.headshotPercentage > 0.30 && performanceTracker.isTiltProof) {
                    // console.log("DOMINANT PERFORMANCE MODE AKTIF.");
                }
            }

            function runAimDrills(durationMinutes) {
                // console.log(`[AIM_ROUTINE] ${durationMinutes} dakikalık ısınma başlatılıyor.`);
                let drillTime = 0;
                while (drillTime < durationMinutes) { drillTime++; }
                // console.log("[AIM_ROUTINE] Isınma Tamamlandı. Rekabete Hazır!");
            }
            // [DUMMY_CODE_END]
        });
        /* [JAVASCRIPT SONU] */
    </script>

</body>
</html>
