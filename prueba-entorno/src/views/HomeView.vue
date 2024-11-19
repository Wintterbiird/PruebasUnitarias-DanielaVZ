<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <PostsView />
  </div>
</template>

<script>
import PostsView from './PostsView.vue';


export default {
  name: 'HomeView',
  components: {
    PostsView
}
}
</script>
