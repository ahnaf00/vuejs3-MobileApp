<script setup>

const icon1 = "/src/assets/img/rocket.png";
const icon2 = "/src/assets/img/trophy.png";
const icon3 = "/src/assets/img/link.png";
const feature = "Our Feature";

</script>

<template>
    <div class="container feature">
      <div class="row">
        <div class="col-lg-12" data-aos="fade-up">
          <div class="feature-head text-center">
            <h1>{{ feature }}</h1>
            <p class="">Far far away, behind the word mountains, far from the countries Vokalia<br> and Consonantia, there live the blind texts. Separated they live in Bookmarksgrove<br> right at the coast of the Semantics, a large language ocean.</p>
          </div>
        </div>
        <!-- Features -->
        <div class="col-lg-12">
          <div class="feature-cild">

            <div class="row">
              <div class="col-lg-4" data-aos="fade-up">
                <div class="text-center">
                  <div class="icon">
                    <img :src="icon1" class="img-fluid" alt="">
                  </div>
                  <h3>Marketing Analysis</h3>
                  <p>Far far away, behind the word mountains<br>, far from the countries Vokalia and<br> Consonantia, there live the blind texts.</p>
                </div>
              </div>

              <div class="col-lg-4" data-aos="fade-up">
                <div class="text-center">
                  <div class="icon">
                    <img :src="icon3" class="img-fluid" alt="">
                  </div>
                  <h3>Digital Marketing</h3>
                  <p>Far far away, behind the word mountains<br>, far from the countries Vokalia and<br> Consonantia, there live the blind texts.</p>
                </div>
              </div>

              <div class="col-lg-4" data-aos="fade-up">
                <div class="text-center">
                  <div class="icon">
                    <img :src="icon2" class="img-fluid" alt="">
                  </div>
                  <h3>SEO and Backlinks</h3>
                  <p>Far far away, behind the word mountains<br>, far from the countries Vokalia and <br>Consonantia, there live the blind texts.</p>
                </div>
              </div>

            </div>

          </div>
        </div>
      </div>
    </div>
</template>

<style scoped></style>