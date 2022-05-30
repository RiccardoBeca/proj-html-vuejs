<template>
  <div>
    <div class="container w-70 d-flex py-5">
      <div class="row">
        <div class="col">
          <img src="../assets/img/h-2-blog-img-1.jpg" alt="">
          <h4>This way, loves: a detail guide through new design</h4>
          <p><em>By Emily Fields</em></p>
        </div>
        <div class="col">
          <img src="../assets/img/h-2-blog-img-2.jpg" alt="">
          <h4>I try to give people a different way of looking art</h4>
          <p><em>By Emily Fields</em></p>
        </div>
        <div class="col">
          <img src="../assets/img/h-2-blog-img-3.jpg" alt="">
          <h4>Introduce Richard Laperri&eacute;rre of those amazing features</h4>
          <p><em>By Emily Fields</em></p>
        </div>
      </div>      
    </div>
  </div>
</template>

<script>
export default {
  name: "BlogComp",
}
</script>

<style lang="scss" scoped>
@import '../assets/style/_vars.scss';
@import '../assets/style/_general.scss';
@import '../assets/style/_utils.scss';

.row{
  padding: 50px 0px;
}
.col img{
  width: 400px;
}

h4{
  font-size: 20px;
  padding-top: 20px;
}

</style>