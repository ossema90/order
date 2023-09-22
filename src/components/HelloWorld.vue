<template>
  <v-card class="card-component " width="450">

    <img :src="backgroundImg" alt="">

    <div class="mx-4 my-8">
      <h1>Order Summary</h1>
    </div>


    <div class="pa-4" width="200">
      <p class="text-center"> You can now listen to millions of songs , audiobooks, and podcasts on any
        device
        anywhere
        you like!</p>
    </div>

    <div class="d-flex jutify-center align-center ma-2 ">
      <div> <img :src="iconImg" alt=""></div>
      <div>
        <div class="ma-8">
          <h4>Annual Plan</h4>
          <p>$59.99/year</p>
        </div>
      </div>
      <div class="ml-16"><a href="" color="" style="">Change</a></div>
    </div>
    <div class="ma-2 "> <v-btn flat color="#3829e0" class="payment-btn"> Proceed to Payment </v-btn></div>
    <div class="ma-2"> <v-btn flat>Cancel order </v-btn></div>

  </v-card>
</template>


<script>
export default {

  data() {
    return {
      backgroundImg: require('../assets/illustration-hero.svg'),
      iconImg: require('../assets/icon-music.svg'),
    }
  }
}
</script>


<style scoped>
.card-component {
  border-radius: 1.5rem;
  display: grid;
  place-items: center;

}

.payment-btn {
  width: 15rem;
  height: 2.5rem;
}
</style>