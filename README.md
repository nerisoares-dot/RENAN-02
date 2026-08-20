<!DOCTYPE html>
<html lang="pt-BR" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nexus Studio | Agência Digital</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-slate-50 text-slate-800 font-sans antialiased">

    <!-- ✅ NAVEGAÇÃO -->
    <header class="fixed top-0 left-0 w-full bg-white/90 backdrop-blur-md shadow-xs z-50">
        <nav class="max-w-7xl mx-auto px-6 py-4 flex justify-between items-center">
            <a href="#" class="text-2xl font-bold text-indigo-600 tracking-tight">NEXUS.</a>
            
            <!-- Menu Desktop -->
            <ul class="hidden md:flex space-x-8 font-medium">
                <li><a href="#inicio" class="hover:text-indigo-600 transition">Início</a></li>
                <li><a href="#servicos" class="hover:text-indigo-600 transition">Serviços</a></li>
                <li><a href="#sobre" class="hover:text-indigo-600 transition">Sobre</a></li>
                <li><a href="#contato" class="hover:text-indigo-600 transition">Contato</a></li>
            </ul>

            <!-- Botão de Ação -->
            <div class="hidden md:block">
                <a href="#contato" class="bg-indigo-600 text-white px-5 py-2 rounded-lg font-medium hover:bg-indigo-700 transition">Fazer Orçamento</a>
            </div>

            <!-- Botão Menu Mobile -->
            <button id="menu-btn" class="md:hidden text-slate-800 focus:outline-none" aria-label="Abrir menu">
                <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16"></path></svg>
            </button>
        </nav>

        <!-- Menu Mobile Dropdown -->
        <div id="mobile-menu" class="hidden md:hidden bg-white border-t border-slate-100 px-6 py-4 space-y-4 shadow-lg">
            <a href="#inicio" class="block font-medium hover:text-indigo-600">Início</a>
            <a href="#servicos" class="block font-medium hover:text-indigo-600">Serviços</a>
            <a href="#sobre" class="block font-medium hover:text-indigo-600">Sobre</a>
            <a href="#contato" class="block font-medium hover:text-indigo-600">Contato</a>
            <a href="#contato" class="block text-center bg-indigo-600 text-white px-4 py-2 rounded-lg font-medium">Fazer Orçamento</a>
        </div>
    </header>

    <!-- 💡 HERO SECTION (INÍCIO) -->
    <section id="inicio" class="pt-32 pb-20 md:pt-48 md:pb-32 bg-gradient-to-b from-indigo-50 to-white">
        <div class="max-w-7xl mx-auto px-6 grid md:grid-cols-2 gap-12 items-center">
            <div class="space-y-6 text-center md:text-left">
                <h1 class="text-4xl md:text-6xl font-extrabold text-slate-900 tracking-tight leading-tight">
                    Transforme sua presença <span class="text-indigo-600">digital</span>
                </h1>
                <p class="text-lg text-slate-600 max-w-xl mx-auto md:mx-0">
                    Criamos sites de alta performance, landing pages que convertem e sistemas sob medida para fazer o seu negócio decolar no ambiente online.
                </p>
                <div class="flex flex-col sm:flex-row justify-center md:justify-start gap-4 pt-2">
                    <a href="#servicos" class="bg-indigo-600 text-white text-center px-8 py-3.5 rounded-lg font-semibold hover:bg-indigo-700 shadow-lg shadow-indigo-200 transition">Conhecer Serviços</a>
                    <a href="#contato" class="bg-white text-slate-800 text-center px-8 py-3.5 rounded-lg font-semibold border border-slate-200 hover:bg-slate-50 transition">Falar com Consultor</a>
                </div>
            </div>
            <div class="relative flex justify-center">
                <div class="w-full max-w-md aspect-square bg-gradient-to-tr from-indigo-500 to-purple-600 rounded-3xl shadow-2xl rotate-3 transform transition hover:rotate-0 duration-500 flex items-center justify-center p-8 text-white text-7xl font-bold">
                    [ / ]
                </div>
            </div>
        </div>
    </section>

    <!-- 🛠️ SEÇÃO DE SERVIÇOS -->
    <section id="servicos" class="py-20 bg-white">
        <div class="max-w-7xl mx-auto px-6">
            <div class="text-center max-w-2xl mx-auto space-y-4 mb-16">
                <h2 class="text-3xl md:text-4xl font-bold text-slate-900">Nossas Especialidades</h2>
                <p class="text-slate-600">Soluções completas de ponta a ponta para garantir a melhor experiência para os seus clientes.</p>
            </div>
            
            <div class="grid md:grid-cols-3 gap-8">
                <!-- Card 1 -->
                <div class="p-8 rounded-2xl border border-slate-100 bg-slate-50/50 hover:bg-white hover:shadow-xl hover:border-transparent transition duration-300 space-y-4">
                    <div class="w-12 h-12 rounded-xl bg-indigo-100 flex items-center justify-center text-indigo-600 text-xl font-bold">💻</div>
                    <h3 class="text-xl font-bold text-slate-900">Desenvolvimento Web</h3>
                    <p class="text-slate-600 text-sm leading-relaxed">Sites institucionais, e-commerces e plataformas customizadas rápidas, seguras e responsivas.</p>
                </div>
                <!-- Card 2 -->
                <div class="p-8 rounded-2xl border border-slate-100 bg-slate-50/50 hover:bg-white hover:shadow-xl hover:border-transparent transition duration-300 space-y-4">
                    <div class="w-12 h-12 rounded-xl bg-indigo-100 flex items-center justify-center text-indigo-600 text-xl font-bold">🎨</div>
                    <h3 class="text-xl font-bold text-slate-900">UI/UX Design</h3>
                    <p class="text-slate-600 text-sm leading-relaxed">Interfaces modernas e protótipos focados na usabilidade e na jornada intuitiva do usuário.</p>
                </div>
                <!-- Card 3 -->
                <div class="p-8 rounded-2xl border border-slate-100 bg-slate-50/50 hover:bg-white hover:shadow-xl hover:border-transparent transition duration-300 space-y-4">
                    <div class="w-12 h-12 rounded-xl bg-indigo-100 flex items-center justify-center text-indigo-600 text-xl font-bold">📈</div>
                    <h3 class="text-xl font-bold text-slate-900">Otimização SEO</h3>
                    <p class="text-slate-600 text-sm leading-relaxed">Aplicação de técnicas avançadas para posicionar sua marca nas primeiras páginas do Google.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- 🔎 SEÇÃO SOBRE -->
    <section id="sobre" class="py-20 bg-slate-50">
        <div class="max-w-7xl mx-auto px-6 grid md:grid-cols-2 gap-12 items-center">
            <div class="space-y-6">
                <span class="text-xs font-bold uppercase tracking-wider text-indigo-600 bg-indigo-50 px-3 py-1 rounded-full">Quem Somos</span>
                <h2 class="text-3xl md:text-4xl font-bold text-slate-900">Criamos pontes entre ideias inovadoras e resultados reais</h2>
                <p class="text-slate-600 leading-relaxed">
                    Nascemos com a missão de descomplicar a tecnologia para empresas de todos os portes. Nossa equipe conta com desenvolvedores, designers e estrategistas obstinados por performance e estética visual.
                </p>
                <div class="grid grid-cols-2 gap-6 pt-4">
                    <div>
                        <h4 class="text-3xl font-extrabold text-indigo-600">98%</h4>
                        <p class="text-sm text-slate-600 font-medium">Clientes Satisfeitos</p>
                    </div>
                    <div>
                        <h4 class="text-3xl font-extrabold text-indigo-600">+150</h4>
                        <p class="text-sm text-slate-600 font-medium">Projetos Entregues</p>
                    </div>
                </div>
            </div>
            <div class="bg-indigo-900 rounded-3xl p-8 text-white space-y-6 shadow-xl">
                <h3 class="text-2xl font-bold">Por que escolher a Nexus?</h3>
                <ul class="space-y-4 text-indigo-100 text-sm">
                    <li class="flex items-start gap-3">
                        <span class="text-emerald-400 font-bold">✓</span> Código limpo, sustentável e fácil de manter.
                    </li>
                    <li class="flex items-start gap-3">
                        <span class="text-emerald-400 font-bold">✓</span> Suporte técnico ativo e transparente pós-entrega.
                    </li>
                    <li class="flex items-start gap-3">
                        <span class="text-emerald-400 font-bold">✓</span> Layouts 100% exclusivos focados no seu público-alvo.
                    </li>
                </ul>
            </div>
        </div>
    </section>

    <!-- 📅 SEÇÃO DE CONTATO -->
    <section id="contato" class="py-20 bg-white">
        <div class="max-w-3xl mx-auto px-6">
            <div class="text-center space-y-4 mb-12">
                <h2 class="text-3xl font-bold text-slate-900">Vamos tirar o seu projeto do papel?</h2>
                <p class="text-slate-600">Preencha os campos abaixo e nosso time responderá em até 24 horas úteis.</p>
            </div>

            <!-- Formulário Completo -->
            <form id="contact-form" class="space-y-6 bg-slate-50 p-8 rounded-2xl border border-slate-100 shadow-sm">
                <div class="grid sm:grid-cols-2 gap-6">
                    <div class="space-y-2">
                        <label for="name" class="text-xs font-bold text-slate-700 uppercase">Nome Completo</label>
                        <input type="text" id="name" required placeholder="Seu nome" class="w-full px-4 py-3 rounded-lg border border-slate-200 focus:outline-none focus:border-indigo-600 bg-white">
                    </div>
                    <div class="space-y-2">
                        <label for="email" class="text-xs font-bold text-slate-700 uppercase">E-mail</label>
                        <input type="email" id="email" required placeholder="seu@email.com" class="w-full px-4 py-3 rounded-lg border border-slate-200 focus:outline-none focus:border-indigo-600 bg-white">
                    </div>
                </div>
                <div class="space-y-2">
                    <label for="message" class="text-xs font-bold text-slate-700 uppercase">Mensagem</label>
                    <textarea id="message" rows="4" required placeholder="Conte um pouco sobre o seu projeto..." class="w-full px-4 py-3 rounded-lg border border-slate-200 focus:outline-none focus:border-indigo-600 bg-white"></textarea>
                </div>
                <button type="submit" class="w-full bg-indigo-600 text-white font-semibold py-3.5 rounded-lg hover:bg-indigo-700 transition">Enviar Mensagem</button>
            </form>
        </div>
    </section>

    <script>
        // Toggle do Menu Mobile
        const menuBtn = document.getElementById('menu-btn');
        const mobileMenu = document.getElementById('mobile-menu');

        menuBtn.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
        });
    </script>
</body>
</html>