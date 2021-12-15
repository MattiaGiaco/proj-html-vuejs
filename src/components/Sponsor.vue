<template>
  <section class="d-flex align-items-center">
    <div class="container">
      <div class="row">
        <div class="col-3">
          <div class="mg_sponsor d-flex flex-column align-items-center">
            <img src="../assets/img/sponsor-1-2x.png" alt="Yoga Studio" width="200px">
            <div class="mg_line"></div>
            <p class="text-center">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Delectus numquam adipisci fuga dolor obcaecati excepturi perspiciatis error ullam deleniti quo.</p>
            <a href="#">Visit Yoga Studio <i class="fas fa-chevron-right"></i></a>
          </div>
        </div>
        <div class="col-3">
          <div class="mg_sponsor d-flex flex-column align-items-center">
            <img src="../assets/img/sponsor-2-2x.png" alt="Fitness Center" width="200px">
            <div class="mg_line"></div>
            <p class="text-center">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Omnis dolorem illum obcaecati ipsam numquam odit porro itaque facilis possimus consectetur!</p>
            <a href="#">Join Fitness center <i class="fas fa-chevron-right"></i></a>
          </div>
        </div>
        <div class="col-3">
          <div class="mg_sponsor d-flex flex-column align-items-center">
            <img src="../assets/img/sponsor-3-2x.png" alt="Fitness Club" width="200px">
            <div class="mg_line"></div>
            <p class="text-center">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Dolore mollitia nulla eos est corporis. Dolorem ullam placeat error facere modi!</p>
            <a href="#">Learn About FC <i class="fas fa-chevron-right"></i></a>
          </div>
        </div>
        <div class="col-3">
          <div class="mg_sponsor d-flex flex-column align-items-center">
            <img src="../assets/img/sponsor-4-2x.png" alt="Power Gym" width="200px">
            <div class="mg_line"></div>
            <p class="text-center">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Ex earum in sapiente nisi atque aut explicabo dolorum cumque eum molestiae?</p>
            <a href="#">Visit Power Gym <i class="fas fa-chevron-right"></i></a>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'Sponsor'
}
</script>

<style lang="scss" scoped>
  section{
    height: 500px;
    color: black;
    .mg_sponsor{
      height: 250px;    
      .mg_line{
        border-color: #4257ef;
      }
      p{
        color: #78787a;
      }
    }
  }
</style>