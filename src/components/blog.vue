<script>
import { CalendarIcon, UserIcon } from "vue-feather-icons";
export default {
  components: {
    CalendarIcon,
    UserIcon
  }
};
</script>
<template>
  <!-- Blog start -->
  <section class="section" id="blog">
    <div class="container">
      <div class="row justify-content-center">
        <div class="col-lg-6">
          <div class="text-center mb-5">
            <h3 class="title mb-3">Artículos de Interés</h3>
            <p
              class="text-muted font-size-15"
            >Encontraras los articulos de los temas mas interesantes que me han impresionado, Checalos y dejame tu feedback.</p>
          </div>
        </div>
      </div>

      <div class="row">
        <div class="col-lg-4">
          <div class="blog-box mb-4 mb-lg-0">
            <img src="@/assets/images/blog/img-1.png" alt class="img-fluid d-block mx-auto rounded" />
            <ul
              class="list-inline text-muted text-uppercase font-size-15 font-weight-medium mt-3 mb-2"
            >
              <li class="list-inline-item mr-3">
                <calendar-icon class="icon-size-15 icon mr-1"></calendar-icon>01 Noviembre 2021
              </li>
              <li class="list-inline-item">
                <user-icon class="icon-size-15 icon mr-1"></user-icon>Juan Cardenas
              </li>
            </ul>
            <a
              href="javascript: void(0);"
              class="text-dark font-weight-bold h5"
            >Top 10 - Como mejorar tu empresa con un buen diseño web</a>
            <p
              class="text-muted font-size-15"
            >Integer ante arcu accumsan a consectetuer eget posuere mauris praesent adipiscing phasellus ullamcorper ipsum rutrum punc.</p>
            <a href="javascript: void(0);" class="text-primary font-weight-semibold">
              Leer Mas
              <span class="ml-2 right-icon">&#8594;</span>
            </a>
          </div>
        </div>
        <div class="col-lg-4">
          <div class="blog-box blog-box mb-4 mb-lg-0">
            <img src="@/assets/images/blog/img-2.png" alt class="img-fluid d-block mx-auto rounded" />
            <ul
              class="list-inline text-muted text-uppercase font-size-15 font-weight-medium mt-3 mb-2"
            >
              <li class="list-inline-item mr-3">
                <calendar-icon class="icon-size-15 icon mr-1"></calendar-icon>01 Noviembre 2021
              </li>
              <li class="list-inline-item">
                <user-icon class="icon-size-15 icon mr-1"></user-icon>Juan Cardenas
              </li>
            </ul>
            <a
              href="javascript: void(0);"
              class="text-dark font-weight-bold h5"
            >¿Que beneficios existen en utilizar marketing Digital?</a>
            <p
              class="text-muted font-size-15"
            >Integer ante arcu accumsan a consectetuer eget posuere mauris praesent adipiscing phasellus ullamcorper ipsum rutrum punc.</p>
            <a href="javascript: void(0);" class="text-primary font-weight-semibold">
              Leer Mas
              <span class="ml-2 right-icon">&#8594;</span>
            </a>
          </div>
        </div>
        <div class="col-lg-4">
          <div class="blog-box blog-box mb-4 mb-lg-0">
            <img src="@/assets/images/blog/img-3.png" alt class="img-fluid d-block mx-auto rounded" />
            <ul
              class="list-inline text-muted text-uppercase font-size-15 font-weight-medium mt-3 mb-2"
            >
              <li class="list-inline-item mr-3">
                <calendar-icon class="icon-size-15 icon mr-1"></calendar-icon>01 Noviembre 2021
              </li>
              <li class="list-inline-item">
                <user-icon class="icon-size-15 icon mr-1"></user-icon>Juan Cardenas
              </li>
            </ul>
            <a
              href="javascript: void(0);"
              class="text-dark font-weight-bold h5"
            >Como hacer que tu propio logo genere beneficios.</a>
            <p
              class="text-muted font-size-15"
            >Integer ante arcu accumsan a consectetuer eget posuere mauris praesent adipiscing phasellus ullamcorper ipsum rutrum punc.</p>
            <a href="javascript: void(0);" class="text-primary font-weight-semibold">
              Leer Mas
              <span class="ml-2 right-icon">&#8594;</span>
            </a>
          </div>
        </div>
      </div>
    </div>
  </section>
  <!-- Blog End -->
</template>