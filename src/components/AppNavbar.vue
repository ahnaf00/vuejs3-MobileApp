<script setup>
    const logoUrl = "/src/assets/img/logo.png.webp";
</script>

<template>
    <div class="container">
        <div class="row">
        <div class="col-lg-12">

            <!-- navbar starts -->
            <nav class="navbar navbar-expand-lg">
            <div class="container-fluid">
                <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
                </button>

                <div class="collapse navbar-collapse"  id="navbarSupportedContent">
                <img :src="logoUrl" alt="logo" >
                <div class="navbar-nav ms-auto">
                    <a class="nav-link px-4" aria-current="page" href="#">Home</a>
                    <a class="nav-link px-4" href="#">About</a>
                    <a class="nav-link px-4" href="#">Service</a>
                    <a class="nav-link px-4" href="#">FAQ</a>
                    <a class="nav-link px-4" href="#">Contact Us</a>
                    <a class="nav-link px-4 button">Download</a>
                </div>
                </div>
            </div>
            </nav>     
            <!-- Navbar nds -->
            
        </div>
        </div>
  </div>
</template>

<style scoped>
</style>