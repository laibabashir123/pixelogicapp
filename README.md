<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Digital Solutions Hub - Professional IT Services</title>
    <link rel="stylesheet" href="style.css">
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
</head>
<body>
    <!-- Navigation -->
    <nav class="navbar">
        <div class="nav-container">
            <div class="nav-logo">
                <a href="#home">DigitalSolutions</a>
            </div>
            <div class="nav-menu" id="nav-menu">
                <a href="#home" class="nav-link">Home</a>
                <a href="#services" class="nav-link">Services</a>
                <a href="#portfolio" class="nav-link">Portfolio</a>
                <a href="#about" class="nav-link">About</a>
                <a href="#testimonials" class="nav-link">Reviews</a>
                <a href="#contact" class="nav-link">Contact</a>
            </div>
            <div class="hamburger" id="hamburger">
                <span></span>
                <span></span>
                <span></span>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="hero">
        <div class="hero-container">
            <div class="hero-content">
                <h1>Elevate Your <span class="highlight">Digital Presence</span> with Expert IT Solutions</h1>
                <p>I provide comprehensive digital services including Social Media Marketing, Web Development, SEO, and Graphic Design to transform your business.</p>
                <div class="hero-buttons">
                    <a href="#portfolio" class="btn btn-primary">View My Work</a>
                    <a href="#contact" class="btn btn-secondary">Get Free Quote</a>
                </div>
            </div>
            <div class="hero-image">
                <div class="floating-card">
                    <i class="fas fa-code"></i>
                    <h3>Web Development</h3>
                </div>
                <div class="floating-card">
                    <i class="fas fa-chart-line"></i>
                    <h3>Digital Marketing</h3>
                </div>
                <div class="floating-card">
                    <i class="fas fa-palette"></i>
                    <h3>Graphic Design</h3>
                </div>
            </div>
        </div>
    </section>

    <!-- Services Section -->
    <section id="services" class="services">
        <div class="container">
            <h2 class="section-title">My Services</h2>
            <p class="section-subtitle">Comprehensive digital solutions to grow your business</p>
            
            <div class="services-grid">
                <!-- Service 1 -->
                <div class="service-card">
                    <div class="service-icon">
                        <i class="fas fa-share-alt"></i>
                    </div>
                    <h3>Social Media Marketing</h3>
                    <p>Complete social media management and strategy for Facebook, Instagram, TikTok to boost your online presence.</p>
                    <ul class="service-features">
                        <li>Content Strategy</li>
                        <li>Community Management</li>
                        <li>Performance Analytics</li>
                    </ul>
                </div>

                <!-- Service 2 -->
                <div class="service-card">
                    <div class="service-icon">
                        <i class="fas fa-bullseye"></i>
                    </div>
                    <h3>Meta Ads Management</h3>
                    <p>Targeted Facebook and Instagram advertising campaigns to generate leads and increase conversions.</p>
                    <ul class="service-features">
                        <li>Ad Creation</li>
                        <li>Audience Targeting</li>
                        <li>ROI Optimization</li>
                    </ul>
                </div>

                <!-- Service 3 -->
                <div class="service-card">
                    <div class="service-icon">
                        <i class="fas fa-paint-brush"></i>
                    </div>
                    <h3>Graphic Designing</h3>
                    <p>Creative design solutions including logos, social media graphics, brochures, and business cards.</p>
                    <ul class="service-features">
                        <li>Logo Design</li>
                        <li>Brand Identity</li>
                        <li>Marketing Materials</li>
                    </ul>
                </div>

                <!-- Service 4 -->
                <div class="service-card">
                    <div class="service-icon">
                        <i class="fas fa-laptop-code"></i>
                    </div>
                    <h3>Web & App Development</h3>
                    <p>Responsive websites and custom web applications built with modern technologies and frameworks.</p>
                    <ul class="service-features">
                        <li>Responsive Design</li>
                        <li>Custom Development</li>
                        <li>Maintenance & Support</li>
                    </ul>
                </div>

                <!-- Service 5 -->
                <div class="service-card">
                    <div class="service-icon">
                        <i class="fas fa-shield-alt"></i>
                    </div>
                    <h3>Web Pentesting</h3>
                    <p>Comprehensive security assessment and vulnerability testing to protect your digital assets.</p>
                    <ul class="service-features">
                        <li>Security Auditing</li>
                        <li>Vulnerability Assessment</li>
                        <li>Penetration Testing</li>
                    </ul>
                </div>

                <!-- Service 6 -->
                <div class="service-card">
                    <div class="service-icon">
                        <i class="fas fa-search"></i>
                    </div>
                    <h3>SEO Optimization</h3>
                    <p>Search engine optimization to improve your website's visibility and drive organic traffic.</p>
                    <ul class="service-features">
                        <li>Keyword Research</li>
                        <li>On-Page SEO</li>
                        <li>Performance Tracking</li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <!-- Portfolio Section -->
    <section id="portfolio" class="portfolio">
        <div class="container">
            <h2 class="section-title">My Portfolio</h2>
            <p class="section-subtitle">Check out some of my recent projects</p>
            
            <div class="portfolio-filter">
                <button class="filter-btn active" data-filter="all">All</button>
                <button class="filter-btn" data-filter="web">Web Development</button>
                <button class="filter-btn" data-filter="graphic">Graphic Design</button>
                <button class="filter-btn" data-filter="marketing">Marketing</button>
            </div>
            
            <div class="portfolio-grid">
                <div class="portfolio-item" data-category="web">
                    <img src="https://via.placeholder.com/400x300/4f46e5/ffffff?text=E-Commerce+Website" alt="E-Commerce Project">
                    <div class="portfolio-overlay">
                        <h3>E-Commerce Store</h3>
                        <p>Full-stack development with payment integration</p>
                        <a href="#" class="portfolio-link">View Project</a>
                    </div>
                </div>
                
                <div class="portfolio-item" data-category="graphic">
                    <img src="https://via.placeholder.com/400x300/10b981/ffffff?text=Brand+Identity" alt="Brand Design">
                    <div class="portfolio-overlay">
                        <h3>Brand Identity</h3>
                        <p>Complete logo and branding package</p>
                        <a href="#" class="portfolio-link">View Project</a>
                    </div>
                </div>
                
                <div class="portfolio-item" data-category="marketing">
                    <img src="https://via.placeholder.com/400x300/f59e0b/ffffff?text=Social+Media+Campaign" alt="Social Media Campaign">
                    <div class="portfolio-overlay">
                        <h3>Social Media Campaign</h3>
                        <p>3-month campaign with 200% engagement growth</p>
                        <a href="#" class="portfolio-link">View Project</a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="about">
        <div class="container">
            <div class="about-grid">
                <div class="about-content">
                    <h2 class="section-title">About Me</h2>
                    <p>I'm a passionate freelance digital expert with over 5 years of experience helping businesses establish and grow their online presence. My mission is to deliver high-quality, results-driven solutions that help my clients achieve their business goals.</p>
                    
                    <div class="skills">
                        <h3>My Skills</h3>
                        <div class="skill-item">
                            <span>Web Development</span>
                            <div class="skill-bar">
                                <div class="skill-progress" data-width="95%"></div>
                            </div>
                        </div>
                        <div class="skill-item">
                            <span>Digital Marketing</span>
                            <div class="skill-bar">
                                <div class="skill-progress" data-width="90%"></div>
                            </div>
                        </div>
                        <div class="skill-item">
                            <span>Graphic Design</span>
                            <div class="skill-bar">
                                <div class="skill-progress" data-width="85%"></div>
                            </div>
                        </div>
                        <div class="skill-item">
                            <span>SEO Optimization</span>
                            <div class="skill-bar">
                                <div class="skill-progress" data-width="88%"></div>
                            </div>
                        </div>
                    </div>
                </div>
                
                <div class="about-image">
                    <img src="https://via.placeholder.com/400x500/6366f1/ffffff?text=Professional+Photo" alt="Professional Photo">
                </div>
            </div>
        </div>
    </section>

    <!-- Testimonials Section -->
    <section id="testimonials" class="testimonials">
        <div class="container">
            <h2 class="section-title">Client Reviews</h2>
            <p class="section-subtitle">What my clients say about my work</p>
            
            <div class="testimonials-grid">
                <div class="testimonial-card">
                    <div class="testimonial-content">
                        <p>"Outstanding work! Our website traffic increased by 300% after implementing their SEO strategies."</p>
                    </div>
                    <div class="testimonial-author">
                        <h4>Sarah Johnson</h4>
                        <p>CEO, TechStart Inc.</p>
                    </div>
                </div>
                
                <div class="testimonial-card">
                    <div class="testimonial-content">
                        <p>"The social media campaign generated over 500 qualified leads in just one month. Highly recommended!"</p>
                    </div>
                    <div class="testimonial-author">
                        <h4>Mike Chen</h4>
                        <p>Marketing Director</p>
                    </div>
                </div>
                
                <div class="testimonial-card">
                    <div class="testimonial-content">
                        <p>"Professional, timely, and exceeded our expectations. The web application works perfectly."</p>
                    </div>
                    <div class="testimonial-author">
                        <h4>Emily Davis</h4>
                        <p>Startup Founder</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="contact">
        <div class="container">
            <h2 class="section-title">Get In Touch</h2>
            <p class="section-subtitle">Let's discuss your project and take your business to the next level</p>
            
            <div class="contact-grid">
                <div class="contact-info">
                    <div class="contact-item">
                        <i class="fas fa-envelope"></i>
                        <div>
                            <h3>Email</h3>
                            <p>contact@digitalsolutions.com</p>
                        </div>
                    </div>
                    
                    <div class="contact-item">
                        <i class="fas fa-phone"></i>
                        <div>
                            <h3>Phone</h3>
                            <p>+92 300 1234567</p>
                        </div>
                    </div>
                    
                    <div class="contact-item">
                        <i class="fas fa-map-marker-alt"></i>
                        <div>
                            <h3>Location</h3>
                            <p>Karachi, Pakistan</p>
                        </div>
                    </div>
                    
                    <div class="social-links">
                        <a href="#"><i class="fab fa-facebook"></i></a>
                        <a href="#"><i class="fab fa-twitter"></i></a>
                        <a href="#"><i class="fab fa-linkedin"></i></a>
                        <a href="#"><i class="fab fa-instagram"></i></a>
                    </div>
                </div>
                
                <div class="contact-form">
                    <form id="contactForm">
                        <div class="form-group">
                            <input type="text" id="name" name="name" placeholder="Your Name" required>
                        </div>
                        <div class="form-group">
                            <input type="email" id="email" name="email" placeholder="Your Email" required>
                        </div>
                        <div class="form-group">
                            <input type="text" id="subject" name="subject" placeholder="Subject" required>
                        </div>
                        <div class="form-group">
                            <textarea id="message" name="message" placeholder="Your Message" rows="5" required></textarea>
                        </div>
                        <button type="submit" class="btn btn-primary">Send Message</button>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="footer">
        <div class="container">
            <div class="footer-content">
                <p>&copy; 2024 Digital Solutions Hub. All rights reserved.</p>
                <p>Professional IT Services & Digital Marketing</p>
            </div>
        </div>
    </footer>

    <script src="script.js"></script>
</body>
</html>
