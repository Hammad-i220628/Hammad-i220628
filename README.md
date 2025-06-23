<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Hammad Ali Duggal - Portfolio</title>
  <style>
    body {
      font-family: 'Fira Code', monospace;
      background: linear-gradient(135deg, #1e1e2f 0%, #2a2a4e 100%);
      color: #ffffff;
      margin: 0;
      padding: 0;
      overflow-x: hidden;
      line-height: 1.6;
    }
    .container {
      max-width: 1200px;
      margin: 0 auto;
      padding: 20px;
      text-align: center;
    }
    h1 {
      font-size: 2.5rem;
      margin-bottom: 10px;
      animation: fadeIn 1.5s ease-in-out;
    }
    h1 img {
      vertical-align: middle;
      animation: wave 2s infinite;
    }
    h3 {
      font-size: 1.5rem;
      color: #00d4ff;
      margin-bottom: 30px;
      animation: slideIn 1.8s ease-out;
    }
    .profile-img {
      width: 350px;
      border-radius: 15px;
      box-shadow: 0 0 20px rgba(0, 212, 255, 0.5);
      transition: transform 0.3s ease, box-shadow 0.3s ease;
      animation: float 3s ease-in-out infinite;
    }
    .profile-img:hover {
      transform: scale(1.05);
      box-shadow: 0 0 30px rgba(0, 212, 255, 0.8);
    }
    .bio {
      font-size: 1.1rem;
      margin: 20px 0;
      animation: fadeInUp 2s ease-in-out;
    }
    .bio p {
      margin: 10px 0;
      transition: color 0.3s ease;
    }
    .bio p:hover {
      color: #00d4ff;
    }
    .connect {
      margin: 40px 0;
      animation: fadeIn 2.2s ease-in-out;
    }
    .connect a {
      margin: 0 15px;
      transition: transform 0.3s ease, filter 0.3s ease;
      display: inline-block;
    }
    .connect a:hover {
      transform: translateY(-5px);
      filter: brightness(1.2);
    }
    .tech-stack {
      background: rgba(255, 255, 255, 0.1);
      padding: 20px;
      border-radius: 10px;
      margin: 40px 0;
      animation: fadeIn 2.4s ease-in-out;
    }
    .tech-stack img {
      margin: 10px;
      transition: transform 0.3s ease;
    }
    .tech-stack img:hover {
      transform: scale(1.2);
    }
    .motto {
      font-size: 1.3rem;
      color: #00d4ff;
      font-weight: bold;
      animation: pulse 2s infinite;
    }
    @keyframes fadeIn {
      0% { opacity: 0; }
      100% { opacity: 1; }
    }
    @keyframes fadeInUp {
      0% { opacity: 0; transform: translateY(20px); }
      100% { opacity: 1; transform: translateY(0); }
    }
    @keyframes slideIn {
      0% { opacity: 0; transform: translateX(-50px); }
      100% { opacity: 1; transform: translateX(0); }
    }
    @keyframes wave {
      0%, 100% { transform: rotate(0deg); }
      50% { transform: rotate(20deg); }
    }
    @keyframes float {
      0%, 100% { transform: translateY(0); }
      50% { transform: translateY(-10px); }
    }
    @keyframes pulse {
      0%, 100% { transform: scale(1); }
      50% { transform: scale(1.05); }
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>
      <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="40px"/>
      Hi, I'm HAMMAD ALI DUGGAL
    </h1>
    <h3>
      <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=22&pause=1000&color=008CFF&width=700&lines=🚀+Full+Stack+Developer+|+Software+Engineer+🎯" alt="Typing SVG" />
    </h3>
    <img class="profile-img" src="https://camo.githubusercontent.com/2366b34bb903c09617990fb5fff4622f3e941349e846ddb7e73df872a9d21233/68747470733a2f2f63646e2e6472696262626c652e636f6d2f75736572732f3733303730332f73637265656e73686f74732f363538313234332f6176656e746f2e676966" alt="coding"/>
    <div class="bio">
      <p>🔭 I’m currently working on <strong>Full Stack Websites</strong></p>
      <p>🌱 Learning <strong>Cloud Computing & DevOps</strong></p>
      <p>💡 Passionate about <strong>Backend Development & System Design</strong></p>
      <p>💬 Ask me about <strong>MERN Stack, Java, Docker, Linux</strong></p>
      <p>📫 Reach me at <a href="mailto:hammadaliduggaljutt@gmail.com">hammadaliduggaljutt@gmail.com</a></p>
    </div>
    <div class="connect">
      <h2>🚀 Connect With Me</h2>
      <p>
        <a href="https://www.linkedin.com/in/hammad-ali-duggal-030ba427b/" target="_blank">
          <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="LinkedIn" height="30" width="40"/>
        </a>
        <a href="https://instagram.com/hammad_ali_duggal_92" target="_blank">
          <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/instagram.svg" alt="Instagram" height="30" width="40"/>
        </a>
      </p>
    </div>
    <div class="tech-stack">
      <h2>🛠️ Tech Stack</h2>
      <p>
        <img src="https://skillicons.dev/icons?i=html,css,js,react,java,python,cpp,postman"/>
      </p>
      <p>
        <img src="https://skillicons.dev/icons?i=nodejs,mongodb,mysql,docker,linux,git,aws,figma"/>
      </p>
    </div>
    <div class="motto">
      🔥 <strong>"Code, Create, Conquer!"</strong> 🚀
    </div>
  </div>
</body>
</html>
