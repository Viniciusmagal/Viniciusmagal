<!DOCTYPE html>
<html lang="pt">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Perfil - Vinícius Magalhães</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f0f5;
            display: flex;
            justify-content: center;
            align-items: center;
            flex-direction: column;
            height: 100vh;
            margin: 0;
        }
   .titulo {
            font-size: 28px;
            font-weight: bold;
            text-align: center;
            opacity: 0;
            animation: fade 3s infinite alternate;
        }
   @keyframes fade {
            0% { opacity: 0; }
            100% { opacity: 1; }
        }
 .conteudo {
            max-width: 800px;
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.1);
            text-align: center;
        }
 .icons {
            display: flex;
            justify-content: center;
            gap: 15px;
            margin-top: 15px;
        }
  .icons img {
            width: 40px;
            height: 40px;
            transition: transform 0.3s;
        }
   .icons img:hover {
            transform: scale(1.1);
        }
 </style>
</head>
<body>
    <div class="titulo">Olá, me chamo Vinícius Magalhães 👋</div>
    <div class="conteudo">
      <h2>👨‍💻 Sobre Mim</h2>
        <p>Sou um desenvolvedor que cria soluções inovadoras e funcionais. Atualmente, estou cursando Análise e Desenvolvimento de Sistemas no Instituto Federal e buscando me aprofundar no desenvolvimento Web.</p>
        <h2>🛠️ Linguagens e Ferramentas</h2>
        <div class="icons">
            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" alt="JavaScript">
            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" alt="HTML5">
            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" alt="CSS3">
            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/php/php-original.svg" alt="PHP">
            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" alt="MySQL">
        </div>
        <h2>📧 Contato</h2>
        <a href="mailto:lucavimagal@gmail.com">📩 Enviar E-mail</a>
        <h2>🌐 Redes Sociais</h2>
        <div class="icons">
            <a href="https://www.linkedin.com/in/vinicius-magalhães-5137402b9/" target="_blank">
                <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linkedin/linkedin-original.svg" alt="LinkedIn">
            </a>
            <a href="https://github.com/Viniciusmagal" target="_blank">
                <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" alt="GitHub">
            </a>
        </div>
    </div>
</body>
</html>
