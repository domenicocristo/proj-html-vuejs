<template>
  <header>
    <section id="info-header">
      <div id="timetables">
        <i class="fas fa-clock"></i>
        <span>Open Hours: Mon - Sat - 9:00 - 18:00</span>
      </div>

      <div id="contacts">
        <i class="fas fa-phone-alt"></i>
        <span>+1(305) 1234-5678</span>
        <i class="fas fa-envelope"></i>
        <span>hello@example.com</span>
        <i class="fab fa-facebook-f"></i>
        <i class="fab fa-twitter"></i>
        <i class="fab fa-linkedin-in"></i>
      </div>
    </section>

    <section id="jumbotron">
      <nav>
        <div id="logo">
          <h4><span id="logo-design">NEX</span> GEN</h4>
        </div>

        <div>
          <ul>
            <li v-for="item, i in itemsHeader" :key="i">{{item.name}}</li>
            <li>
              <i class="far fa-user"></i>
            </li>
          </ul>
          <button>GET IN TOUCH</button>
        </div>
      </nav>

      <div id="human-resources">
        <h5>HUMAN RESOURCES</h5>
        <h1>Get More <span id="title-design">Productivity</span></h1>
        <p>Planning, recruitment and selection process and performance evaluation of employees.</p>
        <button>GET IN TOUCH</button>
        <button id="button-invisible">READ MORE</button>
      </div>
    </section>

  </header>
</template>

<script>
export default {
  name: 'MyHeader',
  props: {
    itemsHeader: Array,
  }
}
</script>

<style scoped lang="scss">
header {
  color: #fff;
  i {
    width: 20px;
    margin: 0 10px 0 25px;
    border-radius: 50%;
    cursor: pointer;
  }
  i:hover {
    color: #048283;
  }
  #info-header {
    display: flex;
    justify-content: space-around;
    align-items: center;
    height: 40px;
    background-color: #21333e;
    span {
      cursor: pointer;
    }
    span:hover {
      color: #048283;
    }
  }
  #jumbotron {
    height: 700px;
    position: relative;
    background-image: url(../assets/img/bg-4.jpg);
    background-size: cover;
    padding-top: 15px;
    nav {
      #logo {
        display: inline-block;
        position: absolute;
        left: 10%;
        cursor: pointer;
      }
      #logo-design {
        color: #048283;
        background-color: #04838348;
        padding: 5px 3px 5px 20px;
        border-radius: 20px 0 0 20px;
      }
      div {
        position: absolute;
        right: 10%;
      }
      ul {
        display: inline-block; 
        list-style-type: none;
      }
      li {
        display: inline-block;
        margin-left: 20px;
        cursor: pointer;
      }
      li:hover {
        color: #048283;
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
      button:hover {
        background-color: #fff;
        color: #048283;
      }
    }
    #human-resources {
      width: 350px;
      position: absolute;
      top: 200px;
      left: 10%;
      h5 {
        color: #048283;
      }
      h1 {
        font-size: 50px;
        margin-bottom: 20px;
      }
      #title-design {
        background-color: #048283;
        border-radius: 5px;
        padding: 0 10px 0 10px;
      }
      button {
        margin: 20px 0 10px 0;
        border: none;
        border-radius: 3px;
        padding: 5px 15px;
        background-color: #048283;
        color: #fff;
        cursor: pointer;
      }
      button:hover {
        background-color: #fff;
        color: #048283;
      }
      #button-invisible {
        margin: 10px;
        border: none;
        border: 1px solid #048283;
        border-radius: 3px;
        padding: 5px 15px;
        background: none;
        color: #fff;
        cursor: pointer;
      }
      #button-invisible:hover {
        background-color: #fff;
        color: #000;
      }
    }
  }
}
</style>