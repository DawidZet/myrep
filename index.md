<html lang="en" dir="ltr">
<head>
  <!-- Required meta tags -->
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
  <!-- Bootstrap CSS -->
  <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" integrity="sha384-JcKb8q3iqJ61gNV9KGb8thSsNjpSL0n8PARn9HuZOnIxN0hoP+VmmDGMN5t9UJ0Z" crossorigin="anonymous">
  <link rel="stylesheet" type="text/css"
    href="css/style.css">
  <title>Exercise_2</title>
</head>
<body>
  <div class="container-fluid">
    <div class="jumbotron text-center m-0 p-5">
        <h1 class="text-uppercase font-weight-bold text-dark">Witamy w świecie mebli marki <span class="font-weight-bolder font-italic">Meblikowo</span></h1>
    </div>
    <!-- Navbar -->
    <div class="navbar-div sticky-top">
      <nav class="navbar d-flex navbar-expand bg-dark navbar-dark text-success font-weight-bold sticky-top">
        <a class="navbar-brand" href="#">Nasza firma</a>
        <!-- navbar-center is custom defined -->
        <ul class="navbar-nav navbar-center">
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle" href="#" id="navbardrop" data-toggle="dropdown">Nasze produkty</a>
            <div class="dropdown-menu">
              <a class="dropdown-item" href="#">Meble biurowe</a>
              <a class="dropdown-item" href="#">Krzesła</a>
              <a class="dropdown-item" href="#">Pościel</a>
            </div>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">O nas</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Kontakt</a>
          </li>
        </ul>
        <!-- Searching buttons -->
        <div class="d-flex ml-auto">
          <form class="form-inline">
            <input class="form-control mr-sm-2" type="text" placeholder="Szukaj">
            <button class="btn btn-success" type="submit">Szukaj</button>
          </form>
        </div>
      </nav>
    </div>
    <!-- Main Content -->
    <div class="row d-flex justify-content-center">
      <div class="col-4">
        <!-- Table title -->
        <table class="table table-hover table-striped table-bordered">
          <caption>Nasze biura</caption>
          <thead>
            <tr class="bg-secondary text-white">
              <th>Miasto</th>
              <th>Ulica</th>
              <th>Osoba kontaktowa</th>
            </tr>
          </thead>
          <tbody>
            <tr>
              <td>Katowice <span class="badge badge-info">Nowa lokalizacja</span></td>
              <td>Morska 3</td>
              <td>Marian Nowak</td>
            </tr>
            <tr>
              <td>Bielsko-Biała</td>
              <td>Mickiewicza 18c</td>
              <td>Marek Ostrowski</td>
            </tr>
            <tr>
              <td>Żywiec</td>
              <td>Wodna</td>
              <td>Anna Kwiatkowska</td>
            </tr>
          </tbody>
        </table>
        <div class="d-flex flex-wrap">
          <h4 class="d-flex justify-content-center text-secondary list-group-header">Sprawdź szczegóły</h4>
          <!-- <div class="d-flex break"></div> -->
          <div class="d-flex flex-grow-1 mt-2 list-group list-group-horizontal">
            <a href="#" class="list-group-item list-group-item-action">Katowice</a>
            <a href="#" class="list-group-item list-group-item-action">Bielsko-Biała</a>
            <a href="#" class="list-group-item list-group-item-action">Żywiec</a>
          </div>
        </div>
      </div>
      <div class="col-4">
        <div id="demo" class="carousel slide pt-3" data-ride="carousel">
          <!-- Indicators -->
          <ul class="carousel-indicators">
            <li data-target="#demo" data-slide-to="0" class="active"></li>
            <li data-target="#demo" data-slide-to="1"></li>
            <li data-target="#demo" data-slide-to="2"></li>
          </ul>
          <!-- The slideshow -->
          <div class="carousel-inner">
            <div class="carousel-item active">
              <img src="HTML_ex_2/images/cat.jpg" alt="cat">
            </div>
            <div class="carousel-item">
              <img src="HTML_ex_2/images/cupboard.jpg" alt="cupboard">
            </div>
            <div class="carousel-item">
              <img src="HTML_ex_2/images/flower.jpg" alt="flower">
            </div>
          </div>
          <!-- Left and right controls -->
          <a class="carousel-control-prev" href="#demo" data-slide="prev">
            <span class="carousel-control-prev-icon"></span>
          </a>
          <a class="carousel-control-next" href="#demo" data-slide="next">
            <span class="carousel-control-next-icon"></span>
          </a>
        </div>
      </div>
      <div class="col-4">
        <!-- Form for user -->
        <form class="mt-3 p-3 w-75 border rounded">
         <div class="form-group">
           <label for="email">Adres email:</label>
           <input type="email" class="form-control" placeholder="Podaj email" id="email">
         </div>
         <div class="form-group">
           <label for="pwd">Hasło:</label>
           <input type="password" class="form-control" placeholder="Podaj hasło" id="pwd">
         </div>
         <!-- Radio buttons -->
         <div class="sex-choice">
           <label for="sex">Płeć:</label>
           <div class="form-check">
             <label class="form-check-label" id="sex">
               <input type="radio" class="form-check-input" name="optradio">Mężczyzna
             </label>
           </div>
           <div class="form-check">
             <label class="form-check-label" id="sex">
               <input type="radio" class="form-check-input" name="optradio">Kobieta
             </label>
           </div>
         </div>
         <div class="form-group form-check pt-3">
           <label class="form-check-label">
             <input class="form-check-input" type="checkbox">Zapamiętaj mnie
           </label>
         </div>
         <button type="submit" class="btn btn-primary">Wyślij</button>
        </form>
      </div>
    </div>
    <div class="row d-flex justify-content-center">
      <div class="col">
        <h2 class="m-3"><span class="badge badge-primary">FAQ</span></h2>
        <div id="accordion">
         <div class="card">
           <div class="card-header">
             <a class="collapsed card-link" data-toggle="collapse" href="#collapseOne">
               Jak długi jest okres gwarancji?
             </a>
           </div>
           <div id="collapseOne" class="collapse show" data-parent="#accordion">
             <div class="card-body">
               2 lata.
             </div>
           </div>
         </div>
         <div class="card">
           <div class="card-header">
             <a class="collapsed card-link" data-toggle="collapse" href="#collapseTwo">
               Gdzie można serwisować meble?
             </a>
           </div>
           <div id="collapseTwo" class="collapse" data-parent="#accordion">
             <div class="card-body">
               Nasze placówki serwisowe znajdują się we wszystkich województwach.
             </div>
           </div>
         </div>
         <div class="card">
           <div class="card-header">
             <a class="collapsed card-link" data-toggle="collapse" href="#collapseThree">
               Czy poza meblami znajdę jeszcze coś ciekawego?
             </a>
           </div>
           <div id="collapseThree" class="collapse" data-parent="#accordion">
             <div class="card-body">
               Oczywiście, oferujemy również artykuły wyposażenia wnętrz.
             </div>
           </div>
         </div>
        </div>
      </div>
    </div>
    <br>
    <ul class="pagination justify-content-center">
      <li class="page-item"><a class="page-link" href="#">Poprzednia</a></li>
      <li class="page-item active"><a class="page-link" href="#">1</a></li>
      <li class="page-item disabled"><a class="page-link" href="#">2</a></li>
      <li class="page-item disabled"><a class="page-link" href="#">3</a></li>
      <li class="page-item"><a class="page-link" href="#">Następna</a></li>
    </ul>
  </div>
  <!-- Optional JavaScript -->
  <!-- jQuery first, then Popper.js, then Bootstrap JS -->
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js" integrity="sha384-B4gt1jrGC7Jh4AgTPSdUtOBvfO8shuf57BaghqFfPlYxofvL8/KUEfYiJOMMV+rV" crossorigin="anonymous"></script>
</body>
</html>
