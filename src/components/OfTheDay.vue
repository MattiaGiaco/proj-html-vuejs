<template>
  <section class=" d-flex justify-content-center align-items-center">
    <div class="text-center">
      <a href="#"><i class="fas fa-play my-4"></i></a>
      <h3 class=" fs-1">Crossfit workout of the day</h3>
      <h4 style="color:#fff941;">November 15th, 2019</h4>
      <a href="#">View all videos <i class="fas fa-long-arrow-alt-right"></i></a>
    </div>
  </section>
</template>

<script>
export default {
  name: 'OfTheDay'
}
</script>

<style lang="scss" scoped>
  section{
    height: 600px;
    background-image: linear-gradient(151deg, rgba(6, 25, 231, 0.8) 35%, rgba(206, 1, 18, 0.8) 100%), url('../assets/img/banner14-2x.jpg');
    background-size: cover;
    .fa-play{
      font-size: 20px;
      padding: 40px;
      border-radius: 50%;
      background-color: white;
    }
  }
</style>