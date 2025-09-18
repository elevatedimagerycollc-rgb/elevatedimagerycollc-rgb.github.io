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
  <style>
    html, body { height: 100%; margin: 0; padding: 0; }
    .gallery-item { transition: all 0.3s ease; }
    .gallery-item:hover { transform: scale(1.03); box-shadow: 0 10px 20px rgba(0,0,0,0.2); }
    @supports (-webkit-touch-callout: none) { #vanta-globe { height: -webkit-fill-available; } }
  </style>
  
body {
  background: url('images/background.jpg') no-repeat center center;
  background-size: cover;
}

/* Only apply parallax fixed effect on desktop */
@media (min-width: 768px) {
  body {
    background-attachment: fixed; }
}
  </style>
</head>

<!-- Navigation -->
<nav class="fixed top-0 left-0 w-full z-50 bg-white shadow-md">
  <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
    <div class="flex justify-between h-16">
      <!-- Logo -->
      <div class="flex items-center">
        <a href="#" class="flex-shrink-0 flex items-center">
          <i data-feather="camera" class="h-8 w-8 text-blue-600"></i>
          <span class="ml-2 text-xl font-bold text-blue-600">Elevated Imagery</span>
        </a>
      </div>

      <!-- Desktop Menu -->
      <div class="hidden md:ml-6 md:flex md:items-center md:space-x-8">
        <a href="#" class="text-blue-600 border-b-2 border-blue-600 px-3 py-2 text-sm font-medium">Home</a>
        <a href="#services" class="text-gray-700 hover:text-blue-600 px-3 py-2 text-sm font-medium">Services</a>
        <a href="#portfolio" class="text-gray-700 hover:text-blue-600 px-3 py-2 text-sm font-medium">Portfolio</a>
        <a href="#about" class="text-gray-700 hover:text-blue-600 px-3 py-2 text-sm font-medium">About</a>
        <a href="#contact" class="text-gray-700 hover:text-blue-600 px-3 py-2 text-sm font-medium">Contact</a>
      </div>

      <!-- Mobile Menu Button -->
      <div class="flex items-center md:hidden">
        <button id="menu-button" type="button" class="p-2 rounded-md text-gray-700 hover:text-blue-600 focus:outline-none">
          <i data-feather="menu" class="h-6 w-6"></i>
        </button>
      </div>
    </div>
  </div>

  <!-- Mobile Menu (hidden by default) -->
  <div id="mobile-menu" class="hidden md:hidden bg-white shadow-md">
    <div class="px-2 pt-2 pb-3 space-y-1">
      <a href="#" class="block text-blue-600 px-3 py-2 rounded-md text-base font-medium">Home</a>
      <a href="#services" class="block text-gray-700 hover:bg-blue-100 px-3 py-2 rounded-md text-base font-medium">Services</a>
      <a href="#portfolio" class="block text-gray-700 hover:bg-blue-100 px-3 py-2 rounded-md text-base font-medium">Portfolio</a>
      <a href="#about" class="block text-gray-700 hover:bg-blue-100 px-3 py-2 rounded-md text-base font-medium">About</a>
      <a href="#contact" class="block text-gray-700 hover:bg-blue-100 px-3 py-2 rounded-md text-base font-medium">Contact</a>
    </div>
  </div>
</nav>

<script>
  const menuButton = document.getElementById("menu-button");
  const mobileMenu = document.getElementById("mobile-menu");

  menuButton.addEventListener("click", () => {
    mobileMenu.classList.toggle("hidden");
  });
</script>


  <!-- Hero Section -->
<section class="relative w-full h-screen flex items-center justify-center">
  <div class="absolute inset-0 bg-cover bg-center" 
       style="background-image: url('/static/images/background.jpg');">
    <div class="absolute inset-0 bg-gradient-to-br from-blue-800/40 to-blue-400/40"></div>
  </div>
  <div class="relative z-10 text-center px-4">
    <h1 class="text-4xl md:text-6xl font-bold text-white mb-6">Capture The World From New Perspectives</h1>
    <p class="text-xl md:text-2xl text-white mb-8 max-w-3xl mx-auto">
      Professional drone and camera photography services for Real Estate, Events, and Personal projects.
    </p>
    <div class="flex flex-col sm:flex-row justify-center gap-4">
      <a href="#contact" class="bg-white text-blue-600 hover:bg-blue-600 hover:text-white px-6 py-3 rounded-lg font-medium shadow-lg transition duration-300">
        Book a Session
      </a>
      <a href="#portfolio" class="bg-white border-2 border-white text-blue-600 hover:bg-blue-600 hover:text-white px-6 py-3 rounded-lg font-medium transition duration-300">
        View Portfolio
      </a>
    </div>
  </div>
</section>

<!-- Services Section -->
<section id="services" class="py-24">
  <div class="max-w-6xl mx-auto px-6 text-center 
              bg-white/70 backdrop-blur-sm rounded-2xl shadow-lg p-12">
    <h2 class="text-3xl font-bold mb-12">Our Services</h2>
    <div class="grid md:grid-cols-3 gap-8">
      
      <!-- Real Estate -->
      <div class="bg-white rounded-2xl shadow-lg overflow-hidden hover:shadow-2xl transition">
        <img src="images/re.example.jpg" alt="Real Estate" class="w-full h-56 object-cover">
        <div class="p-6">
          <h3 class="text-2xl font-semibold text-gray-900">Real Estate Photography</h3>
          <p class="text-gray-600 mt-3">Showcase properties with stunning aerial and interior visuals that captivate buyers.</p>
        </div>
      </div>

      <!-- Event Coverage -->
      <div class="bg-white rounded-2xl shadow-lg overflow-hidden hover:shadow-2xl transition">
        <img src="images/WeddingCelebration.JPG" alt="Wedding" class="w-full h-56 object-cover">
        <div class="p-6">
          <h3 class="text-2xl font-semibold text-gray-900">Event Coverage</h3>
          <p class="text-gray-600 mt-3">Capture the magic of your special events from unique aerial perspectives and ground level moments.</p>
        </div>
      </div>

      <!-- Commercial Projects -->
      <div class="bg-white rounded-2xl shadow-lg overflow-hidden hover:shadow-2xl transition">
        <img src="images/landscape.example.jpg" alt="Commercial Projects" class="w-full h-56 object-cover">
        <div class="p-6">
          <h3 class="text-2xl font-semibold text-gray-900">Commercial Projects</h3>
          <p class="text-gray-600 mt-3">Professional photography for businesses, construction sites, and large-scale projects.</p>
        </div>
      </div>

    </div>
  </div>
</section>

<!-- Portfolio Section -->
<section id="portfolio" class="py-24">
  <div class="max-w-6xl mx-auto px-6 text-center 
              bg-white/70 backdrop-blur-sm rounded-2xl shadow-lg p-12">
    <h2 class="text-3xl font-bold mb-12">Our Portfolio</h2>
    
      <!-- Real Estate -->
      <a href="real-estate.html" class="block bg-white rounded-2xl shadow-lg overflow-hidden hover:shadow-2xl transition">
        <img src="images/re.example.jpg" alt="Real Estate" class="w-full h-56 object-cover">
        <div class="p-6">
          <h3 class="text-xl font-semibold text-gray-900">Real Estate</h3>
          <p class="text-gray-600 mt-2">Elegant Homes</p>
        </div>
      </a>

      <!-- Event Photography -->
      <a href="event-photography.html" class="block bg-white rounded-2xl shadow-lg overflow-hidden hover:shadow-2xl transition">
        <img src="images/WeddingCelebration.JPG" alt="Event Photography" class="w-full h-56 object-cover">
        <div class="p-6">
          <h3 class="text-xl font-semibold text-gray-900">Event Photography</h3>
          <p class="text-gray-600 mt-2">Wedding Celebration</p>
        </div>
      </a>

      <!-- Portraits -->
      <a href="portrait.html" class="block bg-white rounded-2xl shadow-lg overflow-hidden hover:shadow-2xl transition">
        <img src="images/portrait.example.jpg" alt="Portrait Photography" class="w-full h-56 object-cover">
        <div class="p-6">
          <h3 class="text-xl font-semibold text-gray-900">Portraits</h3>
          <p class="text-gray-600 mt-2">Express Yourself</p>
        </div>
      </a>

      <!-- Automotive -->
      <a href="automotive.html" class="block bg-white rounded-2xl shadow-lg overflow-hidden hover:shadow-2xl transition">
        <img src="images/350z.boat.jpg" alt="Automotive" class="w-full h-56 object-cover">
        <div class="p-6">
          <h3 class="text-xl font-semibold text-gray-900">Automotive Photography</h3>
          <p class="text-gray-600 mt-2">Power & Style</p>
        </div>
      </a>

      <!-- Landscape -->
      <a href="landscape-photography.html" class="block bg-white rounded-2xl shadow-lg overflow-hidden hover:shadow-2xl transition">
        <img src="images/landscape.example.jpg" alt="Landscape Photography" class="w-full h-56 object-cover">
        <div class="p-6">
          <h3 class="text-xl font-semibold text-gray-900">Landscape Photography</h3>
          <p class="text-gray-600 mt-2">Beautiful Scenes</p>
        </div>
      </a>

      <!-- Sports -->
      <a href="sports-photography.html" class="block bg-white rounded-2xl shadow-lg overflow-hidden hover:shadow-2xl transition">
        <img src="images/Kyle.Swinging.jpg" alt="Sports Photography" class="w-full h-56 object-cover">
        <div class="p-6">
          <h3 class="text-xl font-semibold text-gray-900">Sports Photography</h3>
          <p class="text-gray-600 mt-2">Action Shots</p>
        </div>
      </a>

    </div>

    <!-- View Full Portfolio Button -->
    <div class="text-center mt-16">
      <a href="full-portfolio.html"
         class="inline-flex items-center px-8 py-4 border border-transparent text-lg font-medium rounded-xl shadow-md text-white bg-blue-600 hover:bg-blue-700">
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
            
            <div class="grid grid-cols-1 sm:grid-cols-1 lg:grid-cols-3 gap-8">
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
                            <p class="text-blue-200">Sports Client</p>
                        </div>
                    </div>
                    <p class="text-blue-100">"Best pictures and drone videos of all time!! Really great quality and quick work."</p>
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
<section class="relative w-full h-96 flex items-center justify-center bg-fixed bg-center bg-cover"
         style="background-image: url('//images/aerial.14.jpg');">
  <div class="absolute inset-0 bg-black bg-opacity-30"></div>
  <div class="relative z-10 text-center px-4">
    <h2 data-aos="fade-up" class="text-3xl md:text-4xl font-bold text-white mb-4">Ready to Elevate Your Visual Content?</h2>
    <a data-aos="fade-up" data-aos-delay="100" href="#contact" class="inline-flex items-center px-6 py-3 rounded-md bg-white text-blue-600 hover:bg-blue-50">
      Get in Touch
      <i data-feather="arrow-right" class="ml-2"></i>
    </a>
  </div>
</section>

    <!-- Contact Section -->
    <section id="contact" class="py-20 bg-white">
  <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
    <div class="lg:flex lg:items-start lg:gap-16">
        
      <!-- Left column: Contact info -->
      <div data-aos="fade-right" class="lg:w-1/2 mb-12 lg:mb-0">
        <h2 class="text-3xl md:text-4xl font-bold text-gray-900 mb-6">Contact Us</h2>
        <p class="text-lg text-gray-600 mb-8">
          Have a project in mind or want to discuss your photography needs? 
          Reach out to us and we'll get back to you within 24 hours.
        </p>

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
              <p class="text-base text-gray-600">State of Delaware (DE), United States of America</p>
            </div>
          </div>
        </div>
      </div>

      <!-- Right column: Form + Follow Us -->
      <div data-aos="fade-left" class="lg:w-1/2 lg:pl-0">
        <div class="bg-white shadow-lg rounded-lg p-6">
          <form id="contact-form" action="https://formspree.io/f/mdklrpba" method="POST" class="space-y-4">
            <!-- Name -->
            <input type="text" name="name" placeholder="Your Name" class="w-full p-2 border rounded-md" required>

            <!-- Email -->
            <input type="email" name="email" placeholder="Your Email" class="w-full p-2 border rounded-md" required>

            <!-- Service Dropdown -->
            <select name="service" class="w-full p-2 border rounded-md" required>
              <option value="">Select a Service</option>
              <option value="Real Estate Photography">Real Estate Photography</option>
              <option value="Drone Photography">Drone Photography</option>
              <option value="Event Coverage">Event Coverage</option>
              <option value="Other">Other</option>
            </select>

            <!-- Message -->
            <textarea name="message" placeholder="Your Message" class="w-full p-2 border rounded-md" rows="5" required></textarea>

            <!-- Submit -->
            <button type="submit" class="px-4 py-2 bg-blue-600 text-white rounded-md hover:bg-blue-700">
              Send Message
            </button>
          </form>

          <!-- Success / Error Message -->
          <p id="form-status" class="mt-4 text-center font-medium"></p>

          <!-- Follow Us -->
          <div class="mt-8">
            <h3 class="text-lg font-semibold text-gray-900 mb-4">Follow Us</h3>
            <div class="flex space-x-4">
              <a href="https://www.instagram.com/elevated_imagery.co/" target="_blank" class="w-12 h-12 flex items-center justify-center rounded-full bg-gradient-to-tr from-pink-500 via-red-500 to-yellow-500 text-white hover:opacity-90 transition">
                <i data-feather="instagram"></i>
              </a>
              <a href="https://www.facebook.com/share/15vMGx44dk/?mibextid=wwXIfr" target="_blank" class="w-12 h-12 flex items-center justify-center rounded-full bg-blue-600 text-white hover:bg-blue-700 transition">
                <i data-feather="facebook"></i>
              </a>
              <a href="http://www.youtube.com/@elevatedimagery-co" target="_blank" class="w-12 h-12 flex items-center justify-center rounded-full bg-red-600 text-white hover:bg-red-700 transition">
                <i data-feather="youtube"></i>
              </a>
            </div>
          </div>
        </div>
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
    <script>AOS.init();</script>
    <script>feather.replace();</script>  
