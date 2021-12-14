<template>
  <footer>
    <section id="footer-left">
        <h5>SEND A MESSAGE</h5>
        <h1>Get in <span id="title-design">Touch</span></h1>
        <p>We will responde to your message as soon as possible</p>
        <input type="text" placeholder="Name">
        <input type="text" placeholder="Email">
        <input type="text" placeholder="Phone">
        <input type="text" placeholder="More info">
        <input id="message" type="text" placeholder="Message">
        <button>SEND</button>
    </section> 

    <section id="footer-right">
        <h1>Example Inc.</h1>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
        <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit.</p>
        <div>
          <i class="fas fa-phone-alt"></i>
          <span>+1(305) 1234-5678</span>
        </div>
        <div>
          <i class="fas fa-envelope"></i>
          <span>hello@example.com</span>
        </div>
        <div>
          <i class="fas fa-map-marker-alt"></i>
          <span>Main Avenue, 987</span>
        </div>
        <button>VIEW MAP</button>
    </section>
  </footer>
</template>

<script>
export default {
  name: 'MyFooter',
}
</script>

<style scoped lang="scss">
footer {
  display: flex;
  justify-content: center;
  background-color: #111118;
  color: #fff;
  padding-top: 100px;
  padding-bottom: 200px;
  #footer-left {
    width: 620px;
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
    input {
      height: 35px;
      width: 300px;
      margin: 10px 10px 0 0;
      background-color: #1d1d23;
      border: none;
      border-radius: 5px;
    }
    #message {
      height: 120px;
      width: 610px;
    }
    button {
      display: block;
      border: none;
      border-radius: 3px;
      padding: 5px 15px;
      background-color: #048283;
      color: #fff;
      margin-top: 20px;
      cursor: pointer;
      }
  }
  #footer-right {
    width: 300px;
    margin-left: 30px;
    h1 {
      margin-bottom: 20px;
    }
    p {
      margin-bottom: 20px;
    }
    div {
      margin-bottom: 20px;
      color: #048283;
    }
    i {
      height: 40px;
      width: 40px;
      background-color: #0f2128;
      margin-right: 10px;
      text-align: center;
      border-radius: 50%;
      padding-top: 4%;
    }
    button {
      display: block;
      margin-top: 10px;
      border: none;
      border: 1px solid #048283;
      border-radius: 3px;
      padding: 5px 15px;
      background: none;
      color: #fff;
      cursor: pointer;
    }
  }
}
</style>