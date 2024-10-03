<template>
  <div>
    <h2 class="text-center repair-title">Repairing services</h2>
  </div>
  <v-container>
    <v-row>
      <v-col v-for="(repair, i) in repairServices" :key="i" cols="12" sm="6" md="3">
        <v-card class="pa-5" elevation="5">
          <v-responsive
            class="icon-container rounded-circle d-flex align-center justify-center"
            max-width="80"
            max-height="80"
          >
            <v-img :src="repair.icon" class="icon-img" alt="Service Icon"></v-img>
          </v-responsive>

          <v-card-title class="font-weight-bold pl-0">
            {{ repair.title }}
          </v-card-title>
          <v-card-text class="pl-0">{{ repair.description }} </v-card-text>
          <v-card-actions>
            <v-btn class="pl-0">More</v-btn>
          </v-card-actions>
        </v-card>
      </v-col>
    </v-row>
  </v-container>
</template>

<script setup>
import image1 from '@/assets/images/1107201.png'
import image2 from '@/assets/images/422315.png'
import image3 from '@/assets/images/5035738.png'
import image4 from '@/assets/images/7315554.png'

const repairServices = [
  {
    icon: image1,
    title: 'Carpentry',
    description:
      'Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt'
  },
  {
    icon: image2,
    title: 'Flooring',
    description:
      'Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt'
  },
  {
    icon: image3,
    title: 'Painting',
    description:
      'Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt'
  },
  {
    icon: image4,
    title: 'Electrical Work',
    description:
      'Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt'
  }
]
</script>
