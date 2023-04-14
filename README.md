# _SMG TRADE_
## HTML5 bootstrap kullanılarak SMG TRADE (E-ticaret) sitesinin Navbar'ı üzerinde çalışma yapıldı. 
### Alt tarafta sırası ile kaynak `kod`'ları ve navbar ekran görüntüsü  bulunmakta.
---
>__KAYNAK`KOD`:__

```html5
 <nav class="navbar navbar-expand-sm navbar-dark bg-success sticky-top fw-bolder mb-4">
      <div class="container-fluid">
        <a class="navbar-brand" href="javascript:void(0)">SMG TRADE</a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#mynavbar">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="mynavbar">
          <ul class="navbar-nav me-auto">
            <li class="nav-item">
              <a class="nav-link" href="javascript:void(0)">Anasayfa</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="javascript:void(0)">Ürünler</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="javascript:void(0)">Hakımızda</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="javascript:void(0)">Misyonumuz</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="javascript:void(0)">Vizyonumuz</a>
            </li>
          </ul>
          <form class="d-flex">
              <button type="button" class="btn btn-lg btn-sm text-light fw-bolder">
                  <i class="material-icons" style="font-size:15px; color:rgb(255, 251, 251); ">shopping_cart</i> Sepetim
               
            <button type="button" class="btn btn-lg btn-sm text-light fw-bolder">
             
               <i class="material-icons"style="font-size:15px; color: rgb(255, 251, 251); ">https</i> Admin
         </form>
            
        </div>
      </div>
    </nav>

```
---
>__Ekran görüntüsü:__

![Ekran görüntüsü_20230130_184934](https://user-images.githubusercontent.com/97148793/215525661-72a091cf-ea19-4f8e-8204-d1c1b71443bb.png)
---
---
## HTML5 bootstrap kullanılarak SMG TRADE (E-ticaret) sitesinin Carousel'ı üzerinde çalışma yapıldı. 
### Alt tarafta sırası ile kaynak `kod`'ları ve carousel ekran görüntüsü  bulunmakta.
---
>__KAYNAK`KOD`:__

```html5
   <div id="demo" class="carousel slide m-auto mb-4" data-bs-ride="carousel"style="width:80%">

      <!-- Indicators/dots -->
      <div class="carousel-indicators">
        <button type="button" data-bs-target="#demo" data-bs-slide-to="0" class="active"></button>
        <button type="button" data-bs-target="#demo" data-bs-slide-to="1"></button>
        <button type="button" data-bs-target="#demo" data-bs-slide-to="2"></button>
      </div>
      
      <!-- The slideshow/carousel -->
      <div class="carousel-inner">
        <div class="carousel-item active">
          <img src="Asets/images/Gardening-tools-Must-have-tools-for-growing-a-home-garden.jpg" alt="Los Angeles" class="d-block" style="width:100%">
          <div class="carousel-caption">
            <h3>Los Angeles</h3>
            <p>We had such a great time in LA!</p>
          </div>
        </div>
        <div class="carousel-item">
          <img src="Asets/images/garden-time-UST.jpg" alt="Chicago" class="d-block" style="width:100%">
          <div class="carousel-caption">
            <h3>Chicago</h3>
            <p>Thank you, Chicago!</p>
          </div> 
        </div>
        <div class="carousel-item">
          <img src="Asets/images/hero-bahce.jpg" alt="New York" class="d-block" style="width:100%">
          <div class="carousel-caption">
            <h3>New York</h3>
            <p>We love the Big Apple!</p>
          </div>  
        </div>
      </div>
      
      <!-- Left and right controls/icons -->
      <button class="carousel-control-prev" type="button" data-bs-target="#demo" data-bs-slide="prev">
        <span class="carousel-control-prev-icon"></span>
      </button>
      <button class="carousel-control-next" type="button" data-bs-target="#demo" data-bs-slide="next">
        <span class="carousel-control-next-icon"></span>
      </button>
  </div>
```
---
>__Ekran görüntüsü:__

![1](https://user-images.githubusercontent.com/97148793/219608981-c44c944d-7bce-4963-a454-5f94e78ef3e1.png)


---
---
## HTML5 bootstrap kullanılarak SMG TRADE (E-ticaret) sitesinin footer'ı üzerinde çalışma yapıldı. 
### Alt tarafta sırası ile kaynak `kod`'ları ve  footer ekran görüntüsü  bulunmakta.
---
>__KAYNAK`KOD`:__

```html5
     <footer class="text-center text-lg-start bg-success text-light fw-bolder ">
            <!-- Section: Social media -->
            <section class="d-flex justify-content-center justify-content-lg-between p-4 border-bottom">
                <!-- Left -->
                <div class="me-5 d-none d-lg-block">
                    <span>Get connected with us on social networks:</span>
                </div>
                <!-- Left -->
                <!-- Right -->
                <div>
                    <a href="" class="me-4 text-reset">
                        <i class="fa fa-facebook-f"></i>
                    </a>
                    <a href="" class="me-4 text-reset">
                        <i class="fa fa-twitter"></i>
                    </a>
                    <a href="" class="me-4 text-reset">
                        <i class="fa fa-google"></i>
                    </a>
                    <a href="" class="me-4 text-reset">
                        <i class="fa fa-instagram"></i>
                    </a>
                    <a href="" class="me-4 text-reset">
                        <i class="fa fa-linkedin"></i>
                    </a>
                    <a href="" class="me-4 text-reset">
                        <i class="fa fa-github"></i>
                    </a>
                </div>
                <!-- Right -->
            </section>
            <!-- Section: Social media -->
            <!-- Section: Links  -->
            <section class="container-fluid">
                <div class="container-fluid text-center text-md-start mt-5">
                    <!-- Grid row -->
                    <div class="row mt-3">
                        <!-- Grid column -->
                        <div class="col-md-3 col-lg-4 col-xl-3 mx-auto mb-4">
                            <!-- Content -->
                            <h6 class="text-uppercase fw-bold mb-4">
                                <i class="fa fa-gem me-3"></i>Company name
                            </h6>
                            <p>
                                Here you can use rows and columns to organize your footer content. Lorem ipsum
                                dolor sit amet, consectetur adipisicing elit.
                            </p>
                        </div>
                        <!-- Grid column -->
                        <!-- Grid column -->
                        <div class="col-md-2 col-lg-2 col-xl-2 mx-auto mb-4">
                            <!-- Links -->
                            <h6 class="text-uppercase fw-bold mb-4">
                                Products
                            </h6>
                            <p>
                                <a href="#!" class="text-reset">Angular</a>
                            </p>
                            <p>
                                <a href="#!" class="text-reset">React</a>
                            </p>
                            <p>
                                <a href="#!" class="text-reset">Vue</a>
                            </p>
                            <p>
                                <a href="#!" class="text-reset">Laravel</a>
                            </p>
                        </div>
                        <!-- Grid column -->
                        <!-- Grid column -->
                        <div class="col-md-3 col-lg-2 col-xl-2 mx-auto mb-4">
                            <!-- Links -->
                            <h6 class="text-uppercase fw-bold mb-4">
                                Useful links
                            </h6>
                            <p>
                                <a href="#!" class="text-reset">Pricing</a>
                            </p>
                            <p>
                                <a href="#!" class="text-reset">Settings</a>
                            </p>
                            <p>
                                <a href="#!" class="text-reset">Orders</a>
                            </p>
                            <p>
                                <a href="#!" class="text-reset">Help</a>
                            </p>
                        </div>
                        <!-- Grid column -->
                        <!-- Grid column -->
                        <div class="col-md-4 col-lg-3 col-xl-3 mx-auto mb-md-0 mb-4">
                            <!-- Links -->
                            <h6 class="text-uppercase fw-bold mb-4">Contact</h6>
                            <p><i class="fa fa-home me-3"></i> New York, NY 10012, US</p>
                            <p>
                                <i class="fa fa-envelope me-3"></i>
                                info@example.com
                            </p>
                            <p><i class="fa fa-phone me-3"></i> + 01 234 567 88</p>
                            <p><i class="fa fa-print me-3"></i> + 01 234 567 89</p>
                        </div>
                        <!-- Grid column -->
                    </div>
                    <!-- Grid row -->
                </div>
            </section>
            <!-- Section: Links  -->
            <!-- Copyright -->
            <div class="text-center p-4" style="background-color: rgba(0, 0, 0, 0.05);">
                © 2021 Copyright:
                <a class="text-reset fw-bold" href="https://mdbootstrap.com/">MDBootstrap.com</a>
            </div>
            <!-- Copyright -->
        </footer>
```
---
>__Ekran görüntüsü:__


![footer-using-bootstrap-4](https://user-images.githubusercontent.com/97148793/224566706-e8274abc-5b7e-4c96-bc04-83f681ea0d50.png)


---
---
## HTML5 bootstrap kullanılarak SMG TRADE (E-ticaret) sitesinin cart'ın üzerinde çalışma yapıldı. 
### Alt tarafta sırası ile kaynak `kod`'ları ve  cart'ın ekran görüntüsü  bulunmakta.
---
>__KAYNAK`KOD`:__

```html5
     
        <div class="col-sm-4 mb-5 mt-3">
  <div class="container-fluid" >      
            <div class="card-sl">
                <div class="card-image">
                    <img
                        src="https://images.pexels.com/photos/1149831/pexels-photo-1149831.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940" />
                </div>
                <div class="card-heading">
                    Audi Q8
                </div>
                <div class="card-text">
                    Audi Q8 is a full-size luxury crossover SUV coupé made by Audi that was launched in 2018.
                </div>
                <div class="card-text">
                    $67,400
                </div>
                <a href="#" class="card-button"> Purchase</a>
            </div>
        </div> 
</div>

```
---
>__Ekran görüntüsü:__


![resim](https://user-images.githubusercontent.com/97148793/229086815-32cd8878-7967-47e8-be40-f5decce2ae8b.png)



---
---
## HTML5 bootstrap kullanılarak SMG TRADE (E-ticaret) sitesinin kategori menüsü  üzerinde çalışma yapıldı. 
### Alt tarafta sırası ile kaynak `kod`'ları ve  kategori menüsü ekran görüntüsü  bulunmakta.
---
>__KAYNAK`KOD`:__

```html5
     
       <div class="list-group">
            <a href="#" class="list-group-item bg-success list-group-item-action active">
              kategori
            </a>
            <a href="#" class="list-group-item list-group-item-action">Dapibus ac facilisis in</a>
            <a href="#" class="list-group-item list-group-item-action">Morbi leo risus</a>
            <a href="#" class="list-group-item list-group-item-action">Porta ac consectetur ac</a>
            <a href="#" class="list-group-item list-group-item-action ">Vestibulum at eros</a>
            <a href="#" class="list-group-item list-group-item-action ">Vestibulum at eros</a>
            <a href="#" class="list-group-item list-group-item-action ">Vestibulum at eros</a>
            <a href="#" class="list-group-item list-group-item-action ">Vestibulum at eros</a>
            <a href="#" class="list-group-item list-group-item-action ">Vestibulum at eros</a>
          </div>
```
---
>__Ekran görüntüsü:__

![1111111](https://user-images.githubusercontent.com/97148793/230497567-5af23113-b36a-49e9-bc36-b64fff0c975f.png)



---
---
## HTML5 bootstrap kullanılarak SMG TRADE (E-ticaret) sitesinin misyonumuz sayfası  üzerinde çalışma yapıldı. Üst menü ve footer aynı olup boody'ye yazı metini gurubu eklendi.
### Alt tarafta sırası ile kaynak `kod`'ları ve yazı metini gurubu  ekran görüntüsü  bulunmakta.
---
>__KAYNAK`KOD`:__

```html5
     
      <div class="mt-4 p-5 bg-success bg-opacity-50 text-dark rounded mb-5 mt-5">
        <h1>SMG TRADE</h1>
        <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Iste inventore atque ipsa nam dolorum tempore cum? Vitae aut id asperiores fuga quibusdam, porro veritatis ipsum culpa, aliquid impedit corrupti dolorem.</p>
      </div> 
```
---
>__Ekran görüntüsü:__




![12222](https://user-images.githubusercontent.com/97148793/230498913-54c5ad18-971a-463a-9d5b-14ac1e53f536.png)

---
---


