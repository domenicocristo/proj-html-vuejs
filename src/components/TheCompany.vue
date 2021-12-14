<template>
  <section id="the-company">
    <div id="the-company-cards">
      <div>
        <i class="fas fa-user-friends"></i>
        <h4>Human Capital</h4>
        <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. A iusto magnam molestiae, nam fugit eum. Expedita.</p>
      </div>

      <div>
        <i class="fas fa-chart-pie"></i>
        <h4>Core Business</h4>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. A iusto magnam molestiae, nam fugit eum. Expedita.</p>
      </div>

      <div>
        <i class="fas fa-thermometer-half"></i>
        <h4>Performance</h4>
        <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. A iusto magnam molestiae, nam fugit eum. Expedita.</p>
        </div>
    </div>

    <div id="the-company-network">
      <div id="the-company-network-left">
        <h5>ABOUT THE NETWORK</h5>
        <h1><span id="title-design">The</span> Company</h1>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quam tot maxime quta ducimus magni excepturi libero quos a?</p>

        <div id="network-cards">
            <div>
              <h2>0</h2>
              <h3>Employees</h3>
              <p>Lorem ipsum dolor sit amet.</p>
            </div>

            <div>
              <h2>0</h2>
              <h3>Partners</h3>
              <p>Lorem ipsum dolor sit amet.</p>
            </div>

            <div>
              <h2>0</h2>
              <h3>Customers</h3>
              <p>Lorem ipsum dolor sit amet.</p>
            </div>
        </div>

        <button>GET IN TOUCH</button>
        <button id="button-invisible">READ MORE</button>
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
    i {
      height: 40px;
      width: 40px;
      background-color: #daebed;
      color: #05a5a6;
      text-align: center;
      border-radius: 50%;
      padding-top: 5.5%;
      margin: 20px 0 15px 0;
    }
    div {
      display: inline-block;
      height: 250px;
      width: 250px;
      border-radius: 10px;
      background-color: #fff;
      margin: 10px;
      padding: 20px;
      h4 {
        margin-bottom: 15px;
        color: #21333e;
      }
    }
  }
  #the-company-network {
    #the-company-network-left {
      display: inline-block;
      width: 50%;
      float: left;
      padding-top: 100px;
      padding-left: 180px;
      h5 {
        color: #05a5a6;
      }
      h1 {
        font-size: 40px;
        color: #21333e;
        margin: 20px 0 20px 0;
      }
      #title-design {
        color: #048283;
        background-color: #daebed;
        padding: 1px 8px 1px 8px;
        border-radius: 5px;
      }
      #network-cards {
        margin: 30px 0 30px 0;
        div {
        display: inline-block;
        width: 25%;
        margin-right: 20px;
          h2 {
            color: #05a5a6;
          }
          h3 {
            font-size: 22px;
            margin-bottom: 15px;
            color: #21333e;
          }
        }
      }
      button {
        margin-left: 20px;
        border: none;
        border-radius: 3px;
        padding: 5px 15px;
        background-color: #048283;
        color: #fff;
        cursor: pointer;
      }
      #button-invisible {
        margin: 10px;
        border: none;
        border: 1px solid #048283;
        border-radius: 3px;
        padding: 5px 15px;
        background: none;
        color: #048283;
        cursor: pointer;
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