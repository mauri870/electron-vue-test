<template>
  <div class="jumbotron">
    <h1>{{ msg }}</h1>
    <marquee><p>This is a <b>VueJs</b> + <b>Electron</b> app</p><marquee>
  </div>
</template>

<script>
export default {
  data () {
    return {
      // Note: modifying `msg` below will not cause changes to occur with
      // hot-reload. As reloaded components preserve their initial state,
      // modifying these values will have no effect.
      msg: 'Hello World!'
    }
  }
}
</script>
