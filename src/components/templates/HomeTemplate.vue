<template>
  <SiteContainer class="homeTemplate">
    <SiteHeader />
    <SitePresentation />
    <SiteServices />
  </SiteContainer>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import { SiteContainer } from '@/components/bosons'
import {
  SiteHeader,
  SitePresentation,
  SiteServices
} from '@/components/organisms'
export default defineComponent({
  components: { SiteContainer, SiteHeader, SitePresentation, SiteServices }
})
</script>

<style lang="scss" scoped>
.homeTemplate {
  margin: 5rem auto;
  display: grid;
  grid-gap: 5rem;
}
</style>
