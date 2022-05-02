<template>
    <div class="jumbotron">
    </div>
</template>

<script>
export default {
  name: 'MyHero',
  props: {
    msg: String
  }
}
</script>

<style scoped lang="scss">
.jumbotron{
    background-color: grey;
    height: 150px;
    position: absolute;
    width: 80%;
    top: 0;
    left: 50%;
    transform: translate(-50%);
    z-index: -1;
    border-radius: 10px;
}
</style>