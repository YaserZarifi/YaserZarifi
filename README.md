<div style="text-align: center; font-family: Arial, sans-serif;">
  <!-- Animated Gradient Background -->
  <div class="background"></div>

  <!-- Animated Title -->
  <h1 class="title">👋 Welcome to Mohammad Yaser Zarifi's GitHub Profile!</h1>

  <!-- About Section with Fade-In Animation -->
  <section class="about-section">
    <h2>💫 About Me:</h2>
    <p>👷 I’m currently studying **Computer Engineering** at Amirkabir University of Technology.</p>
    <p>🤝 I’m looking to collaborate on AI, Machine Learning, and Computer Architecture projects.</p>
    <p>👐 I’m looking for help with OS and Network-related research projects.</p>
    <p>🌱 I’m currently learning more about **Machine Learning** through a 3-month bootcamp by FTL Community (Frontier Tech Leaders).</p>
    <p>💬 Ask me about **Python, Django, SQL, or Embedded Systems.**</p>
    <p>⚡ Fun fact: I transitioned from urban planning and design to computer engineering!</p>
  </section>

  <!-- Social Links with Hover Animation -->
  <div class="socials">
    <a href="https://linkedin.com/in/mohammad-yaser-zarifi-2b16b0205" class="social-link">🔗 LinkedIn</a>
    <a href="mailto:yaserzarifi1378@gmail.com" class="social-link">📧 Email Me</a>
  </div>

  <!-- Tech Stack with Hover Effects -->
  <div class="tech-stack">
    <h2>💻 Tech Stack:</h2>
    <div class="badge">Python</div>
    <div class="badge">Django</div>
    <div class="badge">SQL</div>
    <div class="badge">Embedded Systems</div>
    <div class="badge">Java</div>
    <div class="badge">JavaFX</div>
    <div class="badge">Machine Learning</div>
    <div class="badge">MySQL</div>
  </div>

  <!-- GitHub Stats -->
  <div class="github-stats">
    <h2>📊 GitHub Stats:</h2>
    <img src="https://github-readme-stats.vercel.app/api?username=YaserZarifi&theme=onedark" alt="GitHub Stats" class="stat-image">
    <img src="https://github-readme-streak-stats.herokuapp.com/?user=YaserZarifi&theme=onedark" alt="GitHub Streak" class="stat-image">
    <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=YaserZarifi&layout=compact&theme=onedark" alt="Top Languages" class="stat-image">
  </div>
</div>

<!-- Add some custom CSS -->
<style>
  body {
    margin: 0;
    padding: 0;
    background-color: #121212;
    color: white;
    overflow-x: hidden;
  }

  .background {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: linear-gradient(-45deg, #ff9a9e, #fad0c4, #fad0c4, #fbc2eb);
    background-size: 400% 400%;
    animation: gradient 15s ease infinite;
    z-index: -1;
  }

  @keyframes gradient {
    0% { background-position: 0% 50%; }
    50% { background-position: 100% 50%; }
    100% { background-position: 0% 50%; }
  }

  .title {
    font-size: 2.5rem;
    animation: fadeIn 3s ease-in-out;
  }

  @keyframes fadeIn {
    from { opacity: 0; transform: translateY(-20px); }
    to { opacity: 1; transform: translateY(0); }
  }

  .socials a {
    display: inline-block;
    margin: 10px;
    color: white;
    text-decoration: none;
    font-size: 1.2rem;
    transition: transform 0.3s;
  }

  .socials a:hover {
    transform: scale(1.1);
    color: #ff9a9e;
  }

  .badge {
    display: inline-block;
    margin: 5px;
    padding: 10px 15px;
    background: rgba(255, 255, 255, 0.1);
    border-radius: 5px;
    font-size: 0.9rem;
    transition: transform 0.3s, background-color 0.3s;
  }

  .badge:hover {
    transform: scale(1.1);
    background-color: #ff9a9e;
    color: #121212;
  }

  .stat-image {
    max-width: 400px;
    margin: 20px;
    border-radius: 10px;
    transition: transform 0.3s;
  }

  .stat-image:hover {
    transform: scale(1.05);
    box-shadow: 0 4px 15px rgba(0, 0, 0, 0.5);
  }
</style>
