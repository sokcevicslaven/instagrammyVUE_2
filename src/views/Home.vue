<template>
  <div class="container">
    <div class="row">
      <div class="col-1"></div>
      <div class="col-7">
        <InstaCard/>
        <InstaCard/>
      </div>
      <div class="col-3">
    <Stories/>
    <Suggestions/>
      </div>
    </div>
  </div>
</template>

<style lang="scss">
  .card-body {
    padding: 0;
  }

  .card {
    margin-bottom: 20px;
  }
</style>

<script>

// @ is an alias to /src
import InstaCard from '@/components/InstaCard.vue'
import Stories from '@/components/Stories.vue'
import Suggestions from '@/components/Suggestions.vue'
export default {
  name: 'home',
  components: {
    InstaCard,
    Stories,
    Suggestions
  }
}
</script>
