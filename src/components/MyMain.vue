<template>
  <main>
      <section id="the-company">
          <div id="the-company-cards">
              <div>
                  <h4>Human Capital</h4>
                  <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Inventore molestias magni aperiam similique possimus. Totam hic,</p>
              </div>

              <div>
                  <h4>Core Business</h4>
                  <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. A iusto magnam molestiae, nam fugit eum. Expedita .</p>
              </div>

              <div>
                  <h4>Performance</h4>
                  <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Tempora, esse assumenda! Beatae obcaecati .</p>
              </div>
          </div>

          <div id="the-company-network">
              <div id="the-company-network-left">
                  <h5>ABOUT THE NETWORK</h5>
                  <h1>The Company</h1>
                  <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quam tot maxime quta ducimus magni excepturi libero quos a?</p>

                  <div id="network-cards">
                        <div>
                            <h2>0</h2>
                            <h1>Employees</h1>
                            <p>Lorem ipsum dolor sit amet.</p>
                        </div>

                        <div>
                            <h2>0</h2>
                            <h1>Partners</h1>
                            <p>Lorem ipsum dolor sit amet.</p>
                        </div>

                        <div>
                            <h2>0</h2>
                            <h1>Customers</h1>
                            <p>Lorem ipsum dolor sit amet.</p>
                        </div>
                  </div>

                  <button>GET IN TOUCH</button>
                  <button>READ MORE</button>
              </div>

              <div id="the-company-network-right">
                  <img src="../assets/img/about-5.jpg" alt="">
              </div>
          </div>
      </section>

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
  </main>
</template>

<script>
export default {
  name: 'MyMain',
}
</script>

<style scoped lang="scss">
main {
    #the-company {
        #the-company-cards {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 400px;
            background-color: #e4eae5;
            div {
                display: inline-block;
                height: 250px;
                width: 250px;
                border-radius: 10px;
                background-color: #fff;
                margin: 10px;
                padding: 15px;
            }
        }
        #the-company-network {
            #the-company-network-left {
                display: inline-block;
                width: 50%;
                float: left;
                padding-top: 100px;
                padding-left: 200px;
                #network-cards {
                    div {
                        display: inline-block;
                        width: 100px;
                        margin: 20px;
                        h2 {
                            color: #05a5a6;
                        }
                    }
                }
            }
            #the-company-network-right {
                display: inline-block;
                width: 50%;
                img {
                    width: 100%;
                }
            }
        }
    }
    #actions-projects {
        background-color: #111118;
        color: #fff;
        padding-top: 50px;
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
            }
            h1 {
               position: absolute;
               bottom: 20px; 
               z-index: 2;
            }
        }
    }
}
</style>