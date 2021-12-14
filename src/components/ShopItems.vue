<template>
  <section>
    <div class="container">
      <div class="mg-title d-flex justify-content-between mb-3">
        <h5>Latest articles</h5>
        <a href="#">Read all articles <i class="fas fa-chevron-right"></i></a>
      </div>

      <div class="mg_pl_video">
        <div class="row">
          <div class="col-4">
            <div class="mg_box mg_bg1"></div>
            <div class="px-3 my-4">
              <h6>The best protein shake</h6>
              <span>By admin | November 26th 2019 | Gym</span>
            </div>
          </div>
          <div class="col-4">
            <div class="mg_box mg_bg2"></div>
            <div class="px-3 my-4">
              <h6>Ultimate cardio workout</h6>
              <span>By admin | November 26th 2019 | Gym</span>
            </div>
          </div>
          <div class="col-4">
            <div class="mg_box mg_bg3"> </div>
            <div class="px-3 my-4">
              <h6>New juices available now</h6> 
              <span>By admin | November 26th 2019 | Gym</span>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'ShopItems'
}
</script>

<style lang="scss" scoped>
  section{
    padding-top: 90px;
    color: black;
      .mg_pl_video{
      margin-bottom: 100px;
        h6{
          font-weight: 700;
        }
        span{
          font-size: 14px;
          color: #78787a;
        }
        .mg_box{
          width: 93%;
          height: 230px;
          margin: 10px 0px;
        }
        .mg_bg1{
          background-image: url(../assets/img/blog1-2x.jpg);
          background-size: cover;
        }
        .mg_bg2{
          background-image: url(../assets/img/blog3-2x.jpg);
          background-size: cover;
        }
        .mg_bg3{
          background-image: url(../assets/img/blog4-2x.jpg);
          background-size: cover;
        }
      }
  }
</style>