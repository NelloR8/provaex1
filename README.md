# provaex1
<!DOCTYPE html>
<html lang="it">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Sito Prov </title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
  <style>
    body {
      background-color: #f8f9fa;
    }
    .navbar {
      box-shadow: 0 4px 6px rgba(0,0,0,0.1);
      margin-bottom: 30px;
    }
    .carousel img{
      border-radius: 15px;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
    }

    #carousel{ margin-bottom: 30px;}

      

     #mappa{ margin-top: 30px;}
    
    h2 {
      margin-bottom: 30px;
      font-weight: bold;
    }
    
  </style>
</head>
<body>

 
  <nav class="navbar navbar-expand-lg navbar-dark bg-primary sticky-top">
    <div class="container">
      <a  class="navbar-brand" href="#">Sito</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse justify-content-end" id="navbarNav">
        <ul class="navbar-nav">
          <li class="nav-item"><a class="nav-link active" href="#">Galleria</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Video</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Mappa</a></li>
        </ul>
      </div>
    </div>
  </nav>

  
  <div id="carousel" class="container text-center">
    <h2 class="text-center text-primary">Slydegalley</h2>
    <div id="carouselExample" class="carousel slide" data-bs-ride="carousel">
      <div class="carousel-inner">
        <div class="carousel-item active">
          <img src="https://picsum.photos/1000/500?random=1" class="d-block w-100" alt="Slide 1">
        </div>
        <div class="carousel-item">
          <img src="https://picsum.photos/1000/500?random=2" class="d-block w-100" alt="Slide 2">
        </div>
        <div class="carousel-item">
          <img src="https://picsum.photos/1000/500?random=3" class="d-block w-100" alt="Slide 3">
        </div>
      </div>
      <button class="carousel-control-prev" type="button" data-bs-target="#carouselExample" data-bs-slide="prev">
        <span class="carousel-control-prev-icon"></span>
      </button>
      <button class="carousel-control-next" type="button" data-bs-target="#carouselExample" data-bs-slide="next">
        <span class="carousel-control-next-icon"></span>
      </button>
    </div>
</div>

  
  <div id="video" class="bg-white">
    <div class="container text-center">
      <h2 class="text-primary ">Video</h2>
      <div class="ratio ratio-16x9 mx-auto" style="max-width: 600px;">
        <iframe width="560" height="315" src="https://www.youtube.com/embed/DbGPU1qTt10?si=pCg3wT6F5W1l61cW" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
      </div>
    </div>
</div>

 
  <div id="mappa" class="container">
    <h2 class="text-center text-primary">Mappa di Roma</h2>
    <div class="ratio ratio-16x9 mx-auto" style="max-width: 600px;">
      <iframe src="https://www.google.com/maps?q=Roma,+Italia&output=embed" allowfullscreen loading="lazy"></iframe>
    </div>
  </div>

 

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
