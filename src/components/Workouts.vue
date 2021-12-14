<template>
  <section>
    <div class="container">
      <div class="row py-5">
        <div class="col-4">
          <div class="mg_box">

          </div>
        </div>
        <div class="col-4">
          <div class="mg_box">

          </div>
        </div>
        <div class="col-4">
          <div class="mg_box">

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
    }
  }
</style>