<template>


  <div class="img-wrapper">
    <img src="../assets/img/h-2-port-img-1.jpg" alt="imgblock1">
    <!-- <div class="hover-wrapper">
      <div class="info-tag">
        <span>Illustration of novels</span>
        <span>Illustrations</span>
      </div>
    </div> -->
    <img src="../assets/img/h-2-port-img-2.jpg" alt="imgblock2">
    <img src="../assets/img/h-2-port-img-3.jpg" alt="imgblock3">
    <div class="circle-icon">
       <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 87 87" style="height:26px" fill="#fff"><path d="M55.4 81.5c6.1-11.1 5.2-16.1-4.3-24.3 6.1-3.5 9.5-8.5 9.1-15.7-.5-8.2-7.7-14.7-16.3-14.6-8.5.1-15.6 6.7-15.9 15-.3 8.5 5.9 15.8 14.3 16.6 1.4.1 2.8.2 4.2.5 5.9 1.2 10.2 6.7 9.8 12.6-.4 6.4-5.5 11.4-11.8 11.7-19.6.9-38.6-14.8-41.3-34C-.1 26.9 14.4 6.8 36.4 2.8c22.3-4 43.4 10 48.1 32 4.3 20-8.6 41.2-28.4 46.7h-.7z"/></svg>
    </div>
     <div class="shop-icon">
        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" style="height:16px" fill="#ee2852"><circle cx="9" cy="21" r="2"/><circle cx="20" cy="21" r="2"/><path d="M23.8 5.4c-.2-.3-.5-.4-.8-.4H6.8L6 .8C5.9.3 5.5 0 5 0H1C.4 0 0 .4 0 1s.4 1 1 1h3.2L5 6.2v.1l1.7 8.3C7 16 8.2 17 9.6 17H19.4c1.5 0 2.7-1 3-2.4L24 6.2c0-.3 0-.6-.2-.8z"/></svg>
    </div>
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

.hover-wrapper .info-tag{
  display: block;
  padding: 15px;
  background-color: white;
  border: 2px solid black;
  span:first-of-type{
    font-size: 20px;
    font-weight: bold;
    display: block;
  }

}
.hover-wrapper:hover .info-tag{
  display: block;
}


.circle-icon{
  cursor: pointer;
  background-color: #EF2853;
  padding: 5px;
  height: fit-content;
  position: absolute;
  top: 755px;
  right: 0;
}

.shop-icon{
  display: flex;
  justify-content: center;
  align-items: center;
  background-color: white;
  cursor: pointer;
  padding: 5px;
  height: 36px;
  width: 36px;
  position: absolute;
  top: 800px;
  right: 0;
}
</style>