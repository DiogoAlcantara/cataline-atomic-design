<template>
  <Container class="home-template">
    <Header />
    <Presentantion />
    <Services />
  </Container>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import { Container } from '@/components/bosons'
import { Header, Presentantion, Services } from '../organisms'

export default defineComponent({
  components: { Container, Header, Presentantion, Services }
})
</script>
<style lang="scss" scoped>
.home-template {
  margin: 5rem auto;
  display: grid;
  grid-gap: 5rem;
}
</style>
