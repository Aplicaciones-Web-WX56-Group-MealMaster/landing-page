<script>
export default {
  name: "testimonials.component"
}
</script>

<template>
  <section class="testimonials-content">
    <div class="title-text">
      <h1 class="centered-text">Testimonies</h1>
      <h1 class="centered-text">What do our users say?</h1>
    </div>
    <div class="card-container">
      <div class="card">
        <img src="../../public/Testimony-Img1.png">
        <div class="text-content">
          <p>"MealMaster makes cooking emotional and healthy. It's personalized recipes and advices have changed the way I eat forever."</p>
          <p>- Romina Beer</p>
          <div class="stars">★★★★</div>
        </div>
      </div>
      <div class="card reverse">
        <img src="../../public/Testimony-Img2.png">
        <div class="text-content">
          <p>Thanks to MealMaster, every food is guaranteed to be a hit due to having my preferences match with my necessities.</p>
          <p>- Carlos López</p>
          <div class="stars">★★★★★</div>
        </div>
      </div>
      <div class="card">
        <img src="../../public/Testimony-Img3.png">
        <div class="text-content">
          <p>MealMaster has transformed the way I cook! It's tips and healthy recipes have elevated my culinary skills and wellbeing</p>
          <p>- Andrea Smith</p>
          <div class="stars">★★★★</div>
        </div>
      </div>
    </div>
  </section>
</template>

<style scoped>

.testimonials-content {
  text-align: center;
  color: black;
  background-color: #263d42;

}

.centered-text {
  color: white;
  text-align: center;
}

.card-container {
  display: flex;
  justify-content: space-between;
}

.card {
  flex: 1;
  margin: 20px;
  border: 1px solid #ffffff;
  border-radius: 15px; /* Add this line */
  background-color: #ffffff;
}

.card img {
  width: 100%;
  border-radius: 15px 15px 0 0; /* Add this line */
}

.card.reverse {
  flex-direction: column-reverse;
}

.text-content {
  margin-top: 20px;
}

.stars {
  color: greenyellow;
}
</style>