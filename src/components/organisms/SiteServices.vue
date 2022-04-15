<template>
  <div class="siteServices">
    <SiteService
      title="Front-End"
      description="'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus vel cursus metus. Etiam gravida quis nulla quis euismod. Nunc non velit nibh. Etiam congue et neque ac vehicula. Aliquam scelerisque hendrerit mi eget semper. Integer ut dapibus nibh. Pellentesque consequat sapien at laoreet hendrerit. Cras non tellus arcu. Nunc sed sapien sem. Aenean tincidunt tortor nisi, et ultrices justo egestas ac. Nulla quam nulla, hendrerit id posuere id, tincidunt nec odio. Proin eleifend rhoncus augue, laoreet pellentesque arcu iaculis accumsan. Suspendisse varius placerat imperdiet. Nunc lacus orci, lobortis quis nisi in, hendrerit congue nisi.'"
    />
    <SiteService
      title="Back-End"
      description="'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus vel cursus metus. Etiam gravida quis nulla quis euismod. Nunc non velit nibh. Etiam congue et neque ac vehicula. Aliquam scelerisque hendrerit mi eget semper. Integer ut dapibus nibh. Pellentesque consequat sapien at laoreet hendrerit. Cras non tellus arcu. Nunc sed sapien sem. Aenean tincidunt tortor nisi, et ultrices justo egestas ac. Nulla quam nulla, hendrerit id posuere id, tincidunt nec odio. Proin eleifend rhoncus augue, laoreet pellentesque arcu iaculis accumsan. Suspendisse varius placerat imperdiet. Nunc lacus orci, lobortis quis nisi in, hendrerit congue nisi.'"
    />
    <SiteService
      title="Manutenção"
      description="'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus vel cursus metus. Etiam gravida quis nulla quis euismod. Nunc non velit nibh. Etiam congue et neque ac vehicula. Aliquam scelerisque hendrerit mi eget semper. Integer ut dapibus nibh. Pellentesque consequat sapien at laoreet hendrerit. Cras non tellus arcu. Nunc sed sapien sem. Aenean tincidunt tortor nisi, et ultrices justo egestas ac. Nulla quam nulla, hendrerit id posuere id, tincidunt nec odio. Proin eleifend rhoncus augue, laoreet pellentesque arcu iaculis accumsan. Suspendisse varius placerat imperdiet. Nunc lacus orci, lobortis quis nisi in, hendrerit congue nisi.'"
    />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import { SiteService } from '@/components/molecules'

export default defineComponent({
  components: { SiteService }
})
</script>

<style lang="scss" scoped>
.siteServices {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  grid-gap: 5rem;
}
</style>
