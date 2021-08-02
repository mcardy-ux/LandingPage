<script>
import {
  LayoutIcon,
  LifeBuoyIcon,
  ServerIcon,
  RssIcon
} from "vue-feather-icons";
export default {
  components: { LayoutIcon, LifeBuoyIcon, ServerIcon, RssIcon }
};
</script>

<template>
  <div>
    <!-- Features Start -->
    <section
      class="section bg-light feather-bg-img"
      :style="{'background-image': 'url(' + require('@/assets/images/features-bg-img.png') + ')'}"
      id="features"
    >
      <div class="container">
        <div class="row justify-content-center">
          <div class="col-lg-6">
            <div class="text-center mb-5">
              <h3 class="title mb-3">Desarrollo de todo tipo</h3>
              <p class="text-muted font-size-15">
                Me gusta desarrollar soluciones de todo tipo, desde apps para dispositivos móviles, API REST, Apps para Relojes Inteligentes, Aplicaciones Corporativas y muchos mas.
              </p>
            </div>
          </div>
        </div>

        <div class="row align-items-center">
          <div class="col-lg-6">
            <div class="mb-4 mb-lg-0">
              <img src="@/assets/images/features-img.gif" alt class="img-fluid d-block mx-auto" />
            </div>
          </div>

          <div class="col-lg-5 offset-lg-1">
            <p class="font-weight-medium text-uppercase mb-2">
              <i class="mdi mdi-chart-bubble h2 text-primary mr-1 align-middle"></i> DESARROLLO BACKEND
            </p>
            <h3 class="font-weight-semibold line-height-1_4 mb-4">
              Líneas de Código pueden 
              <b>Potenciar</b>,
              <b>innovar</b>,
              <b>destacar</b> tus objetivos e ideas.
            </h3>
           
            <p class="text-muted mb-2">
              <layout-icon class="icon-xs mr-1"></layout-icon>Desarrollo FullStack
            </p>
            <p class="text-muted">
              <life-buoy-icon class="icon-xs mr-1"></life-buoy-icon>Paginas Web, Tiendas Online, Aplicaciones Creativas.
            </p>
            <div class="mt-5">
              <a href="https://github.com/mcardy-ux?tab=repositories" target="_blank" class="btn btn-primary mr-2">Ver Proyectos</a>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- Features End -->
  </div>
</template>