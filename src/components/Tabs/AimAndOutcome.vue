<template>
  <div id="app">
    <Tabs>
      <Tab name="Our Aim" selected="true">
        <div class="content">
          <div><img src="../../assets/governance.png" alt="" /></div>
          <div class="flex-container  flex-center">
            <p class="mobile__text">
              Design innovative and sustainable ecosystem governance mechanisms
              and tools by combining scientifically proven solutions with the
              indigenous ecological and land management practices.
            </p>
          </div>
        </div>
      </Tab>
      <Tab name="Outcome">
        <div class="content">
          <div><img src="../../assets/learning.png" alt="" /></div>
          <div class="outcome flex-container flex-center">
            <p>
              Open an alternative space for learning and research to addressing
              pressing ecosystems governance challenges while simulatneously
              delivering focused solutions for poverty reduction
            </p>
          </div>
        </div>
      </Tab>
    </Tabs>
  </div>
</template>

<script>
import Tab from "@/components/Tabs/Tab.vue";
import Tabs from "@/components/Tabs/Tabs.vue";
export default {
  components: {
    Tab,
    Tabs,
  },
};
</script>

<style lang="scss" scoped>
@media only screen and (max-width: 900px) {
  .content {
    display: block !important;
  }
  .mobile__text {
    font-size: 14px !important;
  }
}
.content {
  display: grid;
  grid-template-columns: 1fr 2fr;
  background: #fff;
  box-shadow: 2px 5px #A65C72; /*#d8c690*/

  img {
    width: 100%;
  }

  p {
    width: 85%;
    margin: auto;
    font-size: 2rem !important;
    padding: 3rem 0;
    line-height: 1.5;
  }
}

th,
td {
  padding: 5px;
  border: 1px solid #fefefe;
  text-align: center;
}
</style>
