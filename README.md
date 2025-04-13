<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <title>VERSA - Versatilidade em Soluções Avançadas</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link href="https://fonts.googleapis.com/css2?family=Rubik&display=swap" rel="stylesheet">
  <style>
    * { box-sizing: border-box; margin: 0; padding: 0; }
    body {
      font-family: 'Rubik', sans-serif;
      background-color: #f4f6f8;
      color: #333;
      line-height: 1.6;
    }
    nav {
      background: #4A90E2;
      padding: 10px 20px;
    }
    nav ul {
      display: flex;
      justify-content: center;
      gap: 20px;
      list-style: none;
    }
    nav ul li a {
      color: white;
      font-weight: bold;
      text-decoration: none;
    }
    header {
      background: linear-gradient(rgba(0,0,0,0.3), rgba(0,0,0,0.3)), url('header-bg.jpg') no-repeat center center/cover;
      color: white;
      text-align: center;
      padding: 80px 20px;
    }
    header h1 {
      font-size: 3em;
    }
    .profile-img {
      width: 120px;
      height: 120px;
      border-radius: 50%;
      border: 4px solid white;
      margin-top: 20px;
    }
    .contact-btn {
      margin-top: 20px;
      padding: 12px 25px;
      background-color: #ffc107;
      color: #333;
      border-radius: 5px;
      font-weight: bold;
      text-decoration: none;
    }
    main {
      padding: 30px 20px;
      max-width: 1000px;
      margin: auto;
    }
    section {
      margin-bottom: 60px;
    }
    section h2 {
      color: #4A90E2;
      text-align: center;
      margin-bottom: 20px;
    }
    section p, section ul {
      font-size: 1.1em;
      margin-bottom: 15px;
      text-align: justify;
    }
    .info-list li {
      margin-bottom: 10px;
    }
    .planos {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
      justify-content: center;
    }
    .plano {
      background-color: white;
      border: 1px solid #ccc;
      border-radius: 10px;
      padding: 20px;
      flex: 1 1 280px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }
    footer {
      background-color: #4A90E2;
      color: white;
      text-align: center;
      padding: 20px;
    }
  </style>
</head>
<body>

<nav>
  <ul>
    <li><a href="#home">Início</a></li>
    <li><a href="#sobre">Sobre</a></li>
    <li><a href="#ficha">Ficha Técnica</a></li>
    <li><a href="#diferenciais">Diferenciais</a></li>
    <li><a href="#planos">Planos</a></li>
    <li><a href="#contato">Contato</a></li>
  </ul>
</nav>

<header id="home">
  <h1>VERSA</h1>
  <p>Versatilidade em Soluções Avançadas – Serviço Premium 17.0</p>
  <p><em>"A solução que se adapta, resolve e transforma."</em></p>
  <img src="profile.jpg" alt="Foto de perfil" class="profile-img">
  <br>
  <a href="#contato" class="contact-btn">Conecte-se com a VERSA</a>
</header>

<main>
  <section id="sobre">
    <h2>Sobre o Serviço</h2>
    <p>
      VERSA é um serviço completo, ágil e multifuncional, criado para atender a múltiplas demandas com criatividade, inteligência e empatia. Ideal para contextos acadêmicos, projetos de inovação, suporte digital e ambientes colaborativos. 
      Projetado com base em princípios como responsabilidade, proatividade e curiosidade, VERSA busca entregar mais do que resultados: entrega impacto positivo e transformação.
    </p>
  </section>

  <section id="ficha">
    <h2>Ficha Técnica</h2>
    <ul class="info-list">
      <li><strong>Nome do Serviço:</strong> VERSA</li>
      <li><strong>Versão:</strong> 17.0</li>
      <li><strong>Origem:</strong> Cláudio - MG</li>
      <li><strong>Especialidade:</strong> Tecnologia, criatividade e resolução de problemas</li>
      <li><strong>Funcionalidades principais:</strong> Agilidade, versatilidade, comprometimento e inovação</li>
    </ul>
  </section>

  <section id="diferenciais">
    <h2>Diferenciais</h2>
    <ul class="info-list">
      <li>Alta capacidade de aprendizado e adaptação</li>
      <li>Resolução criativa e prática de problemas</li>
      <li>Habilidade de comunicação e trabalho em equipe</li>
      <li>Foco em crescimento contínuo e inovação tecnológica</li>
      <li>Visão de futuro com metas de expansão internacional (Canadá 🇨🇦)</li>
    </ul>
  </section>

  <section id="planos">
    <h2>Planos Disponíveis</h2>
    <div class="planos">
      <div class="plano">
        <h3>Plano Essencial</h3>
        <p>Atendimento personalizado para tarefas escolares, pesquisas e organização de ideias.</p>
      </div>
      <div class="plano">
        <h3>Plano Avançado</h3>
        <p>Auxílio estratégico para projetos acadêmicos, desafios lógicos e suporte a equipes colaborativas.</p>
      </div>
      <div class="plano">
        <h3>Plano Premium+</h3>
        <p>Performance máxima em projetos de inovação, planejamento de carreira, e soluções com foco em tecnologia e dados.</p>
      </div>
    </div>
  </section>

  <section id="contato">
    <h2>Contato</h2>
    <p>Quer saber como a VERSA pode ajudar você ou seu projeto? Entre em contato agora mesmo!</p>
    <p>Email: <a href="mailto:versa@exemplo.com">versa@exemplo.com</a></p>
    <p>Redes Sociais:
      <a href="#">Instagram</a> |
      <a href="#">LinkedIn</a> |
      <a href="#">GitHub</a>
    </p>
  </section>
</main>

<footer>
  © 2025 VERSA. Tecnologia com propósito e versatilidade.
</footer>

</body>
</html>
