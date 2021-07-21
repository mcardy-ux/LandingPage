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
            >Encontraras los artículos de los temas mas interesantes que me han impresionado, Chécalos y déjame tu feedback.</p>
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
                <calendar-icon class="icon-size-15 icon mr-1"></calendar-icon>01 Julio 2021
              </li>
              <li class="list-inline-item">
                <user-icon class="icon-size-15 icon mr-1"></user-icon>Juan Cardenas
              </li>
            </ul>
            <a
              href="http://blog.mcardi.com/programming"
              class="text-dark font-weight-bold h5"
            >¿Como puede mejorar tu empresa con un buen diseño web?</a>
            <p
              class="text-muted font-size-15"
            >El diseño de un sitio web se ha convertido mas que transmitir sentimientos, proveer accesibilidad o identificar tu sector. Ahora es igual de importante incrementar el nivel de confianza, prestigio y confianza hacia tu producto o servicio, Por ello invertir en el diseño de tu pagina web es un aspecto importante. A continuación encontraras variadas razones para tener en cuenta al mejorar tu pagina web.</p>
            <a href="http://blog.mcardi.com/programming" class="text-primary font-weight-semibold">
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
                <calendar-icon class="icon-size-15 icon mr-1"></calendar-icon>01 Julio 2021
              </li>
              <li class="list-inline-item">
                <user-icon class="icon-size-15 icon mr-1"></user-icon>Juan Cardenas
              </li>
            </ul>
            <a
              href="http://blog.mcardi.com/marketing"
              class="text-dark font-weight-bold h5"
            >¿Que beneficios existen en utilizar marketing Digital?</a>
            <p
              class="text-muted font-size-15"
            >Lograr vender productos o servicios a posibles clientes en los medios digitales se ha convertido en una faceta primordial, A continuación encontraras los principales beneficios de tener en cuenta el marketing digital...</p>
            <a href="http://blog.mcardi.com/marketing" class="text-primary font-weight-semibold">
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
                <calendar-icon class="icon-size-15 icon mr-1"></calendar-icon>01 Julio 2021
              </li>
              <li class="list-inline-item">
                <user-icon class="icon-size-15 icon mr-1"></user-icon>Juan Cardenas
              </li>
            </ul>
            <a
              href="http://blog.mcardi.com/design"
              class="text-dark font-weight-bold h5"
            >¿Que beneficios puede aportar tu propio logo?</a>
            <p
              class="text-muted font-size-15"
            >Uno de los objetivos al plasmar tu marca o idea en una imagen es que sea fácil de reconocer, recordar y evocar un buen pensamiento en la persona que lo ve. Y desde luego es muy importante apelar a las conexiones que tenemos como seres humanos como a nivel de gusto, identificación y representación. Pero ademas de tener estos objetivos en mente, puedes ponerte como meta estos objetivos para que tu propio logo genere beneficios...</p>
            <a href="http://blog.mcardi.com/design" class="text-primary font-weight-semibold">
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