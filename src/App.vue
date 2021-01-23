<template>
  <div id="app">
    <Students v-bind:Student1="Students" />
  </div>
</template>

<script>
import Students from './components/Students.vue'

export default {
  name: 'App',
  components: {
    Students,
  },
  data(){
    return{
      Students: [
        {
   "studentId": "614234012",
   "FirstName": "์Naspat",
   "LastName": "Stiramitakon",
   "weight": 63,
   "height": 162,
   "picture": "https://raw.githubusercontent.com/NASPATSTIRAMATAKON/naspat/main/dyo.jpg",
 },
 {
   "studentId": "614234005",
   "FirstName": "Duangruthai",
   "LastName": "Anuto",
   "weight": 63,
   "height": 160,
   "picture": "https://raw.githubusercontent.com/NASPATSTIRAMATAKON/naspat/main/jwew.jpg",
 },
 {
   "studentId": "614234006",
   "FirstName": "Sineenart",
   "LastName": "Songsen",
   "weight": 52,
   "height": 156,
   "picture": "https://raw.githubusercontent.com/NASPATSTIRAMATAKON/naspat/main/kik.jpg",
 },
 {
   "studentId": "613234010",
   "FirstName": "Nur-ateekah",
   "LastName": "Salaeh",
   "weight": 70,
   "height": 152,
   "picture": "https://raw.githubusercontent.com/NASPATSTIRAMATAKON/naspat/main/kah.jpg",
 },
 {
   "studentId": "614234013",
   "FirstName": "Priyaphat",
   "LastName": "Charoenrit",
   "weight": 66,
   "height": 162,
   "picture": "https://raw.githubusercontent.com/NASPATSTIRAMATAKON/naspat/main/pari.jpg",
 }
      ]
    }
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
