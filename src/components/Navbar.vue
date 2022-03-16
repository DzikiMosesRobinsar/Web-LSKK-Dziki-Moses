<template>
  <div class="hello">
     <header id="Home">
    <div class="container-fluid p-0">
      <nav class="navbar navbar-expand-lg">
        <div class="container">
        <a class="navbar-brand" href="#">
        LSKK</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false"
          aria-label="Toggle navigation">
            <b-button title="Align right">
          <b-icon icon="bar-chart-fill" flip-v></b-icon>
        </b-button>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
          <div class="mr-auto"></div>
          <ul class="navbar-nav">
            <li class="nav-item active">
              <a class="nav-link" href="#Home">Home</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#About">Tentang Kami</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Layanan</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Join Us</a>
            </li>
          </ul>
        </div>
        </div>
      </nav>
    </div>
    <div class="container">
      <div class="row">
        <div class="col-md-7 col-sm-12  text-white ">
          <h6>AUTHOR: Dziki Moses R.</h6>
          <h2>PT. Langgeng Sejahtera Kreasi Komputasi.</h2>
          <button class="btn btn-light px-5 py-2 primary-btn">
            More Info
          </button>
        </div>
      </div>
    </div>
  </header>
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
header a {
  font-family: var(--Sniglet-font);
  font-size: 0.9em;
  color: whitesmoke;
}


header .nav-item:last-child {
  padding-right: 10.5em;
}

header .nav-item {
  padding: 0.9em;
}

header .navbar-brand {
  font-size: 30px;
}

header .navbar-nav a {
  font-size: 20px;
}

header .nav-link:hover {
  color: black;
}

header .row .col-md-7 {
  padding: 22vmin 1vmin;
  padding-bottom: 35vmin;
}

header .row .col-md-5 {
  padding: 4.2vmin 1vmin;
}

header .row .col-md-5 img {
  width: 90%;
}

header {
  background-image: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), url("../assets/background.jpg");
  background-size: cover;
  background-repeat: no-repeat;
}

header .container .col-md-7 {
  font-family: "Rubik", sans-serif;
}

header .container .col-md-7 h6 {
  padding: 1vmin;
  letter-spacing: 4px;
}

header .container .col-md-7 h2 {
  font-size: 6vmin;
  font-weight: bold;
  padding: 0.1em 0em;
}

header .container .col-md-7 p {
  padding: 1vmin 5vmin;
}

.primary-btn {
  border-radius: 30px;
  font-weight: bold;
}

</style>
