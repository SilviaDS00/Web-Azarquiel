<div class="container-fluid menu-nav">
  <div class="container-md navbar">
    <div class="col-md-2 p-3">
      <a class="navbar-brand" href="/">
        <img src="./img/logo.png" alt="Logo Azarquiel" style="width:200px;" />
      </a>
    </div>
    <div class="secciones col-md-9 ">
      <ul class="nav justify-content-end">
        <li class="nav-item active">
          <a class="nav-link active" href="/">Inicio</a>
        </li>
        <li class="nav-item dropdown">
          <a
            class="nav-link dropdown-toggle"
            href="/"
            role="button"
            data-bs-toggle="dropdown">Al día</a
          >
          <ul class="dropdown-menu">
            <li><a class="dropdown-item" href="/">Al día</a></li>
            <li><a class="dropdown-item" href="/">Blog del centro</a></li>
            <li>
              <a class="dropdown-item" href="/">Avisos y convocatorias</a>
            </li>
          </ul>
        </li>
        <li class="nav-item dropdown">
          <a
            class="nav-link dropdown-toggle"
            href="/"
            role="button"
            data-bs-toggle="dropdown">El centro</a
          >
          <ul class="dropdown-menu">
            <li><a class="dropdown-item" href="/">General</a></li>
            <li><a class="dropdown-item" href="/">Proyectos</a></li>
            <li><a class="dropdown-item" href="/">Oferta Educativa</a></li>
          </ul>
        </li>
        <li class="nav-item">
          <a class="nav-link dropdown-toggle" href="/">Secretaría</a>
        </li>
        <li class="nav-item">
          <a class="nav-link dropdown-toggle" href="/">Familias</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="/">Bolsa</a>
        </li>
      </ul>
    </div>

    <div class="col-md-1 btn-menu nav justify-content-end">
      <a
        href="/"
        class="btn"
        type="button"
        data-bs-toggle="offcanvas"
        data-bs-target="#demo"
      >
        <i class="fa fa-bars" aria-hidden="true" title="Abrir Menú" />
      </a>
      <!-- <button class="btn btn-primary" type="button" data-bs-toggle="offcanvas" data-bs-target="#demo">
      Toggle Right Offcanvas
    </button> -->
    </div>
    <div class="offcanvas offcanvas-end menu" id="demo">
      <div class="offcanvas-header justify-content-end">
        <button type="button" class="btn-close" data-bs-dismiss="offcanvas" />
      </div>
      <div class="offcanvas-header">
        <h3 class="h2 text-white">Menu</h3>
      </div>
      <div class="offcanvas-header">
        <input
          type="search"
          class="search-field form-control"
          placeholder="Buscar..."
          value=""
          name="s"
        />
      </div>
      <div class="offcanvas-body justify-content-center">
        <ul class="list-group text-center">
          <li class="list-group-item list-group-item-action">
            <a class="nav-link" href="/">Inicio</a>
          </li>
          <li class="list-group-item list-group-item-action">
            <a class="nav-link" href="/">Al día</a>
          </li>
          <li class="list-group-item list-group-item-action">
            <a class="nav-link" href="/">Al loro</a>
          </li>
          <li class="list-group-item list-group-item-action">
            <a class="nav-link" href="/">El centro</a>
          </li>
          <li class="list-group-item list-group-item-action">
            <a class="nav-link" href="/">Secretaría</a>
          </li>
          <li class="list-group-item list-group-item-action">
            <a class="nav-link" href="/">Familias</a>
          </li>
          <li class="list-group-item list-group-item-action">
            <a class="nav-link" href="/">Bolsa</a>
          </li>
        </ul>
      </div>
    </div>
  </div>
</div>

<style>
  .menu-nav {
    box-shadow: rgba(0, 0, 0, 0.15) 1.95px 1.95px 2.6px;
    background-color: rgb(255, 255, 255);
  }
  i {
    font-size: 1.5rem;
  }

  .nav {
    padding: 1rem;
  }

  a {
    color: gray;
    cursor: pointer;
  }

  a:hover {
    color: rgb(40, 151, 221);
  }

  .active {
    color: rgb(40, 151, 221);
  }

  .menu {
    background: rgba( 255, 255, 255, 0.35 );
box-shadow: 0 8px 32px 0 rgba( 31, 38, 135, 0.37 );
backdrop-filter: blur( 12.5px );
-webkit-backdrop-filter: blur( 12.5px );
  }

  @media (max-width: 1000px) {
    .secciones {
      display: none !important;
    }

    .btn-menu {
      margin-right: 1rem;
    }
  }
</style>
