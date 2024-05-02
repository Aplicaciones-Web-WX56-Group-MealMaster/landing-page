<script>
export default {
  name: "plans.component"
}
</script>

<template>
  <section class="plans">
    <div class="centered-text">
      <h1 class="centered-text">Plans</h1>
      <h1 class="centered-text">Learn about our subscription plans</h1>
    </div>
    <div class="card-container">
      <div class="card">
        <div class="card-content">
          <h1>Free plan</h1>
          <p>Organize and diversify your weekly meals for a specific month</p>
          <p>It doesn't include personal preferences</p>
          <p>No personalized advices</p>
          <p>Without guides and recipes</p>
          <button>Register now</button>
        </div>
        <div class="card-image">
          <img src="../../public/payment-symbol.png" alt="Payment Symbol">
        </div>
      </div>
    </div>
  </section>
</template>

<style scoped>
.plans {
  text-align: center;
  color: black;
  background-image: url('../../public/plan-image.png');
  background-size: cover;
}

.centered-text {
  background-color: white;
  padding: 10px;
}

.card-container {
  display: flex;
  justify-content: space-between;
}

.card {
  flex: 1;
  margin: 20px;
  border: 1px solid #ffffff;
  border-radius: 15px;
  background-color: #ffffff;
}

.card-content button {
  background-color: #263d42;
  color: white;
}

.card-content button:hover {
  background-color: black;
  color: white;
}

.card-content {
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  height: 100%;
}

.card-image img {
  width: 100%;
  border-radius: 15px 15px 0 0;
}
</style>