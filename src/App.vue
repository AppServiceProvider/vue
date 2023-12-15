<script setup>
import CommingEvent from './components/CommingEvent.vue'
import TheMembership from './components/TheMembership.vue'
import TheNewsletter from './components/TheNewsletter.vue'
import TheAbout from './components/TheAbout.vue'
import TheFooter from './components/TheFooter.vue'
import TheContract from './components/TheContract.vue'
import TheNav from './components/TheNav.vue'
</script>

<template>
  <main>
    <TheNav />
    <TheAbout />
    <TheNewsletter />
    <TheMembership />
    <CommingEvent />
    <TheContract />
  </main>
  <TheFooter />
</template>