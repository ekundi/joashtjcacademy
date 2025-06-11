<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Joash TJC Academy | Home</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: #f4f6f7;
      color: #333;
    }
    header, footer {
      background-color: #2c3e50;
      color: white;
      padding: 1rem 2rem;
    }
    .logo {
      font-size: 1.5rem;
      font-weight: bold;
    }
    nav ul {
      list-style: none;
      display: flex;
      gap: 1rem;
      padding: 0;
    }
    nav a {
      color: white;
      text-decoration: none;
    }
    nav a.active {
      border-bottom: 2px solid #1abc9c;
    }
    nav a:hover {
      color: #f39c12;
    }
    .hero {
      position: relative;
      background-image: url('https://via.placeholder.com/1200x400?text=Empowering+ICT+Education');
      background-size: cover;
      background-position: center;
      color: white;
      padding: 5rem 2rem;
      text-align: center;
      z-index: 1;
    }
    .hero::before {
      content: '';
      position: absolute;
      inset: 0;
      background-color: rgba(0, 0, 0, 0.5);
      z-index: 0;
    }
    .hero h1, .hero p, .hero a {
      position: relative;
      z-index: 1;
    }
    .hero h1 {
      font-size: 3rem;
      margin-bottom: 1rem;
    }
    .hero p {
      font-size: 1.2rem;
      margin-bottom: 2rem;
    }
    .hero a.button {
      background-color: #1abc9c;
      color: white;
      padding: 0.75rem 1.5rem;
      text-decoration: none;
      border-radius: 5px;
      font-weight: bold;
      transition: background-color 0.3s ease;
    }
    .hero a.button:hover {
      background-color: #16a085;
    }
    .intro, .courses, .contact {
      max-width: 900px;
      margin: auto;
      padding: 2rem;
      text-align: center;
    }
    .intro h2, .courses h2, .contact h2 {
      color: #1abc9c;
    }
    .features, .course-cards {
      display: flex;
      flex-wrap: wrap;
      gap: 2rem;
      justify-content: center;
      margin-top: 2rem;
    }
    .feature, .course-card {
      background: #fff;
      padding: 1.5rem;
      border-radius: 10px;
      width: 250px;
      box-shadow: 0 0 10px rgba(0,0,0,0.05);
    }
    .feature h3, .course-card h3 {
      color: #2c3e50;
      margin-bottom: 0.5rem;
    }
    .feature p, .course-card p {
      font-size: 0.95rem;
      color: #555;
    }
    .course-card a {
      display: inline-block;
      margin-top: 1rem;
      color: #1abc9c;
      text-decoration: none;
      font-weight: bold;
    }
    .course-card a:hover {
      text-decoration: underline;
    }
    .contact input, .contact textarea {
      width: 100%;
      padding: 0.75rem;
      margin: 0.5rem 0;
      border: 1px solid #ccc;
      border-radius: 5px;
    }
    .contact button {
      padding: 0.75rem 1.5rem;
      background-color: #1abc9c;
      color: white;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }
    .contact button:hover {
      background-color: #16a085;
    }
    footer p {
      text-align: center;
      margin: 0;
    }
  </style>
</head>
<body>
  <header>
    <div class="logo">Joash TJC Academy</div>
    <nav>
      <ul>
        <li><a href="#" class="active">Home</a></li>
        <li><a href="#courses">Courses</a></li>
        <li><a href="#success">Success</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <section class="hero">
    <h1>Welcome to Joash TJC Academy</h1>
    <p>Your Gateway to ICT Excellence</p>
    <a href="#courses" class="button">Get Started</a>
  </section>

  <section id="courses" class="courses">
    <h2>Our ICT Courses</h2>
    <div class="course-cards">
      <div class="course-card">
        <h3>Python Programming</h3>
        <p>Learn Python from beginner to advanced level with hands-on examples.</p>
        <a href="python-syllabus.html">View Syllabus</a>
      </div>
      <div class="course-card">
        <h3>Web Development</h3>
        <p>Master HTML, CSS, JavaScript, and build real-world web projects.</p>
        <a href="webdev-syllabus.html">View Syllabus</a>
      </div>
      <div class="course-card">
        <h3>Computer Packages</h3>
        <p>Get equipped with essential computer applications and typing skills.</p>
        <a href="packages-syllabus.html">View Syllabus</a>
      </div>
      <div class="course-card">
        <h3>Networking Essentials</h3>
        <p>Understand computer networks, configurations, protocols and security basics.</p>
        <a href="networking-syllabus.html">View Syllabus</a>
      </div>
    </div>
  </section>
</body>
</html>
