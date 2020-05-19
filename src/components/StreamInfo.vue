<template>
  <div class="stream-info">
    <h1>{{ msg }}</h1>
    <p>
      Streaming link will be made available here shortly before meetup start:
    </p>
    <div v-if="live">
      <a href="https://www.youtube.com/watch?v=7lWbXLLBw_o" target="_blank" rel="noopener noreferrer">YouTube Live Stream</a>
      <br />
      <a href="https://www.twitch.tv/robchew" target="_blank" rel="noopener noreferrer">Twitch Stream</a>
    </div>
    <div v-else>. . .</div>
  </div>
</template>

<script>
export default {
  name: 'StreamInfo',
  data() {
    return {
      live: false
    }
  }
}
</script>

<style scoped>
a {
  color: #42b883;
}
</style>
