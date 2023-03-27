# Home

Welcome to my personal website! Here you will find a collection of information and documents related to my studies and career in physics, starting from my early days as an undergraduate student at. Additionally, you will find links to  interesting websites I recommend and pages of researchers I admire.

<!-- <section>
    <div class="container">
        <div class="carousel">
            <input type="radio" name="slides" checked="checked" id="slide-1">
            <input type="radio" name="slides" id="slide-2">
            <input type="radio" name="slides" id="slide-3">
            <input type="radio" name="slides" id="slide-4">
            <input type="radio" name="slides" id="slide-5">
            <input type="radio" name="slides" id="slide-6">
            <ul class="carousel__slides">
                <li class="carousel__slide">
                    <figure>
                        <div>
                            <img src="https://picsum.photos/id/1041/800/450" alt="">
                        </div>
                        <figcaption>
                            Lorem ipsum dolor sit amet consectetur adipisicing elit.
                            <span class="credit">Photo: Tim Marshall</span>
                        </figcaption>
                    </figure>
                </li>
                <li class="carousel__slide">
                    <figure>
                        <div>
                            <img src="https://picsum.photos/id/1043/800/450" alt="">
                        </div>
                        <figcaption>
                            Lorem ipsum dolor sit amet consectetur adipisicing elit.
                            <span class="credit">Photo: Christian Joudrey</span>
                        </figcaption>
                    </figure>
                </li>
                <li class="carousel__slide">
                    <figure>
                        <div>
                            <img src="https://picsum.photos/id/1044/800/450" alt="">
                        </div>
                        <figcaption>
                            Lorem ipsum dolor sit amet consectetur adipisicing elit.
                            <span class="credit">Photo: Steve Carter</span>
                        </figcaption>
                    </figure>
                </li>
                <li class="carousel__slide">
                    <figure>
                        <div>
                            <img src="https://picsum.photos/id/1045/800/450" alt="">
                        </div>
                        <figcaption>
                            Lorem ipsum dolor sit amet consectetur adipisicing elit.
                            <span class="credit">Photo: Aleksandra Boguslawska</span>
                        </figcaption>
                    </figure>
                </li>
                <li class="carousel__slide">
                    <figure>
                        <div>
                            <img src="https://picsum.photos/id/1049/800/450" alt="">
                        </div>
                        <figcaption>
                            Lorem ipsum dolor sit amet consectetur adipisicing elit.
                            <span class="credit">Photo: Rosan Harmens</span>
                        </figcaption>
                    </figure>
                </li>
                <li class="carousel__slide">
                    <figure>
                        <div>
                            <img src="https://picsum.photos/id/1052/800/450" alt="">
                        </div>
                        <figcaption>
                            Lorem ipsum dolor sit amet consectetur adipisicing elit.
                            <span class="credit">Photo: Annie Spratt</span>
                        </figcaption>
                    </figure>
                </li>
            </ul>
            <ul class="carousel__thumbnails">
                <li>
                    <label for="slide-1"><img src="https://picsum.photos/id/1041/150/150" alt=""></label>
                </li>
                <li>
                    <label for="slide-2"><img src="https://picsum.photos/id/1043/150/150" alt=""></label>
                </li>
                <li>
                    <label for="slide-3"><img src="https://picsum.photos/id/1044/150/150" alt=""></label>
                </li>
                <li>
                    <label for="slide-4"><img src="https://picsum.photos/id/1045/150/150" alt=""></label>
                </li>
                <li>
                    <label for="slide-5"><img src="https://picsum.photos/id/1049/150/150" alt=""></label>
                </li>
                <li>
                    <label for="slide-6"><img src="https://picsum.photos/id/1052/150/150" alt=""></label>
                </li>
            </ul>
        </div>
    </div>
</section>
<style>
      &:before {
        display: block;
        content: "";
        width: 100%;
        padding-top: ($height / $width) * 100%;
      }

      > img {
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            width: 100%;
            height: 100%;
      }
    }

    // Styling

    section {
        background: #F4F4F4;
        padding: 50px 0;
    }

    .container {
        max-width: 1044px;
        margin: 0 auto;
        padding: 0 20px;
    }

    .carousel {
        display: block;
        text-align: left;
        position: relative;
        margin-bottom: 22px;

        > input {
            clip: rect(1px, 1px, 1px, 1px);
            clip-path: inset(50%);
            height: 1px;
            width: 1px;
            margin: -1px;
            overflow: hidden;
            padding: 0;
            position: absolute;

            &:nth-of-type(6):checked ~ .carousel__slides .carousel__slide:first-of-type { margin-left: -500%; }
            &:nth-of-type(5):checked ~ .carousel__slides .carousel__slide:first-of-type { margin-left: -400%; }
            &:nth-of-type(4):checked ~ .carousel__slides .carousel__slide:first-of-type { margin-left: -300%; }
            &:nth-of-type(3):checked ~ .carousel__slides .carousel__slide:first-of-type { margin-left: -200%; }
            &:nth-of-type(2):checked ~ .carousel__slides .carousel__slide:first-of-type { margin-left: -100%; }
            &:nth-of-type(1):checked ~ .carousel__slides .carousel__slide:first-of-type { margin-left: 0%; }

            &:nth-of-type(1):checked ~ .carousel__thumbnails li:nth-of-type(1) { box-shadow: 0px 0px 0px 5px rgba(0,0,255,0.5); }
            &:nth-of-type(2):checked ~ .carousel__thumbnails li:nth-of-type(2) { box-shadow: 0px 0px 0px 5px rgba(0,0,255,0.5); }
            &:nth-of-type(3):checked ~ .carousel__thumbnails li:nth-of-type(3) { box-shadow: 0px 0px 0px 5px rgba(0,0,255,0.5); }
            &:nth-of-type(4):checked ~ .carousel__thumbnails li:nth-of-type(4) { box-shadow: 0px 0px 0px 5px rgba(0,0,255,0.5); }
            &:nth-of-type(5):checked ~ .carousel__thumbnails li:nth-of-type(5) { box-shadow: 0px 0px 0px 5px rgba(0,0,255,0.5); }
            &:nth-of-type(6):checked ~ .carousel__thumbnails li:nth-of-type(6) { box-shadow: 0px 0px 0px 5px rgba(0,0,255,0.5); }
        }
    }

    .carousel__slides {
        position: relative;
        z-index: 1;
        padding: 0;
        margin: 0;
        overflow: hidden;
        white-space: nowrap;
        box-sizing: border-box;
        display: flex;
    }

    .carousel__slide {
        position: relative;
        display: block;
        flex: 1 0 100%;
        width: 100%;
        height: 100%;
        overflow: hidden;
        transition: all 300ms ease-out;
        vertical-align: top;
        box-sizing: border-box;
        white-space: normal;

        figure {
            display: flex;
            margin: 0;
        }

        div {
            @include aspect-ratio(3, 2);
            width: 100%;
        }

        img {
            display: block;
            flex: 1 1 auto;
            object-fit: cover;
        }

        figcaption {
            align-self: flex-end;
            padding: 20px 20px 0 20px;
            flex: 0 0 auto;
            width: 25%;
            min-width: 150px;
        }

        .credit {
            margin-top: 1rem;
            color: rgba(0, 0, 0, 0.5);
            display: block;        
        }

        &.scrollable {
            overflow-y: scroll;
        }
    }

    .carousel__thumbnails {
        list-style: none;
        padding: 0;
        margin: 0;
        display: flex;

        margin: 0 -10px;

        .carousel__slides + & {
            margin-top: 20px;
        }

        li {        
            flex: 1 1 auto;
            max-width: calc((100% / 6) - 20px);  
            margin: 0 10px;
            transition: all 300ms ease-in-out;
        }

        label {
            display: block;
            @include aspect-ratio(1,1);


            &:hover,
            &:focus {
                cursor: pointer;

                img {
                    box-shadow: 0px 0px 0px 1px rgba(0,0,0,0.25);
                    transition: all 300ms ease-in-out;
                }
            }
        }

        img {
            display: block;
            width: 100%;
            height: 100%;
            object-fit: cover;
        }
</style>
 -->
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

<style>
  position: relative;
    
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
