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
        <div class="arrow-up">
          <svg xmlns="http://www.w3.org/2000/svg" width="20" height="23"><path fill="#FFF" stroke="#FFF" stroke-width="2" stroke-linecap="round" stroke-miterlimit="10" d="M10 21.5v-19"/><path fill="#FFF" d="M3.926 7.484c-.388-.404-.388-.801 0-1.188L9.419.803c.14-.176.334-.264.58-.264s.44.088.582.264l5.493 5.493c.387.388.387.784 0 1.188-.389.405-.775.396-1.162-.026L9.999 2.599 5.088 7.458c-.388.422-.775.432-1.162.026z"/></svg>
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
.arrow-up{
  display: flex;
  justify-content: center;
  align-items: center;
  background-color: #D8F0E3;
  cursor: pointer;
  padding: 5px;
  height: 36px;
  width: 36px;
  position: absolute;
  top: 2960px;
  right: 15px;
}

</style>