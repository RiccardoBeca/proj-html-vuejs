<template>
  <div>
    <div class="container-fluid d-flex justify-content-between align-items-center">
      <!-- HEADER LOGO -->
      <div class="logo">
       <img src="../assets/img/logo-sidearea-1.png" alt="Maree Logo">
      </div>
      <!-- NAV MENU -->
      <div class="nav-menu">
        <nav class="d-flex align-self-center">
          <ul>
            <li v-for="(item, index) in menuItem" :key="`nav${index}`">
              <a :class="{'active' :item.isActive}" :href="item.href">{{item.name}}</a>
            </li>
            <li>
              <svg xmlns="http://www.w3.org/2000/svg" width="23" height="23"><circle cx="3" cy="20.1" r="2"/><circle cx="11.7" cy="20.1" r="2"/><circle cx="20.2" cy="20.1" r="2"/><circle cx="3" cy="2.9" r="2"/><circle cx="11.7" cy="2.9" r="2"/><circle cx="20.2" cy="2.9" r="2"/><circle cx="3" cy="11.4" r="2"/><circle cx="11.7" cy="11.4" r="2"/><circle cx="20.2" cy="11.4" r="2"/></svg>
            </li>
          </ul>
        </nav>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "HeaderComp",
 
  data() {
    return {
      menuItem: [
        {
          name: "HOME",
          href: "#",
          isActive: true,
        },
         {
          name: "PAGES",
          href: "#",
          isActive: false,
        },
         {
          name: "PORTFOLIO",
          href: "#",
          isActive: false,
        },
         {
          name: "BLOG",
          href: "#",
          isActive: false,
        },
         {
          name: "SHOP",
          href: "#",
          isActive: false,
        },
         {
          name: "ELEMENTS",
          href: "#",
          isActive: false,
        },
      ]
    }
  },

}
</script>

<style lang="scss" scoped>
@import '../assets/style/_vars.scss';
@import '../assets/style/_general.scss';
@import '../assets/style/_utils.scss';

.logo{
  cursor: pointer;
}

.nav-menu{
  ul{
    list-style: none;
    display: flex;
    margin: 0 !important;
  }
  li{
    cursor: pointer;
    padding: 20px;
  }
  li a{
    text-decoration: none;
    color: black;
    &:hover{
      border-bottom: 3px solid #F3D0C7 ;
    }
    &.active{
      border-bottom: 3px solid #F3D0C7 ;
    }
  } 
}
</style>