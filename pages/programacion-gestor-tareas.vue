<template>
  <CtCard title="Gestor de tareas" width="600" class="mx-auto">
    <v-row dense>
      <p>
        El <b>gestor de tareas</b> es un aplicativo open source que permite a tus usuarios reservar fechas en un horario pre establecido. En formato de plataforma web.
      </p>
      <p>
        Consta de dos proyectos, una api y un frontal.
      </p>
      <ul>
        <li>
          La api está hecha con Laravel 6.2 y tiene tres principales puntos fuertes. Implementa una autenticación con Airlock, tiene una base con la que gestionar entidades con muy poco código y sigue el principio DDD (Driver Domain Design).<br>
          <v-row dense>
            <v-spacer />
            <CtBtn type="text" href="https://github.com/vgrdominik/taskReservationApi" target="_blank">
              Ir al repositorio
            </CtBtn>
            <v-spacer />
          </v-row>
        </li>
        <li>
          El frontal está hecho con Vue, NuxtJS, Vuetify y los iconos font awesome junto con material icons.<br>
          <v-row dense>
            <v-spacer />
            <CtBtn type="text" href="https://github.com/vgrdominik/taskReservationFrontend" target="_blank">
              Ir al repositorio
            </CtBtn>
            <v-spacer />
          </v-row>
        </li>
      </ul>
      <p>
        En la página principal de cada repositorio del <b>gestor de tareas</b> hay un README con todo el contenido necesario para instalar y si lo deseas contribuir en el proyecto.
      </p>
      <CtBtn color="primary" to="/programacion" class="mt-4 mx-auto">
        Volver a programación
      </CtBtn>
    </v-row>
  </CtCard>
</template>

<script>
  export default {
  }
</script>
