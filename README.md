<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <title>Personal Portfolio Page</title>

  <link rel="stylesheet" type="text/css" href="CSS/style.css">
  <script src="https://kit.fontawesome.com/6316d7bce1.js" crossorigin="anonymous"></script>
</head>

<body>
  <!--Barra de navegação-->
  <nav>
    <ul id="nav-principal" class="nav-principal">
      <li>
        <a href="#">Home</a>
      </li>
      <li>
        <a href="#sobre-nos">Sobre Nós</a>
      </li>
      <li>
        <a href="#servicos">Serviços</a>
      </li>
      <li>
        <a href="#contato">Contato</a>
      </li>
      <li>
        <a href="#">Externo</a>
      </li>
      <li class="icon">
        <a href="javascript:void(0);" onclick="myFunction()">
          <i class="fa fa-bars"></i>
        </a>
      </li>
    </ul>
  </nav>

  <!--Primeira dobra com parallax-->
  <main>
    <header id="cabecalho" class="cabecalho">
      <h1>Conquer</h1>
      <h2>Template de página única</h2>
    </header>

    <!--Layout responsivo em três colunas-->
    <section id="sobre-nos" class="container">
      <div class="card">
        <img src="images/1-1.jpg" alt="">
        <h3>Bootstrap v3.3.6</h3>
        <p>
          Morbi sagittis justo a velit placerat ullamcorper quis quis velit. Sed convallis at risus ullamcorper auctor. Praesent quis velit neque. Quisque semper porta nisi vitae suscipit. Duis lectus magna, ornare ac scelerisque.
        </p>
        <a class="btn btn-green">
          Button Green
        </a>
      </div>

      <div class="card">
        <img src="images/1-2.jpg" alt="">
        <h3>Responsive Design</h3>
        <p>
          Conquer Template is provided by TemplateMo for free of charge. You can use this template for any kind of website. No credit link is required. All images by Unsplash. Thank you for visiting our website. Please come again!
        </p>
        <a class="btn btn-blue">
          See Details
        </a>
      </div>

      <div class="card">
        <img src="images/1-3.jpg" alt="">
        <h3>Parallax Layout</h3>
        <p>
          Morbi sagittis justo a velit placerat ullamcorper quis quis velit. Sed convallis at risus ullamcorper auctor. Praesent quis velit neque. Quisque semper porta nisi vitae suscipit. Duis lectus magna, ornare ac scelerisque.
        </p>
        <a class="btn btn-red">
          Button Red
        </a>
      </div>
    </section>

    <!--Layout responsivo em duas colunas-->
    <section class="container">
      <div class="card">
        <img src="images/2-1.jpg" alt="">
        <h3>Two Column Left Side</h3>
        <p>
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam tempor eros eget eros maximus, ut cursus sem euismod. Donec iaculis tristique odio at consectetur. Nullam dignissim varius suscipit. Sed in leo sit amet velit finibus pretium.
        </p>
        <p>
          Vestibulum vel mauris at erat mattis accumsan et ac lorem. Cras non venenatis orci, sed tincidunt massa. Duis nisl lectus, auctor eu sodales at, dignissim eu orci. Sed vitae venenatis magna, in blandit metus.
        </p>
      </div>
      <div class="card">
        <img src="images/2-2.jpg" alt="">
        <h3>Two Column Right Side</h3>
        <p>
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam tempor eros eget eros maximus, ut cursus sem euismod. Donec iaculis tristique odio at consectetur. Nullam dignissim varius suscipit. Sed in leo sit amet velit finibus pretium.
        </p>
        <p>
          Vestibulum vel mauris at erat mattis accumsan et ac lorem. Cras non venenatis orci, sed tincidunt massa. Duis nisl lectus, auctor eu sodales at, dignissim eu orci. Sed vitae venenatis magna, in blandit metus.
        </p>
        <a class="btn btn-light">
          Read More
        </a>
      </div>
    </section>

    <!--Outro parallax-->
    <section id="servicos" class="servicos">
      <h3>Nossos Serviços</h3>
      <p>Nunc diam leo, fringilla vulputate elit lobortis, consectetur vestibulum quam. Sed id felis ligula. In euismod libero at magna dapibus, in rutrum velit lacinia. Etiam a mi quis arcu varius condimentum.</p>
    </section>

    <!--Design responsivo em quatro colunas-->
    <section class="container">
      <div class="card">
        <img src="images/4-1.jpg" alt="">
        <h3>Coluna um</h3>
        <p>
          Ut ac odio scelerisque ante ornare commodo. Sed faucibus dui libero, in tincidunt purus pretium quis. Fusce posuere egestas enim eu viverra.
        </p>
      </div>

      <div class="card">
        <img src="images/4-2.jpg" alt="">
        <h3>Coluna dois</h3>
        <p>
          Ut ac odio scelerisque ante ornare commodo. Sed faucibus dui libero, in tincidunt purus pretium quis. Fusce posuere egestas enim eu viverra.
        </p>
        <a class="btn btn-light">
          Leia Mais
        </a>
      </div>

      <div class="card">
        <img src="images/4-3.jpg" alt="">
        <h3>Coluna três</h3>
        <p>
          Ut ac odio scelerisque ante ornare commodo. Sed faucibus dui libero, in tincidunt purus pretium quis. Fusce posuere egestas enim eu viverra.
        </p>
      </div>

      <div class="card">
        <img src="images/4-4.jpg" alt="">
        <h3>Coluna quatro</h3>
        <p>
          Ut ac odio scelerisque ante ornare commodo. Sed faucibus dui libero, in tincidunt purus pretium quis. Fusce posuere egestas enim eu viverra.
        </p>
        <a class="btn btn-light">
          detalhes
        </a>
      </div>
    </section>

    <!--Uma seção de coluna única-->
    <section class="container">
      <div class="card">
        <img src="images/4-5.jpg" alt="">
        <h3>One big section</h3>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam tempor eros eget eros maximus, ut cursus sem euismod. Donec iaculis tristique odio at consectetur. Nullam dignissim varius suscipit. Sed in leo sit amet velit finibus pretium. Vivamus
          dictum nisi ac fermentum interdum. Vestibulum vel mauris at erat mattis accumsan et ac lorem. Cras non venenatis orci, sed tincidunt massa. Duis nisl lectus, auctor eu sodales at, dignissim eu orci. Sed vitae venenatis magna, in blandit metus.
          Praesent volutpat cursus rhoncus. Aenean arcu diam, suscipit ac neque in, sollicitudin convallis orci.</p>
        <p>Fusce eu porta massa, sed tincidunt turpis. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Vivamus a urna tellus. Integer pharetra vitae nisi et lacinia. Morbi sagittis justo a velit placerat ullamcorper
          quis quis velit. Sed convallis at risus ullamcorper auctor. Praesent quis velit neque. Quisque semper porta nisi vitae suscipit. Duis lectus magna, ornare ac scelerisque quis, maximus eget nisi.</p>
        <a class="btn btn-light">
          Leia Mais
        </a>
      </div>
    </section>

    <!--Um formulário de contato-->
    <section id="contato" class="contato">
      <h3>Contato</h3>
      <p>Nunc diam leo, fringilla vulputate elit lobortis, consectetur vestibulum quam. Sed id felis ligula. In euismod libero at magna dapibus, in rutrum velit lacinia. Etiam a mi quis arcu varius condimentum</p>
      <form>
        <input type="text" name="nome" id="nome" placeholder="Seu nome">
        <input type="email" name="email" id="email" placeholder="Seu e-mail">
        <input type="text" name="assunto" id="assunto" placeholder="Assunto">
        <input type="textarea" name="mensagem" id="mensagem" placeholder="Digite sua mensagem aqui...">
      </form>
      <br>
      <a class="btn btn-dark">
        Enviar
      </a>
    </section>
  </main>

  <!--Um rodapé-->
  <footer class="rodape">
    <h4>Use livremente!!</h4>
    <p>“Conquer is free Bootstrap template from TemplateMo website. No backlink is required to use this layout.”</p>
    <hr>
    <span>Copyright © 2045 Your Company Name | Design: TemplateMo</span>
  </footer>
</body>

<script>
  function myFunction() {
    let x = document.getElementById("nav-principal");
    if (x.className === "nav-principal") {
      x.className += " responsive";
    } else {
      x.className = "nav-principal";
    }
  }
</script>

</html>
