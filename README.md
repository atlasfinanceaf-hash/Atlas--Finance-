<!-- index.html -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Atlas Financial | Premium Banking</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;600;700&family=Inter:wght@300;400;500;600&display=swap" rel="stylesheet">
    <script src="https://unpkg.com/lucide@latest"></script>
    <style>
        body { font-family: 'Inter', sans-serif; background-color: #0a0e1a; color: #e2e8f0; }
        .serif { font-family: 'Playfair Display', serif; }
        .glass { background: rgba(255, 255, 255, 0.03); backdrop-filter: blur(20px); border: 1px solid rgba(255, 255, 255, 0.1); }
        .glass-dark { background: rgba(0, 0, 0, 0.4); backdrop-filter: blur(20px); border: 1px solid rgba(255, 255, 255, 0.05); }
        .gradient-text { background: linear-gradient(135deg, #60a5fa 0%, #c084fc 100%); -webkit-background-clip: text; -webkit-text-fill-color: transparent; }
        .pulse-glow { animation: pulseGlow 2s infinite; }
        @keyframes pulseGlow { 0%, 100% { box-shadow: 0 0 20px rgba(96, 165, 250, 0.3); } 50% { box-shadow: 0 0 40px rgba(96, 165, 250, 0.6); } }
        .hover-lift { transition: transform 0.3s ease; }
        .hover-lift:hover { transform: translateY(-5px); }
    </style>
</head>
<body class="antialiased overflow-x-hidden">

    <nav class="fixed w-full z-50 glass border-b border-white/10 h-20 flex items-center">
        <div class="max-w-7xl mx-auto px-6 w-full flex justify-between items-center">
            <div class="flex items-center space-x-2">
                <div class="w-10 h-10 bg-gradient-to-br from-blue-500 to-purple-600 rounded-xl flex items-center justify-center">
                    <i data-lucide="landmark" class="w-6 h-6 text-white"></i>
                </div>
                <span class="text-2xl font-bold serif">Atlas</span>
            </div>
            <div class="hidden md:flex space-x-8">
                <a href="#features" class="text-gray-300 hover:text-white transition">Features</a>
                <a href="#security" class="text-gray-300 hover:text-white transition">Security</a>
                <a href="#contact" class="text-gray-300 hover:text-white transition">Contact</a>
            </div>
            <button class="bg-blue-600 hover:bg-blue-500 text-white px-6 py-2 rounded-full text-sm font-medium pulse-glow transition-all">Open Account</button>
        </div>
    </nav>

    <main class="pt-32">
        <section class="max-w-7xl mx-auto px-6 py-20 grid lg:grid-cols-2 gap-12 items-center">
            <div class="space-y-6">
                <div class="inline-block px-4 py-2 rounded-full bg-blue-500/10 border border-blue-500/20 text-blue-400 text-sm">
                    🚀 Now serving 50,000+ clients
                </div>
                <h1 class="text-5xl md:text-6xl font-bold serif leading-tight">Banking for the <span class="gradient-text">Modern Era</span></h1>
                <p class="text-xl text-gray-400">Institutional-grade security meets intuitive design. Experience wealth management reimagined for the digital age.</p>
                <div class="flex flex-wrap gap-4">
                    <button class="bg-white text-black px-8 py-4 rounded-full font-bold flex items-center gap-2 hover:bg-gray-100 transition">
                        Get Started <i data-lucide="arrow-right" class="w-5 h-5"></i>
                    </button>
                    <button class="glass px-8 py-4 rounded-full font-medium flex items-center gap-2 hover:bg-white/5 transition">
                        <i data-lucide="play-circle" class="w-5 h-5"></i> Watch Demo
                    </button>
                </div>
                <div class="flex items-center gap-4 pt-4">
                    <div class="flex -space-x-2">
                        <img src="https://i.pravatar.cc/100?img=1" class="w-10 h-10 rounded-full border-2 border-[#0a0e1a]" alt="User">
                        <img src="https://i.pravatar.cc/100?img=2" class="w-10 h-10 rounded-full border-2 border-[#0a0e1a]" alt="User">
                        <img src="https://i.pravatar.cc/100?img=3" class="w-10 h-10 rounded-full border-2 border-[#0a0e1a]" alt="User">
                    </div>
                    <p class="text-sm text-gray-400">Trusted by <span class="text-white font-semibold">10,000+</span> investors</p>
                </div>
            </div>
            <div class="glass rounded-3xl p-8 border border-white/20 shadow-2xl hover-lift">
                <div class="flex justify-between items-start mb-6">
                    <div>
                        <p class="text-sm text-gray-400">Total Balance</p>
                        <h3 class="text-4xl font-bold serif">$84,392.50</h3>
                        <p class="text-green-400 text-sm mt-1 flex items-center gap-1">
                            <i data-lucide="trending-up" class="w-4 h-4"></i> +12.5% this month
                        </p>
                    </div>
                    <div class="w-12 h-12 rounded-full bg-gradient-to-br from-blue-500 to-purple-600 flex items-center justify-center">
                        <i data-lucide="wallet" class="w-6 h-6 text-white"></i>
                    </div>
                </div>
                <div class="h-40 bg-blue-500/10 rounded-xl border border-blue-500/20 mb-4 flex items-end p-4 gap-2">
                    <div class="flex-1 bg-blue-500/60 h-1/3 rounded-t hover:bg-blue-500 transition-all cursor-pointer"></div>
                    <div class="flex-1 bg-blue-500/60 h-1/2 rounded-t hover:bg-blue-500 transition-all cursor-pointer"></div>
                    <div class="flex-1 bg-blue-500/60 h-2/3 rounded-t hover:bg-blue-500 transition-all cursor-pointer"></div>
                    <div class="flex-1 bg-blue-500/60 h-1/2 rounded-t hover:bg-blue-500 transition-all cursor-pointer"></div>
                    <div class="flex-1 bg-blue-500 h-full rounded-t hover:bg-blue-400 transition-all cursor-pointer shadow-lg shadow-blue-500/50"></div>
                    <div class="flex-1 bg-blue-500/60 h-3/4 rounded-t hover:bg-blue-500 transition-all cursor-pointer"></div>
                    <div class="flex-1 bg-blue-500/60 h-1/2 rounded-t hover:bg-blue-500 transition-all cursor-pointer"></div>
                </div>
                <div class="grid grid-cols-3 gap-4">
                    <button class="glass py-3 rounded-xl text-sm font-medium hover:bg-white/10 transition flex flex-col items-center gap-2">
                        <i data-lucide="send" class="w-5 h-5 text-blue-400"></i> Send
                    </button>
                    <button class="glass py-3 rounded-xl text-sm font-medium hover:bg-white/10 transition flex flex-col items-center gap-2">
                        <i data-lucide="download" class="w-5 h-5 text-purple-400"></i> Receive
                    </button>
                    <button class="glass py-3 rounded-xl text-sm font-medium hover:bg-white/10 transition flex flex-col items-center gap-2">
                        <i data-lucide="repeat" class="w-5 h-5 text-green-400"></i> Exchange
                    </button>
                </div>
            </div>
        </section>

        <section id="features" class="max-w-7xl mx-auto px-6 py-20 border-t border-white/10">
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-4xl font-bold serif mb-4">Why Choose Atlas?</h2>
                <p class="text-gray-400 max-w-2xl mx-auto">Experience banking that puts you first with cutting-edge technology and unparalleled security.</p>
            </div>
            <div class="grid md:grid-cols-3 gap-8">
                <div class="glass p-8 rounded-3xl hover-lift">
                    <div class="w-14 h-14 bg-blue-500/20 rounded-2xl flex items-center justify-center mb-6">
                        <i data-lucide="shield-check" class="w-7 h-7 text-blue-400"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3">Bank-Grade Security</h3>
                    <p class="text-gray-400">256-bit encryption and biometric authentication protect your assets 24/7.</p>
                </div>
                <div class="glass p-8 rounded-3xl hover-lift">
                    <div class="w-14 h-14 bg-purple-500/20 rounded-2xl flex items-center justify-center mb-6">
                        <i data-lucide="zap" class="w-7 h-7 text-purple-400"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3">Instant Transfers</h3>
                    <p class="text-gray-400">Send and receive money globally in seconds, not days. Zero hidden fees.</p>
                </div>
                <div class="glass p-8 rounded-3xl hover-lift">
                    <div class="w-14 h-14 bg-green-500/20 rounded-2xl flex items-center justify-center mb-6">
                        <i data-lucide="pie-chart" class="w-7 h-7 text-green-400"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3">Smart Analytics</h3>
                    <p class="text-gray-400">AI-powered insights help you grow your wealth with personalized recommendations.</p>
                </div>
            </div>
        </section>

        <section id="contact" class="max-w-7xl mx-auto px-6 py-20 border-t border-white/10">
            <div class="max-w-4xl mx-auto glass-dark p-8 md:p-12 rounded-3xl text-center">
                <h2 class="text-3xl font-bold serif mb-4">Ready to begin?</h2>
                <p class="text-gray-400 mb-8">Join thousands of forward-thinking investors. No minimum deposit required.</p>
                <form onsubmit="event.preventDefault(); showSuccess();" class="max-w-md mx-auto space-y-4">
                    <input type="email" placeholder="Enter your email" required 
                        class="w-full bg-white/5 border border-white/10 rounded-xl px-6 py-4 text-white placeholder-gray-500 focus:outline-none focus:border-blue-500 transition">
                    <button type="submit" class="w-full bg-gradient-to-r from-blue-600 to-purple-600 py-4 rounded-xl font-bold text-lg hover:opacity-90 transition pulse-glow">
                        Request Early Access
                    </button>
                </form>
                <p id="success-msg" class="text-green-400 mt-4 hidden">✓ You're on the list! Check your inbox.</p>
            </div>
        </section>
    </main>

    <footer class="border-t border-white/10 py-12 mt-20">
        <div class="max-w-7xl mx-auto px-6 grid md:grid-cols-4 gap-8">
            <div>
                <div class="flex items-center space-x-2 mb-4">
                    <div class="w-8 h-8 bg-gradient-to-br from-blue-500 to-purple-600 rounded-lg flex items-center justify-center">
                        <i data-lucide="landmark" class="w-5 h-5 text-white"></i>
                    </div>
                    <span class="text-xl font-bold serif">Atlas</span>
                </div>
                <p class="text-gray-500 text-sm">Banking reimagined for the modern era. Secure, fast, intuitive.</p>
            </div>
            <div>
                <h4 class="font-semibold mb-4">Product</h4>
                <ul class="space-y-2 text-gray-400 text-sm">
                    <li><a href="#" class="hover:text-white transition">Features</a></li>
                    <li><a href="#" class="hover:text-white transition">Security</a></li>
                    <li><a href="#" class="hover:text-white transition">Enterprise</a></li>
                </ul>
            </div>
            <div>
                <h4 class="font-semibold mb-4">Company</h4>
                <ul class="space-y-2 text-gray-400 text-sm">
                    <li><a href="#" class="hover:text-white transition">About</a></li>
                    <li><a href="#" class="hover:text-white transition">Careers</a></li>
                    <li><a href="#" class="hover:text-white transition">Contact</a></li>
                </ul>
            </div>
            <div>
                <h4 class="font-semibold mb-4">Legal</h4>
                <ul class="space-y-2 text-gray-400 text-sm">
                    <li><a href="#" class="hover:text-white transition">Privacy</a></li>
                    <li><a href="#" class="hover:text-white transition">Terms</a></li>
                    <li><a href="#" class="hover:text-white transition">Cookies</a></li>
                </ul>
            </div>
        </div>
        <div class="max-w-7xl mx-auto px-6 mt-12 pt-8 border-t border-white/5 text-center text-gray-600 text-sm">
            <p>© 2026 Atlas Financial Group. All rights reserved.</p>
        </div>
    </footer>

    <script>
        lucide.createIcons();
        
        function showSuccess() {
            const msg = document.getElementById('success-msg');
            msg.classList.remove('hidden');
            setTimeout(() => msg.classList.add('hidden'), 5000);
        }

        // Smooth scroll
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });
    </script>
</body>
</html>
# Atlas--Finance-
