<template>
  <div id="app">
    <reddit-view/>
  </div>
</template>

<script>
import RedditView from './components/RedditView'
export default {
  name: 'app',
  components: {
    RedditView
  } 
}
</script>