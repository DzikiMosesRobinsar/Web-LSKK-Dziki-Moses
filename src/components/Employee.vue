<template>
  <div class="hello">
       <section id="team">
      <div class="container" data-aos="fade-up">
        <div class="section-header">
          <h3 class="section-title">Team</h3>
          <p class="section-description">Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque</p>
        </div>
        <div class="row">
          <div class="col-lg-3 col-md-6">
            <div class="member" data-aos="fade-up" data-aos-delay="100">
              <div class="pic"><img src="../assets/team-1.jpg" alt=""></div>
              <h4>Walter White</h4>
              <span>Chief Executive Officer</span>
            </div>
          </div>

          <div class="col-lg-3 col-md-6">
            <div class="member" data-aos="fade-up" data-aos-delay="200">
              <div class="pic"><img src="../assets/team-4.jpg" alt=""></div>
              <h4>Sarah Jhinson</h4>
              <span>Product Manager</span>
              
            </div>
          </div>

          <div class="col-lg-3 col-md-6">
            <div class="member" data-aos="fade-up" data-aos-delay="300">
              <div class="pic"><img src="../assets/team-3.jpg" alt=""></div>
              <h4>William Anderson</h4>
              <span>CTO</span>
             
            </div>
          </div>

          <div class="col-lg-3 col-md-6">
            <div class="member" data-aos="fade-up" data-aos-delay="400">
              <div class="pic"><img src="../assets/team-4.jpg" alt=""></div>
              <h4>Amanda Jepson</h4>
              <span>Accountant</span>
              
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
#team {
  background: #fff;
  padding: 80px 0 60px 0;
}
#team .member {
  text-align: center;
  margin-bottom: 20px;
}
#team .member .pic {
  margin-bottom: 15px;
  overflow: hidden;
  height: 260px;
}
#team .member .pic img {
  max-width: 100%;
}
#team .member h4 {
  font-weight: 700;
  margin-bottom: 2px;
  font-size: 18px;
}
#team .member span {
  font-style: italic;
  display: block;
  font-size: 13px;
}
#team .member .social {
  margin-top: 15px;
}
#team .member .social a {
  color: #b3b3b3;
}
#team .member .social a:hover {
  color: #2dc997;
}
#team .member .social i {
  font-size: 18px;
  margin: 0 2px;
}


</style>
