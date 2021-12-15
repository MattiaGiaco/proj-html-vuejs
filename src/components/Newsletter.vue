<template>
  <section>
    <div class="mg_ns_info container d-flex flex-column justify-content-center">
      <p style="color:#bc0428;">Join our mailing list today</p>
      <h3 class="fs-1 w-50">Insider offers & flash sales in your inbox every week.</h3>
      <div class="mg_line"></div>
      <div class="my-4">
        <input type="email" placeholder="Insert your email...*">
        <button class="mg_btn">Subscribe</button>
      </div>
      <p style="color:#78787a;" class=" w-50">Curabitur non nulla sit amet nisl tempus convallis quis ac lectus dolor sit amet, consectetur adipiscing elit sed porttitor lectus.</p>
    </div>
  </section>
</template>

<script>
export default {
  name: 'Newsletter'
}
</script>

<style lang="scss" scoped>
  section{
    height: 550px;
    background-image: linear-gradient(90deg, rgb(6, 6, 7) 45%, rgba(6, 6, 7, 0) 75%), url('../assets/img/banner1-2x.jpg');
    background-size: cover;
    .mg_ns_info{
      height: 100%;       
    }
    input{
      width: 400px;
      padding: 7px 10px;
      border-radius: 20px;
      border: none;
    }
    button{
      margin-left: 20px;
      padding: 10px 70px;
      background-color: #4154fe;
    }
  }
</style>