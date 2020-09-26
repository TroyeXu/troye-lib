<script>
import Vue from 'vue'
import { TroyelibSample } from '@/entry'

export default Vue.extend({
  name: 'ServeDev',
  components: {
    TroyelibSample,
  },
})
</script>

<template>
  <div id="app">
    <troyelib-sample />
  </div>
</template>
