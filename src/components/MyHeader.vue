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
          <h4>HOME</h4>
          <h4>ABOUT</h4>
          <h4>PROJECTS</h4>
          <h4>PROCESS</h4>
          <h4>TESTIMONIALS</h4>
          <button>GET IN TOUCH</button>
        </div>
      </nav>

      <div id="human-resources">
        <div>HUMAN RESOURCES</div>
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
    background-color: #5c828c;
  }
  #jumbotron {
    height: 700px;
    background-image: url(../assets/img/bg-4.jpg);
    nav {
      display: flex;
      justify-content: space-around;
      h4 {
        display: inline-block;
        margin: 10px;
      }
    }
  }
}
</style>