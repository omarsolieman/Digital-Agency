<template>
  <div class="relative bg-white pt-16 pb-32 overflow-hidden">
    <feature-item-l class="mt-20">
    </feature-item-l>
    <feature-item-r class="mx-8">
    </feature-item-r>
  </div>
</template>

<script>
import featureItemR from '../components/featureItemR.vue'
import featureItemL from '../components/featureItemL.vue'
export default {
  components: { 
    featureItemR,
    featureItemL,

  },
}
</script>
