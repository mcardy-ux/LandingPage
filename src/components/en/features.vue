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
              <h3 class="title mb-3">Development</h3>
              <p class="text-muted font-size-15">
               I offer a bunch of solutions like apps for mobile devices, API REST, apps for smartwatches, corporative apps, and much more.
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
              <i class="mdi mdi-chart-bubble h2 text-primary mr-1 align-middle"></i>Backend development
            </p>
            <h3 class="font-weight-semibold line-height-1_4 mb-4">
             The coding lines can boot <strong>innovate</strong> and point out your objectives and ideas. 
            </h3>
           
            <p class="text-muted mb-2">
              <layout-icon class="icon-xs mr-1"></layout-icon>Fullstack development
            </p>
            <p class="text-muted">
              <life-buoy-icon class="icon-xs mr-1"></life-buoy-icon>Websites, Online Stores, and creative apps.
            </p>
            <div class="mt-5">
              <a href="https://github.com/mcardy-ux?tab=repositories" target="_blank" class="btn btn-primary mr-2">See our proyects.</a>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- Features End -->
  </div>
</template>