<script>
export default {
  name: "heroimage.component"
}
</script>

<template>
  <section class="heroimage">
    <div class="heroimage-content">
      <h1>Do you have issues planning your weekly foods?</h1>
      <h2>Meal Master takes designing and organizing your diet to another level</h2>
      <button>Register</button>
    </div>
  </section>
</template>

<style scoped>
.heroimage {
  background-image: url('../../public/heroimage.png');
  background-size: cover;
  background-position: center;
  height: 80vh;
  display: flex;
  justify-content: center;
  align-items: center;
}

.heroimage-content {
  text-align: center;
  color: white;
  background-color: rgba(0, 0, 0, 0.3);
  padding: 20px;
  border-radius: 10px;
  width: 50%;
}

.heroimage-content h1 {
  font-size: 2em;
}

.heroimage-content h2 {
  font-size: 1.5em;
  margin-top: 20px;

}

.heroimage-content button {
  padding: 10px 20px;
  font-size: 16px;
  border: none;
  background-color: #7ce577;
  color: black;
  cursor: pointer;
  margin: auto;
}

.heroimage-content button:hover {
  background-color: black;
  color: white;
}
</style>