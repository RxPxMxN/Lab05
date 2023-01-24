<script setup>
import LikeSad from "./components/LikeSad.vue";
</script>
<template>
  <div class="row">
    <div v-for="n in 6" :key="n" class="col-4">
      <div class="card bg-dark" style="width: 18rem">
        <img
          src="./assets/genshinimpact_nilou_cover.jpg"
          class="card-img-top"
          alt="..."
        />
        <div class="card-body">
          <p class="card-text">
            Nilou
          </p>
        </div>
      </div>
      <LikeSad></LikeSad>
    </div>
  </div>
</template>
