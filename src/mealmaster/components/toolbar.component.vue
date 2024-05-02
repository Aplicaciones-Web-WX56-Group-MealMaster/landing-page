<script>
export default {
  name: "toolbar.component"
}
</script>

<template>
  <header class="toolbar">
    <div class="logo">
      <img src="../../public/logo.png">
    </div>
    <div class="navigation">
      <button>About Us</button>
      <button>Testimonials</button>
      <button>Plans</button>
      <button>Login</button>
    </div>
  </header>
</template>

<style scoped>
.toolbar {
  display: flex;
  justify-content: space-between;
  padding: 20px;
  background-color: #263d42;
}

.logo img {
  height: 33px;
}

.navigation button {
  margin-left: 20px;
  padding: 10px 20px;
  font-size: 16px;
  border: none;
  background-color: transparent;
  color: white;
  cursor: pointer;
  border-radius: 20px; /* Add this to make the buttons more oval-shaped */
}

.navigation button:hover {
  background-color: black; /* Change the background color to white on hover */
  color: white; /* Change the text color to black on hover */
}
</style>