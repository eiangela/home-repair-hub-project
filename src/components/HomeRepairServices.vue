<template>
  <v-container>
    <div>
      <h3 class="home-repair-title text-center mb-5">Home Repair Services</h3>
    </div>
    <v-row>
      <v-col cols="12" sm="6" md="4" v-for="(home, i) in homeRepairService" :key="i">
        <v-card class="pa-5 home-card" rounded="0" elevation="5">
          <v-card-title class="font-weight-bold text-center home-subtitle">
            <v-img
              :src="home.image"
              alt="Service Image"
              class="mb-10 service-home-image"
              max-height="200px"
              max-width="100%"
              cover
            ></v-img>
            {{ home.title }}
          </v-card-title>
          <v-card-text class="text-center home-description font-italic">{{
            home.description
          }}</v-card-text>
          <v-card-actions class="d-flex justify-center">
            <v-btn variant="tonal" class="font-weight-bold">more</v-btn>
          </v-card-actions>
        </v-card>
      </v-col>
    </v-row>
  </v-container>
</template>

<script setup>
import image1 from '@/assets/images/22.jpg'
import image2 from '@/assets/images/436.jpg'
import image3 from '@/assets/images/erer.jpg'
import image4 from '@/assets/images/422.jpg'
import image5 from '@/assets/images/r3.jpg'
import image6 from '@/assets/images/7883.jpg'
import image7 from '@/assets/images/4562.jpg'
import image8 from '@/assets/images/wrrt.jpg'
import image9 from '@/assets/images/654.jpg'

const homeRepairService = [
  {
    image: image1,
    title: 'Kitchen Repair',
    description:
      'Nulla aliquet enim tortor at. Sed lectus vestibulum mattis ullamcorper velit sed ullamcorper. Massa tincidunt dui ut ornare. Enim sed faucibus.'
  },
  {
    image: image2,
    title: 'Countertop Repair',
    description:
      'Nulla aliquet enim tortor at. Sed lectus vestibulum mattis ullamcorper velit sed ullamcorper. Massa tincidunt dui ut ornare. Enim sed faucibus.'
  },
  {
    image: image3,
    title: 'Painting Repair',
    description:
      'Nulla aliquet enim tortor at. Sed lectus vestibulum mattis ullamcorper velit sed ullamcorper. Massa tincidunt dui ut ornare. Enim sed faucibus.'
  },
  {
    image: image4,
    title: 'Wall Repair',
    description:
      'Nulla aliquet enim tortor at. Sed lectus vestibulum mattis ullamcorper velit sed ullamcorper. Massa tincidunt dui ut ornare. Enim sed faucibus.'
  },
  {
    image: image5,
    title: 'Flooring Repair',
    description:
      'Nulla aliquet enim tortor at. Sed lectus vestibulum mattis ullamcorper velit sed ullamcorper. Massa tincidunt dui ut ornare. Enim sed faucibus.'
  },
  {
    image: image6,
    title: 'Electrical Repair',
    description:
      'Nulla aliquet enim tortor at. Sed lectus vestibulum mattis ullamcorper velit sed ullamcorper. Massa tincidunt dui ut ornare. Enim sed faucibus.'
  },
  {
    image: image7,
    title: 'Plumbing Repair',
    description:
      'Nulla aliquet enim tortor at. Sed lectus vestibulum mattis ullamcorper velit sed ullamcorper. Massa tincidunt dui ut ornare. Enim sed faucibus.'
  },
  {
    image: image8,
    title: 'General Handyman',
    description:
      'Nulla aliquet enim tortor at. Sed lectus vestibulum mattis ullamcorper velit sed ullamcorper. Massa tincidunt dui ut ornare. Enim sed faucibus.'
  },
  {
    image: image9,
    title: 'Cleaning',
    description:
      'Nulla aliquet enim tortor at. Sed lectus vestibulum mattis ullamcorper velit sed ullamcorper. Massa tincidunt dui ut ornare. Enim sed faucibus.'
  }
]
</script>
