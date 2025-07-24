<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Mary Locher – ACLU Web Demo</title>
<style>
  @import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap');

  /* Reset & base */
  * {
    box-sizing: border-box;
  }
  body {
    margin: 0;
    font-family: 'Inter', sans-serif;
    background: #f0f4f8;
    color: #222;
    line-height: 1.65;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
  }

  /* Container */
  main {
    max-width: 720px;
    margin: 3rem auto;
    background: #fff;
    border-radius: 12px;
    box-shadow: 0 12px 25px rgba(0,0,0,0.1);
    padding: 3rem 2.5rem;
    animation: fadeIn 1s ease forwards;
  }

  /* Header */
  header {
    background: #00437a;
    color: white;
    padding: 5rem 2rem 3rem;
    text-align: center;
    box-shadow: 0 8px 15px rgba(0,0,0,0.15);
    border-bottom-left-radius: 12px;
    border-bottom-right-radius: 12px;
  }
  header h1 {
    margin: 0;
    font-weight: 700;
    font-size: 3rem;
    letter-spacing: 0.03em;
    text-transform: uppercase;
    text-shadow: 1px 1px 3px rgba(0,0,0,0.3);
  }
  header p {
    font-weight: 500;
    font-size: 1.3rem;
    margin-top: 0.7rem;
    letter-spacing: 0.02em;
    font-style: italic;
    opacity: 0.9;
  }

  /* Sections */
  section {
    margin-bottom: 2.5rem;
  }
  h2 {
    color: #00437a;
    font-weight: 700;
    font-size: 1.9rem;
    margin-bottom: 1rem;
    border-bottom: 3px solid #0073e6;
    padding-bottom: 0.3rem;
  }
  p {
    font-weight: 400;
    font-size: 1.05rem;
    margin-bottom: 1.2rem;
  }

  /* Tech badges */
  .tech-stack {
    display: flex;
    flex-wrap: wrap;
    gap: 0.8rem;
  }
  .badge {
    background: #e0ecff;
    color: #00437a;
    font-weight: 600;
    padding: 0.5rem 1.2rem;
    border-radius: 9999px;
    font-size: 0.95rem;
    box-shadow: 0 2px 5px rgba(0,67,122,0.2);
    user-select: none;
    transition: background-color 0.3s ease, color 0.3s ease;
    cursor: default;
  }
  .badge:hover {
    background-color: #00437a;
    color: #e0ecff;
  }

  /* Footer */
  footer {
    text-align: center;
    padding: 1.5rem 0;
    color: #666;
    font-weight: 400;
    font-size: 0.9rem;
    border-top: 1px solid #ddd;
    max-width: 720px;
    margin: 0 auto 2rem;
  }

  /* Responsive */
  @media (max-width: 600px) {
    main {
      padding: 2rem 1.5rem;
      margin: 2rem 1rem;
    }
    header h1 {
      font-size: 2.2rem;
    }
    header p {
      font-size: 1rem;
    }
    h2 {
      font-size: 1.6rem;
    }
  }

  /* Animation */
  @keyframes fadeIn {
    from {opacity: 0; transform: translateY(15px);}
    to {opacity: 1; transform: translateY(0);}
  }
</style>
</head>
<body>

<header>
  <h1>Mary Locher</h1>
  <p>Web builder, future law student, and believer in digital tools for justice.</p>
</header>

<main>
  <section>
    <h2>About Me</h2>
    <p>
      I’m Mary, a self-taught web enthusiast who believes websites should be clear, intentional, and inclusive. I’ve built educational programs, supported students with disabilities, and used code to amplify missions I care deeply about. This demo reflects my love for design with purpose and impact.
    </p>
  </section>

  <section>
    <h2>Why the ACLU</h2>
    <p>
      The ACLU’s mission resonates with every part of my journey — equity, access, and accountability. I want to use my technical skills not just to build websites, but to create momentum behind movements that matter. This internship feels like the perfect intersection of my values and vision.
    </p>
  </section>

  <section>
    <h2>Tech Stack</h2>
    <div class="tech-stack">
      <span class="badge">HTML5</span>
      <span class="badge">CSS3</span>
      <span class="badge">Python</span>
      <span class="badge">R</span>
      <span class="badge">SQL</span>
      <span class="badge">Scheme</span>
      <span class="badge">Git</span>
    </div>
  </section>
</main>

<footer>
  Made with care by Mary Locher | © 2025
</footer>

</body>
</html>


