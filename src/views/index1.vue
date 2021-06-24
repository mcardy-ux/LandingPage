<script>
import Navbar from "@/components/navbar";
import Service from "@/components/services";
import Features from "@/components/features";
import Pricing from "@/components/pricing";
import Blog from "@/components/blog";
import Contact from "@/components/contact";
import Footer from "@/components/footer";

/**
 * Index-1
 */
export default {
  components: { Navbar, Service, Features, Pricing, Blog, Contact, Footer }
};
</script>

<template>
  <div>
    <Navbar />
    <div v-scroll-spy>
      <!-- Hero Start -->
      <br><br>
      <section
        class="hero-1-bg"
        :style="{'background-image': 'url(' + require('@/assets/images/hero-1-bg-img.png') + ')'}"
        id="home"
      >
        <div class="container">
          <div class="row align-items-center justify-content-center">
            <div class="col-lg-6">
              <h4
                class="hero-4-title text-dark font-weight-bold text-shadow mb-4"
              >Hola, soy</h4>
              <h1
                class="hero-1-title text-dark font-weight-bold text-shadow mb-4"
              >Juan David Cardenas</h1>
              <h6
                class="hero-4-title text-dark font-weight-bold text-shadow mb-4"
              >Nickname: Mcardi</h6>
              <h3
                class="hero-4-title text-dark font-weight-bold text-shadow mb-4"
              > Me gusta desarrollar aplicaciones informáticas y te invito a conocer como se pueden crear cosas geniales con código.</h3>
              <div class="w-95 mb-6 mb-lg-0">
                <p class="text-muted mb-5 pb-5 font-size-19">
                  <span class="font-size-20 mr-2">🚀</span>Soy desarrollador de software , apasionado por crear, potenciar e innovar constantemente, Amante de la pizza <span class="font-size-20 mr-2">🍕</span>y de los buenos momentos al lado de la naturaleza. <span class="font-size-20 mr-2">🌄</span>
                  
                </p>
                <p class>
                  
                </p>
                <form action="mailto:contacto@mcardi.com">
                    <button type="submit" class="btn btn-primary" style="float:left;">Hablemos 💬</button>
                </form>
                
              </div>
            </div>
            <div class="col-lg-6 col-md-10">
              <div class="mt-5 mt-lg-0">
                
                <img src="@/assets/images/hero-1-img.png" alt class="img-fluid d-block mx-auto animate__heartBeat" />
                
              </div>
            </div>
          </div>
        </div>
      </section>
      <!-- Hero End -->
      <Service />
      <Features />
      <!-- <Pricing />  -->
      <Blog />
      <!-- <Contact /> -->
      <Footer />
    </div>
  </div>
</template>