<template>
  <body>
    <div class="container">
      <div class="global__height"></div>
      <h1>NEWS</h1>
      <h4>Current Projects</h4>
      <div class="row">
        <div class="col-xs-6 col-md-12 border__">
          <h3>
            Co-developing Data Technology for Inclusive Conservation in the
            Eastern Serengeti.
          </h3>
          <div class="content__text">
            <p>
              This is a 1-year project with the aim of co-developing together
              with the local communities, a mobile app and data collection and
              management protocols. This will serve the interests of the
              communities for more research to inform both the local indigenous
              people on their wildlife monitoring and livestock grazing
              strategies, and protected areas management. This project is funded
              by the Centre for Indigenous Conservation and Development
              Alternatives (CICADA at the University of McGill, Canada.
            </p>
          </div>
        </div>
        <div class="col-xs-6 col-md-12 border__">
          <h3>
            Twiga Wetu: Masai Giraffe Conservation Outside Protected Areas – the
            Role of Indigenous Knowledge and Traditional Systems.
          </h3>
          <div class="content__text">
            <p>
              This project is a 1-year project (Oct. 2020 – Sept. 2021) funded
              by Giraffe Conservation Foundation
              <a href="www.giraffeconservation.org"
                >(www.giraffeconservation.org)</a
              >. The aim of this project is to revitalize indigenous
              conservation of Masai giraffe in the eastern Serengeti Ecosystem.
              This will serve the interests of the local communities to be
              involved in the conservation and monitoring of giraffe linked with
              livestock grazing strategies outside protected areas.
            </p>
          </div>
        </div>
      </div>
      <a href="/projects">
        <Button class="btn__explore" label="Expolre News"
      /></a>
    </div>
  </body>
</template>

<script>
import Button from "@/components/Button.vue";
export default {
  components: {
    Button,
  },
};
</script>

<style lang="scss" scoped>
@media only screen and (max-width: 900px) {
  h4 {
    padding-top: 2rem !important;
    margin-bottom: -3.5rem !important;
  }
  .border__ {
    display: block !important;

    h3 {
      padding: 2rem 0 1rem 0;
    }
    p {
      margin: 0 !important;
      padding: 0.5rem 0;
    }
  }
}

body {
  background: #ddd;
  padding: 2rem 0 6rem 0;

  .btn__explore {
    margin: auto;
    width: 20%;
    text-align: center;
  }

  .row {
    margin: auto;
  }

  .image {
    border: 1px solid #30303011;
  }

  .border__ {
    display: grid;
    grid-template-columns: 1fr 2fr;
    column-gap: 50px;
    padding: 3rem 0;

    p {
      font-size: 1.6rem;
      color: #303030 !important;
    }

    img {
      width: 100%;
      padding: 2rem;
    }
  }

  h1 {
    text-align: center;
  }

  h3 {
    margin: 0;
    font-size: 20px;
    line-height: 1.5;
    padding-bottom: 1rem;
  }

  h4 {
    color: #505050;
    margin: 0;
    padding: 0;
  }
}
</style>
