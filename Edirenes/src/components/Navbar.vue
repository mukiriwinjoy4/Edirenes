<script>
// import HomePage from "HomePage.vue"
// import AboutUs from "AboutUs.vue"
// import Gallery from "Gallery.vue"
// import ContactUs from "ContactUs.vue"
// import Menu from "Menu.vue"
// import HowtoOrder from "HowtoOrder.vue"
</script>


<template>
    <v-app-bar color="blue">
        <div>
            <v-btn to = "/" color = "white" dark >Home</v-btn>
        </div>       
         <div>
            <v-btn to = "/aboutus" color = "white" dark >About Us</v-btn>
        </div>
        <div>
            <v-btn to = "/gallery" color = "white" dark >Gallery</v-btn>
        </div>
        <div>
            <v-btn to = "/contactus" color = "white" dark >Contact Us</v-btn>
        </div>
        <div>
            <v-btn to = "/menu" color = "white" dark >Menu</v-btn>
        </div>
        <div>
            <v-btn to = "/howtoorder" color = "white" dark >How To Order</v-btn>
        </div>
     </v-app-bar>
</template>