```html
<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dr. Shelke Herbalcure | Premium Ayurvedic Care</title>
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Cinzel:wght@500;600;700;800&family=Plus+Jakarta+Sans:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <!-- Lucide Icons -->
    <script src="https://unpkg.com/lucide@latest"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        emerald: {
                            900: '#08331E',
                            800: '#0B4528',
                            700: '#115C36',
                            50: '#F0F7F3',
                        },
                        gold: {
                            DEFAULT: '#D4AF37',
                            light: '#F3E5AB',
                            dark: '#AA820A'
                        },
                        ivory: '#FBF9F5'
                    },
                    fontFamily: {
                        serif: ['Cinzel', 'serif'],
                        sans: ['Plus Jakarta Sans', 'sans-serif'],
                    }
                }
            }
        }
    </script>
    <style>
        body {
            background-color: #FBF9F5;
            color: #1a1a1a;
            font-family: 'Plus Jakarta Sans', sans-serif;
        }
        .glass-card {
            background: rgba(255, 255, 255, 0.85);
            backdrop-filter: blur(12px);
            border: 1px solid rgba(212, 175, 55, 0.25);
        }
        .glass-dark {
            background: rgba(8, 51, 30, 0.95);
            backdrop-filter: blur(12px);
            border: 1px solid rgba(212, 175, 55, 0.3);
        }
        .gold-border {
            border-color: #D4AF37;
        }
        .gold-gradient-text {
            background: linear-gradient(135deg, #FFF0B3 0%, #D4AF37 50%, #997A15 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
        .gold-button {
            background: linear-gradient(135deg, #D4AF37 0%, #B8901C 100%);
            color: #08331E;
            transition: all 0.3s ease;
        }
        .gold-button:hover {
            background: linear-gradient(135deg, #E2BF48 0%, #C99F24 100%);
            transform: translateY(-2px);
            box-shadow: 0 4px 15px rgba(212, 175, 55, 0.4);
        }
    </style>
</head>
<body class="bg-ivory min-h-screen flex flex-col justify-between">

    <!-- TOP ANNOUNCEMENT BAR -->
    <div class="bg-emerald-900 text-gold text-xs sm:text-sm py-2 text-center font-medium border-b border-gold/30 px-4">
        🌿 100% Authentic Pure Ayurvedic Formulations | Free Express Delivery Across India on Orders Above ₹499
    </div>

    <!-- HEADER / NAVIGATION -->
    <header class="sticky top-0 z-40 bg-emerald-900/95 backdrop-blur-md text-white border-b border-gold/30 shadow-xl">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 h-20 flex items-center justify-between">
            <!-- Brand Logo & Name -->
            <a href="#" class="flex items-center space-x-3 group">
                <img src="1000134532.png" onerror="this.onerror=null; this.src='https://placehold.co/120x120/08331E/D4AF37?text=Dr.Shelke'" alt="Dr. Shelke Logo" class="h-12 w-12 rounded-full border-2 border-gold/60 p-0.5 object-cover">
                <div>
                    <span class="font-serif text-xl sm:text-2xl font-bold tracking-wider gold-gradient-text block leading-tight">Dr. Shelke</span>
                    <span class="text-[10px] uppercase tracking-widest text-gold/80 block font-sans">Herbalcure Wellness</span>
                </div>
            </a>

            <!-- Desktop Nav -->
            <nav class="hidden md:flex items-center space-x-8 text-sm font-medium">
                <a href="#products" class="hover:text-gold transition">Products</a>
                <a href="#about" class="hover:text-gold transition">About Us</a>
                <a href="#tracking" class="hover:text-gold transition">Track Order</a>
                <a href="#contact" class="hover:text-gold transition">Contact</a>
            </nav>

            <!-- Action Buttons & Cart trigger -->
            <div class="flex items-center space-x-4">
                <button onclick="toggleTrackingModal()" class="hidden sm:flex items-center space-x-1.5 text-xs bg-emerald-800/80 hover:bg-emerald-800 text-gold px-3 py-2 rounded-full border border-gold/40 transition">
                    <i data-lucide="truck" class="w-4 h-4"></i>
                    <span>Track Order</span>
                </button>

                <button onclick="toggleCartDrawer()" class="relative p-2.5 bg-emerald-800/80 rounded-full border border-gold/40 text-gold hover:bg-emerald-700 transition">
                    <i data-lucide="shopping-bag" class="w-5 h-5"></i>
                    <span id="cartBadge" class="absolute -top-1 -right-1 bg-gold text-emerald-900 text-xs font-bold w-5 h-5 rounded-full flex items-center justify-center hidden">0</span>
                </button>
            </div>
        </div>
    </header>

    <!-- HERO SECTION -->
    <section class="relative bg-emerald-900 text-white py-16 lg:py-24 overflow-hidden border-b border-gold/20">
        <div class="absolute inset-0 opacity-10 bg-[radial-gradient(#D4AF37_1px,transparent_1px)] [background-size:16px_16px]"></div>
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 relative z-10 grid md:grid-cols-2 gap-12 items-center">
            <div class="space-y-6 text-center md:text-left">
                <div class="inline-flex items-center space-x-2 px-3 py-1 rounded-full bg-gold/10 border border-gold/40 text-gold text-xs uppercase tracking-widest">
                    <span>✨ Ancient Wisdom • Modern Wellness</span>
                </div>
                <h1 class="font-serif text-3xl sm:text-5xl font-bold leading-tight">
                    Pure Herbal Care Crafted for <span class="gold-gradient-text">Holistic Healing</span>
                </h1>
                <p class="text-gray-300 text-base sm:text-lg max-w-xl font-light leading-relaxed">
                    Formulated with potent botanical extracts, time-tested herbs, and pure Ayurvedic principles to revitalize your hair and body.
                </p>
                <div class="flex flex-col sm:flex-row items-center justify-center md:justify-start gap-4 pt-2">
                    <a href="#products" class="w-full sm:w-auto gold-button px-8 py-3.5 rounded-full font-bold text-center shadow-lg">Shop Natural Range</a>
                    <button onclick="toggleTrackingModal()" class="w-full sm:w-auto border border-gold/60 text-gold hover:bg-gold/10 px-6 py-3.5 rounded-full font-semibold transition text-center">Track Existing Order</button>
                </div>
            </div>

            <!-- Hero Feature Banner -->
            <div class="relative flex justify-center">
                <div class="relative p-2 rounded-2xl bg-gradient-to-tr from-gold/30 via-emerald-700/40 to-gold/20 backdrop-blur-md max-w-sm w-full">
                    <div class="bg-emerald-950 rounded-xl p-6 text-center border border-gold/30 shadow-2xl">
                        <img src="1000125443.png" onerror="this.onerror=null; this.src='https://placehold.co/400x400/08331E/D4AF37?text=He+and+She+Hair+Oil'" alt="He & She Hair Oil" class="h-64 mx-auto object-contain drop-shadow-2xl mb-4 transition hover:scale-105 duration-300">
                        <h3 class="font-serif text-xl font-bold text-gold">He & She Hair Oil</h3>
                        <p class="text-xs text-gray-300 mt-1">Our Bestselling Hair Nourishment Formula</p>
                        <div class="mt-4 flex items-center justify-between pt-3 border-t border-gold/20">
                            <span class="text-2xl font-bold text-white">₹499</span>
                            <button onclick="addToCart('He and She Hair Oil', 499, '1000125443.png')" class="gold-button px-4 py-2 rounded-full text-xs font-bold">Add To Cart</button>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- PRODUCT CATALOG SECTION -->
    <section id="products" class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-16">
        <div class="text-center max-w-2xl mx-auto mb-12">
            <h2 class="font-serif text-3xl sm:text-4xl font-bold text-emerald-900">Ayurvedic Remedies Catalog</h2>
            <div class="h-1 w-20 bg-gold mx-auto my-3 rounded-full"></div>
            <p class="text-gray-600 text-sm">Discover our range of handcrafted, herbal solutions free from harsh chemicals and enriched with pure botanical extracts.</p>
        </div>

        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 xl:grid-cols-4 gap-6" id="productGrid">
            <!-- Product cards rendered dynamically by JS -->
        </div>
    </section>

    <!-- ABOUT SECTION -->
    <section id="about" class="bg-emerald-900 text-white py-16 border-t border-b border-gold/30">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 grid md:grid-cols-2 gap-12 items-center">
            <div class="space-y-4">
                <span class="text-gold uppercase tracking-widest text-xs font-bold">About Dr. Shelke Herbalcure</span>
                <h2 class="font-serif text-3xl font-bold">Traditional Remedies, Delivered To Your Doorstep</h2>
                <p class="text-gray-300 text-sm leading-relaxed">
                    Dr. Shelke Herbalcure is committed to delivering pure Ayurvedic care formulated directly at our Kalyan West botanical facility. Every product is carefully blended using herbal ingredients to ensure maximum potency for hair growth, skin glow, and overall wellness.
                </p>
                <div class="grid grid-cols-2 gap-4 pt-4">
                    <div class="p-3 bg-emerald-800/50 rounded-lg border border-gold/20">
                        <i data-lucide="shield-check" class="w-6 h-6 text-gold mb-1"></i>
                        <h4 class="font-bold text-sm">100% Ayurvedic</h4>
                        <p class="text-xs text-gray-300">Natural & Chemical-free</p>
                    </div>
                    <div class="p-3 bg-emerald-800/50 rounded-lg border border-gold/20">
                        <i data-lucide="truck" class="w-6 h-6 text-gold mb-1"></i>
                        <h4 class="font-bold text-sm">Fast Dispatch</h4>
                        <p class="text-xs text-gray-300">Directly from Kalyan West</p>
                    </div>
                </div>
            </div>
            <div class="flex justify-center">
                <img src="1000134532.png" onerror="this.onerror=null; this.src='https://placehold.co/400x400/08331E/D4AF37?text=Dr.Shelke+Herbalcure'" alt="Dr. Shelke" class="w-64 h-64 rounded-full border-4 border-gold p-2 bg-emerald-950 object-cover shadow-2xl">
            </div>
        </div>
    </section>

    <!-- FOOTER -->
    <footer id="contact" class="bg-emerald-950 text-white pt-12 pb-6 border-t border-gold/30">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 grid grid-cols-1 md:grid-cols-3 gap-8 pb-8 border-b border-white/10">
            <div>
                <div class="flex items-center space-x-3 mb-4">
                    <img src="1000134532.png" onerror="this.onerror=null; this.src='https://placehold.co/100x100/08331E/D4AF37?text=Dr.Shelke'" alt="Dr. Shelke Logo" class="h-10 w-10 rounded-full border border-gold">
                    <span class="font-serif text-xl font-bold text-gold">Dr. Shelke Herbalcure</span>
                </div>
                <p class="text-xs text-gray-400 leading-relaxed">
                    Your trusted destination for natural, botanical hair care and wellness solutions. Formulated with care and traditional expertise.
                </p>
            </div>
            <div>
                <h4 class="font-serif text-gold font-bold text-sm mb-3 uppercase tracking-wider">Contact & Support</h4>
                <ul class="text-xs space-y-2 text-gray-300">
                    <li class="flex items-center space-x-2"><i data-lucide="phone" class="w-4 h-4 text-gold"></i><span>+91 8689958725</span></li>
                    <li class="flex items-center space-x-2"><i data-lucide="map-pin" class="w-4 h-4 text-gold"></i><span>Kalyan West, Maharashtra, India</span></li>
                    <li class="flex items-center space-x-2"><i data-lucide="message-square" class="w-4 h-4 text-gold"></i><span>WhatsApp Support 24/7</span></li>
                </ul>
            </div>
            <div>
                <h4 class="font-serif text-gold font-bold text-sm mb-3 uppercase tracking-wider">Quick Actions</h4>
                <div class="flex flex-col space-y-2 text-xs">
                    <button onclick="toggleTrackingModal()" class="text-left text-gray-300 hover:text-gold transition">► Track Your Order Status</button>
                    <a href="#products" class="text-gray-300 hover:text-gold transition">► View Full Catalog</a>
                </div>
            </div>
        </div>
        <div class="max-w-7xl mx-auto px-4 text-center pt-6 text-xs text-gray-500">
            © 2026 Dr. Shelke Herbalcure. All Rights Reserved. Pure Ayurvedic Formulations.
        </div>
    </footer>

    <!-- CART SIDE DRAWER -->
    <div id="cartDrawer" class="fixed inset-0 z-50 overflow-hidden hidden">
        <div class="absolute inset-0 bg-black/60 backdrop-blur-sm transition-opacity" onclick="toggleCartDrawer()"></div>
        <div class="fixed inset-y-0 right-0 max-w-full flex pl-10">
            <div class="w-screen max-w-md bg-ivory text-emerald-900 shadow-2xl flex flex-col justify-between border-l border-gold/40">
                <div class="p-6 border-b border-gray-200 bg-emerald-900 text-white flex items-center justify-between">
                    <div class="flex items-center space-x-2">
                        <i data-lucide="shopping-cart" class="text-gold"></i>
                        <h3 class="font-serif text-lg font-bold text-gold">Your Order Cart</h3>
                    </div>
                    <button onclick="toggleCartDrawer()" class="text-gray-300 hover:text-white"><i data-lucide="x"></i></button>
                </div>

                <div id="cartItemsList" class="p-6 flex-1 overflow-y-auto space-y-4">
                    <!-- Cart items rendered dynamically -->
                </div>

                <div class="p-6 border-t border-gray-200 bg-white space-y-4 shadow-lg">
                    <div class="flex justify-between text-sm font-semibold">
                        <span>Subtotal</span>
                        <span id="cartSubtotal" class="text-emerald-900 font-bold">₹0</span>
                    </div>
                    <div class="flex justify-between text-xs text-gray-500">
                        <span>Delivery Charges</span>
                        <span id="deliveryCharge" class="text-emerald-700 font-semibold">FREE</span>
                    </div>
                    <div class="flex justify-between text-base font-bold text-emerald-900 pt-2 border-t">
                        <span>Total Payable</span>
                        <span id="cartTotal" class="text-emerald-900 text-xl font-serif">₹0</span>
                    </div>

                    <button id="checkoutBtn" onclick="openCheckoutModal()" class="w-full gold-button py-3.5 rounded-xl font-bold flex items-center justify-center space-x-2 shadow-md">
                        <span>Proceed to Customer Details</span>
                        <i data-lucide="arrow-right" class="w-4 h-4"></i>
                    </button>
                </div>
            </div>
        </div>
    </div>

    <!-- CHECKOUT DETAILS MODAL -->
    <div id="checkoutModal" class="fixed inset-0 z-50 flex items-center justify-center p-4 bg-black/70 backdrop-blur-sm hidden">
        <div class="glass-card rounded-2xl max-w-lg w-full max-h-[90vh] overflow-y-auto p-6 sm:p-8 relative border-2 border-gold shadow-2xl">
            <button onclick="closeCheckoutModal()" class="absolute top-4 right-4 text-gray-500 hover:text-gray-800"><i data-lucide="x"></i></button>
            
            <div class="text-center mb-6">
                <h3 class="font-serif text-2xl font-bold text-emerald-900">Delivery Information</h3>
                <p class="text-xs text-gray-600 mt-1">Please provide details for order dispatch from Kalyan West</p>
            </div>

            <form id="checkoutForm" onsubmit="handleCheckoutSubmit(event)" class="space-y-4">
                <div>
                    <label class="block text-xs font-bold text-emerald-900 uppercase mb-1">Full Name *</label>
                    <input type="text" id="custName" required placeholder="e.g. Rahul Sharma" class="w-full px-4 py-2.5 rounded-lg border border-gray-300 focus:ring-2 focus:ring-gold focus:outline-none text-sm">
                </div>

                <div>
                    <label class="block text-xs font-bold text-emerald-900 uppercase mb-1">Mobile Number (WhatsApp) *</label>
                    <input type="tel" id="custPhone" required pattern="[0-9]{10}" placeholder="10-digit mobile number" class="w-full px-4 py-2.5 rounded-lg border border-gray-300 focus:ring-2 focus:ring-gold focus:outline-none text-sm">
                </div>

                <div>
                    <label class="block text-xs font-bold text-emerald-900 uppercase mb-1">Email Address</label>
                    <input type="email" id="custEmail" placeholder="name@example.com" class="w-full px-4 py-2.5 rounded-lg border border-gray-300 focus:ring-2 focus:ring-gold focus:outline-none text-sm">
                </div>

                <div>
                    <label class="block text-xs font-bold text-emerald-900 uppercase mb-1">Complete Delivery Address *</label>
                    <textarea id="custAddress" required rows="2" placeholder="House/Flat No., Building, Street Area" class="w-full px-4 py-2.5 rounded-lg border border-gray-300 focus:ring-2 focus:ring-gold focus:outline-none text-sm"></textarea>
                </div>

                <div class="grid grid-cols-2 gap-4">
                    <div>
                        <label class="block text-xs font-bold text-emerald-900 uppercase mb-1">City *</label>
                        <input type="text" id="custCity" required placeholder="City" class="w-full px-4 py-2.5 rounded-lg border border-gray-300 focus:ring-2 focus:ring-gold focus:outline-none text-sm">
                    </div>
                    <div>
                        <label class="block text-xs font-bold text-emerald-900 uppercase mb-1">Pincode *</label>
                        <input type="text" id="custPincode" required pattern="[0-9]{6}" placeholder="6-digit Pincode" class="w-full px-4 py-2.5 rounded-lg border border-gray-300 focus:ring-2 focus:ring-gold focus:outline-none text-sm">
                    </div>
                </div>

                <button type="submit" class="w-full gold-button py-3.5 rounded-xl font-bold text-center mt-4 text-sm shadow-md">
                    Proceed to Payment QR
                </button>
            </form>
        </div>
    </div>

    <!-- QR PAYMENT MODAL WITH UTR -->
    <div id="paymentModal" class="fixed inset-0 z-50 flex items-center justify-center p-4 bg-black/80 backdrop-blur-md hidden">
        <div class="glass-dark rounded-2xl max-w-md w-full p-6 text-white text-center border-2 border-gold shadow-2xl relative">
            <button onclick="closePaymentModal()" class="absolute top-4 right-4 text-gold/70 hover:text-gold"><i data-lucide="x"></i></button>

            <span class="text-xs text-gold uppercase tracking-widest font-bold block mb-1">Scan & Pay Directly</span>
            <h3 class="font-serif text-2xl font-bold text-gold">UPI QR Code Payment</h3>
            <p class="text-xs text-gray-300 mt-1 mb-4">Total Amount: <span id="paymentModalAmount" class="text-gold font-bold text-base">₹0</span></p>

            <!-- Integrated Barcode Image -->
            <div class="bg-white p-4 rounded-xl border-2 border-gold max-w-[220px] mx-auto shadow-inner mb-4">
                <img src="1000134074_2.jpg" onerror="this.onerror=null; this.src='1000134074.jpg'" alt="Dr. Shelke Payment QR Barcode" class="w-full h-auto mx-auto object-contain rounded">
            </div>

            <!-- Quick App Buttons -->
            <p class="text-[11px] text-gray-300 mb-2">Scan using any UPI App or tap to open:</p>
            <div class="grid grid-cols-4 gap-2 mb-4 text-xs">
                <a id="gpayBtn" href="#" class="bg-emerald-900 border border-gold/40 p-2 rounded-lg hover:bg-emerald-800 transition flex flex-col items-center justify-center">
                    <span class="font-bold text-gold">GPay</span>
                </a>
                <a id="phonepeBtn" href="#" class="bg-emerald-900 border border-gold/40 p-2 rounded-lg hover:bg-emerald-800 transition flex flex-col items-center justify-center">
                    <span class="font-bold text-gold">PhonePe</span>
                </a>
                <a id="paytmBtn" href="#" class="bg-emerald-900 border border-gold/40 p-2 rounded-lg hover:bg-emerald-800 transition flex flex-col items-center justify-center">
                    <span class="font-bold text-gold">Paytm</span>
                </a>
                <a id="bhimBtn" href="#" class="bg-emerald-900 border border-gold/40 p-2 rounded-lg hover:bg-emerald-800 transition flex flex-col items-center justify-center">
                    <span class="font-bold text-gold">BHIM</span>
                </a>
            </div>

            <!-- UTR Input Form -->
            <div class="bg-emerald-950 p-4 rounded-xl border border-gold/30 text-left space-y-3">
                <label class="block text-xs font-bold text-gold">Enter Payment UTR / Transaction ID (12 Digits) *</label>
                <input type="text" id="utrNumber" maxlength="12" placeholder="e.g. 329847109283" class="w-full px-3 py-2 rounded-lg bg-emerald-900 text-white border border-gold/50 focus:outline-none focus:border-gold text-sm tracking-widest text-center">
                <p class="text-[10px] text-gray-400">After completing payment in your UPI app, paste the 12-digit UTR/Ref No. here.</p>
            </div>

            <button onclick="confirmOrderWhatsApp()" class="w-full mt-4 bg-green-600 hover:bg-green-500 text-white font-bold py-3.5 rounded-xl shadow-lg flex items-center justify-center space-x-2 transition">
                <i data-lucide="message-square" class="w-5 h-5"></i>
                <span>Confirm Order via WhatsApp</span>
            </button>
        </div>
    </div>

    <!-- TRACKING MODAL -->
    <div id="trackingModal" class="fixed inset-0 z-50 flex items-center justify-center p-4 bg-black/75 backdrop-blur-sm hidden">
        <div class="glass-card rounded-2xl max-w-md w-full p-6 relative border-2 border-gold shadow-2xl">
            <button onclick="toggleTrackingModal()" class="absolute top-4 right-4 text-gray-500 hover:text-gray-800"><i data-lucide="x"></i></button>

            <div class="text-center mb-6">
                <i data-lucide="package" class="w-10 h-10 text-emerald-900 mx-auto mb-2"></i>
                <h3 class="font-serif text-2xl font-bold text-emerald-900">Track Your Shipment</h3>
                <p class="text-xs text-gray-600">Enter your Mobile Number or Order ID</p>
            </div>

            <div class="flex space-x-2 mb-6">
                <input type="text" id="trackInput" placeholder="Mobile No. or Order ID" class="flex-1 px-4 py-2.5 rounded-lg border border-gray-300 focus:ring-2 focus:ring-gold focus:outline-none text-sm">
                <button onclick="searchOrder()" class="gold-button px-4 py-2.5 rounded-lg font-bold text-sm">Track</button>
            </div>

            <div id="trackingResult" class="hidden space-y-4 border-t pt-4 border-gold/30">
                <div class="flex justify-between items-center text-xs font-bold text-emerald-900">
                    <span id="trackOrderId">Order #DSH-8492</span>
                    <span class="bg-emerald-100 text-emerald-800 px-2.5 py-1 rounded-full border border-emerald-300">Processing</span>
                </div>

                <!-- Step Tracker -->
                <div class="space-y-3 relative pl-6 border-l-2 border-gold/40 my-4 text-xs">
                    <div class="relative">
                        <div class="absolute -left-[31px] top-0.5 w-4 h-4 rounded-full bg-gold border-2 border-white"></div>
                        <p class="font-bold text-emerald-900">Order Confirmed</p>
                        <p class="text-[10px] text-gray-500">Order received at Kalyan West facility</p>
                    </div>
                    <div class="relative">
                        <div class="absolute -left-[31px] top-0.5 w-4 h-4 rounded-full bg-gold border-2 border-white"></div>
                        <p class="font-bold text-emerald-900">Herbal Packaging & QC</p>
                        <p class="text-[10px] text-gray-500">Sealed & quality checked</p>
                    </div>
                    <div class="relative opacity-50">
                        <div class="absolute -left-[31px] top-0.5 w-4 h-4 rounded-full bg-gray-300 border-2 border-white"></div>
                        <p class="font-bold text-gray-700">Handed to Courier</p>
                        <p class="text-[10px] text-gray-500">In transit from Kalyan West hub</p>
                    </div>
                    <div class="relative opacity-50">
                        <div class="absolute -left-[31px] top-0.5 w-4 h-4 rounded-full bg-gray-300 border-2 border-white"></div>
                        <p class="font-bold text-gray-700">Out for Delivery</p>
                        <p class="text-[10px] text-gray-500">Delivered to customer address</p>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <!-- MAIN JAVASCRIPT LOGIC -->
    <script>
        // Complete Product Catalog with images
        const products = [
            { id: '1', name: 'He and She Hair Oil', price: 499, image: '1000125443.png', desc: 'Nourishing botanical hair oil formula for root strengthening.' },
            { id: '2', name: 'Disha Hair Shampoo', price: 399, image: '1000134516.png', desc: 'Gentle Ayurvedic cleanser for healthy scalp & shine.' },
            { id: '3', name: 'Herbal Hair Serum', price: 240, image: '1000134516.png', desc: 'Smooths frizz & protects hair strands naturally.' },
            { id: '4', name: 'Herbal Hair Colour', price: 299, image: '1000134516.png', desc: 'Ammonia-free natural herb-based hair color blend.' },
            { id: '5', name: 'Herbal Care Soap (Neem)', price: 75, image: '1000134517.png', desc: 'Antibacterial neem soap for deep skin purification.' },
            { id: '6', name: 'Rose Glow Soap', price: 75, image: '1000134500.png', desc: 'Enriched with fresh rose extracts for radiant skin.' },
            { id: '7', name: 'Charcoal Detox Soap', price: 75, image: '1000134500.png', desc: 'Deep-pore cleansing activated charcoal soap.' },
            { id: '8', name: 'Ubtan Glow Soap', price: 75, image: '1000134500.png', desc: 'Traditional herbal ubtan recipe for smooth complexion.' },
            { id: '9', name: 'Vitamin E Softgel Capsules', price: 99, image: '1000134512.png', desc: 'Skin elasticity & hair follicle vitality supplement.' },
            { id: '10', name: 'Multivitamin Tablets', price: 195, image: '1000134518.png', desc: 'Daily botanical daily energy & wellness boost.' }
        ];

        let cart = [];
        let customerInfo = {};

        // Render Products
        function renderProducts() {
            const grid = document.getElementById('productGrid');
            grid.innerHTML = products.map(p => `
                <div class="glass-card rounded-2xl p-4 flex flex-col justify-between hover:shadow-xl transition duration-300 border border-gold/30">
                    <div>
                        <div class="h-48 bg-emerald-900/5 rounded-xl flex items-center justify-center p-3 mb-3 relative overflow-hidden">
                            <img src="${p.image}" onerror="this.onerror=null; this.src='https://placehold.co/300x300/08331E/D4AF37?text=${encodeURIComponent(p.name)}'" alt="${p.name}" class="max-h-full max-w-full object-contain drop-shadow-md hover:scale-105 transition">
                        </div>
                        <h3 class="font-serif font-bold text-emerald-900 text-base leading-snug">${p.name}</h3>
                        <p class="text-xs text-gray-600 mt-1 line-clamp-2">${p.desc}</p>
                    </div>
                    <div class="mt-4 pt-3 border-t border-gray-200 flex items-center justify-between">
                        <span class="text-lg font-bold text-emerald-900 font-serif">₹${p.price}</span>
                        <button onclick="addToCart('${p.name}', ${p.price}, '${p.image}')" class="gold-button px-3.5 py-1.5 rounded-full text-xs font-bold flex items-center space-x-1">
                            <i data-lucide="plus" class="w-3.5 h-3.5"></i>
                            <span>Add</span>
                        </button>
                    </div>
                </div>
            `).join('');
            lucide.createIcons();
        }

        // Cart Actions
        function addToCart(name, price, image) {
            const existing = cart.find(item => item.name === name);
            if (existing) {
                existing.qty += 1;
            } else {
                cart.push({ name, price, image, qty: 1 });
            }
            updateCartUI();
            toggleCartDrawer(true);
        }

        function updateCartQty(name, change) {
            const item = cart.find(i => i.name === name);
            if (item) {
                item.qty += change;
                if (item.qty <= 0) {
                    cart = cart.filter(i => i.name !== name);
                }
            }
            updateCartUI();
        }

        function updateCartUI() {
            const cartItemsList = document.getElementById('cartItemsList');
            const cartBadge = document.getElementById('cartBadge');
            const totalQty = cart.reduce((acc, item) => acc + item.qty, 0);
            
            cartBadge.innerText = totalQty;
            cartBadge.classList.toggle('hidden', totalQty === 0);

            if (cart.length === 0) {
                cartItemsList.innerHTML = `
                    <div class="text-center py-12 text-gray-500">
                        <i data-lucide="shopping-bag" class="w-12 h-12 mx-auto text-gray-300 mb-2"></i>
                        <p class="text-sm">Your cart is currently empty</p>
                    </div>
                `;
            } else {
                cartItemsList.innerHTML = cart.map(item => `
                    <div class="flex items-center justify-between bg-white p-3 rounded-xl border border-gray-100 shadow-sm">
                        <img src="${item.image}" onerror="this.onerror=null; this.src='https://placehold.co/100x100/08331E/D4AF37?text=Product'" class="w-12 h-12 object-contain rounded bg-gray-50 p-1">
                        <div class="flex-1 px-3">
                            <h4 class="text-xs font-bold text-emerald-900">${item.name}</h4>
                            <p class="text-xs text-gray-500">₹${item.price} x ${item.qty}</p>
                        </div>
                        <div class="flex items-center space-x-2 border rounded-lg px-2 py-1 bg-gray-50">
                            <button onclick="updateCartQty('${item.name}', -1)" class="text-xs font-bold px-1 text-gray-600 hover:text-red-600">-</button>
                            <span class="text-xs font-bold text-emerald-900">${item.qty}</span>
                            <button onclick="updateCartQty('${item.name}', 1)" class="text-xs font-bold px-1 text-gray-600 hover:text-green-600">+</button>
                        </div>
                    </div>
                `).join('');
            }

            const subtotal = cart.reduce((sum, item) => sum + (item.price * item.qty), 0);
            document.getElementById('cartSubtotal').innerText = `₹${subtotal}`;
            document.getElementById('cartTotal').innerText = `₹${subtotal}`;
            document.getElementById('paymentModalAmount').innerText = `₹${subtotal}`;

            // Update Deep Link UPI Apps
            const upiString = `upi://pay?pa=8689958725@okbizaxis&pn=DrShelkeHerbalcure&am=${subtotal}&cu=INR`;
            document.getElementById('gpayBtn').href = upiString;
            document.getElementById('phonepeBtn').href = upiString;
            document.getElementById('paytmBtn').href = upiString;
            document.getElementById('bhimBtn').href = upiString;

            lucide.createIcons();
        }

        // Drawer Controls
        function toggleCartDrawer(open) {
            const drawer = document.getElementById('cartDrawer');
            if (open === undefined) {
                drawer.classList.toggle('hidden');
            } else if (open) {
                drawer.classList.remove('hidden');
            } else {
                drawer.classList.add('hidden');
            }
        }

        // Checkout Modal Logic
        function openCheckoutModal() {
            if (cart.length === 0) {
                alert('Please add items to your cart before proceeding.');
                return;
            }
            toggleCartDrawer(false);
            document.getElementById('checkoutModal').classList.remove('hidden');
        }

        function closeCheckoutModal() {
            document.getElementById('checkoutModal').classList.add('hidden');
        }

        function handleCheckoutSubmit(e) {
            e.preventDefault();
            customerInfo = {
                name: document.getElementById('custName').value,
                phone: document.getElementById('custPhone').value,
                email: document.getElementById('custEmail').value || 'N/A',
                address: document.getElementById('custAddress').value,
                city: document.getElementById('custCity').value,
                pincode: document.getElementById('custPincode').value
            };

            closeCheckoutModal();
            document.getElementById('paymentModal').classList.remove('hidden');
        }

        function closePaymentModal() {
            document.getElementById('paymentModal').classList.add('hidden');
        }

        // Confirm Order WhatsApp Integration
        function confirmOrderWhatsApp() {
            const utr = document.getElementById('utrNumber').value.trim();
            if (!utr || utr.length < 10) {
                alert('Please enter a valid 12-digit UTR/Payment Transaction ID after payment.');
                return;
            }

            const total = cart.reduce((sum, item) => sum + (item.price * item.qty), 0);
            const itemsText = cart.map(i => `• ${i.name} (x${i.qty}) - ₹${i.price * i.qty}`).join('%0A');

            const message = `🌿 *NEW ORDER - DR. SHELKE HERBALCURE*%0A%0A` +
                `*Customer Details:*%0A` +
                `👤 Name: ${customerInfo.name}%0A` +
                `📞 Phone: ${customerInfo.phone}%0A` +
                `📍 Address: ${customerInfo.address}, ${customerInfo.city} - ${customerInfo.pincode}%0A%0A` +
                `*Order Items:*%0A${itemsText}%0A%0A` +
                `💳 *Total Amount:* ₹${total}%0A` +
                `🔢 *Payment UTR/Ref No:* ${utr}%0A%0A` +
                `Please confirm and dispatch from Kalyan West facility.`;

            const whatsappUrl = `https://wa.me/918689958725?text=${message}`;
            window.open(whatsappUrl, '_blank');
        }

        // Tracking Modal Logic
        function toggleTrackingModal() {
            document.getElementById('trackingModal').classList.toggle('hidden');
        }

        function searchOrder() {
            const query = document.getElementById('trackInput').value.trim();
            if (!query) {
                alert('Please enter your mobile number or order ID.');
                return;
            }
            document.getElementById('trackingResult').classList.remove('hidden');
            document.getElementById('trackOrderId').innerText = `Order ID / Ref: ${query}`;
        }

        // Initialization
        window.onload = function() {
            renderProducts();
            updateCartUI();
        };
    </script>
</body>
</html>
```