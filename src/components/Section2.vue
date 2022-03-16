<template>
  <div class="hello">
    <section class="section-4" id="#Project">
       <div class="section-title">
          <h2>Layanan</h2>
          <p>Dibawah ini adalah layanan yang kami punya.</p>
        </div>
       <div class="testimonial" id="testimonial">
      <div class="container">
        <div class="row">
          <div class="col-md">
            <div class="card">
              <img src="../assets/desktop.png" class="card-img-top" alt="..." />
              <div class="card-body">
                <p class="card-text">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Quos fuga repudiandae totam blanditiis </p>
              </div>
            </div>
          </div>
          <div class="col-md">
            <div class="card">
              <img src="../assets/maintenance.png" class="card-img-top" alt="..." />
              <div class="card-body">
                <p class="card-text">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Quaerat ex odit, enim est omnis </p>
              </div>
            </div>
          </div>
          <div class="col-md">
            <div class="card">
              <img src="../assets/worldwide.png" class="card-img-top" alt="..." />
              <div class="card-body">
                <p class="card-text">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Repudiandae soluta aspernatur </p>
              </div>
            </div>
          </div>
          <div class="col-md">
            <div class="card">
              <img src="../assets/desktop.png" class="card-img-top" alt="..." />
              <div class="card-body">
                <p class="card-text">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Quos fuga repudiandae totam blanditiis </p>
              </div>
            </div>
          </div>
          <div class="col-md">
            <div class="card">
              <img src="../assets/desktop.png" class="card-img-top" alt="..." />
              <div class="card-body">
                <p class="card-text">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Quos fuga repudiandae totam blanditiis </p>
              </div>
            </div>
          </div>
          <div class="col-md">
            <div class="card">
              <img src="../assets/desktop.png" class="card-img-top" alt="..." />
              <div class="card-body">
                <p class="card-text">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Quos fuga repudiandae totam blanditiis </p>
              </div>
            </div>
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

.section-title {
  text-align: center;
  padding-bottom: 30px;
  margin-top: 10%;
}
.section-title h2 {
  font-size: 32px;
  font-weight: 600;
  margin-bottom: 20px;
  padding-bottom: 20px;
  position: relative;
}
.section-title h2::before {
  content: "";
  position: absolute;
  display: block;
  width: 120px;
  height: 1px;
  background: #ddd;
  bottom: 1px;
  left: calc(50% - 60px);
}
.section-title h2::after {
  content: "";
  position: absolute;
  display: block;
  width: 40px;
  height: 3px;
  background: #414345;
  bottom: 0;
  left: calc(50% - 20px);
}
.section-title p {
  margin-bottom: 0;
}

.testimonial .row {
  padding-top: 50px;
  margin-top: 5vmin;
}

.testimonial .row .card {
  border: none;
  background: transparent;
  transition: ease-in-out 0.2s;
  box-shadow:  #414345 0px 3px 8px;;
}

.testimonial .row .card:hover {
  box-shadow: rgba(0, 0, 0, 0.25) 0px 54px 55px, rgba(0, 0, 0, 0.12) 0px -12px 30px, rgba(0, 0, 0, 0.12) 0px 4px 6px, rgba(0, 0, 0, 0.17) 0px 12px 13px, rgba(0, 0, 0, 0.09) 0px -3px 5px;
}

.testimonial .card-img-top {
  width: 125px;
  height: 125px;
  margin: auto;
  padding-top: 5%;
 
}

.testimonial .card-text {
  font-family: Arial, Helvetica, sans-serif;
  text-align: center;
}



</style>
