<script>
import {
  FacebookIcon,
  GithubIcon,
  InstagramIcon,
  LinkedinIcon
} from "vue-feather-icons";
export default {
  components: {
    FacebookIcon,
    GithubIcon,
    InstagramIcon,
    LinkedinIcon
  }
};
</script>

<template>
  <div>
    <!-- Footer Start -->
    <section class="footer" style="background-image: url(assets/images/footer-bg.png)">
      <div class="container">
        <div class="row">
          <div class="col-lg-4">
            <div class="mb-5">
              
               <img src="@/assets/images/footer_img_myself.jpg" alt class style="width:100px; height:100px;  border-radius:150px;"   />
                <hr>
              <img src="@/assets/images/logo-light.png" alt class height="24" />
             
              <p class="text-white-50 my-4 font-size-15">
                Diseñamos y creamos tu propia página web con calidad profesional. Ya sea que estés promocionando tu negocio, mostrando tu trabajo, abriendo tu tienda online o automatizando procesos.
              </p>
              <ul class="list-inline footer-social-icon-content">
                <li class="list-inline-item mr-4">
                  <a href="https://www.facebook.com/profile.php?id=100041706443009" target="_blank" class="footer-social-icon">
                    <facebook-icon></facebook-icon>
                  </a>
                </li>
                <li class="list-inline-item mr-4">
                  <a href="https://github.com/mcardy-ux" target="_blank" class="footer-social-icon">
                    <github-icon></github-icon>
                  </a>
                </li>
                <li class="list-inline-item mr-4">
                  <a href="https://www.instagram.com/ux.mcardi/?hl=es" target="_blank" class="footer-social-icon">
                    <instagram-icon></instagram-icon>
                  </a>
                </li>
                <li class="list-inline-item">
                  <a href="https://www.linkedin.com/in/juanchodavid54/" target="_blank" class="footer-social-icon">
                    <linkedin-icon></linkedin-icon>
                  </a>
                </li>
              </ul>
            </div>
          </div>
          <div class="col-lg-7 offset-lg-1">
            <div class="row">
              
              
              <div class="container">
                    <div class="row justify-content-center">
                      <div class="col-lg-10">
                        <div class="text-center mb-5">
                          <h3 class=" text-white mb-3">Contáctame</h3>
                            <p class="text-white-50 my-4 font-size-15">
                              Escribe un poco de tus necesidades especificas en la parte digital al email y 
                              estaré encantado de encontrar la solución mas adecuada para ti. ¡Espero tu mensaje Pronto! 

                            </p>
                          
                              <div class="contact-detail text-white ">
                                <p class>
<<<<<<< HEAD
                                  <a href="mailto:admin@mcardi.com" target="_blank">
                                  <strong>Email: </strong>
                                  <span>admin@mcardi.com</span>
=======
                                  <a  style="color:#ffff" href="mailto:admin@mcardi.com" target="_blank">
                                  <mail-icon class="icon-xs icon mr-1"></mail-icon><strong>Email: </strong>
                                  <span >admin@mcardi.com</span>
>>>>>>> 780d2e2504cd895158aa5fdea34ba00850c3b3c0
                                  </a>
                                </p>
                                
                              
                                <p class>
                                  <strong>Horario: </strong>
                                  <span>9:00 AM - 5:00 PM</span>
                                </p>
                                <p class>
                                  <strong>De: </strong>
                                  <span>Colombia</span>
                                </p>
                              </div>
                              </div>
                            </div>
                          </div>
                      </div>
                    


            </div>
          </div>
        </div>
      </div>
    </section>
    <div class="footer-alt py-3">
      <div class="container">
        <div class="row">
          <div class="col-lg-12">
            <div class="text-center">
              <p
                class="text-white-50 font-size-15 mb-0"
              >{{ new Date().getFullYear()}} © Mcardi. Design by Mcardi</p>
            </div>
          </div>
        </div>
      </div>
    </div>
    <!-- Footer End -->
  </div>
</template>