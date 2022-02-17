<template>
<div>
  <client-only>
    <tip-tap />
  </client-only>
</div>
</template>

<script>
import TipTap from '../components/TipTap.vue'
export default {
  components: { TipTap },
  name: 'IndexPage'
}
</script>
