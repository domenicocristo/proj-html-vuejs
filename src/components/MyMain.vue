<template>
  <main>
      <TheCompany/>

      <ActionsProjects/>

      <Management/>
  </main>
</template>

<script>
import TheCompany from '../components/TheCompany.vue'
import ActionsProjects from '../components/ActionsProjects.vue'
import Management from '../components/Management.vue'

export default {
  name: 'MyMain',
  components: {
      TheCompany,
      ActionsProjects,
      Management,
  }
}
</script>

<style scoped lang="scss">

</style>