<template>
  <div class="hello">
      <section id="contact" class="tm-section-pad-top tm-parallax-2">
      <div class="container tm-container-contact">
        <div class="row">
            <div class="col-12">
                <h2 class="mb-4 tm-section-title">Hubungi Kami!</h2>
                <div class="mb-5 tm-underline">
                  <div class="tm-underline-inner"></div>
                </div>
            </div>
            
            <div class="col-sm-12 col-md-6 d-flex align-items-center tm-contact-item">
              <a href="tel:0100200340" class="tm-contact-item-link">
                  <span class="mb-0">Nomer Telfon/Whatssapp: 08123456789</span>
              </a>              
            </div>
            <div class="col-sm-12 col-md-6 d-flex align-items-center tm-contact-item">
              <a href="mailto:info@company.co" class="tm-contact-item-link">
                  <span class="mb-0">Email: kerenbanget@gmail.com</span>
              </a>              
            </div>
            <div class="col-sm-12 col-md-6 d-flex align-items-center tm-contact-item">
              <a href="https://www.google.com/maps" class="tm-contact-item-link">
                  <span class="mb-0">Alamat: Klik disini untuk melihat alamat.</span>
              </a>              
            </div>
            <div class="col-sm-12 col-md-6 d-flex align-items-center tm-contact-item">
              <form action="" method="get">
                <input name="email" type="email" placeholder="Subscribe your email" class="tm-input" required />
                <button type="submit" class="btn tm-btn-submit">Submit</button>
              </form>
            </div>
        </div>
      </div>
      <footer class="text-center small tm-footer">
          <p class="mb-0">
            Copyright &copy; 2022 Dziki Moses R.
            
           
          </p>
        </footer>
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

#contact {
  color: white;
  background: linear-gradient(to bottom,#232526, #414345);
  min-height: 70vh;
  position: relative;
  padding-bottom: 50px;
  padding-top: 160px;
  margin-top: 15%;
}

.tm-underline {
  border-top: 2px solid white;
  height: 8px;
  width: 100%;
}

.tm-underline-inner {
  width: 25%;
  height: 8px;
  background: white;
}

.tm-contact-item {
  margin-bottom: 75px;
}

.tm-contact-item-link {
  display: flex;
  align-items: center;
}

.tm-contact-item-link i,
.tm-contact-item-link span {
  color: white;
  transition: all 0.3s ease;
}

.tm-contact-item-link:hover i,
.tm-contact-item-link:hover span {
  text-decoration: underline;
}

.tm-input {
  padding: 8px 25px;
  border-radius: 3px;
  border: 1px solid white;
  background: transparent;
  color: white;
}

.tm-btn-submit {
  margin-left: 20px;
  border: 1px solid white;
}

.btn {
  color: white;
}

.tm-footer {
  position: absolute;
  bottom: 35px;
  left: 0;
  right: 0;
  padding: 0 15px;
}

.tm-footer-link {
  color: white;
}

.tm-footer-link:hover,
.tm-footer-link:focus {
  color: #3496d8;
  text-decoration: none;
}

p {
  line-height: 1.9;
}

::placeholder { /* Chrome, Firefox, Opera, Safari 10.1+ */
  color: white;
  opacity: 1; /* Firefox */
}

:-ms-input-placeholder { /* Internet Explorer 10-11 */
  color: white;
}

::-ms-input-placeholder { /* Microsoft Edge */
  color: white;
}



</style>
