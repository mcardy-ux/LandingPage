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
                We design and create your own website with high professional quality. Whether you are promoting your business, releasing your online store, or automatizing processes. 
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
                          <h3 class=" text-white mb-3">Contact me</h3>
                            <p class="text-white-50 my-4 font-size-15">
                              Let me know what your necessities are, make an online request by sending it to the email. I will be more than glad to help you. 
                               I look forward to hearing from you soon!
                            </p>
                          
                              <div class="contact-detail text-white ">
                                <p class>
                                  <a href="mailto:admin@mcardi.com" target="_blank">
                                  <strong>Email: </strong>
                                  <span>admin@mcardi.com</span>
                                  </a>
                                </p>
                                
                              
                                <p class>
                                  <strong>Available: </strong>
                                  <span>9:00 AM - 5:00 PM | UTC−5</span>
                                </p>
                                <p class>
                                  <strong>From: </strong>
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