<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Podverse</title>
  <!-- Fonts -->
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;700&display=swap" rel="stylesheet">
  <link href="https://fonts.googleapis.com/css2?family=Bricolage+Grotesque:wght@400;500;700&display=swap" rel="stylesheet">
     <!-- Font Awesome CDN -->
<link
  rel="stylesheet"
  href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css"
/>

  <!-- Bootstrap CSS CDN -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">

  <!-- Internal CSS -->
  <style>
    body {
      background-color: #000;
    }
    .container .main-menu{
        max-width: 1300px !important;
    }
    @media (max-width: 1300px) {
    .container, .container-lg, .container-md, .container-sm, .container-xl {
        max-width: 1300px;
    }
}

    .logo img{
        width: auto !important;
        height: 46.15px !important;
        padding: 0 !important;
    }
    .col-4.logo{
        padding: 0px !important;
    }
    .h-btn a{
    border-radius: 5px;
    border: 1px solid;
    border-color: #d32f2f;
    background-color: transparent;
    color: #d32f2f;
    font-family: 'Inter' sans-serif;
    font-size: 17.6px;
    font-weight: 500;
    text-decoration: inherit;
    height: 47.45px !important;
    line-height: 19px;
    padding: 12px 24px 12px 24px;
    display: flex;
    justify-content: center;
    align-items: center;
    }
   
    .nav-link{
        font-size: 17.6px;
        font-weight: 500;
        color: #d32f2f;
        padding: 0px 20px 0px 20px !important;
        font-family: 'Inter' sans-serif;
    }
    .ban{
        margin-top: 10px;
    }
    .ban-1{
        background-color: #141414;
        padding: 32px;
        border-radius: 10px;
    }

    .ban-2 img{
        width: 616px;
        height: 211px;
        object-fit: cover;
        border-radius: 10px;
    }
    .ban-1 h6{
        color: #d32f2f;
        font-size: 18px;
        font-weight: 500;
        line-height: 18px;
        font-family: "Bricolage Grotesque", sans-serif;
    }
    .ban-1 h1{
        color: #fafafa;
        font-size: 61px;
        font-weight: 600;
        line-height: 67px;
        font-family: "Bricolage Grotesque", sans-serif;
    }
    .ban-1 p{
        color: #fafafa;
        font-size: 16px;
        font-weight: 400;
        line-height: 22px;
        font-family: "inter", sans-serif;
        margin-bottom: 14.4px;
    }
    .btn-1{
        padding: 16px 32px 16px 32px;
        border-radius: 5px;
        border: 1px solid;
        border-color: #d32f2f;
        background-color: #d32f2f;
        color: #fafafa;
        font-family: "Inter" sans-serif;
        font-size: 17.6px;
        font-weight: 500;
        text-decoration: inherit;
        line-height: 19px;
        margin-right: 10px;
    }
    .btn-2{
        padding: 16px 32px 16px 32px;
        border-radius: 5px;
        border: 1px solid;
        border-color: #fafafa;
        background-color: transparent;
        color: #fafafa;
        font-family: "Inter" sans-serif;
        font-size: 17.6px;
        font-weight: 500;
        text-decoration: inherit;
        line-height: 19px;
        margin-left: 10px;
    }
    .spacer{
        height: 30px;
    }
    
    .ban-1 .btn-1 .btn-2{
        display: flex;
        flex-direction: row;
    }
    .lst-icn{
        display: flex;
        flex-direction: row;
        align-items: center;
    }
    .lst-icn ul li{
       list-style: none;
    }
    .lst-icn p{
        font-size: 18px;
        font-weight: 300;
        line-height: 18px;
        font-family: "Bricolage Grotesque", sans-serif;
    }
    .after-img{
        display: flex;
        margin-top: 108px;
    }
    .listner-sec{
        background-color: #d32f2f;
        border-radius: 10px;
        width: 424.45px;
        padding: 32px;
    }
    .test-img img{
        height: 66px;
        width: 66px !important;
        border: 3px solid;
        border-color: #fafafa;
        border-radius: 50%;
        margin: 0px 2px 0px 2px ;
    }
    .listner-sec h4{
        display: flex;
        justify-content: center;
        font-size: 26px;
        line-height: 26px;
        font-weight: 500;
                font-family: "Bricolage Grotesque", sans-serif;
                color: #fafafa;
    }
    
    .scnd-sec{
        width: 200px;
        display: inline-flex;
        justify-content: center;
        align-items: center;

    }
    .ply-icn{
    font-size: 60px;
    padding: 25px;
    color: #d32f2f;
    border: 1px solid #d32f2f;
    background-color: #141414;
    border-radius: 50%;
    display: inline-flex;
    align-items: center;
    justify-content: center;
    line-height: 45px;
    font-weight: 900;
    }
  </style>
</head>
<body>
    <!-- Header -->
<div class="container main-menu">
    <div class="row pt-3 pb-3 menu-header">
        <div class="col-3 logo p-0">
            <img src="/podverse.png">
        </div>
        <div class="col-6 d-flex justify-content-center">
            <nav class="navbar navbar-expand-lg navbar-dark">
                <div class="container">
                  
                  <button class="navbar-toggler" type="button" data-bs-toggle="collapse"
                    data-bs-target="#navbarNav" aria-controls="navbarNav"
                    aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                  </button>
              
                  <div class="collapse navbar-collapse" id="navbarNav">
                    <ul class="navbar-nav ms-auto">
                      <li class="nav-item">
                        <a class="nav-link active" href="#">Home</a>
                      </li>
                      <li class="nav-item">
                        <a class="nav-link" href="#">About</a>
                      </li>
                      <li class="nav-item">
                        <a class="nav-link" href="#">Pages</a>
                      </li>
                      <li class="nav-item">
                        <a class="nav-link" href="#">Article & News</a>
                      </li>
                      <li class="nav-item">
                        <a class="nav-link" href="#">Contact</a>
                      </li>
                    </ul>
                  </div>
                </div>
              </nav>
                  
        </div>
        <div class="col-2 d-flex justify-content-end align-item-center h-btn">
            <a href="#">Let's Talk</a>
        </div>
        <div class="col-1 d-flex justify-content-end align-item-center h-btn">
            <button></button>
        </div>
    </div>
</div>
<!-- Bananer -->
<div class="container ban">
    <div class="row">
            
        <div class="col-6 ban-1">
                <h6>Turn Up the Volume</h6>
                <h1>Start Listening Your Favorit Podcast
                </h1>
                <p>Dive into our latest episodes and discover captivating stories, insightful interviews, and the best in entertainment. Tune in now and never miss a moment of the action!
                </p>
                <button class="btn-1">Learn More</button>
                <button class="btn-2">See All Episodes</button>
                <div class="spacer"></div>
                <div class="lst-icn">
                <p>Listening On :
                    <ul class="d-flex gap-2">
                        <li><img src="Logo-1.png"></li>
                        <li><img src="Logo-2.png"></li>
                        <li><img src="Logo-3.png"></li>
                        <li><img src="Logo-4.png"></li>
                        <li><img src="Logo-5.png"></li>
                    </ul>
                </p>
            </div>

        </div>

        <div class="col-6 ban-2">
            <img src="/photo-1.jpg">
            <div>
             <div class="after-img">
            <div class="listner-sec">
                <ul class="d-flex list-unstyled test-img justify-content-center">
                    <li><img src="/testimonial-1.png"></li>
                    <li><img src="/testimonial-2.png"></li>
                    <li><img src="/testimonial-3.png"></li>
                </ul>
                <h4>Happy Listener</h4>
            </div>
                    <div class="scnd-sec">
            <i class="fa-solid fa-play ply-icn"></i>
        </div>
        </div>

        </div>
       

    </div>
</div>


</body>
</html>
