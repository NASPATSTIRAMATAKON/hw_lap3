<template>
    <div class="Student-Detail">
       <h1>{{Student.title}}</h1><br/>

       <div style="width:100%;text-align:middle;"><br/>
            <img style="float: middle; padding: 15px" width="150px" v-bind:src="Student.picture" />
            <div style="padding:20px">
                <b>studentId:</b> {{Student.studentId}} <br/>
                <br /><b>FirstName:</b> {{Student.FirstName}} <br/>
                <br /><b>LastName:</b> {{Student.LastName}} <br/>
                <br /><b>weight:</b> {{Student.weight}} <br/>
                <br /><b>height:</b> {{Student.height}} <br/>
            </div>
       </div><br/>
    </div>
</template>

<script>
export default {
  name: 'StudentDetail',
  components: {
   
  },
  props:["Student"]
}
</script>

<style>
  .Student-Detail{
       background: rgb(109, 139, 134);
       padding: 20px;
       border-bottom: indigo 1px;
   }
</style>