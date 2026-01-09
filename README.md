**<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Douae Boudik | Marketing Digital EST Salé</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <!-- AOS pour les animations au scroll -->
    <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">
    <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@300;400;600;700;800&display=swap');
        
        body {
            font-family: 'Plus Jakarta Sans', sans-serif;
            scroll-behavior: smooth;
            overflow-x: hidden;
        }

        .gradient-text {
            background: linear-gradient(135deg, #2563eb, #9333ea, #db2777);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        .custom-shadow {
            box-shadow: 0 20px 40px -15px rgba(0, 0, 0, 0.05);
        }

        .nav-blur {
            background: rgba(255, 255, 255, 0.7);
            backdrop-filter: blur(20px);
            -webkit-backdrop-filter: blur(20px);
        }

        .blob {
            position: absolute;
            filter: blur(80px);
            z-index: -1;
            border-radius: 50%;
            opacity: 0.4;
        }

        .btn-primary {
            transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
        }

        .btn-primary:hover {
            transform: scale(1.05);
            box-shadow: 0 10px 25px -5px rgba(37, 99, 235, 0.4);
        }

        /* Timeline styling */
        .timeline-item::after {
            content: '';
            position: absolute;
            left: -34px;
            top: 5px;
            width: 20px;
            height: 20px;
            background: white;
            border: 4px solid #2563eb;
            border-radius: 50%;
            z-index: 1;
        }
    </style>
</head>
<body class="bg-slate-50 text-slate-900 selection:bg-blue-100 selection:text-blue-900">

    <!-- Blobs de fond décoratifs -->
    <div class="blob bg-blue-200 w-96 h-96 -top-20 -left-20 animate-pulse"></div>
    <div class="blob bg-purple-200 w-[500px] h-[500px] top-1/2 -right-40"></div>

    <!-- Navigation -->
    <nav class="fixed w-full z-50 nav-blur border-b border-slate-100">
        <div class="max-w-7xl mx-auto px-6 py-4 flex justify-between items-center">
            <a href="#" class="text-xl font-extrabold tracking-tighter flex items-center gap-2">
                <span class="w-8 h-8 bg-blue-600 rounded-lg flex items-center justify-center text-white text-sm">DB</span>
                Douae Boudik
            </a>
            <div class="hidden md:flex items-center gap-8 font-bold text-sm tracking-tight text-slate-600">
                <a href="#parcours" class="hover:text-blue-600 transition-colors">Mon Parcours</a>
                <a href="#competences" class="hover:text-blue-600 transition-colors">Compétences</a>
                <a href="#projets" class="hover:text-blue-600 transition-colors">Projets</a>
                <a href="#contact" class="px-6 py-2.5 bg-blue-600 text-white rounded-full btn-primary">Contact</a>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section class="relative pt-48 pb-24 px-6 overflow-hidden">
        <div class="max-w-7xl mx-auto flex flex-col lg:flex-row items-center gap-16">
            <div class="flex-1 text-center lg:text-left" data-aos="fade-right">
                <div class="inline-flex items-center gap-2 px-4 py-1.5 bg-blue-50 text-blue-700 rounded-full text-xs font-black uppercase tracking-widest mb-6 border border-blue-100">
                    <span class="relative flex h-2 w-2">
                        <span class="animate-ping absolute inline-flex h-full w-full rounded-full bg-blue-400 opacity-75"></span>
                        <span class="relative inline-flex rounded-full h-2 w-2 bg-blue-600"></span>
                    </span>
                    À la recherche d'un stage — Rabat / Salé
                </div>
                <h1 class="text-5xl md:text-7xl lg:text-8xl font-black mb-8 leading-[0.9] tracking-tighter">
                    Le Marketing <br><span class="gradient-text">réinventé.</span>
                </h1>
                <p class="text-lg md:text-xl text-slate-500 mb-10 max-w-xl leading-relaxed font-medium">
                    Étudiante en 2ème année à l'**EST de Salé**. J'aide les marques à raconter leur histoire à travers des contenus digitaux percutants et une analyse de données rigoureuse.
                </p>
                <div class="flex flex-wrap justify-center lg:justify-start gap-4">
                    <a href="#contact" class="px-8 py-4 bg-slate-900 text-white font-bold rounded-2xl btn-primary">
                        Démarrer un projet
                    </a>
                    <a href="#parcours" class="px-8 py-4 bg-white border border-slate-200 font-bold rounded-2xl hover:bg-slate-50 transition-all flex items-center gap-2 shadow-sm">
                        Découvrir mon profil <i class="fas fa-arrow-right text-xs"></i>
                    </a>
                </div>
            </div>

            <div class="flex-1 flex justify-center relative" data-aos="fade-left" data-aos-delay="200">
                <!-- Floating Stats Card -->
                <div class="absolute -left-4 top-20 bg-white p-4 rounded-2xl shadow-2xl z-20 hidden md:block animate-bounce" style="animation-duration: 4s;">
                    <div class="flex items-center gap-3">
                        <div class="w-10 h-10 bg-green-100 text-green-600 rounded-full flex items-center justify-center">
                            <i class="fas fa-chart-line"></i>
                        </div>
                        <div>
                            <p class="text-[10px] uppercase font-black text-slate-400">Engagement</p>
                            <p class="font-bold text-lg text-slate-800">+45%</p>
                        </div>
                    </div>
                </div>

                <div class="relative w-72 h-72 md:w-[450px] md:h-[450px]">
                    <div class="absolute inset-0 bg-gradient-to-tr from-blue-600 to-purple-600 rounded-[3.5rem] rotate-3 opacity-10"></div>
                    <div class="relative w-full h-full bg-slate-200 rounded-[3rem] overflow-hidden border-4 border-white shadow-2xl">
                        <img src="https://images.unsplash.com/photo-1573496359142-b8d87734a5a2?auto=format&fit=crop&q=80&w=800" alt="Douae Boudik" class="w-full h-full object-cover grayscale-[20%] hover:grayscale-0 transition-all duration-700">
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Section Parcours (Timeline) -->
    <section id="parcours" class="py-32 bg-white">
        <div class="max-w-7xl mx-auto px-6">
            <div class="grid grid-cols-1 lg:grid-cols-2 gap-20">
                <div data-aos="fade-up">
                    <h2 class="text-4xl font-black mb-8 leading-tight">Mon Éducation & <br>Expériences</h2>
                    <p class="text-slate-500 font-medium mb-12">Mon parcours académique à l'EST de Salé m'a permis d'acquérir une vision 360° du commerce et du marketing digital.</p>
                    
                    <div class="relative border-l-2 border-slate-100 ml-4 space-y-16">
                        <!-- EST Salé -->
                        <div class="timeline-item relative pl-10" data-aos="fade-up" data-aos-delay="100">
                            <span class="text-blue-600 font-black text-sm uppercase tracking-widest">2023 — Aujourd'hui</span>
                            <h3 class="text-2xl font-extrabold mt-2 italic">DUT - Techniques de Commercialisation</h3>
                            <p class="text-slate-800 font-bold mb-4">EST Salé (Université Mohammed V)</p>
                            <p class="text-slate-500 leading-relaxed">
                                Immersion dans le marketing stratégique, la communication d'entreprise et les outils de gestion commerciale.
                            </p>
                        </div>

                        <!-- Stage -->
                        <div class="timeline-item relative pl-10" data-aos="fade-up" data-aos-delay="200">
                            <span class="text-purple-600 font-black text-sm uppercase tracking-widest">ÉTÉ 2024</span>
                            <h3 class="text-2xl font-extrabold mt-2 italic">Projet de Création de Contenu</h3>
                            <p class="text-slate-800 font-bold mb-4">Freelance & Projets Académiques</p>
                            <p class="text-slate-500 leading-relaxed">
                                Développement de stratégies de marque sur Instagram et TikTok. Montage vidéo optimisé pour le taux de rétention.
                            </p>
                        </div>
                    </div>
                </div>

                <!-- Soft Skills & Langues -->
                <div class="bg-slate-50 rounded-[3rem] p-10 md:p-16" data-aos="fade-up" data-aos-delay="300">
                    <h3 class="text-2xl font-black mb-10">Compétences Humaines</h3>
                    <div class="grid grid-cols-1 gap-8">
                        <div>
                            <div class="flex justify-between mb-3 font-bold text-sm">
                                <span>Créativité & Innovation</span>
                                <span>95%</span>
                            </div>
                            <div class="w-full bg-white h-2 rounded-full overflow-hidden">
                                <div class="bg-blue-600 h-full w-[95%]" data-aos="slide-right" data-aos-delay="400"></div>
                            </div>
                        </div>
                        <div>
                            <div class="flex justify-between mb-3 font-bold text-sm">
                                <span>Esprit Analytique</span>
                                <span>85%</span>
                            </div>
                            <div class="w-full bg-white h-2 rounded-full overflow-hidden">
                                <div class="bg-purple-600 h-full w-[85%]" data-aos="slide-right" data-aos-delay="500"></div>
                            </div>
                        </div>
                        <div>
                            <div class="flex justify-between mb-3 font-bold text-sm">
                                <span>Esprit d'Équipe (EST Salé)</span>
                                <span>90%</span>
                            </div>
                            <div class="w-full bg-white h-2 rounded-full overflow-hidden">
                                <div class="bg-pink-600 h-full w-[90%]" data-aos="slide-right" data-aos-delay="600"></div>
                            </div>
                        </div>
                    </div>

                    <div class="mt-16">
                        <h3 class="text-2xl font-black mb-8">Langues</h3>
                        <div class="flex flex-wrap gap-4">
                            <span class="px-6 py-2 bg-white rounded-full font-bold shadow-sm border border-slate-100 italic">Arabe (Maternel)</span>
                            <span class="px-6 py-2 bg-white rounded-full font-bold shadow-sm border border-slate-100 italic">Français (Courant)</span>
                            <span class="px-6 py-2 bg-white rounded-full font-bold shadow-sm border border-slate-100 italic">Anglais (Avancé)</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Section Expertises (Cards) -->
    <section id="competences" class="py-32 bg-slate-900 text-white overflow-hidden">
        <div class="max-w-7xl mx-auto px-6">
            <div class="text-center max-w-2xl mx-auto mb-20" data-aos="fade-up">
                <h2 class="text-4xl md:text-5xl font-black mb-6">Expertises Digitales</h2>
                <p class="text-slate-400 font-medium italic">Une approche hybride entre création et performance.</p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <div class="p-10 bg-white/5 border border-white/10 rounded-[2.5rem] hover:bg-blue-600 transition-all group duration-500" data-aos="zoom-in" data-aos-delay="100">
                    <i class="fas fa-bullseye text-4xl text-blue-500 mb-8 group-hover:text-white transition-colors"></i>
                    <h3 class="text-2xl font-black mb-4">Stratégie Ads</h3>
                    <p class="text-slate-400 group-hover:text-blue-50 leading-relaxed font-medium">Gestion de campagnes Facebook & Instagram Ads. Analyse des KPIs et optimisation du ROI.</p>
                </div>
                <div class="p-10 bg-white/5 border border-white/10 rounded-[2.5rem] hover:bg-purple-600 transition-all group duration-500" data-aos="zoom-in" data-aos-delay="200">
                    <i class="fas fa-magic text-4xl text-purple-500 mb-8 group-hover:text-white transition-colors"></i>
                    <h3 class="text-2xl font-black mb-4">Content Design</h3>
                    <p class="text-slate-400 group-hover:text-purple-50 leading-relaxed font-medium">Création visuelle sur Canva et CapCut. Design de feeds Instagram harmonieux et engageants.</p>
                </div>
                <div class="p-10 bg-white/5 border border-white/10 rounded-[2.5rem] hover:bg-pink-600 transition-all group duration-500" data-aos="zoom-in" data-aos-delay="300">
                    <i class="fas fa-hashtag text-4xl text-pink-500 mb-8 group-hover:text-white transition-colors"></i>
                    <h3 class="text-2xl font-black mb-4">Social Media</h3>
                    <p class="text-slate-400 group-hover:text-pink-50 leading-relaxed font-medium">Community management, modération et stratégies de croissance organique des audiences.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Section Contact (Formulaire Boosté) -->
    <section id="contact" class="py-32 bg-white">
        <div class="max-w-7xl mx-auto px-6">
            <div class="flex flex-col lg:flex-row gap-20 items-center">
                <div class="lg:w-1/3" data-aos="fade-right">
                    <h2 class="text-5xl font-black mb-8 tracking-tighter italic">On commence <br>quand ?</h2>
                    <p class="text-slate-500 font-medium mb-12">Je suis prête à rejoindre vos équipes à Rabat pour mon stage de 2ème année. Envoyez-moi un message !</p>
                    
                    <div class="space-y-6">
                        <a href="mailto:douae.boudik@email.ma" class="flex items-center gap-4 group">
                            <div class="w-12 h-12 bg-slate-50 rounded-xl flex items-center justify-center group-hover:bg-blue-600 group-hover:text-white transition-all">
                                <i class="fas fa-envelope"></i>
                            </div>
                            <span class="font-bold text-slate-700">douae.boudik@email.ma</span>
                        </a>
                        <a href="#" class="flex items-center gap-4 group">
                            <div class="w-12 h-12 bg-slate-50 rounded-xl flex items-center justify-center group-hover:bg-blue-600 group-hover:text-white transition-all">
                                <i class="fab fa-linkedin-in"></i>
                            </div>
                            <span class="font-bold text-slate-700">@douae-boudik-est-sale</span>
                        </a>
                    </div>
                </div>

                <div class="lg:w-2/3 w-full" data-aos="fade-left">
                    <div class="bg-slate-50 p-10 md:p-16 rounded-[3rem] shadow-sm border border-slate-100">
                        <form id="contactForm" class="space-y-6">
                            <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                                <div class="space-y-2">
                                    <label class="text-xs font-black uppercase tracking-widest text-slate-400 ml-1">Nom Complet</label>
                                    <input type="text" placeholder="John Doe" class="w-full px-6 py-4 bg-white border border-slate-200 rounded-2xl focus:ring-4 focus:ring-blue-100 outline-none transition font-bold" required>
                                </div>
                                <div class="space-y-2">
                                    <label class="text-xs font-black uppercase tracking-widest text-slate-400 ml-1">Email</label>
                                    <input type="email" placeholder="contact@entreprise.ma" class="w-full px-6 py-4 bg-white border border-slate-200 rounded-2xl focus:ring-4 focus:ring-blue-100 outline-none transition font-bold" required>
                                </div>
                            </div>
                            <div class="space-y-2">
                                <label class="text-xs font-black uppercase tracking-widest text-slate-400 ml-1">Votre Message</label>
                                <textarea placeholder="Décrivez votre besoin de stagiaire..." class="w-full px-6 py-4 bg-white border border-slate-200 rounded-2xl focus:ring-4 focus:ring-blue-100 outline-none transition h-44 font-bold" required></textarea>
                            </div>
                            <button type="submit" class="w-full py-5 bg-blue-600 text-white font-black rounded-2xl btn-primary shadow-xl">
                                Envoyer le message
                            </button>
                            <p id="successMessage" class="hidden text-center text-green-600 font-bold animate-bounce mt-4">
                                <i class="fas fa-check-circle mr-2"></i> Message envoyé avec succès !
                            </p>
                        </form>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="py-12 bg-white border-t border-slate-100">
        <div class="max-w-7xl mx-auto px-6 flex flex-col md:flex-row justify-between items-center gap-6">
            <p class="text-slate-400 font-bold text-xs uppercase tracking-widest italic">
                Douae Boudik — EST Salé — Promotion 2025
            </p>
            <div class="flex gap-6 text-slate-400">
                <a href="#" class="hover:text-blue-600 transition-colors"><i class="fab fa-instagram"></i></a>
                <a href="#" class="hover:text-blue-600 transition-colors"><i class="fab fa-linkedin"></i></a>
                <a href="#" class="hover:text-blue-600 transition-colors"><i class="fab fa-tiktok"></i></a>
            </div>
        </div>
    </footer>

    <script>
        // Initialisation des animations au scroll
        AOS.init({
            duration: 1000,
            once: true,
            offset: 100
        });

        // Gestion du formulaire
        document.getElementById('contactForm').addEventListener('submit', function(e) {
            e.preventDefault();
            document.getElementById('successMessage').classList.remove('hidden');
            this.reset();
        });
    </script>
</body>
</html>**<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Douae Boudik | Marketing Digital EST Salé</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <!-- AOS pour les animations au scroll -->
    <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">
    <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@300;400;600;700;800&display=swap');
        
        body {
            font-family: 'Plus Jakarta Sans', sans-serif;
            scroll-behavior: smooth;
            overflow-x: hidden;
        }

        .gradient-text {
            background: linear-gradient(135deg, #2563eb, #9333ea, #db2777);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        .nav-blur {
            background: rgba(255, 255, 255, 0.7);
            backdrop-filter: blur(20px);
            -webkit-backdrop-filter: blur(20px);
        }

        .blob {
            position: absolute;
            filter: blur(80px);
            z-index: -1;
            border-radius: 50%;
            opacity: 0.4;
        }

        .btn-primary {
            transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
        }

        .btn-primary:hover {
            transform: scale(1.05);
            box-shadow: 0 10px 25px -5px rgba(37, 99, 235, 0.4);
        }

        .timeline-item::after {
            content: '';
            position: absolute;
            left: -34px;
            top: 5px;
            width: 20px;
            height: 20px;
            background: white;
            border: 4px solid #2563eb;
            border-radius: 50%;
            z-index: 1;
        }

        /* Animation pour l'image si elle est absente */
        .img-placeholder {
            background: linear-gradient(45deg, #e2e8f0, #cbd5e1);
            display: flex;
            align-items: center;
            justify-content: center;
            color: #64748b;
        }
    </style>
</head>
<body class="bg-slate-50 text-slate-900 selection:bg-blue-100 selection:text-blue-900">

    <div class="blob bg-blue-200 w-96 h-96 -top-20 -left-20 animate-pulse"></div>
    <div class="blob bg-purple-200 w-[500px] h-[500px] top-1/2 -right-40"></div>

    <nav class="fixed w-full z-50 nav-blur border-b border-slate-100">
        <div class="max-w-7xl mx-auto px-6 py-4 flex justify-between items-center">
            <a href="#" class="text-xl font-extrabold tracking-tighter flex items-center gap-2">
                <div class="w-8 h-8 bg-blue-600 rounded-lg flex items-center justify-center text-white text-sm">DB</div>
                Douae Boudik
            </a>
            <div class="hidden md:flex items-center gap-8 font-bold text-sm tracking-tight text-slate-600">
                <a href="#parcours" class="hover:text-blue-600 transition-colors">Mon Parcours</a>
                <a href="#competences" class="hover:text-blue-600 transition-colors">Compétences</a>
                <a href="#contact" class="px-6 py-2.5 bg-blue-600 text-white rounded-full btn-primary">Contact</a>
            </div>
        </div>
    </nav>

    <section class="relative pt-48 pb-24 px-6 overflow-hidden">
        <div class="max-w-7xl mx-auto flex flex-col lg:flex-row items-center gap-16">
            <div class="flex-1 text-center lg:text-left" data-aos="fade-right">
                <div class="inline-flex items-center gap-2 px-4 py-1.5 bg-blue-50 text-blue-700 rounded-full text-xs font-black uppercase tracking-widest mb-6 border border-blue-100">
                    <span class="relative flex h-2 w-2">
                        <span class="animate-ping absolute inline-flex h-full w-full rounded-full bg-blue-400 opacity-75"></span>
                        <span class="relative inline-flex rounded-full h-2 w-2 bg-blue-600"></span>
                    </span>
                    En recherche de stage — Rabat / Salé
                </div>
                <h1 class="text-5xl md:text-7xl lg:text-8xl font-black mb-8 leading-[0.9] tracking-tighter">
                    Douae <br><span class="gradient-text">Boudik.</span>
                </h1>
                <p class="text-lg md:text-xl text-slate-500 mb-10 max-w-xl leading-relaxed font-medium">
                    Étudiante en 2ème année à l'**EST de Salé**. J'allie stratégie marketing et créativité digitale pour propulser votre communication.
                </p>
                <div class="flex flex-wrap justify-center lg:justify-start gap-4">
                    <a href="#contact" class="px-8 py-4 bg-slate-900 text-white font-bold rounded-2xl btn-primary">Démarrer un projet</a>
                    <button onclick="window.print()" class="px-8 py-4 bg-white border border-slate-200 font-bold rounded-2xl hover:bg-slate-50 transition-all flex items-center gap-2 shadow-sm">
                        <i class="fas fa-download"></i> Télécharger CV
                    </button>
                </div>
            </div>

            <div class="flex-1 flex justify-center relative" data-aos="fade-left" data-aos-delay="200">
                <div class="relative w-72 h-72 md:w-[450px] md:h-[450px]">
                    <div class="absolute inset-0 bg-gradient-to-tr from-blue-600 to-purple-600 rounded-[3.5rem] rotate-3 opacity-10"></div>
                    <div class="relative w-full h-full bg-slate-200 rounded-[3rem] overflow-hidden border-4 border-white shadow-2xl img-placeholder">
                        <!-- INSTRUCTION: Remplace "profile.jpg" par le nom de TA PHOTO présente dans ton dossier GitHub -->
                        <img src="profile.jpg" alt="Douae Boudik" 
                             onerror="this.style.display='none'; this.parentElement.innerHTML='<i class=\'fas fa-user fa-5x text-slate-400\'></i><p class=\'absolute bottom-10 font-bold text-slate-400\'>Photo en attente</p>';"
                             class="w-full h-full object-cover grayscale-[20%] hover:grayscale-0 transition-all duration-700">
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- SECTION PARCOURS -->
    <section id="parcours" class="py-32 bg-white">
        <div class="max-w-7xl mx-auto px-6">
            <div class="grid grid-cols-1 lg:grid-cols-2 gap-20">
                <div data-aos="fade-up">
                    <h2 class="text-4xl font-black mb-8 leading-tight italic">Parcours & <br>Éducation</h2>
                    <div class="relative border-l-2 border-slate-100 ml-4 space-y-16 mt-12">
                        <div class="timeline-item relative pl-10">
                            <span class="text-blue-600 font-black text-sm uppercase tracking-widest">2023 — Présent</span>
                            <h3 class="text-2xl font-extrabold mt-2 italic">DUT - Techniques de Commercialisation</h3>
                            <p class="text-slate-800 font-bold mb-4">EST Salé (Université Mohammed V)</p>
                            <p class="text-slate-500 leading-relaxed font-medium">Spécialisation en Marketing digital, communication commerciale et analyse comportementale.</p>
                        </div>
                    </div>
                </div>

                <div class="bg-slate-50 rounded-[3rem] p-10 md:p-16" data-aos="fade-up" data-aos-delay="300">
                    <h3 class="text-2xl font-black mb-10">Soft Skills</h3>
                    <div class="space-y-8">
                        <div>
                            <div class="flex justify-between mb-3 font-bold text-sm"><span>Créativité</span><span>95%</span></div>
                            <div class="w-full bg-white h-2 rounded-full overflow-hidden"><div class="bg-blue-600 h-full w-[95%]"></div></div>
                        </div>
                        <div>
                            <div class="flex justify-between mb-3 font-bold text-sm"><span>Marketing Analytique</span><span>85%</span></div>
                            <div class="w-full bg-white h-2 rounded-full overflow-hidden"><div class="bg-purple-600 h-full w-[85%]"></div></div>
                        </div>
                        <div class="mt-12">
                            <h4 class="font-black text-lg mb-4 italic">Langues</h4>
                            <div class="flex flex-wrap gap-3">
                                <span class="px-4 py-2 bg-white rounded-xl shadow-sm border border-slate-100 font-bold">Arabe (Maternel)</span>
                                <span class="px-4 py-2 bg-white rounded-xl shadow-sm border border-slate-100 font-bold">Français (Bilingue)</span>
                                <span class="px-4 py-2 bg-white rounded-xl shadow-sm border border-slate-100 font-bold">Anglais (Avancé)</span>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- SECTION EXPERTISES -->
    <section id="competences" class="py-32 bg-slate-900 text-white">
        <div class="max-w-7xl mx-auto px-6 text-center">
            <h2 class="text-4xl md:text-5xl font-black mb-20 italic">Mes Expertises</h2>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <div class="p-10 bg-white/5 border border-white/10 rounded-[2.5rem] hover:bg-blue-600 transition-all group" data-aos="zoom-in">
                    <i class="fas fa-camera-retro text-4xl text-blue-500 mb-8 group-hover:text-white"></i>
                    <h3 class="text-2xl font-black mb-4 italic">Content Design</h3>
                    <p class="text-slate-400 group-hover:text-white font-medium">Production visuelle impactante (Canva, CapCut) pour Reels et TikTok.</p>
                </div>
                <div class="p-10 bg-white/5 border border-white/10 rounded-[2.5rem] hover:bg-purple-600 transition-all group" data-aos="zoom-in" data-aos-delay="100">
                    <i class="fas fa-ad text-4xl text-purple-500 mb-8 group-hover:text-white"></i>
                    <h3 class="text-2xl font-black mb-4 italic">Publicité Digitale</h3>
                    <p class="text-slate-400 group-hover:text-white font-medium">Initiation aux campagnes Meta Ads et Google Ads pour booster la visibilité.</p>
                </div>
                <div class="p-10 bg-white/5 border border-white/10 rounded-[2.5rem] hover:bg-pink-600 transition-all group" data-aos="zoom-in" data-aos-delay="200">
                    <i class="fas fa-users text-4xl text-pink-500 mb-8 group-hover:text-white"></i>
                    <h3 class="text-2xl font-black mb-4 italic">Social Strategy</h3>
                    <p class="text-slate-400 group-hover:text-white font-medium">Gestion de communauté et planification éditoriale stratégique.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- SECTION CONTACT -->
    <section id="contact" class="py-32 bg-white">
        <div class="max-w-4xl mx-auto px-6 text-center">
            <h2 class="text-5xl font-black mb-8 italic tracking-tighter">Contactez-moi</h2>
            <p class="text-slate-500 font-medium mb-16 text-lg">Disponible pour un stage immédiat à Rabat ou Salé.</p>
            
            <div class="flex flex-col md:flex-row justify-center gap-10">
                <a href="mailto:douae.boudik@email.ma" class="flex flex-col items-center gap-4 p-8 bg-slate-50 rounded-[2rem] hover:bg-blue-50 transition-colors w-full">
                    <div class="w-14 h-14 bg-blue-600 text-white rounded-full flex items-center justify-center text-xl shadow-lg"><i class="fas fa-envelope"></i></div>
                    <span class="font-black">douae.boudik@email.ma</span>
                </a>
                <a href="https://linkedin.com/in/votre-profil" target="_blank" class="flex flex-col items-center gap-4 p-8 bg-slate-50 rounded-[2rem] hover:bg-blue-50 transition-colors w-full">
                    <div class="w-14 h-14 bg-blue-700 text-white rounded-full flex items-center justify-center text-xl shadow-lg"><i class="fab fa-linkedin-in"></i></div>
                    <span class="font-black">LinkedIn</span>
                </a>
            </div>
        </div>
    </section>

    <footer class="py-12 bg-white border-t border-slate-100 text-center">
        <p class="text-slate-400 font-bold text-xs uppercase tracking-widest italic">
            © 2024 Douae Boudik — EST Salé — Rabat / Salé
        </p>
    </footer>

    <script>
        AOS.init({ duration: 1000, once: true });
    </script>
</body>
</html>
