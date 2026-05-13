<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Responsive Portfolio Website</title>  <!-- Bootstrap CSS -->  <link
    href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css"
    rel="stylesheet"
  />  <!-- Bootstrap Icons -->  <link
    rel="stylesheet"
    href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css"
  />  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      scroll-behavior: smooth;
    }

    body {
      font-family: Arial, sans-serif;
      background-color: #f8f9fa;
      color: #333;
    }

    .navbar {
      background-color: #0d6efd;
    }

    .navbar-brand,
    .nav-link {
      color: white !important;
      font-weight: 500;
    }

    .nav-link:hover {
      color: #dbeafe !important;
    }

    section {
      padding: 80px 0;
    }

    #home {
      min-height: 100vh;
      display: flex;
      align-items: center;
      background: linear-gradient(to right, #0d6efd, #4f9bff);
      color: white;
      text-align: center;
    }

    .home-content h1 {
      font-size: 3rem;
      font-weight: bold;
    }

    .home-content p {
      font-size: 1.2rem;
      margin-top: 15px;
    }

    .btn-custom {
      background-color: white;
      color: #0d6efd;
      border-radius: 30px;
      padding: 10px 25px;
      font-weight: bold;
      margin-top: 20px;
    }

    .btn-custom:hover {
      background-color: #e9ecef;
    }

    .section-title {
      text-align: center;
      margin-bottom: 50px;
      font-weight: bold;
      color: #0d6efd;
    }

    .skill-card,
    .project-card,
    .contact-card {
      background: white;
      border-radius: 15px;
      padding: 25px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.1);
      transition: 0.3s;
      height: 100%;
    }

    .skill-card:hover,
    .project-card:hover,
    .contact-card:hover {
      transform: translateY(-5px);
    }

    .skill-icon {
      font-size: 40px;
      color: #0d6efd;
      margin-bottom: 15px;
    }

    footer {
      background-color: #0d6efd;
      color: white;
      text-align: center;
      padding: 20px;
    }

    @media (max-width: 768px) {
      .home-content h1 {
        font-size: 2.2rem;
      }

      .home-content p {
        font-size: 1rem;
      }
    }
  </style></head>
<body>  <!-- Navbar -->  <nav class="navbar navbar-expand-lg fixed-top shadow">
    <div class="container">
      <a class="navbar-brand" href="#home">My Portfolio</a><button
    class="navbar-toggler bg-light"
    type="button"
    data-bs-toggle="collapse"
    data-bs-target="#navbarNav"
  >
    <span class="navbar-toggler-icon"></span>
  </button>

  <div class="collapse navbar-collapse" id="navbarNav">
    <ul class="navbar-nav ms-auto">
      <li class="nav-item">
        <a class="nav-link" href="#home">Home</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#skills">Skills</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#projects">Projects</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#contact">Contact</a>
      </li>
    </ul>
  </div>
</div>

  </nav>  <!-- Home Section -->  <section id="home">
    <div class="container">
      <div class="home-content">
        <h1>Hello, I'm Swetha</h1>
        <p>
          Web Developer | Frontend Designer | Student
        </p>
        <a href="#projects" class="btn btn-custom">
          View Projects
        </a>
      </div>
    </div>
  </section>  <!-- Skills Section -->  <section id="skills">
    <div class="container">
      <h2 class="section-title">My Skills</h2><div class="row g-4">
    <div class="col-md-4">
      <div class="skill-card text-center">
        <div class="skill-icon">
          <i class="bi bi-filetype-html"></i>
        </div>
        <h4>HTML</h4>
        <p>
          Creating structured and semantic webpages.
        </p>
      </div>
    </div>

    <div class="col-md-4">
      <div class="skill-card text-center">
        <div class="skill-icon">
          <i class="bi bi-filetype-css"></i>
        </div>
        <h4>CSS</h4>
        <p>
          Responsive styling using Flexbox, Grid and Bootstrap.
        </p>
      </div>
    </div>

    <div class="col-md-4">
      <div class="skill-card text-center">
        <div class="skill-icon">
          <i class="bi bi-bootstrap"></i>
        </div>
        <h4>Bootstrap</h4>
        <p>
          Designing mobile-friendly and modern layouts.
        </p>
      </div>
    </div>
  </div>
</div>

  </section>  <!-- Projects Section -->  <section id="projects" class="bg-light">
    <div class="container">
      <h2 class="section-title">Projects</h2><div class="row g-4">
    <div class="col-md-4">
      <div class="project-card">
        <h4>Portfolio Website</h4>
        <p>
          A fully responsive personal portfolio website built using HTML, CSS and Bootstrap.
        </p>
      </div>
    </div>

    <div class="col-md-4">
      <div class="project-card">
        <h4>Landing Page</h4>
        <p>
          Modern landing page with responsive design and smooth scrolling.
        </p>
      </div>
    </div>

    <div class="col-md-4">
      <div class="project-card">
        <h4>Student Dashboard</h4>
        <p>
          Dashboard UI designed using Bootstrap cards and responsive grids.
        </p>
      </div>
    </div>
  </div>
</div>

  </section>  <!-- Contact Section -->  <section id="contact">
    <div class="container">
      <h2 class="section-title">Contact Me</h2><div class="row justify-content-center">
    <div class="col-md-6">
      <div class="contact-card text-center">
        <h4>Get In Touch</h4>
        <p>Email: swetha@example.com</p>
        <p>Phone: +91 98765 43210</p>

        <div class="mt-4 d-flex justify-content-center gap-3">
          <a href="#" class="btn btn-primary">
            <i class="bi bi-github"></i>
          </a>

          <a href="#" class="btn btn-primary">
            <i class="bi bi-linkedin"></i>
          </a>

          <a href="#" class="btn btn-primary">
            <i class="bi bi-instagram"></i>
          </a>
        </div>
      </div>
    </div>
  </div>
</div>

  </section>  <!-- Footer -->  <footer>
    <p>
      © 2026 Swetha Portfolio Website | All Rights Reserved
    </p>
  </footer>  <!-- Bootstrap JS -->  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script></body>
</html>
