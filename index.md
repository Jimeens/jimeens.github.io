# Home

Welcome to my personal website! Here you will find a collection of information and documents related to my studies and career in physics, starting from my early days as an undergraduate student at. Additionally, you will find links to  interesting websites I recommend and pages of researchers I admire.

```html
<section>
    <div class="carousel">
      <div class="carousel-inner">
        <!-- Bloco da imagem 1 -->
        <input
          class="carousel-open"
          type="radio"
          id="carousel-1"
          name="carousel"
          aria-hidden="true"
          hidden=""
          checked="checked"
        />
        <div class="carousel-item">
          <img
            src="http://fakeimg.pl/2000x800/0079D8/fff/?text=Img1"
          />
        </div>
        <!-- Bloco da imagem 2 -->
        <input
          class="carousel-open"
          type="radio"
          id="carousel-2"
          name="carousel"
          aria-hidden="true"
          hidden=""
        />
        <div class="carousel-item">
          <img
            src="http://fakeimg.pl/2000x800/0079D8/fff/?text=Img2"
          />
        </div>
        <!-- Bloco da imagem 3 -->
        <input
          class="carousel-open"
          type="radio"
          id="carousel-3"
          name="carousel"
          aria-hidden="true"
          hidden=""
        />
        <div class="carousel-item">
          <img
            src="http://fakeimg.pl/2000x800/0079D8/fff/?text=Img3"
          />
        </div>

        <!-- Pode adicionar mais blocos de imagens aqui -->

        <!-- Adicionar o prev de acordo com a quantidade de páginas que adicionar -->
        <label for="carousel-1" class="carousel-control prev control-2">‹</label>
        <label for="carousel-2" class="carousel-control prev control-3">‹</label>
        <label for="carousel-3" class="carousel-control prev control-1">‹</label>
        <!-- Adicionar o next de acordo com a quantidade de páginas que adicionar -->
        <label for="carousel-1" class="carousel-control next control-3">›</label>
        <label for="carousel-2" class="carousel-control next control-1">›</label>
        <label for="carousel-3" class="carousel-control next control-2">›</label>
        <!-- 
            Abaixo são os indicadores da página ativa. Se não quiser basta remover. 
            E caso adicione mais páginas, é preciso adicionar mais itens e alterar 
            a numeração 
        -->
        <ol class="carousel-indicators">
          <li>
            <label for="carousel-1" class="carousel-bullet">•</label>
          </li>
          <li>
            <label for="carousel-2" class="carousel-bullet">•</label>
          </li>
          <li>
            <label for="carousel-3" class="carousel-bullet">•</label>
          </li>
        </ol>
      </div>
    </div>
</section>

```

<style>
    
  .carousel {
    position: relative;
    box-shadow: 0px 1px 6px rgba(0, 0, 0, 0.64);
    margin-top: 26px;
  }

  .carousel-inner {
    position: relative;
    overflow: hidden;
    width: 100%;
  }

  .carousel-open:checked + .carousel-item {
    position: static;
    opacity: 100;
  }

  .carousel-item {
    position: absolute;
    opacity: 0;
    -webkit-transition: opacity 0.6s ease-out;
    transition: opacity 0.6s ease-out;
  }

  .carousel-item img {
    display: block;
    height: auto;
    max-height: 550px;
    width: 100%;
  }

  .carousel-control {
    border-radius: 50%;
    color: #fff;
    cursor: pointer;
    display: none;
    font-size: 85px;
    height: 40px;
    line-height: 35px;
    position: absolute;
    top: 50%;
    -webkit-transform: translate(0, -50%);
    cursor: pointer;
    -ms-transform: translate(0, -50%);
    transform: translate(0, -50%);
    text-align: center;
    width: 40px;
    z-index: 10;
  }

  .carousel-control.prev {
    left: 2%;
  }

  .carousel-control.next {
    right: 2%;
  }

  .carousel-control:hover {
    color: #aaaaaa;
  }

  #carousel-1:checked ~ .control-1,
  #carousel-2:checked ~ .control-2,
  #carousel-3:checked ~ .control-3,
  #carousel-4:checked ~ .control-4,
  #carousel-5:checked ~ .control-5,
  #carousel-6:checked ~ .control-6,
  #carousel-7:checked ~ .control-7,
  #carousel-8:checked ~ .control-8,
  #carousel-9:checked ~ .control-9 {
    display: block;
  }

  .carousel-indicators {
    list-style: none;
    margin: 0;
    padding: 0;
    position: absolute;
    bottom: 2%;
    left: 0;
    right: 0;
    text-align: center;
    z-index: 10;
  }

  .carousel-indicators li {
    display: inline-block;
    margin: 0 5px;
  }

  .carousel-bullet {
    color: #fff;
    cursor: pointer;
    display: block;
    font-size: 35px;
  }

  .carousel-bullet:hover {
    color: #aaaaaa;
  }

  #carousel-1:checked
    ~ .control-1
    ~ .carousel-indicators
    li:nth-child(1)
    .carousel-bullet,
  #carousel-2:checked
    ~ .control-2
    ~ .carousel-indicators
    li:nth-child(2)
    .carousel-bullet,
  #carousel-3:checked
    ~ .control-3
    ~ .carousel-indicators
    li:nth-child(3)
    .carousel-bullet,
  #carousel-4:checked
    ~ .control-4
    ~ .carousel-indicators
    li:nth-child(4)
    .carousel-bullet,
  #carousel-5:checked
    ~ .control-5
    ~ .carousel-indicators
    li:nth-child(5)
    .carousel-bullet,
  #carousel-6:checked
    ~ .control-6
    ~ .carousel-indicators
    li:nth-child(6)
    .carousel-bullet,
  #carousel-7:checked
    ~ .control-7
    ~ .carousel-indicators
    li:nth-child(7)
    .carousel-bullet,
  #carousel-8:checked
    ~ .control-8
    ~ .carousel-indicators
    li:nth-child(8)
    .carousel-bullet,
  #carousel-9:checked
    ~ .control-9
    ~ .carousel-indicators
    li:nth-child(9)
    .carousel-bullet {
    color: #428bca;
  }

  #title {
    width: 100%;
    position: absolute;
    padding: 0px;
    margin: 0px auto;
    text-align: center;
    font-size: 27px;
    color: rgba(255, 255, 255, 1);
    font-family: "Open Sans", sans-serif;
    z-index: 9999;
    text-shadow: 0px 1px 2px rgba(0, 0, 0, 0.33),
      -1px 0px 2px rgba(255, 255, 255, 0);
  }
</style>
