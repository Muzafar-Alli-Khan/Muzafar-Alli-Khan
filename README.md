<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Muzafar Alli Khan | Profile</title>
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <style>
    body {
      margin: 0;
      background-color: #0f0f0f;
      color: white;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      height: 100vh;
      overflow: hidden;
    }

    .fade-in {
      opacity: 0;
      transform: translateY(30px);
      animation: fadeInUp 1s ease-out forwards;
    }

    .fade-in:nth-child(1) { animation-delay: 0.5s; }
    .fade-in:nth-child(2) { animation-delay: 2s; }
    .fade-in:nth-child(3) { animation-delay: 4s; }
    .fade-in:nth-child(4) { animation-delay: 6s; }

    @keyframes fadeInUp {
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }

    .tag {
      display: inline-block;
      background: #2b2b2b;
      padding: 5px 10px;
      margin: 4px;
      border-radius: 10px;
      font-family: monospace;
      font-size: 14px;
    }

    h1, h2, h3, p {
      margin: 10px 0;
      text-align: center;
    }

    a {
      color: #00bfff;
      text-decoration: none;
    }

    .tools {
      margin-top: 30px;
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 10px;
      animation: fadeInUp 1s ease-out forwards;
      animation-delay: 8s;
      opacity: 0;
    }

    .tools img {
      height: 40px;
      border-radius: 6px;
      padding: 4px;
      background: white;
    }

    .section {
      margin-top: 20px;
      text-align: center;
    }
  </style>
</head>
<body>
  <h1 class="fade-in">👋 This is <span style="color:#00bfff;">Muzafar Alli Khan</span></h1>
  <h2 class="fade-in">✨ Welcome to my Profile ✨</h2>

  <div class="fade-in section">
    <p><strong>📡 Currently working on:</strong></p>
    <div>
      <span class="tag">Spring Boot</span>
      <span class="tag">JDBC</span>
      <span class="tag">Multithreading</span>
      <span class="tag">System Design</span>
    </div>

    <p><strong>🌱 Exploring:</strong></p>
    <div>
      <span class="tag">Microservices</span>
      <span class="tag">Spring Security</span>
      <span class="tag">Design Patterns</span>
    </div>

    <p><strong>📬 Reach me at:</strong></p>
    <p><a href="mailto:muzafar005@gmail.com">muzafar005@gmail.com</a></p>
  </div>

  <div class="tools">
    <!-- Simulated Tech Stack icons (replace src with actual ones if needed) -->
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" alt="Java" />
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/spring/spring-original.svg" alt="Spring Boot" />
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" alt="MySQL" />
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" alt="JavaScript" />
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" alt="HTML" />
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" alt="CSS" />
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" alt="Git" />
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" alt="GitHub" />
  </div>
</body>
</html>
