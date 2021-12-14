<template>
  <footer>
    <div class="mg_footer_top container">
      <div class="row align">
        <div class="col-4 text-center">
          <div class="mg_box">
            <img src="" alt="Avada logo">
            <p>Ac aliquam neque sagittis diam faucibus vitae purus turpis phasellus. Pellentesque consectetur amet purus ultrices mauris.</p>
            <div class="mg_social">
              <i class="fab fa-facebook-f"></i>
              <i class="fab fa-twitter"></i>
              <i class="fab fa-youtube"></i>
              <i class="fab fa-instagram"></i>
              <i class="fab fa-linkedin-in"></i>
            </div>
          </div>
        </div>
        <div class="col-4 text-center">
          <h5>RECENT POST</h5>
        </div>
        <div class="col-4 text-center">
          <div class="mg_box">
            <h5>CONTACT INFORMATION</h5>
          </div>
        </div>
      </div>
    </div>
    <div class="mg_copyright d-flex justify-content-center align-items-center">
      <p style="color:#78787a;">© Copyright 2012 - 2021 | Avada Theme by <span>ThemeFusion</span> | All Rights Reserved | Powered by <span>WordPress</span></p>
    </div>
  </footer>
</template>

<script>
export default {
  name: 'Footer',
}
</script>

<style lang="scss" scoped>
  footer{
    height: 600px;
    background-color: rgb(6, 6, 7);
    .mg_footer_top{
      height: 500px;
    }
    .mg_copyright{
      height: 100px;
      border-top: 1px solid #78787a ;
      span{
        color: white;
      }
    }
  }
</style>