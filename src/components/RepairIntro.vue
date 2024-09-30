<template>
  <div class="repair-container d-flex align-center">
    <div class="image-container">
      <div class="hero-image"></div>
    </div>

    <div>
        <div class="title-container">
          <h1 class="repair-title mb-5">Reliable, Trusted, and Professional Services</h1>
        </div>
      <v-container>
        <v-row>
          <v-col cols="12" md="6">
            <v-checkbox :model-value="true" persistent-hint readonly hide-details>
              <template v-slot:label>
                <div class="checkbox-label font-weight-bold">Office</div>
              </template>
            </v-checkbox>
          </v-col>

          <v-col cols="12" md="6">
            <v-checkbox :model-value="true" persistent-hint readonly hide-details>
              <template v-slot:label>
                <div class="checkbox-label font-weight-bold">Kitchen</div>
              </template>
            </v-checkbox>
          </v-col>

          <v-col>
            <v-checkbox :model-value="true" persistent-hint readonly hide-details>
              <template v-slot:label>
                <div class="checkbox-label font-weight-bold">Living Room</div>
              </template>
            </v-checkbox>
          </v-col>

          <v-col>
            <v-checkbox :model-value="true" persistent-hint readonly hide-details>
              <template v-slot:label>
                <div class="checkbox-label font-weight-bold">Basement</div>
              </template>
            </v-checkbox>
          </v-col>
        </v-row>
        <v-btn class="repair-btn border-thin mt-8" width="250" height="65" elevation="8" size="x-large" rounded="0"
          >Contact Us</v-btn
        >
      </v-container>
    </div>
  </div>
</template>
