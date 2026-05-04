<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact - My ResourceMan</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <!-- Header -->
    <header>
        <nav>
            <div class="logo">My ResourceMan</div>
            <ul class="nav-links">
                <li><a href="index.html">Home</a></li>
                <li><a href="features.html">Features</a></li>
                <li><a href="contact.html" class="active">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- Contact Hero -->
    <section class="hero contact-hero">
        <div class="container">
            <h1>Get In Touch</h1>
            <p>Let's discuss your project</p>
        </div>
    </section>

    <!-- Contact Content -->
    <section class="contact-section">
        <div class="container">
            <div class="contact-grid">
                <div class="contact-info">
                    <h2>Send us a message</h2>
                    <p>Fill out the form below and we'll get back to you within 24 hours.</p>
                    
                    <div class="contact-details">
                        <div class="contact-item">
                            <span>📧</span>
                            <div>
                                <h4>Email</h4>
                                <p>safety88888@gmail.com</p>
                            </div>
                        </div>
                        <div class="contact-item">
                            <span>📱</span>
                            <div>
                                <h4>Phone</h4>
                                <p></p>
                            </div>
                        </div>
                    </div>
                </div>
                
                <form class="contact-form">
                    <div class="form-group">
                        <input type="text" placeholder="Your Name" required>
                    </div>
                    <div class="form-group">
                        <input type="email" placeholder="Your Email" required>
                    </div>
                    <div class="form-group">
                        <input type="text" placeholder="Subject" required>
                    </div>
                    <div class="form-group">
                        <textarea rows="6" placeholder="Your Message" required></textarea>
                    </div>
                    <button type="submit" class="btn btn-primary">Send Message</button>
                </form>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <div class="container">
            <p>&copy; 2024 MyWebsite. All rights reserved.</p>
        </div>
    </footer>

    <script>
        document.querySelector('.contact-form').addEventListener('submit', function(e) {
            e.preventDefault();
            alert('Thank you! Your message has been sent. We\'ll respond within 24 hours.');
            this.reset();
        });
    </script>
</body>
</html>
