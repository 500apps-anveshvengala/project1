<template>
  <div>
  <h1>{{ title }}</h1>
  <p>{{ greeting() }}</p>
  </div>
</template>

<script>
export default {
  data(){
    return {
      title:'Hello Anvesh'
    }
  },
  methods:{
    greeting:function(){
      return 'Hellooooooooo';
    }
  }
}
  
  
</script>

