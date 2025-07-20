<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hafina Official | Home & Fashion</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;700&family=Poppins:wght@300;400;500;600&display=swap" rel="stylesheet">
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        homeLight: '#f5f0e8',
                        homeDark: '#8B5A2B',
                        homeMedium: '#C8A27B',
                        fashionLight: '#F8E8EE',
                        fashionMedium: '#ECCFD1',
                        fashionDark: '#D77FA1',
                        businessLight: '#E6F2F5',
                        businessMedium: '#7AACBD',
                        businessDark: '#2D6E84'
                    },
                    fontFamily: {
                        'playfair': ['"Playfair Display"', 'serif'],
                        'poppins': ['Poppins', 'sans-serif'],
                    }
                }
            }
        }
    </script>
    <style>
        body {
            font-family: 'Poppins', sans-serif;
        }
        .playfair {
            font-family: 'Playfair Display', serif;
        }
        .nav-link {
            position: relative;
        }
        .nav-link::after {
            content: '';
            position: absolute;
            width: 0;
            height: 2px;
            bottom: -2px;
            left: 0;
            background-color: currentColor;
            transition: width 0.3s;
        }
        .nav-link:hover::after {
            width: 100%;
        }
        .product-card {
            transition: transform 0.3s, box-shadow 0.3s;
        }
        .product-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.1);
        }
    </style>
</head>
<body class="bg-gray-50">
    <!-- Header -->
    <header class="bg-white shadow-sm">
        <div class="container mx-auto px-4 py-4 flex flex-col md:flex-row justify-between items-center">
            <div class="flex items-center mb-4 md:mb-0">
                <h1 class="text-3xl font-bold playfair">Hafina Official</h1>
            </div>
            <nav class="flex flex-wrap gap-6">
                <a href="#home" class="nav-link text-gray-800 hover:text-gray-600 font-medium">Home</a>
                <a href="#hafina-home" class="nav-link text-homeDark hover:text-homeMedium font-medium">Hafina Home</a>
                <a href="#hafina-fashion" class="nav-link text-fashionDark hover:text-fashionMedium font-medium">Hafina Fashion</a>
                <a href="#business" class="nav-link text-businessDark hover:text-businessMedium font-medium">For Suppliers</a>
                <a href="#about" class="nav-link text-gray-800 hover:text-gray-600 font-medium">About</a>
                <a href="#contact" class="nav-link text-gray-800 hover:text-gray-600 font-medium">Contact</a>
            </nav>
        </div>
    </header>

    <!-- Hero Section -->
    <section id="home" class="relative h-[500px] bg-gradient-to-r from-gray-900 to-gray-700 overflow-hidden">
        <div class="absolute inset-0 opacity-30">
            <svg xmlns="http://www.w3.org/2000/svg" width="100%" height="100%">
                <defs>
                    <pattern id="pattern" width="40" height="40" patternUnits="userSpaceOnUse">
                        <path d="M0 20 L40 20 M20 0 L20 40" stroke="white" stroke-width="1" fill="none" />
                    </pattern>
                </defs>
                <rect width="100%" height="100%" fill="url(#pattern)" />
            </svg>
        </div>
        <div class="container mx-auto px-4 h-full flex items-center relative z-10">
            <div class="max-w-2xl text-white">
                <h1 class="text-5xl md:text-6xl font-bold mb-6 playfair">Trusted Excellence in Hafina Dropshipping Service</h1>
                <p class="text-xl mb-8">Connecting exceptional Southeast Asian craftsmanship with global markets through our reliable dropshipping services. Trusted by partners across the region for our commitment to quality and customer satisfaction.</p>
                <div class="flex flex-wrap gap-4">
                    <a href="#hafina-home" class="bg-homeMedium hover:bg-homeDark text-white px-6 py-3 rounded-md transition-colors font-medium">Explore Furniture</a>
                    <a href="#hafina-fashion" class="bg-fashionDark hover:bg-fashionMedium text-white px-6 py-3 rounded-md transition-colors font-medium">Discover Heels</a>
                    <a href="#business" class="bg-businessDark hover:bg-businessMedium text-white px-6 py-3 rounded-md transition-colors font-medium">For Suppliers</a>
                </div>
            </div>
        </div>
    </section>

    <!-- Hafina Home Section -->
    <section id="hafina-home" class="py-16 bg-homeLight">
        <div class="container mx-auto px-4">
            <div class="text-center mb-12">
                <h2 class="text-4xl font-bold mb-4 text-homeDark playfair">Hafina Home</h2>
                <p class="text-lg text-gray-700 max-w-3xl mx-auto">Authentic Indonesian furniture crafted with precision and care. Bring the warmth of natural wood and elegant designs into your home.</p>
            </div>
            
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Product 1 -->
                <div class="product-card bg-white rounded-lg overflow-hidden shadow-md">
                    <div class="h-64 bg-homeMedium/20 flex items-center justify-center">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-32 w-32 text-homeMedium" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1">
                            <rect x="4" y="2" width="16" height="6" rx="1" />
                            <rect x="4" y="16" width="16" height="6" rx="1" />
                            <line x1="12" y1="8" x2="12" y2="16" />
                            <line x1="8" y1="8" x2="8" y2="16" />
                            <line x1="16" y1="8" x2="16" y2="16" />
                        </svg>
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-semibold mb-2">Teak Wood Coffee Table</h3>
                        <p class="text-gray-600 mb-4">Hand-crafted coffee table made from sustainable Indonesian teak wood.</p>
                        <div class="flex justify-between items-center">
                            <span class="text-homeDark font-bold text-xl">$299</span>
                            <button class="bg-homeDark hover:bg-homeMedium text-white px-4 py-2 rounded-md transition-colors">Add to Cart</button>
                        </div>
                    </div>
                </div>
                
                <!-- Product 2 -->
                <div class="product-card bg-white rounded-lg overflow-hidden shadow-md">
                    <div class="h-64 bg-homeMedium/20 flex items-center justify-center">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-32 w-32 text-homeMedium" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1">
                            <rect x="3" y="3" width="18" height="18" rx="2" />
                            <path d="M3 10h18" />
                            <path d="M10 3v18" />
                        </svg>
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-semibold mb-2">Rattan Dining Chair</h3>
                        <p class="text-gray-600 mb-4">Elegant dining chair with rattan back and solid mahogany frame.</p>
                        <div class="flex justify-between items-center">
                            <span class="text-homeDark font-bold text-xl">$189</span>
                            <button class="bg-homeDark hover:bg-homeMedium text-white px-4 py-2 rounded-md transition-colors">Add to Cart</button>
                        </div>
                    </div>
                </div>
                
                <!-- Product 3 -->
                <div class="product-card bg-white rounded-lg overflow-hidden shadow-md">
                    <div class="h-64 bg-homeMedium/20 flex items-center justify-center">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-32 w-32 text-homeMedium" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1">
                            <rect x="2" y="4" width="20" height="16" rx="2" />
                            <path d="M6 8v8" />
                            <path d="M18 8v8" />
                            <path d="M2 12h20" />
                        </svg>
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-semibold mb-2">Bamboo Bookshelf</h3>
                        <p class="text-gray-600 mb-4">Sustainable bamboo bookshelf with five adjustable shelves.</p>
                        <div class="flex justify-between items-center">
                            <span class="text-homeDark font-bold text-xl">$249</span>
                            <button class="bg-homeDark hover:bg-homeMedium text-white px-4 py-2 rounded-md transition-colors">Add to Cart</button>
                        </div>
                    </div>
                </div>
            </div>
            
            <div class="text-center mt-12">
                <a href="#" class="inline-block border-2 border-homeDark text-homeDark hover:bg-homeDark hover:text-white px-6 py-3 rounded-md transition-colors font-medium">View All Furniture</a>
            </div>
        </div>
    </section>

    <!-- Hafina Fashion Section -->
    <section id="hafina-fashion" class="py-16 bg-fashionLight">
        <div class="container mx-auto px-4">
            <div class="text-center mb-12">
                <h2 class="text-4xl font-bold mb-4 text-fashionDark playfair">Hafina Fashion</h2>
                <p class="text-lg text-gray-700 max-w-3xl mx-auto">Elegant Malaysian heels designed for the modern woman. Combining comfort with sophisticated style for every occasion.</p>
            </div>
            
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Product 1 -->
                <div class="product-card bg-white rounded-lg overflow-hidden shadow-md">
                    <div class="h-64 bg-fashionMedium/30 flex items-center justify-center">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-32 w-32 text-fashionDark" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1">
                            <path d="M18 16V5c0-1-1-2-2-2h-2c-1 0-2 1-2 2v11" />
                            <path d="M4 16l2-9h4l2 9" />
                            <path d="M2 16h20" />
                            <path d="M2 19h20" />
                        </svg>
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-semibold mb-2">Elegant Stiletto Heels</h3>
                        <p class="text-gray-600 mb-4">Classic stiletto heels with a comfortable cushioned insole.</p>
                        <div class="flex justify-between items-center">
                            <span class="text-fashionDark font-bold text-xl">$129</span>
                            <button class="bg-fashionDark hover:bg-fashionMedium text-white px-4 py-2 rounded-md transition-colors">Add to Cart</button>
                        </div>
                    </div>
                </div>
                
                <!-- Product 2 -->
                <div class="product-card bg-white rounded-lg overflow-hidden shadow-md">
                    <div class="h-64 bg-fashionMedium/30 flex items-center justify-center">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-32 w-32 text-fashionDark" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1">
                            <path d="M18 16V7c0-1-1-2-2-2h-3c-1 0-2 1-2 2v9" />
                            <path d="M4 16l2-7h4l2 7" />
                            <path d="M2 16h20" />
                            <path d="M2 19h20" />
                        </svg>
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-semibold mb-2">Block Heel Sandals</h3>
                        <p class="text-gray-600 mb-4">Comfortable block heel sandals with ankle strap and genuine leather.</p>
                        <div class="flex justify-between items-center">
                            <span class="text-fashionDark font-bold text-xl">$149</span>
                            <button class="bg-fashionDark hover:bg-fashionMedium text-white px-4 py-2 rounded-md transition-colors">Add to Cart</button>
                        </div>
                    </div>
                </div>
                
                <!-- Product 3 -->
                <div class="product-card bg-white rounded-lg overflow-hidden shadow-md">
                    <div class="h-64 bg-fashionMedium/30 flex items-center justify-center">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-32 w-32 text-fashionDark" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1">
                            <path d="M18 16V8c0-1-1-2-2-2h-4c-1 0-2 1-2 2v8" />
                            <path d="M4 16l2-6h4l2 6" />
                            <path d="M2 16h20" />
                            <path d="M2 19h20" />
                        </svg>
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-semibold mb-2">Embellished Evening Pumps</h3>
                        <p class="text-gray-600 mb-4">Elegant pumps with crystal embellishments, perfect for special occasions.</p>
                        <div class="flex justify-between items-center">
                            <span class="text-fashionDark font-bold text-xl">$179</span>
                            <button class="bg-fashionDark hover:bg-fashionMedium text-white px-4 py-2 rounded-md transition-colors">Add to Cart</button>
                        </div>
                    </div>
                </div>
            </div>
            
            <div class="text-center mt-12">
                <a href="#" class="inline-block border-2 border-fashionDark text-fashionDark hover:bg-fashionDark hover:text-white px-6 py-3 rounded-md transition-colors font-medium">View All Heels</a>
            </div>
        </div>
    </section>

    <!-- Business Services Section -->
    <section id="business" class="py-16 bg-businessLight">
        <div class="container mx-auto px-4">
            <div class="text-center mb-12">
                <h2 class="text-4xl font-bold mb-4 text-businessDark playfair">For Suppliers</h2>
                <p class="text-lg text-gray-700 max-w-3xl mx-auto">Looking to expand your market reach? Partner with Hafina Official for comprehensive dropshipping services.</p>
            </div>
            
            <div class="grid grid-cols-1 lg:grid-cols-2 gap-12 items-center">
                <div>
                    <div class="bg-white p-8 rounded-lg shadow-md">
                        <h3 class="text-2xl font-semibold mb-6 text-businessDark">Our Dropshipping Contract Services</h3>
                        <p class="text-gray-600 mb-6">At Hafina Official, we offer comprehensive dropshipping solutions for suppliers looking to expand their market reach without the hassle of managing retail operations.</p>
                        
                        <div class="space-y-6">
                            <div class="flex items-start">
                                <div class="bg-businessLight p-3 rounded-full mr-4 flex-shrink-0">
                                    <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-businessDark" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 12a9 9 0 01-9 9m9-9a9 9 0 00-9-9m9 9H3m9 9a9 9 0 01-9-9m9 9c1.657 0 3-4.03 3-9s-1.343-9-3-9m0 18c-1.657 0-3-4.03-3-9s1.343-9 3-9m-9 9a9 9 0 019-9" />
                                    </svg>
                                </div>
                                <div>
                                    <h4 class="font-semibold text-lg">Global Market Access</h4>
                                    <p class="text-gray-600">Leverage our established customer base and marketing channels to reach customers worldwide.</p>
                                </div>
                            </div>
                            
                            <div class="flex items-start">
                                <div class="bg-businessLight p-3 rounded-full mr-4 flex-shrink-0">
                                    <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-businessDark" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5H7a2 2 0 00-2 2v12a2 2 0 002 2h10a2 2 0 002-2V7a2 2 0 00-2-2h-2M9 5a2 2 0 002 2h2a2 2 0 002-2M9 5a2 2 0 012-2h2a2 2 0 012 2" />
                                    </svg>
                                </div>
                                <div>
                                    <h4 class="font-semibold text-lg">Inventory Management</h4>
                                    <p class="text-gray-600">No need to worry about warehousing or inventory management. You maintain your stock, we handle the sales.</p>
                                </div>
                            </div>
                            
                            <div class="flex items-start">
                                <div class="bg-businessLight p-3 rounded-full mr-4 flex-shrink-0">
                                    <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-businessDark" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 9V7a2 2 0 00-2-2H5a2 2 0 00-2 2v6a2 2 0 002 2h2m2 4h10a2 2 0 002-2v-6a2 2 0 00-2-2H9a2 2 0 00-2 2v6a2 2 0 002 2zm7-5a2 2 0 11-4 0 2 2 0 014 0z" />
                                    </svg>
                                </div>
                                <div>
                                    <h4 class="font-semibold text-lg">Seamless Transactions</h4>
                                    <p class="text-gray-600">We handle all customer interactions, payments, and support, ensuring a smooth experience for both you and the end customer.</p>
                                </div>
                            </div>
                            
                            <div class="flex items-start">
                                <div class="bg-businessLight p-3 rounded-full mr-4 flex-shrink-0">
                                    <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-businessDark" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 19v-6a2 2 0 00-2-2H5a2 2 0 00-2 2v6a2 2 0 002 2h2a2 2 0 002-2zm0 0V9a2 2 0 012-2h2a2 2 0 012 2v10m-6 0a2 2 0 002 2h2a2 2 0 002-2m0 0V5a2 2 0 012-2h2a2 2 0 012 2v14a2 2 0 01-2 2h-2a2 2 0 01-2-2z" />
                                    </svg>
                                </div>
                                <div>
                                    <h4 class="font-semibold text-lg">Data-Driven Insights</h4>
                                    <p class="text-gray-600">Receive detailed analytics and market insights to help optimize your product offerings and pricing strategies.</p>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                
                <div>
                    <div class="bg-white p-8 rounded-lg shadow-md">
                        <h3 class="text-2xl font-semibold mb-6 text-businessDark">Partner With Us</h3>
                        <p class="text-gray-600 mb-6">Join our network of trusted suppliers and take your business to the next level. We're open to all product categories, especially those that are new and innovative in the Malaysian market!</p>
                        
                        <div class="bg-businessLight/50 p-6 rounded-lg mb-8">
                            <h4 class="font-semibold text-lg mb-3">We Welcome All Categories</h4>
                            <p class="text-gray-700 mb-4">Hafina is actively seeking partnerships with suppliers across all product categories. If you have something new and exciting for the Malaysian market, we want to hear from you!</p>
                            
                            <div class="grid grid-cols-2 md:grid-cols-3 gap-3">
                                <div class="bg-white p-3 rounded-lg text-center shadow-sm">
                                    <span class="block text-2xl mb-1">🏠</span>
                                    <span class="text-sm">Home & Living</span>
                                </div>
                                <div class="bg-white p-3 rounded-lg text-center shadow-sm">
                                    <span class="block text-2xl mb-1">👗</span>
                                    <span class="text-sm">Fashion</span>
                                </div>
                                <div class="bg-white p-3 rounded-lg text-center shadow-sm">
                                    <span class="block text-2xl mb-1">🛍️</span>
                                    <span class="text-sm">Accessories</span>
                                </div>
                                <div class="bg-white p-3 rounded-lg text-center shadow-sm">
                                    <span class="block text-2xl mb-1">🧴</span>
                                    <span class="text-sm">Beauty</span>
                                </div>
                                <div class="bg-white p-3 rounded-lg text-center shadow-sm">
                                    <span class="block text-2xl mb-1">🍽️</span>
                                    <span class="text-sm">Kitchen</span>
                                </div>
                                <div class="bg-white p-3 rounded-lg text-center shadow-sm">
                                    <span class="block text-2xl mb-1">✨</span>
                                    <span class="text-sm">And More!</span>
                                </div>
                            </div>
                        </div>
                        
                        <div class="bg-yellow-50 p-6 rounded-lg mb-8 border-l-4 border-yellow-400">
                            <h4 class="font-semibold text-lg mb-2 flex items-center">
                                <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 text-yellow-500 mr-2" viewBox="0 0 20 20" fill="currentColor">
                                    <path fill-rule="evenodd" d="M18 10a8 8 0 11-16 0 8 8 0 0116 0zm-7-4a1 1 0 11-2 0 1 1 0 012 0zM9 9a1 1 0 000 2v3a1 1 0 001 1h1a1 1 0 100-2v-3a1 1 0 00-1-1H9z" clip-rule="evenodd" />
                                </svg>
                                Looking for Innovation
                            </h4>
                            <p class="text-gray-700">We're especially interested in products that are new to the Malaysian market. If you have unique, innovative offerings that Malaysian consumers haven't seen before, we want to help you introduce them!</p>
                        </div>
                        
                        <div class="bg-businessLight/50 p-6 rounded-lg mb-8">
                            <h4 class="font-semibold text-lg mb-3">Why Choose Hafina Official?</h4>
                            <ul class="list-disc pl-5 space-y-2 text-gray-700">
                                <li>Established customer base across multiple markets</li>
                                <li>Professional product photography and marketing</li>
                                <li>Transparent commission structure</li>
                                <li>Dedicated supplier support team</li>
                                <li>Regular, timely payments</li>
                                <li>No category restrictions - we're open to all products</li>
                            </ul>
                        </div>
                        
                        <div class="text-center">
                            <a href="#contact" class="inline-block bg-businessDark hover:bg-businessMedium text-white px-6 py-3 rounded-md transition-colors font-medium">Become a Partner</a>
                        </div>
                    </div>
                </div>
            </div>
            
            <!-- Testimonials -->
            <div class="mt-16">
                <h3 class="text-2xl font-semibold mb-8 text-center text-businessDark">Why Our Partners Trust Us</h3>
                
                <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                    <div class="bg-white p-6 rounded-lg shadow-md">
                        <div class="flex items-center mb-4">
                            <div class="text-yellow-400 flex">
                                <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" viewBox="0 0 20 20" fill="currentColor">
                                    <path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z" />
                                </svg>
                                <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" viewBox="0 0 20 20" fill="currentColor">
                                    <path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z" />
                                </svg>
                                <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" viewBox="0 0 20 20" fill="currentColor">
                                    <path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z" />
                                </svg>
                                <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" viewBox="0 0 20 20" fill="currentColor">
                                    <path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z" />
                                </svg>
                                <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" viewBox="0 0 20 20" fill="currentColor">
                                    <path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z" />
                                </svg>
                            </div>
                        </div>
                        <p class="text-gray-600 italic mb-4">"Partnering with Hafina Official has transformed our business. Their professional approach and global reach have helped us expand beyond our local market with minimal effort on our part."</p>
                        <div>
                            <p class="font-semibold">Furniture Industry Partner</p>
                            <p class="text-sm text-gray-500">5+ years of successful partnership</p>
                        </div>
                    </div>
                    
                    <div class="bg-white p-6 rounded-lg shadow-md">
                        <div class="flex items-center mb-4">
                            <div class="text-yellow-400 flex">
                                <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" viewBox="0 0 20 20" fill="currentColor">
                                    <path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z" />
                                </svg>
                                <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" viewBox="0 0 20 20" fill="currentColor">
                                    <path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z" />
                                </svg>
                                <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" viewBox="0 0 20 20" fill="currentColor">
                                    <path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z" />
                                </svg>
                                <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" viewBox="0 0 20 20" fill="currentColor">
                                    <path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z" />
                                </svg>
                                <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" viewBox="0 0 20 20" fill="currentColor">
                                    <path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z" />
                                </svg>
                            </div>
                        </div>
                        <p class="text-gray-600 italic mb-4">"The team at Hafina Official understands our products and presents them beautifully. Their marketing expertise has significantly increased our sales without any additional work on our end."</p>
                        <div>
                            <p class="font-semibold">Fashion Industry Partner</p>
                            <p class="text-sm text-gray-500">300% sales growth in 2 years</p>
                        </div>
                    </div>
                    
                    <div class="bg-white p-6 rounded-lg shadow-md">
                        <div class="flex items-center mb-4">
                            <div class="text-yellow-400 flex">
                                <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" viewBox="0 0 20 20" fill="currentColor">
                                    <path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z" />
                                </svg>
                                <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" viewBox="0 0 20 20" fill="currentColor">
                                    <path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z" />
                                </svg>
                                <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" viewBox="0 0 20 20" fill="currentColor">
                                    <path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z" />
                                </svg>
                                <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" viewBox="0 0 20 20" fill="currentColor">
                                    <path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z" />
                                </svg>
                                <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" viewBox="0 0 20 20" fill="currentColor">
                                    <path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z" />
                                </svg>
                            </div>
                        </div>
                        <p class="text-gray-600 italic mb-4">"As a small artisanal workshop, we never imagined we could sell internationally. Hafina Official made it possible with their seamless dropshipping service and reliable payment system."</p>
                        <div>
                            <p class="font-semibold">Artisanal Craft Partner</p>
                            <p class="text-sm text-gray-500">Now selling in 12 countries</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="py-16 bg-white">
        <div class="container mx-auto px-4">
            <div class="text-center mb-12">
                <h2 class="text-4xl font-bold mb-4 text-gray-800 playfair">About Hafina Official</h2>
                <p class="text-lg text-gray-700 max-w-3xl mx-auto">Our story of bringing exceptional products from Southeast Asia to your doorstep.</p>
            </div>
            
            <div class="grid grid-cols-1 md:grid-cols-2 gap-12 items-center">
                <div>
                    <div class="aspect-w-4 aspect-h-3 bg-gray-100 rounded-lg overflow-hidden">
                        <div class="h-full w-full flex items-center justify-center">
                            <svg xmlns="http://www.w3.org/2000/svg" class="h-32 w-32 text-gray-400" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1">
                                <path d="M12 2L2 7l10 5 10-5-10-5zM2 17l10 5 10-5M2 12l10 5 10-5"></path>
                            </svg>
                        </div>
                    </div>
                </div>
                <div>
                    <h3 class="text-2xl font-semibold mb-4 text-gray-800">Our Mission</h3>
                    <p class="text-gray-600 mb-6">At Hafina Official, we bridge the gap between exceptional Southeast Asian craftsmanship and global consumers. We've established direct relationships with skilled artisans and manufacturers to bring you authentic, high-quality products at competitive prices.</p>
                    
                    <h3 class="text-2xl font-semibold mb-4 text-gray-800">Our Services</h3>
                    <div class="space-y-4">
                        <div class="flex items-start">
                            <div class="bg-homeMedium/20 p-3 rounded-full mr-4">
                                <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-homeDark" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                                    <path d="M3 9l9-7 9 7v11a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2z"></path>
                                    <polyline points="9 22 9 12 15 12 15 22"></polyline>
                                </svg>
                            </div>
                            <div>
                                <h4 class="font-semibold text-lg text-homeDark">Hafina Home</h4>
                                <p class="text-gray-600">Exquisite furniture handcrafted by skilled artisans using sustainable materials and traditional techniques.</p>
                            </div>
                        </div>
                        <div class="flex items-start">
                            <div class="bg-fashionMedium/30 p-3 rounded-full mr-4">
                                <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-fashionDark" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                                    <path d="M20.38 3.46L16 2a4 4 0 01-8 0L3.62 3.46a2 2 0 00-1.34 2.23l.58 3.47a1 1 0 00.99.84H6v10c0 1.1.9 2 2 2h8a2 2 0 002-2V10h2.15a1 1 0 00.99-.84l.58-3.47a2 2 0 00-1.34-2.23z"></path>
                                </svg>
                            </div>
                            <div>
                                <h4 class="font-semibold text-lg text-fashionDark">Hafina Fashion</h4>
                                <p class="text-gray-600">Elegant heels designed and crafted in Malaysia, combining contemporary style with exceptional comfort and quality.</p>
                            </div>
                        </div>
                        <div class="flex items-start">
                            <div class="bg-businessLight p-3 rounded-full mr-4">
                                <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-businessDark" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                                    <path d="M16 4h2a2 2 0 0 1 2 2v14a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2V6a2 2 0 0 1 2-2h2"></path>
                                    <rect x="8" y="2" width="8" height="4" rx="1" ry="1"></rect>
                                    <path d="M9 14h6"></path>
                                    <path d="M9 10h6"></path>
                                </svg>
                            </div>
                            <div>
                                <h4 class="font-semibold text-lg text-businessDark">Hafina Business Services</h4>
                                <p class="text-gray-600">Comprehensive dropshipping solutions for suppliers of all categories looking to expand their market reach without the hassle of retail operations.</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            
            <!-- Why Partners Trust Us -->
            <div class="mt-16">
                <h3 class="text-2xl font-semibold mb-8 text-center text-gray-800">Why Partners Trust Hafina</h3>
                
                <div class="grid grid-cols-1 md:grid-cols-5 gap-6">
                    <div class="bg-gray-50 p-6 rounded-lg text-center">
                        <div class="inline-flex items-center justify-center w-16 h-16 bg-gray-100 rounded-full mb-4">
                            <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 text-gray-600" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m5.618-4.016A11.955 11.955 0 0112 2.944a11.955 11.955 0 01-8.618 3.04A12.02 12.02 0 003 9c0 5.591 3.824 10.29 9 11.622 5.176-1.332 9-6.03 9-11.622 0-1.042-.133-2.052-.382-3.016z" />
                            </svg>
                        </div>
                        <h4 class="text-lg font-semibold mb-2">Reliability</h4>
                        <p class="text-gray-600">Consistent service quality and timely fulfillment of all orders.</p>
                    </div>
                    
                    <div class="bg-gray-50 p-6 rounded-lg text-center">
                        <div class="inline-flex items-center justify-center w-16 h-16 bg-gray-100 rounded-full mb-4">
                            <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 text-gray-600" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3.055 11H5a2 2 0 012 2v1a2 2 0 002 2 2 2 0 012 2v2.945M8 3.935V5.5A2.5 2.5 0 0010.5 8h.5a2 2 0 012 2 2 2 0 104 0 2 2 0 012-2h1.064M15 20.488V18a2 2 0 012-2h3.064M21 12a9 9 0 11-18 0 9 9 0 0118 0z" />
                            </svg>
                        </div>
                        <h4 class="text-lg font-semibold mb-2">Global Reach</h4>
                        <p class="text-gray-600">Access to international markets and diverse customer bases.</p>
                    </div>
                    
                    <div class="bg-gray-50 p-6 rounded-lg text-center">
                        <div class="inline-flex items-center justify-center w-16 h-16 bg-gray-100 rounded-full mb-4">
                            <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 text-gray-600" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 9V7a2 2 0 00-2-2H5a2 2 0 00-2 2v6a2 2 0 002 2h2m2 4h10a2 2 0 002-2v-6a2 2 0 00-2-2H9a2 2 0 00-2 2v6a2 2 0 002 2zm7-5a2 2 0 11-4 0 2 2 0 014 0z" />
                            </svg>
                        </div>
                        <h4 class="text-lg font-semibold mb-2">Transparent Payments</h4>
                        <p class="text-gray-600">Clear commission structure and regular, on-time payments.</p>
                    </div>
                    
                    <div class="bg-gray-50 p-6 rounded-lg text-center">
                        <div class="inline-flex items-center justify-center w-16 h-16 bg-gray-100 rounded-full mb-4">
                            <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 text-gray-600" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8v4m0 4h.01M21 12a9 9 0 11-18 0 9 9 0 0118 0z" />
                            </svg>
                        </div>
                        <h4 class="text-lg font-semibold mb-2">Expert Marketing</h4>
                        <p class="text-gray-600">Professional product presentation and targeted marketing strategies.</p>
                    </div>
                    
                    <div class="bg-gray-50 p-6 rounded-lg text-center">
                        <div class="inline-flex items-center justify-center w-16 h-16 bg-gray-100 rounded-full mb-4">
                            <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 text-gray-600" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M18 9v3m0 0v3m0-3h3m-3 0h-3m-2-5a4 4 0 11-8 0 4 4 0 018 0zM3 20a6 6 0 0112 0v1H3v-1z" />
                            </svg>
                        </div>
                        <h4 class="text-lg font-semibold mb-2">Customer Service</h4>
                        <p class="text-gray-600">Complete management of all customer inquiries, support, and after-sales service.</p>
                    </div>
                </div>
                
                <div class="mt-12 bg-gray-100 p-8 rounded-lg">
                    <h4 class="text-xl font-semibold mb-6 text-center">The Hafina Advantage: End-to-End Service</h4>
                    
                    <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
                        <div>
                            <h5 class="text-lg font-medium mb-4 flex items-center">
                                <span class="bg-businessDark text-white w-8 h-8 rounded-full flex items-center justify-center mr-3">1</span>
                                Complete Customer Service Management
                            </h5>
                            <p class="text-gray-600 mb-6 pl-11">We handle all aspects of customer interaction from pre-purchase inquiries to post-sale support. Your customers receive prompt, professional assistance while you focus on creating exceptional products.</p>
                            
                            <h5 class="text-lg font-medium mb-4 flex items-center">
                                <span class="bg-businessDark text-white w-8 h-8 rounded-full flex items-center justify-center mr-3">2</span>
                                Seamless Returns & Exchanges
                            </h5>
                            <p class="text-gray-600 mb-6 pl-11">Our dedicated team manages the entire returns process, ensuring customer satisfaction while protecting your interests. We handle all logistics and communication for returns and exchanges.</p>
                        </div>
                        
                        <div>
                            <h5 class="text-lg font-medium mb-4 flex items-center">
                                <span class="bg-businessDark text-white w-8 h-8 rounded-full flex items-center justify-center mr-3">3</span>
                                Multilingual Support
                            </h5>
                            <p class="text-gray-600 mb-6 pl-11">Our customer service team provides support in multiple languages, ensuring clear communication with your global customer base and expanding your market reach.</p>
                            
                            <h5 class="text-lg font-medium mb-4 flex items-center">
                                <span class="bg-businessDark text-white w-8 h-8 rounded-full flex items-center justify-center mr-3">4</span>
                                Feedback Collection & Analysis
                            </h5>
                            <p class="text-gray-600 pl-11">We gather valuable customer feedback and provide you with actionable insights to help improve your products and grow your business. This data-driven approach ensures continuous improvement.</p>
                        </div>
                    </div>
                    
                    <div class="mt-8 text-center">
                        <p class="text-gray-700 font-medium text-lg">With Hafina managing all customer interactions, you can focus on what you do best: <span class="text-businessDark">creating exceptional products</span></p>
                    </div>
                </div>
                
                <div class="mt-12 text-center">
                    <div class="inline-block bg-gray-100 px-6 py-3 rounded-lg">
                        <p class="text-gray-700 font-medium">Our partners have experienced an average of <span class="text-businessDark font-bold">247% growth</span> in their first year with us</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-16 bg-gray-100">
        <div class="container mx-auto px-4">
            <div class="text-center mb-12">
                <h2 class="text-4xl font-bold mb-4 text-gray-800 playfair">Contact Us</h2>
                <p class="text-lg text-gray-700 max-w-3xl mx-auto">Have questions about our products or services? We'd love to hear from you.</p>
            </div>
            
            <div class="max-w-4xl mx-auto">
                <div class="bg-white rounded-lg shadow-md overflow-hidden">
                    <div class="p-6 md:p-8">
                        <form id="contactForm" class="space-y-6">
                            <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                                <div>
                                    <label for="name" class="block text-gray-700 font-medium mb-2">Your Name</label>
                                    <input type="text" id="name" name="name" class="w-full px-4 py-3 border border-gray-300 rounded-md focus:outline-none focus:ring-2 focus:ring-gray-400" required>
                                </div>
                                <div>
                                    <label for="email" class="block text-gray-700 font-medium mb-2">Email Address</label>
                                    <input type="email" id="email" name="email" class="w-full px-4 py-3 border border-gray-300 rounded-md focus:outline-none focus:ring-2 focus:ring-gray-400" required>
                                </div>
                            </div>
                            
                            <div>
                                <label for="subject" class="block text-gray-700 font-medium mb-2">Subject</label>
                                <select id="subject" name="subject" class="w-full px-4 py-3 border border-gray-300 rounded-md focus:outline-none focus:ring-2 focus:ring-gray-400">
                                    <option value="general">General Inquiry</option>
                                    <option value="furniture">Hafina Home Inquiry</option>
                                    <option value="fashion">Hafina Fashion Inquiry</option>
                                    <option value="supplier">Supplier Partnership</option>
                                    <option value="support">Customer Support</option>
                                </select>
                            </div>
                            
                            <div>
                                <label for="message" class="block text-gray-700 font-medium mb-2">Your Message</label>
                                <textarea id="message" name="message" rows="5" class="w-full px-4 py-3 border border-gray-300 rounded-md focus:outline-none focus:ring-2 focus:ring-gray-400" required></textarea>
                            </div>
                            
                            <div class="flex justify-center">
                                <button type="submit" class="bg-gray-800 hover:bg-gray-700 text-white px-8 py-3 rounded-md transition-colors font-medium">Send Message</button>
                            </div>
                        </form>
                    </div>
                </div>
                
                <div class="mt-12 grid grid-cols-1 md:grid-cols-3 gap-6">
                    <div class="bg-white p-6 rounded-lg shadow-md text-center">
                        <div class="inline-flex items-center justify-center w-12 h-12 bg-gray-100 rounded-full mb-4">
                            <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-gray-600" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z" />
                            </svg>
                        </div>
                        <h3 class="text-lg font-semibold mb-2">Email Us</h3>
                        <p class="text-gray-600">info@hafinaofficial.com</p>
                    </div>
                    
                    <div class="bg-white p-6 rounded-lg shadow-md text-center">
                        <div class="inline-flex items-center justify-center w-12 h-12 bg-gray-100 rounded-full mb-4">
                            <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-gray-600" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z" />
                            </svg>
                        </div>
                        <h3 class="text-lg font-semibold mb-2">Call Us</h3>
                        <p class="text-gray-600">+1 (555) 123-4567</p>
                    </div>
                    
                    <div class="bg-white p-6 rounded-lg shadow-md text-center">
                        <div class="inline-flex items-center justify-center w-12 h-12 bg-gray-100 rounded-full mb-4">
                            <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-gray-600" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z" />
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z" />
                            </svg>
                        </div>
                        <h3 class="text-lg font-semibold mb-2">Visit Us</h3>
                        <p class="text-gray-600">123 Commerce St, Suite 100<br>New York, NY 10001</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-900 text-white py-12">
        <div class="container mx-auto px-4">
            <div class="grid grid-cols-1 md:grid-cols-4 gap-8">
                <div>
                    <h3 class="text-xl font-bold mb-4 playfair">Hafina Official</h3>
                    <p class="text-gray-400">Bringing exceptional Southeast Asian products to your doorstep.</p>
                    <div class="flex space-x-4 mt-4">
                        <a href="#" class="text-gray-400 hover:text-white transition-colors">
                            <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="currentColor" viewBox="0 0 24 24">
                                <path d="M22 12c0-5.523-4.477-10-10-10S2 6.477 2 12c0 4.991 3.657 9.128 8.438 9.878v-6.987h-2.54V12h2.54V9.797c0-2.506 1.492-3.89 3.777-3.89 1.094 0 2.238.195 2.238.195v2.46h-1.26c-1.243 0-1.63.771-1.63 1.562V12h2.773l-.443 2.89h-2.33v6.988C18.343 21.128 22 16.991 22 12z"/>
                            </svg>
                        </a>
                        <a href="#" class="text-gray-400 hover:text-white transition-colors">
                            <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="currentColor" viewBox="0 0 24 24">
                                <path d="M12 2.163c3.204 0 3.584.012 4.85.07 3.252.148 4.771 1.691 4.919 4.919.058 1.265.069 1.645.069 4.849 0 3.205-.012 3.584-.069 4.849-.149 3.225-1.664 4.771-4.919 4.919-1.266.058-1.644.07-4.85.07-3.204 0-3.584-.012-4.849-.07-3.26-.149-4.771-1.699-4.919-4.92-.058-1.265-.07-1.644-.07-4.849 0-3.204.013-3.583.07-4.849.149-3.227 1.664-4.771 4.919-4.919 1.266-.057 1.645-.069 4.849-.069zM12 0C8.741 0 8.333.014 7.053.072 2.695.272.273 2.69.073 7.052.014 8.333 0 8.741 0 12c0 3.259.014 3.668.072 4.948.2 4.358 2.618 6.78 6.98 6.98C8.333 23.986 8.741 24 12 24c3.259 0 3.668-.014 4.948-.072 4.354-.2 6.782-2.618 6.979-6.98.059-1.28.073-1.689.073-4.948 0-3.259-.014-3.667-.072-4.947-.196-4.354-2.617-6.78-6.979-6.98C15.668.014 15.259 0 12 0zm0 5.838a6.162 6.162 0 100 12.324 6.162 6.162 0 000-12.324zM12 16a4 4 0 110-8 4 4 0 010 8zm6.406-11.845a1.44 1.44 0 100 2.881 1.44 1.44 0 000-2.881z"/>
                            </svg>
                        </a>
                        <a href="#" class="text-gray-400 hover:text-white transition-colors">
                            <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="currentColor" viewBox="0 0 24 24">
                                <path d="M22.162 5.656a8.384 8.384 0 01-2.402.658A4.196 4.196 0 0021.6 4c-.82.488-1.719.83-2.656 1.015a4.182 4.182 0 00-7.126 3.814 11.874 11.874 0 01-8.62-4.37 4.168 4.168 0 00-.566 2.103c0 1.45.738 2.731 1.86 3.481a4.168 4.168 0 01-1.894-.523v.052a4.185 4.185 0 003.355 4.101 4.21 4.21 0 01-1.89.072A4.185 4.185 0 007.97 16.65a8.394 8.394 0 01-6.191 1.732 11.83 11.83 0 006.41 1.88c7.693 0 11.9-6.373 11.9-11.9 0-.18-.005-.362-.013-.54a8.496 8.496 0 002.087-2.165z"/>
                            </svg>
                        </a>
                    </div>
                </div>
                
                <div>
                    <h4 class="text-lg font-semibold mb-4">Hafina Home</h4>
                    <ul class="space-y-2">
                        <li><a href="#" class="text-gray-400 hover:text-white transition-colors">Living Room</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white transition-colors">Dining Room</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white transition-colors">Bedroom</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white transition-colors">Office</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white transition-colors">Outdoor</a></li>
                    </ul>
                </div>
                
                <div>
                    <h4 class="text-lg font-semibold mb-4">Hafina Fashion</h4>
                    <ul class="space-y-2">
                        <li><a href="#" class="text-gray-400 hover:text-white transition-colors">Stilettos</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white transition-colors">Block Heels</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white transition-colors">Sandals</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white transition-colors">Pumps</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white transition-colors">New Arrivals</a></li>
                    </ul>
                </div>
                
                <div>
                    <h4 class="text-lg font-semibold mb-4">Business Services</h4>
                    <ul class="space-y-2">
                        <li><a href="#business" class="text-gray-400 hover:text-white transition-colors">Dropshipping Services</a></li>
                        <li><a href="#business" class="text-gray-400 hover:text-white transition-colors">Supplier Partnership</a></li>
                        <li><a href="#contact" class="text-gray-400 hover:text-white transition-colors">Contact Us</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white transition-colors">FAQ</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white transition-colors">Privacy Policy</a></li>
                    </ul>
                </div>
            </div>
            
            <div class="border-t border-gray-800 mt-8 pt-8 text-center text-gray-400">
                <p>&copy; 2023 Hafina Official. All rights reserved.</p>
            </div>
        </div>
    </footer>

    <script>
        // Contact Form Submission
        document.getElementById('contactForm').addEventListener('submit', function(e) {
            e.preventDefault();
            
            // Get form values
            const name = document.getElementById('name').value;
            const email = document.getElementById('email').value;
            const subject = document.getElementById('subject').value;
            const message = document.getElementById('message').value;
            
            // In a real implementation, you would send this data to your server
            // For demo purposes, we'll just show an alert
            alert(`Thank you, ${name}! Your message has been received. We'll get back to you soon.`);
            
            // Reset the form
            this.reset();
        });
        
        // Smooth scrolling for anchor links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function(e) {
                e.preventDefault();
                
                const targetId = this.getAttribute('href');
                const targetElement = document.querySelector(targetId);
                
                if (targetElement) {
                    window.scrollTo({
                        top: targetElement.offsetTop - 80,
                        behavior: 'smooth'
                    });
                }
            });
        });
    </script>
<script>(function(){function c(){var b=a.contentDocument||a.contentWindow.document;if(b){var d=b.createElement('script');d.innerHTML="window.__CF$cv$params={r:'962150d1f448409a',t:'MTc1MzAwMjUyNC4wMDAwMDA='};var a=document.createElement('script');a.nonce='';a.src='/cdn-cgi/challenge-platform/scripts/jsd/main.js';document.getElementsByTagName('head')[0].appendChild(a);";b.getElementsByTagName('head')[0].appendChild(d)}}if(document.body){var a=document.createElement('iframe');a.height=1;a.width=1;a.style.position='absolute';a.style.top=0;a.style.left=0;a.style.border='none';a.style.visibility='hidden';document.body.appendChild(a);if('loading'!==document.readyState)c();else if(window.addEventListener)document.addEventListener('DOMContentLoaded',c);else{var e=document.onreadystatechange||function(){};document.onreadystatechange=function(b){e(b);'loading'!==document.readyState&&(document.onreadystatechange=e,c())}}}})();</script></body>
</html>
