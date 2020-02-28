<template>
  <CtCard title="Programación" width="600" class="mx-auto">
    <v-row dense>
      <v-col cols="12" class="mt-5">
        <v-card color="primary" dark>
          <v-card-title class="headline" v-html="'Gestor de tareas open source'" @click="$router.push({ path: '/programacion-gestor-tareas' })" style="cursor: pointer;" />
          <v-card-subtitle v-html="(new Date('2020-02-28 07:00:00')).toLocaleString()" />
          <v-container>
            <p>
              He desarrollado un gestor de tareas open source. Lo tenéis disponible para vuestro uso.
            </p>
            <v-row dense>
              <v-spacer />
              <CtBtn to="/programacion-gestor-tareas">
                Leer más
              </CtBtn>
            </v-row>
          </v-container>
        </v-card>
      </v-col>
    </v-row>
  </CtCard>
</template>

<script>
import CtBtn from "../components/CtBtn";
export default {
  components: {CtBtn}
}
</script>
