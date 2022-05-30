<template>
  <div>
    <div class="container w-70">
      <div class="row">
        <div class="col">
          <img src="../assets/img/logo-sidearea-1.png" alt="">
          <p>Let's get creative</p>
        </div>
        <div class="col">
          <span>maree.qode@gmail.com</span>
          <span>+44645 321 789</span>
        </div>
        <div class="col">
          <span>Avenue d'Auderghem 10</span>
          <span>1040 Brussels, Belgium</span>
        </div>
        <div class="col">
          <span>Stay in touch with us</span>
          <i class="fa-brands fa-twitter"></i>
          <i class="fa-brands fa-pinterest-p"></i>
          <i class="fa-brands fa-facebook-f"></i>
          <i class="fa-brands fa-linkedin-in"></i>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "FooterComp",
}
</script>

<style lang="scss" scoped>
@import '../assets/style/_vars.scss';
@import '../assets/style/_general.scss';
@import '../assets/style/_utils.scss';

div{
  background-color: #c0e1cf;
  padding:10px 20px;
  img{
    padding-bottom: 5px;
  }
  span{
    display: block;
  }
  i{
    padding-top: 5px;
    padding-right: 30px;
    cursor: pointer;
  }
}
</style>