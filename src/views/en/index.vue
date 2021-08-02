<script>
import Navbar from "@/components/en/navbar";
import Service from "@/components/en/services";
import Features from "@/components/en/features";
import Pricing from "@/components/en/pricing";
import Blog from "@/components/en/blog";
import Contact from "@/components/en/contact";
import Footer from "@/components/en/footer";

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
              >Hi everyone. </h4>
              <h1
                class="hero-1-title text-dark font-weight-bold text-shadow mb-4"
              >This is Juan David Cardenas </h1>
              <h6
                class="hero-4-title text-dark font-weight-bold text-shadow mb-4"
              >but you can call me Mcardy.</h6>
              <h3
                class="hero-4-title text-dark font-weight-bold text-shadow mb-4"
              > I love developing apps and software.</h3>
              <div class="w-95 mb-6 mb-lg-0">
                <p class="text-muted mb-5 pb-5 font-size-19">
                  <span class="font-size-20 mr-2">🚀</span> I would like you to know the great things that can be made out of coding. I'm a software developer passionate about creating and innovating. I'm a hardcore pizza lover<span class="font-size-20 mr-2">🍕</span> and I also love good moments in nature <span class="font-size-20 mr-2">🌄</span>.                  
                </p>
                <p class>
                  
                </p>
                <form action="mailto:contacto@mcardi.com">
                    <button type="submit" class="btn btn-primary" style="float:left;">Contact Me 💬</button>
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