<template>
  <main>
      <TheCompany/>

      <ActionsProjects :itemsActionsProjects="itemsActionsProjects" :cardsActionsProjects="cardsActionsProjects"/>

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
  },
  data() {
    return {
      itemsActionsProjects: [
        {
          name: "ALL"
        },

        {
          name: "ISTITUTIONAL"
        },

        {
          name: "SOCIAL"
        },

        {
          name: "EVENTS"
        },

        {
          name: "INNOVATION"
        },

        {
          name: "ENVIRONMENT"
        },

        {
          name: "TECHNOLOGY"
        }
      ],
      cardsActionsProjects: [
        {
          img: "../assets/img/project-1.jpg",
          title: "Academic professional program in social media"
        },

        {
          img: "../assets/img/project-2.jpg",
          title: "President's speech at the annual meeting"
        },

        {
          img: "../assets/img/project-3.jpg",
          title: "International business trip in Shanghai"
        },

        {
          img: "../assets/img/project-4.jpg",
          title: "Technology workshop with education theme"
        },

        {
          img: "../assets/img/project-5.jpg",
          title: "Donation of clothes and food to the partner NGO"
        },

        {
          img: "../assets/img/project-6.jpg",
          title: "Confraternization of the procurementteam"
        },
      ]
    }
  }
}
</script>

<style scoped lang="scss">

</style>