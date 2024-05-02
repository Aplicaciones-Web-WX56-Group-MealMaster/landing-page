<script>
export default {
  name: "footer.component"
}
</script>

<template>
  <footer class="footer">
    <div class="social-media">
      <img src="../../public/facebook.png" alt="Facebook">
      <img src="../../public/instagram.png" alt="Twitter">
      <img src="../../public/whatsapp.png" alt="Whatsapp">
      <img src="../../public/tiktok.png" alt="TikTok">
    </div>
    <p>2024. MealMaster All Rights Reserved</p>
  </footer>
</template>

<style scoped>
.footer {
  text-align: center;
  padding: 20px;
  background-color: white;
  color: black;
}

.social-media img {
  width: 30px;
  height: 30px;
  margin: 10px;
}
</style>