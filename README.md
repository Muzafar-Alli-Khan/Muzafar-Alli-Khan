<div align="center">

<!-- Centered JAVA ASCII Art -->
<pre style="margin:0;">
     ██╗ █████╗ ██╗   ██╗ █████╗ 
     ██║██╔══██╗██║   ██║██╔══██╗
     ██║███████║██║   ██║███████║
██   ██║██╔══██║╚██╗ ██╔╝██╔══██║
╚█████╔╝██║  ██║ ╚████╔╝ ██║  ██║
 ╚════╝ ╚═╝  ╚═╝  ╚═══╝  ╚═╝  ╚═╝
</pre>

<!-- Dynamic Timezone Badge -->
<img src="https://img.shields.io/badge/Dynamic%20Time-IST_%E2%8F%B0_%23FF6B6B-blue?style=for-the-badge&logo=google-chrome&logoColor=white&labelColor=gray&color=blue" alt="Real Time Clock">

<!-- Animated Name -->
<h2 style="margin-bottom: 5px;">
  <a href="https://github.com/MuzafarAliKhan" style="text-decoration: none; color: inherit;">
    <span id="typed-name" style="color: #FF0608;"></span>
  </a>
</h2>

<!-- Pulsing Title -->
<h3 style="animation: pulse 2s infinite; color: #FF0608; margin-top: 5px;">Full Stack Java Developer</h3>

<!-- Profile Links -->
<p align="center">
  <a href="https://www.linkedin.com/in/muzafar-alli-khan/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
  </a>
  <a href="https://leetcode.com/u/Muzafar-Alli-Khan/" target="_blank">
    <img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode">
  </a>
  <a href="https://github.com/MuzafarAliKhan" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
  </a>
  <a href="mailto:your.email@example.com" target="_blank">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email">
  </a>
</p>

</div>

<style>
  /* Typing Animation */
  @keyframes typing {
    from { width: 0 }
    to { width: 100% }
  }
  
  /* Blinking Cursor */
  @keyframes blink-caret {
    from, to { border-color: transparent }
    50% { border-color: #FF0608 }
  }
  
  /* Pulsing Effect */
  @keyframes pulse {
    0% { transform: scale(1); opacity: 0.8; }
    50% { transform: scale(1.05); opacity: 1; }
    100% { transform: scale(1); opacity: 0.8; }
  }
  
  /* Name Styling */
  #typed-name {
    display: inline-block;
    overflow: hidden;
    border-right: 3px solid #FF0608;
    white-space: nowrap;
    animation: 
      typing 3.5s steps(40, end),
      blink-caret .75s step-end infinite;
  }
</style>

<script>
  // Typewriter effect for name
  document.addEventListener('DOMContentLoaded', function() {
    const name = "Muzafar Alli Khan";
    let i = 0;
    const speed = 150;
    
    function typeWriter() {
      if (i < name.length) {
        document.getElementById("typed-name").innerHTML += name.charAt(i);
        i++;
        setTimeout(typeWriter, speed);
      }
    }
    typeWriter();
  });
</script>
