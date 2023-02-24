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

