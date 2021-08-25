<template>
  <div class="services">
      <Service title="Front End" description="Experiencia com desenvolvimento em VueJs e NuxtJs Experiencia com desenvolvimento em VueJs
       e NuxtJs Experiencia com desenvolvimento em VueJs e NuxtJs Experiencia com desenvolvimento em VueJs e NuxtJs"/>

      <Service title="Back End" description="Experiencia com desenvolvimento em Node Express e AdonisJs Experiencia com desenvolvimento
       em Node Express e AdonisJs Experiencia com desenvolvimento em Node Express e AdonisJs Experiencia com desenvolvimento em Node Express e AdonisJs"/>

      <Service title="Mobile" description="Experiencia com desenvolvimento em React Native e Flutter Experiencia com desenvolvimento
       em React Native e Flutter Experiencia com desenvolvimento em React Native e Flutter Experiencia com desenvolvimento em React Native e Flutter"/>
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import {Service} from '@/components/molecules'

export default defineComponent({
    components: {Service}
})
</script>

<style lang="scss" scoped>
.services {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  grid-gap: 5rem;
}
</style>