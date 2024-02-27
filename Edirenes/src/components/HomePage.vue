<template>
    <div id="homepage">
      <v-container>
        <v-layout column>
          <v-carousel>
            <v-img
              src="public/Screenshot (5).png"
              cover
            ></v-img>
              
          </v-carousel>
        </v-layout>
        <v-layout>
          <v-container>
            <v-row align="center" justify="center">
              <div class="d-flex align-center flex-column">
                <div class="text-subtitle-2">With props</div>
  
                <v-card
                  width="400"
                  title="Organic Fruit Farming"
                  
                  text="Yet, most farmers struggle to access the high-quality inputs or the advice they need to thrive. Edirene's Fruit Seedling is radically changing that by blending franchising efficiency with a commitment to generating value for smallholder farmers, their families and communities.As a company we have been involved in propagation and selling of quality fruit tree seedling for several years.
                  Fruit seedling has been our speciliazation because we understood earky how important they are to our society and for commercial purposes if they are taken of. We have various types of seedlings in our nurseries."
                ></v-card>
  
                
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
  