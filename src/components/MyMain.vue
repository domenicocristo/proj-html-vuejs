<template>
  <main>
      <TheCompany/>

      <ActionsProjects/>

      <Management/>

      <Feedback/>
  </main>
</template>

<script>
import TheCompany from '../components/TheCompany.vue'
import ActionsProjects from '../components/ActionsProjects.vue'
import Management from '../components/Management.vue'
import Feedback from '../components/Feedback.vue'

export default {
  name: 'MyMain',
  components: {
      TheCompany,
      ActionsProjects,
      Management,
      Feedback,
  }
}
</script>

<style scoped lang="scss">

</style>