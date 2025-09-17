<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Elevated Imagery | Drone & Camera Photography</title>
    <link rel="icon" type="image/x-icon" href="/static/favicon.ico">
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">
    <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/feather-icons/dist/feather.min.js"></script>
    <script src="https://unpkg.com/feather-icons"></script>
    <script src="https://cdn.jsdelivr.net/npm/vanta@latest/dist/vanta.globe.min.js"></script>
    <style>
 <style>
    html, body {
        height: 100%;
        margin: 0;
        padding: 0;
    }
    #vanta-globe {
        width: 100%;
        height: 100vh; /* Always full screen */
        display: flex;
        align-items: center;
        justify-content: center;
    }
    /* iOS Safari fix */
    @supports (-webkit-touch-callout: none) {
        #vanta-globe {
            height: -webkit-fill-available;
        }
    }
        .hero-bg {
        background: linear-gradient(135deg, rgba(21, 101, 192, 0.9) 0%, rgba(41, 121, 255, 0.8) 100%);
    }
        .gallery-item {
        transition: all 0.3s ease;
    }
    .gallery-item:hover {
        transform: scale(1.03);
        box-shadow: 0 10px 20px rgba(0,0,0,0.2);
    }
        .parallax {
        background-attachment: fixed;
        background-position: center;
        background-repeat: no-repeat;
        background-size: cover;
    }
    </style>

<!-- Navigation -->
<nav class="fixed top-0 left-0 w-full z-50 bg-white shadow-md">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        <div class="flex justify-between h-16">
            <div class="flex items-center">
                <a href="#" class="flex-shrink-0 flex items-center">
                    <i data-feather="camera" class="h-8 w-8 text-white"></i>
                    <span class="ml-2 text-xl font-bold text-blue-600">Elevated Imagery</span>
                </a>
            </div>
            <div class="hidden md:ml-6 md:flex md:items-center md:space-x-8">
                <a href="#" class="text-blue-600 border-b-2 border-blue-600 hover:border-white px-3 py-2 text-sm font-medium">Home</a>
                <a href="#services" class="text-gray-700 border-b-2 border-blue-600 hover:border-white px-3 py-2 text-sm font-medium">Services</a>
                <a href="#portfolio" class="text-gray-700 border-b-2 border-blue-600 hover:border-white px-3 py-2 text-sm font-medium">Portfolio</a>
                <a href="#about" class="text-gray-700 border-b-2 border-blue-600 hover:border-white px-3 py-2 text-sm font-medium">About</a>
                <a href="#contact" class="text-gray-700 border-b-2 border-blue-600 hover:border-white px-3 py-2 text-sm font-medium">Contact</a>
            </div>
            <div class="-mr-2 flex items-center md:hidden">
                <button type="button" class="inline-flex items-center justify-center p-2 rounded-md text-gray-700 hover:text-blue-600 focus:outline-none" aria-controls="mobile-menu" aria-expanded="false">
                    <i data-feather="menu"></i>
                </button>
            <!-- Mobile Menu (hidden by default) -->
<div id="mobile-menu" class="hidden md:hidden bg-white shadow-md">
  <div class="px-2 pt-2 pb-3 space-y-1">
    <a href="#" class="block text-gray-700 hover:bg-blue-100 px-3 py-2 rounded-md text-base font-medium">Home</a>
    <a href="#services" class="block text-gray-700 hover:bg-blue-100 px-3 py-2 rounded-md text-base font-medium">Services</a>
    <a href="#portfolio" class="block text-gray-700 hover:bg-blue-100 px-3 py-2 rounded-md text-base font-medium">Portfolio</a>
    <a href="#about" class="block text-gray-700 hover:bg-blue-100 px-3 py-2 rounded-md text-base font-medium">About</a>
    <a href="#contact" class="block text-gray-700 hover:bg-blue-100 px-3 py-2 rounded-md text-base font-medium">Contact</a>
  </div>
</div>
            </div>
        </div>
    </div>
</nav>

    <!-- Hero Section -->
 <div id="vanta-globe" class="hero-bg min-h-screen flex items-center justify-center pt-16">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-20 text-center">
            <h1 data-aos="fade-up" class="text-4xl md:text-6xl font-bold text-white mb-6">Capture The World From New Perspectives</h1>
            <p data-aos="fade-up" data-aos-delay="100" class="text-xl md:text-2xl text-blue-100 mb-8 max-w-3xl mx-auto">Professional drone and camera photography services for Real Estate, Events, and Personal projects.</p>
            <div data-aos="fade-up" data-aos-delay="200" class="flex flex-col sm:flex-row justify-center gap-4">
                <a href="#contact" class="bg-white text-blue-600 hover:bg-blue-600 hover:text-white px-6 py-3 rounded-lg font-medium shadow-lg transition duration-300">Book a Session</a>
                <a href="#portfolio" class="bg-white border-2 border-white text-blue-600 hover:bg-blue-600 hover:text-white px-6 py-3 rounded-lg font-medium transition duration-300">View Portfolio</a>
            </div>
        </div>
    </div>
    
    <!-- Services Section -->
    <section id="services" class="py-20 bg-gray-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 data-aos="fade-up" class="text-3xl md:text-4xl font-bold text-gray-900 mb-4">Our Services</h2>
                <p data-aos="fade-up" data-aos-delay="100" class="text-lg text-gray-600 max-w-2xl mx-auto">We offer specialized photography services tailored to your unique needs.</p>
            </div>
            
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <!-- Service 1 -->
                <div data-aos="fade-up" data-aos-delay="200" class="bg-white rounded-xl shadow-lg overflow-hidden transition duration-300 hover:shadow-xl">
                    <img src="images/house.example.jpg" alt="House" class="h-48 object-cover object-center w-full">
                    <div class="p-6">
                        <div class="flex items-center mb-4">
                            <div class="bg-blue-100 p-3 rounded-full">
                                <i data-feather="home" class="text-blue-600"></i>
                            </div>
                            <h3 class="ml-3 text-xl font-semibold text-gray-900">Real Estate Photography</h3>
                        </div>
                        <p class="text-gray-600">Showcase properties with stunning aerial and interior photography that highlights every detail.</p>
                    </div>
                </div>
                
                <!-- Service 2 -->
                <div data-aos="fade-up" data-aos-delay="300" class="bg-white rounded-xl shadow-lg overflow-hidden transition duration-300 hover:shadow-xl">
                    <div class="h-48 bg-cover bg-center" style="background-image: url('http://static.photos/event/640x360/2')"></div>
                    <div class="p-6">
                        <div class="flex items-center mb-4">
                            <div class="bg-blue-100 p-3 rounded-full">
                                <i data-feather="calendar" class="text-blue-600"></i>
                            </div>
                            <h3 class="ml-3 text-xl font-semibold text-gray-900">Event Coverage</h3>
                        </div>
                        <p class="text-gray-600">Capture the magic of your special events from unique aerial perspectives and ground-level moments.</p>
                    </div>
                </div>
                
                <!-- Service 3 -->
                <div data-aos="fade-up" data-aos-delay="400" class="bg-white rounded-xl shadow-lg overflow-hidden transition duration-300 hover:shadow-xl">
                    <div class="h-48 bg-cover bg-center" style="background-image: url('http://static.photos/commercial/640x360/3')"></div>
                    <div class="p-6">
                        <div class="flex items-center mb-4">
                            <div class="bg-blue-100 p-3 rounded-full">
                                <i data-feather="briefcase" class="text-blue-600"></i>
                            </div>
                            <h3 class="ml-3 text-xl font-semibold text-gray-900">Commercial Projects</h3>
                        </div>
                        <p class="text-gray-600">Professional photography for businesses, construction sites, and large-scale commercial projects.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Portfolio Section -->
    <section id="portfolio" class="py-20 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 data-aos="fade-up" class="text-3xl md:text-4xl font-bold text-gray-900 mb-4">Our Portfolio</h2>
                <p data-aos="fade-up" data-aos-delay="100" class="text-lg text-gray-600 max-w-2xl mx-auto">A glimpse of our recent work across various photography disciplines.</p>
            </div>
            
            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-6">
                <!-- Portfolio Item 1 -->
                <div data-aos="fade-up" data-aos-delay="200" class="gallery-item rounded-xl overflow-hidden shadow-lg">
                    <img src="images/re.example.jpg" alt="Real Estate" class="w-full h-64 object-cover">
                    <div class="p-4 bg-white">
                        <h3 class="text-lg font-semibold text-gray-900">Real Estate</h3>
                        <p class="text-gray-600 text-sm">Elegant Homes</p>
                    </div>
                </div>
                
                <!-- Portfolio Item 2 -->
                <div data-aos="fade-up" data-aos-delay="250" class="gallery-item rounded-xl overflow-hidden shadow-lg">
                    <img src="http://static.photos/wedding/640x360/5" alt="Wedding" class="w-full h-64 object-cover">
                    <div class="p-4 bg-white">
                        <h3 class="text-lg font-semibold text-gray-900">Wedding Celebration</h3>
                        <p class="text-gray-600 text-sm">Event Photography</p>
                    </div>
                </div>
                
                <!-- Portfolio Item 3 -->
                <div data-aos="fade-up" data-aos-delay="300" class="gallery-item rounded-xl overflow-hidden shadow-lg">
                    <img src="images/portrait.example.jpg" alt="Portrait" class="w-full h-64 object-cover">
                    <div class="p-4 bg-white">
                        <h3 class="text-lg font-semibold text-gray-900">Portraits</h3>
                        <p class="text-gray-600 text-sm">Express Yourself</p>
                    </div>
                </div>
                
                <!-- Portfolio Item 4 -->
                <div data-aos="fade-up" data-aos-delay="350" class="gallery-item rounded-xl overflow-hidden shadow-lg">
                    <img src="images/landscape.example.jpg" alt="Beautiful Scenery" class="w-full h-64 object-cover">
                    <div class="p-4 bg-white">
                        <h3 class="text-lg font-semibold text-gray-900">Mountain Range</h3>
                        <p class="text-gray-600 text-sm">Landscape Photography</p>
                    </div>
                </div>
                
                <!-- Portfolio Item 5 -->
                <div data-aos="fade-up" data-aos-delay="400" class="gallery-item rounded-xl overflow-hidden shadow-lg">
                    <img src="images/350z.boat.jpg" alt="Construction Site" class="w-full h-64 object-cover">
                    <div class="p-4 bg-white">
                        <h3 class="text-lg font-semibold text-gray-900">Automotive Excellence</h3>
                        <p class="text-gray-600 text-sm">On the Road or Track</p>
                    </div>
                </div>
                
                <!-- Portfolio Item 6 -->
                <div data-aos="fade-up" data-aos-delay="450" class="gallery-item rounded-xl overflow-hidden shadow-lg">
                    <img src="images/Kyle.Swinging.jpg" alt="Sports Event" class="w-full h-64 object-cover">
                    <div class="p-4 bg-white">
                        <h3 class="text-lg font-semibold text-gray-900">Action Shots</h3>
                        <p class="text-gray-600 text-sm">Sports Photography</p>
                    </div>
                </div>
            </div>
            
            <div class="text-center mt-12" data-aos="fade-up">
                <a href="#" class="inline-flex items-center px-6 py-3 border border-transparent text-base font-medium rounded-md shadow-sm text-white bg-blue-600 hover:bg-blue-700">
                    View Full Portfolio
                    <i data-feather="arrow-right" class="ml-2"></i>
                </a>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="py-20 bg-gray-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="lg:grid lg:grid-cols-2 lg:gap-16 items-center">
                <div data-aos="fade-right" class="mb-12 lg:mb-0">
                    <img src="http://static.photos/photographer/640x360/10" alt="Photographer" class="rounded-xl shadow-xl w-full">
                </div>
                <div data-aos="fade-left">
                    <h2 class="text-3xl md:text-4xl font-bold text-gray-900 mb-6">About Elevated Imagery</h2>
                    <p class="text-lg text-gray-600 mb-6">Founded in May 2025, Elevated Imagery has been at the forefront of aerial and traditional photography, combining technical expertise with artistic vision to deliver stunning visual content.</p>
                    <p class="text-lg text-gray-600 mb-6">Our team of FAA-certified drone pilots and professional photographers work together to capture images that tell your story from perspectives you've never seen before.</p>
                    <div class="space-y-4">
                        <div class="flex items-start">
                            <div class="flex-shrink-0">
                                <div class="flex items-center justify-center h-8 w-8 rounded-full bg-blue-100">
                                    <i data-feather="award" class="text-blue-600"></i>
                                </div>
                            </div>
                            <div class="ml-3">
                                <p class="text-base font-medium text-gray-900">FAA Certified Pilots</p>
                                <p class="text-base text-gray-600">All our drone operators are fully licensed and insured.</p>
                            </div>
                        </div>
                        <div class="flex items-start">
                            <div class="flex-shrink-0">
                                <div class="flex items-center justify-center h-8 w-8 rounded-full bg-blue-100">
                                    <i data-feather="camera" class="text-blue-600"></i>
                                </div>
                            </div>
                            <div class="ml-3">
                                <p class="text-base font-medium text-gray-900">Professional Equipment</p>
                                <p class="text-base text-gray-600">We use High end drones, DSLR cameras, and Flashes.</p>
                            </div>
                        </div>
                        <div class="flex items-start">
                            <div class="flex-shrink-0">
                                <div class="flex items-center justify-center h-8 w-8 rounded-full bg-blue-100">
                                    <i data-feather="edit" class="text-blue-600"></i>
                                </div>
                            </div>
                            <div class="ml-3">
                                <p class="text-base font-medium text-gray-900">Post-Production</p>
                                <p class="text-base text-gray-600">Every image is professionally edited for maximum impact.</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Testimonials Section -->
    <section class="py-20 bg-blue-600 text-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 data-aos="fade-up" class="text-3xl md:text-4xl font-bold mb-4">Client Testimonials</h2>
                <p data-aos="fade-up" data-aos-delay="100" class="text-xl text-blue-100 max-w-2xl mx-auto">What our clients say about our work</p>
            </div>
            
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <!-- Testimonial 1 -->
                <div data-aos="fade-up" data-aos-delay="200" class="bg-blue-700 rounded-xl p-6 shadow-lg">
                    <div class="flex items-center mb-4">
                        <img class="h-12 w-12 rounded-full" src="http://static.photos/people/200x200/11" alt="Client">
                        <div class="ml-4">
                            <h4 class="text-lg font-semibold">Tony Stark</h4>
                            <p class="text-blue-200">Real Estate Agent</p>
                        </div>
                    </div>
                    <p class="text-blue-100">"The aerial shots Elevated Imagery provided for our luxury listings helped us sell properties 30% faster than before. Their attention to detail is unmatched."</p>
                    <div class="mt-4 flex text-yellow-400">
                        <i data-feather="star" class="fill-current"></i>
                        <i data-feather="star" class="fill-current"></i>
                        <i data-feather="star" class="fill-current"></i>
                        <i data-feather="star" class="fill-current"></i>
                        <i data-feather="star" class="fill-current"></i>
                    </div>
                </div>
                
                <!-- Testimonial 2 -->
                <div data-aos="fade-up" data-aos-delay="300" class="bg-blue-700 rounded-xl p-6 shadow-lg">
                    <div class="flex items-center mb-4">
                        <img class="h-12 w-12 rounded-full" src="http://static.photos/people/200x200/12" alt="Client">
                        <div class="ml-4">
                            <h4 class="text-lg font-semibold">Tyler Selhorst</h4>
                            <p class="text-blue-200">Client</p>
                        </div>
                    </div>
                    <p class="text-blue-100">"Outstanding quality photos, Had a few photos and videos done from a mountain biking trip and they were absolutely stunning!!"</p>
                    <div class="mt-4 flex text-yellow-400">
                        <i data-feather="star" class="fill-current"></i>
                        <i data-feather="star" class="fill-current"></i>
                        <i data-feather="star" class="fill-current"></i>
                        <i data-feather="star" class="fill-current"></i>
                        <i data-feather="star" class="fill-current"></i>
                    </div>
                </div>
                
                <!-- Testimonial 3 -->
                <div data-aos="fade-up" data-aos-delay="400" class="bg-blue-700 rounded-xl p-6 shadow-lg">
                    <div class="flex items-center mb-4">
                        <img class="h-12 w-12 rounded-full" src="http://static.photos/people/200x200/13" alt="Client">
                        <div class="ml-4">
                            <h4 class="text-lg font-semibold">Kyle Rees</h4>
                            <p class="text-blue-200">Sports Photography Client</p>
                        </div>
                    </div>
                    <p class="text-blue-100">"The progress photos from our construction site were invaluable for our investors. Elevated Imagery delivered professional results on tight deadlines."</p>
                    <div class="mt-4 flex text-yellow-400">
                        <i data-feather="star" class="fill-current"></i>
                        <i data-feather="star" class="fill-current"></i>
                        <i data-feather="star" class="fill-current"></i>
                        <i data-feather="star" class="fill-current"></i>
                        <i data-feather="star" class="fill-current"></i>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Parallax Section -->
    <div class="parallax h-96 flex items-center justify-center" style="background-image: url('http://static.photos/aerial/1200x630/14')">
        <div class="text-center px-4">
            <h2 data-aos="fade-up" class="text-3xl md:text-4xl font-bold text-white mb-4">Ready to Elevate Your Visual Content?</h2>
            <a data-aos="fade-up" data-aos-delay="100" href="#contact" class="inline-flex items-center px-6 py-3 border border-transparent text-base font-medium rounded-md shadow-sm text-blue-600 bg-white hover:bg-blue-50">
                Get in Touch
                <i data-feather="arrow-right" class="ml-2"></i>
            </a>
        </div>
    </div>

    <!-- Contact Section -->
    <section id="contact" class="py-20 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="lg:grid lg:grid-cols-2 lg:gap-16">
                <div data-aos="fade-right" class="mb-12 lg:mb-0">
                    <h2 class="text-3xl md:text-4xl font-bold text-gray-900 mb-6">Contact Us</h2>
                    <p class="text-lg text-gray-600 mb-8">Have a project in mind or want to discuss your photography needs? Reach out to us and we'll get back to you within 24 hours.</p>
                    
                    <div class="space-y-6">
                        <div class="flex items-start">
                            <div class="flex-shrink-0">
                                <div class="flex items-center justify-center h-10 w-10 rounded-full bg-blue-100">
                                    <i data-feather="mail" class="text-blue-600"></i>
                                </div>
                            </div>
                            <div class="ml-4">
                                <p class="text-base font-medium text-gray-900">Email</p>
                                <p class="text-base text-gray-600">elevatedimagery.co.llc@gmail.com</p>
                            </div>
                        </div>
                        
                        <div class="flex items-start">
                            <div class="flex-shrink-0">
                                <div class="flex items-center justify-center h-10 w-10 rounded-full bg-blue-100">
                                    <i data-feather="phone" class="text-blue-600"></i>
                                </div>
                            </div>
                            <div class="ml-4">
                                <p class="text-base font-medium text-gray-900">Phone</p>
                                <p class="text-base text-gray-600">(406) 295-2589</p>
                            </div>
                        </div>
                        
                        <div class="flex items-start">
                            <div class="flex-shrink-0">
                                <div class="flex items-center justify-center h-10 w-10 rounded-full bg-blue-100">
                                    <i data-feather="map-pin" class="text-blue-600"></i>
                                </div>
                            </div>
                            <div class="ml-4">
                                <p class="text-base font-medium text-gray-900">Service Broadband</p>
                                <p class="text-base text-gray-600">State of Delaware (DE) United States of Amercica</p>
                            </div>
                        </div>
                    </div>
                    
                    <div class="mt-8">
                        <h3 class="text-lg font-semibold text-gray-900 mb-4">Follow Us</h3>
                        <div class="flex space-x-4">
                            <a href="https://www.instagram.com/elevated_imagery.co/" target="_blank" class="text-blue-600 hover:text-blue-800">
                                <i data-feather="instagram"></i>
                            </a>
                            <a href="https://www.facebook.com/share/15vMGx44dk/?mibextid=wwXIfr" target="_blank" class="text-blue-600 hover:text-blue-800">
                                <i data-feather="facebook"></i>
                            </a>
                            <a href="http://www.youtube.com/@elevatedimagery-co" target="_blank" class="text-blue-600 hover:text-blue-800">
                                <i data-feather="youtube"></i>
                            </a>
                        </div>
                    </div>
                </div>
                
                <div data-aos="fade-left">
                    <form class="space-y-6">
                        <div>
                            <label for="name" class="block text-sm font-medium text-gray-700">Full Name</label>
                            <input type="text" id="name" name="name" class="mt-1 block w-full border border-gray-300 rounded-md shadow-sm py-2 px-3 focus:outline-none focus:ring-blue-500 focus:border-blue-500">
                        </div>
                        
                        <div>
                            <label for="email" class="block text-sm font-medium text-gray-700">Email Address</label>
                            <input type="email" id="email" name="email" class="mt-1 block w-full border border-gray-300 rounded-md shadow-sm py-2 px-3 focus:outline-none focus:ring-blue-500 focus:border-blue-500">
                        </div>
                        
                        <div>
                            <label for="phone" class="block text-sm font-medium text-gray-700">Phone Number</label>
                            <input type="tel" id="phone" name="phone" class="mt-1 block w-full border border-gray-300 rounded-md shadow-sm py-2 px-3 focus:outline-none focus:ring-blue-500 focus:border-blue-500">
                        </div>
                        
                        <div>
                            <label for="service" class="block text-sm font-medium text-gray-700">Service Interested In</label>
                            <select id="service" name="service" class="mt-1 block w-full border border-gray-300 rounded-md shadow-sm py-2 px-3 focus:outline-none focus:ring-blue-500 focus:border-blue-500">
                                <option>Select a service</option>
                                <option>Real Estate Photography</option>
                                <option>Event Coverage</option>
                                <option>Commercial Projects</option>
                                <option>Other</option>
                            </select>
                        </div>
                        
                        <div>
                            <label for="message" class="block text-sm font-medium text-gray-700">Message</label>
                            <textarea id="message" name="message" rows="4" class="mt-1 block w-full border border-gray-300 rounded-md shadow-sm py-2 px-3 focus:outline-none focus:ring-blue-500 focus:border-blue-500"></textarea>
                        </div>
                        
                        <div>
                            <button type="submit" class="w-full flex justify-center py-3 px-4 border border-transparent rounded-md shadow-sm text-sm font-medium text-white bg-blue-600 hover:bg-blue-700 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-blue-500">
                                Send Message
                            </button>
                        </div>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-900 text-white py-12">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-1 md:grid-cols-4 gap-8">
                <div>
                    <h3 class="text-lg font-semibold mb-4">Elevated Imagery</h3>
                    <p class="text-gray-400">Professional drone and camera photography services for businesses and individuals.</p>
                </div>
                
                <div>
                    <h3 class="text-lg font-semibold mb-4">Services</h3>
                    <ul class="space-y-2">
                        <li><a href="#" class="text-gray-400 hover:text-white">Real Estate</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white">Events</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white">Commercial</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white">Real Estate</a></li>
                    </ul>
                </div>
                
                <div>
                    <h3 class="text-lg font-semibold mb-4">Company</h3>
                    <ul class="space-y-2">
                        <li><a href="#about" class="text-gray-400 hover:text-white">About Us</a></li>
                        <li><a href="#portfolio" class="text-gray-400 hover:text-white">Portfolio</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white">Testimonials</a></li>
                        <li><a href="#contact" class="text-gray-400 hover:text-white">Contact</a></li>
                    </ul>
                </div>
                
                <div>
                    <h3 class="text-lg font-semibold mb-4">Legal</h3>
                    <ul class="space-y-2">
                        <li><a href="#" class="text-gray-400 hover:text-white">Privacy Policy</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white">Terms of Service</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white">Cookie Policy</a></li>
                    </ul>
                </div>
            </div>
            
            <div class="mt-12 pt-8 border-t border-gray-800 flex flex-col md:flex-row justify-between items-center">
                <p class="text-gray-400 text-sm">© 2025 Elevated Imagery LLC. All rights reserved.</p>
                <div class="mt-4 md:mt-0 flex space-x-6">
                    <a href="https://www.instagram.com/elevated_imagery.co/" target="_blank" class="text-gray-400 hover:text-white">
                        <i data-feather="instagram"></i>
                    </a>
                    <a href="https://www.facebook.com/share/15vMGx44dk/?mibextid=wwXIfr" target="_blank" class="text-gray-400 hover:text-white">
                        <i data-feather="facebook"></i>
                    </a>
                    <a href="http://www.youtube.com/@elevatedimagery-co" target="_blank" class="text-gray-400 hover:text-white">
                        <i data-feather="youtube"></i>
                    </a>
                </div>
            </div>
        </div>
    </footer>

    <script>
        // Initialize Vanta.js globe effect
        VANTA.GLOBE({
            el: "#vanta-globe",
            mouseControls: true,
            touchControls: true,
            gyroControls: false,
            minHeight: 200.00,
            minWidth: 200.00,
            scale: 1.00,
            scaleMobile: 1.00,
            color: 0x3a86ff,
            backgroundColor: 0x1565c0,
            size: 0.8
        });
    </script>
    <script>AOS.init();</script>
    <script>feather.replace();</script>  
<script>
  // Toggle mobile menu
  const menuButton = document.querySelector("nav button");
  const mobileMenu = document.getElementById("mobile-menu");

  menuButton.addEventListener("click", () => {
    mobileMenu.classList.toggle("hidden");
  });
</script>


