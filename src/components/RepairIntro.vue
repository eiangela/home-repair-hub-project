<template>
  <div class="repair-container d-flex flex-column flex-column-reverse flex-md-row align-center">
    <img src="../assets/images/eeee-min.jpg" class="hero-image" alt="" />

    <div class="pa-10 pa-md-2 pb-0">
      <div class="title-container">
        <h1 class="repair-title mb-md-0 font-weight-bold">
          Reliable, Trusted, and Professional Services
        </h1>
      </div>
      <v-container>
        <v-row>
          <v-col
            cols="12"
            sm="6"
            md="12"
            lg="4"
            class="d-sm-flex justify-sm-center justify-md-start align-sm-center pb-md-0 pb-lg-3"
          >
            <v-checkbox :model-value="true" persistent-hint readonly hide-details>
              <template v-slot:label>
                <div class="checkbox-label font-weight-bold">Office</div>
              </template>
            </v-checkbox>
          </v-col>

          <v-col
            cols="12"
            sm="6"
            md="12"
            lg="6"
            class="d-flex justify-sm-center justify-md-start align-sm-center pb-md-0 pb-lg-3"
          >
            <v-checkbox :model-value="true" persistent-hint readonly hide-details>
              <template v-slot:label>
                <div class="checkbox-label font-weight-bold">Kitchen</div>
              </template>
            </v-checkbox>
          </v-col>

          <v-col
            cols="12"
            sm="6"
            md="12"
            lg="4"
            class="d-flex justify-sm-center justify-md-start align-sm-center pb-lg-3 pb-md-0"
          >
            <v-checkbox :model-value="true" persistent-hint readonly hide-details>
              <template v-slot:label>
                <div class="checkbox-label font-weight-bold">Living</div>
              </template>
            </v-checkbox>
          </v-col>

          <v-col
            cols="12"
            sm="6"
            md="12"
            lg="6"
            class="d-flex justify-sm-center justify-md-start align-sm-center pb-md-0 pb-lg-3 mb-md-5"
          >
            <v-checkbox :model-value="true" persistent-hint readonly hide-details>
              <template v-slot:label>
                <div class="checkbox-label font-weight-bold">Basement</div>
              </template>
            </v-checkbox>
          </v-col>
        </v-row>
        <v-col
          class="d-flex justify-sm-center justify-md-start align-sm-center mt-sm-5 pt-md-0 pt-lg-3"
        >
          <v-btn class="repair-btn" elevation="8" rounded="0">Contact Us</v-btn>
        </v-col>
      </v-container>
    </div>
  </div>
</template>
