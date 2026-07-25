<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nama Bisnis Anda - Solusi Peternakan & Pertanian</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://jsdelivr.net"></script>
    <!-- Font Awesome untuk Ikon -->
    <link rel="stylesheet" href="https://cloudflare.com">
</head>
<body class="bg-gray-50 text-gray-800 font-sans">

    <!-- NAVIGASI -->
    <nav class="bg-white shadow-md sticky top-0 z-50">
        <div class="max-w-6xl mx-auto px-4 py-3 flex justify-between items-center">
            <div class="flex items-center space-x-2">
                <i class="fa-solid fa-cow text-green-600 text-2xl"></i>
                <span class="text-xl font-bold text-gray-900 tracking-wide">LOGO_ANDA</span>
            </div>
            <div class="hidden md:flex space-x-6 font-medium">
                <a href="#home" class="text-green-600 hover:text-green-700">Home</a>
                <a href="#tentang" class="hover:text-green-600">Tentang Kami</a>
                <a href="#produk" class="hover:text-green-600">Produk</a>
                <a href="#kontak" class="hover:text-green-600">Kontak</a>
            </div>
            <a href="https://wa.me" target="_blank" class="bg-green-600 text-white px-4 py-2 rounded-full font-semibold hover:bg-green-700 transition">
                <i class="fa-brands fa-whatsapp mr-1"></i> Hubungi Kami
            </a>
        </div>
    </nav>

    <!-- HERO SECTION -->
    <section id="home" class="relative bg-green-900 text-white py-24 px-4 bg-cover bg-center" style="background-image: linear-gradient(rgba(0,0,0,0.6), rgba(0,0,0,0.6)), url('https://unsplash.com');">
        <div class="max-w-4xl mx-auto text-center">
            <h1 class="text-4xl md:text-6xl font-extrabold mb-6 leading-tight">Penyedia Hewan Ternak & Pakan Berkualitas</h1>
            <p class="text-lg md:text-xl mb-8 text-gray-200">Kami menyediakan sapi, kambing, dan pakan ternak terbaik untuk memenuhi kebutuhan usaha dan konsumsi Anda dengan harga kompetitif.</p>
            <div class="flex flex-wrap justify-center gap-4">
                <a href="#produk" class="bg-yellow-500 text-gray-950 font-bold px-8 py-3 rounded-lg shadow-lg hover:bg-yellow-400 transition">Lihat Stok Produk</a>
                <a href="https://wa.me" target="_blank" class="bg-transparent border-2 border-white px-8 py-3 rounded-lg font-bold hover:bg-white hover:text-gray-950 transition">Konsultasi Gratis</a>
            </div>
        </div>
    </section>

    <!-- TENTANG KAMI -->
    <section id="tentang" class="py-16 max-w-6xl mx-auto px-4">
        <div class="grid md:grid-cols-2 gap-12 items-center">
            <div>
                <span class="text-green-600 font-bold tracking-wider uppercase text-sm">Tentang Kami</span>
                <h2 class="text-3xl font-bold text-gray-900 mt-2 mb-6">Berpengalaman dan Terpercaya Dalam Mengelola Peternakan</h2>
                <p class="text-gray-600 mb-4 leading-relaxed">Kami berkomitmen untuk selalu menjaga kesehatan hewan ternak dan kualitas pakan yang kami distribusikan. Setiap proses dipantau oleh tenaga ahli demi kepuasan pelanggan.</p>
                <div class="space-y-3">
                    <div class="flex items-center space-x-3"><i class="fa-solid fa-circle-check text-green-600"></i> <span class="font-medium">Hewan divaksin dan sehat secara berkala</span></div>
                    <div class="flex items-center space-x-3"><i class="fa-solid fa-circle-check text-green-600"></i> <span class="font-medium">Pakan organik bebas bahan kimia berbahaya</span></div>
                    <div class="flex items-center space-x-3"><i class="fa-solid fa-circle-check text-green-600"></i> <span class="font-medium">Pengiriman aman dan cepat langsung ke lokasi Anda</span></div>
                </div>
            </div>
            <div class="grid grid-cols-2 gap-4">
                <img src="https://unsplash.com" alt="Sapi" class="rounded-xl shadow-md w-full object-cover h-48">
                <img src="https://unsplash.com" alt="Kambing" class="rounded-xl shadow-md w-full object-cover h-48 mt-6">
            </div>
        </div>
    </section>

    <!-- KATALOG PRODUK & STOK -->
    <section id="produk" class="bg-gray-100 py-16 px-4">
        <div class="max-w-6xl mx-auto">
            <div class="text-center mb-12">
                <h2 class="text-3xl font-bold text-gray-900">Produk & Stok Terbaru</h2>
                <p class="text-gray-600 mt-2">Daftar hewan ternak dan pakan yang siap dipesan hari ini.</p>
            </div>
            
            <div class="grid md:grid-cols-3 gap-8">
                <!-- Produk 1 -->
                <div class="bg-white rounded-2xl shadow-sm overflow-hidden hover:shadow-md transition">
                    <img src="https://unsplash.com" alt="Sapi Limosin" class="w-full h-48 object-cover">
                    <div class="p-6">
                        <div class="flex justify-between items-center mb-2">
                            <span class="bg-green-100 text-green-800 text-xs font-semibold px-2.5 py-0.5 rounded-full">Ready Stok</span>
                            <span class="text-gray-500 text-sm">Bobot: ~450kg</span>
                        </div>
                        <h3 class="text-xl font-bold text-gray-900 mb-2">Sapi Limosin Super</h3>
                        <p class="text-gray-600 text-sm mb-4">Sapi sehat, sudah divaksin, nafsu makan baik, cocok untuk kebutuhan kurban atau bisnis potong.</p>
                        <a href="https://wa.me?text=Halo,%20saya%20tertarik%20dengan%20Sapi%20Limosin" target="_blank" class="block text-center bg-green-600 text-white font-semibold py-2.5 rounded-lg hover:bg-green-700 transition">
                            <i class="fa-brands fa-whatsapp mr-1"></i> Cek Harga / Beli
                        </a>
                    </div>
                </div>

                <!-- Produk 2 -->
                <div class="bg-white rounded-2xl shadow-sm overflow-hidden hover:shadow-md transition">
                    <img src="https://unsplash.com" alt="Kambing Etawa" class="w-full h-48 object-cover">
                    <div class="p-6">
                        <div class="flex justify-between items-center mb-2">
                            <span class="bg-green-100 text-green-800 text-xs font-semibold px-2.5 py-0.5 rounded-full">Ready Stok</span>
                            <span class="text-gray-500 text-sm">Bobot: ~45kg</span>
                        </div>
                        <h3 class="text-xl font-bold text-gray-900 mb-2">Kambing Etawa Jantan</h3>
                        <p class="text-gray-600 text-sm mb-4">Kambing etawa kualitas unggul, lincah, perawatan intensif dengan pakan bernutrisi tinggi.</p>
                        <a href="https://wa.me?text=Halo,%20saya%20tertarik%20dengan%20Kambing%20Etawa" target="_blank" class="block text-center bg-green-600 text-white font-semibold py-2.5 rounded-lg hover:bg-green-700 transition">
                            <i class="fa-brands fa-whatsapp mr-1"></i> Cek Harga / Beli
                        </a>
                    </div>
                </div>

                <!-- Produk 3 -->
                <div class="bg-white rounded-2xl shadow-sm overflow-hidden hover:shadow-md transition">
                    <img src="https://unsplash.com" alt="Pakan Konsentrat" class="w-full h-48 object-cover">
                    <div class="p-6">
                        <div class="flex justify-between items-center mb-2">
                            <span class="bg-yellow-100 text-yellow-800 text-xs font-semibold px-2.5 py-0.5 rounded-full">Stok Terbatas</span>
                            <span class="text-gray-500 text-sm">Kemasan: 50kg</span>
                        </div>
                        <h3 class="text-xl font-bold text-gray-900 mb-2">Pakan Konsentrat Premium</h3>
                        <p class="text-gray-600 text-sm mb-4">Formula khusus pakan pengemukan instan yang mempercepat pertumbuhan daging hewan ternak.</p>
                        <a href="https://wa.me?text=Halo,%20saya%20tertarik%20dengan%20Pakan%20Konsentrat" target="_blank" class="block text-center bg-green-600 text-white font-semibold py-2.5 rounded-lg hover:bg-green-700 transition">
                            <i class="fa-brands fa-whatsapp mr-1"></i> Cek Harga / Beli
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- KONTAK & MAPS -->
    <section id="kontak" class="py-16 max-w-6xl mx-auto px-4">
        <div class="grid md:grid-cols-2 gap-12">
            <div>
                <h2 class="text-3xl font-bold text-gray-900 mb-6">Hubungi Kantor Kami</h2>
                <p class="text-gray-600 mb-8">Silakan berkunjung langsung ke kandang/kantor kami atau hubungi admin via WhatsApp untuk pemesanan skala besar.</p>
                <div class="space-y-4">
                    <div class="flex items-start space-x-4">
                        <div class="bg-green-100 p-3 rounded-lg text-green-600"><i class="fa-solid fa-location-dot text-lg"></i></div>
                        <div>
                            <h4 class="font-bold text-gray-900">Alamat Utama</h4>
