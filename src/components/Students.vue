<template>
    <div>
        <div v-bind:key="Student.Studentid" v-for="Student in Student1">
            <StudentDetail v-bind:Student="Student" /> <br/>
        </div>
            
    </div>
</template>

<script>
import StudentDetail from './StudentDetail.vue'
export default {
  name: 'Students',
  components: {
    StudentDetail,
  },
  props:["Student1"]
}
</script>

<style>
 
</style>