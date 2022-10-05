<template>
  <h1>Lifecycle hooks</h1>
</template>

<script>
// import da composition API
import { onMounted } from '@vue/runtime-core'

  // options API
  // export default {
  //   mounted() {
  //     console.log('Foi montado options API');
  //   }
  // }

  // Composition API
  export default {
    setup() {
      onMounted(() => {
        console.log('Foi montado composition API')
      })
    }
  }
</script>

<style scoped>

</style>