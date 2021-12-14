<template>
    <section id="feedback">
        <div id="feedback-title">
            <h5>CUSTOMER TESTIMONIALS</h5>
            <h1>Trusted Feedback</h1>  
            <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Alias delectus sapiente sint faciuptate accusamus, nihil possiitia voluptatibus.</p>
        </div>

        <div id="feedback-cards">
            <div>
                <img src="../assets/img/logo-1.png" alt="">
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Enim necessitatibus incidunt error repellat dignissimos optio hic, repellendus quibusdam. Ducimus saepe placeat tempora eveniet explicabo sequi sunt quas architecto expedita recusandae!</p>
            </div>

            <div>
                <img src="../assets/img/logo-2.png" alt="">
                <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Qui iure quibusdam, esse labore eius iste, corrupti voluptatibus dolorem praesentium voluptates aliquid a animi perferendis, unde temporibus assumenda vitae minus? Unde!</p>
            </div>

            <div>
                <img src="../assets/img/logo-3.png" alt="">
                <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Obcaecati rem, voluptatum totam maiores, ex nam quia nobis quaerat pariatur dolorum neque expedita tempora, nesciunt distinctio doloribus ut facere delectus. Quia?</p>
            </div>
        </div>
    </section>    
</template>

<script>
export default {
  name: 'Feedback',
}
</script>

<style scoped lang="scss">
#feedback {
    background-color: #eef4ed;
    #feedback-title {
        padding-top: 100px;
        text-align: center;
        margin-bottom: 50px;
    }
    #feedback-cards {
        padding-bottom: 100px;
        div {
            display: inline-block;
            width: 350px;
            background-color: #fff;
            border-radius: 10px;
            margin: 20px;
            padding: 20px;
        }
    }
}
</style>