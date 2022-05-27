<template>


  <div class="img-wrapper">
    <img src="../assets/img/h-2-port-img-1.jpg" alt="imgblock1">
    <img src="../assets/img/h-2-port-img-2.jpg" alt="imgblock2">
    <img src="../assets/img/h-2-port-img-3.jpg" alt="imgblock3">
    <img src="../assets/img/h-2-port-img-4.jpg" alt="imgblock4">
    <img src="../assets/img/h-2-port-img-5.jpg" alt="imgblock5">
    <img src="../assets/img/h-2-port-img-6.jpg" alt="imgblock6">
  </div>
   
  

</template>

<script>
export default {
  name: "ImageBlockComp",
}
</script>

<style lang="scss" scoped>
@import '../assets/style/_vars.scss';
@import '../assets/style/_general.scss';
@import '../assets/style/_utils.scss';

.img-wrapper{
  display: flex;
  flex-wrap: wrap;
  img{
    width: calc(100% / 3);
  }
}
</style>