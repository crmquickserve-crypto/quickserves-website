<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Quickserves - After-Sales Service Experts</title>
  <!-- Tailwind CSS CDN -->
  <script src="https://cdn.tailwindcss.com"></script>
  <!-- FontAwesome Icons -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
  <style>
    .bg-brand-blue { background-color: #0b3c5d; }
    .text-brand-blue { color: #0b3c5d; }
    .bg-brand-green { background-color: #3282b8; }
    .border-brand-blue { border-color: #0b3c5d; }
  </style>
</head>
<body class="bg-gray-50 text-gray-800 font-sans">

  <!-- Header / Navigation -->
  <header class="sticky top-0 bg-white shadow-md z-50">
    <div class="max-w-7xl mx-auto px-4 py-4 flex justify-between items-center">
      <div class="flex items-center space-x-2">
        <i class="fa-solid fa-wrench text-2xl text-blue-600"></i>
        <div>
          <h1 class="text-2xl font-bold text-blue-900 tracking-wide">QUICKSERVES</h1>
          <p class="text-xs text-green-600 font-medium tracking-wider">SERVICE MADE QUICK</p>
        </div>
      </div>
      <nav class="hidden md:flex space-x-6 font-medium text-gray-700">
        <a href="#about" class="hover:text-blue-600 transition">About Us</a>
        <a href="#services" class="hover:text-blue-600 transition">Services</a>
        <a href="#categories" class="hover:text-blue-600 transition">Categories</a>
        <a href="#reach" class="hover:text-blue-600 transition">Our Reach</a>
        <a href="#contact" class="hover:text-blue-600 transition">Contact Us</a>
      </nav>
      <a href="tel:8283818084" class="hidden sm:inline-block bg-blue-600 text-white px-5 py-2 rounded-full font-semibold hover:bg-blue-700 transition">
        <i class="fa-solid fa-phone mr-2"></i>Call Now
      </a>
    </div>
  </header>

  <!-- Hero Section -->
  <section class="bg-gradient-to-r from-blue-900 via-blue-800 to-indigo-900 text-white py-20 px-4">
    <div class="max-w-7xl mx-auto text-center md:text-left flex flex-col md:flex-row items-center justify-between">
      <div class="md:w-1/2 space-y-6">
        <span class="bg-green-500 text-white text-xs font-bold px-3 py-1 rounded-full uppercase tracking-wider">An Initiative by Shree Padma Shakti Pvt. Ltd.</span>
        <h2 class="text-4xl md:text-5xl font-extrabold leading-tight">End-To-End Home Appliance Lifecycle Management</h2>
        <p class="text-lg text-blue-100">Your Trusted Service Partner for Repair, Installation, Maintenance & Buyback Services across India.</p>
        <div class="flex flex-wrap justify-center md:justify-start gap-4 pt-4">
          <a href="#contact" class="bg-green-500 hover:bg-green-600 text-white font-bold px-6 py-3 rounded-lg shadow-lg transition">Book a Service</a>
          <a href="https://wa.me/918283818084" target="_blank" class="bg-white text-blue-900 font-bold px-6 py-3 rounded-lg shadow-lg hover:bg-gray-100 transition"><i class="fa-brands fa-whatsapp text-green-500 mr-2"></i>WhatsApp Us</a>
        </div>
      </div>
      <div class="md:w-1/2 mt-10 md:mt-0 grid grid-cols-2 gap-4 text-center">
        <div class="bg-white/10 backdrop-blur-md p-6 rounded-xl border border-white/20">
          <h3 class="text-3xl font-bold text-yellow-400">19,500+</h3>
          <p class="text-sm">Pincodes Covered</p>
        </div>
        <div class="bg-white/10 backdrop-blur-md p-6 rounded-xl border border-white/20">
          <h3 class="text-3xl font-bold text-yellow-400">6,000+</h3>
          <p class="text-sm">Cities Across India</p>
        </div>
        <div class="bg-white/10 backdrop-blur-md p-6 rounded-xl border border-white/20">
          <h3 class="text-3xl font-bold text-yellow-400">5,000+</h3>
          <p class="text-sm">Engineers</p>
        </div>
        <div class="bg-white/10 backdrop-blur-md p-6 rounded-xl border border-white/20">
          <h3 class="text-3xl font-bold text-yellow-400">650+</h3>
          <p class="text-sm">Service Centers</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Key Highlights -->
  <section class="py-8 bg-white border-b">
    <div class="max-w-7xl mx-auto px-4 grid grid-cols-2 md:grid-cols-4 gap-6 text-center">
      <div class="flex flex-col items-center">
        <i class="fa-solid fa-user-gear text-3xl text-blue-600 mb-2"></i>
        <span class="font-bold">Expert Technicians</span>
      </div>
      <div class="flex flex-col items-center">
        <i class="fa-solid fa-shield-check text-3xl text-blue-600 mb-2"></i>
        <span class="font-bold">Genuine Parts</span>
      </div>
      <div class="flex flex-col items-center">
        <i class="fa-solid fa-screwdriver-wrench text-3xl text-blue-600 mb-2"></i>
        <span class="font-bold">Preventive Maintenance</span>
      </div>
      <div class="flex flex-col items-center">
        <i class="fa-solid fa-headset text-3xl text-blue-600 mb-2"></i>
        <span class="font-bold">24/7 Quick Support</span>
      </div>
    </div>
  </section>

  <!-- About Us Section -->
  <section id="about" class="py-16 px-4">
    <div class="max-w-7xl mx-auto">
      <div class="text-center mb-12">
        <h2 class="text-3xl font-bold text-gray-900">About Quickserves</h2>
        <p class="text-gray-600 mt-2">Pan India Network of Last Mile Centers for After-Sales Support</p>
      </div>
      <div class="grid md:grid-cols-3 gap-8">
        <div class="bg-white p-6 rounded-xl shadow-md border-t-4 border-blue-600">
          <i class="fa-solid fa-eye text-3xl text-blue-600 mb-4"></i>
          <h3 class="text-xl font-bold mb-2">Our Vision</h3>
          <p class="text-gray-600">Achieve smiles on customers' faces through our customer-centric services.</p>
        </div>
        <div class="bg-white p-6 rounded-xl shadow-md border-t-4 border-green-500">
          <i class="fa-solid fa-bullseye text-3xl text-green-500 mb-4"></i>
          <h3 class="text-xl font-bold mb-2">Our Aim</h3>
          <p class="text-gray-600">100% Satisfied & Delighted Customers through quality service delivery.</p>
        </div>
        <div class="bg-white p-6 rounded-xl shadow-md border-t-4 border-indigo-600">
          <i class="fa-solid fa-handshake text-3xl text-indigo-600 mb-4"></i>
          <h3 class="text-xl font-bold mb-2">Our Belief</h3>
          <p class="text-gray-600">To be India's leading third-party Brand Service Partner through sustainable & scalable delivery.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Services Offered -->
  <section id="services" class="py-16 bg-gray-100 px-4">
    <div class="max-w-7xl mx-auto">
      <div class="text-center mb-12">
        <h2 class="text-3xl font-bold text-gray-900">Services We Offer</h2>
        <p class="text-gray-600 mt-2">Comprehensive lifecycle solutions powered by proprietary CRM technology</p>
      </div>
      <div class="grid md:grid-cols-4 gap-6">
        <div class="bg-white p-6 rounded-xl shadow-sm hover:shadow-md transition">
          <i class="fa-solid fa-headset text-4xl text-blue-600 mb-4"></i>
          <h3 class="text-xl font-bold mb-2">Call Center & IVR</h3>
          <ul class="text-sm text-gray-600 space-y-1">
            <li>• 24x7 Support</li>
            <li>• VLN / VMN / TFN Services</li>
            <li>• Missed Call & SMS Alerts</li>
          </ul>
        </div>
        <div class="bg-white p-6 rounded-xl shadow-sm hover:shadow-md transition">
          <i class="fa-solid fa-wrench text-4xl text-green-600 mb-4"></i>
          <h3 class="text-xl font-bold mb-2">Repair & Installation</h3>
          <ul class="text-sm text-gray-600 space-y-1">
            <li>• In / Out Warranty Repairs</li>
            <li>• Product Installation</li>
            <li>• Extended Warranty</li>
          </ul>
        </div>
        <div class="bg-white p-6 rounded-xl shadow-sm hover:shadow-md transition">
          <i class="fa-solid fa-laptop-code text-4xl text-indigo-600 mb-4"></i>
          <h3 class="text-xl font-bold mb-2">Proprietary CRM</h3>
          <ul class="text-sm text-gray-600 space-y-1">
            <li>• Web-Based Service CRM</li>
            <li>• Multi-Service UI</li>
            <li>• Engineer & Field Apps</li>
          </ul>
        </div>
        <div class="bg-white p-6 rounded-xl shadow-sm hover:shadow-md transition">
          <i class="fa-solid fa-right-left text-4xl text-yellow-600 mb-4"></i>
          <h3 class="text-xl font-bold mb-2">Buyback & Trade-in</h3>
          <ul class="text-sm text-gray-600 space-y-1">
            <li>• All Electronics Appliances</li>
            <li>• Mobile Devices Buyback</li>
            <li>• Recycle & Safe Disposal</li>
          </ul>
        </div>
      </div>
    </div>
  </section>

  <!-- Categories Serviced -->
  <section id="categories" class="py-16 px-4">
    <div class="max-w-7xl mx-auto text-center">
      <h2 class="text-3xl font-bold text-gray-900 mb-2">Product Categories Serviced</h2>
      <p class="text-gray-600 mb-10">We handle 25+ types of electronic appliances across India</p>
      <div class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-4 lg:grid-cols-6 gap-6">
        <div class="p-4 bg-white rounded-lg shadow border hover:border-blue-500 transition">
          <i class="fa-solid fa-mobile-screen text-3xl text-blue-600 mb-2"></i>
          <p class="font-semibold text-sm">Mobile Phones</p>
        </div>
        <div class="p-4 bg-white rounded-lg shadow border hover:border-blue-500 transition">
          <i class="fa-solid fa-tv text-3xl text-blue-600 mb-2"></i>
          <p class="font-semibold text-sm">Televisions</p>
        </div>
        <div class="p-4 bg-white rounded-lg shadow border hover:border-blue-500 transition">
          <i class="fa-solid fa-wind text-3xl text-blue-600 mb-2"></i>
          <p class="font-semibold text-sm">Air Conditioners</p>
        </div>
        <div class="p-4 bg-white rounded-lg shadow border hover:border-blue-500 transition">
          <i class="fa-solid fa-box-archive text-3xl text-blue-600 mb-2"></i>
          <p class="font-semibold text-sm">Refrigerators</p>
        </div>
        <div class="p-4 bg-white rounded-lg shadow border hover:border-blue-500 transition">
          <i class="fa-solid fa-soap text-3xl text-blue-600 mb-2"></i>
          <p class="font-semibold text-sm">Washing Machines</p>
        </div>
        <div class="p-4 bg-white rounded-lg shadow border hover:border-blue-500 transition">
          <i class="fa-solid fa-temperature-arrow-up text-3xl text-blue-600 mb-2"></i>
          <p class="font-semibold text-sm">Microwave Ovens</p>
        </div>
        <div class="p-4 bg-white rounded-lg shadow border hover:border-blue-500 transition">
          <i class="fa-solid fa-shower text-3xl text-blue-600 mb-2"></i>
          <p class="font-semibold text-sm">Water Heaters</p>
        </div>
        <div class="p-4 bg-white rounded-lg shadow border hover:border-blue-500 transition">
          <i class="fa-solid fa-utensils text-3xl text-blue-600 mb-2"></i>
          <p class="font-semibold text-sm">Dishwashers</p>
        </div>
        <div class="p-4 bg-white rounded-lg shadow border hover:border-blue-500 transition">
          <i class="fa-solid fa-fan text-3xl text-blue-600 mb-2"></i>
          <p class="font-semibold text-sm">Air Coolers</p>
        </div>
        <div class="p-4 bg-white rounded-lg shadow border hover:border-blue-500 transition">
          <i class="fa-solid fa-fire text-3xl text-blue-600 mb-2"></i>
          <p class="font-semibold text-sm">Kitchen Chimneys</p>
        </div>
        <div class="p-4 bg-white rounded-lg shadow border hover:border-blue-500 transition">
          <i class="fa-solid fa-music text-3xl text-blue-600 mb-2"></i>
          <p class="font-semibold text-sm">Home Audio</p>
        </div>
        <div class="p-4 bg-white rounded-lg shadow border hover:border-blue-500 transition">
          <i class="fa-solid fa-headphones text-3xl text-blue-600 mb-2"></i>
          <p class="font-semibold text-sm">Headphones</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Partners Section -->
  <section class="py-12 bg-gray-50 border-t">
    <div class="max-w-7xl mx-auto text-center px-4">
      <p class="text-sm font-bold text-gray-500 uppercase tracking-widest mb-6">Trusted By Leading Brands & Marketplaces</p>
      <div class="flex flex-wrap justify-center items-center gap-8 text-xl font-bold text-gray-400">
        <span>Croma</span>
        <span>Amazon</span>
        <span>Flipkart</span>
        <span>Kent RO</span>
        <span>Hind Power</span>
        <span>Weston</span>
        <span>Hotstar</span>
      </div>
    </div>
  </section>

  <!-- Contact & Location Footer -->
  <footer id="contact" class="bg-blue-950 text-white py-12 px-4">
    <div class="max-w-7xl mx-auto grid md:grid-cols-3 gap-8">
      <div>
        <h3 class="text-2xl font-bold mb-4">QUICKSERVES</h3>
        <p class="text-gray-300 text-sm">An Initiative by <strong class="text-white">Shree Padma Shakti Pvt. Ltd.</strong></p>
        <p class="text-gray-400 text-xs mt-2">Authorized sellers of genuine spare parts and service solutions for top consumer electronic brands across India.</p>
      </div>

      <div>
        <h4 class="text-lg font-semibold mb-4 border-b border-blue-800 pb-2">Corporate Office</h4>
        <p class="text-gray-300 text-sm">
          Plot No. 237, 1st Floor, New Arya Nagar,<br>
          Near Bank of Baroda, Meerut Road,<br>
          Ghaziabad, Uttar Pradesh - 201001
        </p>
      </div>

      <div>
        <h4 class="text-lg font-semibold mb-4 border-b border-blue-800 pb-2">Get in Touch</h4>
        <p class="text-sm text-gray-300 mb-2"><i class="fa-solid fa-user mr-2 text-green-400"></i>Pankaaj Dhiman</p>
        <p class="text-sm text-gray-300 mb-2"><i class="fa-solid fa-phone mr-2 text-green-400"></i><a href="tel:8283818084" class="hover:underline">8283818084</a></p>
        <p class="text-sm text-gray-300 mb-2"><i class="fa-solid fa-envelope mr-2 text-green-400"></i><a href="mailto:sales@quickserveservices.co.in" class="hover:underline">sales@quickserveservices.co.in</a></p>
        <p class="text-sm text-gray-300"><i class="fa-solid fa-globe mr-2 text-green-400"></i><a href="http://www.quickserveservices.co.in" class="hover:underline">www.quickserveservices.co.in</a></p>
      </div>
    </div>

    <div class="max-w-7xl mx-auto border-t border-blue-900 mt-8 pt-6 text-center text-xs text-gray-400">
      &copy; 2026 Quickserves (Shree Padma Shakti Pvt. Ltd.). All Rights Reserved.
    </div>
  </footer>

</body>
</html>
