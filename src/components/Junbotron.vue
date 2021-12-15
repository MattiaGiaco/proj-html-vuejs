<template>
  <section class=" position-relative">
    <div class="mg_junbo_info container">
      <p style="color:#bc0428">Certified fitness professional</p>
      <h2>Take control of your health</h2>
      <div class="mg_line"></div>
      <p style="color:#78787a">Curabitur non nulla sit amet nisl tempus convallis quis ac lectus dolor sit amet</p>
      <div>
        <button class="mg_btn"><i class="fab fa-youtube"></i> Visit my YouTube channel</button>
        <button class="mg_btn_transparent mx-3">Buy Avada today <i class="fas fa-long-arrow-alt-right"></i></button>
      </div>
    </div>
    <div class="mg_play">
      <a href="#"><i class="fas fa-play"></i></a>
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
    .mg_junbo_info{
      padding-top: 5%;
      h2{
        font-size: 45px;
      }
    }
    .mg_play{
      position: absolute;
      top: 30%;
      right: 20%;
      .fa-play{
        font-size: 20px;
        padding: 40px;
        border-radius: 50%;
        background-color: white;
        transition: all 0.3s;
        &:hover{
          color: #ff0000;
        }
      }
    }
  }
</style>