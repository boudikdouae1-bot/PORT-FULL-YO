<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CV Digital - Douae Boudik</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@300;400;600;700;800&display=swap');
        
        body {
            font-family: 'Plus Jakarta Sans', sans-serif;
            scroll-behavior: smooth;
        }

        .gradient-text {
            background: linear-gradient(135deg, #3b82f6, #8b5cf6);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        .skill-card {
            transition: all 0.4s cubic-bezier(0.175, 0.885, 0.32, 1.275);
        }

        .skill-card:hover {
            transform: translateY(-12px);
            box-shadow: 0 25px 50px -12px rgba(59, 130, 246, 0.15);
        }

        .nav-blur {
            background: rgba(255, 255, 255, 0.8);
            backdrop-filter: blur(16px);
            border-bottom: 1px solid rgba(241, 245, 249, 1);
        }

        .hero-blob {
            position: absolute;
            width: 450px;
            height: 450px;
            background: radial-gradient(circle, rgba(59, 130, 246, 0.1) 0%, rgba(139, 92, 246, 0.05) 100%);
            filter: blur(60px);
            border-radius: 50%;
            z-index: -1;
        }
    </style>
</head>
<body class="bg-slate-50 text-slate-900 selection:bg-blue-100 selection:text-blue-900">

    <!-- Barre de Navigation -->
    <nav class="fixed w-full z-50 nav-blur">
        <div class="max-w-7xl mx-auto px-6 py-5 flex justify-between items-center">
            <span class="text-2xl font-extrabold tracking-tight gradient-text">Douae Boudik</span>
            <div class="hidden md:flex space-x-10 font-bold items-center text-sm uppercase tracking-widest text-slate-600">
                <a href="#accueil" class="hover:text-blue-600 transition-colors">Accueil</a>
                <a href="#parcours" class="hover:text-blue-600 transition-colors">Parcours</a>
                <a href="#competences" class="hover:text-blue-600 transition-colors">Expertises</a>
                <a href="#contact" class="px-6 py-3 bg-slate-900 text-white rounded-full hover:bg-blue-600 transition-all shadow-lg active:scale-95">Contact</a>
            </div>
        </div>
    </nav>

    <!-- Section Hero -->
    <section id="accueil" class="relative pt-44 pb-32 px-6">
        <div class="hero-blob -top-20 -left-20 animate-pulse"></div>
        <div class="hero-blob top-1/2 -right-20" style="background: radial-gradient(circle, rgba(139, 92, 246, 0.1) 0%, transparent 100%);"></div>
        
        <div class="max-w-7xl mx-auto flex flex-col md:flex-row items-center gap-20">
            <div class="flex-1 text-center md:text-left">
                <div class="inline-flex items-center gap-3 px-5 py-2 bg-white border border-slate-200 text-blue-600 rounded-full text-xs font-black uppercase tracking-[0.2em] mb-8 shadow-sm">
                    <span class="w-2 h-2 bg-blue-600 rounded-full animate-ping"></span>
                    Disponible pour un stage — Rabat / Salé
                </div>
                <h1 class="text-6xl md:text-8xl font-black mb-8 leading-[0.9] tracking-tighter">
                    Douae <br><span class="gradient-text">Boudik</span>
                </h1>
                <p class="text-xl text-slate-500 mb-12 max-w-2xl leading-relaxed font-medium">
                    Étudiante en 2ème année à l'**EST de Salé**. Future experte en marketing digital, alliant créativité graphique et analyse stratégique pour booster votre présence en ligne.
                </p>
                <div class="flex flex-wrap justify-center md:justify-start gap-6">
                    <a href="#contact" class="px-10 py-5 bg-blue-600 text-white font-extrabold rounded-2xl hover:bg-blue-700 transition-all transform hover:-translate-y-1 shadow-2xl shadow-blue-200">
                        Me recruter
                    </a>
                    <button onclick="window.print()" class="px-10 py-5 bg-white border-2 border-slate-100 font-extrabold rounded-2xl hover:bg-slate-50 hover:border-slate-200 transition-all shadow-sm flex items-center gap-3">
                        <i class="fas fa-file-pdf text-red-500"></i> Télécharger CV
                    </button>
                </div>
            </div>
            
            <div class="flex-1 flex justify-center">
                <div class="relative group">
                    <div class="absolute -inset-4 bg-gradient-to-tr from-blue-600 to-purple-600 rounded-[3rem] opacity-20 blur-2xl group-hover:opacity-30 transition duration-500"></div>
                    <div class="relative w-80 h-80 md:w-[450px] md:h-[450px] bg-white rounded-[2.5rem] overflow-hidden shadow-2xl border-8 border-white">
                        <img src="https://images.unsplash.com/photo-1573496359142-b8d87734a5a2?auto=format&fit=crop&q=80&w=800" alt="Portrait de Douae Boudik" class="w-full h-full object-cover">
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Section Parcours -->
    <section id="parcours" class="py-32 bg-white">
        <div class="max-w-5xl mx-auto px-6">
            <div class="flex flex-col md:flex-row md:items-end justify-between mb-20 gap-6">
                <div>
                    <h2 class="text-4xl font-black mb-4">Parcours Académique</h2>
                    <p class="text-slate-500 font-medium">Mon évolution au sein de l'EST Salé</p>
                </div>
                <div class="h-1 flex-1 bg-slate-100 mx-10 hidden md:block mb-5"></div>
            </div>
            
            <div class="space-y-16">
                <!-- EST SALÉ -->
                <div class="group relative pl-12 border-l-4 border-blue-500">
                    <div class="absolute -left-[14px] top-0 w-6 h-6 bg-white border-4 border-blue-500 rounded-full group-hover:scale-125 transition-transform"></div>
                    <div class="flex flex-col md:flex-row md:justify-between md:items-start mb-4">
                        <div>
                            <h3 class="text-2xl font-extrabold mb-1">DUT - Techniques de Commercialisation</h3>
                            <p class="text-blue-600 font-bold">EST Salé (Université Mohammed V)</p>
                        </div>
                        <span class="mt-2 md:mt-0 px-4 py-2 bg-blue-50 text-blue-700 rounded-xl text-sm font-black">2023 — EN COURS</span>
                    </div>
                    <p class="text-slate-600 leading-relaxed max-w-3xl">
                        Spécialisation en Marketing et Communication. Apprentissage intensif du marketing opérationnel, de la gestion de la relation client et des stratégies de vente. Participation active à des projets tutorés de création d'entreprise.
                    </p>
                </div>

                <!-- Expérience Pro -->
                <div class="group relative pl-12 border-l-4 border-purple-500">
                    <div class="absolute -left-[14px] top-0 w-6 h-6 bg-white border-4 border-purple-500 rounded-full group-hover:scale-125 transition-transform"></div>
                    <div class="flex flex-col md:flex-row md:justify-between md:items-start mb-4">
                        <div>
                            <h3 class="text-2xl font-extrabold mb-1">Stage & Projets Digitaux</h3>
                            <p class="text-purple-600 font-bold">Marketing Digital & Social Media</p>
                        </div>
                        <span class="mt-2 md:mt-0 px-4 py-2 bg-purple-50 text-purple-700 rounded-xl text-sm font-black">ÉTÉ 2024</span>
                    </div>
                    <ul class="space-y-4 text-slate-600 font-medium">
                        <li class="flex items-center gap-4">
                            <span class="w-2 h-2 bg-purple-500 rounded-full"></span>
                            Conception de chartes graphiques pour des micro-entreprises locales.
                        </li>
                        <li class="flex items-center gap-4">
                            <span class="w-2 h-2 bg-purple-500 rounded-full"></span>
                            Optimisation de profils professionnels (LinkedIn/Instagram).
                        </li>
                        <li class="flex items-center gap-4">
                            <span class="w-2 h-2 bg-purple-500 rounded-full"></span>
                            Rédaction de contenus publicitaires (Copywriting).
                        </li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <!-- Section Compétences -->
    <section id="competences" class="py-32 bg-slate-50">
        <div class="max-w-7xl mx-auto px-6">
            <h2 class="text-center text-4xl font-black mb-20 tracking-tight">Expertises Techniques</h2>
            
            <div class="grid grid-cols-1 md:grid-cols-3 gap-10">
                <!-- Social Media -->
                <div class="skill-card bg-white p-10 rounded-[2.5rem] border border-slate-100 shadow-sm">
                    <div class="w-20 h-20 bg-blue-50 text-blue-600 rounded-3xl flex items-center justify-center mb-8 text-3xl">
                        <i class="fab fa-instagram"></i>
                    </div>
                    <h3 class="text-2xl font-extrabold mb-4">Social Media</h3>
                    <p class="text-slate-500 font-medium leading-relaxed">
                        Maîtrise de l'algorithme Instagram et TikTok. Planification éditoriale et gestion de communauté engagée.
                    </p>
                </div>

                <!-- Création -->
                <div class="skill-card bg-white p-10 rounded-[2.5rem] border border-slate-100 shadow-sm">
                    <div class="w-20 h-20 bg-purple-50 text-purple-600 rounded-3xl flex items-center justify-center mb-8 text-3xl">
                        <i class="fas fa-paint-brush"></i>
                    </div>
                    <h3 class="text-2xl font-extrabold mb-4">Content Design</h3>
                    <p class="text-slate-500 font-medium leading-relaxed">
                        Création de visuels impactants sur Canva et montage vidéo dynamique via CapCut pour les formats Reels/Shorts.
                    </p>
                </div>

                <!-- Stratégie -->
                <div class="skill-card bg-white p-10 rounded-[2.5rem] border border-slate-100 shadow-sm">
                    <div class="w-20 h-20 bg-emerald-50 text-emerald-600 rounded-3xl flex items-center justify-center mb-8 text-3xl">
                        <i class="fas fa-chart-line"></i>
                    </div>
                    <h3 class="text-2xl font-extrabold mb-4">Marketing Mix</h3>
                    <p class="text-slate-500 font-medium leading-relaxed">
                        Analyse de marché, positionnement de marque et fondamentaux de la vente acquis durant mon cursus à l'EST Salé.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- Section Contact -->
    <section id="contact" class="py-32 bg-white">
        <div class="max-w-6xl mx-auto px-6">
            <div class="bg-slate-900 rounded-[3rem] p-10 md:p-20 text-white relative overflow-hidden shadow-2xl">
                <div class="absolute bottom-0 right-0 w-96 h-96 bg-blue-600/10 rounded-full blur-3xl -mb-48 -mr-48"></div>
                
                <div class="grid grid-cols-1 lg:grid-cols-2 gap-20 relative z-10">
                    <div>
                        <h2 class="text-5xl font-black mb-8 leading-tight">Donnons vie <br>à vos projets <span class="text-blue-500">digitaux</span>.</h2>
                        <p class="text-slate-400 text-lg mb-12 font-medium">Je suis disponible pour un entretien immédiat à Rabat ou Salé pour discuter de mon futur stage.</p>
                        
                        <div class="space-y-8">
                            <div class="flex items-center gap-6 group">
                                <div class="w-14 h-14 bg-white/10 rounded-2xl flex items-center justify-center group-hover:bg-blue-600 transition duration-300">
                                    <i class="fas fa-envelope text-xl"></i>
                                </div>
                                <span class="text-xl font-bold">douae.boudik@email.ma</span>
                            </div>
                            <div class="flex items-center gap-6 group">
                                <div class="w-14 h-14 bg-white/10 rounded-2xl flex items-center justify-center group-hover:bg-blue-600 transition duration-300">
                                    <i class="fab fa-linkedin-in text-xl"></i>
                                </div>
                                <span class="text-xl font-bold">linkedin.com/in/douae-boudik</span>
                            </div>
                        </div>
                    </div>

                    <div class="bg-white/5 backdrop-blur-sm border border-white/10 p-8 md:p-10 rounded-[2rem]">
                        <form onsubmit="event.preventDefault(); document.getElementById('success').classList.remove('hidden');" class="space-y-6">
                            <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                                <input type="text" placeholder="Nom Complet" class="w-full px-6 py-4 bg-white/5 border border-white/10 rounded-2xl focus:border-blue-500 outline-none transition font-bold" required>
                                <input type="email" placeholder="Email" class="w-full px-6 py-4 bg-white/5 border border-white/10 rounded-2xl focus:border-blue-500 outline-none transition font-bold" required>
                            </div>
                            <textarea placeholder="Comment puis-je vous aider ?" class="w-full px-6 py-4 bg-white/5 border border-white/10 rounded-2xl focus:border-blue-500 outline-none transition h-40 font-bold" required></textarea>
                            <button class="w-full py-5 bg-blue-600 hover:bg-blue-700 text-white font-black rounded-2xl transition shadow-xl active:scale-95">
                                Envoyer la proposition
                            </button>
                            <div id="success" class="hidden text-center p-4 bg-emerald-500/20 text-emerald-400 font-bold rounded-xl border border-emerald-500/30">
                                Message transmis avec succès !
                            </div>
                        </form>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="py-12 bg-slate-50 border-t border-slate-100 text-center">
        <p class="text-slate-400 font-bold text-sm tracking-widest uppercase">
            © 2024 Douae Boudik — EST Salé — Marketing & Communication
        </p>
    </footer>

</body>
</html>
