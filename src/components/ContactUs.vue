<template>
  <v-container>
    <v-row>
      <v-col cols="12" sm="6" md="4" class="d-flex flex-column justify-center">
        <p class="contact-title font-weight-bold text-center mb-5">E-mail</p>
        <p class="contact-description text-center mb-5">
          Email us using our simple form and we'll respond within 10 working days.
        </p>
        <v-text-field
          rounded="0"
          variant="solo"
          label="Enter a valid email adress"
          single-line
        ></v-text-field>
        <v-btn class="contact-btn contact-btn font-weight-bold" rounded="0" height="50"
          >Submit</v-btn
        >
      </v-col>

      <v-col v-for="(contact, i) in contactUs" :key="i" cols="12" sm="6" md="4">
        <div class="d-flex justify-center mb-5 mt-5">
          <v-img :src="contact.icon" max-width="60px" ></v-img>
        </div>
        <p class="contact-title font-weight-bold text-center mb-5">{{ contact.title }}</p>
        <p class="contact-description text-center mb-5">{{ contact.description }}</p>
        <div class="d-flex justify-center">
          <v-btn class="contact-btn font-weight-bold" rounded="0" width="250" height="50">{{
            contact.infoCont
          }}</v-btn>
        </div>
      </v-col>
    </v-row>
  </v-container>
</template>

<script setup>
import whats from '@/assets/images/733585.png'
import liveChat from '@/assets/images/download-chat-white.png'

const contactUs = [
  {
    title: 'Whatsapp Support',
    description: 'Add us on WhatsApp & send queries for instant reply.',
    icon: whats,
    infoCont: '+12+,45+678+89089'
  },
  {
    title: 'Live Chat',
    description: 'The fastest way to get in touch with an Expert for instant reply',
    icon: liveChat,
    infoCont: 'Live Chart'
  }
]
</script>
