# Joshua-bright-okon-
My professional Joshua bright okon <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Joshua Bright Okon - Mechanical Engineer & Music Enthusiast</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        /* Base Styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        :root {
            --primary: #4361ee;
            --secondary: #3f37c9;
            --accent: #4cc9f0;
            --light: #f8f9fa;
            --dark: #212529;
            --success: #4ade80;
        }
        
        body {
            background-color: #f0f2f5;
            color: var(--dark);
            line-height: 1.6;
        }
        
        .container {
            width: 90%;
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 15px;
        }
        
        section {
            padding: 80px 0;
        }
        
        h1, h2, h3 {
            margin-bottom: 20px;
        }
        
        h1 {
            font-size: 3.5rem;
        }
                h2 {
            font-size: 2.5rem;
            position: relative;
            display: inline-block;
            margin-bottom: 50px;
        }
        
        h2::after {
            content: '';
            position: absolute;
            bottom: -10px;
            left: 0;
            width: 60px;
            height: 4px;
            background: var(--primary);
            border-radius: 2px;
        }
        
        p {
            margin-bottom: 15px;
            font-size: 1.1rem;
        }
        
        .btn {
            display: inline-block;
            background: var(--primary);
            color: white;
            padding: 12px 30px;
            border-radius: 30px;
            text-decoration: none;
            font-weight: 600;
            transition: all 0.3s ease;
            border: 2px solid var(--primary);
        }
        
        .btn:hover {
            background: transparent;
            color: var(--primary);
            transform: translateY(-3px);
            box-shadow: 0 10px 20px rgba(0,0,0,0.1);
        }
        
        /* Header Styles */
        header {
            background: white;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
            position: fixed;
            width: 100%;
            top: 0;
            z-index: 1000;        }
        
        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 20px 0;
        }
        
        .logo {
            font-size: 1.8rem;
            font-weight: 700;
            color: var(--primary);
        }
        
        .nav-links {
            display: flex;
            list-style: none;
        }
        
        .nav-links li {
            margin-left: 30px;
        }
        
        .nav-links a {
            text-decoration: none;
            color: var(--dark);
            font-weight: 600;
            transition: color 0.3s;
        }
        
        .nav-links a:hover {
            color: var(--primary);
        }
        
        /* Hero Section */
        .hero {
            background: linear-gradient(135deg, #4361ee 0%, #3a0ca3 100%);
            color: white;
            min-height: 100vh;
            display: flex;
            align-items: center;
            padding-top: 80px;
        }
        
        .hero-content {
            display: flex;
            align-items: center;
            gap: 50px;
        }                .hero-text {
            flex: 1;
        }
        
        .hero-image {
            flex: 1;
            display: flex;
            justify-content: center;
        }
        
        .profile-img {
            width: 300px;
            height: 300px;
            border-radius: 50%;
            border: 5px solid white;
            object-fit: cover;
            box-shadow: 0 10px 30px rgba(0,0,0,0.2);
        }
        
        .hero h1 {
            margin-bottom: 20px;
            font-weight: 800;
        }
        
        .hero p {
            font-size: 1.2rem;
            margin-bottom: 30px;
            opacity: 0.9;
        }
        
        .social-links {
            display: flex;
            gap: 20px;
            margin-top: 30px;
        }
        
        .social-links a {
            display: flex;
            align-items: center;
            justify-content: center;
            width: 50px;
            height: 50px;
            border-radius: 50%;
            background: rgba(255,255,255,0.2);
            color: white;
            font-size: 1.5rem;
            transition: all 0.3s ease;
        }
        
        .social-links a:hover {            background: white;
            color: var(--primary);
            transform: translateY(-5px);
        }
        
        /* About Section */
        .about-content {
            display: flex;
            gap: 50px;
            align-items: center;
        }
        
        .about-text {
            flex: 2;
        }
        
        .about-stats {
            flex: 1;
            background: white;
            padding: 30px;
            border-radius: 15px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.05);
        }
        
        .stat-item {
            margin-bottom: 20px;
        }
        
        .stat-value {
            font-size: 2.5rem;
            font-weight: 700;
            color: var(--primary);
        }
        
        /* Skills Section */
        .skills-container {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
            gap: 30px;
        }
        
        .skill-card {
            background: white;
            padding: 30px;
            border-radius: 15px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.05);
            text-align: center;
            transition: transform 0.3s ease;
        }        
        .skill-card:hover {            transform: translateY(-10px);
        }
        
        .skill-icon {
            font-size: 3rem;
            color: var(--primary);
            margin-bottom: 20px;
        }
        
        /* Contact Section */
        .contact-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 50px;
        }
        
        .contact-info {
            display: flex;
            flex-direction: column;
            gap: 25px;
        }
        
        .contact-item {
            display: flex;
            gap: 15px;
        }
        
        .contact-icon {
            width: 50px;
            height: 50px;
            background: var(--primary);
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            font-size: 1.2rem;
        }
        
        .contact-form {
            background: white;
            padding: 40px;
            border-radius: 15px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.05);
        }
        
        .form-group {
            margin-bottom: 20px;
        }
                .form-group label {
            display: block;
            margin-bottom: 8px;
            font-weight: 600;
        }
        
        .form-control {
            width: 100%;
            padding: 12px 15px;
            border: 1px solid #ddd;
            border-radius: 8px;
            font-size: 1rem;
            transition: border 0.3s;
        }
        
        .form-control:focus {
            outline: none;
            border-color: var(--primary);
        }
        
        textarea.form-control {
            min-height: 150px;
            resize: vertical;
        }
        
        /* Footer */
        footer {
            background: var(--dark);
            color: white;
            padding: 40px 0;
            text-align: center;
        }
        
        .footer-content {
            display: flex;
            flex-direction: column;
            align-items: center;
        }
        
        .footer-logo {
            font-size: 2rem;
            font-weight: 700;
            margin-bottom: 20px;
            color: var(--accent);
        }
        
        .copyright {
            margin-top: 20px;
            opacity: 0.7;
        }        
        /* Responsive Design */
        @media (max-width: 992px) {
            .hero-content, .about-content {
                flex-direction: column;
                text-align: center;
            }
            
            .hero-image {
                order: -1;
                margin-bottom: 30px;
            }
            
            .social-links {
                justify-content: center;
            }
            
            h1 {
                font-size: 2.8rem;
            }
            
            h2 {
                font-size: 2.2rem;
            }
        }
        
        @media (max-width: 768px) {
            .nav-links {
                display: none;
            }
            
            h1 {
                font-size: 2.3rem;
            }
            
            .profile-img {
                width: 250px;
                height: 250px;
            }
        }
    </style>
</head>
<body>
    <!-- Header -->
    <header>
        <div class="container">
            <nav>
                <div class="logo">Joshua</div>                
                <ul class="nav-links">
                    <li><a href="#about">About</a></li>                    <li><a href="#skills">Skills</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="hero" id="home">
        <div class="container">
            <div class="hero-content">
                <div class="hero-text">
                    <h1>Hello, I'm <span style="color:#4cc9f0">Joshua Bright Okon</span></h1>
                    <p>A passionate Mechanical Engineer from Uyo, Akwa Ibom State — where engineering meets rhythm. I believe <strong>music is life</strong>, and I bring that energy into every project.</p>
                    <a href="#contact" class="btn">Get In Touch</a>
                    <div class="social-links">
                        <a href="https://www.facebook.com/profile.php?id=61581080272823&mibextid=ZbWKwL" target="_blank"><i class="fab fa-facebook-f"></i></a>
                        <a href="https://x.com/Joshua29854" target="_blank"><i class="fab fa-x-twitter"></i></a>
                        <a href="https://www.instagram.com/joshuafutureartists?igsh=NzJjYmFhaWkwdm5w" target="_blank"><i class="fab fa-instagram"></i></a>
                    </div>
                </div>
                <div class="hero-image">
                    <!-- Your photo hosted securely -->
                    <img src="https://i.imgur.com/9GvKQzP.jpg" alt="Joshua Bright Okon" class="profile-img">
                </div>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about">
        <div class="container">
            <h2>About Me</h2>
            <div class="about-content">
                <div class="about-text">
                    <p>I love music — music is life! As a Mechanical Engineering professional, I blend technical precision with creative expression. My work is driven by curiosity, discipline, and the belief that innovation thrives at the intersection of logic and art.</p>
                    <p>Based in Uyo, Akwa Ibom State, I’m committed to delivering reliable engineering solutions while staying connected to my roots and my passion for music — whether through performance, production, or simply letting the rhythm guide my focus.</p>
                    <a href="#" class="btn">Download CV</a>
                </div>
                <div class="about-stats">
                    <div class="stat-item">
                        <div class="stat-value">3+</div>
                        <div>Years Experience</div>                    
                    </div>
                    <div class="stat-item">
                        <div class="stat-value">15+</div>
                        <div>Projects Completed</div>
                    </div>
                    <div class="stat-item">
                        <div class="stat-value">10+</div>                        <div>Happy Clients / Collaborators</div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Skills Section -->
    <section id="skills" style="background:#f8f9fa">
        <div class="container">
            <h2>My Skills</h2>
            <div class="skills-container">
                <div class="skill-card">
                    <div class="skill-icon"><i class="fas fa-cogs"></i></div>
                    <h3>Mechanical Design</h3>
                    <p>AutoCAD, SolidWorks, Technical Drawings</p>
                </div>
                <div class="skill-card">
                    <div class="skill-icon"><i class="fas fa-thermometer-half"></i></div>
                    <h3>Thermodynamics & HVAC</h3>
                    <p>Heat Transfer, Energy Systems, Refrigeration</p>
                </div>
                <div class="skill-card">
                    <div class="skill-icon"><i class="fas fa-project-diagram"></i></div>
                    <h3>Project Execution</h3>
                    <p>Planning, QA/QC, Field Supervision</p>
                </div>
                <div class="skill-card">
                    <div class="skill-icon"><i class="fas fa-music"></i></div>
                    <h3>Music & Audio</h3>
                    <p>Composition, Performance, Sound Engineering</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact">
        <div class="container">
            <h2>Get In Touch</h2>
            <div class="contact-container">
                <div class="contact-info">                    
                    <div class="contact-item">
                        <div class="contact-icon"><i class="fas fa-envelope"></i></div>
                        <div>
                            <h3>Email</h3>
                            <p>okonjoshua250@gmail.com</p>
                        </div>
                    </div>
                    <div class="contact-item">                        <div class="contact-icon"><i class="fas fa-map-marker-alt"></i></div>
                        <div>
                            <h3>Location</h3>
                            <p>12 Itighe Street, Off Ikot Ekpene Road, Uyo, Akwa Ibom State, Nigeria</p>
                        </div>
                    </div>
                    <div class="contact-item">
                        <div class="contact-icon"><i class="fas fa-phone"></i></div>
                        <div>
                            <h3>Phone</h3>
                            <p>+234 701 875 8811</p>
                        </div>
                    </div>
                </div>
                <div class="contact-form">
                    <form>
                        <div class="form-group">
                            <label for="name">Name</label>
                            <input type="text" id="name" class="form-control" required>
                        </div>
                        <div class="form-group">
                            <label for="email">Email</label>
                            <input type="email" id="email" class="form-control" required>
                        </div>
                        <div class="form-group">
                            <label for="message">Message</label>
                            <textarea id="message" class="form-control" required></textarea>
                        </div>
                        <button type="submit" class="btn">Send Message</button>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <div class="container">
            <div class="footer-content">
                <div class="footer-logo">Joshua</div>
                <p>Engineering with purpose • Music with soul</p>
                <div class="social-links">                    
                    <a href="https://www.facebook.com/profile.php?id=61581080272823&mibextid=ZbWKwL" target="_blank"><i class="fab fa-facebook-f"></i></a>
                    <a href="https://x.com/Joshua29854" target="_blank"><i class="fab fa-x-twitter"></i></a>
                    <a href="https://www.instagram.com/joshuafutureartists?igsh=NzJjYmFhaWkwdm5w" target="_blank"><i class="fab fa-instagram"></i></a>
                </div>
                <div class="copyright">
                    &copy; 2026 Joshua Bright Okon. All Rights Reserved.
                </div>
            </div>        </div>
    </footer>

    <script>
        // Smooth scrolling
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });

        // Form handling
        const form = document.querySelector('form');
        if(form) {
            form.addEventListener('submit', (e) => {
                e.preventDefault();
                alert('Thank you for your message! I will get back to you soon.');
                form.reset();
            });
        }
    </script>
</body>
</html>
