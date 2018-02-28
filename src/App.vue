<template>
  <div id="app" class="container">
    <div class="row">
      <div class="col">
        <router-view/>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style lang="scss">
  $theme-colors: (
    "primary": #4ab3e4,
    "danger": #ff4136
  );

  @import "node_modules/bootstrap/scss/bootstrap";
</style>
