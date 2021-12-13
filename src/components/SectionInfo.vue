<template>
  <section>
    <div class="container position-relative">
      <div class="mg_fusion row justify-content-around">
        <div class="col-4 mg_square mg_bg1">
          <div class="mg_overlay">
            <div class="line"></div>
            <h4>New gym apparel</h4>
            <h6>Look good, feel good</h6>
          </div>
        </div>
        <div class="col-4 mg_square mg_bg2">
          <div class="mg_overlay">
            <div class="line"></div>
            <h4>New gym apparel</h4>
            <h6>Look good, feel good</h6>
          </div>
        </div>
        <div class="col-4 mg_square mg_bg3">
          <div class="mg_overlay">
            <div class="line"></div>
            <h4>New gym apparel</h4>
            <h6>Look good, feel good</h6>
          </div>
        </div>
      </div>
      <div class="quote">
        <p class="text-center">"How you respond to the challenge in the second half will determine what you become after the game, whether you are a winner or a loser."</p>
        <div class="line"></div>
        <div class="author">

        </div>
      </div>
    </div>

  </section>
</template>

<script>
export default {
  name: 'SectionInfo'
}
</script>

<style lang="scss" scoped>
section{
  height: 700px;
  background-image: linear-gradient(150deg, #0219eb 0%,#d5000b 100%);
  .mg_fusion{
    position: absolute;
    width: 100%;
    margin-top: -5%;
    .mg_bg1{
      background-image: url(../assets/img/service6-2x.jpg);
      background-size: cover;
    }
    .mg_bg2{
      background-image: url(../assets/img/box1-2x.jpg);
      background-size: cover;
    }
    .mg_bg3{
      background-image: url(../assets/img/box3-2x.jpg);
      background-size: cover;
    }
    .mg_square{
      width: 30%;
      height: 400px;
      padding: 0;
      border-radius: 4px 4px 40px;
      background-color: brown;
      img{
        width: 100%;
      }
      .mg_overlay{
        width: 100%;
        height: 100%;
        padding-top: 280px;
        padding-left: 30px;
        border-radius: 4px 4px 40px;
        background-color: rgba(100, 100, 100, 0.2);
      }
    }
  }
  .quote{
    width: 60%;
    margin: 0 auto;
    padding-top: 450px;
    p{
      font-size: 32px;
    }
  }
}

</style>