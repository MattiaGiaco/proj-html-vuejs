<template>
  <section>
    <div class="container">
      <div class="row py-5">
        <div class="col-4">
          <div class="mg_box d-flex flex-column justify-content-center align-items-center text-center">
            <i class="fas fa-running mb-3"></i>
            <h5>Team training</h5>
            <h6>Find a partner</h6>
            <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Dolor delectus repudiandae dignissimos suscipit? Hic praesentium enim fuga perferendis dolor a.</p>
            <a href="#">Find a partner <i class="fas fa-chevron-right"></i></a>
          </div>
        </div>
        <div class="col-4">
          <div class="mg_box d-flex flex-column justify-content-center align-items-center text-center">
              <i class="fas fa-dumbbell mb-3"></i>
              <h5>Crossfit workout</h5>
              <h6>Push your limits</h6>
              <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Dolor  delectus repudiandae dignissimos suscipit? Hic praesentium enim fuga   perferendis dolor a.</p>
              <a href="#">Learn about Crossfit <i class="fas fa-chevron-right"></i></a>
          </div>
        </div>
        <div class="col-4">
          <div class="mg_box d-flex flex-column justify-content-center align-items-center text-center">
            <i class="fas fa-balance-scale-left mb-3"></i>
              <h5>Weight loss plan</h5>
              <h6>Shed those pounds</h6>
              <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Dolor  delectus repudiandae dignissimos suscipit? Hic praesentium enim fuga   perferendis dolor a.</p>
              <a href="#">Schedule a workout <i class="fas fa-chevron-right"></i></a>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'Workouts'
}
</script>

<style lang="scss" scoped>
  section{
    height: 550px;
    background-color: rgb(6, 6, 7);
    .mg_box{
      width: 90%;
      height: 450px;
      border: 3px solid #4257ef;
      border-radius: 5px;
      cursor: pointer;
      transition: all 1s;
      &:hover{
        transform: scale(110%);
      }
      i{
        font-size: 50px;
      }
      h6{
        color: yellow;
      }
      p{
        margin: 40px;
        color: #bcbcbc;
      }
      a{
        color: white;
        .fa-chevron-right{
          font-size: 15px;
        }
      }
    }
  }
</style>