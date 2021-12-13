<template>
  <section id="the-company">
    <div id="the-company-cards">
      <div>
        <i class="fas fa-user-friends"></i>
        <h4>Human Capital</h4>
        <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Inventore molestias magni aperiam similique possimus. Totam hic,</p>
      </div>

      <div>
        <i class="fas fa-chart-pie"></i>
        <h4>Core Business</h4>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. A iusto magnam molestiae, nam fugit eum. Expedita .</p>
      </div>

      <div>
        <i class="fas fa-thermometer-half"></i>
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
</template>

<script>
export default {
  name: 'TheCompany',
}
</script>

<style scoped lang="scss">
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
</style>