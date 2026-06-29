<!DOCTYPE html>
<html>

<head>
  <title>Introdução</title>
      <style>
          body {
            background-color: #121212;
            color: white; /*Isso aqui define o estilo do negócio*/
            font-family: Arial;
        }
        .block {
            background-color: #2b2b2b;
            padding: 20px;
            border-radius: 15px; /*Se eu colocar um "block" dentro de uma <div class= "#"> vai ficar com um estilo de card */
            margin-bottom: 30px;
            box-shadow: 0px 0px 10px black;
        }
        h1 {
            color: red;
            text-align: center;
            font-size: 50px;
        }
        button {
          color: black;
          width: 250px;
          height: 50px; /*E isso define o tamanho do botão*/
          font-size: 20px;
          
          display: block;        /* Transforma o botão em bloco */
          margin-left: auto;     /* Empurra para a direita */
          margin-right: auto;    /* Empurra para a esquerda */
        }

        }
        img {
            width: 250px; /*Essa budega faz o formato da imagem*/
            border-radius: 15px;
            
            display: block;
            margin-left: auto;
            margin-right: auto; /* E essa budega centraliza todas as imagens*/
            max-width: 100%;
            height: auto;
         }
         .gif {
            text-align: center;
         }
          h4 {
             text-align: center;
             font-size: 25px;
             color: #2b2b2b;
             background-color: #444444;
          }
          p  {
             text-align: center;
             font-size: 18px;
          }
      </style>
</head>
<body>
   
  <div class="block">   
      <h1>Você entrou!</h1>
    <p>Para explorar, escolha o conteúdo desejado.</p>
  </div>
      <div class="block">
          <br><a href="Conteúdo-jogos.html" class="container" target="_blank">
              <button style="background-color: #ff073a">Jogos</button>
          </a>
        <br>
          <a href="Conteúdo-Streaming.html" class="container" target="_blank">
              <button style="background-color: #FF5C00">Streaming</button>
          </a>
        <br>
          <a href="Desktop mode.html" class="container" target="_blank">
              <button style="background-color: #FFDE21">Desktop mode</button>
          </a>
        <br>
          <a href="minigames.html" class="container" target="_blank">
              <button style="background-color: #39FF14">Minigames</button>
          </a>
        <br>
          <a href="calculadora.html" class="container" target="_black">
              <button style="background-color: #1F51FF">Calculadora</button>
          </a>
        <br>
          <a href="recomendacoes.html">
              <button style="background-color: #8a00c4">Recomendações de jogos</button>
          </a>
        <br>
          <a href="tarefaV.html" class="container" target="_blank">
              <button style="background-color: #BC13FE">Lista de tarefas</button>
          </a>
              <br><div class="gif">
                <img src="https://c.tenor.com/nYyGRI9Ogu8AAAAd/tenor.gif" alt="gif">
              </div>
      <div id="menssagemSair()"class="sair">
          <a href="new_email.html" class="container" target="_blank"> 
              <br><button style="background-color: #808080">Sair ></button>
          </a>
      </div>
      <br><div class="block">
          <h3>Colaborador(a): Alice Silva Pereira</h3>
        <hr>
          <h3>Tecnologias/ linguagens:<br>
              — HTML5<br>
              — CSS3<br>
              — JavaScript<br>
          </h3>
        
        <h4>Avalie-nos!!</h4>
        <input type="radio" name="avaliacao" value="1">
        <label id="avaliacao">1⭐</label>
        <input type="radio" name="avaliacao" value="2">
        <label id="avaliacao">2⭐</label>
        <input type="radio" name="avaliacao" value="3">
        <label id="avaliacao">3⭐</label>
        <input type="radio" name="avaliacao" value="4">
        <label id="avaliacao">4⭐</label>
        <input type="radio" name="avaliacao" value="5">
        <label id="avaliacao">5⭐</label>
      </div> 
      
      
      <script>
        var nome = prompt("INSIRA SEU NICKNAME!");
        alert("Conta conectada com sucesso! Bem-vindo(a)" + nome);
    </script>
</body>
</html>