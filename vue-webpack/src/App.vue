<template>
  <h1>{{ title }}</h1>
</template>

<script>
import Vue from 'vue'

export default Vue.extend({
  name: 'app',
  data(){
  	return { title: 'Hello Vue!' }
  },
})
</script>
