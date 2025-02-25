<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Perfil - Vinícius Magalhães</title>
  <link rel="stylesheet" type="text/css" href="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/devicon.min.css" />
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f0f0f5;
      margin: 0;
      padding: 0;
      display: flex;
      flex-direction: column;
      align-items: center;
      position: relative;
      min-height: 100vh;
    }
    
    /* Texto animado no topo */
    .intro-text {
      position: fixed;
      top: 20px;
      left: 50%;
      transform: translateX(-50%);
      font-size: 24px;
      font-weight: bold;
      color: #007bff;
      background: rgba(255, 255, 255, 0.9);
      padding: 10px 20px;
      border-radius: 5px;
      opacity: 0;
      animation: fadeInOut 4s ease-in-out forwards;
      z-index: 1000;
    }

    @keyframes fadeInOut {
      0% {
        opacity: 0;
        transform: translateX(-50%) translateY(-30px);
      }
      20% {
        opacity: 1;
        transform: translateX(-50%) translateY(0);
      }
      80% {
        opacity: 1;
        transform: translateX(-50%) translateY(0);
      }
      100% {
        opacity: 0;
        transform: translateX(-50%) translateY(-30px);
      }
    }

    .container {
      display: flex;
      align-items: flex-start;
      padding: 20px;
      background-color: #ffffff;
      border-radius: 15px;
      box-shadow: 0 4px 20px rgba(0, 0, 0, 0.1);
      max-width: 900px;
      width: 100%;
      margin-top: 100px; /* Para evitar sobreposição com o texto animado */
    }

    .sidebar {
      flex: 30%;
      max-width: 300px;
      padding: 20px;
      background-color: #f4f4f9;
      border-radius: 10px;
      text-align: center;
    }

    .sidebar img {
      border-radius: 50%;
      width: 150px;
      height: 150px;
      object-fit: cover;
      border: 3px solid #007bff;
    }

    .content {
      flex: 70%;
      padding-left: 20px;
    }

    h1 {
      font-size: 28px;
      margin-bottom: 20px;
      color: #333;
      border-bottom: 2px solid #007bff;
      padding-bottom: 5px;
    }

    p {
      font-size: 16px;
      color: #555;
    }
  </style>
</head>
<body>
  <div class="intro-text">Olá, me chamo Vinícius Magalhães</div>
  
  <div class="container">
    <div class="sidebar">
      <img src="https://avatars.githubusercontent.com/u/162904345?v=4" alt="Vinícius Magalhães" />
      <h2>Vinícius Magalhães</h2>
      <p>👨‍💻 | Estudante de Programação</p>
      <h3>📧 Contato</h3>
      <p>
        <a href="mailto:lucavimagal@gmail.com" target="_blank">
          <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/7/7e/Gmail_icon_%282020%29.svg/2560px-Gmail_icon_%282020%29.svg.png" alt="Email" width="35" height="35" />
        </a>
      </p>
      <h3>🌐 Redes Sociais</h3>
      <p>
        <a href="https://www.linkedin.com/in/vinicius-magalhães-5137402b9/" target="_blank">
          <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linkedin/linkedin-original.svg" alt="LinkedIn" width="35" height="35" />
        </a>
        <a href="https://github.com/Viniciusmagal" target="_blank">
          <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" alt="GitHub" width="35" height="35" />
        </a>
      </p>
    </div>
  <div class="content">
      <h1>🚀 Sobre Mim</h1>
      <p>
        Sou um desenvolvedor que cria soluções inovadoras e funcionais. Atualmente, estou cursando Análise e Desenvolvimento de Sistemas no Instituto Federal e buscando me aprofundar no desenvolvimento Web. Tenho experiência em diversas tecnologias como JavaScript, PHP, MySQL, entre outras, e estou sempre em busca de novos conhecimentos.
      </p>
      <h1>🛠️ Linguagens e Ferramentas</h1>
      <p style="display: flex; justify-content: start; gap: 15px; flex-wrap: wrap;">
        <a href="https://github.com/Viniciusmagal/mobileapps" target="_blank">
          <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/android/android-original.svg" alt="Android" width="40" height="40" />
        </a>
        <a href="https://getbootstrap.com" target="_blank">
          <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/bootstrap/bootstrap-original.svg" alt="Bootstrap" width="40" height="40" />
        </a>
        <a href="https://docs.microsoft.com/en-us/dotnet/csharp/" target="_blank">
          <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/csharp/csharp-original.svg" alt="C#" width="40" height="40" />
        </a>
        <a href="https://github.com/Viniciusmagal/Web-projects" target="_blank">
          <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original-wordmark.svg" alt="CSS3" width="40" height="40" />
        </a>
        <a href="https://github.com/Viniciusmagal/Web-projects" target="_blank">
          <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" alt="HTML5" width="40" height="40" />
        </a>
        <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank">
          <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" alt="JavaScript" width="40" height="40" />
        </a>
        <a href="https://www.mysql.com/" target="_blank">
          <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" alt="MySQL" width="40" height="40" />
        </a>
        <a href="https://github.com/Viniciusmagal/Web-projects" target="_blank">
          <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/php/php-original.svg" alt="PHP" width="40" height="40" />
        </a>
      </p>
      <h1>🎓 Formação Acadêmica</h1>
      <ul style="list-style-type: none; padding-left: 0;">
        <li style="font-size: 16px; margin-bottom: 10px; color: #555;">
  <strong>Análise e Desenvolvimento de Sistemas</strong><br />
      Instituto Federal de São Paulo (2024 - 2026)
  </li>
  <li style="font-size: 16px; margin-bottom: 10px; color: #555;">
  <strong>Análise e Desenvolvimento de Sistemas</strong><br />
   ETEC Prof. Carmine Biagio Tundisi (2021 - 2023)<br />
   Habilidades: CSS, MySQL, Java, HTML5, PHP, Banco de Dados, Trabalho em Equipe, Análise de Projetos.
   </li>
   <li style="font-size: 16px; color: #555;">
   <strong>Certificação em Inteligência Artificial (AI-900)</strong><br />
  SENAI Bragança Paulista (Ago 2023 - Out 2023)<br />
   Competências: Azure DevOps, Azure Machine Learning, Microsoft AI-900.
  </li>
  </ul>
  <h1>📊 GitHub Stats</h1>
  <div style="display: flex; justify-content: center; gap: 20px;">
   <img src="https://github-readme-stats.vercel.app/api?username=ViniciusMagal&show_icons=true&theme=radical" alt="GitHub Stats" style="width: 48%; height: 200px; border-radius: 10px; box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ViniciusMagal&layout=compact&theme=radical" alt="Top Languages" style="width: 48%; height: 200px; border-radius: 10px; box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);" />
      </div>
    </div>
  </div>
</body>
</html>
