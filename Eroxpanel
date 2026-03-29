<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>EroxPanel</title>
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-black text-white font-sans">

<!-- Navbar -->
<header class="flex justify-between items-center p-5 border-b border-gray-800">
  <h1 class="text-2xl font-bold text-green-400">EroxPanel</h1>
  <a href="#pricing" class="bg-green-500 px-4 py-2 rounded-xl">Buy Now</a>
</header>

<!-- Hero -->
<section class="text-center py-20">
  <h2 class="text-4xl font-bold mb-4">Premium Gaming Panel</h2>
  <p class="text-gray-400 mb-6">Fast, Secure & Reliable Tools</p>
  <a href="#pricing" class="bg-green-500 px-6 py-3 rounded-xl text-lg">Get Started</a>
</section>

<!-- Features -->
<section class="py-16 px-6">
  <h2 class="text-3xl text-center mb-10">Features</h2>
  <div class="grid md:grid-cols-3 gap-6">
    <div class="bg-gray-900 p-6 rounded-2xl">⚡ Fast Performance</div>
    <div class="bg-gray-900 p-6 rounded-2xl">🔒 Secure System</div>
    <div class="bg-gray-900 p-6 rounded-2xl">🎮 Easy to Use</div>
  </div>
</section>

<!-- Pricing -->
<section id="pricing" class="py-16 px-6">
  <h2 class="text-3xl text-center mb-10">Pricing</h2>
  <div class="grid md:grid-cols-3 gap-6 text-center">
    <div class="bg-gray-900 p-6 rounded-2xl">
      <h3 class="text-xl mb-2">15 Day</h3>
      <p class="text-2xl font-bold">Rs 500</p>
      <button onclick="showQRCode('Rs 500')" class="mt-4 bg-green-500 px-4 py-2 rounded-xl">Buy</button>
    </div>
    <div class="bg-gray-900 p-6 rounded-2xl">
      <h3 class="text-xl mb-2">30 Days</h3>
      <p class="text-2xl font-bold">Rs 900</p>
      <button onclick="showQRCode('Rs 900')" class="mt-4 bg-green-500 px-4 py-2 rounded-xl">Buy</button>
    </div>
    <div class="bg-gray-900 p-6 rounded-2xl">
      <h3 class="text-xl mb-2">Permanent</h3>
      <p class="text-2xl font-bold">Rs 1400</p>
      <button onclick="showQRCode('Rs 1400')" class="mt-4 bg-green-500 px-4 py-2 rounded-xl">Buy</button>
    </div>
  </div>
</section>

<!-- Reviews -->
<section class="py-16 px-6 text-center">
  <h2 class="text-3xl mb-10">Reviews</h2>
  <p class="text-gray-400">"Best panel ever!" - User</p>
</section>

<!-- FAQ -->
<section class="py-16 px-6">
  <h2 class="text-3xl text-center mb-10">FAQ</h2>
  <div class="space-y-4">
    <div class="bg-gray-900 p-4 rounded-xl">Q: How to buy?<br>A: Click buy button.</div>
    <div class="bg-gray-900 p-4 rounded-xl">Q: Is it safe?<br>A: Yes.</div>
  </div>
</section>

<!-- Footer -->
<footer class="text-center p-6 border-t border-gray-800">
  <p>© 2026 EroxPanel. All rights reserved.</p>
</footer>

<!-- QR Modal -->
<div id="qrModal" class="fixed inset-0 bg-black bg-opacity-90 flex items-center justify-center hidden z-50">
  <div class="bg-gray-900 p-6 rounded-2xl text-center relative w-80">
    <span class="absolute top-2 right-3 cursor-pointer text-gray-400 text-xl" onclick="closeQRCode()">×</span>
    <h2 class="text-xl font-bold mb-4">Scan to Pay</h2>
    <img id="qrImage" src="qr.png" alt="eSewa QR" class="mx-auto mb-4 w-48 h-48 object-contain">
   <h2 class="text-xl font-bold mb-4">Enter Your Details</h2>

    <!-- Input Form -->
    <div id="clientForm" class="space-y-2">
      <input id="clientName" type="text" placeholder="Your Esewa Name" class="w-full p-2 rounded-xl text-black">
      <input id="clientNumber" type="text" placeholder="Esewa Number" class="w-full p-2 rounded-xl text-black">
      <input id="clientFB" type="text" placeholder="FB Name / ID" class="w-full p-2 rounded-xl text-black">
      <button onclick="showQR()" class="bg-green-500 px-6 py-2 rounded-xl mt-2 w-full">Continue</button>
    </div>
  </div>
</div>

<script>
  function showQRCode(price) {
    document.getElementById('qrModal').classList.remove('hidden');
  }
  function closeQRCode() {
    document.getElementById('qrModal').classList.add('hidden');
  }
  function goHome() {
    closeQRCode();
    window.scrollTo({ top: 0, behavior: 'smooth' });
  }
</script>

</body>
</html>
