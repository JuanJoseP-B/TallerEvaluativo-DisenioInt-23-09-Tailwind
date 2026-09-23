<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Boardto Dashboard</title>
    
    <!-- Fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    
    <!-- Icons (FontAwesome) -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                    },
                    colors: {
                        background: '#E8F1F5',
                        primary: '#10B9B0',
                        sidebar: '#E8F1F5',
                        cardbg: '#F8FBFC',
                        textdark: '#1E293B',
                        textmuted: '#64748B',
                        iconpink: '#F43F5E',
                        icongreen: '#10B981',
                        iconblue: '#3B82F6',
                        iconorange: '#F59E0B',
                        iconpurple: '#8B5CF6'
                    },
                    boxShadow: {
                        'card': '0 10px 25px -5px rgba(0, 0, 0, 0.05), 0 8px 10px -6px rgba(0, 0, 0, 0.01)',
                        'floating': '0 20px 25px -5px rgba(0, 0, 0, 0.1), 0 10px 10px -5px rgba(0, 0, 0, 0.04)'
                    }
                }
            }
        }
    </script>
    <style>
        /* Custom scrollbar for a cleaner look */
        ::-webkit-scrollbar {
            width: 6px;
            height: 6px;
        }
        ::-webkit-scrollbar-track {
            background: transparent; 
        }
        ::-webkit-scrollbar-thumb {
            background: #cbd5e1; 
            border-radius: 10px;
        }
        ::-webkit-scrollbar-thumb:hover {
            background: #94a3b8; 
        }
    </style>
</head>
<body class="bg-background text-textdark font-sans antialiased h-screen overflow-hidden flex selection:bg-primary selection:text-white">

    <!-- Mobile overlay (hidden by default) -->
    <div id="mobile-overlay" class="fixed inset-0 bg-black/50 z-40 lg:hidden hidden" onclick="toggleSidebar()"></div>

    <!-- Sidebar -->
    <aside id="sidebar" class="bg-sidebar w-64 h-full flex flex-col py-6 px-4 fixed lg:relative z-50 transform -translate-x-full lg:translate-x-0 transition-transform duration-300 ease-in-out border-r border-slate-200/50">
        
        <!-- Logo -->
        <div class="flex items-center gap-3 px-4 mb-10">
            <div class="w-8 h-8 rounded-full bg-primary flex items-center justify-center shadow-lg shadow-primary/30 text-white font-bold text-sm ring-4 ring-white/50">
                <div class="w-3 h-3 bg-white rounded-full"></div>
            </div>
            <span class="text-xl font-bold tracking-tight text-textdark">Boardto</span>
        </div>

        <!-- Navigation Links -->
        <nav class="flex-1 space-y-2 overflow-y-auto pr-2">
            <a href="#" class="flex items-center gap-4 px-4 py-3 text-textmuted hover:text-textdark hover:bg-white/50 rounded-xl transition-all font-medium">
                <i class="fa-solid fa-border-all w-5 text-center text-lg"></i>
                <span>Boards</span>
            </a>
            
            <a href="#" class="flex items-center gap-4 px-4 py-3 text-textmuted hover:text-textdark hover:bg-white/50 rounded-xl transition-all font-medium">
                <i class="fa-regular fa-calendar-check w-5 text-center text-lg"></i>
                <span>Plan Schedule</span>
            </a>
            
            <a href="#" class="flex items-center gap-4 px-4 py-3 bg-primary text-white rounded-xl shadow-md shadow-primary/20 transition-all font-medium">
                <i class="fa-solid fa-file-invoice w-5 text-center text-lg"></i>
                <span>Reporting</span>
            </a>
            
            <a href="#" class="flex items-center gap-4 px-4 py-3 text-textmuted hover:text-textdark hover:bg-white/50 rounded-xl transition-all font-medium">
                <i class="fa-regular fa-message w-5 text-center text-lg"></i>
                <span>Messages</span>
            </a>
            
            <a href="#" class="flex items-center gap-4 px-4 py-3 text-textmuted hover:text-textdark hover:bg-white/50 rounded-xl transition-all font-medium">
                <i class="fa-solid fa-users-viewfinder w-5 text-center text-lg"></i>
                <span>Team Member</span>
            </a>
            
            <a href="#" class="flex items-center gap-4 px-4 py-3 text-textmuted hover:text-textdark hover:bg-white/50 rounded-xl transition-all font-medium">
                <i class="fa-solid fa-plug w-5 text-center text-lg"></i>
                <span>Tools Plugin</span>
            </a>
            
            <a href="#" class="flex items-center gap-4 px-4 py-3 text-textmuted hover:text-textdark hover:bg-white/50 rounded-xl transition-all font-medium">
                <i class="fa-solid fa-route w-5 text-center text-lg"></i>
                <span>Roadmap</span>
            </a>
            
            <a href="#" class="flex items-center gap-4 px-4 py-3 text-textmuted hover:text-textdark hover:bg-white/50 rounded-xl transition-all font-medium">
                <i class="fa-solid fa-sliders w-5 text-center text-lg"></i>
                <span>Setting</span>
            </a>
        </nav>

        <!-- Logout -->
        <div class="mt-auto pt-6 border-t border-slate-200/50">
            <a href="#" class="flex items-center gap-4 px-4 py-3 text-textmuted hover:text-red-500 hover:bg-white/50 rounded-xl transition-all font-medium">
                <i class="fa-solid fa-arrow-right-from-bracket w-5 text-center text-lg"></i>
                <span>Logout</span>
            </a>
        </div>
    </aside>

    <!-- Main Content -->
    <main class="flex-1 flex flex-col h-full overflow-hidden relative">
        
        <!-- Top Header -->
        <header class="flex items-center justify-between py-4 px-6 lg:px-10">
            <!-- Left: Mobile toggle & Search -->
            <div class="flex items-center gap-4 flex-1">
                <button onclick="toggleSidebar()" class="lg:hidden p-2 text-textmuted hover:bg-white/50 rounded-lg">
                    <i class="fa-solid fa-bars text-xl"></i>
                </button>
                
                <div class="relative max-w-md w-full hidden sm:block">
                    <i class="fa-solid fa-magnifying-glass absolute left-3 top-1/2 transform -translate-y-1/2 text-slate-400"></i>
                    <input type="text" placeholder="Search..." class="w-full bg-transparent border-none focus:ring-0 pl-10 py-2 text-sm text-textdark placeholder-slate-400 font-medium outline-none">
                </div>
            </div>

            <!-- Right: Notifications & Profile -->
            <div class="flex items-center gap-6">
                <!-- Notification Bell -->
                <button class="relative p-2 text-textmuted hover:text-textdark transition-colors">
                    <i class="fa-regular fa-bell text-xl"></i>
                    <span class="absolute top-1 right-2 w-2 h-2 bg-red-500 rounded-full border border-background"></span>
                </button>
                
                <!-- Profile -->
                <div class="flex items-center gap-3 cursor-pointer hover:bg-white/40 p-1.5 rounded-full pr-4 transition-colors">
                    <img src="https://randomuser.me/api/portraits/women/44.jpg" alt="Augusta Ryan" class="w-10 h-10 rounded-full object-cover shadow-sm">
                    <div class="hidden sm:block">
                        <p class="text-sm font-semibold text-textdark">Augusta Ryan</p>
                        <p class="text-xs text-textmuted">Director</p>
                    </div>
                    <i class="fa-solid fa-circle-dot text-[8px] text-slate-400 ml-2 hidden sm:block"></i>
                </div>
            </div>
        </header>

        <!-- Scrollable Area -->
        <div class="flex-1 overflow-y-auto px-6 pb-12 lg:px-10">
            
            <!-- Page Title Area -->
            <div class="bg-background/80 backdrop-blur-sm sticky top-0 z-10 pt-4 pb-4 flex flex-col sm:flex-row sm:items-center justify-between gap-4">
                <div>
                    <h1 class="text-3xl font-bold text-textdark mb-1">Reporting</h1>
                    <p class="text-sm text-textmuted font-medium">All project in current month</p>
                </div>
                
                <!-- Add Button -->
                <button class="w-10 h-10 bg-primary hover:bg-primary/90 text-white rounded-xl shadow-lg shadow-primary/30 flex items-center justify-center transition-transform hover:scale-105">
                    <i class="fa-solid fa-plus"></i>
                </button>
            </div>

            <!-- Filters Area -->
            <div class="flex flex-col xl:flex-row justify-between items-start xl:items-center mt-6 gap-4">
                <!-- Filter Pills -->
                <div class="flex flex-wrap items-center gap-2">
                    <button class="flex items-center gap-2 px-4 py-2 bg-background border border-primary/20 hover:bg-primary/5 rounded-full text-sm font-semibold text-textdark transition-colors">
                        All <span class="bg-primary/20 text-primary px-2 py-0.5 rounded text-xs">50</span>
                    </button>
                    <button class="flex items-center gap-2 px-4 py-2 hover:bg-white/60 rounded-full text-sm font-medium text-textmuted transition-colors">
                        Started <span class="bg-white px-2 py-0.5 rounded text-xs text-slate-500 shadow-sm">20</span>
                    </button>
                    <button class="flex items-center gap-2 px-4 py-2 hover:bg-white/60 rounded-full text-sm font-medium text-textmuted transition-colors">
                        Approval <span class="bg-white px-2 py-0.5 rounded text-xs text-slate-500 shadow-sm">15</span>
                    </button>
                    <button class="flex items-center gap-2 px-4 py-2 hover:bg-white/60 rounded-full text-sm font-medium text-textmuted transition-colors">
                        Completed <span class="bg-white px-2 py-0.5 rounded text-xs text-slate-500 shadow-sm">34</span>
                    </button>
                </div>
                
                <!-- View Toggles -->
                <div class="flex items-center gap-2 bg-background p-1 rounded-xl">
                    <button class="px-4 py-2 text-sm font-medium text-textdark bg-white rounded-lg shadow-sm flex items-center gap-2 hover:bg-slate-50">
                        <i class="fa-solid fa-sliders"></i> More
                    </button>
                    <button class="w-10 h-10 flex items-center justify-center text-textmuted hover:text-textdark hover:bg-white rounded-lg transition-colors">
                        <i class="fa-solid fa-list-ul"></i>
                    </button>
                    <button class="w-10 h-10 flex items-center justify-center text-primary bg-primary/10 rounded-lg transition-colors">
                        <i class="fa-solid fa-grip"></i>
                    </button>
                </div>
            </div>

            <!-- Cards Grid -->
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 xl:grid-cols-4 gap-x-6 gap-y-10 mt-12">
                
                <!-- Card 1: App Development -->
                <div class="bg-cardbg rounded-[1.5rem] p-6 pt-8 relative shadow-card hover:shadow-floating transition-shadow duration-300">
                    <!-- Overlapping Icon -->
                    <div class="absolute -top-5 left-6 w-12 h-12 rounded-full bg-iconpink shadow-lg shadow-iconpink/40 flex items-center justify-center text-white text-lg">
                        <i class="fa-solid fa-mobile-screen"></i>
                    </div>
                    
                    <h3 class="text-lg font-bold text-textdark mt-2 mb-3">App Development</h3>
                    
                    <div class="space-y-2.5 mb-6">
                        <div class="flex items-center gap-3 text-sm text-textmuted font-medium">
                            <i class="fa-solid fa-bezier-curve w-4 text-center"></i> Marketing Team
                        </div>
                        <div class="flex items-center gap-3 text-sm text-textdark font-semibold">
                            <i class="fa-regular fa-square-check w-4 text-center text-textmuted"></i> 1 Weeks Left
                        </div>
                    </div>
                    
                    <div class="border-t border-slate-200/60 my-4"></div>
                    
                    <div class="flex justify-between items-end mt-4">
                        <div>
                            <p class="text-xs text-textmuted font-medium mb-2">Team Member</p>
                            <div class="flex -space-x-2">
                                <img src="https://randomuser.me/api/portraits/women/68.jpg" class="w-7 h-7 rounded-full border-2 border-cardbg shadow-sm">
                                <img src="https://randomuser.me/api/portraits/women/12.jpg" class="w-7 h-7 rounded-full border-2 border-cardbg shadow-sm">
                                <img src="https://randomuser.me/api/portraits/men/32.jpg" class="w-7 h-7 rounded-full border-2 border-cardbg shadow-sm">
                                <div class="w-7 h-7 rounded-full bg-slate-200 border-2 border-cardbg flex items-center justify-center text-[10px] font-bold text-textdark shadow-sm">
                                    <i class="fa-solid fa-circle text-[4px] text-textmuted"></i>
                                </div>
                            </div>
                        </div>
                        <div class="text-right">
                            <p class="text-xs text-textmuted font-medium mb-1">Progress</p>
                            <p class="text-lg font-bold text-textdark">34%</p>
                        </div>
                    </div>
                </div>

                <!-- Card 2: Web Design -->
                <div class="bg-cardbg rounded-[1.5rem] p-6 pt-8 relative shadow-card hover:shadow-floating transition-shadow duration-300">
                    <div class="absolute -top-5 left-6 w-12 h-12 rounded-full bg-icongreen shadow-lg shadow-icongreen/40 flex items-center justify-center text-white text-lg">
                        <i class="fa-solid fa-layer-group"></i>
                    </div>
                    <h3 class="text-lg font-bold text-textdark mt-2 mb-3">Web Design</h3>
                    <div class="space-y-2.5 mb-6">
                        <div class="flex items-center gap-3 text-sm text-textmuted font-medium">
                            <i class="fa-solid fa-bezier-curve w-4 text-center"></i> Core UI Team
                        </div>
                        <div class="flex items-center gap-3 text-sm text-textdark font-semibold">
                            <i class="fa-regular fa-square-check w-4 text-center text-textmuted"></i> 3 Weeks Left
                        </div>
                    </div>
                    <div class="border-t border-slate-200/60 my-4"></div>
                    <div class="flex justify-between items-end mt-4">
                        <div>
                            <p class="text-xs text-textmuted font-medium mb-2">Team Member</p>
                            <div class="flex -space-x-2">
                                <img src="https://randomuser.me/api/portraits/men/46.jpg" class="w-7 h-7 rounded-full border-2 border-cardbg shadow-sm">
                                <div class="w-7 h-7 rounded-full bg-slate-200 border-2 border-cardbg flex items-center justify-center text-[10px] font-bold text-textdark shadow-sm">
                                    <i class="fa-solid fa-circle text-[4px] text-textmuted"></i>
                                </div>
                            </div>
                        </div>
                        <div class="text-right">
                            <p class="text-xs text-textmuted font-medium mb-1">Progress</p>
                            <p class="text-lg font-bold text-textdark">76%</p>
                        </div>
                    </div>
                </div>

                <!-- Card 3: Landing Page -->
                <div class="bg-cardbg rounded-[1.5rem] p-6 pt-8 relative shadow-card hover:shadow-floating transition-shadow duration-300">
                    <div class="absolute -top-5 left-6 w-12 h-12 rounded-full bg-iconblue shadow-lg shadow-iconblue/40 flex items-center justify-center text-white text-lg">
                        <i class="fa-solid fa-window-maximize"></i>
                    </div>
                    <h3 class="text-lg font-bold text-textdark mt-2 mb-3">Landing Page</h3>
                    <div class="space-y-2.5 mb-6">
                        <div class="flex items-center gap-3 text-sm text-textmuted font-medium">
                            <i class="fa-solid fa-bezier-curve w-4 text-center"></i> Marketing Team
                        </div>
                        <div class="flex items-center gap-3 text-sm text-textdark font-semibold">
                            <i class="fa-regular fa-square-check w-4 text-center text-textmuted"></i> 2 Days Left
                        </div>
                    </div>
                    <div class="border-t border-slate-200/60 my-4"></div>
                    <div class="flex justify-between items-end mt-4">
                        <div>
                            <p class="text-xs text-textmuted font-medium mb-2">Team Member</p>
                            <div class="flex -space-x-2">
                                <img src="https://randomuser.me/api/portraits/women/24.jpg" class="w-7 h-7 rounded-full border-2 border-cardbg shadow-sm">
                                <img src="https://randomuser.me/api/portraits/men/22.jpg" class="w-7 h-7 rounded-full border-2 border-cardbg shadow-sm">
                                <img src="https://randomuser.me/api/portraits/men/11.jpg" class="w-7 h-7 rounded-full border-2 border-cardbg shadow-sm">
                                <div class="w-7 h-7 rounded-full bg-slate-200 border-2 border-cardbg flex items-center justify-center text-[10px] font-bold text-textdark shadow-sm">
                                    <i class="fa-solid fa-circle text-[4px] text-textmuted"></i>
                                </div>
                            </div>
                        </div>
                        <div class="text-right">
                            <p class="text-xs text-textmuted font-medium mb-1">Progress</p>
                            <p class="text-lg font-bold text-textdark">4%</p>
                        </div>
                    </div>
                </div>

                <!-- Card 4: Business Compare -->
                <div class="bg-cardbg rounded-[1.5rem] p-6 pt-8 relative shadow-card hover:shadow-floating transition-shadow duration-300">
                    <div class="absolute -top-5 left-6 w-12 h-12 rounded-full bg-iconorange shadow-lg shadow-iconorange/40 flex items-center justify-center text-white text-lg">
                        <i class="fa-solid fa-chart-pie"></i>
                    </div>
                    <h3 class="text-lg font-bold text-textdark mt-2 mb-3">Business Compare</h3>
                    <div class="space-y-2.5 mb-6">
                        <div class="flex items-center gap-3 text-sm text-textmuted font-medium">
                            <i class="fa-solid fa-bezier-curve w-4 text-center"></i> Marketing Team
                        </div>
                        <div class="flex items-center gap-3 text-sm text-textdark font-semibold">
                            <i class="fa-regular fa-square-check w-4 text-center text-textmuted"></i> 1 Month Left
                        </div>
                    </div>
                    <div class="border-t border-slate-200/60 my-4"></div>
                    <div class="flex justify-between items-end mt-4">
                        <div>
                            <p class="text-xs text-textmuted font-medium mb-2">Team Member</p>
                            <div class="flex -space-x-2">
                                <img src="https://randomuser.me/api/portraits/women/90.jpg" class="w-7 h-7 rounded-full border-2 border-cardbg shadow-sm">
                                <img src="https://randomuser.me/api/portraits/men/84.jpg" class="w-7 h-7 rounded-full border-2 border-cardbg shadow-sm">
                                <div class="w-7 h-7 rounded-full bg-slate-200 border-2 border-cardbg flex items-center justify-center text-[10px] font-bold text-textdark shadow-sm">
                                    <i class="fa-solid fa-circle text-[4px] text-textmuted"></i>
                                </div>
                            </div>
                        </div>
                        <div class="text-right">
                            <p class="text-xs text-textmuted font-medium mb-1">Progress</p>
                            <p class="text-lg font-bold text-textdark">90%</p>
                        </div>
                    </div>
                </div>

                <!-- Card 5: Commerce Checkout -->
                <div class="bg-cardbg rounded-[1.5rem] p-6 pt-8 relative shadow-card hover:shadow-floating transition-shadow duration-300">
                    <div class="absolute -top-5 left-6 w-12 h-12 rounded-full bg-iconpurple shadow-lg shadow-iconpurple/40 flex items-center justify-center text-white text-lg">
                        <i class="fa-solid fa-credit-card"></i>
                    </div>
                    <h3 class="text-lg font-bold text-textdark mt-2 mb-3">Comerce Checkout</h3>
                    <div class="space-y-2.5 mb-6">
                        <div class="flex items-center gap-3 text-sm text-textmuted font-medium">
                            <i class="fa-solid fa-bezier-curve w-4 text-center"></i> Order Process Team
                        </div>
                        <div class="flex items-center gap-3 text-sm text-textdark font-semibold">
                            <i class="fa-regular fa-square-check w-4 text-center text-textmuted"></i> 3 Weeks Left
                        </div>
                    </div>
                    <div class="border-t border-slate-200/60 my-4"></div>
                    <div class="flex justify-between items-end mt-4">
                        <div>
                            <p class="text-xs text-textmuted font-medium mb-2">Team Member</p>
                            <div class="flex -space-x-2">
                                <img src="https://randomuser.me/api/portraits/women/51.jpg" class="w-7 h-7 rounded-full border-2 border-cardbg shadow-sm">
                                <div class="w-7 h-7 rounded-full bg-slate-200 border-2 border-cardbg flex items-center justify-center text-[10px] font-bold text-textdark shadow-sm">
                                    <i class="fa-solid fa-circle text-[4px] text-textmuted"></i>
                                </div>
                            </div>
                        </div>
                        <div class="text-right">
                            <p class="text-xs text-textmuted font-medium mb-1">Progress</p>
                            <p class="text-lg font-bold text-textdark">65%</p>
                        </div>
                    </div>
                </div>

                <!-- Card 6: Data Staging -->
                <div class="bg-cardbg rounded-[1.5rem] p-6 pt-8 relative shadow-card hover:shadow-floating transition-shadow duration-300">
                    <div class="absolute -top-5 left-6 w-12 h-12 rounded-full bg-iconorange shadow-lg shadow-iconorange/40 flex items-center justify-center text-white text-lg">
                        <i class="fa-solid fa-server"></i>
                    </div>
                    <h3 class="text-lg font-bold text-textdark mt-2 mb-3">Data Staging</h3>
                    <div class="space-y-2.5 mb-6">
                        <div class="flex items-center gap-3 text-sm text-textmuted font-medium">
                            <i class="fa-solid fa-bezier-curve w-4 text-center"></i> Core Data Team
                        </div>
                        <div class="flex items-center gap-3 text-sm text-textdark font-semibold">
                            <i class="fa-regular fa-clock w-4 text-center text-textmuted"></i> 2 Month Left
                        </div>
                    </div>
                    <div class="border-t border-slate-200/60 my-4"></div>
                    <div class="flex justify-between items-end mt-4">
                        <div>
                            <p class="text-xs text-textmuted font-medium mb-2">Team Member</p>
                            <div class="flex -space-x-2">
                                <img src="https://randomuser.me/api/portraits/women/33.jpg" class="w-7 h-7 rounded-full border-2 border-cardbg shadow-sm">
                                <img src="https://randomuser.me/api/portraits/men/33.jpg" class="w-7 h-7 rounded-full border-2 border-cardbg shadow-sm">
                                <div class="w-7 h-7 rounded-full bg-slate-200 border-2 border-cardbg flex items-center justify-center text-[10px] font-bold text-textdark shadow-sm">
                                    <i class="fa-solid fa-circle text-[4px] text-textmuted"></i>
                                </div>
                            </div>
                        </div>
                        <div class="text-right">
                            <p class="text-xs text-textmuted font-medium mb-1">Progress</p>
                            <p class="text-lg font-bold text-textdark">96%</p>
                        </div>
                    </div>
                </div>

                <!-- Card 7: Campaign Store -->
                <div class="bg-cardbg rounded-[1.5rem] p-6 pt-8 relative shadow-card hover:shadow-floating transition-shadow duration-300">
                    <div class="absolute -top-5 left-6 w-12 h-12 rounded-full bg-iconblue shadow-lg shadow-iconblue/40 flex items-center justify-center text-white text-lg">
                        <i class="fa-solid fa-video"></i>
                    </div>
                    <h3 class="text-lg font-bold text-textdark mt-2 mb-3">Campaign Store</h3>
                    <div class="space-y-2.5 mb-6">
                        <div class="flex items-center gap-3 text-sm text-textmuted font-medium">
                            <i class="fa-solid fa-bezier-curve w-4 text-center"></i> Internal Communication
                        </div>
                        <div class="flex items-center gap-3 text-sm text-textdark font-semibold">
                            <i class="fa-regular fa-square-check w-4 text-center text-textmuted"></i> 11 Days Left
                        </div>
                    </div>
                    <div class="border-t border-slate-200/60 my-4"></div>
                    <div class="flex justify-between items-end mt-4">
                        <div>
                            <p class="text-xs text-textmuted font-medium mb-2">Team Member</p>
                            <div class="flex -space-x-2">
                                <img src="https://randomuser.me/api/portraits/men/61.jpg" class="w-7 h-7 rounded-full border-2 border-cardbg shadow-sm">
                                <img src="https://randomuser.me/api/portraits/women/71.jpg" class="w-7 h-7 rounded-full border-2 border-cardbg shadow-sm">
                                <img src="https://randomuser.me/api/portraits/men/55.jpg" class="w-7 h-7 rounded-full border-2 border-cardbg shadow-sm">
                                <div class="w-7 h-7 rounded-full bg-slate-200 border-2 border-cardbg flex items-center justify-center text-[10px] font-bold text-textdark shadow-sm">
                                    <i class="fa-solid fa-circle text-[4px] text-textmuted"></i>
                                </div>
                            </div>
                        </div>
                        <div class="text-right">
                            <p class="text-xs text-textmuted font-medium mb-1">Progress</p>
                            <p class="text-lg font-bold text-textdark">24%</p>
                        </div>
                    </div>
                </div>

                <!-- Card 8: Acquisition Mitra -->
                <div class="bg-cardbg rounded-[1.5rem] p-6 pt-8 relative shadow-card hover:shadow-floating transition-shadow duration-300">
                    <div class="absolute -top-5 left-6 w-12 h-12 rounded-full bg-iconpink shadow-lg shadow-iconpink/40 flex items-center justify-center text-white text-lg">
                        <i class="fa-solid fa-user-astronaut"></i>
                    </div>
                    <h3 class="text-lg font-bold text-textdark mt-2 mb-3">Acquisition Mitra</h3>
                    <div class="space-y-2.5 mb-6">
                        <div class="flex items-center gap-3 text-sm text-textmuted font-medium">
                            <i class="fa-solid fa-bezier-curve w-4 text-center"></i> Merchant team
                        </div>
                        <div class="flex items-center gap-3 text-sm text-textdark font-semibold">
                            <i class="fa-regular fa-square-check w-4 text-center text-textmuted"></i> 1 Weeks Left
                        </div>
                    </div>
                    <div class="border-t border-slate-200/60 my-4"></div>
                    <div class="flex justify-between items-end mt-4">
                        <div>
                            <p class="text-xs text-textmuted font-medium mb-2">Team Member</p>
                            <div class="flex -space-x-2">
                                <img src="https://randomuser.me/api/portraits/women/89.jpg" class="w-7 h-7 rounded-full border-2 border-cardbg shadow-sm">
                                <div class="w-7 h-7 rounded-full bg-slate-200 border-2 border-cardbg flex items-center justify-center text-[10px] font-bold text-textdark shadow-sm">
                                    <i class="fa-solid fa-circle text-[4px] text-textmuted"></i>
                                </div>
                            </div>
                        </div>
                        <div class="text-right">
                            <p class="text-xs text-textmuted font-medium mb-1">Progress</p>
                            <p class="text-lg font-bold text-textdark">70%</p>
                        </div>
                    </div>
                </div>

            </div>
        </div>
    </main>

    <script>
        // Simple script to handle mobile sidebar toggle
        function toggleSidebar() {
            const sidebar = document.getElementById('sidebar');
            const overlay = document.getElementById('mobile-overlay');
            
            if (sidebar.classList.contains('-translate-x-full')) {
                // Open sidebar
                sidebar.classList.remove('-translate-x-full');
                overlay.classList.remove('hidden');
            } else {
                // Close sidebar
                sidebar.classList.add('-translate-x-full');
                overlay.classList.add('hidden');
            }
        }
    </script>
</body>
</html>
