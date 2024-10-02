<template>
  <v-app-bar :elevation="0" >
    <v-row>
      <v-col class="d-flex align-center justify-center">
        <img src="../assets/images/default-logo.png" class="logo-bar" alt="Logo" />
      </v-col>

      <v-col class="d-flex justify-center">
        <v-app-bar-nav-icon class="d-md-none"></v-app-bar-nav-icon>
        <div class="d-none d-sm-none d-md-block">
          <v-btn class="font-weight-bold menu_btn" vairant="text" href="https://www.google.com"
            >Home</v-btn
          >
          <v-btn class="font-weight-bold menu_btn" vairant="text" href="https://www.google.com"
            >Team</v-btn
          >
          <v-btn class="font-weight-bold menu_btn" vairant="text" href="https://www.google.com"
            >About Us</v-btn
          >
          <v-btn class="font-weight-bold menu_btn" vairant="text" href="https://www.google.com"
            >Landing</v-btn
          >
        </div>
      </v-col>
    </v-row>
  </v-app-bar>
</template>
