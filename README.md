<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>SMD Electronic Security Services</title>

  <!-- SEO -->
  <meta name="description"
        content="SMD Electronic Security Services provides CCTV installation, gate automation, electric fence, alarms, access control and intercom systems in Accra and surrounding areas.">

  <!-- Tailwind CSS -->
  <script src="https://cdn.tailwindcss.com"></script>
</head>

<body class="bg-gray-50 text-gray-900">

<!-- ================= HAMBURGER BUTTON ================= -->
<button onclick="toggleMenu()"
  class="fixed top-6 left-6 z-50 bg-black text-white p-3 rounded-md">
  ☰
</button>

<!-- ================= SIDE MENU ================= -->
<div id="sideMenu"
  class="fixed top-0 left-0 h-full w-72 bg-white shadow-lg transform -translate-x-full transition-transform duration-300 z-40 overflow-y-auto">

  <div class="p-6">
    <button onclick="toggleMenu()" class="mb-6 text-xl font-bold">✕ Close</button>

    <h3 class="text-xl font-bold mb-2">📸 Our Work</h3>
    <p class="mb-4 text-gray-600">
      CCTV, gate automation, electric fence,
      access control & intercom systems.
    </p>

    <img src="images/Screenshot_20260124-082414~2.png"
         class="w-full rounded mb-6"
         alt="Our Work">

    <h3 class="text-xl font-bold mb-2">⭐ Why Choose Us</h3>
    <ul class="list-disc pl-5 mb-6 text-gray-600">
      <li>Professional installers</li>
      <li>Quality equipment</li>
      <li>Affordable pricing</li>
      <li>Trusted support</li>
    </ul>

    <h3 class="text-xl font-bold mb-3">💬 Message Us</h3>

    <!-- SIDE MENU WHATSAPP BUTTON -->
    <a href="https://wa.me/233248622823?text=Hello%20SMD%20Electronic%20Security,%20I%20need%20your%20Services."
       target="_blank"
       rel="noopener noreferrer"
       class="flex items-center justify-center gap-3 bg-green-500 hover:bg-green-600 text-white py-3 rounded-lg font-semibold">

      <svg xmlns="http://www.w3.org/2000/svg"
           viewBox="0 0 32 32"
           class="h-6 w-6 fill-current">
        <path d="M16 .5C7.4.5.5 7.3.5 15.8c0 2.8.7 5.4 2.1 7.8L.5 31.5l8.1-2.1c2.3 1.3 5 2.1 7.9 2.1 8.6 0 15.5-6.8 15.5-15.3C32 7.3 24.6.5 16 .5z"/>
        <path fill="#fff"
              d="M23.5 19.7c-.3-.2-1.8-.9-2.1-1s-.5-.2-.8.2-.9 1-1.1 1.2-.4.2-.7 0-1.3-.5-2.5-1.6c-.9-.8-1.6-1.9-1.8-2.2s0-.5.2-.7.4-.4.5-.6.2-.4.3-.6 0-.4 0-.6-.8-1.9-1.1-2.6-.6-.6-.8-.6h-.7c-.2 0-.6.1-.9.4s-1.1 1.1-1.1 2.7 1.1 3.1 1.2 3.3 2.2 3.5 5.3 4.9c.7.3 1.3.5 1.8.6.8.3 1.6.2 2.2.1.7-.1 2.1-.9 2.4-1.7s.3-1.5.2-1.7-.3-.2-.6-.4z"/>
      </svg>

      <span>Chat on WhatsApp</span>
    </a>
  </div>
</div>

<!-- ================= HEADER ================= -->
<header class="flex items-center justify-between gap-4 p-6 pt-16 sm:pt-6 pl-20">
  <div class="flex items-center gap-3">
    <img src="-image-300d47bd-a602-495b-a9c6-57d9dbf8f8a3
         alt="SMD Electronic Security Services Logo"
         class="h-20 w-auto">
    <h1 class="text-2xl sm:text-3xl font-bold">
      SMD ELECTRONIC SECURITY SERVICES 
    </h1>
  </div>
</header>

<!-- ================= HERO ================= -->
<section class="text-center py-20 bg-blue-800 text-white px-6">
  <h2 class="text-4xl font-bold mb-4">Protect Your Home & Business</h2>
  <p class="mb-6 max-w-xl mx-auto">
    CCTV, alarms, access control, gate automation & electric fence systems.
  </p>
  <a href="#contact"
     class="bg-white text-blue-800 px-6 py-3 rounded font-semibold">
    Request a Quote
  </a>
</section>

<!-- ================= CONTACT ================= -->
<section id="contact" class="py-20 px-6 text-center bg-gray-100">
  <h2 class="text-3xl font-bold mb-4">CONTACT SMD ELECTRONIC SECURITY SERVICES </h2>
  <p>📍 Nsakina – Accra</p>
  <p>🕘 Monday – Saturday | 7:00 AM – 5:00 PM</p>
  <p class="mt-4">📞 +233 256 033 072</p>
  <p>✉️ smdelectronic7@gmail.com</p>
</section>

<footer class="text-center py-6 text-sm text-gray-500">
  © 2021 SMD ELECTRONIC SECURITY SERVICES 
</footer>
