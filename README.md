# staticwebsite
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Static Website</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
  <style>
      * {
          margin: 0;
          padding: 0;
          box-sizing: border-box;
      }

      body {
          font-family: 'Times New Roman', Times, serif;
      }

      .nav {
          background-color: #333;
          padding: 1rem;
          position: fixed;
          width: 100%;
          top: 0;
      }

      .nav-list {
          list-style-type: none;
          display: flex;
          gap: 2rem;
          justify-content: flex-end;
          margin-right: 2rem;
      }

      .nav-items {
          color: white;
          text-transform: capitalize;
          cursor: pointer;
      }

      .hero {
          height: 100vh;
          background: linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.5)), url('https://images.unsplash.com/photo-1492571350019-22de08371fd3');
          background-size: cover;
          background-position: center;
          display: flex;
          align-items: center;
          justify-content: center;
          color: white;
          text-align: center;
      }

      .hero-content h1 {
          font-size: 3.5rem;
          margin-bottom: 1rem;
      }

      .target-section {
          padding: 4rem 2rem;
          background-color: #f5f5f5;
      }

      .target-content {
          max-width: 1200px;
          margin: 0 auto;
      }

      .contact-section {
          padding: 4rem 2rem;
          background-color: #333;
          color: white;
      }

      .contact-content {
          max-width: 1200px;
          margin: 0 auto;
          text-align: center;
      }

      .social-icons {
          margin-top: 2rem;
      }

      .social-icons i {
          font-size: 2rem;
          margin: 0 1rem;
          cursor: pointer;
      }
  </style>
</head>
<body>
  <nav class="nav">
      <ul class="nav-list">
          <li class="nav-items">Home</li>
          <li class="nav-items">Target</li>
          <li class="nav-items">Contact</li>
      </ul>
  </nav>

  <section class="hero">
      <div class="hero-content">
          <h1>Welcome to Our Website</h1>
          <p>Discover amazing possibilities with us</p>
      </div>
  </section>

  <section class="target-section">
      <div class="target-content">
          <h2>Our Target</h2>
          <p>We aim to provide exceptional services to our clients and create lasting impact in the industry.</p>
      </div>
  </section>

  <section class="contact-section">
      <div class="contact-content">
          <h2>Contact Us</h2>
          <p>Email: contact@example.com</p>
          <p>Phone: +1 234 567 890</p>
          <div class="social-icons">
              <i class="fa fa-facebook"></i>
              <i class="fa fa-twitter"></i>
              <i class="fa fa-instagram"></i>
              <i class="fa fa-linkedin"></i>
          </div>
      </div>
  </section>
</body>
</html>
