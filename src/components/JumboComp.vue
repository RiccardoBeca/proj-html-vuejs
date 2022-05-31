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
          <img class="leaf-1" src="../assets/img/h-2-slider-img-12.png" alt="">
          <img class="leaf-2" src="../assets/img/h-2-slider-img-13.png" alt=""> 
          <img class="leaf-3" src="../assets/img/h-2-slider-img-14.png" alt=""> 
          <img class="main-img" src="../assets/img/h-2-slider-img-15.png" alt="">
          <img class="main-img" src="../assets/img/h-2-slider-img-16.png" alt="">
          <img class="leaf-4" src="../assets/img/h-2-slider-img-17.png" alt="">
          <img class="leaf-5" src="../assets/img/short-slider-rev-1-img-2.png" alt="">
          <img class="leaf-6" src="../assets/img/short-slider-rev-1-img-6.png" alt="">
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

button{
  cursor: pointer;
  padding: 15px 30px;
  font-family: "Greta Sans Condensed Bold", "Greta Sans Bold", Arial, sans-serif;
  border-style: none;
  border: 4px solid #f5d8ca;
  background-color: white;
  letter-spacing: 3px;
  font-size: 15px;
  font-weight: bold;
  &:hover{
    transform: scale(1.1);
    transition: all .3s ease-in-out;
  }
}

.leaf-1{
  height: 50px;
  transform: translate(0px,110px);
}
.leaf-2{
  height: 70px;
  transform: translate(10px, 226px);
  
}
.leaf-3{
  height: 50px;
  transform: translate(475px,-56px);
}
.leaf-4{
  height: 100px;
  transform: translate(15px,200px);
}
.leaf-5{
  transform: translate(-580px,-40px);
  height: 50px;
}
.leaf-6{
  height: 50px;
  transform: translate(-125px,25px);
}



</style>