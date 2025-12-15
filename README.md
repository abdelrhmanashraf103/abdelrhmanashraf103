<div align="center">
  
  <!-- Animated Header with Gradient -->
  <svg width="100%" height="200">
    <defs>
      <style>
        @keyframes gradientMove {
          0% { background-position: 0% 50%; }
          50% { background-position: 100% 50%; }
          100% { background-position: 0% 50%; }
        }
        @keyframes float {
          0%, 100% { transform: translateY(0px); }
          50% { transform: translateY(-10px); }
        }
        @keyframes glow {
          0%, 100% { filter: drop-shadow(0 0 5px #58a6ff); }
          50% { filter: drop-shadow(0 0 15px #58a6ff); }
        }
        @keyframes bounce {
          0%, 100% { transform: scale(1); }
          50% { transform: scale(1.05); }
        }
        .gradient-bg {
          fill: url(#gradient);
          animation: gradientMove 8s ease infinite;
        }
      </style>
      <linearGradient id="gradient" x1="0%" y1="0%" x2="100%" y2="100%">
        <stop offset="0%" style="stop-color:#0d1117;stop-opacity:1" />
        <stop offset="50%" style="stop-color:#161b22;stop-opacity:1" />
        <stop offset="100%" style="stop-color:#0d1117;stop-opacity:1" />
      </linearGradient>
    </defs>
    
    <rect class="gradient-bg" width="100%" height="200" rx="10" ry="10" stroke="#30363d" stroke-width="1"/>
    
    <foreignObject x="0" y="0" width="100%" height="200">
      <div xmlns="http://www.w3.org/1999/xhtml" style="
        height: 200px;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        padding: 20px;
      ">
        <h1 style="
          color: #58a6ff;
          font-size: 2.5rem;
          margin: 0;
          animation: float 3s ease-in-out infinite;
        ">
          ⚡ Abdelrahman Haroun ⚡
        </h1>
        <p style="
          color: #f0f6fc;
          font-size: 1.5rem;
          margin: 10px 0;
          animation: glow 2s ease-in-out infinite;
        ">
          Data Analyst | Python Expert | Former Samsung Professional
        </p>
        <div style="display: flex; justify-content: center; gap: 15px; flex-wrap: wrap; margin-top: 15px;">
          <span style="
            background: #238636;
            padding: 5px 15px;
            border-radius: 20px;
            color: white;
            animation: bounce 2s ease-in-out infinite;
          ">📊 Data Visualization</span>
          <span style="
            background: #1f6feb;
            padding: 5px 15px;
            border-radius: 20px;
            color: white;
            animation: bounce 2s ease-in-out infinite 0.2s;
          ">🔍 Insights</span>
          <span style="
            background: #8957e5;
            padding: 5px 15px;
            border-radius: 20px;
            color: white;
            animation: bounce 2s ease-in-out infinite 0.4s;
          ">📈 Analytics</span>
        </div>
      </div>
    </foreignObject>
  </svg>

  <!-- Typing Animation Intro -->
  <svg width="100%" height="50">
    <foreignObject width="100%" height="50">
      <div xmlns="http://www.w3.org/1999/xhtml" style="
        text-align: center;
        padding: 20px 0;
      ">
        <h1 style="
          color: #58a6ff;
          font-size: 2rem;
          margin: 0;
          overflow: hidden;
          white-space: nowrap;
          border-right: 3px solid #58a6ff;
          width: 0;
          animation: typing 3.5s steps(40, end) forwards, blink 0.75s step-end infinite;
        ">
          Hi there, I'm Abdelrahman Haroun! 👋
        </h1>
        <style>
          @keyframes typing {
            from { width: 0 }
            to { width: 100% }
          }
          @keyframes blink {
            from, to { border-color: transparent }
            50% { border-color: #58a6ff; }
          }
        </style>
      </div>
    </foreignObject>
  </svg>

  <!-- Professional tagline with fade-in -->
  <svg width="100%" height="80">
    <foreignObject width="100%" height="80">
      <div xmlns="http://www.w3.org/1999/xhtml" style="
        text-align: center;
        padding: 10px 0;
      ">
        <p style="
          font-size: 1.2rem;
          color: #f0f6fc;
          opacity: 0;
          animation: fadeIn 2s ease forwards 3.5s;
        ">
          <b>Data Analyst | Former Samsung Professional | Transforming Raw Data into Strategic Insights 📈</b>
        </p>
        <style>
          @keyframes fadeIn {
            to { opacity: 1; }
          }
        </style>
      </div>
    </foreignObject>
  </svg>

  <!-- GitHub stats with hover effects -->
  <div align="center" style="
    display: flex;
    justify-content: center;
    gap: 20px;
    flex-wrap: wrap;
    margin: 30px 0;
  ">
    <a href="https://github.com/abdelrhmanashraf103" style="text-decoration: none;">
      <img src="https://github-readme-stats.vercel.app/api?username=abdelrhmanashraf103&show_icons=true&theme=radical&hide_border=true" 
           alt="GitHub Stats" 
           width="45%"
           style="
             transition: transform 0.3s ease;
             border-radius: 10px;
           "
           onmouseover="this.style.transform='scale(1.05)'"
           onmouseout="this.style.transform='scale(1)'"/>
    </a>
    <a href="https://github.com/abdelrhmanashraf103" style="text-decoration: none;">
      <img src="https://github-readme-streak-stats.herokuapp.com/?user=abdelrhmanashraf103&theme=radical" 
           alt="GitHub Streak" 
           width="45%"
           style="
             transition: transform 0.3s ease;
             border-radius: 10px;
           "
           onmouseover="this.style.transform='scale(1.05)'"
           onmouseout="this.style.transform='scale(1)'"/>
    </a>
  </div>

  <!-- Top Languages with pulse animation -->
  <svg width="100%" height="200">
    <foreignObject width="100%" height="200">
      <div xmlns="http://www.w3.org/1999/xhtml" style="
        text-align: center;
        padding: 20px;
      ">
        <h2 style="
          color: #58a6ff;
          margin-bottom: 20px;
          animation: pulse 2s ease-in-out infinite;
        ">Top Languages 🚀</h2>
        <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=abdelrhmanashraf103&layout=compact&theme=radical&hide_border=true" 
             alt="Top Languages" 
             width="50%"
             style="
               border-radius: 10px;
               transition: all 0.3s ease;
             "
             onmouseover="this.style.filter='brightness(1.2)'"
             onmouseout="this.style.filter='brightness(1)'"/>
        <style>
          @keyframes pulse {
            0%, 100% { transform: scale(1); }
            50% { transform: scale(1.05); }
          }
        </style>
      </div>
    </foreignObject>
  </svg>

  <!-- Skills & Tools Section -->
  <h2 style="
    color: #58a6ff;
    margin: 40px 0 20px;
    position: relative;
    display: inline-block;
  ">
    Skills & Tools 💻
    <span style="
      position: absolute;
      bottom: -5px;
      left: 0;
      width: 100%;
      height: 3px;
      background: linear-gradient(90deg, transparent, #58a6ff, transparent);
      animation: slide 2s linear infinite;
    "></span>
    <style>
      @keyframes slide {
        0% { transform: translateX(-100%); }
        100% { transform: translateX(100%); }
      }
    </style>
  </h2>
  
  <!-- Programming Languages with hover effects -->
  <h3>Programming Languages 💻</h3>
  <div style="
    display: flex;
    gap: 15px;
    flex-wrap: wrap;
    justify-content: center;
    margin: 15px 0;
  ">
    <!-- Python with special animation -->
    <div style="
      position: relative;
      animation: pythonSpin 4s linear infinite;
    ">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" 
           width="60" 
           height="60" 
           title="Python"
           style="
             transition: all 0.3s ease;
             filter: drop-shadow(0 0 5px #3776ab);
           "
           onmouseover="this.style.filter='drop-shadow(0 0 15px #3776ab)'; this.style.transform='rotate(360deg)'"
           onmouseout="this.style.filter='drop-shadow(0 0 5px #3776ab)'; this.style.transform='rotate(0deg)'"/> 
    </div>
    <style>
      @keyframes pythonSpin {
        0% { transform: rotate(0deg); }
        25% { transform: rotate(5deg); }
        50% { transform: rotate(0deg); }
        75% { transform: rotate(-5deg); }
        100% { transform: rotate(0deg); }
      }
    </style>
    
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/r/r-original.svg" 
         width="50" 
         height="50" 
         title="R"
         style="transition: all 0.3s ease;"
         onmouseover="this.style.transform='translateY(-10px) scale(1.2)'"
         onmouseout="this.style.transform='translateY(0) scale(1)'"/>
    
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/c/c-original.svg" 
         width="50" 
         height="50" 
         title="C"
         style="transition: all 0.3s ease;"
         onmouseover="this.style.transform='translateY(-10px) scale(1.2)'"
         onmouseout="this.style.transform='translateY(0) scale(1)'"/>
    
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/php/php-original.svg" 
         width="50" 
         height="50" 
         title="PHP"
         style="transition: all 0.3s ease;"
         onmouseover="this.style.transform='translateY(-10px) scale(1.2)'"
         onmouseout="this.style.transform='translateY(0) scale(1)'"/>
    
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" 
         width="50" 
         height="50" 
         title="HTML5"
         style="transition: all 0.3s ease;"
         onmouseover="this.style.transform='translateY(-10px) scale(1.2)'"
         onmouseout="this.style.transform='translateY(0) scale(1)'"/>
    
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" 
         width="50" 
         height="50" 
         title="CSS3"
         style="transition: all 0.3s ease;"
         onmouseover="this.style.transform='translateY(-10px) scale(1.2)'"
         onmouseout="this.style.transform='translateY(0) scale(1)'"/>
  </div>

  <!-- Databases -->
  <h3>Databases 🗃️</h3>
  <div style="
    display: flex;
    gap: 15px;
    flex-wrap: wrap;
    justify-content: center;
    margin: 15px 0;
  ">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" 
         width="50" 
         height="50" 
         title="MySQL"
         style="transition: all 0.3s ease;"
         onmouseover="this.style.transform='translateY(-10px) scale(1.2)'"
         onmouseout="this.style.transform='translateY(0) scale(1)'"/>
    
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" 
         width="50" 
         height="50" 
         title="PostgreSQL"
         style="transition: all 0.3s ease;"
         onmouseover="this.style.transform='translateY(-10px) scale(1.2)'"
         onmouseout="this.style.transform='translateY(0) scale(1)'"/>
    
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mongodb/mongodb-original.svg" 
         width="50" 
         height="50" 
         title="MongoDB"
         style="transition: all 0.3s ease;"
         onmouseover="this.style.transform='translateY(-10px) scale(1.2)'"
         onmouseout="this.style.transform='translateY(0) scale(1)'"/>
  </div>

  <!-- Data Visualization -->
  <h3>Data Visualization 📊</h3>
  <div style="
    display: flex;
    gap: 10px;
    flex-wrap: wrap;
    justify-content: center;
    margin: 10px 0;
  ">
    <span style="
      display: inline-block;
      padding: 10px 20px;
      background: linear-gradient(45deg, #f2c811, #e6b400);
      border-radius: 5px;
      color: black;
      font-weight: bold;
      transition: all 0.3s ease;
      animation: colorShift 4s infinite alternate;
    "
    onmouseover="this.style.transform='scale(1.1) rotate(2deg)'"
    onmouseout="this.style.transform='scale(1) rotate(0deg)'">
      Power BI
    </span>
    
    <span style="
      display: inline-block;
      padding: 10px 20px;
      background: linear-gradient(45deg, #e97627, #d1661f);
      border-radius: 5px;
      color: white;
      font-weight: bold;
      transition: all 0.3s ease;
      animation: colorShift 4s infinite alternate-reverse;
    "
    onmouseover="this.style.transform='scale(1.1) rotate(-2deg)'"
    onmouseout="this.style.transform='scale(1) rotate(0deg)'">
      Tableau
    </span>
    
    <style>
      @keyframes colorShift {
        0% { filter: hue-rotate(0deg); }
        100% { filter: hue-rotate(20deg); }
      }
    </style>
  </div>

  <!-- Data Science -->
  <h3>Data Science 🧠</h3>
  <div style="
    display: flex;
    gap: 15px;
    flex-wrap: wrap;
    justify-content: center;
    margin: 15px 0;
  ">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pandas/pandas-original.svg" 
         width="50" 
         height="50" 
         title="Pandas"
         style="
           transition: all 0.3s ease;
           animation: floatUp 3s ease-in-out infinite;
         "
         onmouseover="this.style.animationPlayState='paused'; this.style.transform='scale(1.3)'"
         onmouseout="this.style.animationPlayState='running'; this.style.transform='scale(1)'"/>
    
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/numpy/numpy-original.svg" 
         width="50" 
         height="50" 
         title="NumPy"
         style="
           transition: all 0.3s ease;
           animation: floatUp 3s ease-in-out infinite 0.5s;
         "
         onmouseover="this.style.animationPlayState='paused'; this.style.transform='scale(1.3)'"
         onmouseout="this.style.animationPlayState='running'; this.style.transform='scale(1)'"/>
    
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/jupyter/jupyter-original.svg" 
         width="50" 
         height="50" 
         title="Jupyter"
         style="
           transition: all 0.3s ease;
           animation: floatUp 3s ease-in-out infinite 1s;
         "
         onmouseover="this.style.animationPlayState='paused'; this.style.transform='scale(1.3)'"
         onmouseout="this.style.animationPlayState='running'; this.style.transform='scale(1)'"/>
    
    <style>
      @keyframes floatUp {
        0%, 100% { transform: translateY(0); }
        50% { transform: translateY(-10px); }
      }
    </style>
  </div>

  <!-- Projects Section with slide-in -->
  <svg width="100%" height="150">
    <foreignObject width="100%" height="150">
      <div xmlns="http://www.w3.org/1999/xhtml" style="
        text-align: center;
        padding: 30px 0;
      ">
        <h2 style="
          color: #58a6ff;
          margin-bottom: 10px;
          opacity: 0;
          transform: translateY(20px);
          animation: slideUp 1s ease forwards 1s;
        ">Featured Projects 🚀</h2>
        <p style="
          color: #f0f6fc;
          opacity: 0;
          transform: translateY(20px);
          animation: slideUp 1s ease forwards 1.2s;
        ">Check out my pinned repositories below to see some of my data analysis projects!</p>
        <style>
          @keyframes slideUp {
            to {
              opacity: 1;
              transform: translateY(0);
            }
          }
        </style>
      </div>
    </foreignObject>
  </svg>

  <!-- Connect Section with wave animation -->
  <h2 style="
    color: #58a6ff;
    margin: 40px 0 20px;
    position: relative;
  ">
    Let's Connect 🌐
    <span style="
      position: absolute;
      bottom: -5px;
      left: 0;
      width: 100%;
      height: 2px;
      background: linear-gradient(90deg, #58a6ff, #8957e5, #58a6ff);
      background-size: 200% 100%;
      animation: wave 2s linear infinite;
    "></span>
    <style>
      @keyframes wave {
        0% { background-position: 0% 50%; }
        100% { background-position: 200% 50%; }
      }
    </style>
  </h2>
  
  <div align="center" style="
    display: flex;
    gap: 15px;
    flex-wrap: wrap;
    justify-content: center;
    margin: 20px 0;
  ">
    <a href="https://linkedin.com/in/abdelrahman-haroun" 
       target="_blank"
       style="
         display: inline-block;
         transition: all 0.3s ease;
         animation: socialBounce 2s ease-in-out infinite;
       "
       onmouseover="this.style.transform='scale(1.2) rotate(5deg)'"
       onmouseout="this.style.transform='scale(1) rotate(0deg)'">
      <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" 
           alt="LinkedIn"/>
    </a>
    
    <a href="https://x.com/abdo_ashraf103" 
       target="_blank"
       style="
         display: inline-block;
         transition: all 0.3s ease;
         animation: socialBounce 2s ease-in-out infinite 0.1s;
       "
       onmouseover="this.style.transform='scale(1.2) rotate(5deg)'"
       onmouseout="this.style.transform='scale(1) rotate(0deg)'">
      <img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white" 
           alt="X (Twitter)"/>
    </a>
    
    <a href="mailto:bnashraf440@gmail.com"
       style="
         display: inline-block;
         transition: all 0.3s ease;
         animation: socialBounce 2s ease-in-out infinite 0.2s;
       "
       onmouseover="this.style.transform='scale(1.2) rotate(5deg)'"
       onmouseout="this.style.transform='scale(1) rotate(0deg)'">
      <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" 
           alt="Email"/>
    </a>
    
    <style>
      @keyframes socialBounce {
        0%, 100% { transform: translateY(0); }
        50% { transform: translateY(-5px); }
      }
    </style>
  </div>

  <!-- Profile Views with counter animation -->
  <br>
  <svg width="200" height="30">
    <foreignObject width="200" height="30">
      <div xmlns="http://www.w3.org/1999/xhtml" style="
        text-align: center;
      ">
        <img src="https://komarev.com/ghpvc/?username=abdelrhmanashraf103&label=Profile%20Views&color=0e75b6&style=flat" 
             alt="Profile views"
             style="
               transition: all 0.3s ease;
               animation: pulseCounter 2s ease-in-out infinite;
             "
             onmouseover="this.style.transform='scale(1.1)'"
             onmouseout="this.style.transform='scale(1)'"/>
        <style>
          @keyframes pulseCounter {
            0%, 100% { opacity: 1; }
            50% { opacity: 0.7; }
          }
        </style>
      </div>
    </foreignObject>
  </svg>
  
  <!-- Closing message with fade-in -->
  <svg width="100%" height="100">
    <foreignObject width="100%" height="100">
      <div xmlns="http://www.w3.org/1999/xhtml" style="
        text-align: center;
        padding: 20px 0;
      ">
        <p style="
          color: #f0f6fc;
          font-size: 1.1rem;
          opacity: 0;
          animation: fadeInUp 2s ease forwards 2s;
        ">
          Thanks for visiting my profile! Feel free to explore my repositories and get in touch. 🚀
        </p>
        <style>
          @keyframes fadeInUp {
            to {
              opacity: 1;
              transform: translateY(0);
            }
            from {
              opacity: 0;
              transform: translateY(20px);
            }
          }
        </style>
      </div>
    </foreignObject>
  </svg>

</div>

<!-- Star animation in background -->
<svg width="0" height="0" style="position: absolute;">
  <defs>
    <filter id="star-glow">
      <feGaussianBlur stdDeviation="2" result="blur" />
      <feMerge>
        <feMergeNode in="blur" />
        <feMergeNode in="blur" />
        <feMergeNode in="blur" />
        <feMergeNode in="SourceGraphic" />
      </feMerge>
    </filter>
  </defs>
</svg>
