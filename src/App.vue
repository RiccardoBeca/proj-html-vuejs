<template>
  <div>
    <HeaderComp />
    <JumboComp />
    <MainComp />
    <FooterComp />
    <div class="svg">
      0
      <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 25 26.1" class="edgtf-butterfly"><path d="M9.4 10.8C9.7 5.3 5.4.5 5.4.5S.7 4.8.4 10.4c-.3 5.6 4 10.3 4 10.3s4.7-4.3 5-9.9z"/><path d="M24.6 21.7s-4.3-4.7-9.9-5c-5.6-.3-10.3 4-10.3 4s4.3 4.7 9.9 5c5.5.3 10.3-4 10.3-4z"/></svg>
      1
      <svg xmlns="http://www.w3.org/2000/svg" width="23" height="23"><circle cx="3" cy="20.1" r="2"/><circle cx="11.7" cy="20.1" r="2"/><circle cx="20.2" cy="20.1" r="2"/><circle cx="3" cy="2.9" r="2"/><circle cx="11.7" cy="2.9" r="2"/><circle cx="20.2" cy="2.9" r="2"/><circle cx="3" cy="11.4" r="2"/><circle cx="11.7" cy="11.4" r="2"/><circle cx="20.2" cy="11.4" r="2"/></svg>
      2
      <svg xmlns="http://www.w3.org/2000/svg" width="20" height="23"><path fill="#FFF" stroke="#FFF" stroke-width="2" stroke-linecap="round" stroke-miterlimit="10" d="M10 21.5v-19"/><path fill="#FFF" d="M3.926 7.484c-.388-.404-.388-.801 0-1.188L9.419.803c.14-.176.334-.264.58-.264s.44.088.582.264l5.493 5.493c.387.388.387.784 0 1.188-.389.405-.775.396-1.162-.026L9.999 2.599 5.088 7.458c-.388.422-.775.432-1.162.026z"/></svg>
      3
      <svg xmlns="http://www.w3.org/2000/svg" width="1095" height="126" viewBox="0 0 1095.3 126"><path d="M2.3 58s70 50.4 177 52c101.5 1.5 145.1-20.7 170-31.8 5.9-2.6 38.9-20.5 38.9-20.5 3.8-2.8 72.7-43.4 159.4-43.7s132.1 29.3 162.3 45.4c0 0 26.6 14.5 36.7 19.3 2.9 1.4 64.7 29.3 169.7 30.3s166-46.3 178-50" fill="none" stroke-width="2" stroke="#f1cfc6"/></svg>
      4
      <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 87 87" style="height:26px" fill="#fff"><path d="M55.4 81.5c6.1-11.1 5.2-16.1-4.3-24.3 6.1-3.5 9.5-8.5 9.1-15.7-.5-8.2-7.7-14.7-16.3-14.6-8.5.1-15.6 6.7-15.9 15-.3 8.5 5.9 15.8 14.3 16.6 1.4.1 2.8.2 4.2.5 5.9 1.2 10.2 6.7 9.8 12.6-.4 6.4-5.5 11.4-11.8 11.7-19.6.9-38.6-14.8-41.3-34C-.1 26.9 14.4 6.8 36.4 2.8c22.3-4 43.4 10 48.1 32 4.3 20-8.6 41.2-28.4 46.7h-.7z"/></svg>
      5
      <svg xmlns="http://www.w3.org/2000/svg" width="32" height="32" style="height:20px" fill="#fff"><path d="M4 15a1 1 0 001 1h19.586l-4.292 4.292a1 1 0 001.414 1.414l6-6a.99.99 0 00.292-.702V15c0-.13-.026-.26-.078-.382a.99.99 0 00-.216-.324l-6-6a1 1 0 00-1.414 1.414L24.586 14H5a1 1 0 00-1 1z"/></svg>
      6
      <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" style="height:16px" fill="#ee2852"><circle cx="9" cy="21" r="2"/><circle cx="20" cy="21" r="2"/><path d="M23.8 5.4c-.2-.3-.5-.4-.8-.4H6.8L6 .8C5.9.3 5.5 0 5 0H1C.4 0 0 .4 0 1s.4 1 1 1h3.2L5 6.2v.1l1.7 8.3C7 16 8.2 17 9.6 17H19.4c1.5 0 2.7-1 3-2.4L24 6.2c0-.3 0-.6-.2-.8z"/></svg>
      7
      <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 87 87" style="height:40px" fill="#ee2852"><path d="M55.4 81.5c6.1-11.1 5.2-16.1-4.3-24.3 6.1-3.5 9.5-8.5 9.1-15.7-.5-8.2-7.7-14.7-16.3-14.6-8.5.1-15.6 6.7-15.9 15-.3 8.5 5.9 15.8 14.3 16.6 1.4.1 2.8.2 4.2.5 5.9 1.2 10.2 6.7 9.8 12.6-.4 6.4-5.5 11.4-11.8 11.7-19.6.9-38.6-14.8-41.3-34C-.1 26.9 14.4 6.8 36.4 2.8c22.3-4 43.4 10 48.1 32 4.3 20-8.6 41.2-28.4 46.7h-.7z"/></svg>
      8
      <svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" width="9" height="9"><image width="9" height="9" xlink:href="data:img/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAkAAAAJCAQAAABKmM6bAAAABGdBTUEAALGPC/xhBQAAACBjSFJNAAB6JgAAgIQAAPoAAACA6AAAdTAAAOpgAAA6mAAAF3CculE8AAAAAmJLR0QAAKqNIzIAAAAJcEhZcwAACxIAAAsSAdLdfvwAAAAHdElNRQfjBhISBAPLk0qYAAAAZ0lEQVQI103OsQnCUACE4S9qmofLWLpDcChXEPcIksoF3CG94ALaBDmLl0j+Kw7urjgxq2TMmBIblWLQag1KE2jcbT1w9F1WN53JpNPvQFzm6uO6rFaso/3s/xOHPHOKkFcq75xr+QPBNi/UsU/OawAAAABJRU5ErkJggg=="/></svg>
    </div>
  </div>
</template>

<script>
import HeaderComp from './components/HeaderComp.vue';
import MainComp from './components/MainComp.vue';
import FooterComp from './components/FooterComp.vue';
import JumboComp from './components/JumboComp.vue';

export default {
  name: 'App',
  components: {
    HeaderComp,
    MainComp,
    FooterComp,
    JumboComp
}
}
</script>

<style lang="scss">
@import './assets/style/_vars.scss';
@import './assets/style/_general.scss';
@import './assets/style/_utils.scss';

.svg{
  background-color: lightgrey;
}
</style>
