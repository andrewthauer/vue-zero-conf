<template>
  <h1>{{ title }}</h1>
</template>

<script>
import Vue from 'vue'

export default Vue.extend({
  name: 'app',
  props: {
    person: Stringss
  },
  data() {
  	return { title: 'Hello Vue TS!' }
  },
})
</script>
