<template>
  <section>
    <div class="container position-relative">
      <div class="mg_fusion row justify-content-around">
        <div class="col-4 mg_square mg_bg1">
          <div class="mg_overlay">
            <div class="mg_line"></div>
            <h4>New gym apparel</h4>
            <h6>Look good, feel good</h6>
          </div>
        </div>
        <div class="col-4 mg_square mg_bg2">
          <div class="mg_overlay">
            <div class="mg_line"></div>
            <h4>New gym apparel</h4>
            <h6>Look good, feel good</h6>
          </div>
        </div>
        <div class="col-4 mg_square mg_bg3">
          <div class="mg_overlay">
            <div class="mg_line"></div>
            <h4>New gym apparel</h4>
            <h6>Look good, feel good</h6>
          </div>
        </div>
      </div>
      <div class="mg_quote d-flex flex-column align-items-center">
        <p class=" text-center">"How you respond to the challenge in the second half will determine what you become after the game, whether you are a winner or a loser."</p>
        <div class="mg_line"></div>
        <div class="mg_author">
          <img src="../assets/img/avatar-1-2x.jpg" alt="Brad Johnson" class="mx-3">
          <span>Brad Johnson</span>
          <span class="mx-3" style="color:#bcbcbc">Las Vegas</span>
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
  height: 100%;
  padding-bottom: 150px;
  background-image: linear-gradient(150deg, #0219eb 0%,#d5000b 100%);
  .mg_fusion{
    position: absolute;
    width: 100%;
    margin-top: -5%;
    .mg_bg1{
      background-image: linear-gradient(rgba(3, 4, 15, 0) 11%, rgba(3, 4, 15, 0.7) 100%),url(../assets/img/service6-2x.jpg);
      background-size: cover;
    }
    .mg_bg2{
      background-image: linear-gradient(rgba(3, 4, 15, 0) 11%, rgba(3, 4, 15, 0.7) 100%),url(../assets/img/box1-2x.jpg);
      background-size: cover;
    }
    .mg_bg3{
      background-image: linear-gradient(rgba(3, 4, 15, 0) 11%, rgba(3, 4, 15, 0.7) 100%),url(../assets/img/box3-2x.jpg);
      background-size: cover;
    }
    .mg_square{
      width: 30%;
      height: 400px;
      border-radius: 4px 4px 40px;
      cursor: pointer;
      transition: all 0.5s;
      &:hover{
        transform: scale(105%);
        box-shadow: rgb(0 0 0 / 20%) 0px 10px 30px 0px;
      }
      .mg_overlay{
        margin: 70% 20px;
      }
    }
  }
  .mg_quote{
    width: 60%;
    margin: 0 auto;
    padding-top: 450px;
    p{
      font-size: 32px;
    }
    .mg_author{
      img{
        width: 50px;
        border-radius: 50%;
        
      }
    }
  }
}

</style>