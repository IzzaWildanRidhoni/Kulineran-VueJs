<template>
<div class="pesanan-sukses">
  <Navbar/>
  <div class="container">
    <div class="row justify-content-center mt-5">
        <div class="col text-center">
            <img src="../assets/images/menunggu.png" alt="" width="300px">
            <h2><strong>Sukses !!!</strong> </h2>
            <h4>Pesanan Anda Segera Diproses <br> Selamat Menunggu</h4>
             <router-link class="btn btn-success mt-3" to="/">Back To Home</router-link>
        </div>
    </div>
  </div>
</div>
</template>

<script>
import Navbar from "@/components/Navbar.vue";
export default {
    nama:"PesananSukses",
    components:{
        Navbar
    }
}
</script>

<style>

</style>