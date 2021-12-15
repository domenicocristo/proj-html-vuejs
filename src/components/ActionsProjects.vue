<template>
<section id="actions-projects">
    <div>
        <h5>WE DO MORE FOR EVERYONE</h5>
        <h1>Actions & <span id="title-design">Projects</span></h1>  
    </div>

    <ul>
        <li v-for="item, i in itemsActionsProjects" :key="i">{{item.name}}</li>
    </ul>

    <div id="actions-projects-cards">
        <!-- <div v-for="card, i in cardsActionsProjects" :key="i" class="actions-projects-card">
            <img :src="card.img" alt="">
            <h2>{{card.title}}</h2>
        </div> -->
        <div class="actions-projects-card">
            <img src="../assets/img/project-1.jpg" alt="">
            <h2>Academic professional program in social media</h2>
        </div>

        <div class="actions-projects-card">
            <img src="../assets/img/project-2.jpg" alt="">
            <h2>President's speech at the annual meeting</h2>
        </div>

        <div class="actions-projects-card">
            <img src="../assets/img/project-3.jpg" alt="">
            <h2>International business trip in Shanghai</h2>
        </div>

        <div class="actions-projects-card">
            <img src="../assets/img/project-4.jpg" alt="">
            <h2>Technology workshop with education theme</h2>
        </div>

        <div class="actions-projects-card">
            <img src="../assets/img/project-5.jpg" alt="">
            <h2>Donation of clothes and food to the partner NGO</h2>
        </div>

        <div class="actions-projects-card">
            <img src="../assets/img/project-6.jpg" alt="">
            <h2>Confraternization of the procurementteam</h2>
        </div>
    </div>
</section>
</template>

<script>
export default {
  name: 'ActionsProjects',
  props: {
      itemsActionsProjects: Array,
      cardsActionsProjects: Array,
  }
}
</script>

<style scoped lang="scss">
#actions-projects {
    text-align: center;
    background-color: #111118;
    color: #fff;
    padding-top: 70px;
    padding-bottom: 100px;
    h5 {
        color: #05a5a6;
        margin-bottom: 15px;
    }
    h1 {
        font-size: 40px;
        margin-bottom: 30px;
    }
    #title-design {
        background-color: #0e262d;
        padding: 1px 10px 1px 10px;
        border-radius: 5px;
    }
    ul {
        list-style-type: none;
    }
    li {
        display: inline-block;
        margin: 20px;
        cursor: pointer;
    }
    li:hover {
        color: #048283;
    }
    .actions-projects-card {
        display: inline-block;
        width: calc(100% / 4);
        position: relative;
        margin: 20px;
        cursor: pointer;
        img {
            width: 100%;
            z-index: 1;
            border-radius: 10px;
            filter: opacity(0.5);
        }
        img:hover {
            border: 3px solid #fff;
        }
        h2 {
            position: absolute;
            bottom: 20px; 
            z-index: 2;
        }
    }
}
</style>