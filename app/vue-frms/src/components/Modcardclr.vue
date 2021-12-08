<template>
    <section>
        <b-steps
            v-model="activeStep"
            :animated="isAnimated"
            :has-navigation="hasNavigation"
            :icon-prev="prevIcon"
            :icon-next="nextIcon"
            :label-position="labelPosition"
            :mobile-mode="mobileMode"
            type="is-warning"
            >
            <b-step-item step="1" label="Paso" :clickable="isStepsClickable">
                
              <v-card
                    class="mx-auto card-contnt"
                    height="200"
                    width="1200"
                    >
                    <h1 class="title has-text-left card-h1"><i class="far fa-bell"></i>16 de Julio al 13 de Agosto 2021</h1> 
                    <hr class="solid">     
                    <p class="p-txt"><i class="far fa-clock"></i>Cuestionario de opinión sobre los servicios de la UNAM, Actualización de datos y optativas DIMEI</p>
                   
                </v-card>
            </b-step-item>

            <b-step-item step="2" label="Paso" :clickable="isStepsClickable">
                <v-card
                    class="mx-auto card-contnt"
                    height="200"
                    width="1200"
                    >
                    <h1 class="title has-text-left card-h1"><i class="far fa-bell"></i>16 de Julio al 13 de Agosto 2021</h1> 
                    <hr class="solid">     
                    <p class="p-txt"><i class="far fa-clock"></i>Cuestionario de opinión sobre los servicios de la UNAM, Actualización de datos y optativas DIMEI</p>
                   
                </v-card>
            </b-step-item>

            <b-step-item step="3" label="Paso" :clickable="isStepsClickable">
                <v-card
                    class="mx-auto card-contnt"
                    height="200"
                    width="1200"
                    >
                    <h1 class="title has-text-left card-h1"><i class="far fa-bell"></i>16 de Julio al 13 de Agosto 2021</h1> 
                    <hr class="solid">     
                    <p class="p-txt"><i class="far fa-clock"></i>Cuestionario de opinión sobre los servicios de la UNAM, Actualización de datos y optativas DIMEI</p>
                   
                </v-card>
            </b-step-item>

            <b-step-item step="4" label="Paso" :clickable="isStepsClickable" disabled>
                <v-card
                    class="mx-auto card-contnt"
                    height="200"
                    width="1200"
                    >
                    <h1 class="title has-text-left card-h1"><i class="far fa-bell"></i>16 de Julio al 13 de Agosto 2021</h1> 
                    <hr class="solid">     
                    <p class="p-txt"><i class="far fa-clock"></i>Cuestionario de opinión sobre los servicios de la UNAM, Actualización de datos y optativas DIMEI</p>
                   
                </v-card>
            </b-step-item>
            <b-step-item step="5" label="Paso" :clickable="isStepsClickable" disabled>
                <v-card
                    class="mx-auto card-contnt"
                    height="200"
                    width="1200"
                    >
                    <h1 class="title has-text-left card-h1"><i class="far fa-bell"></i>16 de Julio al 13 de Agosto 2021</h1> 
                    <hr class="solid">     
                    <p class="p-txt"><i class="far fa-clock"></i>Cuestionario de opinión sobre los servicios de la UNAM, Actualización de datos y optativas DIMEI</p>
                   
                </v-card>
            </b-step-item>
            <b-step-item step="7" label="Paso" :clickable="isStepsClickable" disabled>
                <v-card
                    class="mx-auto card-contnt"
                    height="200"
                    width="1200"
                    >
                    <h1 class="title has-text-left card-h1"><i class="far fa-bell"></i>16 de Julio al 13 de Agosto 2021</h1> 
                    <hr class="solid">     
                    <p class="p-txt"><i class="far fa-clock"></i>Cuestionario de opinión sobre los servicios de la UNAM, Actualización de datos y optativas DIMEI</p>
                   
                </v-card>
            </b-step-item>
            <b-step-item step="8" label="Paso" :clickable="isStepsClickable" disabled>
                <v-card
                    class="mx-auto card-contnt"
                    height="200"
                    width="1200"
                    >
                    <h1 class="title has-text-left card-h1"><i class="far fa-bell"></i>16 de Julio al 13 de Agosto 2021</h1> 
                    <hr class="solid">     
                    <p class="p-txt"><i class="far fa-clock"></i>Cuestionario de opinión sobre los servicios de la UNAM, Actualización de datos y optativas DIMEI</p>
                   
                </v-card>
            </b-step-item>
            <b-step-item step="9" label="Paso" :clickable="isStepsClickable" disabled>
               <v-card
                    class="mx-auto card-contnt"
                    height="200"
                    width="1200"
                    >
                    <h1 class="title has-text-left card-h1"><i class="far fa-bell"></i>16 de Julio al 13 de Agosto 2021</h1> 
                    <hr class="solid">     
                    <p class="p-txt"><i class="far fa-clock"></i>Cuestionario de opinión sobre los servicios de la UNAM, Actualización de datos y optativas DIMEI</p>
                   
                </v-card>
            </b-step-item>
            <b-step-item step="10" label="Paso" :clickable="isStepsClickable" disabled>
               <v-card
                    class="mx-auto card-contnt"
                    height="200"
                    width="1200"
                    >
                    <h1 class="title has-text-left card-h1"><i class="far fa-bell"></i>16 de Julio al 13 de Agosto 2021</h1> 
                    <hr class="solid">     
                    <p class="p-txt"><i class="far fa-clock"></i>Cuestionario de opinión sobre los servicios de la UNAM, Actualización de datos y optativas DIMEI</p>
                   
                </v-card>
            </b-step-item>
            <b-step-item step="11" label="Paso" :clickable="isStepsClickable" disabled>
               <v-card
                    class="mx-auto card-contnt"
                    height="200"
                    width="1200"
                    >
                    <h1 class="title has-text-left card-h1"><i class="far fa-bell"></i>16 de Julio al 13 de Agosto 2021</h1> 
                    <hr class="solid">     
                    <p class="p-txt"><i class="far fa-clock"></i>Cuestionario de opinión sobre los servicios de la UNAM, Actualización de datos y optativas DIMEI</p>
                   
                </v-card>
            </b-step-item>
            <b-step-item step="13" label="Paso" :clickable="isStepsClickable" disabled>
                <v-card
                    class="mx-auto card-contnt"
                    height="200"
                    width="1200"
                    >
                    <h1 class="title has-text-left card-h1"><i class="far fa-bell"></i>16 de Julio al 13 de Agosto 2021</h1> 
                    <hr class="solid">     
                    <p class="p-txt"><i class="far fa-clock"></i>Cuestionario de opinión sobre los servicios de la UNAM, Actualización de datos y optativas DIMEI</p>
                   
                </v-card>
            </b-step-item>
        </b-steps>
    </section>
</template>

<script>
    export default {
        data() {
            return {
                activeStep: 6,

                isAnimated: true,
                isStepsClickable: true,

                hasNavigation: false,
                customNavigation: false,

                prevIcon: 'chevron-left',
                nextIcon: 'chevron-right',
                labelPosition: 'left',
                mobileMode: 'compact'
            }
        }
    }
</script>
<style scoped>
hr.solid {
  border-top: 2px solid #acacac ;
}
.card-contnt{
    padding: 2em 8em; 
    display: hidden;
    border-radius: 20px;
}
.card-h1{
    color: #DA5E28;
}
.fa-clock{
    font-size: 20px; 
    color: #DA5E28;
    margin-right: 1em;
}
.fa-bell{
    font-size: 55px; 
    color: #DA5E28;
    text-align: left;
    margin-right: 0.5em;
}
.p-txt{
    color:#5a5a5a;
    font-weight: bolder;
}

</style>