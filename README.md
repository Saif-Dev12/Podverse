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
        margin-top: 118px;
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
    .story h5{
        color: #d32f2f;
        font-size: 18px;
        font-weight: 500;
        line-height: 18px;
        font-family: "Bricolage Grotesque", sans-serif;
    }
    .story h1{
        color: #fafafa;
        font-size: 51px;
        font-weight: 500;
        line-height: 51px;
        font-family: "Bricolage Grotesque", sans-serif;
    
    }
    .g-pic img{
        width: 404px;
        height: 370px;
        object-fit: cover;
        border-radius: 20px;
        margin-right: 20px;
    }
    .cntnt p{
        font-size: 16px;
        font-weight: 400;
        line-height: 22px;
        font-family: 'inter', sans-serif;
        margin-bottom: 14.4px;
        padding-right: 10px;
    }
    .cntnt button{
        margin-top: 20px;
    }
        .scnd-img img{
        width: 414px;
        height: 507px;
        object-fit: cover;
        border-radius: 20px;
        margin-right: 20px;
    }
 .counter {
    font-size: 61px;
    font-weight: 600;
    line-height: 67px;
    color: #d32f2f;
    font-family: "Bricolage Grotesque", sans-serif;
  }
  .count-text{
    margin-top: 0.5rem;
    font-size: 19px;
    color:#e9e9e9 !important;
    font-family: "Bricolage Grotesque", sans-serif;
    text-align: justify;
  }
  .img-flw{
    overflow: hidden;
    padding-bottom: 112px;
  }
  .tune {
  position: relative;
  background-image: url(/photo-4.jpg);
  background-size: cover;
  background-position: center;
  padding-top: 100px;
  padding-bottom: 100px;
}

.tune::before {
  content: "";
  position: absolute;
  top: 0; 
  left: 0;
  width: 100%;
  height: 100%;
  background: rgba(0, 0, 0, 0.5); /* black overlay at 50% opacity */
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
<div class="container ban py-5">
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
</div>
<!-- Our Story -->
 <div class="container mt-3 mb-3">
    <div class="row">
        <div class="col-md-12 text-center story d-flex justify-content-center pt-3 flex-column">   
            <h5>Our Story</h5>
            <h1 class="w-75 mx-auto">Crafting Unique Soundscapes for Every Listener</h1>
        </div>
    </div>
<!-- Our Story-2 -->
 <div class="container img-flw">
    <div class="row">
        <div class="col-8 p-0">
            <div class="d-flex">
                <div class="g-pic">
                    <img src="photo-2-1.jpg">
                </div>
                <div class="cntnt text-white">
                    <p>We are passionate about the transformative power of conversation. Our mission is to bring you daily episodes that dive deep into the stories, ideas, and experiences of remarkable individuals from all walks of life. From entrepreneurs and thought leaders to everyday heroes.</p>
                    <p>We explore the journeys that shape their lives and the lessons they’ve learned along the way. Each episode is designed to spark inspiration, provoke thought, and offer fresh perspectives that encourage personal growth and positive change. Whether it’s overcoming obstacles, chasing dreams.</p>
                    <button class="btn-1">Read More</button>
                </div>
            </div>
            <div class="count-sec d-flex text-center my-5">
    <div class="col-md-4 d-flex justify-content-center align-items-center">
      <h3 class="counter" data-target="20">0</h3>
      <p class="count-text">Expert Host</p>
    </div>
    <div class="col-md-4 d-flex justify-content-center align-items-center">
      <h3 class="counter" data-target="15">0</h3>
      <p class="count-text">Episode Downloads</p>
    </div>
    <div class="col-md-4 d-flex justify-content-center align-items-center">
      <h3 class="counter" data-target="10">0</h3>
      <p class="count-text">Years Experience</p>
    </div>
            </div>
        </div>
        <div class="col-4 scnd-img">
            <img src="photo-3.jpg">
        </div>
    </div>
 </div>
<!-- Tune-In Section -->
 <div class="container-fluid tune">
    <div class="row">
        <div class="col-md-12">
            <div class="col-md-12 text-center story d-flex justify-content-center pt-3 flex-column">   
            <h5>Tune In</h5>
            <h1 class="w-75 mx-auto">Catch Up on What You’ve Missed</h1>
            <p class="w75">Dive into our full episode library and catch up on all the exciting conversations, inspiring stories, and trending topics you’ve missed.</p>
        </div>
        </div>
    </div>
 </div>
</body>
<script>
  const counters = document.querySelectorAll('.counter');

  counters.forEach(counter => {
    counter.innerText = '0';

    const updateCounter = () => {
      const target = +counter.getAttribute('data-target');
      const count = +counter.innerText;

      // Adjust speed
      const increment = target / 400;

      if (count < target) {
        counter.innerText = `${Math.ceil(count + increment)}`;
        setTimeout(updateCounter, 60);
      } else {
        // For 1.5K and 20+
        if (target >= 1000) {
          counter.innerText = `${(target / 1000).toFixed(1)}K`;
        } else {
          counter.innerText = `${target}+`;
        }
      }
    };

    updateCounter();
  });
</script>

</html>
