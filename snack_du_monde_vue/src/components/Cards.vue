<template>
<div class="container-fluid py-5">
    <div class="row">
        <div class="col-md-4 text-center">
            <div class="card mb-4" style="background-color: #f2f9e7;" >
                <div class="card-body">
                    <h4 class="card-title">Comment ça marche ?</h4>
                    <br>
                    <p class="card-text">Choissisez votre forfait et commencez votre tour du monde !</p>
                    <p>Choisissez le forfait qui vous convient : plus l'abonnement est long, moins la boîte est chère !</p>
                    <br>
                    <p>Livraison dans le monde entier : Votre boîte vous sera envoyée régulièrement chaque mois, où que vous soyez !</p>
                    <br>
                    <p>Dégustez, c'est tout !</p>
                    <a href="abonnement.html" class="btn btn-success">Abonnez-vous</a>
                </div>
            </div>
        </div>
        <div class="col-md-4 text-center">
            <div class="card mb-4" style="background-color: #f2f9e7;">
                <div class="card-body">
                    <h4 class="card-title">Dans chaque boîte vous trouverez...</h4>
                    <table class="table table-borderless">
                        <thead>
                            <tr>
                                <th scope="col"></th>
                                <th scope="col"></th>
                                <th scope="col"></th>
                                <th scope="col"></th>
                            </tr>
                        </thead>
                        <tbody>
                            <tr>
                                <th scope="row"><img src="../assets/images/cookie.png"></th>
                                <td colspan="3" style="text-align: left; vertical-align: middle;">Des paquets de délicieux biscuits - salés ou sucrés</td>
                            </tr>
                            <tr>
                                <th scope="row"><img src="../assets/images/cake.png"></th>
                                <td colspan="3" style="text-align: left; vertical-align: middle;">Une sélection de beaux gâteaux et pâtisseries</td>
                            </tr>
                            <tr>
                                <th scope="row"><img src="../assets/images/bonbon.png"></th>
                                <td colspan="3" style="text-align: left; vertical-align: middle;">Beaucoup de friandises traditionnelles</td>
                            </tr>
                            <tr>
                                <th scope="row"><img src="../assets/images/theiere.png"></th>
                                <td colspan="3" style="text-align: left; vertical-align: middle;">Une sélection de thés, cafés ou autres boissons chaudes typiques du pays du mois</td>
                            </tr>
                            <tr>
                                <th scope="row"><img src="../assets/images/soda.png"></th>
                                <td colspan="3" style="text-align: left; vertical-align: middle;">Les meilleurs sodas et boissons fraîches</td>
                            </tr>
                        </tbody>

                    </table>
                    <a href="les_boites.html" class="btn btn-success">En savoir plus</a>
                </div>
            </div>
        </div>
        <div class="col-md-4">
            <div class="card mb-4" style="background-color: #f2f9e7;">
                <div class="card-body text-center">
                    <h4 class="card-title">Vous trouverez également...</h4>
                    <table class="table table-borderless">
                        <thead>
                            <tr>
                                <th scope="col"></th>
                                <th scope="col"></th>
                                <th scope="col"></th>
                                <th scope="col"></th>
                            </tr>
                        </thead>
                        <tbody>
                            <tr>
                                <th scope="row"><img src="../assets/images/ble.png"></th>
                                <td colspan="3" style="text-align: left; vertical-align: middle;">Un guide contenant toutes les informations dont vous avez besoin concernant la nutrition et les allergènes.</td>
                            </tr>
                            <tr>
                                <th scope="row"><img src="../assets/images/book.png"></th>
                                <td colspan="3" style="text-align: left; vertical-align: middle;">Un guide culturel spécifique au pays du mois</td>
                            </tr>
                            <tr>
                                <th scope="row"><img src="../assets/images/avion.png"></th>
                                <td colspan="3" style="text-align: left; vertical-align: middle;">Des informations complètes sur nos modes et tarifs de livraison</td>
                            </tr>
                        </tbody>
                    </table>
                    <a href="#" class="btn btn-success">En savoir plus</a>
                </div>
            </div>
        </div>
    </div>
</div>

</template>

<script>


</script>

<style>

.card{
    height:95%;
    font-size: 1.2em;
    font-weight:500;
    border:#45b046 solid 2px;
    border-radius: 15px;
}
.card-title{
    color: #45b046;
    font-weight: bold;
}
table td{
    vertical-align: middle;
    height:80px;

}
table th img{
    width:100%;
    height:auto;
    background-color: #e5dd90;
    border:#45b046 solid 3px;
    border-radius: 10px;
    padding:1em;
}

</style>