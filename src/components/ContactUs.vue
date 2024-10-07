<template>
  <v-container>
    <v-row>
      <v-col cols="12" sm="6" md="4">
        <p>E-mail</p>
        <p>description</p>
        <v-text-field> Input </v-text-field>
        <v-btn>Submit</v-btn>
      </v-col>

      <v-col v-for="(contact, i) in contactUs" :key="i" cols="12" sm="6" md="4">
        <v-img :src="contact.icon" width="50"></v-img>
        <p>{{ contact.title }}</p>
        <p>{{ contact.description }}</p>
        <v-btn>{{ contact.infoCont }}</v-btn>
      </v-col>
    </v-row>
  </v-container>
</template>

<script setup>
import whats from '@/assets/images/733585.png'
import liveChat from '@/assets/images/684849.png'

const contactUs = [
  {
    title: 'Whatsapp Support',
    description: 'Add us on WhatsApp & send queries for instant reply.',
    icon: whats,
    infoCont: '+12+,45+678+89089'
  },
  {
    title: 'Live Chat',
    description: 'The fastest way to get in touch with an Expert',
    icon: liveChat,
    infoCont: 'Live Chart'
  }
]
</script>
