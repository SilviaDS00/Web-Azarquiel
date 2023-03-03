<div
  class="container-fluid contenedor align-content-center justify-content-center"
>
  <div class="container row text-white text-center">
    <div class="col-sm-3 seccion">
      <i class="fa-solid fa-graduation-cap" />
      <h3>Bachillerato</h3>
      <p>
        Centro donde se imparten los Bachilleratos de Ciencias y Humanidades y
        Ciencias Sociales.
      </p>
    </div>
    <div class="col-sm-3 list-group seccion">
      <i class="fa-solid fa-flag" />
      <h3>Programas Lingüísticos</h3>
      <p><a href="/">Centro Bilingüe (Seccion Europea) desde 2006</a></p>
      <p><a href="/">Cambridge English Centre desde 2013</a></p>
    </div>
    <div class="col-sm-3 seccion">
      <i class="fa-solid fa-mobile-screen-button" />
      <h3>Enseñanzas digitales</h3>
      <p>
        Algunos grupos de nuestro centro sustituyen libros y cuadernos por
        materiales y herramientas digitales
      </p>
      <a href="/">Más información</a>
    </div>
    <div class="col-sm-3 list-group seccion">
      <i class="fa-solid fa-computer" />
      <h3>Formación Profesional</h3>
      <p><a href="/">FP - Familias FP</a></p>
      <p><a href="/">2 grupos FP Grado Básico.</a></p>
      <p><a href="/">14 grupos de Grado Medio.</a></p>
      <p><a href="/">24 grupos de Grado Superior.</a></p>
      <p><a href="/">FP Dual, FP Distancia.</a></p>
      <p><a href="/">C. Especialización Videojuegos</a></p>
    </div>
  </div>
</div>

<!-- ------------------------------------------------------------------------------------------ -->

<div class="text-center container-fluid cursos pt-4 pb-2">
  <div style="color: rgb(40, 151, 221); text-decoration:overline">
    <h1 class="h1">Cursos de especialización</h1>
  </div>
</div>

<!-- ------------------------------------------------------------------------------------------ -->

<div class="container justify-content-center align-content-center">
  <div class=" row align-content-center tarjeta mt-4 mb-4">
    <div class="col-lg-6 col-md-6 p-4 text-center">
      <h3 class="card-title display-5 mb-3">
        <i class="fa-solid fa-gamepad" /> Videojuegos
      </h3>
      <p class="card-text lead">
        La competencia general de este curso de especialización consiste en
        diseñar y desarrollar videojuegos para diferentes dispositivos y
        plataformas, garantizando la experiencia del usuario, utilizando
        herramientas de última generación que permitan actuar en todas las fases
        de su desarrollo, así como aplicaciones interactivas de realidad virtual
        y aumentada ...
      </p>
      <a href="/videojuegos" class="btn m-4">Más información</a>
    </div>
    <div class="col-lg-6 col-md-4 p-4 align-content-center">
      <video class="rounded" src="./vid/videojuegos.mp4" autoplay loop muted></video>
    </div>
  </div>
</div>

<!-- ------------------------------------------------------------------------------------------ -->

<div class="container justify-content-center">
  <div class="row align-content-center tarjeta mt-4 mb-4">
    <div class="col-lg-6 col-md-4 p-4">
      <video src="./vid/ciberseguridad2.mp4" autoplay loop muted></video>
      <!-- <img class="rounded" src="./img/ciberseguridad.jpg" alt="" /> -->
    </div>
    <div class="col-lg-6 col-md-6 p-4 text-center">
      <h3 class="card-title display-5 mb-3">
        <i class="fa-solid fa-user-secret " /> Ciberseguridad
      </h3>
      <p class="card-text lead">
        Este curso de especialización consiste en definir e implementar
        estrategias de seguridad en los sistemas de información realizando
        diagnósticos de ciberseguridad, identificando vulnerabilidades e
        implementando las medidas necesarias para mitigarlas aplicando la
        normativa vigente y estándares del sector, siguiendo los protocolos de
        calidad ...
      </p>
      <a href="/ciberseguridad" class="btn m-4">Más información</a>
    </div>
  </div>
</div>

<!-- ------------------------------------------------------------------------------------------ -->

<style>
  i {
    font-size: 2rem;
  }

  img {
    max-width: 100%;
  }
  video{
    max-width: 100%;
  }

  .contenedor {
    min-height: 20rem;
    background-color: rgb(40, 151, 221);
    display: flex;
    align-items: center;
    justify-content: center;
  }
  a {
    color: white;
    text-decoration: none;
  }
  .seccion {
    width: 20rem;
  }
  i {
    font-size: 2rem;
    margin-bottom: 1rem;
  }
  p {
    margin: 0;
  }
  .tarjeta {
    border: 1px solid rgb(40, 151, 221);
    border-radius: 1rem;
    color: rgb(40, 151, 221);
    box-shadow: rgba(0, 0, 0, 0.1) 0px 4px 12px;
    transition: all 0.5s;
  }
  .tarjeta:hover {
    box-shadow: 0 6px 20px 0 rgba(0, 0, 0, 0.25);
    animation: ch-color 300ms;
    animation-fill-mode: forwards;
    border: 1px solid transparent;
    transform: scale(1.02);
  }
  .btn {
    background-color: rgb(40, 151, 221);
    border: 1px solid rgb(255, 255, 255);
    border-radius: 1rem;
    transition: all 0.3s;
  }
  .btn:hover {
    background-color: white;
    color: black;
    transform: scale(1.05);
  }

  @keyframes ch-color {
    0% {
      background-color: rgb(255, 255, 255);
    }

    100% {
      background-color: rgb(40, 151, 221);
      color: white;
    }

  }
</style>
