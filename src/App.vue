<template>
  <div id="">
    <h1>{{title}}</h1>
    <p>{{greeting()}}</p>
    <router-view/>
  </div>
</template>

<script>
export default {
  data(){
    return {
      title:'yourfirst vue file'
      }

},
  methods: {
    greeting:function(){
      return 'heeyy';
    }
    }
    }
</script>



</style>
