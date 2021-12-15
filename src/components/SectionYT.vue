<template>
  <section>
    <div class="mg_container d-flex">
      <div class="mg_video_img d-flex justify-content-center align-items-center">
        <a href="#"><i class="fas fa-play"></i></a>
      </div>
      
      <div class="yt_info">
        <p style="color:#4154fe">Tune up your workouts</p>
        <h3>The best health & fitness advice online</h3>

        <div class="mg_yt_channel my-4 d-flex">
          <img src="../assets/img/unnamed.jpg" alt="Yt logo" width="50px">
          <div class="mx-2">
            <span style="color:#78787a;">ThemeFusion</span>
            <div class="mg_yt mt-2">
              <span><i class="fas fa-play"></i> YouTube</span>
              <span style="color:#78787a;">999+</span>
            </div>
          </div>
        </div>

        <p style="color:#78787a;">Arcu eu facilisi ut quisque placerat nunc habitant. Magna semper mauris, venenatis, leo integer sit pellentesque.</p>
        <button class="mg_btn"><i class="fab fa-youtube"></i> Visit my YouTube channel</button>
      </div>
    </div>

    <div class="mg_playlist container">
      <div class="mg-title d-flex justify-content-between">
        <h5>Featured playlist</h5>
        <a class="mx-5" href="#">View all videos <i class="fas fa-chevron-right"></i></a>
      </div>

      <div class="mg_pl_video">
        <div class="row">
          <div class="col-4">
            <div class="mg_box mg_bg1 d-flex justify-content-center align-items-center">
              <a href="#"><i class="fas fa-play"></i></a>
            </div>
            <div class="text-center my-4">
              <h6>Thighs & glute workout</h6>
              <span>Increase your mobility</span>
            </div>
          </div>
          <div class="col-4">
            <div class="mg_box mg_bg2 d-flex justify-content-center align-items-center">
              <a href="#"><i class="fas fa-play"></i></a>
            </div>
            <div class="text-center my-4">
              <h6>Lift, firm & perk up</h6>
              <span>Feel young again</span>
            </div>
          </div>
          <div class="col-4">
            <div class="mg_box mg_bg3 d-flex justify-content-center align-items-center">
              <a href="#"><i class="fas fa-play"></i></a>
            </div>
            <div class="text-center my-4">
              <h6>Slim & trim your waist</h6> 
              <span>Shed those extra pounds</span>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'SectionYT'
}
</script>

<style lang="scss" scoped>
  section{
    min-height: 1000px;
    color: black;
    .mg_container{
      margin-bottom: 80px;    
      .mg_video_img{
        width: 50%;
        height: 700px;
        background-image: linear-gradient(rgba(0, 0, 0, 0) 0%, rgba(0, 0, 0, 0.3) 100%), url(../assets/img/service15-2x.jpg);
        background-position: center center;
        background-repeat: no-repeat;
        background-size: cover;
        border-radius: 0px 4px 40px 0px;
        margin-top: -50px;
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
      .yt_info{
        width: 50%;
        padding: 100px;
        h3{
          font-size: 45px;
          font-weight: 700;
        }
        button{
          background-color: #ff0000;
          &:hover{
            background-color: #fd5555;
          }
        }
        .mg_yt_channel{
          font-size: 14px;
          .mg_yt{
            
            span:first-child{
              padding: 3px;
              background-color: #ff0000;
              border: 1px solid #bcbcbc;
              color: white;
              border-right: none;
              .fa-play{
                font-size: 8px;
                color: #ff0000;
                background-color: white;
                padding: 3px 5px;
                border-radius: 2px;
              }
            }
            span:last-child{
              padding: 3px;
              border: 1px solid #bcbcbc;
              border-left: none;
            }
          }
        }
      }
    }
    .mg_pl_video{
      margin-bottom: 100px;
        span{
          color: #4257ef;
        }
        .mg_box{
          width: 93%;
          height: 230px;
          margin: 10px 0px;
          border-radius: 0px 4px 30px 0px;
          .fa-play{
            font-size: 10px;
            padding: 20px;
            border-radius: 50%;
            background-color: white;
          }
        }
        .mg_bg1{
          background-image: url(../assets/img/video2-2x.jpg);
          background-size: cover;
        }
        .mg_bg2{
          background-image: url(../assets/img/video7-2x.jpg);
          background-size: cover;
        }
        .mg_bg3{
          background-image: url(../assets/img/video9-2x.jpg);
          background-size: cover;
        }
      }
  }
</style>