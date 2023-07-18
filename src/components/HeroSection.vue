<script setup>
    const heroImg = "/src/assets/img/hero_1.png.webp";
</script>

<template>

<div class="container hero-section">
    <div class="col-lg-12">
        <div class="row">
            <div class="col-lg-6" data-aos="fade-up">
                <h1>
                    Expert SEO, SEM <br> Services in London
                </h1>
                <p>
                    Far far away, behind the word mountains, far from the countries Vokalia and Consonantia, there live the blind texts. Separated they live in Bookmarksgrove right at the coast of the Semantics, a large language ocean.
                </p>
                <div class="buttons">
                    <div class="btn btn-primary">How we work</div>
                    <div class="btn btn-primary">Contact Us</div>
                </div>
            </div>
            <div class="col-lg-6" data-aos="fade-left">
                <img :src="heroImg" class="img-fluid" alt="hero section image">
            </div>
        </div>
    </div>
</div>
    
</template>

<style scoped></style>