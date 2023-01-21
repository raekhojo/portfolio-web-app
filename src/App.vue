<template>
  <nav class="navbar bg-info navbar-expand-lg bg-white p-0  border-0 py-3  sticky-top" style="border-bottom: 1px solid rgba(201, 201, 201, 0.605);">
    <div class="container-fluid container px-5">
      <router-link to="/" class="navbar-brand" href="#"><img src="@/assets/images/62b40acee51b4b86ee1252e3_jonas-logo.svg" alt=""></router-link>
      <button class="navbar-toggler  custom-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <input type="checkbox" id="checkbox2" class="checkbox2 visuallyHidden">
        <label for="checkbox2">
            <div class="hamburger hamburger2">
                <span class="bar bar1"></span>
                <span class="bar bar2"></span>
                <span class="bar bar3"></span>
                <span class="bar bar4"></span>
            </div>
        </label>
      </button>
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
          <li class="nav-item">
            <router-link to="/about" class="nav-link active fw-normal me-3" aria-current="page" href="./index.html" style="font-family: 20px; font-weight: bold;">Work</router-link>
          </li>
          <li class="nav-item">
            <a class="nav-link active fw-normal me-3" aria-current="page" href="#">About</a>
          </li>
          <li class="nav-item">
            <a  class="nav-link active fw-normal" aria-current="page" href="#contact">Contact</a>
          </li>
        </ul>
        <!-- <div class="d-flex" role="search">
          <button class="btn btn-outline-success  rounded-pill mb-2" type="submit" style="padding: 2px 20px;">Donate</button>
        </div> -->
      </div>
    </div>
  </nav>
  <router-view/>
</template>

<style>
@import url("https://fonts.googleapis.com/css2?family=Inter:wght@100;200;300;400;500;600;700;800;900&display=swap");
#app {
  font-family: Inter, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

.container,
.container-fluid,
.container-lg,
.container-md,
.container-sm,
.container-xl,
.container-xxl {
  width: 100%;
  padding-right: var(--bs-gutter-x, 0.75rem);
  padding-left: var(--bs-gutter-x, 0.75rem);
  margin-right: auto;
  margin-left: auto;
}

.navbar .collapse .navbar-nav .nav-item .nav-link {
  font-size: 18px;
  font-size: "Inter";
  line-height: 27px;
  vertical-align: top;
  letter-spacing: -0.18px;
  word-spacing: 0px;
  /* margin-right: 10px; */

  /* padding: 6px 10px; */
  font-weight: 700 !important;
  background-image: linear-gradient(
    to right,
    #54b3d6,
    #54b3d6 50%,
    RGB(82, 82, 82) 50%
  );
  background-size: 200% 100%;
  background-position: -100%;
  display: inline-block;
  padding: 5px 0;
  position: relative;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  transition: all 0.3s ease-in-out;
  color: #f7f7f7;
}
.navbar .collapse .navbar-nav .nav-item .nav-link::before {
  content: "";
  background: #54b3d6;
  display: block;
  position: absolute;
  bottom: -3px;
  left: 0;
  width: 0;
  height: 3px;
  transition: all 0.3s ease-in-out;
}
.navbar .collapse .navbar-nav .nav-item .nav-link:hover {
  background-position: 0;
}
.navbar .collapse .navbar-nav .nav-item .nav-link:hover::before {
  width: 100%;
}
.navbar-toggler {
  border: none;
}
.menustyle #bar2 {
  opacity: 0;
}

.menustyle #bar1 {
  transform: rotate(-45deg) translate(-5px, 5px);
}

.menustyle #bar3 {
  transform: rotate(45deg) translate(-1px, -2px);
}

#bar1,
#bar2,
#bar3 {
  padding: 0.1em 0.6em 0.1em 0.6em;
  margin: 20% auto;
  background-color: rgb(3, 3, 3);
  border-radius: 50px;
  transition: 0.5s;
  /* width: 60%; */
}

/* GENERAL STYLES */
.visuallyHidden {
  position: absolute;
  overflow: hidden;
  clip: rect(0 0 0 0);
  height: 1px;
  width: 1px;
  margin: -1px;
  padding: 0;
  border: 0;
}

.hamburger {
  margin: 0 0px;
  margin-top: 24px;
  width: 30px;
  height: 30px;
  position: relative;
}

.hamburger .bar {
  padding: 0;
  width: 30px;
  height: 3px;
  background-color: rgb(0, 0, 0);
  display: block;
  border-radius: 4px;
  transition: all 0.4s ease-in-out;
  position: absolute;
}

.bar1 {
  top: 0;
}
.bar2,
.bar3 {
  top: 5.5px;
}
.bar3 {
  right: 0;
}
.checkbox2:checked + label > .hamburger2 > .bar1 {
  transform: translateX(40px);
  background-color: transparent;
}

.checkbox2:checked + label > .hamburger2 > .bar2 {
  transform: rotate(45deg);
}

.checkbox2:checked + label > .hamburger2 > .bar3 {
  transform: rotate(-45deg);
}

.checkbox2:checked + label > .hamburger2 > .bar4 {
  transform: translateX(-40px);
  background-color: transparent;
}

.navbar-toggler:focus,
.navbar-toggler:active,
.navbar-toggler-icon:focus {
  outline: none;
  box-shadow: none;
}
</style>
