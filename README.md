<!DOCTYPE html>
<html>
<head>
<style>
  :root {
    --primary: #6b48ff;
    --secondary: #8f6aff;
    --text-primary: #2f363d;
    --text-secondary: #586069;
    --bg-light: #f6f8fa;
  }

  body {
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
    line-height: 1.6;
    margin: 0;
    padding: 20px;
    background: linear-gradient(120deg, var(--bg-light), #eef1f5);
    color: var(--text-primary);
  }

  .container {
    max-width: 1200px;
    margin: 0 auto;
  }

  .header {
    text-align: center;
    padding: 40px 20px;
    background: linear-gradient(135deg, var(--primary), var(--secondary));
    color: white;
    border-radius: 15px;
    margin-bottom: 30px;
    box-shadow: 0 4px 15px rgba(0,0,0,0.1);
  }

  .profile-views {
    background: white;
    padding: 8px 15px;
    border-radius: 20px;
    display: inline-block;
    margin: 10px 0;
    color: var(--text-secondary);
  }

  .section {
    background: white;
    padding: 25px;
    border-radius: 10px;
    margin-bottom: 25px;
    box-shadow: 0 2px 10px rgba(0,0,0,0.05);
  }

  .grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 20px;
  }

  .info-item {
    display: flex;
    align-items: flex-start;
    margin-bottom: 15px;
  }

  .info-item span {
    margin-right: 10px;
    color: var(--primary);
  }

  .tools-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(60px, 1fr));
    gap: 15px;
    margin-top: 20px;
  }

  .tool-item {
    display: flex;
    flex-direction: column;
    align-items: center;
    text-align: center;
    padding: 10px;
    border-radius: 8px;
    transition: transform 0.2s;
  }

  .tool-item:hover {
    transform: translateY(-5px);
    background: var(--bg-light);
  }

  .tool-item img {
    width: 40px;
    height: 40px;
    margin-bottom: 5px;
  }

  .stats {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 20px;
    margin-top: 25px;
  }

  .stats img {
    width: 100%;
    border-radius: 10px;
    box-shadow: 0 2px 10px rgba(0,0,0,0.05);
  }

  .connect {
    display: flex;
    gap: 15px;
    margin-top: 15px;
  }

  .connect a {
    display: flex;
    align-items: center;
    padding: 10px 20px;
    background: var(--bg-light);
    border-radius: 20px;
    text-decoration: none;
    color: var(--text-primary);
    transition: transform 0.2s;
  }

  .connect a:hover {
    transform: translateY(-2px);
    background: var(--primary);
    color: white;
  }

  .section-title {
    color: var(--primary);
    border-bottom: 2px solid var(--primary);
    padding-bottom: 10px;
    margin-bottom: 20px;
  }

  .highlight {
    background: linear-gradient(120deg, var(--primary), var(--secondary));
    background-clip: text;
    -webkit-background-clip: text;
    color: transparent;
    font-weight: bold;
  }
</style>
</head>
<body>
  <div class="container">
    <div class="header">
      <h1>👋 Hi, I'm Jayani Malsha</h1>
      <h3>🎓 Third-Year Computer Science Student | Machine Learning Developer</h3>
      <div class="profile-views">Profile Views: 1,234</div>
    </div>
    
<p align="left"> <img src="https://komarev.com/ghpvc/?username=jayanimalsha&label=Profile%20views&color=0e75b6&style=flat" alt="jayanimalsha" /> </p>

<p align="left"> <a href="https://github.com/ryo-ma/github-profile-trophy"><img src="https://github-profile-trophy.vercel.app/?username=jayanimalsha" alt="jayanimalsha" /></a> </p>

<p align="left"> <a href="https://twitter.com/" target="blank"><img src="https://img.shields.io/twitter/follow/?logo=twitter&style=for-the-badge" alt="" /></a> </p>

<div class="section">
      <h2 class="section-title">About Me</h2>
      <div class="grid">
        <div class="info-item">
          <span>🎓</span>
          <div>Third-year Computer Science student at IIT (University of Westminster)</div>
        </div>
        <div class="info-item">
          <span>🔧</span>
          <div>Machine Learning Developer at AryaLabs (Pvt) Ltd</div>
        </div>
        <div class="info-item">
          <span>💻</span>
          <div>Passionate about Programming, Web Development, and Machine Learning</div>
        </div>
        <div class="info-item">
          <span>🏆</span>
          <div>Goal: To continually develop IT skills and contribute to the tech industry</div>
        </div>
      </div>
    </div>

    <div class="section">
      <h2 class="section-title">Looking To</h2>
      <div class="grid">
        <div class="info-item">
          <span>👯</span>
          <div>Collaborate on open-source machine learning projects</div>
        </div>
        <div class="info-item">
          <span>🤝</span>
          <div>Develop innovative web applications</div>
        </div>
        <div class="info-item">
          <span>💬</span>
          <div>Discuss machine learning frameworks like TensorFlow and PyTorch</div>
        </div>
      </div>
    </div>

    <div class="section">
      <h2 class="section-title">Languages and Tools</h2>
      <div class="tools-grid">
        <div class="tool-item">
          <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python"/>
          <span>Python</span>
        </div>
        <div class="tool-item">
          <img src="https://www.vectorlogo.zone/logos/tensorflow/tensorflow-icon.svg" alt="tensorflow"/>
          <span>TensorFlow</span>
        </div>
        <div class="tool-item">
          <img src="https://www.vectorlogo.zone/logos/pytorch/pytorch-icon.svg" alt="pytorch"/>
          <span>PyTorch</span>
        </div>
        <!-- Add more tool items similarly -->
      </div>
    </div>

    <div class="section">
      <h2 class="section-title">GitHub Stats</h2>
      <div class="stats">
        <img src="https://github-readme-stats.vercel.app/api/top-langs?username=jayanimalsha&show_icons=true&locale=en&layout=compact" alt="top languages"/>
        <img src="https://github-readme-stats.vercel.app/api?username=jayanimalsha&show_icons=true&locale=en" alt="github stats"/>
      </div>
    </div>

    <div class="section">
      <h2 class="section-title">Connect with Me</h2>
      <div class="connect">
        <a href="mailto:jayanikatugampala4@gmail.com">
          📫 Email
        </a>
        <a href="https://linkedin.com/in/jayani-malsha">
          💼 LinkedIn
        </a>
        <a href="https://drive.google.com/file/d/1JnSPSEEqO1hgxKsuc2_M8cRefo-YgDmS/view">
          📄 Resume
        </a>
      </div>
    </div>

    <div class="section" style="text-align: center;">
      <div class="highlight">⚡ Fun fact: I think I am funny 😄</div>
    </div>
  </div>
</body>
</html>

<h3 align="left">Connect with me:</h3>
<p align="left">
<a href="https://linkedin.com/in/jayani malsha" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="jayani malsha" height="30" width="40" /></a>
</p>

<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://www.w3schools.com/css/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="40" height="40"/> </a> <a href="https://www.docker.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original-wordmark.svg" alt="docker" width="40" height="40"/> </a> <a href="https://flask.palletsprojects.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/pocoo_flask/pocoo_flask-icon.svg" alt="flask" width="40" height="40"/> </a> <a href="https://git-scm.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/> </a> <a href="https://www.w3.org/html/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="40" height="40"/> </a> <a href="https://www.java.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="java" width="40" height="40"/> </a> <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="40" height="40"/> </a> <a href="https://www.linux.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" alt="linux" width="40" height="40"/> </a> <a href="https://www.mysql.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="40" height="40"/> </a> <a href="https://nodejs.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="nodejs" width="40" height="40"/> </a> <a href="https://opencv.org/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/opencv/opencv-icon.svg" alt="opencv" width="40" height="40"/> </a> <a href="https://www.oracle.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/oracle/oracle-original.svg" alt="oracle" width="40" height="40"/> </a> <a href="https://pandas.pydata.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/2ae2a900d2f041da66e950e4d48052658d850630/icons/pandas/pandas-original.svg" alt="pandas" width="40" height="40"/> </a> <a href="https://www.php.net" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/php/php-original.svg" alt="php" width="40" height="40"/> </a> <a href="https://www.postgresql.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original-wordmark.svg" alt="postgresql" width="40" height="40"/> </a> <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> <a href="https://pytorch.org/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/pytorch/pytorch-icon.svg" alt="pytorch" width="40" height="40"/> </a> <a href="https://reactjs.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="react" width="40" height="40"/> </a> <a href="https://scikit-learn.org/" target="_blank" rel="noreferrer"> <img src="https://upload.wikimedia.org/wikipedia/commons/0/05/Scikit_learn_logo_small.svg" alt="scikit_learn" width="40" height="40"/> </a> <a href="https://seaborn.pydata.org/" target="_blank" rel="noreferrer"> <img src="https://seaborn.pydata.org/_images/logo-mark-lightbg.svg" alt="seaborn" width="40" height="40"/> </a> <a href="https://www.selenium.dev" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/detain/svg-logos/780f25886640cef088af994181646db2f6b1a3f8/svg/selenium-logo.svg" alt="selenium" width="40" height="40"/> </a> <a href="https://www.tensorflow.org" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/tensorflow/tensorflow-icon.svg" alt="tensorflow" width="40" height="40"/> </a> </p>

<p><img align="left" src="https://github-readme-stats.vercel.app/api/top-langs?username=jayanimalsha&show_icons=true&locale=en&layout=compact" alt="jayanimalsha" /></p>

<p>&nbsp;<img align="center" src="https://github-readme-stats.vercel.app/api?username=jayanimalsha&show_icons=true&locale=en" alt="jayanimalsha" /></p>


