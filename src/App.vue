<template>
  <div class="component">
    <Service
      title="Front End"
      description="Lorem ipsum dolor sit amet consectetur adipisicing elit. Reprehenderit fugit recusandae, possimus quaerat minima aliquid libero iusto nam qui vitae culpa doloribus aspernatur incidunt nemo quae pariatur id, sed architecto."
    />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import { Service } from '@/components/molecules'

export default defineComponent({
  name: 'App',
  components: { Service }
})
</script>

<style lang="scss" scoped>
.component {
  margin: 5rem;
}
</style>
