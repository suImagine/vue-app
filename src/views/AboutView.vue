<template>
  <div class="about">
    <h1>This is an about page</h1>
  </div>
</template>

<style lang="scss" scoped>
@media (min-width: 900px) {
  $color: #ff0000;
  h1 {
    color: $color;
  }
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
@media (max-width: 900px) {
  $color: orange;
  h1 {
    color: $color;
  }
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style>
