<script setup>
    const aboutImg = "/src/assets/img/about_1.png.webp";
    const title = "Why Our Agency";
</script>
<template>
        <div class="container about">
            <div class="row">
                <div class="col-lg-12">
                    <div class="row">
                        <div class="col-lg-6" data-aos="fade-up">
                        <img :src="aboutImg" class="img-fluid" alt="">
                        </div>
                        <div class="col-lg-6 info" data-aos="fade-up">
                        <h1>{{ title }}</h1>
                        <p>Separated they live in Bookmarksgrove right at the coast of the Semantics, a large language ocean.</p>

                        <p>Far far away, behind the word mountains, far from the countries Vokalia and Consonantia, there live the blind texts. Separated they live in Bookmarksgrove right at the coast of the Semantics, a large language ocean.</p>
                        <ul class="list-items">
                            <li>  Behind the word mountains</li>
                            <li>Bookmarksgrove right at the coast</li>
                            <li>Semantics, a large language</li>
                        </ul>

                        <div class="btn btn-primary">About Us</div>
                        </div>
                    </div>
                </div> 
            </div>
        </div>
</template>

<style scoped></style>