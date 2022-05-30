<template>
  <div class="container-fluid bg">
    <svg id="leaf-1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 25 26.1" class="edgtf-butterfly"><path d="M9.4 10.8C9.7 5.3 5.4.5 5.4.5S.7 4.8.4 10.4c-.3 5.6 4 10.3 4 10.3s4.7-4.3 5-9.9z"/><path d="M24.6 21.7s-4.3-4.7-9.9-5c-5.6-.3-10.3 4-10.3 4s4.3 4.7 9.9 5c5.5.3 10.3-4 10.3-4z"/></svg>
    <svg id="leaf-2" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 25 26.1" class="edgtf-butterfly"><path d="M9.4 10.8C9.7 5.3 5.4.5 5.4.5S.7 4.8.4 10.4c-.3 5.6 4 10.3 4 10.3s4.7-4.3 5-9.9z"/><path d="M24.6 21.7s-4.3-4.7-9.9-5c-5.6-.3-10.3 4-10.3 4s4.3 4.7 9.9 5c5.5.3 10.3-4 10.3-4z"/></svg>
    <img id="cloud" src="../assets/img/short-slider-rev-1-img-5.png" alt="">
    <img id="cloud-2" src="../assets/img/short-slider-rev-1-img-5.png" alt="">
    <img id="cloud-3" src="../assets/img/short-slider-rev-1-img-5.png" alt="">
    <img id="cloud-4" src="../assets/img/short-slider-rev-1-img-5.png" alt="">
    <img id="cloud-5" src="../assets/img/short-slider-rev-1-img-5.png" alt="">

    <div class="container w-70 text-center">
      <h2>Want to work with us? Send us <em>a message!</em></h2>
      <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Dignissimos molestiae totam magni explicabo facilis nesciunt distinctio recusandae molestias adipisci quidem, laudantium, error nihil beatae ullam neque tenetur sunt perspiciatis doloribus dolor reprehenderit? Quisquam, fugit.</p>
      <button>CONTACT</button>
    </div>
  </div>
</template>

<script>
export default {
  name: "MainComp",
}
</script>

<style lang="scss" scoped>
@import '../assets/style/_vars.scss';
@import '../assets/style/_general.scss';
@import '../assets/style/_utils.scss';


.bg{
  background-color: #FAF7F1;
  div{
    padding: 100px;
  }
  overflow: hidden;
}

#leaf-1{
  transform: translate(1681px, 33px) scaleX(-1);
  width: 50px;
  fill: #F3D0C7;
}

#leaf-2{
  transform: translate(200px, 350px);
  width: 50px;
  fill: #F3D0C7;
}

#cloud{
  transform: rotate(180deg) translate(118px);
  width: 200px;
}
#cloud-2{
  transform: rotate(180deg) translate(-1410px,0px);
  width: 200px;
}
#cloud-3{
  transform: rotate(180deg) translate(-1070px, 42px);
  width: 200px;
}
#cloud-4{
  transform: translate(-360px, 420px);
  width: 200px;
}
#cloud-5{
  transform: translate(800px, 370px);
  width: 200px;
}


h2{
  font-size: 50px;
}
em{
  font-weight: bold;
}


// button{
// }
</style>