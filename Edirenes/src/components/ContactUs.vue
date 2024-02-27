<template>
    <div id="homepage">
      <v-container>
        <v-layout column>
          <v-carousel>
            <v-carousel-item
              src="/charlotte-harrison-RcDJZCVRrQ4-unsplash.jpg"
              cover
            ></v-carousel-item>
  
            <v-carousel-item
              src="/amirul-islam-vUlr2F01z-o-unsplash.jpg"
              cover
            ></v-carousel-item>
  
            <v-carousel-item
              src="/rodion-kutsaiev-HJcb2t7rmJg-unsplash.jpg"
              cover
            ></v-carousel-item>
          </v-carousel>
        </v-layout>
        <v-layout>
          <v-container>
            <v-row align="center" justify="center">
              <div class="d-flex align-center flex-column">
                <div class="text-subtitle-2">With props</div>
  
                <v-card
                  width="400"
                  title="Want To Know More?"
                  
                  text="Reach Out To Us Through!"
                ></v-card>
  
                <div class="mt-4 text-subtitle-2">With slots</div>
  
                <v-card width="400">
                  <template v-slot:title> Email </template>
  
                    
                  <template v-slot:text
                    >Edirenesseedlings@gmail.com
                  </template>
                </v-card>
  
                <div class="mt-4 text-subtitle-2">With markup</div>
  
                <v-card width="400">
                  <v-card-item>
                    <v-card-title>WhatsApp/Message</v-card-title>
                      
                  </v-card-item>
  
                  <v-card-text>
                    0716194355
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
  