
<html lang="en">

  body {
      margin: 0;
      overflow: hidden;
 
    }

    video {
      position: absolute;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      min-width: 100%;
      min-height: 100%;
      width: auto;
      height: auto;
      z-index: -1;
    }
    
    content {
      z-index: 1;
    }

    
  </style>
</head>
<body>
  <video autoplay loop controls>
    <source src="video/gokil.mp4" type="video/mp4">
  </video>
  <div id="lyrics"></div>

  <div class="content">
    <h1></h1>
    
  </div>
</body>
</style>
<body>
    

  <div class="paper image">
    <p>Untuk ku</p>
    <img src="gambar/gambar4.jpeg" />
  </div>

  <div class="paper image">
    <p>Kau</p>
    <img src="gambar/gambar3.jpeg" />
  </div>
  <div class="paper image">
    <p>Yang memilih</p>
    <img src="gambar/gambar2.jpeg" />
  </div>
  <div class="paper image">
    <p>Inilah aku</p>
    <img src="gambar/gambar1.jpeg" />
  </div>

 

  <script  src="card.js"></script>
</body>
</html>
