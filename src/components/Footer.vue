<template>
  <footer>
    <div class="mg_footer_top container d-flex align-items-center">
      <div class="row align">
        <div class="col-4 text-center">
          <div class="mg_box">
            <img src="../assets/img/logo-200x34.png" alt="Avada logo">
            <p class="my-4" style="color:#bcbcbc;">Ac aliquam neque sagittis diam faucibus vitae purus turpis phasellus. Pellentesque consectetur amet purus ultrices mauris.</p>
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
          <ul>
            <li
              v-for="(post, index) in posts"
              :key="index"
            >
              <i class="fas fa-chevron-right"></i>
              <a style="color:white;" href="#"> {{post}}</a>
            </li>
          </ul>
        </div>
        <div class="col-4 text-center">
          <div class="mg_box">
            <h5>CONTACT INFORMATION</h5>
            <p style="color:#bcbcbc;">4746 Tipple Road Michigan 48449</p>
            <span>Mobile : 1.800.000.0000</span>
            <p>Email : info@your-company.com</p>
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
  props: {
    posts: Array
  }
}
</script>

<style lang="scss" scoped>
  footer{
    height: 600px;
    background-color: rgb(6, 6, 7);
    .mg_footer_top{
      height: 500px;
      .mg_social{
        i{
          padding: 10px;
          color: #ec5a57;
        }
      }
      h5{
        padding-bottom: 20px;
      }
      ul{
        line-height: 40px;
        li a:hover{
          text-decoration: underline;
        }
      }
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