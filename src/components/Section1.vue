<template>
  <div class="hello">
     <section class="section-1" id="About">
      <div class="container text-center">
        <div class="row">
          <div class="col-md-6 col-12">
            <div class="pray">
              <img src="../assets/hero2.jpg" alt="Pray" class="" />
            </div>
          </div>
          <div class="col-md-6 col-12">
            <div class="panel text-left">
              <h1>Tentang Kami</h1>
              <p class="pt-4">
                Indonesia <br />
               PT. LSKK (Langgeng Sejahtera Kreasi Komputasi) didirikan pada tahun 2008 sebagai perusahaan yang bergerak di bidang integrasi teknologi. Perusahaan ini didirikan untuk memberikan kontribusi bagi pembangunan nasional, khususnya di bidang elektroteknik dan rekayasa pada umumnya. 
              </p>
            </div>
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
.section-1 {
  padding: 10vmin 0vmin;
  margin-top: 10%;
  
}

.section-1 .row .col-md-6 .pray img {
  width: 80%;
  border-radius: 0.2em;
  box-shadow: rgba(0, 0, 0, 0.24) 0px 3px 8px;
}

.section-1 .row .col-md-6:last-child {
  position: relative;
}

.section-1 .row .col-md-6 .panel {
  position: absolute;
  top: 4vmin;
  left: -18vmin;
  background: white;
  border-radius: 3px;
  text-align: left;
  padding: 10vmin 5vmin 13vmin 10vmin;
  box-shadow: rgba(0, 0, 0, 0.24) 0px 3px 8px;
  z-index: 1;
}

.section-1 .row .col-md-6 .panel h1 {
  font-weight: bold;
  padding: 0.4em 0;
  padding-bottom: 0.01;
  font-size: 2em;
}

.section-1 .row .col-md-6 .panel p {
  font-size: 0.9em;
  color: rgba(0, 0, 0, 0.5);
}

@media only screen and (max-width: 768px) {
  .section-1 .row .col-md-6 .panel {
    position: initial;
    width: initial;
    height: initial;
  }
}

</style>
