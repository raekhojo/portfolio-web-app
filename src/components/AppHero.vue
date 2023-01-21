<template>
    <section class="container hero-text px-4  mobile-margin visible-xs mb-5">
        <div class="w px-4">
          <h1 class="ml2 text-start text-dark">I’m Enock — a  senior product designer <span class="hero-span">that cares a lot about positive impact projects </span></h1>
         </div>
    </section>
</template>
<style>
.hero-text {
    height: 100vh;
    display: flex;
    align-items: center;
    justify-items: center;
    /* max-width: 1600px; */
    width: 100vw;
    padding: 125px 0px;
    /* background-color: red; */
  }
.portfolio-container {
    max-width: 1600px;
    padding: 128px 88px !important;
  }
.ml2 {
    margin-top: 0;
    margin-bottom: 0;
    font-family: Inter, sans-serif;
    font-size: 64px;
    line-height: 1.15;
    font-weight: 600;
    letter-spacing: -0.04em;
    display: block;
    /* font-size: 2em; */
    margin-block-start: 0.67em;
    margin-block-end: 0.67em;
    margin-inline-start: 0px;
    margin-inline-end: 0px;
    font-weight: bold;
  }
.hero-span {
    color: #757575;
  }
  @media (max-width: 728px) {
    .ml2 {
      font-size: 36px;
      line-height: 51.4px;
      vertical-align: baseline;
      line-height: 1.15;
      font-weight: 600;
      letter-spacing: -0.04em;
      word-spacing: 0px;
      margin: 0px;
      padding: 0px;
      width: 100% !important;
    }
    .hero-text {
      padding: 10px !important;
      height: 40vh;
      /* background: #000; */
    }
}
</style>
