<template>
  <div class="component">
    <SocialLink name="Github" to="https://github.com" icon="github.svg" />
    <SocialLink name="Twitter" to="https://twitter.com" icon="twitter.svg" />
    <SocialLink name="Facebook" to="https://facebook.com" icon="facebook.svg" />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import { SocialLink } from '@/components/atoms'

export default defineComponent({
  name: 'App',
  components: { SocialLink }
})
</script>

<style lang="scss" scoped>
.component {
  margin: 5rem;
}
</style>
