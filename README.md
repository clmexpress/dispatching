<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="CLM Express LLC - Providing reliable dispatch and transportation services for owner operators and fleet owners. Specializing in Dry Vans, Reefers, Flatbeds, and more. 24/7 Availability.">
    <meta name="keywords" content="trucking, dispatch, logistics, owner operator, fleet owner, transportation, CLM Express, Mississippi trucking">
    <title>CLM Express LLC - Delivery & Transportation</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
    <style>
      @font-face {
        font-family: 'LucideIcons';
        src: url(https://cdn.jsdelivr.net/npm/lucide-static@latest/font/Lucide.ttf) format('truetype');
      }
      .lucide {
        font-family: 'LucideIcons';
        font-size: 1.25rem; /* Adjust size as needed */
        line-height: 1;
        display: inline-block;
      }
      body {
        font-family: 'Inter', sans-serif;
      }
      /* Add a subtle background pattern or texture if desired */
      body {
        /* background-color: #f8fafc; */ /* Light gray background */
      }
      /* Custom styles for better visual hierarchy */
      h1, h2, h3 {
        font-weight: 700; /* Bolder headings */
      }
      .cta-button {
        transition: all 0.3s ease;
      }
      .cta-button:hover {
        transform: translateY(-2px);
        box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.1), 0 2px 4px -1px rgba(0, 0, 0, 0.06);
      }
      .service-card, .requirement-item {
         transition: transform 0.3s ease, box-shadow 0.3s ease;
      }
       .service-card:hover, .requirement-item:hover {
         transform: translateY(-4px);
         box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.1), 0 4px 6px -2px rgba(0, 0, 0, 0.05);
       }
    </style>
</head>
<body class="bg-gray-100 text-gray-800">

    <header class="bg-gray-900 text-white shadow-md sticky top-0 z-50">
        <nav class="container mx-auto px-6 py-4 flex justify-between items-center">
            <div class="flex items-center space-x-3">
                <span class="lucide text-green-500" aria-hidden="true">&#xe8c1;</span> <a href="#" class="text-2xl font-bold hover:text-green-400 transition duration-300">CLM Express LLC</a>
            </div>
            <div class="hidden md:flex items-center space-x-6">
                <a href="#home" class="hover:text-green-400 transition duration-300">Home</a>
                <a href="#services" class="hover:text-green-400 transition duration-300">Services</a>
                <a href="#specialize" class="hover:text-green-400 transition duration-300">We Specialize In</a>
                <a href="#requirements" class="hover:text-green-400 transition duration-300">Requirements</a>
                <a href="#contact" class="bg-green-600 hover:bg-green-700 text-white font-semibold py-2 px-4 rounded-lg transition duration-300 cta-button">Contact Us</a>
            </div>
            <button id="mobile-menu-button" class="md:hidden focus:outline-none">
                <span class="lucide text-white">&#xea3a;</span> </button>
        </nav>
        <div id="mobile-menu" class="hidden md:hidden bg-gray-800">
            <a href="#home" class="block px-6 py-3 text-white hover:bg-gray-700">Home</a>
            <a href="#services" class="block px-6 py-3 text-white hover:bg-gray-700">Services</a>
            <a href="#specialize" class="block px-6 py-3 text-white hover:bg-gray-700">We Specialize In</a>
            <a href="#requirements" class="block px-6 py-3 text-white hover:bg-gray-700">Requirements</a>
            <a href="#contact" class="block px-6 py-3 text-white bg-green-600 hover:bg-green-700 font-semibold">Contact Us</a>
        </div>
    </header>

    <main>
        <section id="home" class="relative bg-gray-800 text-white py-24 md:py-32 px-6 text-center overflow-hidden">
             <img src="https://placehold.co/1920x800/333333/cccccc?text=Truck+on+Road"
                  alt="Background image of a freight truck on the road"
                  class="absolute inset-0 w-full h-full object-cover opacity-30"
                  onerror="this.onerror=null; this.src='https://placehold.co/1920x800/374151/ffffff?text=Image+Not+Found'; this.alt='Placeholder image: Image not found';">
             <div class="relative z-10 container mx-auto">
                <h1 class="text-4xl md:text-6xl font-bold mb-4 leading-tight">Our Eyes On The Load</h1>
                <h2 class="text-4xl md:text-6xl font-bold mb-8 leading-tight text-green-400">Your Eyes On The Road</h2>
                <p class="text-xl md:text-2xl mb-6 max-w-3xl mx-auto">Reliable Delivery & Transportation Services. 24/7 Dispatch Availability.</p>
                <p class="text-lg md:text-xl font-semibold mb-10 bg-green-600 inline-block px-6 py-3 rounded-lg shadow-lg">Now Accepting Owner Operators and Fleet Owners Across The Nation!</p>
                <div>
                    <a href="#contact" class="bg-white text-gray-900 hover:bg-gray-200 font-bold py-3 px-8 rounded-lg text-lg transition duration-300 cta-button mr-4">Get Started</a>
                    <a href="#services" class="bg-transparent border-2 border-white hover:bg-white hover:text-gray-900 font-bold py-3 px-8 rounded-lg text-lg transition duration-300 cta-button">Learn More</a>
                </div>
            </div>
        </section>

        <section id="services" class="py-16 md:py-24 bg-white px-6">
            <div class="container mx-auto text-center">
                <h2 class="text-3xl md:text-4xl font-bold mb-12 text-gray-900">Services We Offer</h2>
                <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-8">
                    <div class="service-card bg-gray-50 p-6 rounded-lg shadow-md text-left hover:shadow-xl">
                        <span class="lucide text-green-600 mb-3 inline-block">&#xea8f;</span> <h3 class="text-xl font-semibold mb-2">Credit Check</h3>
                        <p class="text-gray-600">Thorough credit checks for reliable partnerships.</p>
                    </div>
                    <div class="service-card bg-gray-50 p-6 rounded-lg shadow-md text-left hover:shadow-xl">
                        <span class="lucide text-green-600 mb-3 inline-block">&#xe9d3;</span> <h3 class="text-xl font-semibold mb-2">Invoicing & Paperwork</h3>
                        <p class="text-gray-600">Efficient handling of all necessary documentation.</p>
                    </div>
                    <div class="service-card bg-gray-50 p-6 rounded-lg shadow-md text-left hover:shadow-xl">
                        <span class="lucide text-green-600 mb-3 inline-block">&#xe8ce;</span> <h3 class="text-xl font-semibold mb-2">Dedicated Lanes</h3>
                        <p class="text-gray-600">Consistent routes available for steady work.</p>
                    </div>
                    <div class="service-card bg-gray-50 p-6 rounded-lg shadow-md text-left hover:shadow-xl">
                         <span class="lucide text-green-600 mb-3 inline-block">&#xea9d;</span> <h3 class="text-xl font-semibold mb-2">Top Paying Loads</h3>
                        <p class="text-gray-600">Access to high-revenue freight opportunities.</p>
                    </div>
                    <div class="service-card bg-gray-50 p-6 rounded-lg shadow-md text-left hover:shadow-xl">
                         <span class="lucide text-green-600 mb-3 inline-block">&#xe8c7;</span> <h3 class="text-xl font-semibold mb-2">Rate Negotiation</h3>
                        <p class="text-gray-600">Expert negotiation to maximize your earnings.</p>
                    </div>
                     <div class="service-card bg-gray-50 p-6 rounded-lg shadow-md text-left hover:shadow-xl">
                         <span class="lucide text-green-600 mb-3 inline-block">&#xe8cd;</span> <h3 class="text-xl font-semibold mb-2">Customized Trip Planning</h3>
                        <p class="text-gray-600">Tailored route planning to fit your needs.</p>
                    </div>
                     <div class="service-card bg-gray-50 p-6 rounded-lg shadow-md text-left hover:shadow-xl">
                         <span class="lucide text-green-600 mb-3 inline-block">&#xe91f;</span> <h3 class="text-xl font-semibold mb-2">E-Sign Available</h3>
                        <p class="text-gray-600">Convenient electronic document signing.</p>
                    </div>
                     <div class="service-card bg-gray-50 p-6 rounded-lg shadow-md text-left hover:shadow-xl">
                         <span class="lucide text-green-600 mb-3 inline-block">&#xea7a;</span> <h3 class="text-xl font-semibold mb-2">Shippers List</h3>
                        <p class="text-gray-600">Access to our network of reliable shippers.</p>
                    </div>
                </div>
            </div>
        </section>

        <section id="specialize" class="py-16 md:py-24 bg-gray-200 px-6">
            <div class="container mx-auto text-center">
                <h2 class="text-3xl md:text-4xl font-bold mb-12 text-gray-900">We Specialize In</h2>
                <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-5 gap-6 max-w-4xl mx-auto">
                    <div class="bg-white p-4 rounded-lg shadow-md flex items-center justify-center space-x-2">
                        <span class="lucide text-green-600">&#xe8c1;</span> <span class="font-medium">Dry Vans</span>
                    </div>
                     <div class="bg-white p-4 rounded-lg shadow-md flex items-center justify-center space-x-2">
                        <span class="lucide text-green-600">&#xe8b2;</span> <span class="font-medium">Reefers</span>
                    </div>
                     <div class="bg-white p-4 rounded-lg shadow-md flex items-center justify-center space-x-2">
                        <span class="lucide text-green-600">&#xe973;</span> <span class="font-medium">HotShots</span>
                    </div>
                     <div class="bg-white p-4 rounded-lg shadow-md flex items-center justify-center space-x-2">
                        <span class="lucide text-green-600">&#xe962;</span> <span class="font-medium">Flatbeds</span>
                    </div>
                     <div class="bg-white p-4 rounded-lg shadow-md flex items-center justify-center space-x-2">
                        <span class="lucide text-green-600">&#xe90f;</span> <span class="font-medium">Box Trucks</span>
                    </div>
                     <div class="bg-white p-4 rounded-lg shadow-md flex items-center justify-center space-x-2">
                        <span class="lucide text-green-600">&#xe8c1;</span> <span class="font-medium">Sprinter</span>
                    </div>
                     <div class="bg-white p-4 rounded-lg shadow-md flex items-center justify-center space-x-2">
                        <span class="lucide text-green-600">&#xe968;</span> <span class="font-medium">Power Only</span>
                    </div>
                     <div class="bg-white p-4 rounded-lg shadow-md flex items-center justify-center space-x-2">
                        <span class="lucide text-green-600">&#xe8c1;</span> <span class="font-medium">Cargo Vans</span>
                    </div>
                     <div class="bg-white p-4 rounded-lg shadow-md flex items-center justify-center space-x-2">
                        <span class="lucide text-green-600">&#xe9b1;</span> <span class="font-medium">RV Hauler</span>
                    </div>
                     <div class="bg-white p-4 rounded-lg shadow-md flex items-center justify-center space-x-2">
                        <span class="lucide text-green-600">&#xe912;</span> <span class="font-medium">Car Hauler</span>
                    </div>
                </div>
            </div>
        </section>

        <section id="requirements" class="py-16 md:py-24 bg-white px-6">
            <div class="container mx-auto">
                <h2 class="text-3xl md:text-4xl font-bold mb-12 text-center text-gray-900">Carrier Requirements</h2>
                <div class="max-w-3xl mx-auto grid grid-cols-1 md:grid-cols-2 gap-8">
                    <div class="requirement-item bg-gray-50 p-6 rounded-lg shadow-md flex items-start space-x-4 hover:shadow-lg">
                        <span class="lucide text-green-600 mt-1">&#xe916;</span> <div>
                            <h3 class="text-xl font-semibold mb-1">Active Authority</h3>
                            <p class="text-gray-600">Must possess a valid and active MC authority.</p>
                        </div>
                    </div>
                    <div class="requirement-item bg-gray-50 p-6 rounded-lg shadow-md flex items-start space-x-4 hover:shadow-lg">
                        <span class="lucide text-green-600 mt-1">&#xe916;</span> <div>
                            <h3 class="text-xl font-semibold mb-1">Carrier Packet</h3>
                            <p class="text-gray-600">Completed carrier packet required.</p>
                        </div>
                    </div>
                    <div class="requirement-item bg-gray-50 p-6 rounded-lg shadow-md flex items-start space-x-4 hover:shadow-lg">
                        <span class="lucide text-green-600 mt-1">&#xe916;</span> <div>
                            <h3 class="text-xl font-semibold mb-1">Copy of CDL</h3>
                            <p class="text-gray-600">Valid Commercial Driver's License copy.</p>
                        </div>
                    </div>
                    <div class="requirement-item bg-gray-50 p-6 rounded-lg shadow-md flex items-start space-x-4 hover:shadow-lg">
                        <span class="lucide text-green-600 mt-1">&#xe916;</span> <div>
                            <h3 class="text-xl font-semibold mb-1">W-9 Form</h3>
                            <p class="text-gray-600">Completed and signed W-9 form.</p>
                        </div>
                    </div>
                     <div class="requirement-item bg-gray-50 p-6 rounded-lg shadow-md flex items-start space-x-4 hover:shadow-lg">
                        <span class="lucide text-green-600 mt-1">&#xe916;</span> <div>
                            <h3 class="text-xl font-semibold mb-1">Dispatcher/Carrier Agreement</h3>
                            <p class="text-gray-600">Signed agreement outlining terms.</p>
                        </div>
                    </div>
                     <div class="requirement-item bg-gray-50 p-6 rounded-lg shadow-md flex items-start space-x-4 hover:shadow-lg">
                        <span class="lucide text-green-600 mt-1">&#xe916;</span> <div>
                            <h3 class="text-xl font-semibold mb-1">Proof of Insurance</h3>
                            <p class="text-gray-600">$1,000,000 in Liability & $100,000 in Cargo Insurance.</p>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <section id="contact" class="py-16 md:py-24 bg-gray-900 text-white px-6">
            <div class="container mx-auto text-center">
                <h2 class="text-3xl md:text-4xl font-bold mb-6">Ready to Roll With Us?</h2>
                <p class="text-lg text-gray-300 mb-10 max-w-2xl mx-auto">Contact CLM Express LLC today to learn more about our dispatch services and how we can help you succeed on the road.</p>
                <div class="bg-green-600 inline-block p-6 rounded-lg shadow-lg mb-8">
                     <p class="text-xl font-semibold mb-2">CALL US TODAY:</p>
                     <a href="tel:662-699-0913" class="text-3xl md:text-4xl font-bold hover:text-gray-200 transition duration-300">
                        <span class="lucide align-middle mr-2">&#xea5b;</span> (855) 818-3231 or (662) 699-0913
                    </a>
                </div>

                <div class="mt-12 text-gray-400">
                    <p class="mb-2">
                        <span class="lucide align-middle mr-2">&#xe81a;</span> <a href="https://www.google.com/maps/search/?api=1&query=1231+Sunset+Drive+STE+187+Grenada+MS+38901" target="_blank" rel="noopener noreferrer" class="hover:text-green-400 transition duration-300" Email address: dispatch@clmexpress.net
                        </a>
                    </p>
                    <p>24/7 Dispatch Availability</p>
                </div>
            </div>
        </section>
    </main>

    <footer class="bg-gray-800 text-gray-400 py-8 px-6">
        <div class="container mx-auto text-center">
            <p>&copy; <span id="current-year"></span> CLM Express LLC. All Rights Reserved.</p>
            <p>Website hosted on clmdispatch.net</p>
            </div>
    </footer>

    <script>
        // Mobile menu toggle
        const menuButton = document.getElementById('mobile-menu-button');
        const mobileMenu = document.getElementById('mobile-menu');

        menuButton.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
            // Optional: Change icon on toggle
            const icon = menuButton.querySelector('.lucide');
            if (mobileMenu.classList.contains('hidden')) {
                icon.innerHTML = '&#xea3a;'; // Menu icon
            } else {
                icon.innerHTML = '&#xea0f;'; // X icon
            }
        });

        // Close mobile menu when a link is clicked
        const mobileLinks = mobileMenu.querySelectorAll('a');
        mobileLinks.forEach(link => {
            link.addEventListener('click', () => {
                mobileMenu.classList.add('hidden');
                menuButton.querySelector('.lucide').innerHTML = '&#xea3a;'; // Reset icon
            });
        });


        // Set current year in footer
        document.getElementById('current-year').textContent = new Date().getFullYear();

        // Smooth scrolling for anchor links (optional but nice)
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                const targetId = this.getAttribute('href');
                // Ensure target is not just '#'
                if (targetId.length > 1) {
                    const targetElement = document.querySelector(targetId);
                    if (targetElement) {
                         targetElement.scrollIntoView({
                            behavior: 'smooth'
                        });
                    }
                }
            });
        });
    </script>

</body>
</html>
