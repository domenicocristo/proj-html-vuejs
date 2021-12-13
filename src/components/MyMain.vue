<template>
  <main>
      <TheCompany/>

      <ActionsProjects/>
  </main>
</template>

<script>
import TheCompany from '../components/TheCompany.vue'
import ActionsProjects from '../components/ActionsProjects.vue'

export default {
  name: 'MyMain',
  components: {
      TheCompany,
      ActionsProjects,
  }
}
</script>

<style scoped lang="scss">

</style>