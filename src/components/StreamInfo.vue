<template>
  <div class="stream-info">
    <h1>{{ msg }}</h1>
    <p>
      Streaming link will be made available here shortly before meetup start:
    </p>
    <div v-if="live">
      <a href="https://www.youtube.com/watch?v=YFi7-tibK0I" target="_blank" rel="noopener noreferrer">YouTube Live Stream</a>
    </div>
    <div v-else>. . .</div>
  </div>
</template>

<script>
export default {
  name: 'StreamInfo',
  data() {
    return {
      live: true
    }
  }
}
</script>

<style scoped>
a {
  color: #42b883;
}
</style>
