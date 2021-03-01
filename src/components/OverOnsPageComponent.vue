<template>
    <div>
        <b-container class="contents">
            <div>
                <b-jumbotron>
                    <template v-slot:header>Voor en door de zorg.</template>
                    <template v-slot:lead>
                        Rond in de Zorg is een dienstverlener die zorgorganisaties helpt met actuele HRM-vraagstukken op het gebied van interim personeel, werving en selectie en outplacement.
                    </template>
                </b-jumbotron>
            </div>
            <b-row>
                <b-col class="p-3">
                    <div class="row text-content">
                        <div class="ridz-box">
                            <img class="ridz-logo" src="../img/logo2.png" />
                            <span>Voor en door de zorg</span>
                        </div>
                        <p>
                            Rond in de Zorg ondersteunt zorgorganisaties bij het oplossen van Ad Hoc problemen en ook detacheringsopdrachten. Wij zorgen ervoor dat het vaste personeel ontlast wordt in hun werkzaamheden en met veel plezier blijft werken.<br><br>
                            Naast onze dienstverlening houden wij u op de hoogte van de succesverhalen van uw collega's in het land. Wat zijn bijvoorbeeld de ervaringen met het invoeren van talent management, kennismanagement en prestatiemanagement? Wij creëren een platform voor het delen van kennis en ervaring. Daarnaast bieden wij u de helpende hand bij het realiseren van uw ambities en het oplossen van knelpunten.
                        </p>
                    </div>
                </b-col>
                <menu-component></menu-component>
            </b-row>
        </b-container>
    </div>
</template>

<script>
    import MenuComponent from "./MenuComponent";

    export default {
        components: {MenuComponent},
        name: "OverOnsPageComponent"
    }
</script>

<style scoped>
    .contents{
        margin-top: 25px;
        margin-bottom: 25px;
    }

    .ridz-box{
        display: flex;
        align-items: center;
        margin-bottom: 15px;
    }

    .ridz-box span{
        font-size: 25px;
    }

    .ridz-logo{
        width: 55px;
        height: 55px;
        margin-right: 15px;
    }

    .text-content{
        text-align: left;
    }

    .jumbotron {
        text-align: left;
    }

</style>
