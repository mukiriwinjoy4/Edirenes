<template>
    <v-row>
      <v-col
        v-for="n in 6"
        :key="n"
        class="d-flex child-flex"
        cols="4"
      >
        <v-img
          :src="`/jen-uppend-3mS_VX70noM-unsplash.jpgimage`"
          :lazy-src="`/vladzimir-nikitsin-wY1GIiiTRak-unsplash.jpgimage`"
          aspect-ratio="1"
          cover
          class="bg-grey-lighten-2"
        >
          <template v-slot:placeholder>
            <v-row
              class="fill-height ma-0"
              align="center"
              justify="center"
            >
              <v-progress-circular
                indeterminate
                color="grey-lighten-5"
              ></v-progress-circular>
            </v-row>
          </template>
        </v-img>
      </v-col>
    </v-row>
  </template>