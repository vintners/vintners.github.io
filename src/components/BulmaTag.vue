<template>
  <div class="tags">
    <a href="#">
      <span class="tag is-primary" v-for="tag in tags" :key="tag">{{tag}}</span>
    </a>
  </div>
</template>

<script>
export default {
  props: {
    tags: Array
  }
};
</script>

<style>

</style>
