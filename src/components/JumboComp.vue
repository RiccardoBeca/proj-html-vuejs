<template>
  <div>
    <div class="container-fluid p-4">
      <div class="container w-70 d-flex justify-content-center p-5">
        <div class="row row-cols-2">
          <div class="col text-wrapper mr-4 p-5">
            <p>Devotion that <br> never <em>ends</em></p>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Magnam, nam eveniet autem natus sint saepe eaque porro facilis? Tenetur, tempora.</p>
            <button>READ MORE</button>
          </div>
        <div class="col img-container d-flex">
          <!-- <img class="" src="../assets/img/h-2-slider-img-12.png" alt="">
          <img class="" src="../assets/img/h-2-slider-img-13.png" alt=""> -->
          <!-- <img class="" src="../assets/img/h-2-slider-img-14.png" alt=""> -->
          <img class="main-img" src="../assets/img/h-2-slider-img-15.png" alt="">
          <img class="main-img" src="../assets/img/h-2-slider-img-16.png" alt="">
          <!-- <img class="" src="../assets/img/h-2-slider-img-17.png" alt=""> -->
          <!-- <img class="" src="../assets/img/" alt="">
          <img class="" src="../assets/img/" alt=""> -->
        </div>
        </div>
       
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "JumboComp",
}
</script>

<style lang="scss" scoped>
@import '../assets/style/_vars.scss';
@import '../assets/style/_general.scss';
@import '../assets/style/_utils.scss';

p:first-child{
  font-family: 'Raleway', sans-serif;
  font-size: 60px;
  line-height: 50px ;
  em{
    font-weight: bold;
  }
}

p:last-of-type{
  color: #A6A6A6;
  margin-right: 100px;
}

.main-img{
  height: 70%;
}




</style>