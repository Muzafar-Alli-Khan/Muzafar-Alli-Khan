<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Muzafar Alli Khan | Java Developer</title>
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <style>
    body {
      margin: 0;
      background: #0f0f0f;
      color: #fff;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      height: 100vh;
      overflow: hidden;
    }

    h1, h2, p {
      text-align: center;
      margin: 10px;
    }

    #typing1, #typing2 {
      font-size: 24px;
      min-height: 40px;
      color: #00bfff;
      white-space: nowrap;
      overflow: hidden;
      border-right: 2px solid #00bfff;
      width: 0;
    }

    .fade {
      opacity: 0;
      transition: opacity 1s ease-in;
    }

    .show {
      opacity: 1;
    }

    .tag {
      background: #2b2b2b;
      color: #fff;
      padding: 5px 10px;
      margin: 4px;
      border-radius: 10px;
      font-family: monospace;
      font-size: 14px;
      display: inline-block;
    }

    .tools {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 10px;
      margin-top: 20px;
    }

    .tools img {
      height: 40px;
      background: white;
      border-radius: 6px;
      padding: 4px;
    }

    a {
      color: #00bfff;
      text-decoration: none;
    }

    #profile {
      text-align: center;
      margin-top: 20px;
    }
  </style>
</head>
<body>

  <h1 id="typing1"></h1>
  <h2 id="typing2"></h2>

  <div id="profile" class="fade">
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

    <div class="tools">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" alt="Java" />
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/spring/spring-original.svg" alt="Spring Boot" />
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" alt="MySQL" />
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" alt="JavaScript" />
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" alt="HTML" />
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" alt="CSS" />
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" alt="Git" />
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" alt="GitHub" />
    </div>
  </div>

  <script>
    const text1 = "👋 This is Muzafar";
    const text2 = "✨ Welcome to my Profile ✨";

    let i = 0;
    let j = 0;
    const speed = 100;

    function typeFirstLine() {
      if (i < text1.length) {
        document.getElementById("typing1").style.width = i + "ch";
        document.getElementById("typing1").textContent += text1.charAt(i);
        i++;
        setTimeout(typeFirstLine, speed);
      } else {
        setTimeout(typeSecondLine, 1000);
      }
    }

    function typeSecondLine() {
      if (j < text2.length) {
        document.getElementById("typing2").style.width = j + "ch";
        document.getElementById("typing2").textContent += text2.charAt(j);
        j++;
        setTimeout(typeSecondLine, speed);
      } else {
        setTimeout(() => {
          document.getElementById("profile").classList.add("show");
        }, 800);
      }
    }

    window.onload = typeFirstLine;
  </script>

</body>
</html>
