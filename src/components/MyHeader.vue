<template>
  <header>
    <section id="info-header">
      <div id="timetables">
        <span>Open Hours: Mon - Sat - 9:00 - 18:00</span>
      </div>

      <div id="contacts">
        <span>+1(305) 1234-5678 </span>
        <span>hello@example.com</span>
      </div>
    </section>

    <section id="jumbotron">
      <nav>
        <div>
          <h4>NEX GEN</h4>
        </div>

        <div>
          <ul>
            <li>
              <h4>HOME</h4>
            </li>
            <li>
              <h4>ABOUT</h4>
            </li>
            <li>
              <h4>PROJECTS</h4>
            </li>
            <li>
              <h4>PROCESS</h4>
            </li>
            <li>
              <h4>TESTIMONIALS</h4>
            </li>
          </ul>
          <button>GET IN TOUCH</button>
        </div>
      </nav>

      <div id="human-resources">
        <h5>HUMAN RESOURCES</h5>
        <h1>Get More Productivity</h1>
        <p>Planning, recruitment and selection process and performance evaluation of employees.</p>
        <button>GET IN TOUCH</button>
        <button>READ MORE</button>
      </div>
    </section>

  </header>
</template>

<script>
export default {
  name: 'MyHeader',
}
</script>

<style scoped lang="scss">
header {
  color: #fff;
  #info-header {
    display: flex;
    justify-content: space-around;
    align-items: center;
    height: 40px;
    background-color: #21333e;
  }
  #jumbotron {
    height: 700px;
    background-image: url(../assets/img/bg-4.jpg);
    nav {
      display: flex;
      justify-content: space-around;
      ul {
        display: inline-block;
        list-style-type: none;
      }
      li {
        display: inline-block;
        margin: 10px;
        cursor: pointer;
      }
      button {
        
      }
    }
  }
}
</style>