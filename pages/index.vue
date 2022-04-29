<template>
  <div>
    <Navbar />
    <Slide /> 
    <News v-for="cardInfo in newsInfo"
     :key="cardInfo.id" 
     :cardsSection="cardInfo"/> 
  </div>
</template>

<script>
import {newsCardSections} from "@/assets/newsdata.js"
export default {
  data() {
    return {
      newsInfo: newsCardSections
    }
  }
}
</script>
