<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <title>Do Campo à Cidade</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: #f0f8f5;
    }

    header {
      background-color: #4CAF50;
      color: white;
      padding: 20px;
      text-align: center;
    }

    h1 {
      margin: 0;
    }

    .container {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      padding: 30px;
      gap: 20px;
    }

    .card {
      background-color: white;
      width: 300px;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
      overflow: hidden;
      transition: transform 0.3s ease;
    }

    .card:hover {
      transform: scale(1.03);
    }

    .card img {
      width: 100%;
      height: 180px;
      object-fit: cover;
    }

    .card-content {
      padding: 15px;
    }

    .card-content h3 {
      margin: 0 0 10px;
      color: #4CAF50;
    }

    details {
      margin-top: 10px;
      font-size: 15px;
    }

    footer {
      background-color: #e0e0e0;
      padding: 10px;
      text-align: center;
      font-size: 14px;
      color: #555;
    }
  </style>
</head>
<body>

<header>
  <h1>Do Campo à Cidade 🌾🏙️</h1>
  <p>Festejando a conexão que alimenta, movimenta e inspira!</p>
</header>

<main class="container">

  <!-- Card 1 -->
  <div class="card">
    <img src="images.jpg" alt="Pão artesanal">
    <div class="card-content">
      <h3>🥖 Pão Caseiro</h3>
      <details>
        <summary>Do campo à cidade</summary>
        <p>O trigo é cultivado no campo, colhido e levado ao moinho. Depois, nas padarias da cidade, transforma-se em alimento na mesa das famílias urbanas.</p>
      </details>
    </div>
  </div>

  <!-- Card 2 -->
  <div class="card">
    <img src="138365-como-comprar-maquinas-agricolas-sem-erros.jpg" alt="Trator moderno">
    <div class="card-content">
      <h3>🚜 Trator Inteligente</h3>
      <details>
        <summary>Do campo à cidade</summary>
        <p>Desenvolvido com alta tecnologia urbana, o trator moderno otimiza colheitas e retorna à cidade como símbolo de inovação e produção sustentável.</p>
      </details>
    </div>
  </div>

  <!-- Card 3 -->
  <div class="card">
    <img src="araucaria.jpeg" alt="" srcset="">
    <div class="card-content">
      <h3>🎉 ARAUCARIAS </h3>
      <details>
        <summary>Dos tempos antigos aos tempos atuais</summary>
        <p>A araucária é uma árvore que chegou ao Paraná há cerca de 15 mil anos, tendo uma longa história de adaptação ao clima e uso pelos povos indígenas, que utilizavam seus pinhões e madeira. Com a chegada dos europeus, a exploração intensificou-se, causando desmatamento e devastação, especialmente no século XX. Hoje, a araucária está em perigo crítico, com sua área de ocorrência reduzida pela metade nos últimos 10 anos, ameaçando não só ela, mas também outras espécies que dependem dela. A degradação do habitat, o desmatamento, a crise climática e a falta de ações de conservação colocam sua sobrevivência em risco no Paraná e no Brasil..</p>
      </details>
    </div>
  </div>

</main>

<footer>
  <p>&copy; 2025 - Projeto Agrinho: Conexão Campo-Cidade</p>
</footer>

</body>
</html>
