<template>
  <section>
    <div class="junbo_info container">
      <p>Certified fitness professional</p>
      <h2>Take control of your health</h2>
      <div class="mg_line"></div>
      <p>Curabitur non nulla sit amet nisl tempus convallis quis ac lectus dolor sit amet</p>
      <div>
        <button class="mg_btn">Visit my YouTube channel</button>
        <button class="mg_btn">Buy Avada today <i class="fas fa-long-arrow-alt-right"></i></button>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'Junbotron'
}
</script>

<style lang="scss" scoped>
  section{
    height: 550px;
    background-image: linear-gradient(90deg, rgb(6, 6, 7) 45%, rgba(6, 6, 7, 0) 75%), url('../assets/img/slider82x-scaled.jpg');
    background-size: cover;
    .mg_line{
      content: '\e913';
    }
  }
</style>