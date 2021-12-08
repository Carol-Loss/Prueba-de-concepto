<template>
    <section>

        <b-steps
            :position="position"
            :label-position="labelPosition"
            :size="size"
            type="is-info is-light"
            vertical>
            <b-step-item label="Contar con contraseña personalizada" step="0">
                <v-row>
                    <v-col>
                        <v-img
                        class="img--p2"
                        src="../assets/a5.png"
                        width="200px"
                        ></v-img>
                    </v-col>
                    <v-col>
                        <a href="https://www.ssa.ingenieria.unam.mx/"><h1>Paso 0</h1></a>
                        Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolorum magnam asperiores dicta accusamus inventore dolore officia sapiente, corporis perspiciatis numquam assumenda provident voluptatum, natus dolor. Ducimus saepe quod debitis repellat.
                        Corrupti minus, earum sapiente quo quod similique fuga asperiores sit molestias autem velit deleniti rem culpa commodi maxime tempora, quae debitis. Est iste eaque, accusamus harum laborum eligendi ab dolore!
                    </v-col>
                </v-row>
            </b-step-item>

            <b-step-item label="Actualización de datos y optativas DIMEI" step="1">
               <v-row>
                    <v-col>
                        <v-img
                        class="img--p2"
                        src="../assets/a4.png"
                        width="200px"
                        ></v-img>
                    </v-col>
                    <v-col>
                        <a href="https://www.ssa.ingenieria.unam.mx/"><h1>Paso 2</h1></a>
                        Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolorum magnam asperiores dicta accusamus inventore dolore officia sapiente, corporis perspiciatis numquam assumenda provident voluptatum, natus dolor. Ducimus saepe quod debitis repellat.
                        Corrupti minus, earum sapiente quo quod similique fuga asperiores sit molestias autem velit deleniti rem culpa commodi maxime tempora, quae debitis. Est iste eaque, accusamus harum laborum eligendi ab dolore!
                    </v-col>
                </v-row>
            </b-step-item>

            <b-step-item label="Publicación de grupos y horarios programados" step="2">
               <v-row>
                    <v-col>
                        <v-img
                        class="img--p2"
                        src="../assets/a3.png"
                        width="200px"
                        ></v-img>
                    </v-col>
                    <v-col>
                        <a href="https://www.ssa.ingenieria.unam.mx/"><h1>Paso 3</h1></a>
                        Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolorum magnam asperiores dicta accusamus inventore dolore officia sapiente, corporis perspiciatis numquam assumenda provident voluptatum, natus dolor. Ducimus saepe quod debitis repellat.
                        Corrupti minus, earum sapiente quo quod similique fuga asperiores sit molestias autem velit deleniti rem culpa commodi maxime tempora, quae debitis. Est iste eaque, accusamus harum laborum eligendi ab dolore!
                    </v-col>
                </v-row>
            </b-step-item>
            <b-step-item label="Publicación de grupos y horarios programados" step="3">
               <v-row>
                    <v-col>
                        <v-img
                        class="img--p2"
                        src="../assets/a4.png"
                        width="200px"
                        ></v-img>
                    </v-col>
                    <v-col>
                        <a href="https://www.ssa.ingenieria.unam.mx/"><h1>Paso 3</h1></a>
                        Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolorum magnam asperiores dicta accusamus inventore dolore officia sapiente, corporis perspiciatis numquam assumenda provident voluptatum, natus dolor. Ducimus saepe quod debitis repellat.
                        Corrupti minus, earum sapiente quo quod similique fuga asperiores sit molestias autem velit deleniti rem culpa commodi maxime tempora, quae debitis. Est iste eaque, accusamus harum laborum eligendi ab dolore!
                    </v-col>
                </v-row>
            </b-step-item>
            <b-step-item label="Consulta de número de inscripción" step="4">
               <v-row>
                    <v-col>
                        <v-img
                        class="img--p2"
                        src="../assets/a5.png"
                        width="200px"
                        ></v-img>
                    </v-col>
                    <v-col>
                        <a href="https://www.ssa.ingenieria.unam.mx/"><h1>Paso 4</h1></a>
                        Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolorum magnam asperiores dicta accusamus inventore dolore officia sapiente, corporis perspiciatis numquam assumenda provident voluptatum, natus dolor. Ducimus saepe quod debitis repellat.
                        Corrupti minus, earum sapiente quo quod similique fuga asperiores sit molestias autem velit deleniti rem culpa commodi maxime tempora, quae debitis. Est iste eaque, accusamus harum laborum eligendi ab dolore!
                    </v-col>
                </v-row>
            </b-step-item>
            <b-step-item label="Inscripción por internet" step="5">
               <v-row>
                    <v-col>
                        <v-img
                        class="img--p2"
                        src="../assets/a6.png"
                        width="200px"
                        ></v-img>
                    </v-col>
                    <v-col>
                        <a href="https://www.ssa.ingenieria.unam.mx/"><h1>Paso 5</h1></a>
                        Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolorum magnam asperiores dicta accusamus inventore dolore officia sapiente, corporis perspiciatis numquam assumenda provident voluptatum, natus dolor. Ducimus saepe quod debitis repellat.
                        Corrupti minus, earum sapiente quo quod similique fuga asperiores sit molestias autem velit deleniti rem culpa commodi maxime tempora, quae debitis. Est iste eaque, accusamus harum laborum eligendi ab dolore!
                    </v-col>
                </v-row>
            </b-step-item>
            <!--último-->
            <b-step-item label="Consulta de inscripción en el SIAE" step="6" disabled>
               <v-row>
                    <v-col>
                        <v-img
                        class="img--p2"
                        src="../assets/a7.png"
                        width="200px"
                        ></v-img>
                    </v-col>
                    <v-col>
                        <a href="https://www.ssa.ingenieria.unam.mx/"><h1>Paso 13</h1></a>
                        Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolorum magnam asperiores dicta accusamus inventore dolore officia sapiente, corporis perspiciatis numquam assumenda provident voluptatum, natus dolor. Ducimus saepe quod debitis repellat.
                        Corrupti minus, earum sapiente quo quod similique fuga asperiores sit molestias autem velit deleniti rem culpa commodi maxime tempora, quae debitis. Est iste eaque, accusamus harum laborum eligendi ab dolore!
                    </v-col>
                </v-row>
            </b-step-item>
        </b-steps>
    </section>
</template>

<script>
    export default {
        data() {
            return {
                labelPosition: 'bottom',
                position: null,
                size: null,
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