<template>
  <div>
    <div>
      <top-bar></top-bar>
      <dashboard-content></dashboard-content>
      <footer-comp></footer-comp>
    </div>
  </div>
</template>

<script>
import TopBar from "../layouts/TopBar.vue";
import FooterComp from "../layouts/FooterComp.vue";
import DashboardContent from "../components/ContentView.vue";

export default {
  components: {
    DashboardContent,
    TopBar,
    FooterComp,
  },

  data() {
    return {};
  },
};
</script>

<style lang="scss">
.v-btn.v-size--large {
  border-radius: 50px !important;
  box-shadow: 0px !important;
  font-size: 1.5rem !important;
  font-weight: 600 !important;
  letter-spacing: 0em !important;
  height: 100px !important;
  // width: 233px !important;
}

.v-application .text-h1 {
  font-size: 54px !important;
  font-weight: 800 !important;
  color: #303532 !important;
}
.v-application .body-1 {
  font-family: 'Raleway' !important;
  font-weight: 600 !important;
}
.v-application .text-h5 {
  font-size: 24px !important;
  font-weight: 600 !important;
  font-family: 'Open_Sans' !important;
  line-height: 32.68px !important;
  color: #939393 ;
}
@media only screen and (max-width: 600px) {
  .v-application .text-h1 {
    font-size: 40px !important;
    font-weight: 700 !important;
    line-height: 3.5rem !important;
  }
}

@media only screen and (max-width: 600px) {
  .v-application .text-h2 {
    font-size: 40px !important;
    font-weight: 700 !important;
    line-height: 3.5rem !important;
  }
}

@media only screen and (max-width: 600px) {
  .fs40 {
    font-size: 20px !important;
    font-weight: 700 !important;
    // line-height: 3.5rem !important;
  }
}

.v-application .text-h4 {
  font-size: 22px !important;
  font-weight: 500 !important;
  font-family: 'Raleway' !important;
  line-height: 33px !important;
  color: #303532 !important;
}
.v-application .text-h6 {
  font-size: 20px !important;
  font-weight: 600 !important;
  font-family: 'Open_Sans' !important;
  line-height: 33px !important;
  // color: #303532 !important;
}
.v-application .text-caption {
  font-size: 40px !important;
  font-weight: 600 !important;
  line-height: 3.25rem !important;
  letter-spacing: 0.0333333333em !important;
  color: #303532 !important;
  
}

.v-application .subtitle-2 {
  font-size: 17px !important;
  font-weight: 500 !important;
  color: #303532 !important;
  font-family: 'Raleway' !important;
}

.fs40 {
  font-size: 40px;
  color: #303532 !important;
  font-weight: 700 !important;
  font-family: 'Raleway' !important;
}

.cardText {
  color: #939393 !important;
  font-weight: 600 !important;
}
.v-card.v-sheet.theme--light.rounded {
  border-radius: 15px !important;
}

.cursor-pointer {
  cursor: pointer;
}

.v-input input {
  max-height: 50px !important;
  // color: red !important;
}

::placeholder {
  font-size: 24px !important;
  font-weight: 500;
  color: #939393 !important;
  font-family: "Open_Sans";
}
.v-text-field--solo > .v-input__control > .v-input__slot {
  align-items: stretch;
  min-height: 100px !important;
  box-shadow: 0px 0px !important;
}

@font-face {
  font-family: "Raleway";
  src: url('../assets/Raleway/static/Raleway-Regular.ttf');
}

@font-face {
  font-family: "Open_Sans";
  src:url('../assets/Open_Sans/static/OpenSans-Regular.ttf');
}

.openSans {
  font-family: "Open_Sans" !important;
}

.raleway {
  font-family: "Raleway" !important;
}

.v-layout {
  flex-direction: column;
}
.gradient-container {
  background: linear-gradient(to bottom left, #ecf5f5, #f8f8f8, #ebf5f5, #f8f8f8);
  padding-left: 100px;
  padding-right: 100px;
}
@media only screen and (max-width: 600px) {
  .gradient-container {
    padding-left: 10px;
    padding-right: 10px;
  }
}
.fs36{
font-size: 36px;
}
.gradient-container2 {
  background: linear-gradient(to bottom left, #f8f8f8, #f1f6f6, #f8f8f8, #f1f6f6);
  padding-left: 100px;
  padding-right: 100px;
  padding-bottom: 120px;
}
@media only screen and (max-width: 600px) {
  .gradient-container2 {
    padding-left: 10px;
    padding-right: 10px;
  }
}

.topRow {
  background-color: #f8f8f8;
  padding-left: 100px;
  padding-right: 100px;
}

@media only screen and (max-width: 600px) {
  .topRow {
    padding-left: 20px;
    padding-right: 10px;
  }
}
.text {
  color: #01b7c4;
}

.bg {
  background-color: #f8f8f8;
}

.navItemBorder {
  border-bottom: 1px solid #01b7c4;
}
.navBarBtn {
  border: 1px solid black;
  border-radius: 50px;
  padding-top: 5px;
  padding-bottom: 5px;
}
.background {
  background-image: url("../assets/Rectangle 1579.svg"), url("../assets/Group.svg");
  background-size: cover;
}
</style>
