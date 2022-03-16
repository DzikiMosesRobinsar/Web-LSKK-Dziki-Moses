<template>
  <div class="hello">
     <section id="about">
      <div class="container" data-aos="fade-up">
        <div class="row about-container">

          <div class="col-lg-6 content order-lg-1 order-2">
            <h2 class="title">Tentang Kami</h2>
            <p>
              Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
            </p>

            <div class="icon-box" data-aos="fade-up" data-aos-delay="100">
              <div class="icon"><i class="bi bi-briefcase"></i></div>
              <h4 class="title"><a href="">Eiusmod Tempor</a></h4>
              <p class="description">Et harum quidem rerum facilis est et expedita distinctio. Nam libero tempore, cum soluta nobis est eligendi</p>
            </div>

            <div class="icon-box" data-aos="fade-up" data-aos-delay="200">
              <div class="icon"><i class="bi bi-card-checklist"></i></div>
              <h4 class="title"><a href="">Magni Dolores</a></h4>
              <p class="description">Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum</p>
            </div>

            <div class="icon-box" data-aos="fade-up" data-aos-delay="300">
              <div class="icon"><i class="bi bi-binoculars"></i></div>
              <h4 class="title"><a href="">Dolor Sitema</a></h4>
              <p class="description">Minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat tarad limino ata</p>
            </div>

          </div>

          <div class="col-lg-6 background order-lg-2 order-1" data-aos="fade-left" data-aos-delay="100"></div>
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
#about {
  background: #fff;
  padding: 80px 0;
}
#about .about-container .background {
  min-height: 300px;
  background: url(../assets/employee.webp) center top no-repeat;
  margin-bottom: 10px;
}
#about .about-container .content {
  background: #fff;
}
#about .about-container .title {
  color: #333;
  font-weight: 700;
  font-size: 32px;
}
@media (max-width: 768px) {
  #about .about-container .title {
    padding-top: 15px;
  }
}
#about .about-container p {
  line-height: 26px;
}
#about .about-container p:last-child {
  margin-bottom: 0;
}
#about .about-container .icon-box {
  background: #fff;
  background-size: cover;
  padding: 0 0 30px 0;
}
#about .about-container .icon-box .icon {
  float: left;
  background: #fff;
  width: 64px;
  height: 64px;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  text-align: center;
  border-radius: 50%;
  border: 2px solid #2dc997;
}
#about .about-container .icon-box .icon i {
  color: #2dc997;
  font-size: 24px;
  line-height: 0;
}
#about .about-container .icon-box .title {
  margin-left: 80px;
  font-weight: 500;
  margin-bottom: 5px;
  font-size: 18px;
  text-transform: uppercase;
}
#about .about-container .icon-box .title a {
  color: #111;
}
#about .about-container .icon-box .description {
  margin-left: 80px;
  line-height: 24px;
  font-size: 14px;
}
</style>
