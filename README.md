<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mariachi Latino Toronto</title>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f7f3e9;
        }
        .header-bg {
            background-image: url('https://placehold.co/1200x600/a83134/ffffff?text=Mariachi+Latino+Toronto');
            background-size: cover;
            background-position: center;
        }
    </style>
</head>
<body class="antialiased text-gray-800">

    <!-- Navigation Bar -->
    <nav class="bg-white bg-opacity-90 backdrop-blur-sm shadow-lg sticky top-0 z-50 rounded-b-lg mx-2 sm:mx-4 lg:mx-8 mt-2 transition-all duration-300">
        <div class="container mx-auto px-4 py-4 flex flex-col sm:flex-row justify-between items-center">
            <a href="#" class="text-2xl font-bold text-red-600 mb-2 sm:mb-0">Mariachi Latino</a>
            <div class="space-x-4 flex flex-wrap justify-center">
                <a href="#about" class="text-gray-600 hover:text-red-600 transition-colors duration-300 font-semibold rounded-full px-3 py-1">About</a>
                <a href="#services" class="text-gray-600 hover:text-red-600 transition-colors duration-300 font-semibold rounded-full px-3 py-1">Services</a>
                <a href="#contact" class="text-gray-600 hover:text-red-600 transition-colors duration-300 font-semibold rounded-full px-3 py-1">Contact</a>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <header class="header-bg relative text-white py-24 sm:py-32 flex items-center justify-center text-center rounded-lg shadow-xl m-2 sm:m-4 lg:m-8">
        <div class="absolute inset-0 bg-black bg-opacity-50 rounded-lg"></div>
        <div class="relative z-10 p-6 sm:p-10">
            <h1 class="text-4xl sm:text-5xl lg:text-6xl font-extrabold mb-4 sm:mb-6 leading-tight">Authentic Mariachi Music in Toronto</h1>
            <p class="text-lg sm:text-xl font-light mb-8 max-w-2xl mx-auto">Bringing the vibrant spirit of Mexico to your events with passion and tradition. Voted Toronto's most loved mariachi band.</p>
            <a href="#contact" class="bg-white text-red-600 hover:bg-gray-100 transition-colors duration-300 font-bold py-3 px-8 rounded-full shadow-lg transform hover:scale-105">Book a Performance</a>
        </div>
    </header>

    <main class="container mx-auto px-4 sm:px-6 lg:px-8 py-12 sm:py-16">

        <!-- About Section -->
        <section id="about" class="mb-16 sm:mb-24 bg-white p-6 sm:p-10 rounded-xl shadow-lg border border-gray-100">
            <h2 class="text-3xl sm:text-4xl font-bold text-center text-red-600 mb-8 sm:mb-12">About Our Band</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 gap-8 items-center">
                <div class="text-lg text-gray-700 leading-relaxed">
                    <p class="mb-4">Mariachi Latino Toronto is a unique ensemble of talented musicians, a blend of Latin American heritage and Canadian passion. Our journey began with a simple idea: to share the rich, cultural tradition of mariachi music with the world. With musicians hailing from various backgrounds, we are a testament to the power of music to unite diverse cultures and hearts.</p>
                    <p class="mb-4">Our repertoire is a vibrant mix of classic mariachi ballads, traditional folk songs, and modern Latin-infused melodies. Each performance is more than just music; it's a celebration of life, love, and tradition. We pride ourselves on our authentic costumes and instruments, carrying forward the legacy of mariachi with every note we play.</p>
                    <p>We've had the honor of performing at some of Toronto's most prestigious venues, and we are proudly recommended by the Mexican Consulate in Toronto. Our mission is to make every event an unforgettable fiesta, filled with joy, rhythm, and the soul of Mexico.</p>
                </div>
                <div class="flex justify-center items-center">
                    <img src="https://placehold.co/600x400/e9a25b/ffffff?text=Band+Image" alt="Mariachi Latino Band performing" class="rounded-xl shadow-md transform hover:scale-105 transition-transform duration-300">
                </div>
            </div>
        </section>

        <!-- Services Section -->
        <section id="services" class="mb-16 sm:mb-24 bg-red-600 p-6 sm:p-10 rounded-xl shadow-lg text-white">
            <h2 class="text-3xl sm:text-4xl font-bold text-center mb-8 sm:mb-12">Our Services</h2>
            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-8 text-center">
                <div class="bg-white bg-opacity-20 p-6 rounded-lg shadow-md hover:bg-opacity-30 transition-all duration-300">
                    <h3 class="text-2xl font-semibold mb-3">Weddings & Anniversaries</h3>
                    <p class="text-sm font-light leading-relaxed">Add a touch of romance and tradition to your special day with a customized musical performance. We make your moments unforgettable.</p>
                </div>
                <div class="bg-white bg-opacity-20 p-6 rounded-lg shadow-md hover:bg-opacity-30 transition-all duration-300">
                    <h3 class="text-2xl font-semibold mb-3">Festivals & Corporate Events</h3>
                    <p class="text-sm font-light leading-relaxed">Energize your event with the lively and joyful sounds of mariachi. Perfect for captivating crowds and creating a festive atmosphere.</p>
                </div>
                <div class="bg-white bg-opacity-20 p-6 rounded-lg shadow-md hover:bg-opacity-30 transition-all duration-300">
                    <h3 class="text-2xl font-semibold mb-3">Private Parties & Serenades</h3>
                    <p class="text-sm font-light leading-relaxed">From intimate birthday celebrations to heartfelt serenades, we offer personalized packages to suit any occasion.</p>
                </div>
            </div>
        </section>

        <!-- Contact Section -->
        <section id="contact" class="bg-white p-6 sm:p-10 rounded-xl shadow-lg border border-gray-100">
            <h2 class="text-3xl sm:text-4xl font-bold text-center text-red-600 mb-8 sm:mb-12">Contact Us to Book</h2>
            <div class="max-w-xl mx-auto text-center">
                <p class="text-lg text-gray-700 mb-6">Ready to book Mariachi Latino for your next event? We'd love to hear from you. Get in touch to discuss our personalized packages and rates.</p>
                <div class="space-y-4">
                    <a href="tel:+14166506314" class="block w-full bg-red-600 text-white font-bold py-3 px-6 rounded-full shadow-md hover:bg-red-700 transition-colors duration-300 transform hover:scale-105">Call Us: (416) 650-6314</a>
                    <a href="mailto:booking@mariachilatinotoronto.com" class="block w-full bg-gray-200 text-gray-700 font-bold py-3 px-6 rounded-full shadow-md hover:bg-gray-300 transition-colors duration-300 transform hover:scale-105">Email Us: booking@mariachilatinotoronto.com</a>
                </div>
                <p class="mt-8 text-sm text-gray-500">
                    We are Mariachi Latino, Toronto's most recommended mariachi band for over 25 years.
                </p>
            </div>
        </section>

    </main>

    <!-- Footer -->
    <footer class="bg-gray-800 text-white py-8 mt-12 text-center rounded-t-lg mx-2 sm:mx-4 lg:mx-8">
        <div class="container mx-auto px-4">
            <p>&copy; 2024 Mariachi Latino Toronto. All Rights Reserved.</p>
            <div class="flex justify-center space-x-4 mt-4">
                <a href="#" class="text-gray-400 hover:text-white transition-colors duration-300">Facebook</a>
                <a href="#" class="text-gray-400 hover:text-white transition-colors duration-300">Instagram</a>
            </div>
        </div>
    </footer>

</body>
</html>
