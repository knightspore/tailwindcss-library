<template>
  <div id="app">
    <h2 class="text-sm font-black my-2 text-center">ACCOMMODATION CARDS</h2>
    <div class="w-10/12 flex flex-col lg:flex-row justify-center m-auto">
    <AccommodationCard
      title="Kommetjie"
      rating="4.2"
      description="Tucked away in the quietest corner of the peninsula, an hour from the city center. " 
      img="https://q-cf.bstatic.com/images/hotel/max1024x768/143/143105271.jpg"/>

    <AccommodationCard
      title="Scarborough"
      rating="3.8"
      description="Secluded and surrounded by endless horizons, lapping waves and stunning sunsets." 
      img="https://a0.muscache.com/im/pictures/f919f8ac-b3c3-4ef4-a398-789778b0bf86.jpg"/>

    <AccommodationCard 
      title="Elands Bay"
      rating="4.0"
      description="One for the surfers - a crayfishing town with the best waves between Cape Town & Namibia."
      img="https://www.forkwest.co.za/media/img/mg/shutterstock_31491526.jpg"/>

    </div>
  </div>
</template>

<script>
import AccommodationCard from './components/cards/AccommodationCard.vue'

export default {
  name: 'App',
  components: {
    AccommodationCard
  }
}
</script>

<style src="./index.css">
</style>