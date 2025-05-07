<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Guia de Estudos - Sistemas e IA</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <h1>Guia de Estudos</h1>
    <nav>
      <button onclick="navigate('sistemas')">Sistemas Digitais</button>
      <button onclick="navigate('ia')">Inteligência Artificial</button>
    </nav>
  </header>

  <main>
    <section id="sistemas">
      <h2>🧠 Sistemas Digitais</h2>
      <div class="topic">
        <h3>1. Pipeline</h3>
        <p>Execução de instruções em etapas simultâneas para melhorar o desempenho do processador.</p>
      </div>
      <div class="topic">
        <h3>2. Instruções RISC e CISC</h3>
        <p><strong>RISC</strong>: poucas instruções simples (ex: ARM, MIPS).<br><strong>CISC</strong>: muitas instruções complexas (ex: x86).<br>RISC = performance. CISC = flexibilidade.</p>
      </div>
      <div class="topic">
        <h3>3. Tabela Verdade - Display de 7 Segmentos</h3>
        <p>A tabela verdade é uma tabela usada para mostrar todos os possíveis valores de entrada e os resultados correspondentes de uma expressão lógica ou circuito digital. Ela ajuda a visualizar como as portas lógicas (AND, OR, NOT, XOR, etc.) vão funcionar com diferentes combinações de entradas.
            O display de 7 segmentos é um tipo de display eletrônico usado para exibir números e algumas letras. Ele é formado por 7 LEDs dispostos de maneira que formam um número 8 no visual, mas podem ser acesos de diferentes maneiras para mostrar outros números ou letras. Como funciona? Cada segmento do display pode ser aceso ou apagado individualmente. Com a combinação dos segmentos, podemos representar números de 0 a 9 (e algumas letras de A a F, se for um display de 7 segmentos com 16 possibilidades).
        </p>
      </div>
      <div class="topic">
        <h3>4. MUX / DEMUX</h3>
        <p><strong>MUX</strong>: várias entradas, uma saída.<br><strong>DEMUX</strong>: uma entrada, várias saídas.<br>Usados para seleção e distribuição de dados em sistemas digitais.
            MUX (Multiplexador) Um multiplexador é um circuito digital que recebe várias entradas e escolhe qual delas deve ser enviada para a saída, de acordo com um controle. Exemplo: Um MUX de 2 entradas (2-to-1 MUX) tem 2 linhas de entrada, 1 linha de controle e 1 linha de saída. Com o controle, você escolhe qual das 2 entradas vai sair.</p>
      </div>
    </section>

    <section id="ia" style="display: none">
      <h2>🤖 Inteligência Artificial</h2>

      <div class="topic">
        <h3>1. Introdução à Inteligência Artifi cial</h3>
        <p>Estudo de agentes capazes de tomar decisões e aprender com dados.</p>
        <iframe src="https://www.youtube.com/embed/s72TlLlHBwg" frameborder="0" allowfullscreen></iframe>
      </div>

      <div class="topic">
        <h3>2. Agentes Inteligentes</h3>
        <p>Entidades que percebem o ambiente e agem para alcançar objetivos.</p>
        <iframe src="https://www.youtube.com/embed/jZY2-DXdVCs" frameborder="0" allowfullscreen></iframe>
      </div>

      <div class="topic">
        <h3>3. Sistemas MultiAgente</h3>
        <p>Vários agentes interagindo entre si, cooperando ou competindo.</p>
        <iframe src="https://www.youtube.com/embed/0DTRehLGFm8" frameborder="0" allowfullscreen></iframe>
      </div>

      <div class="topic">
        <h3>4. Inteligência Distribuída</h3>
        <p>Distribuição de inteligência entre múltiplas unidades autônomas.</p>
        <iframe src="https://www.youtube.com/embed/urC7rtghvRI" frameborder="0" allowfullscreen></iframe>
      </div>

      <div class="topic">
        <h3>5. Matriz de Confusão</h3>
        <p>Tabela para avaliar desempenho de classificadores (TP, TN, FP, FN).</p>
        <iframe src="https://www.youtube.com/embed/FZqMCgCbo3U" frameborder="0" allowfullscreen></iframe>
      </div>

      <div class="topic">
        <h3>6. Variáveis Numéricas</h3>
        <p>Dados quantitativos usados como entrada em modelos de IA.</p>
        <iframe src="https://www.youtube.com/embed/ZWTU41DW_I8" frameborder="0" allowfullscreen></iframe>
      </div>

      <div class="topic">
        <h3>7. Árvore de Decisão</h3>
        <p>Modelo baseado em decisões binárias para classificação e regressão.</p>
        <iframe src="https://www.youtube.com/embed/aNrdgC0lIZ8" frameborder="0" allowfullscreen></iframe>
      </div>

      <div class="topic">
        <h3>8. Entropia</h3>
        <p>Medida de incerteza usada em árvores de decisão para dividir os dados.</p>
        <iframe src="https://www.youtube.com/embed/qjHfkfIs1Ug" frameborder="0" allowfullscreen></iframe>
      </div>

      <div class="topic">
        <h3>9. Redes Neurais</h3>
        <p>Modelos computacionais inspirados no cérebro humano para aprendizado profundo.</p>
        <iframe src="https://www.youtube.com/embed/1_c_MA1F-vU" frameborder="0" allowfullscreen></iframe>
      </div>

      <div class="topic">
        <h3>10. Neurônio Artificial</h3>
        <p>Unidade básica das redes neurais, realiza soma ponderada e função de ativação.</p>
        <iframe src="https://www.youtube.com/embed/QPwDmx0VYpY" frameborder="0" allowfullscreen></iframe>
      </div>

      <div class="topic">
        <h3>11. Classificação e Regressão</h3>
        <p><strong>Classificação</strong>: prever categorias (ex: spam ou não spam).<br><strong>Regressão</strong>: prever valores contínuos (ex: preço de uma casa).</p>
        <iframe src="https://www.youtube.com/embed/tvCw48-Xn8Q" frameborder="0" allowfullscreen></iframe>
      </div>

    </section>
  </main>

  <script src="script.js"></script>
</body>
</html>



/* CSS: styles.css */
@import url('https://fonts.googleapis.com/css2?family=Open+Sans:wght@400;600;700&display=swap');

* {
  box-sizing: border-box;
  scroll-behavior: smooth;
}

body {
  font-family: 'Open Sans', sans-serif;
  background-color: #121212;
  margin: 0;
  padding: 0;
  color: #fff;
  transition: background 0.5s, color 0.5s;
}

body.light-mode {
  background-color: #f4f4f4;
  color: #121212;
}

header {
  background: linear-gradient(90deg, #1db954 0%, #1ed760 100%);
  color: white;
  padding: 2rem 1rem;
  text-align: center;
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.5);
  animation: fadeIn 1s ease-out;
}

header h1 {
  margin: 0;
  font-size: 2.5rem;
  font-weight: 700;
  letter-spacing: -1px;
}

.toggle-mode {
  position: fixed;
  top: 15px;
  right: 15px;
  background: #1db954;
  color: #121212;
  border: none;
  border-radius: 50px;
  padding: 10px 20px;
  cursor: pointer;
  font-weight: bold;
  z-index: 1000;
  transition: background 0.3s;
}

.toggle-mode:hover {
  background: #1ed760;
}

#backToTop {
  display: none;
  position: fixed;
  bottom: 20px;
  right: 20px;
  z-index: 999;
  font-size: 16px;
  border: none;
  outline: none;
  background-color: #1db954;
  color: white;
  cursor: pointer;
  padding: 12px;
  border-radius: 50%;
  box-shadow: 0 4px 8px rgba(0,0,0,0.3);
  transition: background 0.3s;
}

#backToTop:hover {
  background-color: #1ed760;
}

nav {
  margin-top: 1.5rem;
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
  gap: 10px;
  animation: slideIn 1s ease-out;
}

nav button {
  padding: 12px 28px;
  background-color: transparent;
  color: #1db954;
  border: 2px solid #1db954;
  border-radius: 999px;
  cursor: pointer;
  font-weight: 600;
  font-size: 1rem;
  transition: all 0.3s ease;
}

nav button:hover {
  background-color: #1db954;
  color: #121212;
  transform: scale(1.05);
}

main {
  padding: 40px 20px;
  max-width: 960px;
  margin: auto;
  animation: fadeIn 1s ease-in;
}

h2 {
  font-size: 2rem;
  color: #1db954;
  margin-bottom: 1.5rem;
  border-bottom: 2px solid #1db954;
  padding-bottom: 0.5rem;
}

.topic {
  background: #181818;
  border: 1px solid #282828;
  margin-bottom: 30px;
  padding: 24px;
  border-radius: 14px;
  box-shadow: 0 8px 16px rgba(0, 0, 0, 0.3);
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

body.light-mode .topic {
  background: #ffffff;
  color: #121212;
  border: 1px solid #ccc;
}

.topic:hover {
  transform: translateY(-5px);
  box-shadow: 0 12px 24px rgba(0, 0, 0, 0.5);
}

.topic h3 {
  margin-top: 0;
  color: #1db954;
  font-size: 1.4rem;
  font-weight: 600;
}

.topic p {
  line-height: 1.7;
  color: #d1d1d1;
  margin-top: 0.5rem;
}

body.light-mode .topic p {
  color: #222;
}

.topic iframe {
  width: 100%;
  height: 340px;
  margin-top: 16px;
  border-radius: 8px;
  border: none;
  box-shadow: 0 0 14px rgba(0, 0, 0, 0.5);
}

@keyframes fadeIn {
  from { opacity: 0; transform: translateY(20px); }
  to { opacity: 1; transform: translateY(0); }
}

@keyframes slideIn {
  from { opacity: 0; transform: translateX(-20px); }
  to { opacity: 1; transform: translateX(0); }
}

@media screen and (max-width: 768px) {
  nav button {
    width: 100%;
    margin: 8px 0;
  }

  main {
    padding: 20px 10px;
  }

  .topic iframe {
    height: 220px;
  }
}

function navigate(sectionId) {
    document.querySelectorAll("main section").forEach(sec => {
      sec.style.display = "none";
    });
    document.getElementById(sectionId).style.display = "block";
  }
  
  navigate("sistemas");  
