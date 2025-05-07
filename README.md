# business.github.io
!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jindal Chips Store - Premium Tiles & Marbles in Jind</title>
    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <!-- Font Awesome -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        :root {
            --primary: #d4a373;
            --secondary: #606c38;
            --dark: #283618;
            --light: #fefae0;
        }
        
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            scroll-behavior: smooth;
        }
        
        .navbar {
            background-color: var(--dark) !important;
        }
        
        .hero-section {
            background: linear-gradient(rgba(0,0,0,0.7), rgba(0,0,0,0.7)), url('https://images.unsplash.com/photo-1600585154340-be6161a56a0c?ixlib=rb-4.0.3');
            background-size: cover;
            background-position: center;
            color: white;
            padding: 150px 0 100px;
            margin-top: 56px;
        }
        
        .product-card {
            transition: transform 0.3s;
            border: none;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
        }
        
        .product-card:hover {
            transform: translateY(-10px);
        }
        
        .gallery-img {
            transition: transform 0.3s;
            cursor: pointer;
            border-radius: 5px;
        }
        
        .gallery-img:hover {
            transform: scale(1.03);
        }
        
        .btn-primary {
            background-color: var(--primary);
            border: none;
            padding: 10px 25px;
        }
        
        .btn-primary:hover {
            background-color: #b08968;
        }
        
        section {
            padding: 80px 0;
        }
        
        .contact-info i {
            color: var(--primary);
            width: 30px;
        }
    </style>
</head>
<body>
    <!-- Navigation -->
    <nav class="navbar navbar-expand-lg navbar-dark fixed-top">
        <div class="container">
            <a class="navbar-brand fw-bold" href="#">
                <i class="fas fa-store me-2"></i>JINDAL CHIPS STORE
            </a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item"><a class="nav-link active" href="#home">Home</a></li>
                    <li class="nav-item"><a class="nav-link" href="#products">Products</a></li>
                    <li class="nav-item"><a class="nav-link" href="#gallery">Gallery</a></li>
                    <li class="nav-item"><a class="nav-link" href="#about">About Us</a></li>
                    <li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="hero-section">
        <div class="container text-center">
            <h1 class="display-4 fw-bold mb-4">Premium Construction Materials in Jind</h1>
            <p class="lead fs-4 mb-5">Tiles • Granites • Marble • Sanitaryware • Stone Products</p>
            <div class="d-flex gap-3 justify-content-center">
                <a href="#contact" class="btn btn-primary btn-lg">
                    <i class="fas fa-phone-alt me-2"></i>Call Now
                </a>
                <a href="#products" class="btn btn-outline-light btn-lg">
                    <i class="fas fa-box-open me-2"></i>Our Products
                </a>
            </div>
        </div>
    </section>

    <!-- Products Section -->
    <section id="products" class="bg-light">
        <div class="container">
            <div class="text-center mb-5">
                <h2 class="display-5 fw-bold">Our Premium Products</h2>
                <p class="lead text-muted">Quality materials for all your construction needs</p>
            </div>
            <div class="row g-4">
                <!-- Product 1 -->
                <div class="col-lg-4 col-md-6">
                    <div class="card product-card h-100">
                        <img src="https://images.unsplash.com/photo-1599427303058-f04cbcf4756f?ixlib=rb-4.0.3"
                            class="card-img-top" alt="Tiles" style="height: 200px; object-fit: cover;">
                        <div class="card-body">
                            <h5 class="card-title fw-bold">Tiles Collection</h5>
                            <p class="card-text">Ceramic, Vitrified, Digital, and Designer tiles for floors and walls.</p>
                            <ul class="list-unstyled">
                                <li><i class="fas fa-check text-primary me-2"></i> 100+ Modern Designs</li>
                                <li><i class="fas fa-check text-primary me-2"></i> Imported & Indian Options</li>
                                <li><i class="fas fa-check text-primary me-2"></i> All Size Available</li>
                            </ul>
                        </div>
                        <div class="card-footer bg-white border-0">
                            <a href="#contact" class="btn btn-sm btn-primary w-100">Enquire Now</a>
                        </div>
                    </div>
                </div>
                
                <!-- Product 2 -->
                <div class="col-lg-4 col-md-6">
                    <div class="card product-card h-100">
                        <img src="https://images.unsplash.com/photo-1605100804763-247f67b3557e?ixlib=rb-4.0.3"
                            class="card-img-top" alt="Granite" style="height: 200px; object-fit: cover;">
                        <div class="card-body">
                            <h5 class="card-title fw-bold">Granite Stones</h5>
                            <p class="card-text">Premium quality granite for countertops, flooring, and cladding.</p>
                            <ul class="list-unstyled">
                                <li><i class="fas fa-check text-primary me-2"></i> 50+ Varieties</li>
                                <li><i class="fas fa-check text-primary me-2"></i> Custom Cutting</li>
                                <li><i class="fas fa-check text-primary me-2"></i> Polish & Matte Finish</li>
                            </ul>
                        </div>
                        <div class="card-footer bg-white border-0">
                            <a href="#contact" class="btn btn-sm btn-primary w-100">Enquire Now</a>
                        </div>
                    </div>
                </div>
                
                <!-- Product 3 -->
                <div class="col-lg-4 col-md-6">
                    <div class="card product-card h-100">
                        <img src="https://images.unsplash.com/photo-1600566752355-35792bedcfe3?ixlib=rb-4.0.3"
                            class="card-img-top" alt="Marble" style="height: 200px; object-fit: cover;">
                        <div class="card-body">
                            <h5 class="card-title fw-bold">Marble Collection</h5>
                            <p class="card-text">Luxurious marble for flooring, tabletops, and decorative purposes.</p>
                            <ul class="list-unstyled">
                                <li><i class="fas fa-check text-primary me-2"></i> Italian & Indian Marble</li>
                                <li><i class="fas fa-check text-primary me-2"></i> Polished Finish</li>
                                <li><i class="fas fa-check text-primary me-2"></i> All Thickness Available</li>
                            </ul>
                        </div>
                        <div class="card-footer bg-white border-0">
                            <a href="#contact" class="btn btn-sm btn-primary w-100">Enquire Now</a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Gallery Section -->
    <section id="gallery">
        <div class="container">
            <div class="text-center mb-5">
                <h2 class="display-5 fw-bold">Our Work Gallery</h2>
                <p class="lead text-muted">See our premium quality materials in real projects</p>
            </div>
            <div class="row g-3">
                <div class="col-lg-3 col-md-4 col-6">
                    <img src="https://images.unsplash.com/photo-1600585152220-90363fe7e115?ixlib=rb-4.0.3" 
                         class="img-fluid gallery-img" alt="Tile Installation" style="height: 200px; width: 100%; object-fit: cover;">
                </div>
                <div class="col-lg-3 col-md-4 col-6">
                    <img src="https://images.unsplash.com/photo-1600210492493-0946911123ea?ixlib=rb-4.0.3" 
                         class="img-fluid gallery-img" alt="Granite Countertop" style="height: 200px; width: 100%; object-fit: cover;">
                </div>
                <div class="col-lg-3 col-md-4 col-6">
                    <img src="https://images.unsplash.com/photo-1600566753190-17f0baa2a6c3?ixlib=rb-4.0.3" 
                         class="img-fluid gallery-img" alt="Marble Flooring" style="height: 200px; width: 100%; object-fit: cover;">
                </div>
                <div class="col-lg-3 col-md-4 col-6">
                    <img src="https://images.unsplash.com/photo-1600585154340-be6161a56a0c?ixlib=rb-4.0.3" 
                         class="img-fluid gallery-img" alt="Bathroom Tiles" style="height: 200px; width: 100%; object-fit: cover;">
                </div>
                <div class="col-lg-3 col-md-4 col-6">
                    <img src="https://images.unsplash.com/photo-1600121848594-d8644e57abab?ixlib=rb-4.0.3" 
                         class="img-fluid gallery-img" alt="Kitchen Granite" style="height: 200px; width: 100%; object-fit: cover;">
                </div>
                <div class="col-lg-3 col-md-4 col-6">
                    <img src="https://images.unsplash.com/photo-1600210491892-03d54c0aaf87?ixlib=rb-4.0.3" 
                         class="img-fluid gallery-img" alt="Staircase Marble" style="height: 200px; width: 100%; object-fit: cover;">
                </div>
                <div class="col-lg-3 col-md-4 col-6">
                    <img src="https://images.unsplash.com/photo-1600566752355-35792bedcfe3?ixlib=rb-4.0.3" 
                         class="img-fluid gallery-img" alt="Marble Wall" style="height: 200px; width: 100%; object-fit: cover;">
                </div>
                <div class="col-lg-3 col-md-4 col-6">
                    <img src="https://images.unsplash.com/photo-1583845112203-4541b58ff8a9?ixlib=rb-4.0.3" 
                         class="img-fluid gallery-img" alt="Outdoor Tiles" style="height: 200px; width: 100%; object-fit: cover;">
                </div>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="bg-dark text-white">
        <div class="container">
            <div class="row align-items-center">
                <div class="col-lg-6 mb-4 mb-lg-0">
                    <h2 class="display-5 fw-bold mb-4">About Jindal Chips Store</h2>
                    <p class="lead">Jind's trusted supplier of premium construction materials since 2005</p>
                    <p>We specialize in providing high-quality tiles, granites, marbles, and stone products for residential and commercial projects. With our extensive collection and expert guidance, we help customers find the perfect materials for their construction needs.</p>
                    <ul class="list-unstyled fs-5">
                        <li class="mb-2"><i class="fas fa-check-circle text-primary me-2"></i> 18+ Years of Experience</li>
                        <li class="mb-2"><i class="fas fa-check-circle text-primary me-2"></i> 5000+ Satisfied Customers</li>
                        <li class="mb-2"><i class="fas fa-check-circle text-primary me-2"></i> Competitive Pricing</li>
                        <li class="mb-2"><i class="fas fa-check-circle text-primary me-2"></i> Quality Assurance</li>
                    </ul>
                </div>
                <div class="col-lg-6">
                    <div class="ratio ratio-16x9">
                        <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3483.467123456789!2d76.31654321561817!3d29.12345678901234!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x0%3A0x0!2zMjnCsDA3JzI0LjQiTiA3NsKwMTknMDAuOCJF!5e0!3m2!1sen!2sin!4v1621234567890!5m2!1sen!2sin" 
                                allowfullscreen="" loading="lazy"></iframe>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact">
        <div class="container">
            <div class="row">
                <div class="col-lg-5 mb-5 mb-lg-0">
                    <h2 class="display-5 fw-bold mb-4">Contact Information</h2>
                    <div class="contact-info">
                        <div class="d-flex mb-4">
                            <i class="fas fa-map-marker-alt mt-1 me-3 fs-4"></i>
                            <div>
                                <h5>Address</h5>
                                <p class="mb-0">Scheme No. 6, Near Bus Stand<br>Jind, Haryana 126102</p>
                            </div>
                        </div>
                        
                        <div class="d-flex mb-4">
                            <i class="fas fa-phone-alt mt-1 me-3 fs-4"></i>
                            <div>
                                <h5>Phone</h5>
                                <p class="mb-0">+91 98765 43210<br>+91 98765 43211</p>
                            </div>
                        </div>
                        
                        <div class="d-flex mb-4">
                            <i class="fas fa-envelope mt-1 me-3 fs-4"></i>
                            <div>
                                <h5>Email</h5>
                                <p class="mb-0">info@jindalchips.com<br>sales@jindalchips.com</p>
                            </div>
                        </div>
                        
                        <div class="d-flex">
                            <i class="fas fa-clock mt-1 me-3 fs-4"></i>
                            <div>
                                <h5>Opening Hours</h5>
                                <p class="mb-0">Monday-Saturday: 9:00 AM - 8:00 PM<br>Sunday: 10:00 AM - 4:00 PM</p>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col-lg-7">
                    <div class="card shadow">
                        <div class="card-body p-5">
                            <h3 class="fw-bold mb-4">Send Enquiry</h3>
                            <form id="contactForm">
                                <div class="row">
                                    <div class="col-md-6 mb-3">
                                        <label for="name" class="form-label">Your Name</label>
                                        <input type="text" class="form-control" id="name" required>
                                    </div>
                                    <div class="col-md-6 mb-3">
                                        <label for="phone" class="form-label">Phone Number</label>
                                        <input type="tel" class="form-control" id="phone" required>
                                    </div>
                                </div>
                                <div class="mb-3">
                                    <label for="email" class="form-label">Email Address</label>
                                    <input type="email" class="form-control" id="email">
                                </div>
                                <div class="mb-3">
                                    <label for="product" class="form-label">Product Interested In</label>
                                    <select class="form-select" id="product">
                                        <option value="">Select Product</option>
                                        <option value="Tiles">Tiles</option>
                                        <option value="Granite">Granite</option>
                                        <option value="Marble">Marble</option>
                                        <option value="Other">Other</option>
                                    </select>
                                </div>
                                <div class="mb-3">
                                    <label for="message" class="form-label">Your Message</label>
                                    <textarea class="form-control" id="message" rows="4"></textarea>
                                </div>
                                <button type="submit" class="btn btn-primary w-100 py-2">
                                    <i class="fas fa-paper-plane me-2"></i>Send Enquiry
                                </button>
                            </form>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-dark text-white py-4">
        <div class="container">
            <div class="row">
                <div class="col-md-4 mb-4 mb-md-0">
                    <h5 class="fw-bold mb-3">Jindal Chips Store</h5>
                    <p>Your trusted partner for premium construction materials in Jind, Haryana.</p>
                    <div class="social-links">
                        <a href="#" class="text-white me-3"><i class="fab fa-facebook-f"></i></a>
                        <a href="#" class="text-white me-3"><i class="fab fa-instagram"></i></a>
                        <a href="#" class="text-white me-3"><i class="fab fa-whatsapp"></i></a>
                    </div>
                </div>
                <div class="col-md-4 mb-4 mb-md-0">
                    <h5 class="fw-bold mb-3">Quick Links</h5>
                    <ul class="list-unstyled">
                        <li class="mb-2"><a href="#home" class="text-white text-decoration-none">Home</a></li>
                        <li class="mb-2"><a href="#products" class="text-white text-decoration-none">Products</a></li>
                        <li class="mb-2"><a href="#gallery" class="text-white text-decoration-none">Gallery</a></li>
                        <li class="mb-2"><a href="#about" class="text-white text-decoration-none">About Us</a></li>
                        <li><a href="#contact" class="text-white text-decoration-none">Contact</a></li>
                    </ul>
                </div>
                <div class="col-md-4">
                    <h5 class="fw-bold mb-3">Business Hours</h5>
                    <ul class="list-unstyled">
                        <li class="mb-2">Monday - Saturday: 9AM - 8PM</li>
                        <li class="mb-2">Sunday: 10AM - 4PM</li>
                        <li>Closed on Public Holidays</li>
                    </ul>
                </div>
            </div>
            <hr class="my-4">
            <div class="text-center">
                <p class="mb-0">&copy; 2023 Jindal Chips Store. All Rights Reserved.</p>
            </div>
        </div>
    </footer>

    <!-- Bootstrap JS -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
    <script>
        // Form submission handling
        document.getElementById('contactForm').addEventListener('submit', function(e) {
            e.preventDefault();
            alert('Thank you for your enquiry! We will contact you shortly.');
            this.reset();
        });
        
        // Smooth scrolling for anchor links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });
    </script>
</body>
</html>


