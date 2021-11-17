<template>
  <div class="component">
    <NavItem text="Home" to="/home" />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import { NavItem } from '@/components/atoms'

export default defineComponent({
  name: 'App',
  components: { NavItem }
})
</script>

<style lang="scss" scoped>
.component {
  width: 300px;
}
</style>
