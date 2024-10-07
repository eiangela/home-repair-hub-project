<script setup>
import RepairIntro from '../components/RepairIntro.vue'
import RepairServices from '../components/RepairServices.vue'
import HomeRepairServices from '../components/HomeRepairServices.vue'
import ContactUs from '@/components/ContactUs.vue'
</script>

<template>
  <section class="repair-intro">
    <RepairIntro />
  </section>

  <section class="repair-services">
    <RepairServices />
  </section>

  <section class="home-repair-services">
    <HomeRepairServices />
  </section>

  <section class="contact-us">
    <ContactUs />
  </section>
</template>
