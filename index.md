
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">

    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-alpha3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-CuOF+2SnTUfTwSZjCXf01h7uYhfOBuxIhGKPbfEJ3+FqH/s6cIFN9bGr1HmAg4fQ" crossorigin="anonymous">

    <title>Hello, world!</title>
  </head>
  <body>
  	<style>
  	.header {
  	background: rgb(255,163,45);
      background: linear-gradient(80deg, rgba(255,163,45,1) 0%, rgba(255,93,201,1) 35%, rgba(0,220,255,1) 100%);
  	}

  .button {
  	background: linear-gradient(to left, #6699ff 0%, #9966ff 68%);
      text-decoration: none;
      width:  50px;
      padding: 20px;
      color: white;
      border: #fff solid 3px;
      transition: 2s ease all;
  	}

  .button:hover {
  	background: linear-gradient(to top right, #9966ff 0%, #ff99ff 68%);
      color: white;  
       width: 500px;

       .garis {
    position: relative;
    top: 50%;
    width: 24em;
    margin: 0 auto;
    border-right: 2px solid rgba(255, 255, 255, 0.75);
    font-size: 180%;
    text-align: center;
    white-space: nowrap;
    overflow: hidden;
    transform: translateY(-50%);
}

.animasi-ketikan {
    animation: ketikan 4s steps(20) 1s 1 normal both,
        kedip 500ms steps(20) infinite normal;
}

@keyframes ketikan {
    from {
        width: 0;
    } to {
        width: 9em;
    }
}

@keyframes kedip {
    from {
        border-right-color: rgba(255, 255, 255, 0.75);
    } to {
        border-right-color: transparent;
    }

}
 	}


  	</style>
  	<div class="header">
   <nav class="navbar navbar-expand-lg navbar-dark">
  <div class="container-fluid">
    <a class="navbar-brand" href="#">Naufal aqilrasyad</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav">
        <li class="nav-item">
          <a class="nav-link active" aria-current="page" href="#">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Features</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Pricing</a>
        </li>
        <li class="nav-item">
          <a class="nav-link disabled" href="#" tabindex="-1" aria-disabled="true">Disabled</a>
        </li>
      </ul>
    </div>
  </div>
</nav>
<br><div class="jumbotron jumbotron-fluid text-white">
  <div class="container">
  	<img src="naufal.png" width="300">
    <h1 class="display-4 ">hi i'm naufal aqilrasyad</h1>
        <p class="animasi-ketikan">web progamer cilik from indonesian, merauke</p>
     <br><a class="button" href="#">about me<a>
                <br><br><h9>.</h9>
 
</div>
</div>


    <!-- Optional JavaScript; choose one of the two! -->

    <!-- Option 1: Bootstrap Bundle with Popper.js -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-alpha3/dist/js/bootstrap.bundle.min.js" integrity="sha384-popRpmFF9JQgExhfw5tZT4I9/CI5e2QcuUZPOVXb1m7qUmeR2b50u+YFEYe1wgzy" crossorigin="anonymous"></script>

    <!-- Option 2: Separate Popper.js and Bootstrap JS
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-alpha3/dist/js/bootstrap.min.js" integrity="sha384-t6I8D5dJmMXjCsRLhSzCltuhNZg6P10kE0m0nAncLUjH6GeYLhRU1zfLoW3QNQDF" crossorigin="anonymous"></script>
    -->
  </body>
</html>
