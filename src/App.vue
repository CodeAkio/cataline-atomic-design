<template>
  <div class="component">
    <Container>
      <p>
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Recusandae
        necessitatibus quam officia neque quia consequuntur quidem saepe
        deleniti. Voluptatibus sunt unde minus tenetur consequatur dolore nulla
        quae obcaecati odit ipsum.
      </p>
    </Container>
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import { Container } from '@/components/bosons'

export default defineComponent({
  name: 'App',
  components: { Container }
})
</script>

<style lang="scss" scoped>
.component {
  margin: 5rem;
}
</style>
