<template>
  <div>
    <div class="container-fluid">
      <div class="container w-70 d-flex align-items-center flex-column p-5">
        <h2 class="pb-5">Working <em>process</em></h2>
        <div class="icons-wrapper">
          <svg xmlns="http://www.w3.org/2000/svg" width="1095" height="126" viewBox="0 0 1095.3 126"><path d="M2.3 58s70 50.4 177 52c101.5 1.5 145.1-20.7 170-31.8 5.9-2.6 38.9-20.5 38.9-20.5 3.8-2.8 72.7-43.4 159.4-43.7s132.1 29.3 162.3 45.4c0 0 26.6 14.5 36.7 19.3 2.9 1.4 64.7 29.3 169.7 30.3s166-46.3 178-50" fill="none" stroke-width="2" stroke="#f1cfc6"/></svg>
          <div class="lightbulb icon">
            <i class="fa-solid fa-lightbulb"></i>
          </div>
          <div class="message icon">
            <i class="fa-regular fa-comment"></i>
          </div>
          <div class="cloud icon">
            <i class="fa-solid fa-cloud"></i>
          </div>
          <div class="pen icon">
            <i class="fa-solid fa-pencil"></i>
          </div>
        </div>
        <div class="container text-center">
          <div class="row row-cols-4">
            <div class="col">
              <h5>First there's an idea</h5>
              <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Similique necessitatibus suscipit dignissimos autem!</p>
            </div>
            <div class="col">
              <h5>Then we talk about it</h5>
              <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Similique necessitatibus suscipit dignissimos autem!</p>
            </div>
            <div class="col">
              <h5>And we think about it</h5>
              <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Similique necessitatibus suscipit dignissimos autem!</p>
            </div>
            <div class="col">
              <h5>So we draw along</h5>
              <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Similique necessitatibus suscipit dignissimos autem!</p>
            </div>
          </div>
        </div>
      </div>
      <div class="arrow-up">
        <svg xmlns="http://www.w3.org/2000/svg" width="20" height="23"><path fill="#FFF" stroke="#FFF" stroke-width="2" stroke-linecap="round" stroke-miterlimit="10" d="M10 21.5v-19"/><path fill="#FFF" d="M3.926 7.484c-.388-.404-.388-.801 0-1.188L9.419.803c.14-.176.334-.264.58-.264s.44.088.582.264l5.493 5.493c.387.388.387.784 0 1.188-.389.405-.775.396-1.162-.026L9.999 2.599 5.088 7.458c-.388.422-.775.432-1.162.026z"/></svg>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "WorkingProcessComp",
}
</script>

<style lang="scss" scoped>
@import '../assets/style/_vars.scss';
@import '../assets/style/_general.scss';
@import '../assets/style/_utils.scss';

h2{
  font-family: 'Raleway', sans-serif;
  em{
    font-weight: bold;
  }
}
.icons-wrapper{
  max-height: 180px;
}
.icon{
  width: 100px;
  height: 100px;
  border-radius: 50%;
  line-height: 100px;
  background-color: #FAF7F1;
  i{
    font-size: 30px;
    display: flex;
    justify-content: center;
    align-self: center;
    line-height: 100px;
  }
  
}
.lightbulb.icon{
  transform: translate(-20px, -90px);
  color: #BADAC9;
  &:hover{
    transform: translate(-20px, -90px) scale(1.3) rotate(360deg);
    transition: all .5s ease-in;
  }
}

.message.icon{
  transform: translate(300px, -190px);
  color:#F8D12D;
  &:hover{
    transform: translate(300px, -190px) scale(1.3) rotate(360deg);
    transition: all .5s ease-in;
  }
}

.cloud.icon{
  transform: translate(600px, -330px);
  color: #80465F;
  &:hover{
    transform: translate(600px, -330px) scale(1.3) rotate(360deg);
    transition: all .5s ease-in;
  }
}

.pen.icon{
  transform: translate(1000px, -400px);
  color: #EB6950;
  &:hover{
    transform: translate(1000px, -400px) scale(1.3) rotate(360deg);
    transition: all .5s ease-in;
  }
}

.col{
  p{
    color: #A6A6A6
  }
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
  top: 2395px;
  right: 15px;
}
  

</style>