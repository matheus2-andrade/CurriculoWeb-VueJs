<template>
  <div class="social-networks">
      <SocialLink name="GitHub" to="https://github.com/matheus2-andrade" icon="github.svg"/>
      
      <SocialLink name="Linkedin" to="https://www.linkedin.com/in/matheus-andrade-3b9a81197/" icon="linkedin.png"/>

      <SocialLink name="Facebook" to="https://facebook.com" icon="facebook.svg"/>
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import {SocialLink} from '@/components/atoms'

export default defineComponent({
    components: {SocialLink}
})
</script>

<style lang="scss" scoped>
.social-networks {
  display: grid;
  grid-gap: 1rem;
}
</style>