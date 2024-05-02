<script>
export default {
  name: "about-us-component",
}
</script>

<template>
  <section class="about-us">
    <h1 class="centered-text">ABOUT US</h1>
    <h1 class="centered-text">The best solution for a good diet</h1>
    <div class="card-container">
      <div class="card">
        <img src="../../public/AboutUsImg-1.png" />
        <div class="text-content">
          <h1>About us?</h1>
          <p>We are a group of Software Engineering students from the Peruvian University of Applied Sciences. MealMaster was born from a problematic related to the poor organization and planning of people's meals.</p>
        </div>
      </div>
      <div class="card reverse">
        <img src="../../public/AboutUsImg-2.png" />
        <div class="text-content">
          <h1>Vision</h1>
          <p>Be the leading platform in organization and planification of meals. Incentivise people to take more healthy and conscient decisions about their alimentation.</p>
        </div>
      </div>
      <div class="card">
        <img src="../../public/AboutUsImg-3.png" />
        <div class="text-content">
          <h1>Mission</h1>
          <p>Bring an easy to use meal planning platform to organize and simplify the process of daily meals, bringing healthy and low-cost options that adapt to people's lifestyle.</p>
        </div>
      </div>
    </div>
  </section>
</template>

<style scoped>
.about-us {
  text-align: center;
  font-family: 'Raleway', sans-serif;
}
.card-container {
  display: flex;
  flex-direction: column;
  align-items: center;
}

.card {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin: 20px;
  flex-basis: 100%;
}

.card.reverse {
  flex-direction: row-reverse;
}

.card img {
  width: 40%;
  height: auto;
  object-fit: cover;
}

.text-content {
  width: 40%;
  padding: 20px;
}
</style>