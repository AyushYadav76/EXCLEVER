# EXCLEVER
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Homepage</title>
    <link rel="stylesheet" href="https://unpkg.com/aos@next/dist/aos.css" />
    <link rel="stylesheet" href="disadter_managment1.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Anek+Devanagari&display=swap" rel="stylesheet">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha2/dist/css/bootstrap.min.css" rel="stylesheet"integrity="sha384-aFq/bzH65dt+w6FI2ooMVUpc+21e0SRygnTpmBvdBgSdnuTN7QbdgL+OapgHtvPp" crossorigin="anonymous">
</head>
<body>
    <div id="eng">
      <div class="top">
          <div class="gradient-background" style="height: 500px;">
              <header class="p-3 " id="home">
                  <div class="container1">
                    <div class="d-flex flex-wrap align-items-center justify-content-center justify-content-lg-start">
                      <!-- <a href="/" class="d-flex align-items-center mb-2 mb-lg-0 text-white text-decoration-none">
                        <svg class="bi me-2" width="40" height="32" role="img" aria-label="Bootstrap"><use xlink:href="#bootstrap"/></svg>
                        <svg class="bi me-2" width="40" height="32" role="img" aria-label="Bootstrap"><use xlink:href="#bootstrap"/></svg>
                      </a> -->
              
                      <ul class="nav col-12 col-lg-auto me-lg-auto mb-2 justify-content-center mb-md-0">
                        <li><a href="#home" class="nav-link px-2 text-white">Home</a></li>
                        <li class="nav-item dropdown"><a href="#disaster" class="nav-link px-2 text-white dropdown-toggle" role="button" data-bs-toggle="dropdown" aria-expanded="false">Disasters</a>
                          <ul class="dropdown-menu">
                            <li><a class="dropdown-item" href="flood.html">Floods</a></li>
                            <li><a class="dropdown-item" href="earthquake.html">Earthquakes</a></li>
                            <li><a class="dropdown-item" href="cyclone.html">Cyclones</a></li>
                            <li><a class="dropdown-item" href="landslides.html">Landslides</a></li>
                            <!-- <li><hr class="dropdown-divider"></li>
                            <li><a class="dropdown-item" href="#">Something else here</a></li> -->
                          </ul>
                        </li>
                        <li><a href="#donate" class="nav-link px-2 text-white">Donate</a></li>
                        <!-- <li><a href="#" class="nav-link px-2 text-white"></a></li> -->
                        <li><a href="#about" class="nav-link px-2 text-white">About</a></li>
                        <li class="nav-link px-2 text-white">Helpline Number
                            
                            
                        </li>    
                      </ul>
              
                      <form class="col-6 col-lg-auto mb-3 mb-lg-0 me-lg-3" role="search">
                        <input type="search" id="search" list="input" class="form-control form-control-dark text-bg-light" placeholder="Search here" aria-label="Search" color="white" autocomplete="off">
                        <datalist id="input">
                          <option value="Floods" onclick="submit()">Floods</option>
                          <option value="Earthquakes">Earthquakes</option>
                          <option value="Cyclones">Cyclones</option>
                          <option value="Landslides">Landslides</option>
                          <option value="Disasters" onclick="submit()"><a href="#disaster">Disasters</a></option>
                          <option value="Donate"><a href="#donate">Donate</a></option>
                          <option value="About"><a href="#about">About</a></option>
                        </datalist>
                      </form>
                    </div>      
                  </div>
              </header>

              <div class="container">
                <div>
                  <h5 style="margin-bottom: 5rem;"></h5>
                  <h3 style="margin-left: 0;"><span style="margin-left: 0; font-size: 12rem; margin: 1rem 0 0.5rem 5rem;">d-Managment</span></h3> 
                          <!-- <h6>Use D-App To Prepare For The D-Day</h6> -->
                </div>
                <!-- <img src="screen.jpg" alt="" loading="lazy" style="height: 350px; width: 200px; margin: 0rem 0.5rem 0rem 46rem; position: absolute; top: 10rem;"> -->
              </div>
          </div>
      </div>
      <a href="https://t.me/DAAP31_BOT" class="bot" style="display: flex; flex-direction: column; align-items: end; justify-content: right; margin: 0.4rem 1rem 0 0; position: sticky; top: 0; bottom: -1px; ">
        <img src="https://github.com/InfiniteVoid07/SIH-DisasterManagement/blob/main/bot.png?raw=true" role="button" style="height: 100px; width: 100px; margin-bottom: 0; border-radius: 1rem; border: none;">
      </a>  
      <div class="mid ">
        <div class="container2">
          <section id="disaster">
            <div>
              <h2 style="color: rgb(41, 70, 143);">Disasters</h2>
              <div class="box gradient-background container"></div>
                <div class="cards">
                  <div class="card">
                    <div class="card1">
                      <span><img src="https://c1.wallpaperflare.com/preview/45/41/234/earthquake-rubble-l-aquila-collapse.jpg" alt="Earthquakes" class="card-img dis"></span>
                      <div class="card-body">
                        <h2 class="card-title">Earthquakes</h2><br>
                        <p class="info">Any sudden shaking of the ground caused by the passage of seismic waves through Earth's rocks. Seismic waves are produced when some form of energy stored in Earth's crust is suddenly released</p>
                        <button class="card-btn" onclick="window.location.assign('earthquake.html')">More info</button>
                      </div>
                    </div>
                  </div>

                  <div class="card">
                    <div class="card1">
                      <span><img src="https://cdn.downtoearth.org.in/library/large/2020-07-18/0.43229900_1595054679_assam-floods.jpg" alt="Floods" class="card-img dis"></span>
                      <div class="card-body">
                        <h2 class="card-title">Floods</h2>
                        <p class="info">Floods are the most frequent type of natural disaster and occur when an overflow of water submerges land that is usually dry. Floods are often caused by heavy rainfall, rapid snowmelt or a storm surge from a tropical cyclone or tsunami in coastal areas.</p>
                        <button class="card-btn" onclick="window.location.assign('flood.html')">More info</button>
                      </div>
                    </div>
                  </div>
                </div>
                <div class="cards">
                  <div class="card">
                    <div class="card1">
                      <span><img src="https://eoimages.gsfc.nasa.gov/images/imagerecords/148000/148325/indiacyclone_vir_2021137_th.jpg" alt="Cyclones" class="card-img dis"></span>
                      <div class="card-body">
                        <h2 class="card-title">Cyclones</h2>
                        <p class="info"> Any large system of winds that circulates about a centre of low atmospheric pressure in a counterclockwise direction north of the Equator and in a clockwise direction to the south.</p>
                        <button class="card-btn" onclick="window.location.assign('cyclone.html')">More info</button>
                      </div>
                    </div>
                  </div>

                  <div class="card">
                    <div class="card1">
                      <span><img src="https://media.istockphoto.com/id/469239302/photo/landslide-in-the-roadway-in-el-salvador.jpg?s=612x612&w=0&k=20&c=wveT9bmJk6r6OPP4muFrAOmidmNBgDu5DRlVCtBWodk=" alt="Landslides" class="card-img dis"></span>
                      <div class="card-body">
                        <h2 class="card-title">Landslides</h2>
                        <p class="info"> A mass movement of material, such as rock, earth or debris, down a slope. They can happen suddenly or more slowly over long periods of time. When the force of gravity acting on a slope exceeds the resisting forces of a slope, the slope will fail and a landslide occurs.</p>
                        <button class="card-btn" onclick="window.location.assign('landslides.html')">More info</button>
                      </div>
                    </div>
                  </div>
                </div>
            </div>
          </section>

          <!-- <section id="donate">
            <h2 style="color: rgb(41, 70, 143);">Donate</h2>
            <div class="box gradient-background container"></div>
          </section> -->
          
        </div>
      </div>
      
      <div class="last gradient-background">
        <div class="bottom" style="margin: 0; padding: 0;">
          <div class="container1">
            <form class="form2" action="https://formspree.io/f/myyqdqba" method="POST" data-aos="zoom-in">
              <h2>Contact Us</h2>
              <input type="text" id="name" name="name" placeholder="Full Name" required autocomplete="off">
              <input type="email" id="email" name="email" placeholder="demo@gmail.com" required autocomplete="off">
              <textarea id="message" rows="5" name="message" placeholder="How can we help you?" required autocomplete="off"></textarea>
              <button type="submit">Submit</button>
            </form>
            <footer><h6 style="margin-bottom: 0px;">© d-ऐPP 2023</h6></footer>
          </div>
        </div>
        <div class="vl"></div>
        <div style="display: flex; flex-direction: column;">
          <section id="about" >
            <h2 style="color: rgb(41, 70, 143);">About Us</h2>
            <div class="box gradient-background container"></div>
            <p data-aos="fade-right">Our team aims to provide the users with information related to various natural disasters including their causes, prevention techniques and warning systems to have everything prepared in advance for the D-DAY. 
              Through our application we also provide users with the safety measures that must be taken during the time of disaster. We have also elaborated on what has to be done before and after a disaster. It also provides the mapping of the nearest rescue centers. To avoid panic due to low internet connectivity that a person might face during a disaster we have provided the offline map system. 
              We are a team of 4 and this is a demo website developed for the CODE OFF DUTY hackathon.</p>
          </section>
        </div>
      </div>
    </div>

   

          <!-- <section id="donate">
            <h2 style="color: rgb(41, 70, 143);">Donate</h2>
            <div class="box gradient-background container"></div>
          </section> -->
          
        </div>
      </div>
      
    <script src="https://unpkg.com/aos@next/dist/aos.js"></script>
    <script>
      AOS.init({
        offset: 120,
        duration: 1000,
      });
    </script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha3/dist/js/bootstrap.bundle.min.js"
    integrity="sha384-ENjdO4Dr2bkBIFxQpeoTz1HIcje39Wm4jDKdf19U8gI4ddQ3GYNS7NTKfAdVQSZe"
    crossorigin="anonymous"></script>
</body>
</html>
