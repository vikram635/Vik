<!DOCTYPE html>
<html lang="en" class="dark scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Vikram R | Photography & Video Portfolio</title>
    
    <!-- Meta Tags -->
    <meta name="description" content="Official photography, cinematography, and digital media portfolio of Vikram R.">
    <meta name="author" content="Vikram R">
    
    <!-- Favicon -->
    <link rel="icon" href="data:image/svg+xml,<svg xmlns=%22http://www.w3.org/2000/svg%22 viewBox=%220 0 100 100%22><text y=%22.9em%22 font-size=%2290%22>VR</text></svg>">

    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            darkMode: 'class',
            theme: {
                extend: {
                    colors: {
                        brand: {
                            purple: '#8b5cf6',
                            pink: '#ec4899',
                            dark: '#09090b',
                            cardDark: 'rgba(24, 24, 27, 0.65)',
                            cardLight: 'rgba(255, 255, 255, 0.75)',
                        }
                    },
                    animation: {
                        'pulse-slow': 'pulse 4s cubic-bezier(0.4, 0, 0.6, 1) infinite',
                    }
                }
            }
        }
    </script>

    <!-- Font Awesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">

    <!-- Custom Glassmorphism Styles -->
    <style>
        body {
            font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, sans-serif;
            transition: background-color 0.3s, color 0.3s;
        }

        .dark body {
            background-color: #09090b;
            color: #f4f4f5;
        }

        body:not(.dark) {
            background-color: #f4f4f5;
            color: #18181b;
        }

        .glass-card {
            backdrop-filter: blur(16px);
            -webkit-backdrop-filter: blur(16px);
            transition: all 0.3s ease;
        }

        .dark .glass-card {
            background: rgba(24, 24, 27, 0.6);
            border: 1px solid rgba(255, 255, 255, 0.1);
        }

        body:not(.dark) .glass-card {
            background: rgba(255, 255, 255, 0.7);
            border: 1px solid rgba(0, 0, 0, 0.08);
            box-shadow: 0 8px 30px rgba(0,0,0,0.04);
        }

        .glass-nav {
            backdrop-filter: blur(20px);
            -webkit-backdrop-filter: blur(20px);
        }

        .dark .glass-nav {
            background: rgba(9, 9, 11, 0.8);
            border-bottom: 1px solid rgba(255, 255, 255, 0.1);
        }

        body:not(.dark) .glass-nav {
            background: rgba(244, 244, 245, 0.8);
            border-bottom: 1px solid rgba(0, 0, 0, 0.08);
        }

        .text-gradient {
            background: linear-gradient(135deg, #8b5cf6 0%, #ec4899 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        /* Custom Scrollbar */
        ::-webkit-scrollbar { width: 8px; }
        ::-webkit-scrollbar-track { background: transparent; }
        ::-webkit-scrollbar-thumb { background: #3f3f46; border-radius: 4px; }
        ::-webkit-scrollbar-thumb:hover { background: #8b5cf6; }
    </style>
</head>
<body class="relative min-h-screen flex flex-col justify-between selection:bg-purple-500 selection:text-white">

    <!-- Toast Notification Container -->
    <div id="toast-container" class="fixed top-24 right-5 z-50 flex flex-col gap-3 pointer-events-none"></div>

    <!-- Confirmation Modal -->
    <div id="confirm-modal" class="fixed inset-0 z-50 hidden items-center justify-center bg-black/70 backdrop-blur-sm p-4">
        <div class="glass-card max-w-md w-full p-6 rounded-2xl space-y-4">
            <h3 id="confirm-title" class="text-xl font-bold">Confirm Action</h3>
            <p id="confirm-msg" class="text-sm opacity-80">Are you sure you want to proceed?</p>
            <div class="flex justify-end gap-3 pt-2">
                <button id="confirm-cancel" class="px-4 py-2 text-sm rounded-xl border border-zinc-500/30 hover:bg-zinc-500/10 transition">Cancel</button>
                <button id="confirm-ok" class="px-4 py-2 text-sm rounded-xl bg-red-600 hover:bg-red-700 text-white transition">Delete</button>
            </div>
        </div>
    </div>

    <!-- Ambient Glow Background -->
    <div class="fixed top-0 left-1/4 w-96 h-96 bg-purple-600/15 rounded-full filter blur-[120px] pointer-events-none -z-10 animate-pulse-slow"></div>
    <div class="fixed bottom-1/4 right-1/4 w-96 h-96 bg-pink-600/15 rounded-full filter blur-[120px] pointer-events-none -z-10 animate-pulse-slow"></div>

    <!-- Navigation Header -->
    <header class="fixed top-0 left-0 w-full z-40 glass-nav transition-all duration-300">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 h-20 flex items-center justify-between">
            <!-- Brand -->
            <a href="#home" onclick="navigateTo('home')" class="flex items-center gap-3 group">
                <div id="logo-icon" class="w-10 h-10 rounded-xl bg-gradient-to-tr from-purple-600 to-pink-500 flex items-center justify-center text-white font-bold text-lg shadow-lg shadow-purple-500/20 group-hover:scale-105 transition-transform">
                    VR
                </div>
                <span id="logo-text" class="text-xl font-black tracking-wider text-gradient uppercase">Vikram R</span>
            </a>

            <!-- Desktop Nav -->
            <nav class="hidden lg:flex items-center gap-6 text-sm font-semibold">
                <a href="#home" onclick="navigateTo('home')" class="nav-btn hover:text-purple-400 transition-colors">Home</a>
                <a href="#about" onclick="navigateTo('about')" class="nav-btn hover:text-purple-400 transition-colors">About</a>
                <a href="#photos" onclick="navigateTo('photos')" class="nav-btn hover:text-purple-400 transition-colors">Photos</a>
                <a href="#videos" onclick="navigateTo('videos')" class="nav-btn hover:text-purple-400 transition-colors">Videos</a>
                <a href="#albums" onclick="navigateTo('albums')" class="nav-btn hover:text-purple-400 transition-colors">Albums</a>
                <a href="#contact" onclick="navigateTo('contact')" class="nav-btn hover:text-purple-400 transition-colors">Contact</a>
            </nav>

            <!-- Actions & User Controls -->
            <div class="hidden lg:flex items-center gap-4">
                <button id="theme-toggle" onclick="toggleTheme()" class="p-2.5 rounded-xl glass-card hover:text-purple-400 transition-colors" title="Toggle Theme">
                    <i class="fa-solid fa-moon text-lg dark:hidden"></i>
                    <i class="fa-solid fa-sun text-lg hidden dark:block"></i>
                </button>

                <div id="nav-auth-container" class="flex items-center gap-3">
                    <!-- Dynamic Auth State rendered by JS -->
                </div>
            </div>

            <!-- Mobile Menu Toggle -->
            <div class="flex items-center gap-3 lg:hidden">
                <button onclick="toggleTheme()" class="p-2 rounded-xl glass-card">
                    <i class="fa-solid fa-moon text-lg dark:hidden"></i>
                    <i class="fa-solid fa-sun text-lg hidden dark:block"></i>
                </button>
                <button onclick="toggleMobileMenu()" class="p-2 rounded-xl glass-card text-xl">
                    <i class="fa-solid fa-bars"></i>
                </button>
            </div>
        </div>

        <!-- Mobile Drawer -->
        <div id="mobile-menu" class="hidden lg:hidden glass-card border-t border-zinc-700/30 px-6 py-6 space-y-4">
            <a href="#home" onclick="navigateTo('home'); toggleMobileMenu()" class="block font-semibold">Home</a>
            <a href="#about" onclick="navigateTo('about'); toggleMobileMenu()" class="block font-semibold">About</a>
            <a href="#photos" onclick="navigateTo('photos'); toggleMobileMenu()" class="block font-semibold">Photos</a>
            <a href="#videos" onclick="navigateTo('videos'); toggleMobileMenu()" class="block font-semibold">Videos</a>
            <a href="#albums" onclick="navigateTo('albums'); toggleMobileMenu()" class="block font-semibold">Albums</a>
            <a href="#contact" onclick="navigateTo('contact'); toggleMobileMenu()" class="block font-semibold">Contact</a>
            <div id="mobile-auth-container" class="pt-4 border-t border-zinc-700/30 flex flex-col gap-3"></div>
        </div>
    </header>

    <!-- MAIN CONTENT VIEW ROUTER -->
    <main class="flex-grow pt-28 pb-16 px-4 sm:px-6 lg:px-8 max-w-7xl mx-auto w-full">

        <!-- VIEW: HOME -->
        <section id="view-home" class="view-section hidden space-y-20">
            <!-- Hero -->
            <div class="grid lg:grid-cols-12 gap-12 items-center min-h-[70vh]">
                <div class="lg:col-span-7 space-y-6 text-center lg:text-left">
                    <div class="inline-flex items-center gap-2 px-4 py-2 rounded-full glass-card text-xs font-bold uppercase tracking-widest text-purple-400">
                        <span class="w-2 h-2 rounded-full bg-green-400 animate-ping"></span> Visual Storyteller
                    </div>
                    <h1 class="text-4xl sm:text-6xl font-black tracking-tight">
                        Visualizing World Through <span class="text-gradient">Vikram R</span>
                    </h1>
                    <p id="hero-tagline" class="text-base sm:text-xl text-zinc-400 leading-relaxed max-w-2xl mx-auto lg:mx-0">
                        Capturing timeless photography, cinematic video stories, and high-impact digital experiences across the globe.
                    </p>
                    <div class="flex flex-wrap items-center justify-center lg:justify-start gap-4 pt-4">
                        <button onclick="navigateTo('photos')" class="px-7 py-3.5 rounded-full bg-gradient-to-r from-purple-600 to-pink-600 text-white font-bold text-sm shadow-lg shadow-purple-500/25 hover:scale-105 transition">
                            <i class="fa-solid fa-camera mr-2"></i> View Photos
                        </button>
                        <button onclick="navigateTo('videos')" class="px-7 py-3.5 rounded-full glass-card hover:bg-zinc-800/50 font-bold text-sm transition border border-zinc-500/20">
                            <i class="fa-solid fa-film mr-2"></i> Watch Videos
                        </button>
                        <button onclick="navigateTo('contact')" class="px-7 py-3.5 rounded-full glass-card hover:bg-zinc-800/50 font-bold text-sm transition border border-zinc-500/20">
                            <i class="fa-regular fa-paper-plane mr-2"></i> Contact Me
                        </button>
                    </div>
                </div>
                <div class="lg:col-span-5 flex justify-center">
                    <div class="relative w-72 h-72 sm:w-80 sm:h-80 lg:w-96 lg:h-96">
                        <div class="absolute inset-0 rounded-3xl bg-gradient-to-tr from-purple-600 to-pink-600 blur-2xl opacity-40"></div>
                        <img id="hero-profile-img" src="https://images.unsplash.com/photo-1534528741775-53994a69daeb?auto=format&fit=crop&w=800&q=80" alt="Vikram R" class="relative w-full h-full object-cover rounded-3xl glass-card border border-white/20 shadow-2xl">
                    </div>
                </div>
            </div>

            <!-- Featured Highlights -->
            <div class="space-y-8">
                <div class="flex justify-between items-end">
                    <div>
                        <h2 class="text-2xl sm:text-3xl font-bold">Featured Works</h2>
                        <p class="text-sm text-zinc-400">Handpicked recent photos and video projects</p>
                    </div>
                    <button onclick="navigateTo('photos')" class="text-sm font-semibold text-purple-400 hover:text-purple-300">Explore All &rarr;</button>
                </div>
                <div id="home-featured-grid" class="grid sm:grid-cols-2 lg:grid-cols-3 gap-6"></div>
            </div>
        </section>

        <!-- VIEW: ABOUT -->
        <section id="view-about" class="view-section hidden space-y-12">
            <div class="text-center max-w-3xl mx-auto space-y-3">
                <h2 class="text-sm font-bold tracking-widest text-purple-400 uppercase">About Me</h2>
                <p class="text-3xl sm:text-4xl font-extrabold">The Creative Mind Behind Vikram R</p>
                <div class="w-20 h-1 bg-gradient-to-r from-purple-500 to-pink-500 mx-auto rounded-full"></div>
            </div>

            <div class="grid lg:grid-cols-12 gap-12 items-center">
                <div class="lg:col-span-5">
                    <div class="glass-card p-3 rounded-3xl overflow-hidden border border-white/10">
                        <img id="about-img" src="https://images.unsplash.com/photo-1507003211169-0a1dd7228f2d?auto=format&fit=crop&w=800&q=80" alt="Vikram R Profile" class="w-full h-96 object-cover rounded-2xl">
                    </div>
                </div>
                <div class="lg:col-span-7 space-y-6">
                    <h3 class="text-2xl font-bold">Hello! I'm Vikram R</h3>
                    <p id="about-text-bio" class="text-zinc-400 leading-relaxed">
                        I am a professional photographer, cinematographer, and visual content creator passionate about capturing raw human emotions, architecture, and breathtaking natural landscapes.
                    </p>
                    
                    <div class="space-y-3">
                        <h4 class="text-sm font-bold uppercase text-purple-400">Skills & Focus Areas</h4>
                        <div id="about-skills-list" class="flex flex-wrap gap-2">
                            <!-- Rendered by JS -->
                        </div>
                    </div>

                    <div class="pt-4 flex items-center gap-4">
                        <span class="text-sm font-bold text-zinc-400">Follow Me:</span>
                        <div id="about-social-links" class="flex gap-3 text-lg"></div>
                    </div>
                </div>
            </div>
        </section>

        <!-- VIEW: PHOTO GALLERY -->
        <section id="view-photos" class="view-section hidden space-y-8">
            <div class="flex flex-col md:flex-row justify-between items-start md:items-center gap-4">
                <div>
                    <h2 class="text-3xl font-extrabold">Photo Gallery</h2>
                    <p class="text-sm text-zinc-400">Explore photography collections and artistic captures</p>
                </div>
                <div class="flex flex-wrap gap-3 w-full md:w-auto">
                    <input type="text" id="photo-search" oninput="filterPhotos()" placeholder="Search photos..." class="px-4 py-2 rounded-xl bg-zinc-800/40 border border-zinc-700/40 text-sm focus:outline-none focus:border-purple-500 w-full sm:w-48">
                    <select id="photo-category-filter" onchange="filterPhotos()" class="px-4 py-2 rounded-xl bg-zinc-800/40 border border-zinc-700/40 text-sm focus:outline-none focus:border-purple-500">
                        <option value="ALL">All Categories</option>
                    </select>
                </div>
            </div>

            <div id="photo-grid" class="grid sm:grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-6"></div>
        </section>

        <!-- VIEW: VIDEO GALLERY -->
        <section id="view-videos" class="view-section hidden space-y-8">
            <div>
                <h2 class="text-3xl font-extrabold">Video Gallery</h2>
                <p class="text-sm text-zinc-400">Cinematic video reels, short films, and visual projects</p>
            </div>
            <div id="video-grid" class="grid sm:grid-cols-2 lg:grid-cols-3 gap-6"></div>
        </section>

        <!-- VIEW: ALBUMS -->
        <section id="view-albums" class="view-section hidden space-y-8">
            <div>
                <h2 class="text-3xl font-extrabold">Albums & Collections</h2>
                <p class="text-sm text-zinc-400">Curated themed collections of photos and video media</p>
            </div>
            <div id="albums-grid" class="grid sm:grid-cols-2 lg:grid-cols-3 gap-6"></div>
        </section>

        <!-- VIEW: SINGLE ALBUM DETAIL -->
        <section id="view-album-detail" class="view-section hidden space-y-8">
            <button onclick="navigateTo('albums')" class="text-sm font-semibold text-purple-400 hover:text-purple-300 flex items-center gap-2">
                <i class="fa-solid fa-arrow-left"></i> Back to All Albums
            </button>
            <div id="album-detail-header" class="glass-card p-6 rounded-2xl border border-white/10 space-y-2"></div>
            <div id="album-media-grid" class="grid sm:grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-6"></div>
        </section>

        <!-- VIEW: CONTACT -->
        <section id="view-contact" class="view-section hidden space-y-12">
            <div class="text-center max-w-2xl mx-auto space-y-3">
                <h2 class="text-3xl font-black">Get In Touch</h2>
                <p class="text-zinc-400 text-sm">Have a project, query, or collaboration request? Send a direct message.</p>
            </div>

            <div class="grid lg:grid-cols-12 gap-8 items-start">
                <div class="lg:col-span-5 glass-card p-8 rounded-2xl space-y-6">
                    <h3 class="text-xl font-bold">Contact Information</h3>
                    <div class="space-y-4 text-sm">
                        <p class="flex items-center gap-3"><i class="fa-solid fa-envelope text-purple-400"></i> contact@vikramr.com</p>
                        <p class="flex items-center gap-3"><i class="fa-solid fa-location-dot text-purple-400"></i> Available Worldwide (Remote / On-site)</p>
                    </div>
                    <div class="pt-4 border-t border-zinc-700/40 flex gap-4 text-xl">
                        <a id="whatsapp-btn" href="#" target="_blank" class="px-4 py-2.5 rounded-xl bg-green-600/20 text-green-400 border border-green-500/30 text-xs font-bold flex items-center gap-2 hover:bg-green-600/30 transition">
                            <i class="fa-brands fa-whatsapp text-lg"></i> WhatsApp Direct
                        </a>
                    </div>
                </div>

                <div class="lg:col-span-7 glass-card p-8 rounded-2xl">
                    <form onsubmit="handleContactSubmit(event)" class="space-y-4">
                        <div class="grid sm:grid-cols-2 gap-4">
                            <div>
                                <label class="block text-xs font-semibold mb-1">Name</label>
                                <input type="text" id="contact-name" required class="w-full px-4 py-2.5 rounded-xl bg-zinc-800/40 border border-zinc-700/40 text-sm focus:outline-none focus:border-purple-500">
                            </div>
                            <div>
                                <label class="block text-xs font-semibold mb-1">Email</label>
                                <input type="email" id="contact-email" required class="w-full px-4 py-2.5 rounded-xl bg-zinc-800/40 border border-zinc-700/40 text-sm focus:outline-none focus:border-purple-500">
                            </div>
                        </div>
                        <div>
                            <label class="block text-xs font-semibold mb-1">Subject</label>
                            <input type="text" id="contact-subject" required class="w-full px-4 py-2.5 rounded-xl bg-zinc-800/40 border border-zinc-700/40 text-sm focus:outline-none focus:border-purple-500">
                        </div>
                        <div>
                            <label class="block text-xs font-semibold mb-1">Message</label>
                            <textarea id="contact-message" rows="4" required class="w-full px-4 py-2.5 rounded-xl bg-zinc-800/40 border border-zinc-700/40 text-sm focus:outline-none focus:border-purple-500"></textarea>
                        </div>
                        <button type="submit" class="w-full py-3.5 rounded-xl bg-gradient-to-r from-purple-600 to-pink-600 text-white font-bold text-sm shadow-lg shadow-purple-500/25 hover:opacity-90 transition">
                            Send Message
                        </button>
                    </form>
                </div>
            </div>
        </section>

        <!-- VIEW: LOGIN -->
        <section id="view-login" class="view-section hidden max-w-md mx-auto">
            <div class="glass-card p-8 rounded-2xl space-y-6">
                <div class="text-center space-y-1">
                    <h2 class="text-2xl font-bold">Welcome Back</h2>
                    <p class="text-xs text-zinc-400">Log in to manage your account or admin panel</p>
                </div>
                <form onsubmit="handleLogin(event)" class="space-y-4">
                    <div>
                        <label class="block text-xs font-semibold mb-1">Email Address</label>
                        <input type="email" id="login-email" required class="w-full px-4 py-2.5 rounded-xl bg-zinc-800/40 border border-zinc-700/40 text-sm focus:outline-none focus:border-purple-500">
                    </div>
                    <div>
                        <label class="block text-xs font-semibold mb-1">Password</label>
                        <input type="password" id="login-password" required class="w-full px-4 py-2.5 rounded-xl bg-zinc-800/40 border border-zinc-700/40 text-sm focus:outline-none focus:border-purple-500">
                    </div>
                    <div class="flex items-center justify-between text-xs">
                        <label class="flex items-center gap-2"><input type="checkbox" id="login-remember" class="rounded border-zinc-700"> Remember Me</label>
                        <a href="#forgot-password" onclick="navigateTo('forgot-password')" class="text-purple-400 hover:underline">Forgot Password?</a>
                    </div>
                    <button type="submit" class="w-full py-3 rounded-xl bg-purple-600 text-white font-bold text-sm hover:bg-purple-700 transition">Log In</button>
                </form>
                <p class="text-xs text-center text-zinc-400">Don't have an account? <a href="#signup" onclick="navigateTo('signup')" class="text-purple-400 font-bold hover:underline">Sign Up</a></p>
            </div>
        </section>

        <!-- VIEW: SIGNUP -->
        <section id="view-signup" class="view-section hidden max-w-md mx-auto">
            <div class="glass-card p-8 rounded-2xl space-y-6">
                <div class="text-center space-y-1">
                    <h2 class="text-2xl font-bold">Create Account</h2>
                    <p class="text-xs text-zinc-400">Join Vikram R community</p>
                </div>
                <form onsubmit="handleSignup(event)" class="space-y-4">
                    <div>
                        <label class="block text-xs font-semibold mb-1">Full Name</label>
                        <input type="text" id="signup-name" required class="w-full px-4 py-2.5 rounded-xl bg-zinc-800/40 border border-zinc-700/40 text-sm focus:outline-none focus:border-purple-500">
                    </div>
                    <div>
                        <label class="block text-xs font-semibold mb-1">Email Address</label>
                        <input type="email" id="signup-email" required class="w-full px-4 py-2.5 rounded-xl bg-zinc-800/40 border border-zinc-700/40 text-sm focus:outline-none focus:border-purple-500">
                    </div>
                    <div>
                        <label class="block text-xs font-semibold mb-1">Password</label>
                        <input type="password" id="signup-password" required class="w-full px-4 py-2.5 rounded-xl bg-zinc-800/40 border border-zinc-700/40 text-sm focus:outline-none focus:border-purple-500">
                    </div>
                    <div>
                        <label class="block text-xs font-semibold mb-1">Confirm Password</label>
                        <input type="password" id="signup-confirm" required class="w-full px-4 py-2.5 rounded-xl bg-zinc-800/40 border border-zinc-700/40 text-sm focus:outline-none focus:border-purple-500">
                    </div>
                    <button type="submit" class="w-full py-3 rounded-xl bg-purple-600 text-white font-bold text-sm hover:bg-purple-700 transition">Create Account</button>
                </form>
                <p class="text-xs text-center text-zinc-400">Already registered? <a href="#login" onclick="navigateTo('login')" class="text-purple-400 font-bold hover:underline">Log In</a></p>
            </div>
        </section>

        <!-- VIEW: FORGOT PASSWORD -->
        <section id="view-forgot-password" class="view-section hidden max-w-md mx-auto">
            <div class="glass-card p-8 rounded-2xl space-y-6">
                <div class="text-center space-y-1">
                    <h2 class="text-2xl font-bold">Reset Password</h2>
                    <p class="text-xs text-zinc-400">Enter your email address to receive password reset link</p>
                </div>
                <form onsubmit="handleForgotPassword(event)" class="space-y-4">
                    <div>
                        <label class="block text-xs font-semibold mb-1">Email Address</label>
                        <input type="email" id="forgot-email" required class="w-full px-4 py-2.5 rounded-xl bg-zinc-800/40 border border-zinc-700/40 text-sm focus:outline-none focus:border-purple-500">
                    </div>
                    <button type="submit" class="w-full py-3 rounded-xl bg-purple-600 text-white font-bold text-sm hover:bg-purple-700 transition">Send Reset Request</button>
                </form>
                <p class="text-xs text-center"><a href="#login" onclick="navigateTo('login')" class="text-purple-400 font-bold hover:underline">&larr; Back to Login</a></p>
            </div>
        </section>

        <!-- VIEW: USER PROFILE -->
        <section id="view-profile" class="view-section hidden max-w-2xl mx-auto space-y-8">
            <div class="glass-card p-8 rounded-2xl space-y-6">
                <h2 class="text-2xl font-bold border-b border-zinc-700/40 pb-4">Account Settings</h2>
                <form onsubmit="handleProfileUpdate(event)" class="space-y-4">
                    <div>
                        <label class="block text-xs font-semibold mb-1">Full Name</label>
                        <input type="text" id="profile-name" required class="w-full px-4 py-2.5 rounded-xl bg-zinc-800/40 border border-zinc-700/40 text-sm focus:outline-none focus:border-purple-500">
                    </div>
                    <div>
                        <label class="block text-xs font-semibold mb-1">Email</label>
                        <input type="email" id="profile-email" readonly class="w-full px-4 py-2.5 rounded-xl bg-zinc-800/20 border border-zinc-700/20 text-sm opacity-60 cursor-not-allowed">
                    </div>
                    <div>
                        <label class="block text-xs font-semibold mb-1">New Password (leave blank to keep current)</label>
                        <input type="password" id="profile-new-password" class="w-full px-4 py-2.5 rounded-xl bg-zinc-800/40 border border-zinc-700/40 text-sm focus:outline-none focus:border-purple-500">
                    </div>
                    <button type="submit" class="px-6 py-2.5 rounded-xl bg-purple-600 text-white font-bold text-sm hover:bg-purple-700 transition">Save Changes</button>
                </form>
            </div>
        </section>

        <!-- VIEW: ADMIN PANEL (Protected) -->
        <section id="view-admin" class="view-section hidden space-y-8">
            <div class="flex flex-col sm:flex-row justify-between items-start sm:items-center gap-4 pb-4 border-b border-zinc-700/40">
                <div>
                    <h2 class="text-3xl font-extrabold text-gradient">Admin Panel</h2>
                    <p class="text-xs text-zinc-400">Website Management & Content Administration</p>
                </div>
                <div class="flex flex-wrap gap-2 text-xs font-semibold">
                    <button onclick="switchAdminTab('dashboard')" class="admin-tab-btn px-4 py-2 rounded-xl glass-card bg-purple-600 text-white" data-tab="dashboard">Dashboard</button>
                    <button onclick="switchAdminTab('photos')" class="admin-tab-btn px-4 py-2 rounded-xl glass-card" data-tab="photos">Photos</button>
                    <button onclick="switchAdminTab('videos')" class="admin-tab-btn px-4 py-2 rounded-xl glass-card" data-tab="videos">Videos</button>
                    <button onclick="switchAdminTab('albums')" class="admin-tab-btn px-4 py-2 rounded-xl glass-card" data-tab="albums">Albums</button>
                    <button onclick="switchAdminTab('messages')" class="admin-tab-btn px-4 py-2 rounded-xl glass-card" data-tab="messages">Messages</button>
                    <button onclick="switchAdminTab('users')" class="admin-tab-btn px-4 py-2 rounded-xl glass-card" data-tab="users">Users</button>
                    <button onclick="switchAdminTab('settings')" class="admin-tab-btn px-4 py-2 rounded-xl glass-card" data-tab="settings">Site Settings</button>
                </div>
            </div>

            <!-- ADMIN TAB: DASHBOARD -->
            <div id="admin-tab-dashboard" class="admin-content space-y-8">
                <div class="grid grid-cols-2 lg:grid-cols-5 gap-4">
                    <div class="glass-card p-5 rounded-2xl border border-white/10 text-center">
                        <p class="text-xs font-bold text-zinc-400">Total Photos</p>
                        <p id="stat-photos" class="text-3xl font-black text-purple-400 mt-2">0</p>
                    </div>
                    <div class="glass-card p-5 rounded-2xl border border-white/10 text-center">
                        <p class="text-xs font-bold text-zinc-400">Total Videos</p>
                        <p id="stat-videos" class="text-3xl font-black text-pink-400 mt-2">0</p>
                    </div>
                    <div class="glass-card p-5 rounded-2xl border border-white/10 text-center">
                        <p class="text-xs font-bold text-zinc-400">Total Albums</p>
                        <p id="stat-albums" class="text-3xl font-black text-blue-400 mt-2">0</p>
                    </div>
                    <div class="glass-card p-5 rounded-2xl border border-white/10 text-center">
                        <p class="text-xs font-bold text-zinc-400">Total Users</p>
                        <p id="stat-users" class="text-3xl font-black text-green-400 mt-2">0</p>
                    </div>
                    <div class="glass-card p-5 rounded-2xl border border-white/10 text-center col-span-2 lg:col-span-1">
                        <p class="text-xs font-bold text-zinc-400">Messages</p>
                        <p id="stat-messages" class="text-3xl font-black text-amber-400 mt-2">0</p>
                    </div>
                </div>

                <div class="grid lg:grid-cols-2 gap-8">
                    <div class="glass-card p-6 rounded-2xl space-y-4">
                        <h3 class="text-lg font-bold">Recent Uploads</h3>
                        <div id="admin-recent-uploads" class="space-y-3"></div>
                    </div>
                    <div class="glass-card p-6 rounded-2xl space-y-4">
                        <h3 class="text-lg font-bold">Recent Registrations</h3>
                        <div id="admin-recent-users" class="space-y-3"></div>
                    </div>
                </div>
            </div>

            <!-- ADMIN TAB: PHOTOS -->
            <div id="admin-tab-photos" class="admin-content hidden space-y-6">
                <div class="glass-card p-6 rounded-2xl space-y-4">
                    <h3 class="text-lg font-bold">Add / Upload Photo</h3>
                    <form onsubmit="handleAdminPhotoUpload(event)" class="grid sm:grid-cols-2 gap-4">
                        <div>
                            <label class="block text-xs font-semibold mb-1">Photo Title</label>
                            <input type="text" id="admin-photo-title" required class="w-full px-4 py-2 rounded-xl bg-zinc-800/40 border border-zinc-700/40 text-sm">
                        </div>
                        <div>
                            <label class="block text-xs font-semibold mb-1">Category</label>
                            <input type="text" id="admin-photo-category" placeholder="e.g. Portrait, Travel, Nature" required class="w-full px-4 py-2 rounded-xl bg-zinc-800/40 border border-zinc-700/40 text-sm">
                        </div>
                        <div>
                            <label class="block text-xs font-semibold mb-1">Image URL or Local Upload</label>
                            <input type="text" id="admin-photo-url" placeholder="https://..." class="w-full px-4 py-2 rounded-xl bg-zinc-800/40 border border-zinc-700/40 text-sm mb-2">
                            <input type="file" id="admin-photo-file" accept="image/*" class="text-xs text-zinc-400">
                        </div>
                        <div>
                            <label class="block text-xs font-semibold mb-1">Assign to Album (Optional)</label>
                            <select id="admin-photo-album" class="w-full px-4 py-2 rounded-xl bg-zinc-800/40 border border-zinc-700/40 text-sm">
                                <option value="">None</option>
                            </select>
                        </div>
                        <div class="sm:col-span-2">
                            <label class="block text-xs font-semibold mb-1">Description</label>
                            <textarea id="admin-photo-desc" rows="2" class="w-full px-4 py-2 rounded-xl bg-zinc-800/40 border border-zinc-700/40 text-sm"></textarea>
                        </div>
                        <div class="sm:col-span-2">
                            <button type="submit" class="px-6 py-2.5 rounded-xl bg-purple-600 text-white font-bold text-sm">Save Photo</button>
                        </div>
                    </form>
                </div>

                <div class="glass-card p-6 rounded-2xl overflow-x-auto">
                    <h3 class="text-lg font-bold mb-4">Manage Photos</h3>
                    <table class="w-full text-left text-sm">
                        <thead class="border-b border-zinc-700/40 text-xs text-zinc-400 uppercase">
                            <tr>
                                <th class="p-3">Preview</th>
                                <th class="p-3">Title</th>
                                <th class="p-3">Category</th>
                                <th class="p-3">Actions</th>
                            </tr>
                        </thead>
                        <tbody id="admin-photos-table"></tbody>
                    </table>
                </div>
            </div>

            <!-- ADMIN TAB: VIDEOS -->
            <div id="admin-tab-videos" class="admin-content hidden space-y-6">
                <div class="glass-card p-6 rounded-2xl space-y-4">
                    <h3 class="text-lg font-bold">Add / Upload Video</h3>
                    <form onsubmit="handleAdminVideoUpload(event)" class="grid sm:grid-cols-2 gap-4">
                        <div>
                            <label class="block text-xs font-semibold mb-1">Video Title</label>
                            <input type="text" id="admin-video-title" required class="w-full px-4 py-2 rounded-xl bg-zinc-800/40 border border-zinc-700/40 text-sm">
                        </div>
                        <div>
                            <label class="block text-xs font-semibold mb-1">Cover Thumbnail URL</label>
                            <input type="text" id="admin-video-thumb" placeholder="https://..." required class="w-full px-4 py-2 rounded-xl bg-zinc-800/40 border border-zinc-700/40 text-sm">
                        </div>
                        <div class="sm:col-span-2">
                            <label class="block text-xs font-semibold mb-1">Video URL (MP4, YouTube Embed, etc.)</label>
                            <input type="text" id="admin-video-url" placeholder="https://..." class="w-full px-4 py-2 rounded-xl bg-zinc-800/40 border border-zinc-700/40 text-sm mb-2">
                            <input type="file" id="admin-video-file" accept="video/*" class="text-xs text-zinc-400">
                        </div>
                        <div class="sm:col-span-2">
                            <label class="block text-xs font-semibold mb-1">Description</label>
                            <textarea id="admin-video-desc" rows="2" class="w-full px-4 py-2 rounded-xl bg-zinc-800/40 border border-zinc-700/40 text-sm"></textarea>
                        </div>
                        <div class="sm:col-span-2">
                            <button type="submit" class="px-6 py-2.5 rounded-xl bg-purple-600 text-white font-bold text-sm">Save Video</button>
                        </div>
                    </form>
                </div>

                <div class="glass-card p-6 rounded-2xl overflow-x-auto">
                    <h3 class="text-lg font-bold mb-4">Manage Videos</h3>
                    <table class="w-full text-left text-sm">
                        <thead class="border-b border-zinc-700/40 text-xs text-zinc-400 uppercase">
                            <tr>
                                <th class="p-3">Thumbnail</th>
                                <th class="p-3">Title</th>
                                <th class="p-3">Actions</th>
                            </tr>
                        </thead>
                        <tbody id="admin-videos-table"></tbody>
                    </table>
                </div>
            </div>

            <!-- ADMIN TAB: ALBUMS -->
            <div id="admin-tab-albums" class="admin-content hidden space-y-6">
                <div class="glass-card p-6 rounded-2xl space-y-4">
                    <h3 class="text-lg font-bold">Create New Album</h3>
                    <form onsubmit="handleAdminCreateAlbum(event)" class="grid sm:grid-cols-2 gap-4">
                        <div>
                            <label class="block text-xs font-semibold mb-1">Album Title</label>
                            <input type="text" id="admin-album-title" required class="w-full px-4 py-2 rounded-xl bg-zinc-800/40 border border-zinc-700/40 text-sm">
                        </div>
                        <div>
                            <label class="block text-xs font-semibold mb-1">Cover Image URL</label>
                            <input type="text" id="admin-album-cover" placeholder="https://..." required class="w-full px-4 py-2 rounded-xl bg-zinc-800/40 border border-zinc-700/40 text-sm">
                        </div>
                        <div class="sm:col-span-2">
                            <label class="block text-xs font-semibold mb-1">Description</label>
                            <textarea id="admin-album-desc" rows="2" class="w-full px-4 py-2 rounded-xl bg-zinc-800/40 border border-zinc-700/40 text-sm"></textarea>
                        </div>
                        <div class="sm:col-span-2">
                            <button type="submit" class="px-6 py-2.5 rounded-xl bg-purple-600 text-white font-bold text-sm">Create Album</button>
                        </div>
                    </form>
                </div>

                <div class="glass-card p-6 rounded-2xl overflow-x-auto">
                    <h3 class="text-lg font-bold mb-4">Manage Albums</h3>
                    <table class="w-full text-left text-sm">
                        <thead class="border-b border-zinc-700/40 text-xs text-zinc-400 uppercase">
                            <tr>
                                <th class="p-3">Cover</th>
                                <th class="p-3">Title</th>
                                <th class="p-3">Actions</th>
                            </tr>
                        </thead>
                        <tbody id="admin-albums-table"></tbody>
                    </table>
                </div>
            </div>

            <!-- ADMIN TAB: MESSAGES -->
            <div id="admin-tab-messages" class="admin-content hidden space-y-6">
                <div class="glass-card p-6 rounded-2xl overflow-x-auto">
                    <h3 class="text-lg font-bold mb-4">Contact Messages</h3>
                    <div id="admin-messages-list" class="space-y-4"></div>
                </div>
            </div>

            <!-- ADMIN TAB: USERS -->
            <div id="admin-tab-users" class="admin-content hidden space-y-6">
                <div class="glass-card p-6 rounded-2xl overflow-x-auto">
                    <h3 class="text-lg font-bold mb-4">Registered Users</h3>
                    <table class="w-full text-left text-sm">
                        <thead class="border-b border-zinc-700/40 text-xs text-zinc-400 uppercase">
                            <tr>
                                <th class="p-3">Name</th>
                                <th class="p-3">Email</th>
                                <th class="p-3">Role</th>
                                <th class="p-3">Status</th>
                                <th class="p-3">Actions</th>
                            </tr>
                        </thead>
                        <tbody id="admin-users-table"></tbody>
                    </table>
                </div>
            </div>

            <!-- ADMIN TAB: SETTINGS -->
            <div id="admin-tab-settings" class="admin-content hidden space-y-6">
                <div class="glass-card p-6 rounded-2xl space-y-4">
                    <h3 class="text-lg font-bold">Site Content & Branding Settings</h3>
                    <form onsubmit="handleAdminSettingsUpdate(event)" class="space-y-4">
                        <div class="grid sm:grid-cols-2 gap-4">
                            <div>
                                <label class="block text-xs font-semibold mb-1">Hero / Profile Photo URL</label>
                                <input type="text" id="setting-hero-img" class="w-full px-4 py-2 rounded-xl bg-zinc-800/40 border border-zinc-700/40 text-sm">
                            </div>
                            <div>
                                <label class="block text-xs font-semibold mb-1">About Image URL</label>
                                <input type="text" id="setting-about-img" class="w-full px-4 py-2 rounded-xl bg-zinc-800/40 border border-zinc-700/40 text-sm">
                            </div>
                        </div>
                        <div>
                            <label class="block text-xs font-semibold mb-1">Hero Tagline</label>
                            <input type="text" id="setting-hero-tagline" class="w-full px-4 py-2 rounded-xl bg-zinc-800/40 border border-zinc-700/40 text-sm">
                        </div>
                        <div>
                            <label class="block text-xs font-semibold mb-1">About Bio Text</label>
                            <textarea id="setting-about-text" rows="3" class="w-full px-4 py-2 rounded-xl bg-zinc-800/40 border border-zinc-700/40 text-sm"></textarea>
                        </div>
                        <button type="submit" class="px-6 py-2.5 rounded-xl bg-purple-600 text-white font-bold text-sm">Save Site Settings</button>
                    </form>
                </div>
            </div>
        </section>

    </main>

    <!-- MEDIA LIGHTBOX MODAL -->
    <div id="lightbox-modal" class="fixed inset-0 z-50 hidden bg-black/90 backdrop-blur-md p-4 sm:p-8 flex flex-col justify-between">
        <div class="flex justify-between items-center text-white">
            <div>
                <h3 id="lightbox-title" class="font-bold text-lg"></h3>
                <p id="lightbox-desc" class="text-xs text-zinc-400"></p>
            </div>
            <div class="flex items-center gap-4">
                <a id="lightbox-download" href="#" download class="px-4 py-2 rounded-xl bg-zinc-800 hover:bg-zinc-700 text-xs font-bold text-white transition"><i class="fa-solid fa-download mr-1"></i> Download</a>
                <button onclick="closeLightbox()" class="text-2xl hover:text-purple-400"><i class="fa-solid fa-xmark"></i></button>
            </div>
        </div>
        <div class="flex-grow flex items-center justify-center my-4 overflow-hidden">
            <div id="lightbox-content" class="max-h-[80vh] max-w-full flex justify-center items-center"></div>
        </div>
        <div id="lightbox-footer" class="text-center text-xs text-zinc-500">Vikram R Portfolio Showcase</div>
    </div>

    <!-- FOOTER -->
    <footer class="glass-nav border-t border-zinc-700/30 py-8 px-4 text-center text-xs text-zinc-400 space-y-2">
        <div class="flex justify-center gap-6 text-lg text-zinc-300 mb-2">
            <a href="https://instagram.com" target="_blank" class="hover:text-purple-400 transition"><i class="fa-brands fa-instagram"></i></a>
            <a href="https://youtube.com" target="_blank" class="hover:text-purple-400 transition"><i class="fa-brands fa-youtube"></i></a>
            <a href="https://twitter.com" target="_blank" class="hover:text-purple-400 transition"><i class="fa-brands fa-x-twitter"></i></a>
        </div>
        <p>&copy; 2026 Vikram R. All Rights Reserved.</p>
        <p class="opacity-70">Designed for High Performance & Premium Aesthetics</p>
    </footer>

    <!-- CLIENT-SIDE APPLICATION LOGIC & STORAGE -->
    <script>
        // INITIAL DATABASE SETUP
        const DEFAULT_DATA = {
            settings: {
                heroImg: "https://images.unsplash.com/photo-1534528741775-53994a69daeb?auto=format&fit=crop&w=800&q=80",
                aboutImg: "https://images.unsplash.com/photo-1507003211169-0a1dd7228f2d?auto=format&fit=crop&w=800&q=80",
                heroTagline: "Capturing timeless photography, cinematic video stories, and high-impact digital experiences across the globe.",
                aboutText: "I am a professional photographer, cinematographer, and visual content creator passionate about capturing raw human emotions, architecture, and breathtaking natural landscapes."
            },
            users: [
                { id: "u1", name: "Admin Vikram", email: "admin@vikramr.com", password: "admin", role: "admin", status: "active" },
                { id: "u2", name: "John Doe", email: "user@example.com", password: "user123", role: "user", status: "active" }
            ],
            photos: [
                { id: "p1", title: "Alpine Glow", category: "Nature", url: "https://images.unsplash.com/photo-1464822759023-fed622ff2c3b?auto=format&fit=crop&w=800&q=80", desc: "Sunrise over the mountain range", albumId: "a1" },
                { id: "p2", title: "Urban Reflections", category: "Architecture", url: "https://images.unsplash.com/photo-1513694203232-719a280e022f?auto=format&fit=crop&w=800&q=80", desc: "Night lights in the metropolis", albumId: "a2" },
                { id: "p3", title: "Serene Portrait", category: "Portrait", url: "https://images.unsplash.com/photo-1534528741775-53994a69daeb?auto=format&fit=crop&w=800&q=80", desc: "Natural studio light portraiture", albumId: "" }
            ],
            videos: [
                { id: "v1", title: "Cinematic Travel Reel", url: "https://assets.mixkit.co/videos/preview/mixkit-set-of-plateaus-seen-from-the-sky-in-a-sunset-26070-large.mp4", thumb: "https://images.unsplash.com/photo-1507525428034-b723cf961d3e?auto=format&fit=crop&w=800&q=80", desc: "Aerial views across mountain passes." },
                { id: "v2", title: "Urban Lights Motion", url: "https://assets.mixkit.co/videos/preview/mixkit-a-girl-blowing-a-bubble-gum-39326-large.mp4", thumb: "https://images.unsplash.com/photo-1514565131-fce0801e5785?auto=format&fit=crop&w=800&q=80", desc: "Modern aesthetic creative video." }
            ],
            albums: [
                { id: "a1", title: "Nature & Wilderness", cover: "https://images.unsplash.com/photo-1464822759023-fed622ff2c3b?auto=format&fit=crop&w=800&q=80", desc: "Pure natural landscapes" },
                { id: "a2", title: "Urban Architecture", cover: "https://images.unsplash.com/photo-1513694203232-719a280e022f?auto=format&fit=crop&w=800&q=80", desc: "Modern cityscapes" }
            ],
            messages: [
                { id: "m1", name: "Sarah Smith", email: "sarah@example.com", subject: "Photo Shoot Inquiry", message: "Hi Vikram, I loved your portfolio. Are you available for a portrait shoot next month?", date: "2026-09-20" }
            ]
        };

        function getDB() {
            const data = localStorage.getItem("vikram_r_db");
            return data ? JSON.parse(data) : DEFAULT_DATA;
        }

        function saveDB(db) {
            localStorage.setItem("vikram_r_db", JSON.stringify(db));
        }

        // CURRENT SESSION MANAGEMENT
        let currentUser = JSON.parse(localStorage.getItem("vikram_r_session") || "null");

        // APP STATE
        let activeView = "home";

        // THEME TOGGLE
        function toggleTheme() {
            document.documentElement.classList.toggle('dark');
            const isDark = document.documentElement.classList.contains('dark');
            localStorage.setItem("vikram_r_theme", isDark ? "dark" : "light");
        }

        if (localStorage.getItem("vikram_r_theme") === "light") {
            document.documentElement.classList.remove('dark');
        }

        // NAVIGATION ROUTER
        function navigateTo(viewId, params = null) {
            activeView = viewId;
            document.querySelectorAll('.view-section').forEach(el => el.classList.add('hidden'));

            const targetView = document.getElementById(`view-${viewId}`);
            if (targetView) {
                targetView.classList.remove('hidden');
                window.scrollTo({ top: 0, behavior: 'smooth' });
            }

            if (viewId === 'home') renderHome();
            if (viewId === 'about') renderAbout();
            if (viewId === 'photos') renderPhotos();
            if (viewId === 'videos') renderVideos();
            if (viewId === 'albums') renderAlbums();
            if (viewId === 'album-detail' && params) renderAlbumDetail(params);
            if (viewId === 'profile') renderProfile();
            if (viewId === 'admin') renderAdmin();

            updateAuthUI();
        }

        function toggleMobileMenu() {
            document.getElementById('mobile-menu').classList.toggle('hidden');
        }

        // AUTHENTICATION UI & GUARDS
        function updateAuthUI() {
            const navAuth = document.getElementById('nav-auth-container');
            const mobileAuth = document.getElementById('mobile-auth-container');

            if (currentUser) {
                const isAdmin = currentUser.role === 'admin';
                navAuth.innerHTML = `
                    <button onclick="navigateTo('profile')" class="text-xs font-semibold hover:text-purple-400 flex items-center gap-2">
                        <i class="fa-solid fa-user-circle text-base"></i> ${currentUser.name}
                    </button>
                    ${isAdmin ? `<button onclick="navigateTo('admin')" class="px-3 py-1.5 rounded-lg bg-gradient-to-r from-purple-600 to-pink-600 text-white text-xs font-bold">Admin Panel</button>` : ''}
                    <button onclick="handleLogout()" class="text-xs text-red-400 font-bold hover:underline">Logout</button>
                `;
                mobileAuth.innerHTML = `
                    <div class="text-xs text-zinc-400">Logged in as ${currentUser.name}</div>
                    <button onclick="navigateTo('profile'); toggleMobileMenu()" class="text-left font-semibold">Profile Settings</button>
                    ${isAdmin ? `<button onclick="navigateTo('admin'); toggleMobileMenu()" class="text-left font-bold text-purple-400">Admin Panel</button>` : ''}
                    <button onclick="handleLogout(); toggleMobileMenu()" class="text-left font-bold text-red-400">Logout</button>
                `;
            } else {
                navAuth.innerHTML = `
                    <button onclick="navigateTo('login')" class="text-xs font-semibold hover:text-purple-400">Log In</button>
                    <button onclick="navigateTo('signup')" class="px-4 py-2 rounded-xl bg-purple-600 text-white text-xs font-bold hover:bg-purple-700 transition">Sign Up</button>
                `;
                mobileAuth.innerHTML = `
                    <button onclick="navigateTo('login'); toggleMobileMenu()" class="text-left font-semibold">Log In</button>
                    <button onclick="navigateTo('signup'); toggleMobileMenu()" class="text-left font-bold text-purple-400">Sign Up</button>
                `;
            }
        }

        // TOAST SYSTEM
        function showToast(msg, type = "info") {
            const container = document.getElementById('toast-container');
            const toast = document.createElement('div');
            const bgClass = type === 'success' ? 'bg-green-600' : type === 'error' ? 'bg-red-600' : 'bg-purple-600';
            toast.className = `${bgClass} text-white px-5 py-3 rounded-2xl text-xs font-bold shadow-xl flex items-center gap-3 transition-all pointer-events-auto`;
            toast.innerHTML = `<span>${msg}</span><button onclick="this.parentElement.remove()">&times;</button>`;
            container.appendChild(toast);
            setTimeout(() => toast.remove(), 4000);
        }

        // CONFIRM MODAL
        function showConfirm(title, msg, onOk) {
            const modal = document.getElementById('confirm-modal');
            document.getElementById('confirm-title').textContent = title;
            document.getElementById('confirm-msg').textContent = msg;
            modal.classList.remove('hidden');
            modal.classList.add('flex');

            const okBtn = document.getElementById('confirm-ok');
            const cancelBtn = document.getElementById('confirm-cancel');

            const cleanup = () => {
                modal.classList.add('hidden');
                modal.classList.remove('flex');
            };

            okBtn.onclick = () => { cleanup(); onOk(); };
            cancelBtn.onclick = cleanup;
        }

        // RENDER VIEWS
        function renderHome() {
            const db = getDB();
            document.getElementById('hero-profile-img').src = db.settings.heroImg;
            document.getElementById('hero-tagline').textContent = db.settings.heroTagline;

            const grid = document.getElementById('home-featured-grid');
            grid.innerHTML = db.photos.slice(0, 6).map(p => `
                <div onclick="openLightbox('image', '${p.url}', '${p.title}', '${p.desc}')" class="glass-card rounded-2xl overflow-hidden group cursor-pointer border border-white/10 hover:border-purple-500/50">
                    <div class="h-64 overflow-hidden relative">
                        <img src="${p.url}" alt="${p.title}" class="w-full h-full object-cover group-hover:scale-110 transition duration-500">
                        <div class="absolute inset-0 bg-black/40 opacity-0 group-hover:opacity-100 transition flex items-center justify-center text-white">
                            <i class="fa-solid fa-expand text-2xl"></i>
                        </div>
                    </div>
                    <div class="p-4">
                        <h4 class="font-bold text-sm">${p.title}</h4>
                        <p class="text-xs text-zinc-400">${p.category}</p>
                    </div>
                </div>
            `).join('');
        }

        function renderAbout() {
            const db = getDB();
            document.getElementById('about-img').src = db.settings.aboutImg;
            document.getElementById('about-text-bio').textContent = db.settings.aboutText;
            
            const skills = ["Photography", "Cinematography", "Lighting Design", "Drone Operator", "Color Grading", "Post Production"];
            document.getElementById('about-skills-list').innerHTML = skills.map(s => `
                <span class="px-3 py-1 rounded-full text-xs font-semibold glass-card border border-purple-500/30 text-purple-300">${s}</span>
            `).join('');

            document.getElementById('about-social-links').innerHTML = `
                <a href="#" class="hover:text-purple-400"><i class="fa-brands fa-instagram"></i></a>
                <a href="#" class="hover:text-purple-400"><i class="fa-brands fa-youtube"></i></a>
                <a href="#" class="hover:text-purple-400"><i class="fa-brands fa-x-twitter"></i></a>
            `;
        }

        function renderPhotos() {
            const db = getDB();
            const filterSelect = document.getElementById('photo-category-filter');
            const categories = Array.from(new Set(db.photos.map(p => p.category)));
            filterSelect.innerHTML = `<option value="ALL">All Categories</option>` + categories.map(c => `<option value="${c}">${c}</option>`).join('');
            filterPhotos();
        }

        function filterPhotos() {
            const db = getDB();
            const search = document.getElementById('photo-search').value.toLowerCase();
            const cat = document.getElementById('photo-category-filter').value;

            const filtered = db.photos.filter(p => {
                const matchesCat = cat === 'ALL' || p.category === cat;
                const matchesSearch = p.title.toLowerCase().includes(search) || p.desc.toLowerCase().includes(search);
                return matchesCat && matchesSearch;
            });

            const grid = document.getElementById('photo-grid');
            if(filtered.length === 0) {
                grid.innerHTML = `<div class="col-span-full text-center py-12 text-zinc-500 text-sm">No photos found.</div>`;
                return;
            }

            grid.innerHTML = filtered.map(p => `
                <div class="glass-card rounded-2xl overflow-hidden group border border-white/10 hover:border-purple-500/50 transition">
                    <div class="h-64 overflow-hidden relative cursor-pointer" onclick="openLightbox('image', '${p.url}', '${p.title}', '${p.desc}')">
                        <img src="${p.url}" alt="${p.title}" class="w-full h-full object-cover group-hover:scale-105 transition duration-500">
                    </div>
                    <div class="p-4 flex justify-between items-center">
                        <div>
                            <h4 class="font-bold text-sm">${p.title}</h4>
                            <p class="text-xs text-zinc-400">${p.category}</p>
                        </div>
                        <a href="${p.url}" download="${p.title}.jpg" target="_blank" class="p-2 text-zinc-400 hover:text-purple-400" title="Download">
                            <i class="fa-solid fa-download"></i>
                        </a>
                    </div>
                </div>
            `).join('');
        }

        function renderVideos() {
            const db = getDB();
            const grid = document.getElementById('video-grid');
            grid.innerHTML = db.videos.map(v => `
                <div class="glass-card rounded-2xl overflow-hidden group border border-white/10 hover:border-purple-500/50 transition">
                    <div class="h-52 overflow-hidden relative cursor-pointer" onclick="openLightbox('video', '${v.url}', '${v.title}', '${v.desc}')">
                        <img src="${v.thumb}" alt="${v.title}" class="w-full h-full object-cover group-hover:scale-105 transition duration-500">
                        <div class="absolute inset-0 bg-black/40 flex items-center justify-center">
                            <div class="w-12 h-12 rounded-full bg-purple-600 text-white flex items-center justify-center shadow-lg group-hover:scale-110 transition">
                                <i class="fa-solid fa-play text-lg ml-1"></i>
                            </div>
                        </div>
                    </div>
                    <div class="p-4">
                        <h4 class="font-bold text-sm">${v.title}</h4>
                        <p class="text-xs text-zinc-400 mt-1">${v.desc}</p>
                    </div>
                </div>
            `).join('');
        }

        function renderAlbums() {
            const db = getDB();
            const grid = document.getElementById('albums-grid');
            grid.innerHTML = db.albums.map(a => {
                const count = db.photos.filter(p => p.albumId === a.id).length;
                return `
                    <div onclick="navigateTo('album-detail', '${a.id}')" class="glass-card rounded-2xl overflow-hidden group cursor-pointer border border-white/10 hover:border-purple-500/50 transition">
                        <div class="h-56 overflow-hidden relative">
                            <img src="${a.cover}" alt="${a.title}" class="w-full h-full object-cover group-hover:scale-105 transition duration-500">
                            <div class="absolute top-3 right-3 px-3 py-1 rounded-full bg-black/60 text-xs font-bold text-white backdrop-blur-md">
                                ${count} Items
                            </div>
                        </div>
                        <div class="p-5">
                            <h4 class="font-bold text-base">${a.title}</h4>
                            <p class="text-xs text-zinc-400 mt-1">${a.desc}</p>
                        </div>
                    </div>
                `;
            }).join('');
        }

        function renderAlbumDetail(albumId) {
            const db = getDB();
            const album = db.albums.find(a => a.id === albumId);
            if (!album) return navigateTo('albums');

            document.getElementById('album-detail-header').innerHTML = `
                <h2 class="text-3xl font-extrabold">${album.title}</h2>
                <p class="text-sm text-zinc-400">${album.desc}</p>
            `;

            const albumPhotos = db.photos.filter(p => p.albumId === albumId);
            const grid = document.getElementById('album-media-grid');

            if (albumPhotos.length === 0) {
                grid.innerHTML = `<div class="col-span-full text-center py-12 text-zinc-500">No media uploaded in this album yet.</div>`;
                return;
            }

            grid.innerHTML = albumPhotos.map(p => `
                <div onclick="openLightbox('image', '${p.url}', '${p.title}', '${p.desc}')" class="glass-card rounded-2xl overflow-hidden cursor-pointer group border border-white/10">
                    <img src="${p.url}" alt="${p.title}" class="w-full h-56 object-cover group-hover:scale-105 transition duration-500">
                    <div class="p-3 text-xs font-bold">${p.title}</div>
                </div>
            `).join('');
        }

        // LIGHTBOX SYSTEM
        function openLightbox(type, url, title, desc) {
            const modal = document.getElementById('lightbox-modal');
            const content = document.getElementById('lightbox-content');
            document.getElementById('lightbox-title').textContent = title;
            document.getElementById('lightbox-desc').textContent = desc;
            document.getElementById('lightbox-download').href = url;

            if (type === 'image') {
                content.innerHTML = `<img src="${url}" class="max-h-[75vh] max-w-full rounded-2xl object-contain">`;
            } else {
                content.innerHTML = `<video src="${url}" controls autoplay class="max-h-[75vh] max-w-full rounded-2xl"></video>`;
            }

            modal.classList.remove('hidden');
        }

        function closeLightbox() {
            document.getElementById('lightbox-modal').classList.add('hidden');
            document.getElementById('lightbox-content').innerHTML = '';
        }

        // HANDLERS: AUTHENTICATION & FORM SUBMISSIONS
        function handleSignup(e) {
            e.preventDefault();
            const name = document.getElementById('signup-name').value;
            const email = document.getElementById('signup-email').value;
            const password = document.getElementById('signup-password').value;
            const confirm = document.getElementById('signup-confirm').value;

            if (password !== confirm) {
                return showToast("Passwords do not match!", "error");
            }

            const db = getDB();
            if (db.users.find(u => u.email === email)) {
                return showToast("Email address already registered!", "error");
            }

            const newUser = { id: 'u_' + Date.now(), name, email, password, role: 'user', status: 'active' };
            db.users.push(newUser);
            saveDB(db);

            currentUser = newUser;
            localStorage.setItem("vikram_r_session", JSON.stringify(currentUser));
            showToast("Account created successfully!", "success");
            navigateTo('home');
        }

        function handleLogin(e) {
            e.preventDefault();
            const email = document.getElementById('login-email').value;
            const password = document.getElementById('login-password').value;

            const db = getDB();
            const user = db.users.find(u => u.email === email && u.password === password);

            if (!user) {
                return showToast("Invalid email or password", "error");
            }

            if (user.status !== 'active') {
                return showToast("Account deactivated. Contact Admin.", "error");
            }

            currentUser = user;
            localStorage.setItem("vikram_r_session", JSON.stringify(currentUser));
            showToast(`Welcome back, ${user.name}!`, "success");
            
            if (user.role === 'admin') navigateTo('admin');
            else navigateTo('home');
        }

        function handleLogout() {
            currentUser = null;
            localStorage.removeItem("vikram_r_session");
            showToast("Logged out successfully", "info");
            navigateTo('home');
        }

        function handleForgotPassword(e) {
            e.preventDefault();
            showToast("Password reset link sent to your email!", "success");
            navigateTo('login');
        }

        function renderProfile() {
            if (!currentUser) return navigateTo('login');
            document.getElementById('profile-name').value = currentUser.name;
            document.getElementById('profile-email').value = currentUser.email;
        }

        function handleProfileUpdate(e) {
            e.preventDefault();
            const newName = document.getElementById('profile-name').value;
            const newPass = document.getElementById('profile-new-password').value;

            const db = getDB();
            const user = db.users.find(u => u.id === currentUser.id);
            if (user) {
                user.name = newName;
                if (newPass.trim()) user.password = newPass;
                saveDB(db);
                currentUser = user;
                localStorage.setItem("vikram_r_session", JSON.stringify(currentUser));
                showToast("Profile updated successfully", "success");
            }
        }

        function handleContactSubmit(e) {
            e.preventDefault();
            const db = getDB();
            db.messages.push({
                id: 'm_' + Date.now(),
                name: document.getElementById('contact-name').value,
                email: document.getElementById('contact-email').value,
                subject: document.getElementById('contact-subject').value,
                message: document.getElementById('contact-message').value,
                date: new Date().toISOString().split('T')[0]
            });
            saveDB(db);
            showToast("Message sent to Admin panel!", "success");
            e.target.reset();
        }

        // ADMIN PANEL FUNCTIONS
        function renderAdmin() {
            if (!currentUser || currentUser.role !== 'admin') {
                showToast("Unauthorized Admin Access!", "error");
                return navigateTo('login');
            }

            const db = getDB();
            // Update Stats
            document.getElementById('stat-photos').textContent = db.photos.length;
            document.getElementById('stat-videos').textContent = db.videos.length;
            document.getElementById('stat-albums').textContent = db.albums.length;
            document.getElementById('stat-users').textContent = db.users.length;
            document.getElementById('stat-messages').textContent = db.messages.length;

            // Render Recent
            document.getElementById('admin-recent-uploads').innerHTML = db.photos.slice(0, 3).map(p => `
                <div class="flex items-center gap-3 text-xs">
                    <img src="${p.url}" class="w-10 h-10 rounded-lg object-cover">
                    <div><p class="font-bold">${p.title}</p><p class="text-zinc-400">${p.category}</p></div>
                </div>
            `).join('');

            document.getElementById('admin-recent-users').innerHTML = db.users.slice(0, 3).map(u => `
                <div class="flex items-center justify-between text-xs">
                    <div><p class="font-bold">${u.name}</p><p class="text-zinc-400">${u.email}</p></div>
                    <span class="px-2 py-0.5 rounded bg-purple-500/20 text-purple-300 font-bold">${u.role}</span>
                </div>
            `).join('');

            // Populate Album Select Dropdown
            document.getElementById('admin-photo-album').innerHTML = `<option value="">None</option>` + db.albums.map(a => `<option value="${a.id}">${a.title}</option>`).join('');

            // Render Tables
            renderAdminTables();
        }

        function switchAdminTab(tab) {
            document.querySelectorAll('.admin-content').forEach(el => el.classList.add('hidden'));
            document.querySelectorAll('.admin-tab-btn').forEach(el => {
                el.classList.remove('bg-purple-600', 'text-white');
            });

            document.getElementById(`admin-tab-${tab}`).classList.remove('hidden');
            const activeBtn = document.querySelector(`.admin-tab-btn[data-tab="${tab}"]`);
            if (activeBtn) activeBtn.classList.add('bg-purple-600', 'text-white');
        }

        function renderAdminTables() {
            const db = getDB();

            // Photos Table
            document.getElementById('admin-photos-table').innerHTML = db.photos.map(p => `
                <tr class="border-b border-zinc-700/30">
                    <td class="p-3"><img src="${p.url}" class="w-12 h-12 rounded-lg object-cover"></td>
                    <td class="p-3 font-bold">${p.title}</td>
                    <td class="p-3 text-zinc-400">${p.category}</td>
                    <td class="p-3">
                        <button onclick="deletePhoto('${p.id}')" class="text-red-400 hover:text-red-300"><i class="fa-solid fa-trash"></i></button>
                    </td>
                </tr>
            `).join('');

            // Videos Table
            document.getElementById('admin-videos-table').innerHTML = db.videos.map(v => `
                <tr class="border-b border-zinc-700/30">
                    <td class="p-3"><img src="${v.thumb}" class="w-12 h-12 rounded-lg object-cover"></td>
                    <td class="p-3 font-bold">${v.title}</td>
                    <td class="p-3">
                        <button onclick="deleteVideo('${v.id}')" class="text-red-400 hover:text-red-300"><i class="fa-solid fa-trash"></i></button>
                    </td>
                </tr>
            `).join('');

            // Albums Table
            document.getElementById('admin-albums-table').innerHTML = db.albums.map(a => `
                <tr class="border-b border-zinc-700/30">
                    <td class="p-3"><img src="${a.cover}" class="w-12 h-12 rounded-lg object-cover"></td>
                    <td class="p-3 font-bold">${a.title}</td>
                    <td class="p-3">
                        <button onclick="deleteAlbum('${a.id}')" class="text-red-400 hover:text-red-300"><i class="fa-solid fa-trash"></i></button>
                    </td>
                </tr>
            `).join('');

            // Messages Table
            document.getElementById('admin-messages-list').innerHTML = db.messages.map(m => `
                <div class="glass-card p-4 rounded-xl border border-white/10 space-y-2">
                    <div class="flex justify-between items-center text-xs">
                        <span class="font-bold text-purple-400">${m.name} (${m.email})</span>
                        <span class="text-zinc-500">${m.date}</span>
                    </div>
                    <p class="text-sm font-bold">${m.subject}</p>
                    <p class="text-xs text-zinc-300">${m.message}</p>
                    <button onclick="deleteMessage('${m.id}')" class="text-xs text-red-400 font-bold hover:underline pt-2">Delete Message</button>
                </div>
            `).join('');

            // Users Table
            document.getElementById('admin-users-table').innerHTML = db.users.map(u => `
                <tr class="border-b border-zinc-700/30">
                    <td class="p-3 font-bold">${u.name}</td>
                    <td class="p-3 text-zinc-400">${u.email}</td>
                    <td class="p-3"><span class="px-2 py-0.5 rounded text-xs ${u.role === 'admin' ? 'bg-purple-500/30 text-purple-300' : 'bg-zinc-700 text-zinc-300'} font-bold">${u.role}</span></td>
                    <td class="p-3"><span class="px-2 py-0.5 rounded text-xs ${u.status === 'active' ? 'bg-green-500/30 text-green-300' : 'bg-red-500/30 text-red-300'} font-bold">${u.status}</span></td>
                    <td class="p-3">
                        ${u.id !== currentUser.id ? `<button onclick="toggleUserStatus('${u.id}')" class="text-xs text-purple-400 hover:underline mr-3">Toggle Status</button>` : ''}
                    </td>
                </tr>
            `).join('');
        }

        // ADMIN MUTATIONS
        function handleAdminPhotoUpload(e) {
            e.preventDefault();
            const title = document.getElementById('admin-photo-title').value;
            const category = document.getElementById('admin-photo-category').value;
            const desc = document.getElementById('admin-photo-desc').value;
            const albumId = document.getElementById('admin-photo-album').value;
            const urlInput = document.getElementById('admin-photo-url').value;
            const fileInput = document.getElementById('admin-photo-file').files[0];

            const processPhoto = (url) => {
                const db = getDB();
                db.photos.unshift({ id: 'p_' + Date.now(), title, category, url, desc, albumId });
                saveDB(db);
                showToast("Photo saved successfully!", "success");
                e.target.reset();
                renderAdmin();
            };

            if (fileInput) {
                const reader = new FileReader();
                reader.onload = (evt) => processPhoto(evt.target.result);
                reader.readAsDataURL(fileInput);
            } else if (urlInput) {
                processPhoto(urlInput);
            } else {
                showToast("Please provide photo URL or file!", "error");
            }
        }

        function handleAdminVideoUpload(e) {
            e.preventDefault();
            const title = document.getElementById('admin-video-title').value;
            const thumb = document.getElementById('admin-video-thumb').value;
            const desc = document.getElementById('admin-video-desc').value;
            const urlInput = document.getElementById('admin-video-url').value;
            const fileInput = document.getElementById('admin-video-file').files[0];

            const processVideo = (url) => {
                const db = getDB();
                db.videos.unshift({ id: 'v_' + Date.now(), title, thumb, url, desc });
                saveDB(db);
                showToast("Video saved successfully!", "success");
                e.target.reset();
                renderAdmin();
            };

            if (fileInput) {
                const reader = new FileReader();
                reader.onload = (evt) => processVideo(evt.target.result);
                reader.readAsDataURL(fileInput);
            } else if (urlInput) {
                processVideo(urlInput);
            } else {
                showToast("Please provide video URL or file!", "error");
            }
        }

        function handleAdminCreateAlbum(e) {
            e.preventDefault();
            const db = getDB();
            db.albums.push({
                id: 'a_' + Date.now(),
                title: document.getElementById('admin-album-title').value,
                cover: document.getElementById('admin-album-cover').value,
                desc: document.getElementById('admin-album-desc').value
            });
            saveDB(db);
            showToast("Album created successfully!", "success");
            e.target.reset();
            renderAdmin();
        }

        function handleAdminSettingsUpdate(e) {
            e.preventDefault();
            const db = getDB();
            db.settings.heroImg = document.getElementById('setting-hero-img').value || db.settings.heroImg;
            db.settings.aboutImg = document.getElementById('setting-about-img').value || db.settings.aboutImg;
            db.settings.heroTagline = document.getElementById('setting-hero-tagline').value || db.settings.heroTagline;
            db.settings.aboutText = document.getElementById('setting-about-text').value || db.settings.aboutText;
            saveDB(db);
            showToast("Settings updated successfully!", "success");
        }

        function deletePhoto(id) {
            showConfirm("Delete Photo", "Are you sure you want to delete this photo?", () => {
                const db = getDB();
                db.photos = db.photos.filter(p => p.id !== id);
                saveDB(db);
                renderAdmin();
                showToast("Photo deleted", "info");
            });
        }

        function deleteVideo(id) {
            showConfirm("Delete Video", "Are you sure you want to delete this video?", () => {
                const db = getDB();
                db.videos = db.videos.filter(v => v.id !== id);
                saveDB(db);
                renderAdmin();
                showToast("Video deleted", "info");
            });
        }

        function deleteAlbum(id) {
            showConfirm("Delete Album", "Are you sure you want to delete this album?", () => {
                const db = getDB();
                db.albums = db.albums.filter(a => a.id !== id);
                saveDB(db);
                renderAdmin();
                showToast("Album deleted", "info");
            });
        }

        function deleteMessage(id) {
            showConfirm("Delete Message", "Delete message permanently?", () => {
                const db = getDB();
                db.messages = db.messages.filter(m => m.id !== id);
                saveDB(db);
                renderAdmin();
                showToast("Message deleted", "info");
            });
        }

        function toggleUserStatus(id) {
            const db = getDB();
            const user = db.users.find(u => u.id === id);
            if (user) {
                user.status = user.status === 'active' ? 'deactivated' : 'active';
                saveDB(db);
                renderAdmin();
                showToast(`User status updated to ${user.status}`, "info");
            }
        }

        // INITIALIZATION
        window.addEventListener('DOMContentLoaded', () => {
            if (!localStorage.getItem("vikram_r_db")) {
                saveDB(DEFAULT_DATA);
            }
            navigateTo('home');
        });
    </script>
</body>
</html>
