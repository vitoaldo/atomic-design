<template>
  <div class="socialNetworks">
    <SocialLink to="https://twitter.com/" icon="twitter.svg" name="twitter" />
    <SocialLink
      to="https://facebook.com/"
      icon="facebook.svg"
      name="facebook"
    />
    <SocialLink to="https://github.com/" icon="github.svg" name="github" />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import { SocialLink } from '@/components/atoms'
export default defineComponent({
  component: { SocialLink }
})
</script>

<style lang="scss" scoped>
.socialNetworks {
  display: grid;
  grid-gap: 1rem;
}
</style>
