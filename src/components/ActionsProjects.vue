<template>
<section id="actions-projects">
    <div>
        <h5>WE DO MORE FOR EVERYONE</h5>
        <h1>Actions & Projects</h1>  
    </div>

    <ul>
        <li>
            <h4>ALL</h4> 
            </li>
        <li>
            <h4>ISTITUTTIONAL</h4>
        </li>
        <li>
            <h4>SOCIAL</h4>
        </li>
        <li>
            <h4>EVENTS</h4>
        </li>
        <li>
            <h4>INNOVATION</h4>
        </li>
        <li>
            <h4>ENVIRORMENT</h4>
        </li>
        <li>
            <h4>TECHNOLOGY</h4>
        </li>
    </ul>

    <div id="actions-projects-cards">
        <div class="actions-projects-card">
            <img src="../assets/img/project-1.jpg" alt="">
            <h1>Academic professional program in social media</h1>
        </div>

        <div class="actions-projects-card">
            <img src="../assets/img/project-2.jpg" alt="">
            <h1>President's speech at the annual meeting</h1>
        </div>

        <div class="actions-projects-card">
            <img src="../assets/img/project-3.jpg" alt="">
            <h1>International business trip in Shanghai</h1>
        </div>

        <div class="actions-projects-card">
            <img src="../assets/img/project-4.jpg" alt="">
            <h1>Technology workshop with education theme</h1>
        </div>

        <div class="actions-projects-card">
            <img src="../assets/img/project-5.jpg" alt="">
            <h1>Donation of clothes and food to the partner NGO</h1>
        </div>

        <div class="actions-projects-card">
            <img src="../assets/img/project-6.jpg" alt="">
            <h1>Confraternization of the procurementteam</h1>
        </div>
    </div>
</section>
</template>

<script>
export default {
  name: 'ActionsProjects',
}
</script>

<style scoped lang="scss">
#actions-projects {
    background-color: #111118;
    color: #fff;
    padding-top: 50px;
    padding-bottom: 100px;
    ul {
        list-style-type: none;
    }
    li {
        display: inline-block;
        margin: 10px;
        cursor: pointer;
    }
    .actions-projects-card {
        display: inline-block;
        width: calc(100% / 4);
        position: relative;
        margin: 20px;
        img {
            width: 100%;
            z-index: 1;
            border-radius: 10px;
            filter: opacity(0.5);
        }
        h1 {
            position: absolute;
            bottom: 20px; 
            z-index: 2;
        }
    }
}
</style>