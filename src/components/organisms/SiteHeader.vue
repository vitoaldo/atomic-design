<template>
  <div class="siteHeader">
    <SiteLogo />
    <NavBar />
    <SearchForm />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import { SiteLogo } from '@/components/atoms'
import { NavBar, SearchForm } from '@/components/molecules'
export default defineComponent({
  components: { SiteLogo, NavBar, SearchForm }
})
</script>

<style lang="scss" scoped>
.siteHeader {
  width: 100%;
  display: grid;
  grid-template-columns: 160px repeat(2, auto);
  align-items: center;
  justify-content: space-between;
}
</style>
