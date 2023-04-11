<template>
  <div class="min-w-screen min-h-screen bg-gray-50 flex items-center justify-center px-3 py-32">
    <MentionChat></MentionChat>
  </div>
</template>

<script>
import MentionChat from './MentionChat.vue';
export default {
  name: 'HelloWorld',
  components: {
    MentionChat
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
