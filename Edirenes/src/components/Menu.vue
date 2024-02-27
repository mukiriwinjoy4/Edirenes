<template>
    <div id="homepage">
      <v-container>
        <v-layout column>
          <v-carousel>
                <v-carousel-item
                src="/vladzimir-nikitsin-wY1GIiiTRak-unsplash.jpg"
                cover
                ></v-carousel-item>
  
                <v-carousel-item
                src="/julian-ackroyd-DjN9dJH44d4-unsplash.jpg"
                cover
                ></v-carousel-item>
    
                <v-carousel-item
                src="/oriol-portell-AbwqpFnBDms-unsplash.jpg"
                cover
                ></v-carousel-item>
          </v-carousel>
        </v-layout>
        <v-layout>
          <v-container>
            <v-row align="center" justify="center">
              <div class="d-flex align-center flex-column">
               
                    <v-card width="400">
                  <v-card-item>
                    <v-card-title>{{ componentTitle }}</v-card-title>
                    </v-card-item>
  
                    <v-card-text>
                        <v-list
                        :items="fruit"
                        item-title="fruit_seedlings"
                        item-value="id"
                        ></v-list>
                    </v-card-text>
                </v-card>
              </div>
            </v-row>
          </v-container>
        </v-layout>
      </v-container>
    </div>
  </template>
  <script>
  export default {
    // Properties returned from data() become reactive state
    // and will be exposed on `this`.
    data() {
      return {
        fruit:[
            {
                id: 1,
                fruit: 'Hass Avocadoes'
           },
            {
                id: 2,
                fruit: 'pomegranates'
            },
            {
                id: 3,
                fruit: 'Yellow Passion'
           },
            {
                id: 4,
                fruit: 'Tommy'
            },
            {
                id: 5,
                fruit: 'Kent'
            },
            {
                id: 6,
                fruit: 'Apple Mangoes'
            },
            {
                id: 7,
                fruit: 'Tangerine'
            },
            {
                id: 8,
                fruit: 'Washington'
            },
            {
                id: 9,
                fruit: 'Pixie Oranges'
            },
            {
                id: 10,
                fruit: 'Fuerte'
            },
          ],
        componentTitle: 'Fruit Seedlings'
      }
    },
  
    // Methods are functions that mutate state and trigger updates.
    // They can be bound as event handlers in templates.
    methods: {
      increment() {
        this.count++
      }
    },
  
    // Lifecycle hooks are called at different stages
    // of a component's lifecycle.
    // This function will be called when the component is mounted.
    mounted() {
    console.log(this.fruit)
    }
  }
  </script>