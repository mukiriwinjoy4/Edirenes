<template>
    <div id="homepage">
      <v-container>
        <v-layout column>
          <v-carousel>
            <v-carousel-item
              src="/ethan-weil-fiOU98HM2Uc-unsplash.jpg"
              cover
            ></v-carousel-item>
  
            <v-carousel-item
              src="/nathalie-jolie-IBekPHDDFxQ-unsplash.jpg"
              cover
            ></v-carousel-item>
  
            <v-carousel-item
              src="/nick-fewings-IkiUJ4XNC10-unsplash.jpg"
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
                  title="Product Type"
                  
                  text="Message"
                ></v-card>
  
                <div class="mt-4 text-subtitle-2">With slots</div>
  
                <v-card width="400">
                  <template v-slot:title> County </template>
  
                    
                  <template v-slot:text
                    ><Address>home address</Address>
                  </template>
                </v-card>
  
                <div class="mt-4 text-subtitle-2">With markup</div>
  
                <v-card width="400">
                  <v-card-item>
                    <v-card-title>Phone Number</v-card-title>
                      
                  </v-card-item>
  
                  <v-card-text>
                    Submit
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
  