<template>
    <div>
    <nav class="navbar navbar-expand-lg custom-navbar sticky-top" style="background-color: #E5DD90;">
         <button class="navbar-toggler overlay-toggle" type="button" @click="openNav">
             <span class="navbar-toggler-icon"></span>
             </button>
            <a class="navbar-brand navbar-center" href="index.html">
                <img src="../assets/images/SNACK_DU_MONDE_logo2.png" alt="Brand Logo">
            </a>
            <div class="d-flex align-items-center">
            <a href="panier.html" class="cart-icon position-relative" style="right: 10px; top: 50% translateY(-50%);">
                <svg xmlns="http://www.w3.org/2000/svg" width="2em" height="2em" fill="#45b046" class="bi bi-cart" viewBox="0 0 16 16">
                    <path d="M0 1.5A.5.5 0 0 1 .5 1H2a.5.5 0 0 1 .485.379L2.89 3H14.5a.5.5 0 0 1 .491.592l-1.5 8A.5.5 0 0 1 13 12H4a.5.5 0 0 1-.491-.408L2.01 3.607 1.61 2H.5a.5.5 0 0 1-.5-.5M3.102 4l1.313 7h8.17l1.313-7zM5 12a2 2 0 1 0 0 4 2 2 0 0 0 0-4m7 0a2 2 0 1 0 0 4 2 2 0 0 0 0-4m-7 1a1 1 0 1 1 0 2 1 1 0 0 1 0-2m7 0a1 1 0 1 1 0 2 1 1 0 0 1 0-2"/>
                  </svg>
            </a>
            </div>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ml-auto">
                    <li class="nav-item">
                        <a class="nav-link custom-nav-link" href="#">Abonnement</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link custom-nav-link" href="#">Les boîtes</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link custom-nav-link" href="#">À propos</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link custom-nav-link" href="#">Panier</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link custom-nav-link" href="#">Se connecter</a>
                    </li>
                </ul>
            </div>
    </nav>
    <!-- Overlay Menu -->
    <div id="myNav" class="overlay" :style="{ width: navWidth }">
      <a href="javascript:void(0)" class="closebtn" @click="closeNav">&times;</a>
      <div class="overlay-content">
        <a href="#">Accueil</a>
        <a href="#">Contact</a>
        <a href="#">FAQ</a>
        <a href="#">Abonnement</a>
        <a href="#">Les boîtes</a>
        <a href="#">À propos</a>
        <a href="#">Panier</a>
        <a href="#">Se connecter</a>
      </div>
    </div>
</div>
</template>

<script setup>
import { ref } from 'vue';

const navWidth = ref('0%');

const openNav = () => {
  navWidth.value = '80%';
};

const closeNav = () => {
  navWidth.value = '0%';
};
</script>

<style>
/* Custom CSS for overlay */
.overlay {
    height: 100%;
    width: 0;
    position: fixed;
    z-index: 1;
    top: 0;
    left: 0;
    background-color: rgba(229, 221, 144, 1);
    overflow-x: hidden;
    transition: 0.5s;
}
.overlay-content {
    position: relative;
    top: 25%;
    width: 80%;
    text-align: left;
    margin-top: 10px;
    margin-left: 20px;
}
.overlay a {
    padding: 10px;
    text-decoration: none;
    font-size: 1.5em;
    font-weight: bold;
    font-family: inter;
    color: #45b046;
    display: block;
    transition: 0.3s;
}
.overlay a:hover, .overlay a:focus {
    color: darkgreen;
}
.overlay .closebtn {
    position: absolute;
    top: 90px;
    right: 45px;
    font-size:3em;
}
.custom-navbar {
    padding: 20px 10px;
    background-color: #e5dd90; 
    border-bottom: 3px solid #45b046;
}
.custom-nav-link {
    color: #45b046;
    font-weight: bold; 
    font-size: 1.2em;
}
.custom-nav-link:hover {
    color:darkgreen; 
}
.navbar-brand img {
    height: 60px; 
}
.navbar-toggler {
    border-color: transparent;
}
.navbar-toggler-icon {
    background-image: url("data:image/svg+xml;charset=UTF8,%3Csvg viewBox='0 0 30 30' xmlns='http://www.w3.org/2000/svg'%3E%3Cpath stroke='rgba%2869, 176, 70, 1%29' stroke-width='2' stroke-linecap='round' stroke-miterlimit='10' d='M4 7h22M4 15h22M4 23h22'/%3E%3C/svg%3E");
}
.navbar-center {
    position: absolute;
    left: 50%;
    transform: translateX(-50%);
}

</style>