<script setup>
import RepairIntro from '../components/RepairIntro.vue'
import RepairServices from '../components/RepairServices.vue'
import HomeRepairServices from '../components/HomeRepairServices.vue'
import ContactUs from '@/components/ContactUs.vue'
import FooterSection from '../components/FooterSection.vue'
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

  <footer class="footer-section">
    <FooterSection />
  </footer>
</template>
