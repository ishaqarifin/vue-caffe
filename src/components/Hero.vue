<template>
<div class="row">
  <div class="col justify-content-denter align-self-center">
    <h2><strong>Delicious foods,</strong> <br />Book in your gatged</h2>
    <p>Pilih pesanan anda!!!</p>
    <router-link to="/foods">
      <button class="btn btn-success"><b-icon-arrow-right-circle></b-icon-arrow-right-circle> Pesan</button>
    </router-link>
  </div>
  <div class="col">
    <img src="../assets/foos.png" alt="" width="100%">
  </div>
</div>
</template>
<script>
export default {
  name : "Hero"
}
</script>