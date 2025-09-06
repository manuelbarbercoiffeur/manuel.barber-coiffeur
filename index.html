# manuel.barber-coiffeur
<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BarberStyle - Termin buchen</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap');
        body { font-family: 'Inter', sans-serif; }
        
        .calendar-day {
            transition: all 0.2s ease;
        }
        
        .calendar-day:hover {
            transform: translateY(-2px);
            box-shadow: 0 4px 12px rgba(0,0,0,0.15);
        }
        
        .service-card {
            transition: all 0.3s ease;
        }
        
        .service-card:hover {
            transform: translateY(-4px);
            box-shadow: 0 8px 25px rgba(0,0,0,0.15);
        }
        
        .time-slot {
            transition: all 0.2s ease;
        }
        
        .time-slot:hover {
            transform: scale(1.05);
        }
        
        .fade-in {
            animation: fadeIn 0.5s ease-in;
        }
        
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }

        .notification-badge {
            animation: pulse 2s infinite;
        }

        @keyframes pulse {
            0%, 100% { transform: scale(1); }
            50% { transform: scale(1.1); }
        }

        .notification-popup {
            animation: slideIn 0.3s ease-out;
        }

        @keyframes slideIn {
            from { transform: translateX(100%); opacity: 0; }
            to { transform: translateX(0); opacity: 1; }
        }
    </style>
</head>
<body class="bg-gradient-to-br from-black via-gray-900 to-black min-h-screen">
    <!-- Header -->
    <header class="bg-black/20 backdrop-blur-lg border-b border-white/10">
        <div class="max-w-6xl mx-auto px-6 py-4">
            <div class="flex items-center justify-between">
                <div class="flex items-center space-x-3">
                    <div class="w-10 h-10 bg-gradient-to-r from-red-600 to-red-800 rounded-lg flex items-center justify-center">
                        <span class="text-white font-bold text-lg">✂️</span>
                    </div>
                    <h1 class="text-2xl font-bold text-white">BarberStyle</h1>
                </div>
                <div class="text-red-400 font-medium">Premium Barbershop</div>
            </div>
        </div>
    </header>

    <div class="max-w-6xl mx-auto px-6 py-8">
        <!-- Progress Steps -->
        <div class="mb-8">
            <div class="flex items-center justify-center space-x-4 mb-6">
                <div class="flex items-center">
                    <div id="step1-indicator" class="w-8 h-8 bg-red-600 text-white rounded-full flex items-center justify-center font-bold">1</div>
                    <span class="ml-2 text-white font-medium">Service wählen</span>
                </div>
                <div class="w-12 h-0.5 bg-gray-600"></div>
                <div class="flex items-center">
                    <div id="step2-indicator" class="w-8 h-8 bg-gray-600 text-gray-400 rounded-full flex items-center justify-center font-bold">2</div>
                    <span class="ml-2 text-gray-400 font-medium">Datum & Zeit</span>
                </div>
                <div class="w-12 h-0.5 bg-gray-600"></div>
                <div class="flex items-center">
                    <div id="step3-indicator" class="w-8 h-8 bg-gray-600 text-gray-400 rounded-full flex items-center justify-center font-bold">3</div>
                    <span class="ml-2 text-gray-400 font-medium">Bestätigung</span>
                </div>
            </div>
        </div>

        <!-- Step 1: Service Selection -->
        <div id="step1" class="fade-in">
            <h2 class="text-3xl font-bold text-white text-center mb-8">Wählen Sie Ihre Dienstleistung</h2>
            <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-6">
                <div class="service-card bg-white/10 backdrop-blur-lg rounded-xl p-6 border border-white/20 cursor-pointer" onclick="selectService('Herrenschnitt', 35, 45)">
                    <div class="text-4xl mb-4">💇‍♂️</div>
                    <h3 class="text-xl font-bold text-white mb-2">Herrenschnitt</h3>
                    <p class="text-gray-300 mb-4">Klassischer Herrenschnitt mit Styling</p>
                    <div class="flex justify-between items-center">
                        <span class="text-2xl font-bold text-red-400">35€</span>
                        <span class="text-gray-400">45 Min</span>
                    </div>
                </div>

                <div class="service-card bg-white/10 backdrop-blur-lg rounded-xl p-6 border border-white/20 cursor-pointer" onclick="selectService('Bart trimmen', 25, 30)">
                    <div class="text-4xl mb-4">🧔</div>
                    <h3 class="text-xl font-bold text-white mb-2">Bart trimmen</h3>
                    <p class="text-gray-300 mb-4">Professionelle Bartpflege und Styling</p>
                    <div class="flex justify-between items-center">
                        <span class="text-2xl font-bold text-red-400">25€</span>
                        <span class="text-gray-400">30 Min</span>
                    </div>
                </div>

                <div class="service-card bg-white/10 backdrop-blur-lg rounded-xl p-6 border border-white/20 cursor-pointer" onclick="selectService('Komplett-Paket', 55, 75)">
                    <div class="text-4xl mb-4">✨</div>
                    <h3 class="text-xl font-bold text-white mb-2">Komplett-Paket</h3>
                    <p class="text-gray-300 mb-4">Schnitt + Bart + Waschen + Styling</p>
                    <div class="flex justify-between items-center">
                        <span class="text-2xl font-bold text-red-400">55€</span>
                        <span class="text-gray-400">75 Min</span>
                    </div>
                </div>

                <div class="service-card bg-white/10 backdrop-blur-lg rounded-xl p-6 border border-white/20 cursor-pointer" onclick="selectService('Rasur', 30, 40)">
                    <div class="text-4xl mb-4">🪒</div>
                    <h3 class="text-xl font-bold text-white mb-2">Klassische Rasur</h3>
                    <p class="text-gray-300 mb-4">Traditionelle Nassrasur mit heißem Handtuch</p>
                    <div class="flex justify-between items-center">
                        <span class="text-2xl font-bold text-red-400">30€</span>
                        <span class="text-gray-400">40 Min</span>
                    </div>
                </div>

                <div class="service-card bg-white/10 backdrop-blur-lg rounded-xl p-6 border border-white/20 cursor-pointer" onclick="selectService('Kinderschnitt', 20, 30)">
                    <div class="text-4xl mb-4">👶</div>
                    <h3 class="text-xl font-bold text-white mb-2">Kinderschnitt</h3>
                    <p class="text-gray-300 mb-4">Für unsere kleinen Kunden (bis 12 Jahre)</p>
                    <div class="flex justify-between items-center">
                        <span class="text-2xl font-bold text-red-400">20€</span>
                        <span class="text-gray-400">30 Min</span>
                    </div>
                </div>

                <div class="service-card bg-white/10 backdrop-blur-lg rounded-xl p-6 border border-white/20 cursor-pointer" onclick="selectService('Haarpflege', 40, 50)">
                    <div class="text-4xl mb-4">🧴</div>
                    <h3 class="text-xl font-bold text-white mb-2">Haarpflege</h3>
                    <p class="text-gray-300 mb-4">Intensive Haarpflege mit Premium-Produkten</p>
                    <div class="flex justify-between items-center">
                        <span class="text-2xl font-bold text-red-400">40€</span>
                        <span class="text-gray-400">50 Min</span>
                    </div>
                </div>
            </div>
        </div>

        <!-- Step 2: Date & Time Selection -->
        <div id="step2" class="hidden">
            <h2 class="text-3xl font-bold text-white text-center mb-8">Datum und Uhrzeit wählen</h2>
            
            <!-- Selected Service Display -->
            <div id="selected-service" class="bg-red-600/20 border border-red-600/30 rounded-xl p-4 mb-8">
                <div class="flex items-center justify-between">
                    <div>
                        <h3 class="text-lg font-bold text-white" id="service-name"></h3>
                        <p class="text-red-300" id="service-details"></p>
                    </div>
                    <button onclick="goToStep(1)" class="text-red-400 hover:text-red-300 underline">Ändern</button>
                </div>
            </div>

            <div class="grid lg:grid-cols-2 gap-8">
                <!-- Calendar -->
                <div class="bg-white/10 backdrop-blur-lg rounded-xl p-6 border border-white/20">
                    <h3 class="text-xl font-bold text-white mb-4">Datum auswählen</h3>
                    <div class="grid grid-cols-7 gap-2 mb-4">
                        <div class="text-center text-gray-400 font-medium py-2">Mo</div>
                        <div class="text-center text-gray-400 font-medium py-2">Di</div>
                        <div class="text-center text-gray-400 font-medium py-2">Mi</div>
                        <div class="text-center text-gray-400 font-medium py-2">Do</div>
                        <div class="text-center text-gray-400 font-medium py-2">Fr</div>
                        <div class="text-center text-gray-400 font-medium py-2">Sa</div>
                        <div class="text-center text-gray-400 font-medium py-2">So</div>
                    </div>
                    <div id="calendar-grid" class="grid grid-cols-7 gap-2">
                        <!-- Calendar days will be generated by JavaScript -->
                    </div>
                </div>

                <!-- Time Slots -->
                <div class="bg-white/10 backdrop-blur-lg rounded-xl p-6 border border-white/20">
                    <h3 class="text-xl font-bold text-white mb-4">Verfügbare Zeiten</h3>
                    <div id="time-slots" class="grid grid-cols-2 gap-3">
                        <div class="text-center text-gray-400 py-8">
                            Bitte wählen Sie zuerst ein Datum
                        </div>
                    </div>
                </div>
            </div>

            <div class="flex justify-center mt-8">
                <button id="continue-btn" onclick="goToStep(3)" class="bg-red-600 hover:bg-red-700 text-white font-bold py-3 px-8 rounded-lg disabled:opacity-50 disabled:cursor-not-allowed" disabled>
                    Weiter zur Bestätigung
                </button>
            </div>
        </div>

        <!-- Step 3: Confirmation -->
        <div id="step3" class="hidden">
            <h2 class="text-3xl font-bold text-white text-center mb-8">Termin bestätigen</h2>
            
            <div class="max-w-2xl mx-auto">
                <div class="bg-white/10 backdrop-blur-lg rounded-xl p-8 border border-white/20 mb-8">
                    <h3 class="text-xl font-bold text-white mb-6">Ihre Buchungsdetails</h3>
                    
                    <div class="space-y-4">
                        <div class="flex justify-between items-center py-3 border-b border-white/10">
                            <span class="text-gray-300">Dienstleistung:</span>
                            <span class="text-white font-medium" id="confirm-service"></span>
                        </div>
                        <div class="flex justify-between items-center py-3 border-b border-white/10">
                            <span class="text-gray-300">Datum:</span>
                            <span class="text-white font-medium" id="confirm-date"></span>
                        </div>
                        <div class="flex justify-between items-center py-3 border-b border-white/10">
                            <span class="text-gray-300">Uhrzeit:</span>
                            <span class="text-white font-medium" id="confirm-time"></span>
                        </div>
                        <div class="flex justify-between items-center py-3 border-b border-white/10">
                            <span class="text-gray-300">Dauer:</span>
                            <span class="text-white font-medium" id="confirm-duration"></span>
                        </div>
                        <div class="flex justify-between items-center py-3">
                            <span class="text-gray-300 text-lg">Preis:</span>
                            <span class="text-red-400 font-bold text-xl" id="confirm-price"></span>
                        </div>
                    </div>
                </div>

                <!-- Contact Form -->
                <div class="bg-white/10 backdrop-blur-lg rounded-xl p-8 border border-white/20 mb-8">
                    <h3 class="text-xl font-bold text-white mb-6">Ihre Kontaktdaten</h3>
                    <div class="space-y-4">
                        <div>
                            <label class="block text-gray-300 mb-2">Name *</label>
                            <input type="text" id="customer-name" class="w-full bg-white/5 border border-white/20 rounded-lg px-4 py-3 text-white placeholder-gray-400 focus:border-red-500 focus:outline-none" placeholder="Ihr vollständiger Name" required>
                        </div>
                        <div>
                            <label class="block text-gray-300 mb-2">Telefon *</label>
                            <input type="tel" id="customer-phone" class="w-full bg-white/5 border border-white/20 rounded-lg px-4 py-3 text-white placeholder-gray-400 focus:border-red-500 focus:outline-none" placeholder="+49 123 456 789" required>
                        </div>
                        <div>
                            <label class="block text-gray-300 mb-2">E-Mail</label>
                            <input type="email" id="customer-email" class="w-full bg-white/5 border border-white/20 rounded-lg px-4 py-3 text-white placeholder-gray-400 focus:border-red-500 focus:outline-none" placeholder="ihre.email@beispiel.de">
                        </div>
                        <div>
                            <label class="block text-gray-300 mb-2">Besondere Wünsche</label>
                            <textarea id="customer-notes" class="w-full bg-white/5 border border-white/20 rounded-lg px-4 py-3 text-white placeholder-gray-400 focus:border-red-500 focus:outline-none h-24 resize-none" placeholder="Haben Sie besondere Wünsche oder Anmerkungen?"></textarea>
                        </div>
                    </div>
                </div>

                <div class="flex space-x-4">
                    <button onclick="goToStep(2)" class="flex-1 bg-gray-600 hover:bg-gray-700 text-white font-bold py-3 px-6 rounded-lg">
                        Zurück
                    </button>
                    <button onclick="confirmBooking()" class="flex-1 bg-red-600 hover:bg-red-700 text-white font-bold py-3 px-6 rounded-lg">
                        Termin buchen
                    </button>
                </div>
            </div>
        </div>

        <!-- Success Message -->
        <div id="success-message" class="hidden">
            <div class="max-w-2xl mx-auto text-center">
                <div class="bg-green-500/20 border border-green-500/30 rounded-xl p-8 mb-8">
                    <div class="text-6xl mb-4">✅</div>
                    <h2 class="text-3xl font-bold text-white mb-4">Termin erfolgreich gebucht!</h2>
                    <p class="text-gray-300 mb-6">Vielen Dank für Ihre Buchung. Wir haben Ihren Termin bestätigt und werden Sie kurz vorher per SMS/Anruf kontaktieren.</p>
                    
                    <div class="bg-white/10 rounded-lg p-6 mb-6">
                        <h3 class="text-lg font-bold text-white mb-4">Ihre Buchungsnummer</h3>
                        <div class="text-2xl font-mono text-red-400" id="booking-number"></div>
                    </div>
                    
                    <button onclick="newBooking()" class="bg-red-600 hover:bg-red-700 text-white font-bold py-3 px-8 rounded-lg">
                        Neuen Termin buchen
                    </button>
                </div>
            </div>
        </div>

        <!-- Admin Access Button -->
        <div class="fixed bottom-6 right-6">
            <button onclick="showAdminLogin()" class="relative bg-red-600 hover:bg-red-700 text-white p-3 rounded-full shadow-lg">
                <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M10.325 4.317c.426-1.756 2.924-1.756 3.35 0a1.724 1.724 0 002.573 1.066c1.543-.94 3.31.826 2.37 2.37a1.724 1.724 0 001.065 2.572c1.756.426 1.756 2.924 0 3.35a1.724 1.724 0 00-1.066 2.573c.94 1.543-.826 3.31-2.37 2.37a1.724 1.724 0 00-2.572 1.065c-.426 1.756-2.924 1.756-3.35 0a1.724 1.724 0 00-2.573-1.066c-1.543.94-3.31-.826-2.37-2.37a1.724 1.724 0 00-1.065-2.572c-1.756-.426-1.756-2.924 0-3.35a1.724 1.724 0 001.066-2.573c-.94-1.543.826-3.31 2.37-2.37.996.608 2.296.07 2.572-1.065z"></path>
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 12a3 3 0 11-6 0 3 3 0 016 0z"></path>
                </svg>
                <!-- Notification Badge -->
                <div id="notification-badge" class="absolute -top-2 -right-2 bg-red-500 text-white text-xs rounded-full w-6 h-6 flex items-center justify-center notification-badge hidden">
                    <span id="notification-count">0</span>
                </div>
            </button>
        </div>

        <!-- Admin Login Modal -->
        <div id="admin-login-modal" class="fixed inset-0 bg-black/50 backdrop-blur-sm hidden flex items-center justify-center z-50">
            <div class="bg-white/10 backdrop-blur-lg rounded-xl p-8 border border-white/20 max-w-md w-full mx-4">
                <h3 class="text-xl font-bold text-white mb-6">Admin Login</h3>
                <div class="space-y-4">
                    <div>
                        <label class="block text-gray-300 mb-2">Benutzername</label>
                        <input type="text" id="admin-username" class="w-full bg-white/5 border border-white/20 rounded-lg px-4 py-3 text-white placeholder-gray-400 focus:border-red-500 focus:outline-none" placeholder="admin">
                    </div>
                    <div>
                        <label class="block text-gray-300 mb-2">Passwort</label>
                        <input type="password" id="admin-password" class="w-full bg-white/5 border border-white/20 rounded-lg px-4 py-3 text-white placeholder-gray-400 focus:border-red-500 focus:outline-none" placeholder="••••••••">
                    </div>
                </div>
                <div class="flex space-x-4 mt-6">
                    <button onclick="hideAdminLogin()" class="flex-1 bg-gray-600 hover:bg-gray-700 text-white font-bold py-3 px-6 rounded-lg">
                        Abbrechen
                    </button>
                    <button onclick="adminLogin()" class="flex-1 bg-red-600 hover:bg-red-700 text-white font-bold py-3 px-6 rounded-lg">
                        Anmelden
                    </button>
                </div>
            </div>
        </div>
    </div>

    <!-- Notification Popup -->
    <div id="notification-popup" class="fixed top-4 right-4 bg-green-500/90 backdrop-blur-lg text-white p-4 rounded-lg shadow-lg hidden notification-popup z-50">
        <div class="flex items-center space-x-3">
            <div class="text-2xl">🔔</div>
            <div>
                <h4 class="font-bold">Neue Buchung!</h4>
                <p class="text-sm" id="notification-text"></p>
            </div>
            <button onclick="hideNotification()" class="text-white/80 hover:text-white">
                <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12"></path>
                </svg>
            </button>
        </div>
    </div>

    <!-- Admin Panel -->
    <div id="admin-panel" class="hidden min-h-screen bg-gradient-to-br from-black via-gray-900 to-black">
        <!-- Admin Header -->
        <header class="bg-black/20 backdrop-blur-lg border-b border-white/10">
            <div class="max-w-7xl mx-auto px-6 py-4">
                <div class="flex items-center justify-between">
                    <div class="flex items-center space-x-3">
                        <div class="w-10 h-10 bg-gradient-to-r from-red-600 to-red-800 rounded-lg flex items-center justify-center">
                            <span class="text-white font-bold text-lg">⚙️</span>
                        </div>
                        <h1 class="text-2xl font-bold text-white">BarberStyle Admin</h1>
                        <!-- Notification Bell in Admin -->
                        <div class="relative ml-4">
                            <button onclick="showNotifications()" class="text-white hover:text-red-400 p-2">
                                <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 17h5l-1.405-1.405A2.032 2.032 0 0118 14.158V11a6.002 6.002 0 00-4-5.659V5a2 2 0 10-4 0v.341C7.67 6.165 6 8.388 6 11v3.159c0 .538-.214 1.055-.595 1.436L4 17h5m6 0v1a3 3 0 11-6 0v-1m6 0H9"></path>
                                </svg>
                                <div id="admin-notification-badge" class="absolute -top-1 -right-1 bg-red-500 text-white text-xs rounded-full w-5 h-5 flex items-center justify-center notification-badge hidden">
                                    <span id="admin-notification-count">0</span>
                                </div>
                            </button>
                        </div>
                    </div>
                    <button onclick="logoutAdmin()" class="bg-red-600 hover:bg-red-700 text-white px-4 py-2 rounded-lg">
                        Abmelden
                    </button>
                </div>
            </div>
        </header>

        <div class="max-w-7xl mx-auto px-6 py-8">
            <div class="grid lg:grid-cols-4 gap-8">
                <!-- Admin Navigation -->
                <div class="lg:col-span-1">
                    <div class="bg-white/10 backdrop-blur-lg rounded-xl p-6 border border-white/20 sticky top-8">
                        <h3 class="text-lg font-bold text-white mb-4">Navigation</h3>
                        <nav class="space-y-2">
                            <button onclick="showAdminSection('dashboard')" class="admin-nav-item w-full text-left px-4 py-3 rounded-lg bg-red-600 text-white">
                                📊 Dashboard
                            </button>
                            <button onclick="showAdminSection('appointments')" class="admin-nav-item w-full text-left px-4 py-3 rounded-lg text-gray-300 hover:text-white hover:bg-white/10">
                                📅 Termine
                            </button>
                            <button onclick="showAdminSection('customers')" class="admin-nav-item w-full text-left px-4 py-3 rounded-lg text-gray-300 hover:text-white hover:bg-white/10">
                                👥 Kunden
                            </button>
                            <button onclick="showAdminSection('notifications')" class="admin-nav-item w-full text-left px-4 py-3 rounded-lg text-gray-300 hover:text-white hover:bg-white/10 relative">
                                🔔 Benachrichtigungen
                                <div id="nav-notification-badge" class="absolute top-2 right-2 bg-red-500 text-white text-xs rounded-full w-5 h-5 flex items-center justify-center notification-badge hidden">
                                    <span id="nav-notification-count">0</span>
                                </div>
                            </button>
                            <button onclick="showAdminSection('settings')" class="admin-nav-item w-full text-left px-4 py-3 rounded-lg text-gray-300 hover:text-white hover:bg-white/10">
                                🎨 Design & Einstellungen
                            </button>
                        </nav>
                    </div>
                </div>

                <!-- Admin Content -->
                <div class="lg:col-span-3">
                    <!-- Dashboard Section -->
                    <div id="dashboard-section">
                        <h2 class="text-3xl font-bold text-white mb-8">Dashboard</h2>
                        
                        <!-- Stats Cards -->
                        <div class="grid md:grid-cols-3 gap-6 mb-8">
                            <div class="bg-white/10 backdrop-blur-lg rounded-xl p-6 border border-white/20">
                                <div class="flex items-center justify-between">
                                    <div>
                                        <p class="text-gray-300">Heute</p>
                                        <p class="text-2xl font-bold text-white">4 Termine</p>
                                    </div>
                                    <div class="text-3xl">📅</div>
                                </div>
                            </div>
                            <div class="bg-white/10 backdrop-blur-lg rounded-xl p-6 border border-white/20">
                                <div class="flex items-center justify-between">
                                    <div>
                                        <p class="text-gray-300">Diese Woche</p>
                                        <p class="text-2xl font-bold text-white">28 Termine</p>
                                    </div>
                                    <div class="text-3xl">📊</div>
                                </div>
                            </div>
                            <div class="bg-white/10 backdrop-blur-lg rounded-xl p-6 border border-white/20">
                                <div class="flex items-center justify-between">
                                    <div>
                                        <p class="text-gray-300">Umsatz heute</p>
                                        <p class="text-2xl font-bold text-red-400">180€</p>
                                    </div>
                                    <div class="text-3xl">💰</div>
                                </div>
                            </div>
                        </div>

                        <!-- Today's Appointments -->
                        <div class="bg-white/10 backdrop-blur-lg rounded-xl p-6 border border-white/20">
                            <div class="flex items-center justify-between mb-6">
                                <h3 class="text-xl font-bold text-white">Heutige Termine</h3>
                                <span class="text-gray-300" id="today-date"></span>
                            </div>
                            <div id="appointments-list" class="space-y-4">
                                <!-- Appointments will be loaded here -->
                            </div>
                        </div>
                    </div>

                    <!-- Appointments Section -->
                    <div id="appointments-section" class="hidden">
                        <h2 class="text-3xl font-bold text-white mb-8">Terminverwaltung</h2>
                        
                        <div class="bg-white/10 backdrop-blur-lg rounded-xl p-6 border border-white/20 mb-6">
                            <div class="flex items-center justify-between mb-4">
                                <h3 class="text-xl font-bold text-white">Alle Termine</h3>
                                <div class="flex space-x-4">
                                    <select class="bg-white/5 border border-white/20 rounded-lg px-4 py-2 text-white">
                                        <option>Heute</option>
                                        <option>Diese Woche</option>
                                        <option>Diesen Monat</option>
                                    </select>
                                    <button class="bg-red-600 hover:bg-red-700 text-white px-4 py-2 rounded-lg">
                                        + Neuer Termin
                                    </button>
                                </div>
                            </div>
                            
                            <div class="overflow-x-auto">
                                <table class="w-full">
                                    <thead>
                                        <tr class="border-b border-white/20">
                                            <th class="text-left text-gray-300 py-3">Zeit</th>
                                            <th class="text-left text-gray-300 py-3">Kunde</th>
                                            <th class="text-left text-gray-300 py-3">Service</th>
                                            <th class="text-left text-gray-300 py-3">Telefon</th>
                                            <th class="text-left text-gray-300 py-3">Status</th>
                                            <th class="text-left text-gray-300 py-3">Aktionen</th>
                                        </tr>
                                    </thead>
                                    <tbody class="text-white" id="all-appointments-table">
                                        <!-- Dynamic appointments will be loaded here -->
                                    </tbody>
                                </table>
                            </div>
                        </div>
                    </div>

                    <!-- Customers Section -->
                    <div id="customers-section" class="hidden">
                        <h2 class="text-3xl font-bold text-white mb-8">Kundenverwaltung</h2>
                        
                        <div class="bg-white/10 backdrop-blur-lg rounded-xl p-6 border border-white/20">
                            <div class="flex items-center justify-between mb-6">
                                <h3 class="text-xl font-bold text-white">Kundenliste</h3>
                                <div class="flex space-x-4">
                                    <input type="text" placeholder="Kunde suchen..." class="bg-white/5 border border-white/20 rounded-lg px-4 py-2 text-white placeholder-gray-400">
                                    <button class="bg-red-600 hover:bg-red-700 text-white px-4 py-2 rounded-lg">
                                        + Neuer Kunde
                                    </button>
                                </div>
                            </div>
                            
                            <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-4" id="customers-grid">
                                <!-- Dynamic customers will be loaded here -->
                            </div>
                        </div>
                    </div>

                    <!-- Notifications Section -->
                    <div id="notifications-section" class="hidden">
                        <h2 class="text-3xl font-bold text-white mb-8">Benachrichtigungen</h2>
                        
                        <div class="bg-white/10 backdrop-blur-lg rounded-xl p-6 border border-white/20 mb-6">
                            <div class="flex items-center justify-between mb-6">
                                <h3 class="text-xl font-bold text-white">Neue Buchungen</h3>
                                <button onclick="markAllAsRead()" class="text-red-400 hover:text-red-300 underline">
                                    Alle als gelesen markieren
                                </button>
                            </div>
                            
                            <div id="notifications-list" class="space-y-4">
                                <div class="text-center text-gray-400 py-8">
                                    Keine neuen Benachrichtigungen
                                </div>
                            </div>
                        </div>

                        <!-- Notification Settings -->
                        <div class="bg-white/10 backdrop-blur-lg rounded-xl p-6 border border-white/20">
                            <h3 class="text-xl font-bold text-white mb-6">Benachrichtigungs-Einstellungen</h3>
                            
                            <div class="space-y-6">
                                <!-- Browser Notifications -->
                                <div class="flex items-center justify-between">
                                    <div>
                                        <h4 class="text-white font-medium">🌐 Browser-Benachrichtigungen</h4>
                                        <p class="text-gray-400 text-sm">Erhalten Sie Popup-Benachrichtigungen bei neuen Buchungen</p>
                                    </div>
                                    <label class="relative inline-flex items-center cursor-pointer">
                                        <input type="checkbox" id="browser-notifications" class="sr-only peer" checked>
                                        <div class="w-11 h-6 bg-gray-600 peer-focus:outline-none rounded-full peer peer-checked:after:translate-x-full peer-checked:after:border-white after:content-[''] after:absolute after:top-[2px] after:left-[2px] after:bg-white after:rounded-full after:h-5 after:w-5 after:transition-all peer-checked:bg-red-600"></div>
                                    </label>
                                </div>
                                
                                <!-- Sound Notifications -->
                                <div class="flex items-center justify-between">
                                    <div>
                                        <h4 class="text-white font-medium">🔊 Sound-Benachrichtigungen</h4>
                                        <p class="text-gray-400 text-sm">Akustisches Signal bei neuen Buchungen</p>
                                    </div>
                                    <label class="relative inline-flex items-center cursor-pointer">
                                        <input type="checkbox" id="sound-notifications" class="sr-only peer" checked>
                                        <div class="w-11 h-6 bg-gray-600 peer-focus:outline-none rounded-full peer peer-checked:after:translate-x-full peer-checked:after:border-white after:content-[''] after:absolute after:top-[2px] after:left-[2px] after:bg-white after:rounded-full after:h-5 after:w-5 after:transition-all peer-checked:bg-red-600"></div>
                                    </label>
                                </div>

                                <!-- SMS Notifications -->
                                <div class="border-t border-white/10 pt-4">
                                    <div class="flex items-center justify-between mb-4">
                                        <div>
                                            <h4 class="text-white font-medium">📱 SMS-Benachrichtigungen</h4>
                                            <p class="text-gray-400 text-sm">Erhalten Sie SMS bei neuen Buchungen auf Ihr Handy</p>
                                        </div>
                                        <label class="relative inline-flex items-center cursor-pointer">
                                            <input type="checkbox" id="sms-notifications" class="sr-only peer">
                                            <div class="w-11 h-6 bg-gray-600 peer-focus:outline-none rounded-full peer peer-checked:after:translate-x-full peer-checked:after:border-white after:content-[''] after:absolute after:top-[2px] after:left-[2px] after:bg-white after:rounded-full after:h-5 after:w-5 after:transition-all peer-checked:bg-red-600"></div>
                                        </label>
                                    </div>
                                    
                                    <div id="sms-settings" class="space-y-3 opacity-50">
                                        <div>
                                            <label class="block text-gray-300 mb-2">Admin Telefonnummer</label>
                                            <input type="tel" id="admin-phone" placeholder="+49 123 456789" class="w-full bg-white/5 border border-white/20 rounded-lg px-4 py-2 text-white placeholder-gray-400 focus:border-red-500 focus:outline-none" disabled>
                                        </div>
                                        <div class="bg-blue-500/20 border border-blue-500/30 rounded-lg p-3">
                                            <p class="text-blue-300 text-sm">💡 <strong>Demo-Hinweis:</strong> SMS-Versand ist in dieser Demo simuliert. In der echten Version würde ein SMS-Service wie Twilio verwendet werden.</p>
                                        </div>
                                    </div>
                                </div>

                                <!-- Email Notifications -->
                                <div class="border-t border-white/10 pt-4">
                                    <div class="flex items-center justify-between mb-4">
                                        <div>
                                            <h4 class="text-white font-medium">📧 E-Mail-Benachrichtigungen</h4>
                                            <p class="text-gray-400 text-sm">Erhalten Sie E-Mails bei neuen Buchungen</p>
                                        </div>
                                        <label class="relative inline-flex items-center cursor-pointer">
                                            <input type="checkbox" id="email-notifications" class="sr-only peer">
                                            <div class="w-11 h-6 bg-gray-600 peer-focus:outline-none rounded-full peer peer-checked:after:translate-x-full peer-checked:after:border-white after:content-[''] after:absolute after:top-[2px] after:left-[2px] after:bg-white after:rounded-full after:h-5 after:w-5 after:transition-all peer-checked:bg-red-600"></div>
                                        </label>
                                    </div>
                                    
                                    <div id="email-settings" class="space-y-3 opacity-50">
                                        <div>
                                            <label class="block text-gray-300 mb-2">Admin E-Mail</label>
                                            <input type="email" id="admin-email" placeholder="admin@barbershop.de" class="w-full bg-white/5 border border-white/20 rounded-lg px-4 py-2 text-white placeholder-gray-400 focus:border-red-500 focus:outline-none" disabled>
                                        </div>
                                        <div class="bg-blue-500/20 border border-blue-500/30 rounded-lg p-3">
                                            <p class="text-blue-300 text-sm">💡 <strong>Demo-Hinweis:</strong> E-Mail-Versand ist in dieser Demo simuliert. In der echten Version würde ein E-Mail-Service verwendet werden.</p>
                                        </div>
                                    </div>
                                </div>

                                <!-- WhatsApp Notifications -->
                                <div class="border-t border-white/10 pt-4">
                                    <div class="flex items-center justify-between mb-4">
                                        <div>
                                            <h4 class="text-white font-medium">💬 WhatsApp-Benachrichtigungen</h4>
                                            <p class="text-gray-400 text-sm">Erhalten Sie WhatsApp-Nachrichten bei neuen Buchungen</p>
                                        </div>
                                        <label class="relative inline-flex items-center cursor-pointer">
                                            <input type="checkbox" id="whatsapp-notifications" class="sr-only peer">
                                            <div class="w-11 h-6 bg-gray-600 peer-focus:outline-none rounded-full peer peer-checked:after:translate-x-full peer-checked:after:border-white after:content-[''] after:absolute after:top-[2px] after:left-[2px] after:bg-white after:rounded-full after:h-5 after:w-5 after:transition-all peer-checked:bg-red-600"></div>
                                        </label>
                                    </div>
                                    
                                    <div id="whatsapp-settings" class="space-y-3 opacity-50">
                                        <div>
                                            <label class="block text-gray-300 mb-2">WhatsApp Nummer</label>
                                            <input type="tel" id="whatsapp-phone" placeholder="+49 123 456789" class="w-full bg-white/5 border border-white/20 rounded-lg px-4 py-2 text-white placeholder-gray-400 focus:border-red-500 focus:outline-none" disabled>
                                        </div>
                                        <div class="bg-blue-500/20 border border-blue-500/30 rounded-lg p-3">
                                            <p class="text-blue-300 text-sm">💡 <strong>Demo-Hinweis:</strong> WhatsApp-Versand ist in dieser Demo simuliert. In der echten Version würde die WhatsApp Business API verwendet werden.</p>
                                        </div>
                                    </div>
                                </div>

                                <!-- Test Notifications -->
                                <div class="border-t border-white/10 pt-4">
                                    <h4 class="text-white font-medium mb-4">🧪 Test-Benachrichtigungen</h4>
                                    <div class="grid grid-cols-2 gap-3">
                                        <button onclick="testBrowserNotification()" class="bg-blue-600 hover:bg-blue-700 text-white px-4 py-2 rounded-lg text-sm">
                                            Browser testen
                                        </button>
                                        <button onclick="testSMSNotification()" class="bg-green-600 hover:bg-green-700 text-white px-4 py-2 rounded-lg text-sm">
                                            SMS testen
                                        </button>
                                        <button onclick="testEmailNotification()" class="bg-purple-600 hover:bg-purple-700 text-white px-4 py-2 rounded-lg text-sm">
                                            E-Mail testen
                                        </button>
                                        <button onclick="testWhatsAppNotification()" class="bg-green-500 hover:bg-green-600 text-white px-4 py-2 rounded-lg text-sm">
                                            WhatsApp testen
                                        </button>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- Settings Section -->
                    <div id="settings-section" class="hidden">
                        <h2 class="text-3xl font-bold text-white mb-8">Design & Einstellungen</h2>
                        
                        <!-- Design Settings -->
                        <div class="bg-white/10 backdrop-blur-lg rounded-xl p-6 border border-white/20 mb-6">
                            <h3 class="text-xl font-bold text-white mb-6">🎨 Design anpassen</h3>
                            
                            <div class="grid md:grid-cols-2 gap-6">
                                <div>
                                    <h4 class="text-lg font-medium text-white mb-4">Farben</h4>
                                    <div class="space-y-4">
                                        <div>
                                            <label class="block text-gray-300 mb-2">Hauptfarbe</label>
                                            <div class="flex items-center space-x-3">
                                                <input type="color" id="primary-color" value="#661414" class="w-12 h-10 rounded border border-white/20">
                                                <input type="text" value="#661414" class="bg-white/5 border border-white/20 rounded-lg px-3 py-2 text-white text-sm">
                                            </div>
                                        </div>
                                        <div>
                                            <label class="block text-gray-300 mb-2">Akzentfarbe</label>
                                            <div class="flex items-center space-x-3">
                                                <input type="color" id="accent-color" value="#ffffff" class="w-12 h-10 rounded border border-white/20">
                                                <input type="text" value="#ffffff" class="bg-white/5 border border-white/20 rounded-lg px-3 py-2 text-white text-sm">
                                            </div>
                                        </div>
                                        <div>
                                            <label class="block text-gray-300 mb-2">Hintergrundfarbe</label>
                                            <div class="flex items-center space-x-3">
                                                <input type="color" id="background-color" value="#000000" class="w-12 h-10 rounded border border-white/20">
                                                <input type="text" value="#000000" class="bg-white/5 border border-white/20 rounded-lg px-3 py-2 text-white text-sm">
                                            </div>
                                        </div>
                                    </div>
                                </div>
                                
                                <div>
                                    <h4 class="text-lg font-medium text-white mb-4">Texte</h4>
                                    <div class="space-y-4">
                                        <div>
                                            <label class="block text-gray-300 mb-2">Shop Name</label>
                                            <input type="text" id="shop-name" value="BarberStyle" class="w-full bg-white/5 border border-white/20 rounded-lg px-4 py-3 text-white">
                                        </div>
                                        <div>
                                            <label class="block text-gray-300 mb-2">Untertitel</label>
                                            <input type="text" id="shop-tagline" value="Premium Barbershop" class="w-full bg-white/5 border border-white/20 rounded-lg px-4 py-3 text-white">
                                        </div>
                                        <div>
                                            <label class="block text-gray-300 mb-2">Logo hochladen</label>
                                            <div class="border-2 border-dashed border-white/20 rounded-lg p-6 text-center">
                                                <div class="text-gray-400 mb-2">📁</div>
                                                <p class="text-gray-400 text-sm">Logo hier ablegen oder klicken zum Auswählen</p>
                                                <input type="file" accept="image/*" class="hidden">
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                            
                            <div class="flex space-x-4 mt-8">
                                <button onclick="previewDesign()" class="bg-blue-600 hover:bg-blue-700 text-white px-6 py-3 rounded-lg">
                                    👁️ Vorschau
                                </button>
                                <button onclick="saveDesignSettings()" class="bg-green-600 hover:bg-green-700 text-white px-6 py-3 rounded-lg">
                                    💾 Speichern
                                </button>
                                <button onclick="resetToDefaults()" class="bg-gray-600 hover:bg-gray-700 text-white px-6 py-3 rounded-lg">
                                    🔄 Zurücksetzen
                                </button>
                            </div>
                        </div>

                        <!-- Business Settings -->
                        <div class="bg-white/10 backdrop-blur-lg rounded-xl p-6 border border-white/20 mb-6">
                            <h3 class="text-xl font-bold text-white mb-6">🏪 Geschäftseinstellungen</h3>
                            
                            <div class="grid md:grid-cols-2 gap-6">
                                <div>
                                    <h4 class="text-lg font-medium text-white mb-4">Öffnungszeiten</h4>
                                    <div class="space-y-3">
                                        <div class="flex items-center justify-between">
                                            <span class="text-gray-300">Montag</span>
                                            <div class="flex space-x-2">
                                                <input type="time" value="09:00" class="bg-white/5 border border-white/20 rounded px-2 py-1 text-white text-sm">
                                                <span class="text-gray-400">-</span>
                                                <input type="time" value="19:00" class="bg-white/5 border border-white/20 rounded px-2 py-1 text-white text-sm">
                                            </div>
                                        </div>
                                        <div class="flex items-center justify-between">
                                            <span class="text-gray-300">Dienstag</span>
                                            <div class="flex space-x-2">
                                                <input type="time" value="09:00" class="bg-white/5 border border-white/20 rounded px-2 py-1 text-white text-sm">
                                                <span class="text-gray-400">-</span>
                                                <input type="time" value="19:00" class="bg-white/5 border border-white/20 rounded px-2 py-1 text-white text-sm">
                                            </div>
                                        </div>
                                        <div class="flex items-center justify-between">
                                            <span class="text-gray-300">Sonntag</span>
                                            <span class="text-red-400">Geschlossen</span>
                                        </div>
                                    </div>
                                </div>
                                
                                <div>
                                    <h4 class="text-lg font-medium text-white mb-4">Kontaktdaten</h4>
                                    <div class="space-y-4">
                                        <div>
                                            <label class="block text-gray-300 mb-2">Telefon</label>
                                            <input type="tel" value="+49 123 456789" class="w-full bg-white/5 border border-white/20 rounded-lg px-4 py-2 text-white">
                                        </div>
                                        <div>
                                            <label class="block text-gray-300 mb-2">E-Mail</label>
                                            <input type="email" value="info@barberstyle.de" class="w-full bg-white/5 border border-white/20 rounded-lg px-4 py-2 text-white">
                                        </div>
                                        <div>
                                            <label class="block text-gray-300 mb-2">Adresse</label>
                                            <textarea class="w-full bg-white/5 border border-white/20 rounded-lg px-4 py-2 text-white h-20 resize-none">Musterstraße 123
12345 Musterstadt</textarea>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>

                        <!-- Service Management -->
                        <div class="bg-white/10 backdrop-blur-lg rounded-xl p-6 border border-white/20">
                            <h3 class="text-xl font-bold text-white mb-6">✂️ Dienstleistungen verwalten</h3>
                            
                            <div class="space-y-4">
                                <div class="flex items-center justify-between bg-white/5 rounded-lg p-4">
                                    <div class="flex items-center space-x-4">
                                        <span class="text-2xl">💇‍♂️</span>
                                        <div>
                                            <h4 class="text-white font-medium">Herrenschnitt</h4>
                                            <p class="text-gray-400 text-sm">45 Minuten • 35€</p>
                                        </div>
                                    </div>
                                    <div class="flex space-x-2">
                                        <button class="text-blue-400 hover:text-blue-300">Bearbeiten</button>
                                        <button class="text-red-400 hover:text-red-300">Löschen</button>
                                    </div>
                                </div>
                                
                                <div class="flex items-center justify-between bg-white/5 rounded-lg p-4">
                                    <div class="flex items-center space-x-4">
                                        <span class="text-2xl">🧔</span>
                                        <div>
                                            <h4 class="text-white font-medium">Bart trimmen</h4>
                                            <p class="text-gray-400 text-sm">30 Minuten • 25€</p>
                                        </div>
                                    </div>
                                    <div class="flex space-x-2">
                                        <button class="text-blue-400 hover:text-blue-300">Bearbeiten</button>
                                        <button class="text-red-400 hover:text-red-300">Löschen</button>
                                    </div>
                                </div>
                            </div>
                            
                            <button class="mt-4 bg-red-600 hover:bg-red-700 text-white px-4 py-2 rounded-lg">
                                + Neue Dienstleistung
                            </button>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <script>
        let selectedService = null;
        let selectedDate = null;
        let selectedTime = null;
        let currentStep = 1;
        let notifications = [];
        let unreadCount = 0;

        // Available time slots
        const timeSlots = [
            '09:00', '09:30', '10:00', '10:30', '11:00', '11:30',
            '12:00', '12:30', '14:00', '14:30', '15:00', '15:30',
            '16:00', '16:30', '17:00', '17:30', '18:00', '18:30'
        ];

        function selectService(name, price, duration) {
            selectedService = { name, price, duration };
            goToStep(2);
        }

        function goToStep(step) {
            // Hide all steps
            document.getElementById('step1').classList.add('hidden');
            document.getElementById('step2').classList.add('hidden');
            document.getElementById('step3').classList.add('hidden');
            document.getElementById('success-message').classList.add('hidden');

            // Update step indicators
            for (let i = 1; i <= 3; i++) {
                const indicator = document.getElementById(`step${i}-indicator`);
                const text = indicator.nextElementSibling;
                if (i <= step) {
                    indicator.className = 'w-8 h-8 bg-red-600 text-white rounded-full flex items-center justify-center font-bold';
                    text.className = 'ml-2 text-white font-medium';
                } else {
                    indicator.className = 'w-8 h-8 bg-gray-600 text-gray-400 rounded-full flex items-center justify-center font-bold';
                    text.className = 'ml-2 text-gray-400 font-medium';
                }
            }

            // Show current step
            if (step <= 3) {
                document.getElementById(`step${step}`).classList.remove('hidden');
                document.getElementById(`step${step}`).classList.add('fade-in');
            }

            currentStep = step;

            if (step === 2 && selectedService) {
                updateSelectedServiceDisplay();
                generateCalendar();
            } else if (step === 3) {
                updateConfirmationDetails();
            }
        }

        function updateSelectedServiceDisplay() {
            document.getElementById('service-name').textContent = selectedService.name;
            document.getElementById('service-details').textContent = `${selectedService.price}€ • ${selectedService.duration} Minuten`;
        }

        function generateCalendar() {
            const calendarGrid = document.getElementById('calendar-grid');
            const today = new Date();
            const currentMonth = today.getMonth();
            const currentYear = today.getFullYear();

            // Get first day of month and number of days
            const firstDay = new Date(currentYear, currentMonth, 1);
            const lastDay = new Date(currentYear, currentMonth + 1, 0);
            const daysInMonth = lastDay.getDate();
            const startingDayOfWeek = (firstDay.getDay() + 6) % 7; // Convert to Monday = 0

            calendarGrid.innerHTML = '';

            // Add empty cells for days before the first day of the month
            for (let i = 0; i < startingDayOfWeek; i++) {
                const emptyDay = document.createElement('div');
                calendarGrid.appendChild(emptyDay);
            }

            // Add days of the month
            for (let day = 1; day <= daysInMonth; day++) {
                const dayElement = document.createElement('div');
                const date = new Date(currentYear, currentMonth, day);
                const isToday = date.toDateString() === today.toDateString();
                const isPast = date < today && !isToday;
                const isWeekend = date.getDay() === 0; // Sunday closed

                dayElement.textContent = day;
                dayElement.className = 'calendar-day text-center py-3 rounded-lg cursor-pointer';

                if (isPast || isWeekend) {
                    dayElement.className += ' text-gray-500 cursor-not-allowed';
                } else {
                    dayElement.className += ' text-white bg-white/5 hover:bg-red-600/20 border border-white/10';
                    dayElement.onclick = () => selectDate(date);
                }

                if (isToday) {
                    dayElement.className += ' ring-2 ring-red-600';
                }

                calendarGrid.appendChild(dayElement);
            }
        }

        function selectDate(date) {
            selectedDate = date;
            
            // Update calendar selection
            document.querySelectorAll('.calendar-day').forEach(day => {
                day.classList.remove('bg-red-600', 'text-white');
                if (day.textContent == date.getDate() && !day.classList.contains('text-gray-500')) {
                    day.classList.add('bg-red-600', 'text-white');
                }
            });

            generateTimeSlots();
        }

        function generateTimeSlots() {
            const timeSlotsContainer = document.getElementById('time-slots');
            timeSlotsContainer.innerHTML = '';

            // Calculate available slots based on service duration
            const serviceDuration = selectedService.duration;
            const availableSlots = [];

            for (let i = 0; i < timeSlots.length; i++) {
                const currentTime = timeSlots[i];
                const [hours, minutes] = currentTime.split(':').map(Number);
                const currentMinutes = hours * 60 + minutes;
                const endMinutes = currentMinutes + serviceDuration;
                
                // Check if service would end before closing time (19:00 = 1140 minutes)
                if (endMinutes <= 1140) {
                    availableSlots.push(currentTime);
                }
            }

            // Simulate some booked slots
            const bookedSlots = ['10:30', '14:00', '16:30'];

            availableSlots.forEach(time => {
                const timeElement = document.createElement('div');
                timeElement.textContent = time;
                timeElement.className = 'time-slot text-center py-3 rounded-lg cursor-pointer';

                if (bookedSlots.includes(time)) {
                    timeElement.className += ' text-gray-500 bg-gray-600/20 cursor-not-allowed';
                    timeElement.innerHTML += '<br><small>Belegt</small>';
                } else {
                    timeElement.className += ' text-white bg-white/5 hover:bg-red-600/20 border border-white/10';
                    timeElement.onclick = () => selectTime(time);
                }

                timeSlotsContainer.appendChild(timeElement);
            });
        }

        function selectTime(time) {
            selectedTime = time;
            
            // Update time selection
            document.querySelectorAll('.time-slot').forEach(slot => {
                slot.classList.remove('bg-red-600', 'text-white');
                if (slot.textContent.includes(time) && !slot.classList.contains('text-gray-500')) {
                    slot.classList.add('bg-red-600', 'text-white');
                }
            });

            // Enable continue button
            document.getElementById('continue-btn').disabled = false;
        }

        function updateConfirmationDetails() {
            document.getElementById('confirm-service').textContent = selectedService.name;
            document.getElementById('confirm-date').textContent = selectedDate.toLocaleDateString('de-DE', {
                weekday: 'long',
                year: 'numeric',
                month: 'long',
                day: 'numeric'
            });
            document.getElementById('confirm-time').textContent = selectedTime;
            document.getElementById('confirm-duration').textContent = `${selectedService.duration} Minuten`;
            document.getElementById('confirm-price').textContent = `${selectedService.price}€`;
        }

        function confirmBooking() {
            const name = document.getElementById('customer-name').value;
            const phone = document.getElementById('customer-phone').value;
            const email = document.getElementById('customer-email').value;
            const notes = document.getElementById('customer-notes').value;

            if (!name || !phone) {
                alert('Bitte füllen Sie alle Pflichtfelder aus.');
                return;
            }

            // Generate booking number
            const bookingNumber = 'BS' + Date.now().toString().slice(-6);
            document.getElementById('booking-number').textContent = bookingNumber;

            // Create new booking object
            const newBooking = {
                id: bookingNumber,
                time: selectedTime,
                customer: name,
                service: selectedService.name,
                phone: phone,
                email: email,
                notes: notes,
                date: selectedDate.toLocaleDateString('de-DE'),
                price: selectedService.price,
                duration: selectedService.duration,
                status: 'pending',
                timestamp: new Date().toISOString()
            };

            // Save booking to localStorage (in real app would be database)
            let bookings = JSON.parse(localStorage.getItem('barbershop-bookings') || '[]');
            bookings.push(newBooking);
            localStorage.setItem('barbershop-bookings', JSON.stringify(bookings));

            // Send admin notification
            sendAdminNotification(newBooking);

            // Hide all steps and show success
            document.getElementById('step1').classList.add('hidden');
            document.getElementById('step2').classList.add('hidden');
            document.getElementById('step3').classList.add('hidden');
            document.getElementById('success-message').classList.remove('hidden');
            document.getElementById('success-message').classList.add('fade-in');

            // Reset step indicators
            for (let i = 1; i <= 3; i++) {
                const indicator = document.getElementById(`step${i}-indicator`);
                const text = indicator.nextElementSibling;
                indicator.className = 'w-8 h-8 bg-gray-600 text-gray-400 rounded-full flex items-center justify-center font-bold';
                text.className = 'ml-2 text-gray-400 font-medium';
            }
        }

        function sendAdminNotification(booking) {
            // Create notification object
            const notification = {
                id: Date.now(),
                type: 'new_booking',
                title: 'Neue Buchung!',
                message: `${booking.customer} hat einen Termin für ${booking.service} am ${booking.date} um ${booking.time} gebucht.`,
                booking: booking,
                timestamp: new Date().toISOString(),
                read: false
            };

            // Add to notifications array
            notifications.unshift(notification);
            unreadCount++;

            // Update notification badges
            updateNotificationBadges();

            // Show popup notification
            showNotificationPopup(notification);

            // Play notification sound (if enabled)
            playNotificationSound();

            // Send additional notifications based on settings
            sendSMSNotification(notification);
            sendEmailNotification(notification);
            sendWhatsAppNotification(notification);

            // Save to localStorage
            localStorage.setItem('barbershop-notifications', JSON.stringify(notifications));
        }

        function sendSMSNotification(notification) {
            const smsEnabled = document.getElementById('sms-notifications')?.checked;
            const adminPhone = document.getElementById('admin-phone')?.value;
            
            if (smsEnabled && adminPhone) {
                // In a real application, this would send an actual SMS via Twilio or similar service
                console.log('📱 SMS würde gesendet werden an:', adminPhone);
                console.log('📱 SMS Inhalt:', notification.message);
                
                // Simulate SMS sending with a delay
                setTimeout(() => {
                    showSimulatedNotification('SMS', `SMS an ${adminPhone} gesendet: "${notification.message}"`);
                }, 1000);
            }
        }

        function sendEmailNotification(notification) {
            const emailEnabled = document.getElementById('email-notifications')?.checked;
            const adminEmail = document.getElementById('admin-email')?.value;
            
            if (emailEnabled && adminEmail) {
                // In a real application, this would send an actual email via SendGrid, Mailgun, etc.
                console.log('📧 E-Mail würde gesendet werden an:', adminEmail);
                console.log('📧 E-Mail Betreff:', notification.title);
                console.log('📧 E-Mail Inhalt:', notification.message);
                
                // Simulate email sending with a delay
                setTimeout(() => {
                    showSimulatedNotification('E-Mail', `E-Mail an ${adminEmail} gesendet: "${notification.title}"`);
                }, 1500);
            }
        }

        function sendWhatsAppNotification(notification) {
            const whatsappEnabled = document.getElementById('whatsapp-notifications')?.checked;
            const whatsappPhone = document.getElementById('whatsapp-phone')?.value;
            
            if (whatsappEnabled && whatsappPhone) {
                // In a real application, this would send via WhatsApp Business API
                console.log('💬 WhatsApp würde gesendet werden an:', whatsappPhone);
                console.log('💬 WhatsApp Inhalt:', notification.message);
                
                // Simulate WhatsApp sending with a delay
                setTimeout(() => {
                    showSimulatedNotification('WhatsApp', `WhatsApp an ${whatsappPhone} gesendet: "${notification.message}"`);
                }, 2000);
            }
        }

        function showSimulatedNotification(type, message) {
            // Create a temporary notification popup to show the simulated sending
            const popup = document.createElement('div');
            popup.className = 'fixed top-20 right-4 bg-blue-500/90 backdrop-blur-lg text-white p-4 rounded-lg shadow-lg z-50 notification-popup';
            popup.innerHTML = `
                <div class="flex items-center space-x-3">
                    <div class="text-2xl">${type === 'SMS' ? '📱' : type === 'E-Mail' ? '📧' : '💬'}</div>
                    <div>
                        <h4 class="font-bold">${type} Demo</h4>
                        <p class="text-sm">${message}</p>
                    </div>
                    <button onclick="this.parentElement.parentElement.remove()" class="text-white/80 hover:text-white">
                        <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12"></path>
                        </svg>
                    </button>
                </div>
            `;
            document.body.appendChild(popup);
            
            // Auto-remove after 4 seconds
            setTimeout(() => {
                if (popup.parentElement) {
                    popup.remove();
                }
            }, 4000);
        }

        // Test notification functions
        function testBrowserNotification() {
            const testNotification = {
                id: Date.now(),
                type: 'test',
                title: 'Test Browser-Benachrichtigung',
                message: 'Dies ist eine Test-Benachrichtigung für den Browser.',
                timestamp: new Date().toISOString(),
                read: false
            };
            
            showNotificationPopup(testNotification);
            playNotificationSound();
        }

        function testSMSNotification() {
            const adminPhone = document.getElementById('admin-phone')?.value || '+49 123 456789';
            const testMessage = 'Test SMS: Neue Buchung von Max Mustermann für Herrenschnitt am 20.12.2024 um 10:00.';
            
            showSimulatedNotification('SMS', `Test-SMS an ${adminPhone} gesendet: "${testMessage}"`);
        }

        function testEmailNotification() {
            const adminEmail = document.getElementById('admin-email')?.value || 'admin@barbershop.de';
            const testSubject = 'Test E-Mail: Neue Buchung';
            
            showSimulatedNotification('E-Mail', `Test-E-Mail an ${adminEmail} gesendet: "${testSubject}"`);
        }

        function testWhatsAppNotification() {
            const whatsappPhone = document.getElementById('whatsapp-phone')?.value || '+49 123 456789';
            const testMessage = 'Test WhatsApp: Neue Buchung von Max Mustermann für Herrenschnitt am 20.12.2024 um 10:00.';
            
            showSimulatedNotification('WhatsApp', `Test-WhatsApp an ${whatsappPhone} gesendet: "${testMessage}"`);
        }

        function updateNotificationBadges() {
            const badges = [
                'notification-badge',
                'admin-notification-badge', 
                'nav-notification-badge'
            ];
            
            const counts = [
                'notification-count',
                'admin-notification-count',
                'nav-notification-count'
            ];

            badges.forEach((badgeId, index) => {
                const badge = document.getElementById(badgeId);
                const count = document.getElementById(counts[index]);
                
                if (unreadCount > 0) {
                    badge.classList.remove('hidden');
                    count.textContent = unreadCount;
                } else {
                    badge.classList.add('hidden');
                }
            });
        }

        function showNotificationPopup(notification) {
            const popup = document.getElementById('notification-popup');
            const text = document.getElementById('notification-text');
            
            text.textContent = notification.message;
            popup.classList.remove('hidden');
            
            // Auto-hide after 5 seconds
            setTimeout(() => {
                hideNotification();
            }, 5000);
        }

        function hideNotification() {
            document.getElementById('notification-popup').classList.add('hidden');
        }

        function playNotificationSound() {
            // Create a simple beep sound using Web Audio API
            if (document.getElementById('sound-notifications')?.checked !== false) {
                try {
                    const audioContext = new (window.AudioContext || window.webkitAudioContext)();
                    const oscillator = audioContext.createOscillator();
                    const gainNode = audioContext.createGain();
                    
                    oscillator.connect(gainNode);
                    gainNode.connect(audioContext.destination);
                    
                    oscillator.frequency.value = 800;
                    oscillator.type = 'sine';
                    
                    gainNode.gain.setValueAtTime(0.3, audioContext.currentTime);
                    gainNode.gain.exponentialRampToValueAtTime(0.01, audioContext.currentTime + 0.5);
                    
                    oscillator.start(audioContext.currentTime);
                    oscillator.stop(audioContext.currentTime + 0.5);
                } catch (e) {
                    console.log('Audio notification not supported');
                }
            }
        }

        function newBooking() {
            // Reset all selections
            selectedService = null;
            selectedDate = null;
            selectedTime = null;
            
            // Clear form
            document.getElementById('customer-name').value = '';
            document.getElementById('customer-phone').value = '';
            document.getElementById('customer-email').value = '';
            document.getElementById('customer-notes').value = '';
            
            // Go back to step 1
            goToStep(1);
        }

        function showAdminLogin() {
            document.getElementById('admin-login-modal').classList.remove('hidden');
        }

        function hideAdminLogin() {
            document.getElementById('admin-login-modal').classList.add('hidden');
            document.getElementById('admin-username').value = '';
            document.getElementById('admin-password').value = '';
        }

        function adminLogin() {
            const username = document.getElementById('admin-username').value;
            const password = document.getElementById('admin-password').value;

            // Simple demo login (in real app, this would be secure)
            if (username === 'admin' && password === 'admin123') {
                hideAdminLogin();
                showAdminPanel();
            } else {
                alert('Ungültige Anmeldedaten');
            }
        }

        function showAdminPanel() {
            // Hide booking interface
            document.querySelector('.max-w-6xl').style.display = 'none';
            
            // Show admin panel
            document.getElementById('admin-panel').classList.remove('hidden');
            loadAdminDashboard();
            loadNotifications();
        }

        function loadAdminDashboard() {
            // Load today's appointments
            const today = new Date().toLocaleDateString('de-DE');
            document.getElementById('today-date').textContent = today;
            
            // Load bookings from localStorage
            const bookings = JSON.parse(localStorage.getItem('barbershop-bookings') || '[]');
            
            // Sample appointments data (merge with real bookings)
            const sampleAppointments = [
                { time: '09:00', customer: 'Max Mustermann', service: 'Herrenschnitt', phone: '+49 123 456789', status: 'confirmed' },
                { time: '10:30', customer: 'Anna Schmidt', service: 'Komplett-Paket', phone: '+49 987 654321', status: 'pending' }
            ];
            
            // Combine sample with real bookings for today
            const todayBookings = bookings.filter(booking => booking.date === today);
            const allAppointments = [...sampleAppointments, ...todayBookings];
            
            displayAppointments(allAppointments);
            loadAllAppointments();
            loadCustomers();
        }

        function displayAppointments(appointments) {
            const container = document.getElementById('appointments-list');
            container.innerHTML = '';
            
            if (appointments.length === 0) {
                container.innerHTML = '<div class="text-center text-gray-400 py-8">Keine Termine für heute</div>';
                return;
            }
            
            appointments.forEach(apt => {
                const statusColor = apt.status === 'confirmed' ? 'text-green-400' : 'text-yellow-400';
                const statusText = apt.status === 'confirmed' ? 'Bestätigt' : 'Ausstehend';
                
                const aptElement = document.createElement('div');
                aptElement.className = 'bg-white/10 rounded-lg p-4 border border-white/20';
                aptElement.innerHTML = `
                    <div class="flex justify-between items-start">
                        <div>
                            <div class="flex items-center space-x-3 mb-2">
                                <span class="text-red-400 font-bold">${apt.time}</span>
                                <span class="text-white font-medium">${apt.customer}</span>
                                <span class="${statusColor} text-sm">${statusText}</span>
                            </div>
                            <div class="text-gray-300 text-sm">${apt.service}</div>
                            <div class="text-gray-400 text-sm">${apt.phone}</div>
                        </div>
                        <div class="flex space-x-2">
                            <button onclick="editAppointment('${apt.time}')" class="text-blue-400 hover:text-blue-300">
                                <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M11 5H6a2 2 0 00-2 2v11a2 2 0 002 2h11a2 2 0 002-2v-5m-1.414-9.414a2 2 0 112.828 2.828L11.828 15H9v-2.828l8.586-8.586z"></path>
                                </svg>
                            </button>
                            <button onclick="cancelAppointment('${apt.time}')" class="text-red-400 hover:text-red-300">
                                <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 7l-.867 12.142A2 2 0 0116.138 21H7.862a2 2 0 01-1.995-1.858L5 7m5 4v6m4-6v6m1-10V4a1 1 0 00-1-1h-4a1 1 0 00-1 1v3M4 7h16"></path>
                                </svg>
                            </button>
                        </div>
                    </div>
                `;
                container.appendChild(aptElement);
            });
        }

        function loadAllAppointments() {
            const bookings = JSON.parse(localStorage.getItem('barbershop-bookings') || '[]');
            const tableBody = document.getElementById('all-appointments-table');
            
            // Sample data
            const sampleData = [
                { time: '09:00', customer: 'Max Mustermann', service: 'Herrenschnitt', phone: '+49 123 456789', status: 'confirmed' },
                { time: '10:30', customer: 'Anna Schmidt', service: 'Komplett-Paket', phone: '+49 987 654321', status: 'pending' }
            ];
            
            const allAppointments = [...sampleData, ...bookings];
            
            tableBody.innerHTML = '';
            allAppointments.forEach(apt => {
                const statusColor = apt.status === 'confirmed' ? 'text-green-400' : 'text-yellow-400';
                const statusText = apt.status === 'confirmed' ? 'Bestätigt' : 'Ausstehend';
                
                const row = document.createElement('tr');
                row.className = 'border-b border-white/10';
                row.innerHTML = `
                    <td class="py-3">${apt.time}</td>
                    <td class="py-3">${apt.customer}</td>
                    <td class="py-3">${apt.service}</td>
                    <td class="py-3">${apt.phone}</td>
                    <td class="py-3"><span class="${statusColor}">${statusText}</span></td>
                    <td class="py-3">
                        <button class="text-blue-400 hover:text-blue-300 mr-2">Bearbeiten</button>
                        <button class="text-red-400 hover:text-red-300">Stornieren</button>
                    </td>
                `;
                tableBody.appendChild(row);
            });
        }

        function loadCustomers() {
            const bookings = JSON.parse(localStorage.getItem('barbershop-bookings') || '[]');
            const customersGrid = document.getElementById('customers-grid');
            
            // Sample customers
            const sampleCustomers = [
                { name: 'Max Mustermann', phone: '+49 123 456789', lastVisit: '15.12.2024', visits: 5 },
                { name: 'Anna Schmidt', phone: '+49 987 654321', lastVisit: '10.12.2024', visits: 3 },
                { name: 'Peter Weber', phone: '+49 555 123456', lastVisit: '08.12.2024', visits: 8 }
            ];
            
            // Extract unique customers from bookings
            const realCustomers = bookings.reduce((acc, booking) => {
                const existing = acc.find(c => c.phone === booking.phone);
                if (existing) {
                    existing.visits++;
                } else {
                    acc.push({
                        name: booking.customer,
                        phone: booking.phone,
                        lastVisit: booking.date,
                        visits: 1
                    });
                }
                return acc;
            }, []);
            
            const allCustomers = [...sampleCustomers, ...realCustomers];
            
            customersGrid.innerHTML = '';
            allCustomers.forEach(customer => {
                const customerCard = document.createElement('div');
                customerCard.className = 'bg-white/5 rounded-lg p-4 border border-white/10';
                customerCard.innerHTML = `
                    <h4 class="text-white font-medium">${customer.name}</h4>
                    <p class="text-gray-300 text-sm">${customer.phone}</p>
                    <p class="text-gray-400 text-sm">Letzter Besuch: ${customer.lastVisit}</p>
                    <p class="text-red-400 text-sm">${customer.visits} Termine</p>
                `;
                customersGrid.appendChild(customerCard);
            });
        }

        function loadNotifications() {
            // Load notifications from localStorage
            const savedNotifications = JSON.parse(localStorage.getItem('barbershop-notifications') || '[]');
            notifications = savedNotifications;
            unreadCount = notifications.filter(n => !n.read).length;
            
            updateNotificationBadges();
            displayNotifications();
        }

        function displayNotifications() {
            const container = document.getElementById('notifications-list');
            container.innerHTML = '';
            
            if (notifications.length === 0) {
                container.innerHTML = '<div class="text-center text-gray-400 py-8">Keine neuen Benachrichtigungen</div>';
                return;
            }
            
            notifications.forEach(notification => {
                const notificationElement = document.createElement('div');
                notificationElement.className = `bg-white/10 rounded-lg p-4 border border-white/20 ${!notification.read ? 'ring-2 ring-red-600/50' : ''}`;
                
                const timeAgo = getTimeAgo(new Date(notification.timestamp));
                
                notificationElement.innerHTML = `
                    <div class="flex justify-between items-start">
                        <div class="flex-1">
                            <div class="flex items-center space-x-2 mb-2">
                                <span class="text-2xl">🔔</span>
                                <h4 class="text-white font-medium">${notification.title}</h4>
                                ${!notification.read ? '<span class="bg-red-600 text-white text-xs px-2 py-1 rounded-full">Neu</span>' : ''}
                            </div>
                            <p class="text-gray-300 text-sm mb-2">${notification.message}</p>
                            <p class="text-gray-400 text-xs">${timeAgo}</p>
                        </div>
                        <div class="flex space-x-2 ml-4">
                            ${!notification.read ? `<button onclick="markAsRead(${notification.id})" class="text-blue-400 hover:text-blue-300 text-sm">Als gelesen markieren</button>` : ''}
                            <button onclick="deleteNotification(${notification.id})" class="text-red-400 hover:text-red-300 text-sm">Löschen</button>
                        </div>
                    </div>
                `;
                container.appendChild(notificationElement);
            });
        }

        function getTimeAgo(date) {
            const now = new Date();
            const diffInMinutes = Math.floor((now - date) / (1000 * 60));
            
            if (diffInMinutes < 1) return 'Gerade eben';
            if (diffInMinutes < 60) return `vor ${diffInMinutes} Minuten`;
            
            const diffInHours = Math.floor(diffInMinutes / 60);
            if (diffInHours < 24) return `vor ${diffInHours} Stunden`;
            
            const diffInDays = Math.floor(diffInHours / 24);
            return `vor ${diffInDays} Tagen`;
        }

        function markAsRead(notificationId) {
            const notification = notifications.find(n => n.id === notificationId);
            if (notification && !notification.read) {
                notification.read = true;
                unreadCount--;
                updateNotificationBadges();
                displayNotifications();
                localStorage.setItem('barbershop-notifications', JSON.stringify(notifications));
            }
        }

        function markAllAsRead() {
            notifications.forEach(n => n.read = true);
            unreadCount = 0;
            updateNotificationBadges();
            displayNotifications();
            localStorage.setItem('barbershop-notifications', JSON.stringify(notifications));
        }

        function deleteNotification(notificationId) {
            const index = notifications.findIndex(n => n.id === notificationId);
            if (index > -1) {
                const notification = notifications[index];
                if (!notification.read) {
                    unreadCount--;
                }
                notifications.splice(index, 1);
                updateNotificationBadges();
                displayNotifications();
                localStorage.setItem('barbershop-notifications', JSON.stringify(notifications));
            }
        }

        function showAdminSection(section) {
            // Hide all sections
            document.getElementById('dashboard-section').classList.add('hidden');
            document.getElementById('appointments-section').classList.add('hidden');
            document.getElementById('customers-section').classList.add('hidden');
            document.getElementById('notifications-section').classList.add('hidden');
            document.getElementById('settings-section').classList.add('hidden');
            
            // Show selected section
            document.getElementById(section + '-section').classList.remove('hidden');
            
            // Update navigation
            document.querySelectorAll('.admin-nav-item').forEach(item => {
                item.classList.remove('bg-red-600', 'text-white');
                item.classList.add('text-gray-300', 'hover:text-white', 'hover:bg-white/10');
            });
            
            event.target.classList.remove('text-gray-300', 'hover:text-white', 'hover:bg-white/10');
            event.target.classList.add('bg-red-600', 'text-white');
            
            if (section === 'settings') {
                loadCurrentSettings();
            } else if (section === 'notifications') {
                displayNotifications();
            }
        }

        function showNotifications() {
            showAdminSection('notifications');
        }

        function loadCurrentSettings() {
            // Load current design settings
            const currentSettings = {
                primaryColor: '#661414',
                accentColor: '#ffffff',
                backgroundColor: '#000000',
                shopName: 'BarberStyle',
                shopTagline: 'Premium Barbershop'
            };
            
            document.getElementById('primary-color').value = currentSettings.primaryColor;
            document.getElementById('accent-color').value = currentSettings.accentColor;
            document.getElementById('background-color').value = currentSettings.backgroundColor;
            document.getElementById('shop-name').value = currentSettings.shopName;
            document.getElementById('shop-tagline').value = currentSettings.shopTagline;
        }

        function previewDesign() {
            const primaryColor = document.getElementById('primary-color').value;
            const accentColor = document.getElementById('accent-color').value;
            const backgroundColor = document.getElementById('background-color').value;
            const shopName = document.getElementById('shop-name').value;
            const shopTagline = document.getElementById('shop-tagline').value;
            
            // Apply preview styles
            document.documentElement.style.setProperty('--primary-color', primaryColor);
            document.documentElement.style.setProperty('--accent-color', accentColor);
            document.documentElement.style.setProperty('--background-color', backgroundColor);
            
            // Update text content
            document.querySelector('h1').textContent = shopName;
            document.querySelector('.text-red-400').textContent = shopTagline;
            
            alert('Vorschau wird angewendet! Scrollen Sie nach unten, um die Änderungen zu sehen.');
        }

        function saveDesignSettings() {
            const settings = {
                primaryColor: document.getElementById('primary-color').value,
                accentColor: document.getElementById('accent-color').value,
                backgroundColor: document.getElementById('background-color').value,
                shopName: document.getElementById('shop-name').value,
                shopTagline: document.getElementById('shop-tagline').value
            };
            
            // In a real app, this would save to database
            localStorage.setItem('barbershop-settings', JSON.stringify(settings));
            alert('Design-Einstellungen wurden gespeichert!');
        }

        function resetToDefaults() {
            document.getElementById('primary-color').value = '#661414';
            document.getElementById('accent-color').value = '#ffffff';
            document.getElementById('background-color').value = '#000000';
            document.getElementById('shop-name').value = 'BarberStyle';
            document.getElementById('shop-tagline').value = 'Premium Barbershop';
            
            previewDesign();
        }

        function logoutAdmin() {
            document.getElementById('admin-panel').classList.add('hidden');
            document.querySelector('.max-w-6xl').style.display = 'block';
        }

        function editAppointment(time) {
            alert(`Termin um ${time} bearbeiten (Demo-Funktion)`);
        }

        function cancelAppointment(time) {
            if (confirm(`Termin um ${time} wirklich stornieren?`)) {
                alert(`Termin um ${time} wurde storniert`);
                loadAdminDashboard(); // Refresh list
            }
        }

        // Initialize the app
        document.addEventListener('DOMContentLoaded', function() {
            goToStep(1);
            loadNotifications();
            setupNotificationToggles();
            
            // Request notification permission
            if ('Notification' in window && Notification.permission === 'default') {
                Notification.requestPermission();
            }
        });

        function setupNotificationToggles() {
            // Setup toggle functionality for notification settings
            const smsToggle = document.getElementById('sms-notifications');
            const emailToggle = document.getElementById('email-notifications');
            const whatsappToggle = document.getElementById('whatsapp-notifications');
            
            if (smsToggle) {
                smsToggle.addEventListener('change', function() {
                    const settings = document.getElementById('sms-settings');
                    const phoneInput = document.getElementById('admin-phone');
                    
                    if (this.checked) {
                        settings.classList.remove('opacity-50');
                        phoneInput.disabled = false;
                        phoneInput.focus();
                    } else {
                        settings.classList.add('opacity-50');
                        phoneInput.disabled = true;
                    }
                });
            }
            
            if (emailToggle) {
                emailToggle.addEventListener('change', function() {
                    const settings = document.getElementById('email-settings');
                    const emailInput = document.getElementById('admin-email');
                    
                    if (this.checked) {
                        settings.classList.remove('opacity-50');
                        emailInput.disabled = false;
                        emailInput.focus();
                    } else {
                        settings.classList.add('opacity-50');
                        emailInput.disabled = true;
                    }
                });
            }
            
            if (whatsappToggle) {
                whatsappToggle.addEventListener('change', function() {
                    const settings = document.getElementById('whatsapp-settings');
                    const phoneInput = document.getElementById('whatsapp-phone');
                    
                    if (this.checked) {
                        settings.classList.remove('opacity-50');
                        phoneInput.disabled = false;
                        phoneInput.focus();
                    } else {
                        settings.classList.add('opacity-50');
                        phoneInput.disabled = true;
                    }
                });
            }
        }
    </script>
<script>(function(){function c(){var b=a.contentDocument||a.contentWindow.document;if(b){var d=b.createElement('script');d.innerHTML="window.__CF$cv$params={r:'97ad6a2d438a5da5',t:'MTc1NzE1NTkyNC4wMDAwMDA='};var a=document.createElement('script');a.nonce='';a.src='/cdn-cgi/challenge-platform/scripts/jsd/main.js';document.getElementsByTagName('head')[0].appendChild(a);";b.getElementsByTagName('head')[0].appendChild(d)}}if(document.body){var a=document.createElement('iframe');a.height=1;a.width=1;a.style.position='absolute';a.style.top=0;a.style.left=0;a.style.border='none';a.style.visibility='hidden';document.body.appendChild(a);if('loading'!==document.readyState)c();else if(window.addEventListener)document.addEventListener('DOMContentLoaded',c);else{var e=document.onreadystatechange||function(){};document.onreadystatechange=function(b){e(b);'loading'!==document.readyState&&(document.onreadystatechange=e,c())}}}})();</script></body>
</html>
