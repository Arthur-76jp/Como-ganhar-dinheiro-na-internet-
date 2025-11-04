# Como-ganhar-dinheiro-na-internet-
Neste site eu ensino brevemente a ganhar dinheiro pela internet 
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Ganhe Dinheiro Online</title>
  <style>
    :root {
      --primary: #0073e6;
      --dark: #0a0a0a;
      --light: #ffffff;
      --gray: #f3f3f3;
    }

    body {
      font-family: "Poppins", Arial, sans-serif;
      margin: 0;
      background-color: var(--gray);
      color: var(--dark);
    }

    header {
      background: linear-gradient(135deg, var(--primary), var(--dark));
      color: var(--light);
      padding: 80px 20px;
      text-align: center;
    }

    header h1 {
      font-size: 2.8rem;
      margin-bottom: 10px;
    }

    header p {
      font-size: 1.2rem;
      opacity: 0.9;
    }

    main {
      max-width: 1000px;
      margin: 50px auto;
      background: var(--light);
      border-radius: 10px;
      box-shadow: 0 4px 20px rgba(0, 0, 0, 0.1);
      padding: 40px;
    }

    section {
      margin-bottom: 40px;
    }

    h2 {
      color: var(--primary);
      margin-bottom: 15px;
    }

    p {
      line-height: 1.7;
      color: #333;
    }

    .newsletter {
      background: var(--dark);
      color: var(--light);
      padding: 40px;
      border-radius: 10px;
      text-align: center;
    }

    .newsletter h3 {
      margin-bottom: 10px;
      font-size: 1.6rem;
    }

    .newsletter p {
      opacity: 0.9;
      margin-bottom: 20px;
    }

    .newsletter form {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      gap: 10px;
    }

    .newsletter input[type="email"] {
      padding: 12px 15px;
      border: none;
      border-radius: 5px;
      width: 250px;
      font-size: 1rem;
    }

    .newsletter button {
      background: var(--primary);
      border: none;
      padding: 12px 25px;
      border-radius: 5px;
      color: var(--light);
      font-weight: 600;
      cursor: pointer;
      transition: 0.3s;
    }

    .newsletter button:hover {
      background: #005bb5;
    }

    footer {
      background: var(--dark);
      color: var(--light);
      text-align: center;
      padding: 20px;
      margin-top: 50px;
    }

    footer a {
      color: var(--primary);
      text-decoration: none;
    }

    @media (max-width: 600px) {
      header h1 {
        font-size: 2rem;
      }
      main {
        padding: 20px;
      }
      .newsletter input[type="email"] {
        width: 100%;
      }
    }
  </style>
</head>

<body>
  <header>
    <h1>Ganhe Dinheiro Online</h1>
    <p>Aprenda estratégias reais para construir renda pela internet</p>
  </header>

  <main>
    <section>
      <h2>1. Marketing de Afiliados</h2>
      <p>
        Promova produtos digitais ou físicos e receba comissões por cada venda
        realizada. Plataformas como Hotmart, Eduzz e Amazon Afiliados são ótimos pontos de partida.
      </p>
    </section>

    <section>
      <h2>2. Criação de Conteúdo</h2>
      <p>
        Use YouTube, TikTok, Instagram ou blogs para criar conteúdo e monetizar
        com anúncios, parcerias e produtos próprios. A consistência é o segredo
        do sucesso.
      </p>
    </section>

    <section>
      <h2>3. Freelancing e Serviços Online</h2>
      <p>
        Ofereça seus serviços em plataformas como Workana, Upwork e Fiverr. Há
        demanda constante por design, redação, programação e marketing digital.
      </p>
    </section>

    <section>
      <h2>4. Crie Produtos Digitais</h2>
      <p>
        Desenvolva e-books, cursos ou templates. Produtos digitais permitem
        escala, já que você vende sem precisar de estoque físico.
      </p>
    </section>

    <section>
      <h2>5. Investimentos Online</h2>
      <p>
        Aprenda a investir com segurança em ativos digitais, fundos e ações.
        Lembre-se: conhecimento é essencial antes de aplicar dinheiro.
      </p>
    </section>

    <div class="newsletter">
      <h3>Receba dicas exclusivas no seu e-mail!</h3>
      <p>Cadastre-se e aprenda novas formas de ganhar dinheiro online toda semana.</p>
      <form onsubmit="return enviarEmail(event)">
        <input type="email" id="email" placeholder="Seu e-mail" required />
        <button type="submit">Quero Receber</button>
      </form>
      <p id="mensagem" style="margin-top: 15px; font-size: 0.95rem;"></p>
    </div>
  </main>

  <footer>
    <p>© 2025 - Ganhe Dinheiro Online | Desenvolvido por <a href="#">Você</a></p>
  </footer>

  <script>
    function enviarEmail(event) {
      event.preventDefault();
      const email = document.getElementById("email").value;
      const msg = document.getElementById("mensagem");
      msg.textContent = "Obrigado! Seu e-mail foi cadastrado com sucesso.";
      msg.style.color = "#00c853";
      document.getElementById("email").value = "";
      return false;
    }
  </script>
</body>
</html>
