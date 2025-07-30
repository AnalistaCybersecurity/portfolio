<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="style.css">
  <title>Portfólio | Ismael Camargo</title>
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
</head>
<body class="bg-gray-900 text-white font-sans">

  <!-- Navbar -->
  <header class="flex justify-between items-center px-3 py-0.5 bg-gray-800 shadow-md">
    <div>
      <h2 class="text-2xl font-bold text-yellow-400">Ismael Camargo</h2>
      <p class="text-sm text-gray-300" >Analista de Sistemas | Segurança da Informação</p>
    </div>
    <nav class="flex gap-4 text-blue-400">
      <a href="#about" class="hover:text-yellow-400">Sobre</a>
      <a href="#skills" class="hover:text-yellow-400">Habilidades</a>
      <a href="#projects" class="hover:text-yellow-400">Projetos</a>
      <a href="#experience" class="hover:text-yellow-400">Experiência</a>
      <a href="#education" class="hover:text-yellow-400">Formação</a>
      <a href="#contact" class="hover:text-yellow-400">Contato</a>
    </nav>
  </header>

  <!-- Seção Apresentação -->
  <section class="text-center py-2 px-4" id="about">
    <img src="img/foto1.jpg" alt="Foto Profissional" class="mx-auto w-15 h-20 rounded-full mb-4 border-4 border-yellow-500">
    <h2 class="text-2xl font-bold mb-.5">Olá! Eu sou Camargo</h2>
    <p class="text-gray-300 max-w-xl mx-auto">Sou apaixonado por tecnologia, com experiência em desenvolvimento de sistemas, segurança da informação e soluções inovadoras.</p>
    <div class="mt-1 space-x-4">
     <!--<a href="camargo.uff@gmail.com" class="hover:text-yellow-400">Email</a>-->
      <a href="https://linkedin.com/in/ismael-camargo" class="hover:text-yellow-400">LinkedIn</a>
      <a href="https://github.com/ismael-camargo" class="hover:text-yellow-400">GitHub</a>
      <a href="Curriculos/Análista de Dados.pdf" class="hover:text-yellow-400">Currículo</a>
    </div>
  </section>

  <!-- Seção Habilidades -->
  <section class="px-6 py-2 bg-gray-800" id="skills">
    <h2 class="text-2xl font-bold mb-6 text-yellow-400">Habilidades</h2>
    <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
      <div>
        <h3 class="font-semibold text-lg mb-2" >Técnicas</h3>
        <ul class="list-disc list-inside text-gray-300">
          <li>Desenvolvimento Web (HTML, CSS, JavaScript, Python);</li>
          <li>Análise de Dados e Perícia Forense Computacional;</li>
          <li>Python para Data Science e Machine Learning;</li>
          <li>Programação Python do básico ao avançado;</li>
           <li>Lei Geral de Proteção de Dados (LGPD);</li>
           <li>Administrador de Sistemas Linux;</li>
          <li>Segurança da Informação;</li>         
          <li>Cientista de Dados;</li>
          <li>Linux, NoSQL, Git</li>
        </ul>
      </div>
      <div>
        <h3 class="font-semibold text-lg mb-2">Comportamentais</h3>
        <ul class="list-disc list-inside text-gray-300">
          <li>Comunicação</li>
          <li>Trabalho em equipe</li>
          <li>Resolução de problemas</li>
          <li>Proatividade</li>
        </ul>
      </div>
    </div>
  </section>

  <!-- Seção Projetos -->
  <section class="px-0 py-2" id="projects">
    <h2 class="text-2xl font-bold mb-4 text-yellow-400">Projetos</h2>
    <div class="grid grid-cols-1 md:grid-cols-2 gap-5">
      <div class="bg-gray-800 p-6 rounded-lg shadow-lg">
        <h3 class="text-xl font-semibold">Android</h3>
        <p class="text-gray-300 mt-2">O desenvolvimento do projeto visa a atualização do android no decorrer dos tempo.</p>
        <p class="text-sm mt-2"><strong>Tecnologias:</strong>  html, css e JavaScript</p>
        <p class="text-sm"><strong>Desafios:</strong>  Integração com API externa</p>
        <p class="text-sm"><strong>Resultados:</strong>  Redução de 30% no tempo de processamento</p>
        <div class="mt-2 flex gap-4 text-sm">
          <a href="https://github.com/AnalistaCybersecurity/android" class="text-blue-400 hover:underline">Código</a>
          <a href="https://github.com/AnalistaCybersecurity/android10.git" class="text-blue-400 hover:underline">Ver projeto</a>
        </div>
        <img src="print-do-projeto.jpg" alt="Projeto" class="mt-4 rounded">
      </div>
      <!-- Adicione mais projetos conforme necessário -->
    </div>
  </section>

  <!-- Seção Experiência -->
  <section class="px-3 py-2 bg-gray-800" id="experience">
    <h2 class="text-2xl font-bold mb-6 text-yellow-400">Experiência</h2>
    <div class="space-y-4">
      <div>
        <h3 class="text-lg font-semibold">CDI - Comitê para Democratização da Informática</h3>
        <p class="text-gray-300 text-sm">Coordenador de Projetos Sociais | Março 2005 a Setembro 2007.</p>
        <p class="text-gray-400 mt-1">Responsável pelo Atualização do sistema, infraestrutura de sistemas internos, reuniões interna. </p>
      </div>
      <div>
        <h3 class="text-lg font-semibold">Precisa Quadros e Painéis LTDA</h3>
        <p class="text-gray-300 text-sm">Coordenador de almoxarifado.</p>
        <p class="text-gray-400 mt-1">Supervisionar e gerenciar as operações, Conferência de NF, solicitação de compras, expedição de materiais, inventário.  | Setembro 2008 a Março 2012. </p>
      </div>
      <div>
        <h3 class="text-lg font-semibold">Paraíso Auto Peças LTDA</h3>
        <p class="text-gray-300 text-sm">Auxiliar Administartivo.</p>
        <p class="text-gray-400 mt-1">Cobrança caixa, efetuar compras, lançamento de NF no sistema, Serviços bancários, pagamento de duplicatas. </p>
      </div>
    </div>
  </section>

  <!-- Seção Formação -->
  <section class="px-6 py-2" id="education">
    <h2 class="text-2xl font-bold mb-6 text-yellow-400">Formação Acadêmica</h2>
    <ul class="text-gray-300 space-y-3">
      <li><strong>Pós-graduação</strong> – Cybercrimes e Cybersecurity – Facuminas – Concluído em 2023</li>
      <li><strong>Graduação</strong> – Análise e Desenvolvimento de Sistemas – Multivix – Concluído em 2022</li>
    </ul>
  </section>

  <!-- Seção Contato -->
  <section class="px-6 py-2 bg-gray-800" id="contact">
    <h2 class="text-2xl font-bold mb-6 text-yellow-400">Contato</h2>
    <p class="text-gray-300">📧 Email: camargo.uff@gmail.com</p>
    <p class="text-gray-300">📞 Telefone: (27) 99266-3412 - Zap</p>
  </section>

  <!-- Rodapé -->
  <footer class="text-center text-sm py-4 bg-gray-900 text-gray-400">
    © 2025 | Desenvolvido por Ismael Camargo
  </footer>

</body>
</html>![foto1](https://github.com/user-attachments/assets/acf1cefd-afe3-40fb-81b4-e8a0bcc0bf0c)
