<template>
<div class="full-screen-bg">
        <div class="content text-center">
            <div id="text-box" style="background-color: rgba(255, 242, 240, 1);">
                <h1>Savourez le monde!</h1>
                <h2>Chaque mois vous pouvez découvrir un pays différent</h2>
                <h2>Ce mois-ci est...</h2>
                <div>
                    <img src="../assets/images/so_british.png" class="img-fluid" alt="the words so british decorated in the british flag">
                </div>
            </div>
            <br>
            <div id="gift-basket" class="text-center">
                <img src="../assets/images/gift_basket.png" class="img-fluid rounded-circle p-3 bg-white" alt="a british themed gift basket">
            </div>   
        </div>
    </div>
</template>



<script>


</script>


<style>
.full-screen-bg{
    height: 110vh;
    background: url(../assets/images/british_background.png) no-repeat center center;
    background-size: cover;
    position: relative;
    color: #000;
    text-align: center;
    display: flex;
    align-items: center;
    justify-content: center;
}
.content {
    height: 100vh;
    position: relative;
    z-index: 1;

}

#text-box{
    border-radius: 10px;
}

#text-box h1 {
    padding-top: 20px;
    margin-left: auto;
    margin-right: auto;
    font-weight: bold;
    max-width: 90%;
}

#text-box h2 {
    margin-left: auto;
    margin-right: auto;
    font-weight: bold;
    max-width: 90%;
}

 /* Default size for gift-basket image */
 #gift-basket img {
    border:#000 5px solid;
    width: 80%;
    max-width: 300px;
}


</style>