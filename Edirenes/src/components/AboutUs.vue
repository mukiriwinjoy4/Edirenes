<template>
  <div id="homepage">
    <v-container>
      <v-layout column>
        <v-carousel>
          <v-carousel-item
            src="public/cesar-guel-wds9ue_gops-unsplash.jpg"
            cover
          ></v-carousel-item>

          <v-carousel-item 
          src="public/jen-uppend-3mS_VX70noM-unsplash.jpg" 
          cover
          ></v-carousel-item>

          <v-carousel-item
            src="public/jen-uppend-T4FZYPixWfM-unsplash.jpg"
            cover
          ></v-carousel-item>
        </v-carousel>
      </v-layout>
      <v-layout>
        <v-container>
          <v-row align="center" justify="center">
            <div class="d-flex align-center flex-column">
              
              
              <v-card width="400">
                <v-card-text>
                  We sell grafted fruit seedlings, provide quality hardened
                  fruit seedlings and offer consultancy and extension services.
                  We are dedicated to supplying Quality organic produce to our
                  customers by building strong, lasting relationship with
                  growers who are stewards of the land and their communities.
                  Growers who pack in the Edirene's Fruit Seedlings meet our
                  strict criteria for excellence and consistency.
                </v-card-text>
              </v-card>
            </div>
          </v-row>
        </v-container>
      </v-layout>
    </v-container>
  </div>
</template>
<script setup>
const variants = ["elevated", "flat", "tonal", "outlined"];
</script>
