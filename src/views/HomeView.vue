<template>
  <v-container fluid class="px-0">
    <v-row class="topRow">
      <v-col cols="12" lg="12" md="12" sm="12">
        <v-img src="../assets/image 1.svg"></v-img>
      </v-col>
    </v-row>
    <v-row class="pt-16 topRow">
      <v-col cols="12" lg="8" md="12" sm="12" class="pl-md-16 pr-md-14">
        <text-field
          :placeHolder="`Drug Identification Number`"
          class="ml-md-16"
        ></text-field>
      </v-col>
      <v-col cols="12" lg="2" md="12" sm="12">
        <v-btn
          large
          rounded
          :block="$vuetify.breakpoint.mdAndDown"
          color="#01B7C4"
          class="white--text px-16 mx-auto"
          >Enter</v-btn
        >
      </v-col>
      <v-col cols="12" lg="12" md="12" sm="12">
        <div class="text-center mt-10">
          <p
            class="mt-md-16 text-center font-weight-black ralewayy mb-0 text-h1"
          >
            How can Zimed® PF help?
          </p>
          <img src="../assets/Rectangle 43.svg" alt="" />
        </div>
      </v-col>
    </v-row>

    <v-row class="gradient-container2 py-12">
      <v-col>
        <v-img src="../assets/Group 4635.svg">
          <v-layout row class="pb-8 pt-4">
            <v-flex xs12 md6 lg6 class="pl-4">
              <v-card
                rounded
                class="mt-6 mt-lg-16 ml-md-16 pa-0 pa-md-4 elevation-0"
                width="95%"
              >
                <v-card-text>
                  <p class="openSans text-h5 font-weight-medium cardText">
                    ZIMED® PF's recommended dosage is one drop in the affected
                    eye(s) once daily in the evening.
                  </p>
                </v-card-text>
              </v-card>
              <v-card
                rounded
                class="mt-6 mt-lg-16 ml-md-16 pa-0 pa-md-4 elevation-0"
                width="95%"
              >
                <v-card-text>
                  <p class="openSans text-h5 font-weight-medium cardText">
                    ZIMED® PF is a 100% Preservative - free formula dispensed in
                    a multi-dose bottle.
                  </p>
                </v-card-text>
              </v-card>
              <v-card
                rounded
                class="mt-6 mt-lg-16 ml-md-16 pa-0 pa-md-4 elevation-0"
                width="95%"
              >
                <v-card-text>
                  <p class="openSans text-h5 font-weight-medium cardText">
                    ZIMED® PF is stored between 15 °C and 25 °C, no
                    refrigeration needed.
                  </p>
                </v-card-text>
              </v-card>
            </v-flex>
          </v-layout>
        </v-img>
      </v-col>
    </v-row>
    <v-row class="topRow">
      <v-col cols="12" lg="12" md="12" sm="12">
        <div class="text-center">
          <p class="mt-md-16 font-weight-black openSans mb-0 text-h1">
            How to use Zimed® PF?
          </p>
          <img src="../assets/Rectangle 43.svg" alt="" />
        </div>
      </v-col>
    </v-row>
    <v-row class="gradient-container pt-8 pb-16">
      <v-col cols="12" lg="4" md="12" sm="12">
        <v-card
          rounded
          color="white"
          width="80%"
          height="352"
          class="pa-10 elevation-0"
        >
          <div class="text-center">
            <img src="../assets/Group 4639 (1).svg" />
            <v-card-title class="justify-center font-weight-bold text-h5"
              >Step 1</v-card-title
            >
            <p class="subtitle-2 raleway">
              Before putting a drop in the eye, release the first drop away from
              the eye to check the force needed to get only one drop out of the
              bottle.
            </p>
          </div>
        </v-card>
      </v-col>
      <v-col cols="12" lg="4" md="12" sm="12">
        <v-card
          rounded
          color="transparent"
          width="80%"
          height="352"
          class="pa-10 elevation-0"
        >
          <div class="text-center">
            <img src="../assets/Group 4640.svg" />
            <v-card-title class="justify-center font-weight-bold text-h5"
              >Step 2</v-card-title
            >
            <p class="subtitle-2 raleway">
              Wash your hands. Tilt your head back and look at the ceiling.
            </p>
          </div>
        </v-card>
      </v-col>
      <v-col cols="12" lg="4" md="12" sm="12">
        <v-card
          rounded
          color="transparent"
          width="80%"
          height="352"
          class="pa-10 elevation-0"
        >
          <div class="text-center">
            <img src="../assets/Group 4641.svg" />
            <v-card-title class="justify-center font-weight-bold text-h5"
              >Step 3</v-card-title
            >
            <p class="subtitle-2 raleway">
              Gently pull down the lower eyelid until there is a small pocket.
            </p>
          </div>
        </v-card>
      </v-col>
      <v-col cols="12" lg="4" md="12" sm="12">
        <v-card
          rounded
          color="transparent"
          width="80%"
          height="352"
          class="pa-10 elevation-0"
        >
          <div class="text-center">
            <img src="../assets/Group 4644.svg" />
            <v-card-title class="justify-center font-weight-bold text-h5"
              >Step 4</v-card-title
            >
            <p class="subtitle-2 raleway">
              Turn the bottle upside down and squeeze it to release one drop
              into each eye that needs treatment.
            </p>
          </div>
        </v-card>
      </v-col>
      <v-col cols="12" lg="4" md="12" sm="12">
        <v-card
          rounded
          color="transparent"
          width="80%"
          height="352"
          class="pa-10 elevation-0"
        >
          <div class="text-center">
            <img src="../assets/Group 4643.svg" />
            <v-card-title class="justify-center font-weight-bold text-h5"
              >Step 5</v-card-title
            >
            <p class="subtitle-2 raleway">
              Let go of the lower lid and close your eye for 30 seconds.
            </p>
          </div>
        </v-card>
      </v-col>
      <v-col cols="12" lg="4" md="12" sm="12">
        <v-card
          rounded
          color="transparent"
          width="80%"
          height="352"
          class="pa-10 elevation-0"
        >
          <div class="text-center">
            <img src="../assets/Group 4642.svg" />
            <v-card-title class="justify-center font-weight-bold text-h5"
              >Step 6</v-card-title
            >
            <p class="subtitle-2 raleway">
              Wipe off any excess that runs down the cheek or other skin areas.
            </p>
          </div>
        </v-card>
      </v-col>
    </v-row>
    <v-row style="background-color: #fdfdfd">
      <v-col cols="12" lg="6" md="12" sm="12" class="pt-8">
        <div class="text-center">
          <img src="../assets/Fichier 17@5x 1.svg" />
        </div>
      </v-col>
      <!-- </v-row>
    <v-row> -->
      <v-col cols="12" lg="6" md="12" sm="12" class="pt-16">
        <h1
          class="mt-md-16 font-weight-black openSans mb-0 text-center text-md-left text-h2"
        >
          Storing Zimed® PF
        </h1>
        <p class="mt-16 text-h4 raleway px-8 px-md-0">
          Before putting the cap back on, shake the bottle once in a downwards
          direction, without touching the dropper tip. This is to remove any
          liquid on the tip. To avoid infections and eye injury, do not let the
          tip of the bottle touch your eye or anything else. Put the cap back on
          and close the bottle right after you have used it. Keep the bottle at
          room temperature.
        </p>
      </v-col>
    </v-row>
    <v-row
      style="
        background-color: #f8f8f8;
        padding-top: 100px;
        padding-bottom: 200px;
      "
    >
      <v-col cols="12" lg="6" md="12" sm="12">
        <v-card
          width="66%"
          color="transparent"
          class="mx-auto elevation-0 mt-md-16 pt-md-16"
        >
          <p class="fs40 raleway font-weight-bold">
            For more information, please see the
            <span class="text"> Patient Medication Information </span> or
            contact your Health Care professional.
          </p>
        </v-card>
      </v-col>
      <v-col cols="12" lg="6" md="12" sm="12">
        <h2 class="fs40 raleway font-weight-bold ml-16">
          Dosing & Administration
        </h2>
        <v-card
          rounded
          width="80%"
          class="pa-md-8 pa-2 mt-12 elevation-0 mx-auto mx-md-0"
        >
          <v-list>
            <v-list-item>
              <v-list-item-icon class="pt-12 pt-md-0 mr-2">
                <img src="../assets/Group 4645.svg" />
              </v-list-item-icon>
              <v-list-item-content>
                <p class="text-h6 font-weight-bold openSans ml-md-4 ml-2">
                  The recommended dose is 1 drop in the affected eye(s) once
                  daily in the evening.
                </p>
              </v-list-item-content>
            </v-list-item>
          </v-list>
        </v-card>
        <v-card
          rounded
          width="80%"
          class="pa-md-8 pa-2 mt-6 elevation-0 mx-auto mx-md-0"
        >
          <v-list>
            <v-list-item>
              <v-list-item-icon class="pt-12 pt-md-0 mr-2">
                <img src="../assets/Mask group.svg" />
              </v-list-item-icon>
              <v-list-item-content>
                <p class="text-h6 font-weight-bold openSans ml-md-4 ml-2">
                  The recommended dose is 1 drop in the affected eye(s) once
                  daily in the evening.
                </p>
              </v-list-item-content>
            </v-list-item>
          </v-list>
        </v-card>
        <v-card
          rounded
          width="80%"
          class="pa-md-8 pa-2 mt-6 elevation-0 mx-auto mx-md-0"
        >
          <v-list>
            <v-list-item>
              <v-list-item-icon class="pt-12 pt-md-0 mr-2">
                <img src="../assets/Group 4646.svg" />
              </v-list-item-icon>
              <v-list-item-content>
                <p class="text-h6 font-weight-bold openSans ml-md-4 ml-2">
                  The recommended dose is 1 drop in the affected eye(s) once
                  daily in the evening.
                </p>
              </v-list-item-content>
            </v-list-item>
          </v-list>
        </v-card>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
import TextField from "../components/TextField.vue";
export default {
  name: "HomeView",
  components: {
    TextField,
  },

  data() {
    return {
      requiredRules: [(v) => (!!v && v != undefined ? true : "Required !")],
    };
  },
  methods: {},
  computed: {},
};
</script>

<style>
</style>
