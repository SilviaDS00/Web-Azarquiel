<script>
  import Nav from "../lib/nav.svelte";
  import Footer from "../lib/footer.svelte";
  import Contacto from "../lib/contacto.svelte"
</script>

<!-- Para hacer el header, el nav, el desplegable y el footer y se reutiliza esta estructura en todas las paginas -->

<Contacto/>

<Nav/>

<slot></slot>

<Footer/>
