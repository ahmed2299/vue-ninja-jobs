<template>
  <h1>jobs</h1>
  <div v-for="job in jobs" :key="job.id">
    <h2>{{job.title}}</h2>
  </div>
</template>

<script>
export default {
  data(){
    return{
      jobs:[
        {title:'ninja ux',id:1,details:'lorem'},
        {title:'ninja web',id:2,details:'lorem'},
        {title:'ninja vue',id:3,details:'lorem'},

      ]
    }
  }
}
</script>