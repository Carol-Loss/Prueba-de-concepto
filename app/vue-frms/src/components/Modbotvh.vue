<template>
    <section>
        <b-steps
            v-model="activeStep"
            :animated="isAnimated"
            :rounded="isRounded"
            :has-navigation="hasNavigation"
            :icon-prev="prevIcon"
            :icon-next="nextIcon"
            :label-position="labelPosition"
            :mobile-mode="mobileMode"
            type="is-danger">
            <b-step-item step="0" label="Contar con contraseña personalizada" :clickable="isStepsClickable">
                <v-row>
          
          <v-col>
            <a href="https://www.ssa.ingenieria.unam.mx/"><h1>Paso 1</h1></a>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolorum magnam asperiores dicta accusamus inventore dolore officia sapiente, corporis perspiciatis numquam assumenda provident voluptatum, natus dolor. Ducimus saepe quod debitis repellat.
            Corrupti minus, earum sapiente quo quod similique fuga asperiores sit molestias autem velit deleniti rem culpa commodi maxime tempora, quae debitis. Est iste eaque, accusamus harum laborum eligendi ab dolore!
          </v-col>
          <v-col>
            <v-img
              class="img--p2"
              src="../assets/0H0.png"
              width="200px"
            ></v-img>
          </v-col>
        </v-row>
          
            </b-step-item>

            <b-step-item step="1" label="Actualización de datos y optativas DIMEI" :clickable="isStepsClickable">
                <v-row>
          
          <v-col>
            <a href="https://www.ssa.ingenieria.unam.mx/"><h1>Paso 2</h1></a>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolorum magnam asperiores dicta accusamus inventore dolore officia sapiente, corporis perspiciatis numquam assumenda provident voluptatum, natus dolor. Ducimus saepe quod debitis repellat.
            Corrupti minus, earum sapiente quo quod similique fuga asperiores sit molestias autem velit deleniti rem culpa commodi maxime tempora, quae debitis. Est iste eaque, accusamus harum laborum eligendi ab dolore!
          </v-col>
          <v-col>
            <v-img
              class="img--p2"
              src="../assets/1H1.png"
              width="200px"
            ></v-img>
          </v-col>
        </v-row>
            </b-step-item>
          
          <b-step-item step="2" label="Publicación de grupos y horarios programados" :clickable="isStepsClickable">
                <v-row>
          
          <v-col>
            <a href="https://www.ssa.ingenieria.unam.mx/"><h1>Paso 3</h1></a>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolorum magnam asperiores dicta accusamus inventore dolore officia sapiente, corporis perspiciatis numquam assumenda provident voluptatum, natus dolor. Ducimus saepe quod debitis repellat.
            Corrupti minus, earum sapiente quo quod similique fuga asperiores sit molestias autem velit deleniti rem culpa commodi maxime tempora, quae debitis. Est iste eaque, accusamus harum laborum eligendi ab dolore!
          </v-col>
          <v-col>
            <v-img
              class="img--p2"
              src="../assets/2H2.png"
              width="200px"
            ></v-img>
          </v-col>
        </v-row>
            </b-step-item>
            <b-step-item step="3" label="Consulta de número de inscripción" :clickable="isStepsClickable">
                <v-row>
          
          <v-col>
            <a href="https://www.ssa.ingenieria.unam.mx/"><h1>Paso 4</h1></a>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolorum magnam asperiores dicta accusamus inventore dolore officia sapiente, corporis perspiciatis numquam assumenda provident voluptatum, natus dolor. Ducimus saepe quod debitis repellat.
            Corrupti minus, earum sapiente quo quod similique fuga asperiores sit molestias autem velit deleniti rem culpa commodi maxime tempora, quae debitis. Est iste eaque, accusamus harum laborum eligendi ab dolore!
          </v-col>
          <v-col>
            <v-img
              class="img--p2"
              src="../assets/3H3.png"
              width="200px"
            ></v-img>
          </v-col>
        </v-row>
            </b-step-item>

            <b-step-item step="4" label="Inscripción por internet" :clickable="isStepsClickable">
                <v-row>
          
          <v-col>
            <a href="https://www.ssa.ingenieria.unam.mx/"><h1>Paso 5</h1></a>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolorum magnam asperiores dicta accusamus inventore dolore officia sapiente, corporis perspiciatis numquam assumenda provident voluptatum, natus dolor. Ducimus saepe quod debitis repellat.
            Corrupti minus, earum sapiente quo quod similique fuga asperiores sit molestias autem velit deleniti rem culpa commodi maxime tempora, quae debitis. Est iste eaque, accusamus harum laborum eligendi ab dolore!
          </v-col>
          <v-col>
            <v-img
              class="img--p2"
              src="../assets/4H4.png"
              width="200px"
            ></v-img>
          </v-col>
        </v-row>
            </b-step-item>
          
           <b-step-item step="5" label="Consulta asignatura sin vacantes" :clickable="isStepsClickable">
                <v-row>
          
          <v-col>
            <a href="https://www.ssa.ingenieria.unam.mx/"><h1>Paso 6</h1></a>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolorum magnam asperiores dicta accusamus inventore dolore officia sapiente, corporis perspiciatis numquam assumenda provident voluptatum, natus dolor. Ducimus saepe quod debitis repellat.
            Corrupti minus, earum sapiente quo quod similique fuga asperiores sit molestias autem velit deleniti rem culpa commodi maxime tempora, quae debitis. Est iste eaque, accusamus harum laborum eligendi ab dolore!
          </v-col>
          <v-col>
            <v-img
              class="img--p2"
              src="../assets/5H5.png"
              width="200px"
            ></v-img>
          </v-col>
        </v-row>
            </b-step-item>

            <b-step-item :step="showSocial ? '6' : '5'" label="Consulta de inscripción en el SIAE" :clickable="isStepsClickable" disabled>
                <v-row>
          
          <v-col>
            <a href="https://www.ssa.ingenieria.unam.mx/"><h1>Paso 13</h1></a>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolorum magnam asperiores dicta accusamus inventore dolore officia sapiente, corporis perspiciatis numquam assumenda provident voluptatum, natus dolor. Ducimus saepe quod debitis repellat.
            Corrupti minus, earum sapiente quo quod similique fuga asperiores sit molestias autem velit deleniti rem culpa commodi maxime tempora, quae debitis. Est iste eaque, accusamus harum laborum eligendi ab dolore!
          </v-col>
          <v-col>
            <v-img
              class="img--p2"
              src="../assets/6H6.png"
              width="200px"
            ></v-img>
          </v-col>
        </v-row>
            </b-step-item>

            <template
                v-if="customNavigation"
                #navigation="{previous, next}">
                <b-button
                    outlined
                    type="is-danger"
                    icon-pack="fas"
                    icon-left="backward"
                    :disabled="previous.disabled"
                    @click.prevent="previous.action">
                    Previous
                </b-button>
                <b-button
                    outlined
                    type="is-success"
                    icon-pack="fas"
                    icon-right="forward"
                    :disabled="next.disabled"
                    @click.prevent="next.action">
                    Next
                </b-button>
            </template>
        </b-steps>
    </section>
</template>

<script>
    export default {
        data() {
            return {
                activeStep: 0,

                showSocial: false,
                isAnimated: true,
                isRounded: true,
                isStepsClickable: false,

                hasNavigation: true,
                customNavigation: false,
                isProfileSuccess: false,

                prevIcon: 'chevron-left',
                nextIcon: 'chevron-right',
                labelPosition: 'bottom',
                mobileMode: 'minimalist'
            }
        }
    }
</script>
<style scoped>
.img--p2{
  padding: 3em;
  margin: auto;
}
</style>