<svelte:head>
	<meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
	<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.0/css/bootstrap.min.css" integrity="sha384-9aIt2nRpC12Uk9gS9baDl411NQApFmC26EwAOH8WgZl5MYYxFfc+NcPb1dKGj7Sk" crossorigin="anonymous">
	<link rel="stylesheet" href="style.css">
</svelte:head>
<sapper:scripts>
	<script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
	<script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js" integrity="sha384-Q6E9RHvbIyZFJoft+2mJbHaEWldlvI9IOYy5n3zV9zzTtmI3UksdQRVvoxMfooAo" crossorigin="anonymous"></script>
	<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.0/js/bootstrap.min.js" integrity="sha384-OgVRvuATP1z7JjHLkuOU7Xw704+h835Lr+6QL9UvYjZE3Ipu6Tp75j7Bh/kR0JKI" crossorigin="anonymous"></script>
</sapper:scripts>

<nav class="navbar fixed-top navbar-expand-lg">
      <div class="container">
        <a class="navbar-brand" href="#">
          <img class="logo" src="./images/agro_logo.png">
        </a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
      </div>
      
    </nav>

<section class="jumbotron">
    <div class="container">
        <div class="row">
            <div class="col col-md-6">
                <h1 class="display-4 mb-4">
                    Produtos da fazenda, frescos, entregues na sua casa
                </h1>

            <div class="row">
              <div class="col d-none d-md-block">
                <p class="mb-5">
                  Tenha as melhores frutas, verduras, legumes e diversos outros produtos naturais entregues no conforto da sua casa em até um dia. Aqui, conectamos o pequeno produtor rural com você, sendo tudo isso por um preço acessível e sem taxa de entrega.
                </p>
                <a href="sdf" id="register" class="btn btn-warning">Cadastre-se</a>
                <div class="row mt-5">
                  <div class="col-md-1">
                    <img src="./images/face.svg" alt="" class="src">
                  </div>

                  <div class="col-md-1">
                    <img src="./images/instagram.svg" alt="" class="src">
                  </div>
                </div>
              </div>
            </div>
          </div>

          <div class="col-xs-12 col-md-6">
            <img class="img-fluid img-cesta" src="./images/homemcesta.svg" alt="">
          </div>

          <div class="row">
            <div class="col d-xs-block d-md-none text-box">
              <p class="mt-4 mb-5">
                Tenha as melhores frutas, verduras, legumes e diversos outros produtos naturais entregues no conforto da sua casa em até um dia. Aqui, conectamos o pequeno produtor rural com você, sendo tudo isso por um preço acessível e sem taxa de entrega.
              </p>
              <div class="text-center">
                <a href="#" id="register" class="btn btn-warning">Cadastre-se</a>
              </div>
              
              <div class="row justify-content-center mt-5 pb-4">
                <div class="col-auto">
                  <img src="./images/face.svg" alt="" class="src">
                </div>

                <div class="col-auto">
                  <img src="./images/instagram.svg" alt="" class="src">
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
</section>