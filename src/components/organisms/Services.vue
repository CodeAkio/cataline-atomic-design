<template>
  <div class="services">
    <Service
      title="Front End"
      description="Lorem ipsum dolor, sit amet consectetur adipisicing elit. Veniam maxime nesciunt nisi vel, voluptas nulla porro inventore. Reprehenderit, amet quam fugiat, aperiam dignissimos quo rerum qui ipsam repellat sit totam."
    />

    <Service
      title="Back End"
      description="Lorem ipsum dolor, sit amet consectetur adipisicing elit. Veniam maxime nesciunt nisi vel, voluptas nulla porro inventore. Reprehenderit, amet quam fugiat, aperiam dignissimos quo rerum qui ipsam repellat sit totam."
    />

    <Service
      title="Manutenção"
      description="Lorem ipsum dolor, sit amet consectetur adipisicing elit. Veniam maxime nesciunt nisi vel, voluptas nulla porro inventore. Reprehenderit, amet quam fugiat, aperiam dignissimos quo rerum qui ipsam repellat sit totam."
    />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import { Service } from '@/components/molecules'

export default defineComponent({
  components: { Service }
})
</script>

<style lang="scss" scoped>
.services {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  grid-gap: 5rem;
}
</style>
