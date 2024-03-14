<template>
  <div class="services">
    <Service
      title="Front End"
      description="    Lorem ipsum dolor sit amet consectetur adipisicing elit. Ipsam cupiditate ratione dicta ab architecto corrupti molestias voluptatem? Debitis pariatur reprehenderit ut dolor, vitae molestias repellat! Inventore illum cum eligendi facilis!"
    />

    <Service
      title="Back End"
      description="    Lorem ipsum dolor sit amet consectetur adipisicing elit. Ipsam cupiditate ratione dicta ab architecto corrupti molestias voluptatem? Debitis pariatur reprehenderit ut dolor, vitae molestias repellat! Inventore illum cum eligendi facilis!"
    />

    <Service
      title="Manutenção"
      description="    Lorem ipsum dolor sit amet consectetur adipisicing elit. Ipsam cupiditate ratione dicta ab architecto corrupti molestias voluptatem? Debitis pariatur reprehenderit ut dolor, vitae molestias repellat! Inventore illum cum eligendi facilis!"
    />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import { Service } from '@/components/molecules'

export default defineComponent({ components: { Service } })
</script>
<style lang="scss" scoped>
.services {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  grid-gap: 5rem;
}
</style>
