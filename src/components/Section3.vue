<template>
  <div class="hello">
     <section id="#Working" class="section-2 container-fluid p-0">
      <div class="cover">
        <div class="overlay"></div>
        <div class="content text-center">
          <h1>Mari Bergabung Bersama Kami</h1>
          <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Vitae, eum?
          </p>
        </div>
      </div>
      <div class="container-fluid text-center">
        <div class="numbers d-flex flex-md-row flex-wrap justify-content-center">
          <div class="rect">
            <h1>2345</h1>
            <p>Total Client</p>
          </div>
          <div class="rect">
            <h1>30</h1>
            <p>Total Karyawan</p>
          </div>
          <div class="rect">
            <h1>9152</h1>
            <p>Total Projects</p>
          </div>
        </div>
      </div>
     </section>
  </div>
  
</template>

<script>
export default {
  name: 'HomeView',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.cover {
  width: 100%;
  height: 55vmin;
  background: url("../assets/employee.webp");
  background-position: -24rem -19rem;
  background-size: 150%;
  position: relative;
  margin-top: 15%;
}

.cover .overlay {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  z-index: 999;
}

.cover .content {
  width: 100%;
  height: 100%;
  background: rgba(0, 0, 0, 0.7);
  padding-top: 19vmin;
}

.cover .content > h1 {
  font-family: var(--Patua);
  font-size: 6vmin;
  color: whitesmoke;
}

.cover .content > p {
  font-family: var(--Rubik);
  font-size: 2vmin;
  color: #e5e5e5;
}

.numbers .rect {
  position: relative;
  z-index: 1;
  background: white;
  width: 17rem;
  height: 12rem;
  padding-top: 3.5vmin;
  margin: 2rem;
  border-radius: 0.5em;
  box-shadow: #414345 0px 3px 8px;;
}

.numbers {
  margin-top: -15vmin;
}

.numbers .rect h1 {
  font-size: 5rem;
  color: #414345;
}

.numbers .rect > p {
  font-family: var(--Patua);
}

.purchase > h1 {
  padding-top: 15vmin;
  padding-bottom: 0.1em;
  font-family: var(--Lobster);
}




</style>
