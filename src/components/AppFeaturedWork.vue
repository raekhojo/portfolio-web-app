<template>
    <section class="container mt-5 mb-5">
        <h2 class="featured-work mb-4 px-4 text-start">
          Featured work <span style="color: #767676;"> ·  2018–2022</span>
         </h2>
        <div class="px-4">
          <div class="row row-cols-1 row-cols-sm-2 row-cols-md-2" data-masonry='{"percentPosition": true }'>
            <div class="col  py-1">
              <div class="card mb-4 border-0 rounded-5">
                <img class="card-img-top" src="@/assets/images/62b31dddf5adbc11ff9e2776_project-6-thumbnail.jpg" alt="Card image" style="width:100%;">
                <div class="card-body" style="background: #f7f7f7;">
                  <h4 class="card-title mb-1">Rule Ratio</h4>
                  <p class="card-text">Product Design</p>
                </div>
              </div>
              <div class="card mb-4 border-0">
                <img class="card-img-top" src="@/assets/images/62b32209761c968fda50f476_project-2-thumbnail.jpg" alt="Card image" style="width:100%;">
                <div class="card-body">
                  <h4 class="card-title">Dry air</h4>
                  <p class="card-text">User research</p>
                </div>
              </div>
              <div class="card mb-4 border-0">
                <img class="card-img-top" src="@/assets/images/62b321f13a6b3e7f6cd0566d_project-3-thumbnail.jpg" alt="Card image" style="width:100%;">
                <div class="card-body">
                  <h4 class="card-title">Variable compose</h4>
                  <p class="card-text">Product design</p>
                </div>
              </div>
            </div>
            <div class="col  py-1">
              <div class="card mb-4 border-0" >
                <img class="card-img-top" src="@/assets/images/62b3216f1e53510cc23e1942_project-5-thumbnail.jpg" alt="Card image" style="width:100%">
                <div class="card-body">
                  <h4 class="card-title">Situation</h4>
                  <p class="card-text">Visual identity</p>
                </div>
              </div>
              <div class="card mb-4 border-0">
                <img class="card-img-top" src="@/assets/images/62b41865f2feb17d228b80b9_project-4-thumbnail.jpg" alt="Card image" style="width:100%">
                <div class="card-body">
                  <h4 class="card-title">Vertical</h4>
                  <p class="card-text"> Product design</p>
                </div>
              </div>
              <div class="card mb-4 border-0">
                <img class="card-img-top" src="@/assets/images/62b427ac5b1d8f581a094663_project-1-thumbnail.jpg" alt="Card image" style="width:100%">
                <div class="card-body">
                  <h4 class="card-title">Vertical</h4>
                  <p class="card-text"> Product design</p>
                </div>
              </div>
            </div>
          </div>
        </div>
       </section>
</template>
<style>
.featured-work {
    font-size: 18px;
    line-height: 23.4px;
    vertical-align: baseline;
    letter-spacing: -0.54px;
    word-spacing: 0px;
    margin: 0px;
    padding: 0px;
    font-weight: 600;
  }
  .card {
    position: relative;
    top: 0;
    transition: top ease 0.5s;
  }
  .card:hover {
    top: -3px;
    cursor: pointer;
    opacity: 0.8;
  }
  .card-img-top {
    border-radius: 30px 30px 0px 0px;
  }
  .card-body {
    border-radius: 0px 0px 30px 30px;
    background: #FAFAFA;
    padding: 24px 28px 24px 24px;
  }
  .card-title {
    font-size: 20px;
    line-height: 26px;
    vertical-align: baseline;
    letter-spacing: -0.6px;
    word-spacing: 0px;
    margin: 0px;
    padding: 0px;
    font-family: "Inter";
    font-weight: 600;
    text-align: start;
    color:black;
  }

  .card-text {
    font-family: Inter;
    font-size: 20px;
    line-height: 26px;
    vertical-align: baseline;
    letter-spacing: -0.6px;
    word-spacing: 0px;
    margin: 0px;
    padding: 0px;
    font-weight: 600;
    font-style: normal;
    color: #757575;
    text-decoration: none solid rgb(117, 117, 117);
    text-align: start;
    text-indent: 0px;
  }
</style>
