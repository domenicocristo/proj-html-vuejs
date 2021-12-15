<template>
    <section id="management">
        <div id="management-title">
            <h5>HOW IT WORKS IN PRACTICE</h5>
            <h1><span id="title-design">Process</span> Management</h1>  
            <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Alias delectus sapiente sint faciuptate accusamus, nihil possiitia voluptatibus.</p>
        </div>

        <div id="management-cards">
            <div>
                <h2>01</h2>
                <h1>Collection of information</h1>
                <p>Lorem ipsum dolor sit amet consecteur.</p>
            </div>

            <div>
                <h2>02</h2>
                <h1>Strategic planning</h1>
                <p>Lorem ipsum dolor sit amet consecteur.</p>
            </div>

            <div>
                <h2>03</h2>
                <h1>Assignment of responsibilities</h1>
                <p>Lorem ipsum dolor sit amet consecteur.</p>
            </div>

            <div>
                <h2>04</h2>
                <h1>Formatting process</h1>
                <p>Lorem ipsum dolor sit amet consecteur.</p>
            </div>

            <div>
                <h2>05</h2>
                <h1>Continuity formalization</h1>
                <p>Lorem ipsum dolor sit amet consecteur.</p>
            </div>
        </div>
    </section>    
</template>

<script>
export default {
  name: 'Management',
}
</script>

<style scoped lang="scss">
#management {
    margin-top: 100px;
    #management-title {
        text-align: center;
        h5 {
            color: #05a5a6;
        }
        h1 {
            font-size: 40px;
            color: #21333e;
            margin: 20px 0 15px 0;
        }
        #title-design {
            color: #048283;
            background-color: #daebed;
            padding: 1px 8px 1px 8px;
            border-radius: 5px;
        }
    }
    #management-cards {
        display: flex;
        justify-content: center;
        flex-wrap: wrap;
        margin-top: 50px;
        margin-bottom: 100px;
        div {
            width: 220px;
            display: inline-block;
            text-align: center;
            margin: 20px;
            h2 {
                display: inline-block;
                color: #048283;
                background-color: #daebed;
                border-radius: 50%;
                padding: 10px 13px;
            }
        }
    }
}
</style>