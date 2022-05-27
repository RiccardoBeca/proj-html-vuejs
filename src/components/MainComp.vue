<template>
  
  <div>
    MAIN
    <ImageBlockComp />
    <WorkingProcessComp />
    <WorkWUsComp />
    <BlogComp />

  </div>

</template>

<script>
import ImageBlockComp from './ImageBlockComp.vue';
import WorkingProcessComp from './WorkingProcessComp.vue';
import WorkWUsComp from './WorkWUsComp.vue';
import BlogComp from './BlogComp.vue';

export default {
    name: "MainComp",
    components: { ImageBlockComp, WorkingProcessComp, WorkWUsComp, BlogComp }

  }
</script>

<style lang="scss" scoped>
@import '../assets/style/_vars.scss';
@import '../assets/style/_general.scss';
@import '../assets/style/_utils.scss';
</style>